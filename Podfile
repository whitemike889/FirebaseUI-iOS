# Uncomment this line to define a global platform for your project
platform :ios, '8.0'

target 'FirebaseUI' do
  use_frameworks!

  pod 'Firebase'
  pod 'Firebase/Database'
  pod 'Firebase/Auth'

  pod 'FBSDKLoginKit', '~> 4.0'
  pod 'GoogleSignIn', '~> 4.0'
  pod 'TwitterKit', '~> 2.4'
end

target 'FirebaseDatabaseUI' do
  # Pods for Database
  pod 'Firebase/Database'

  target 'FirebaseDatabaseUITests' do
    inherit! :search_paths
  end
end

target 'FirebaseAuthUI' do
  # Pods for Auth
  pod 'Firebase/Auth'

  target 'FirebaseAuthUITests' do
    inherit! :search_paths
  end
end

target 'FirebaseFacebookAuthUI' do
  # Pods for Facebook Auth
  pod 'FBSDKLoginKit', '~> 4.0'

  target 'FirebaseFacebookAuthUITests' do
    inherit! :search_paths
  end
end

target 'FirebaseGoogleAuthUI' do
  # Pods for Google Auth
  pod 'GoogleSignIn', '~> 4.0'

  target 'FirebaseGoogleAuthUITests' do
    inherit! :search_paths
  end
end

target 'FirebaseTwitterAuthUI' do
  # Pods for Twitter Auth
  pod 'TwitterKit', '~> 2.4'

  target 'FirebaseTwitterAuthUITests' do
    inherit! :search_paths
  end
end

target 'Database' do
  # Pods for Database
  pod 'Firebase/Database'
end

target 'Auth' do
  # Pods for Auth
  pod 'Firebase/Auth'
end

target 'Facebook' do
  # Pods for Facebook Auth
  pod 'Firebase/Auth'
  pod 'FBSDKLoginKit', '~> 4.0'
end

target 'Google' do
  # Pods for Google Auth
  pod 'Firebase/Auth'
  pod 'GoogleSignIn', '~> 4.0'
end

target 'Twitter' do
  # Pods for Twitter Auth
  pod 'Firebase/Auth'
  pod 'TwitterKit', '~> 2.4'
end
