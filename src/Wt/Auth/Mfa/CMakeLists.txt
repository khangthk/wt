file(GLOB AUTH_MFA_H_FILES RELATIVE "${CMAKE_CURRENT_SOURCE_DIR}" "*.h")
install(FILES ${AUTH_MFA_H_FILES} DESTINATION include/Wt/Auth/Mfa)
