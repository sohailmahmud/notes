XCode build failed solved

In my Flutter project, I Also faced with this issue. Please fun below commands on there terminal

If you have fem user 'fvm' before flutter commands

flutter clean
rm -Rf ios/Pods
rm -Rf ios/.symlinks
rm -Rf ios/Flutter/Flutter.framework
rm -Rf ios/Flutter/Flutter.podspec
cd iOS
pod install
cd ..
flutter build ios
