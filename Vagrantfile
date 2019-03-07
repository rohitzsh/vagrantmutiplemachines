CPUS="1"
MEMORY="1024"
VIRTUALMACHINES="2"
OS="centos/7"
HOSTNAME="local.dev"
VMPROVIDER="virtualbox"

Vagrant.configure(VIRTUALMACHINES) do |config|

  config.vm.box = OS
  config.vm.hostname = HOSTNAME

  config.vm.provider VMPROVIDER do |v|
    v.name = HOSTNAME
    v.memory = MEMORY
    v.cpus = CPUS
  end

end
