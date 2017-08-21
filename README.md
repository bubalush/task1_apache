# task1_apache LOG

-----> Starting Kitchen (v1.17.0)
-----> Cleaning up any prior instances of <default-centos-73>
-----> Destroying <default-centos-73>...
       Finished destroying <default-centos-73> (0m0.00s).
-----> Testing <default-centos-73>
-----> Creating <default-centos-73>...
       /opt/chefdk/embedded/lib/ruby/gems/2.4.0/gems/mixlib-shellout-2.3.2/lib/mixlib/shellout/unix.rb:340: warning: Insecure world writable dir /home/student/maven in PATH, mode 040777
       /opt/chefdk/embedded/lib/ruby/gems/2.4.0/gems/mixlib-shellout-2.3.2/lib/mixlib/shellout/unix.rb:340: warning: Insecure world writable dir /home/student/maven in PATH, mode 040777
       /opt/vagrant/embedded/gems/gems/vagrant-1.9.5/lib/vagrant/util/platform.rb:25: warning: Insecure world writable dir /home/student/maven in PATH, mode 040777
       Bringing machine 'default' up with 'virtualbox' provider...
       ==> default: Importing base box 'sbeliakou/centos-7.3-x86_64-minimal'...
       
[KProgress: 10%
[KProgress: 30%
[KProgress: 50%
[KProgress: 70%
[KProgress: 80%
[KProgress: 90%
[K==> default: Matching MAC address for NAT networking...
       ==> default: Checking if box 'sbeliakou/centos-7.3-x86_64-minimal' is up to date...
       ==> default: Setting the name of the VM: kitchen-task1_apache-default-centos-73_default_1503328165295_99582
       ==> default: Clearing any previously set network interfaces...
       ==> default: Preparing network interfaces based on configuration...
           default: Adapter 1: nat
           default: Adapter 2: hostonly
       ==> default: Forwarding ports...
           default: 80 (guest) => 8080 (host) (adapter 1)
           default: 22 (guest) => 2222 (host) (adapter 1)
       ==> default: Booting VM...
       ==> default: Waiting for machine to boot. This may take a few minutes...
           default: SSH address: 127.0.0.1:2222
           default: SSH username: vagrant
           default: SSH auth method: private key
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: Warning: Connection reset. Retrying...
           default: Warning: Remote connection disconnect. Retrying...
           default: 
           default: Vagrant insecure key detected. Vagrant will automatically replace
           default: this with a newly generated keypair for better security.
           default: 
           default: Inserting generated public key within guest...
           default: Removing insecure key from the guest if it's present...
           default: Key inserted! Disconnecting and reconnecting using new SSH key...
       ==> default: Machine booted and ready!
       ==> default: Checking for guest additions in VM...
       ==> default: Setting hostname...
       ==> default: Configuring and enabling network interfaces...
           default: SSH address: 127.0.0.1:2222
           default: SSH username: vagrant
           default: SSH auth method: private key
       ==> default: Machine not provisioned because `--no-provision` is specified.
       [SSH] Established
       Vagrant instance <default-centos-73> created.
       Finished creating <default-centos-73> (1m28.89s).
-----> Converging <default-centos-73>...
       Preparing files for transfer
       Preparing dna.json
       Resolving cookbook dependencies with Berkshelf 6.3.0...
       Removing non-cookbook files before transfer
       Preparing validation.pem
       Preparing client.rb
-----> Installing Chef Omnibus (install only if missing)
       Downloading https://omnitruck.chef.io/install.sh to file /tmp/install.sh
       Trying wget...
       Download complete.
       el 7 x86_64
       Getting information for chef stable  for el...
       downloading https://omnitruck.chef.io/stable/chef/metadata?v=&p=el&pv=7&m=x86_64
         to file /tmp/install.sh.10561/metadata.txt
       trying wget...
       sha1	d3d26412b6304c92f72749d00e62e0191ceada05
       sha256	fe051b504856a74ccce1fd23ff92c296506cb8292a3933c71069ae915e7a4a00
       url	https://packages.chef.io/files/stable/chef/13.3.42/el/7/chef-13.3.42-1.el7.x86_64.rpm
       version	13.3.42
       downloaded metadata file looks valid...
       downloading https://packages.chef.io/files/stable/chef/13.3.42/el/7/chef-13.3.42-1.el7.x86_64.rpm
         to file /tmp/install.sh.10561/chef-13.3.42-1.el7.x86_64.rpm
       trying wget...
       Comparing checksum with sha256sum...
       
       WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING
       
       You are installing an omnibus package without a version pin.  If you are installing
       on production servers via an automated process this is DANGEROUS and you will
       be upgraded without warning on new releases, even to new major releases.
       Letting the version float is only appropriate in desktop, test, development or
       CI/CD environments.
       
       WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING
       
       Installing chef 
       installing with rpm...
       warning: /tmp/install.sh.10561/chef-13.3.42-1.el7.x86_64.rpm: Header V4 DSA/SHA1 Signature, key ID 83ef826a: NOKEY
       Preparing...                                                            (100%)#                                 (100%)##                                (100%)###                               (100%)####                              (100%)#####                             (100%)######                            (100%)#######                           (100%)########                          (100%)#########                         (100%)##########                        (100%)###########                       (100%)############                      (100%)#############                     (100%)##############                    (100%)###############                   (100%)################                  (100%)#################                 (100%)##################                (100%)###################               (100%)####################              (100%)#####################             (100%)######################            (100%)#######################           (100%)########################          (100%)#########################         (100%)##########################        (100%)###########################       (100%)############################      (100%)#############################     (100%)##############################    (100%)###############################   (100%)################################  (100%)################################# (100%)################################# [100%]
       Updating / installing...
          1:chef-13.3.42-1.el7                                                 (  1%)#                                 (  4%)##                                (  7%)###                               ( 10%)####                              ( 13%)#####                             ( 16%)######                            ( 19%)#######                           ( 22%)########                          ( 25%)#########                         ( 28%)##########                        ( 31%)###########                       ( 34%)############                      ( 37%)#############                     ( 40%)##############                    ( 43%)###############                   ( 46%)################                  ( 49%)#################                 ( 52%)##################                ( 54%)###################               ( 57%)####################              ( 60%)#####################             ( 63%)######################            ( 66%)#######################           ( 69%)########################          ( 72%)#########################         ( 75%)##########################        ( 78%)###########################       ( 81%)############################      ( 84%)#############################     ( 87%)##############################    ( 90%)###############################   ( 93%)################################  ( 96%)################################# ( 99%)################################# [100%]
       Thank you for installing Chef!
       Transferring files to <default-centos-73>
       Starting Chef Client, version 13.3.42
       Creating a new client identity for default-centos-73 using the validator key.
       resolving cookbooks for run list: ["task1_apache::default"]
       Synchronizing Cookbooks:
         - task1_apache (0.1.0)
       Installing Cookbook Gems:
       Compiling Cookbooks...
       Converging 3 resources
       Recipe: task1_apache::default
         * yum_package[httpd, php, php-fpm] action install
           - install version 2.4.6-45.el7.centos.4 of package httpd
           - install version 5.4.16-42.el7 of package php
           - install version 5.4.16-42.el7 of package php-fpm
         * template[/var/www/html/info.php] action create
           - create new file /var/www/html/info.php
           - update content in file /var/www/html/info.php from none to 075368
           --- /var/www/html/info.php	2017-08-21 16:14:02.824190585 +0100
           +++ /var/www/html/.chef-info20170821-12067-17hgv3m.php	2017-08-21 16:14:02.824190585 +0100
           @@ -1 +1,2 @@
           +<?php phpinfo(); ?>
           - change mode from '' to '0644'
           - change owner from '' to 'root'
           - change group from '' to 'root'
         * service[httpd] action enable
           - enable service service[httpd]
         * service[httpd] action start
           - start service service[httpd]
         * service[httpd] action restart
           - restart service service[httpd]
       
       Running handlers:
       Running handlers complete
       Chef Client finished, 5/5 resources updated in 58 seconds
       Finished converging <default-centos-73> (3m36.67s).
-----> Setting up <default-centos-73>...
       Finished setting up <default-centos-73> (0m0.00s).
-----> Verifying <default-centos-73>...
       Loaded tests from test/smoke/default 

Profile: tests from test/smoke/default
Version: (not specified)
Target:  ssh://vagrant@127.0.0.1:2222


  System Package
[38;5;41m     ✔  httpd should be installed[0m
  Service httpd
[38;5;41m     ✔  should be enabled[0m
[38;5;41m     ✔  should be running[0m
  File /var/www/html/info.php
[38;5;41m     ✔  should be file[0m
  http GET
[38;5;41m     ✔  on http://localhost:8080/info.php status should eq 200[0m

Test Summary: [38;5;41m5 successful[0m, [38;5;9m0 failures[0m, [38;5;247m0 skipped[0m
       Finished verifying <default-centos-73> (0m2.02s).
-----> Destroying <default-centos-73>...
       /opt/chefdk/embedded/lib/ruby/gems/2.4.0/gems/mixlib-shellout-2.3.2/lib/mixlib/shellout/unix.rb:340: warning: Insecure world writable dir /home/student/maven in PATH, mode 040777
       /opt/vagrant/embedded/gems/gems/vagrant-1.9.5/lib/vagrant/util/platform.rb:25: warning: Insecure world writable dir /home/student/maven in PATH, mode 040777
       ==> default: Forcing shutdown of VM...
       ==> default: Destroying VM and associated drives...
       Vagrant instance <default-centos-73> destroyed.
       Finished destroying <default-centos-73> (0m4.00s).
       Finished testing <default-centos-73> (5m11.59s).
-----> Kitchen is finished. (5m12.98s)


