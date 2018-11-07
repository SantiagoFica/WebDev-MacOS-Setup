# WebDev-MacOS-Setup

    
    // Para instalar utilizando Cask
    // *Revisar listado de aplicaciones
       // brew search
    declare -a cask_apps=(
        ‘1password’
        ‘adobe-creative-cloud’
        ‘alfred’
        ‘authy’
        ‘bartender’
        ‘droplr’
        ‘expressvpn’
        ‘flume’
        ‘gitkraken’
        ‘google-backup-and-sync’
        ‘google-chrome’
        ‘iterm2-nightly’
        ‘keepingyouawake’
        ‘postman’
        ‘screenflow’
        ‘sip’
        ‘skype’
        ‘slack’
        ‘sublime-text’
        ‘sequel-pro’
        ‘transmit’
    )

    for app in "${cask_apps[@]}"; do
        brew cask install "$app"
    done
