xcodeproj 'JSONTools.xcodeproj'
platform :ios, '7.0'

pod 'KiteJSONValidator', :git => 'git@github.com:corinnekrych/KiteJSONValidator.git', :branch => 'podspec.public.header'

target :JSONToolsTests, :exclusive => false do
  pod 'JSON-Schema-Test-Suite', '~> 1.1.2-Pod'
  pod 'KiteJSONValidator/KiteJSONResources', :git => 'git@github.com:corinnekrych/KiteJSONValidator.git', :branch => 'podspec.public.header'
  pod 'KiteJSONValidator', :git => 'git@github.com:corinnekrych/KiteJSONValidator.git', :branch => 'podspec.public.header'
end
