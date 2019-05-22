platform :ios, '11.0'
inhibit_all_warnings!
use_frameworks!

workspace 'PodTest.xcworkspace'

# The main app target
target 'PodTest' do
  project 'PodTest.xcodeproj'
  pod 'Instabug'

  target 'PodTestTests' do
    inherit! :search_paths
      pod 'OHHTTPStubs/Swift'
  end
end

# A framework target that's linked by TheApp
target 'Logging' do
  project 'Logging/Logging.xcodeproj'
  pod 'Instabug'

  target 'LoggingTests' do
    inherit! :search_paths
  end
end