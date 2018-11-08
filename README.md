# WebDev-MacOS-Setup


// Para instalar utilizando Cask
// *Revisar listado de aplicaciones
   // brew search
       
       
    declare -a cask_apps=(
        ‘visual-studio-code’
        ‘atom’
        ‘sublime-text’
        ‘flux’
        ‘alfred’
        ‘authy’
        ‘bartender’
        ‘droplr’
        ‘expressvpn’
        ‘flume’
        ‘gitkraken’
        ‘google-backup-and-sync’
        ‘google-chrome’
        ‘firefox’
        ‘iterm2-nightly’
        ‘keepingyouawake’
        ‘postman’
        ‘screenflow’
        ‘sip’
        ‘skype’
        ‘slack’
        ‘sequel-pro’
        ‘transmit’
        ‘spotify’
    )

    for app in "${cask_apps[@]}"; do
        brew cask install "$app"
    done
