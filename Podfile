source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!

#This shared pod generate a global `Pods/Target Support Files/Pods/Pods.debug.xcconfig` file which are erased by target configs
# using #import in those target configs file does not work
#pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'tvOS'

#Pods for tvOS only
target :tvos_target do
    
    platform :tvos, '9.0'
    
    pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'tvOS'
end

#Pods for iOS only
target :ios_target do

    platform :ios, '9.0'

    pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'tvOS'
end

