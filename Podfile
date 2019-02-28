platform :ios, '9.0'

target 'Pick in Time' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Pick in Time
    pod 'Alamofire'
    pod 'Firebase'
    pod 'Firebase/Auth'
    pod 'SVProgressHUD'
    pod 'ChameleonFramework'

end

post_install do |installer|
installer.pods_project.targets.each do |target|
target.build_configurations.each do |config|
config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
end
end
end
