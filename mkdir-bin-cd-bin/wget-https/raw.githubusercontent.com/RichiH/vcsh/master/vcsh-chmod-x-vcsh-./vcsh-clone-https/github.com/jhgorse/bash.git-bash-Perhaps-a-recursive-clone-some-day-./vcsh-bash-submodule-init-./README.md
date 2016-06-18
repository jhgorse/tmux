# tmux

mkdir bin && cd bin/
wget https://raw.githubusercontent.com/RichiH/vcsh/master/vcsh
chmod +x vcsh
./vcsh clone https://github.com/jhgorse/tmux.git bash # Perhaps a recursive clone some day
./vcsh enter tmux
git submodule init
git submodule update
# ./vcsh bash submodule init
# ./vcsh bash submodule update
