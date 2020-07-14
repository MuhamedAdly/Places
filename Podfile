source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
use_frameworks!

def development_pods
  pod 'RxSwift', '~> 5.1'
  pod 'RxCocoa', '~> 5.1'
  pod 'Alamofire' , '~> 4.9.1'
  pod 'Kingfisher' , '~> 4.10.1'
  pod 'SwiftLint', '~> 0.39'
  pod 'ViewAnimator', '~> 2.7'
end

def testing_pods
  pod 'Quick', '~> 2.2'
  pod 'Nimble', '9.0.0-beta.2'
  pod 'OHHTTPStubs/Swift', '~> 9.0'
end

target 'Places' do
  development_pods
  target 'PlacesTests' do
    inherit! :search_paths
    testing_pods
  end

end
