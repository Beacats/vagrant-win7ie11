Vagrant.configure("2") do |config|

  # VirtualBox
  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    vb.memory = "2048"
  end

  # Vagrant Box Name
  config.vm.box = "win7ie11"

  # Guest OS
  config.vm.guest = "windows"

  # User Name
  config.ssh.username = "IEUser"

  # Password
  config.ssh.password = "Passw0rd!"

  # SSH Off
  config.ssh.insert_key = false

  # SSH Login Shell
  config.ssh.shell = 'sh -l'

  # Windows No Sudo
  config.ssh.sudo_command = ''

  # Shared Folder
  config.vm.synced_folder ".", "/vagrant", disabled: true
  # Shared Folder Example
  # config.vm.synced_folder "./vagrant", "c:\\vagrant"

end