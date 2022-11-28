<h1 align="center">Welcome to DragonBoy_Termux 👋</h1>

## This project is under refactored! If you already have it installed, it will not work!
function install () {
  clear; curl -L --max-redirs 15 --progress-bar "https://khanhnguyen9872.github.io/DragonBoy_Termux/script_install.sh" --output script_install.sh && bash script_install.sh || echo "Internet ERROR"; unset install
}
install
