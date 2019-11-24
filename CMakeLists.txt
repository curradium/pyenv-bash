cmake_minimum_required(VERSION 3.10.2)
project(pyenv-bash)

install(PROGRAMS
  pyenv-bash.sh
  DESTINATION /etc/profile.d
)
