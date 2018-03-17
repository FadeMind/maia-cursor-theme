cmake_minimum_required(VERSION 3.10)

set(ICON_INSTALL_DIR /usr/share/icons)
project(maia-cursor-theme)
install(DIRECTORY Maia/cursors DESTINATION ${ICON_INSTALL_DIR}/maia_cursors)
install(FILES Maia/index.theme DESTINATION ${ICON_INSTALL_DIR}/maia_cursors)
