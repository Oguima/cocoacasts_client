

target 'Cocoacasts' do
  platform :ios, '12.0'
  use_frameworks!

  #Wrappers
  pod 'KeychainAccess', '~> 3.1.2'
  pod 'ReachabilitySwift', '~> 4.3.0'

  pod 'Reveal-SDK', configurations: ['Debug']
  
  target 'CocoacastsTests' do
    inherit! :search_paths
  end

  target 'CocoacastsUITests' do
    inherit! :search_paths
  end
end
