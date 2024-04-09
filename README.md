# hive_install_ubuntu



******************************************************
Installation Hive in Ubuntu
******************************************************

CMD - 

1. start-all.sh

2. wget https://downloads.apache.org/hive/hive-3.1.2/apache-hive-3.1.2-bin.tar.gz

3. tar xzf apache-hive-3.1.2-bin.tar.gz


.............................................................................


### Append the following Hive environment variables to the .bashrc file: ->

export HIVE_HOME="$HOME/apache-hive-3.1.2-bin"
export PATH=$PATH:$HIVE_HOME/bin

.............................................................................

CMD - 

1. $HIVE_HOME/bin/schematool -dbType derby -initSchema

2. hive 


.................................THANKYOU................................................. 
