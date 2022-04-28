
# iOS Developer Backpack

a bunch of cool shoutcuts for iOS developers


[**Homebrew**](http://brew.sh/)

#### uninstall brew 
```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall.sh)"
```

####  methods
```bash
  brew list
  brew list --cask
  brew search <name>
  brew update 
  brew upgrade
  brew uninstall "PACKAGE_NAME"
  brew cleanup                   ---> remove old versions
  brew search --casks brave      ---> brave-browser
```

#### install packages
```bash
  brew install sonar-scanner
  brew install --cask firefox
  brew install --cask google-chrome
  brew install --cask postman
  brew install --cask visual-studio-code
  brew install --cask iterm2
  brew install --cask sourcetree
  brew install quicktype
```

[**Cocoapods**](https://guides.cocoapods.org/using/getting-started.html#installation)

```bash
  sudo gem install cocoapods && pod setup
  pod install 
  pod update "POD_NAME"
  pod update
  pod repo update
  pod install --no-repo-update
  pod deintegrate
```

#### Pod List
  pod 'lottie-ios'
  pod 'Firebase/Analytics'
  pod 'Firebase/Core'
  pod 'Firebase/RemoteConfig' 
  pod 'Firebase/Crashlytics' 
  pod 'openssl-ios-bitcode'
  pod 'GoogleTagManager'
  pod 'Adjust'
  pod "Realm"
  pod 'Moya'
  pod "PromiseKit"
  pod 'SnapKit'
  pod 'SwiftLint'

[**iterm2**](https://lobster1234.github.io/2017/04/08/setting-up-fish-and-iterm2/)
```bash
  fish
  bash install.sh
```

#### SourceTree Auth Clean
```bash
~/Library/Application Support/SourceTree
```
### Git (source control)
* [**Swift**](https://github.com/github/gitignore/blob/master/Swift.gitignore):star: .gitignore list  
* [**Xcode**](https://github.com/github/gitignore/blob/master/Global/Xcode.gitignore) .gitignore list  
* [**OSX**](https://github.com/github/gitignore/blob/master/Global/OSX.gitignore) .gitignore list  

### Continuous Integration (CI) 
* [**Jenkins app**](https://github.com/stisti/jenkins-app) open source ci  
	* [**CocoaPods Plugin**](https://wiki.jenkins-ci.org/display/JENKINS/CocoaPods+Plugin) This plugin provides a build step for projects which use CocoaPods.
	* [**Xcode+Plugin**](https://wiki.jenkins-ci.org/display/JENKINS/Xcode+Plugin) adds the ability to call Xcode command line tools to automate build and packaging iOS applications

### License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)  

