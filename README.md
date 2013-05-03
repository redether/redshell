redshell
========
 * shell extensions for power users
 * mod - modules - extend functionality
  * env - environment
  * fs - filesystem
  * mvn - maven build system
  * net - network utilities
  * note - notes
  * proc - process management
  * sft - software installation
  * src - source control management
  * tom - tomcat application server
 * etc - configuration declarative configuration of the modules
  * env - environment declaration
  * history - manipulate local history
  * net - networking configuration
  * prompt - prompt customization
  * sft - declarative software installation
  * src - declarative source 

install
=======
 * $ cp dot-redshell ${HOME}/.redshell
 * $ cp ~/.bashrc ~/.bashrc_`date +%Y%m%d_%H%M%S`
 * $ printf "# install redshell\n[ -f \"%s\" ] && source \"%s\"\n" "${HOME}/.redshell" "${HOME}/.redshell" >> ~/.bashrc 2>&1
