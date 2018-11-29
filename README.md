# Xcode

**Random Issues**
1. `rm -rf ios/build/`
2. Clean Xcode `⌘-Shift-K`

**Apollo Issues**
1. `yarn global add apollo`

**Pods**
1. `pod install --repo-update`
2. `pod cache clean`
3. `pod install`

**Manual Linking**
https://facebook.github.io/react-native/docs/linking-libraries-ios

# Node Modules

**Can't find a package**
1. `rm -rf node_modules`
2. Then `yarn`

**Multiple Proccesses Running**
1. `sudo lsof -i tcp:8081`
2. `kill -9 [PID]`

**Run On Specific Device**
1. `react-native run-ios --simulator="iPhone X"`

# Fake Workouts

1. https://dashboard.heroku.com/apps/flex-qa?web-console=flex-qa
2. To create more fake users `rake db:seed:fake_users`
3. To simulate fake workouts `rake workouts:fake video_id=[id] workout_id=[id] quantity=[num]` `workout_id` is optional
