fastlane documentation
================
# Installation

1-:Need to set up fastlane and rubby
2-:Create a slack account and create app.
3-:Once you create app -> create webhook and access token
4-:Replace webhook url and replace in your fastlane
Copy your generated web hook url and paste it in ENV[“SLACK_URL”]

After the above step.Run the below command it will succesfully generate apk in slack work space.
bundle exec fastlane slack_build