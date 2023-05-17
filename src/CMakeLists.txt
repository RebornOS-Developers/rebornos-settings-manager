add_subdirectory(libmsm)
add_subdirectory(modules)
add_subdirectory(msm)
add_subdirectory(notifier)

install(FILES rebornos-category.desktop DESTINATION  ${KDE_INSTALL_DATADIR}/systemsettings/categories)
