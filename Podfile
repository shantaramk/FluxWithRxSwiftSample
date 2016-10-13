source 'https://github.com/CocoaPods/Specs.git'
use_frameworks!

target 'FluxWithRxSwiftSample' do
    platform :ios, '9.0'

    pod 'Kingfisher', '3.1.1'
    pod 'Cartography', '1.0.0'
    pod 'SwiftDate', '~> 4.0.1'
    pod 'SpringIndicator', '1.4.1'
    pod 'NavigationNotice', '1.2.1'
    
    ## Network
    pod 'APIKit', :git => 'git@github.com:ishkawa/APIKit.git', :tag => '3.0.0-beta.2'
    pod 'Himotoki', :git => 'git@github.com:ikesyo/Himotoki.git', :tag => '3.0.0'
    
    ## Reactive
    pod 'RxSwift', :git => 'git@github.com:ReactiveX/RxSwift.git', :tag => '3.0.0-beta.2'
    pod 'RxCocoa', :git => 'git@github.com:ReactiveX/RxSwift.git', :tag => '3.0.0-beta.2'
    

    target 'FluxWithRxSwiftSampleTests' do
        inherit! :search_paths
    
        pod 'Quick', :git => 'git@github.com:Quick/Quick.git', :branch => 'master'
        pod 'Nimble', :git => 'git@github.com:Quick/Nimble.git', :branch => 'master'
    end

end


