
platform :ios, '8.0'
use_frameworks!

target 'RxDemo' do
    pod 'RxSwift',    '~> 3.0'
    pod 'RxCocoa',    '~> 3.0'
    pod 'RealmSwift'
    pod 'Alamofire'
    pod 'ObjectMapper'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0'
    end
  end
end
