include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = DontKillMyMusic
DontKillMyMusic_FILES = DKMRootListController.m
DontKillMyMusic_INSTALL_PATH = /Library/PreferenceBundles
DontKillMyMusic_FRAMEWORKS = UIKit
DontKillMyMusic_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/DontKillMyMusic.plist$(ECHO_END)
