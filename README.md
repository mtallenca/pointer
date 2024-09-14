# PlatformView crash in beta

Sample repo with a TextField in a dialog, TextField wrapped in a PointerInterceptor.

with Flutter beta 3.26.0-0.1.pre, run this app in debug mode on an older iOS device that is capped at iOS 16 (ipad mini, iPad Pro 9.7, iPhone 6s, etc. 

Open and close the dialog a few times. The app will crash in BringLayersIntoView (platform_views_controller.mm) 
