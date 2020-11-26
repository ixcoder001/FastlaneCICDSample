# FastlaneCICDSample

Step 1: Setup a project

Step 2: Fastlane setup
* Step 1: In terminal, Go to project folder, Run "fastlane init"
* Step 2: open Fastfile, in fastlane folder (Project folder)
* Step 3: In the first line add "setup_travis" and save

Step 3: Travis file setup
* Step 1: In terminal, Go to project folder, Run "touch .travis.yml"
* Step 2:

      language: swift
      osx_image: xcode12.2
      script:
          - fastlane scan 
* Step 3: Save the changes and commit

Step 4: Based on the travis setup for commits / PR travis build runs and you can see the status in Github
