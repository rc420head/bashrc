# bashrc

export FUN_BUILDTYPE=OFFICIAL

export PATH=~/bin:$PATH

export USE_CCACHE=1

alias tb10="sb && mc && b10"

alias tbg4="sb && mc && bh811"

alias gra="git remote add"

alias grv="git remote -v"

alias gs="git status"

alias gco="git checkout"

alias gcpc="gcp --continue"

alias glo="git log --oneline"

alias gcp="git cherry-pick"

alias sb=". build/envsetup.sh"

alias b10="time brunch pme userdebug -j8"

alias bh811="time brunch h811 userdebug -j8"

alias l10="lunch fun_pme-userdebug"

alias lh811="lunch fun_h811-userdebug"

alias mc="make clobber"

alias bapps="make Settings && make framework-res && make SystemUI"

alias rsfs="time repo sync --force-sync"
