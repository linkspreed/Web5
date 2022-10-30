## Version 2.2.7
#### Release date: 30. Oct 2022
- We fixed some bugs.
- Improvement in the performance.

## Version 2.2.6
#### Release date: 30. Oct 2022
- Minor updates.

## Version 2.2.5
#### Release date: 30. Oct 2022
- improved tracking for Google Analytics

## Version 2.2.4
#### Release date: 30. Oct 2022
- Account verification email is now sending in preferred app language
- Fixed issue where metered billing mode still count in some cases members after team folder was deleted
- In case if cron isn't set, in Settings/Server tab you will see suggestions for cron command

## Version 2.2.3
#### Release date: 30. Oct 2022
- Subscription module is now available for Regular license type 

## Version 2.2.2
#### Release date: 30. Oct 2022
- Fixed issue when email wasn't sent in active app language
- Fixed issue with subscription module loading

## Version 2.2.1
#### Release date: 30. Oct 2022
### New Usage Restriction Rules for User Accounts for Metered Billing
- Allow limiting max usage before users will be forced to increase balance in first month of account existence
- Force users to increase balance when usage is bigger than their current balance

#### Release date: 30. Oct 2022
- Fixed reCaptcha for the contact form

## Version 2.2.0.13
#### Release date: 30. Oct 2022
- Extended login time up to 3 months
- Fixed deleted at language string in grid view browsed in trash section

- ## Version 2.2.0.12
#### Release date: 30. Oct 2022
- Fixed paystack transaction issue

## Version 2.2.0.11
#### Release date: 03. Jul 2022
- Added hint to set cron command in dashboard panel when cron is not set correctly

## Version 2.2.0.10
#### Release date: 27. Jun 2022
- Fixed issue with downloading certain file types when you are using Backblaze storage driver
- Fixed issue when Google Analytics doesn't record visitors

## Version 2.2.0.9
#### Release date: 23. Jun 2022
- Added spinner when pdf is loading
- Set sandbox/live mode in PayPal key configuration setup form
- Fixed issue when after deleting user, the related subscription wasn't deleted
- Fixed issue when you perform composer update with private repository
- Fixed issue where change in sorting option will duplicate the content in file view
- Fixed issue where Dragged & Dropped folder from desktop didn't start uploading
- Fixed issue when you upload empty .txt file, it stops the upload process

## Version 2.2.0.8
#### Release date: 15. Jun 2022
- Fixed issue when you tried switch to another language, the language stay same

## Version 2.2.0.7
#### Release date: 13. Jun 2022
- Solved issue when you click on the PayPal logo it makes the new copy of the payment buttons

## Version 2.2.0.6
#### Release date: 13. Jun 2022
- Solved issue when user wasn't redirected into stripe checkout

## Version 2.2.0.5
#### Release date: 12. Jun 2022
- Solved issue with showing trash content (Affected since 2.2.0)

## Version 2.2
#### Release date: 18. May 2022
***PHP 8.1***

### Fixes
- Solved issue with database backup notifications
- Solved issue where after team member was invited into team folder, email with urging the recipient to create new account was sent
- You are now allowed to set price for metered billing in 3 decimal places
- Solved UI issue with empty notification popup
- Plans in fixed subscription are now automatically sorted from lower to higher price
- When new user was created via admin, the verification email was send
- Item name in list view type is now extended on the full page width

### New Features
- API version 1 released
- Paginated records loading with infinity scroller
- If you send file request for native user via email option, the push notification will be sent to the user
- Ability to test your websocket (Broadcasting) connection

## Version 2.1.3
#### Release date: 10. May 2022
- Ability to manually synchronize plans in fixed subscription type
- Improved sanitization for .env values to prevent crash your app
- Improved reCaptcha validation errors
- Fixed issue when upload doesn't start after you drag the file into empty view
- Fixed issue when homepage flash to sign in screen after the homepage was disabled in admin panel
- Fixed trash navigator issue
- Fixed issue when you create plan with 0 team members amount

## Version 2.1.2
#### Release date: 8. May 2022
- Fixed issue with chunk uploads (Critical issue affected since 2.1.1)
- Fixed issue with creating plan with unlimited team members

## Version 2.1.1
#### Release date: 29. April 2022
- Fixed issue with reading image upload

## Version 2.1.0
#### Release date: 25. April 2022
- New **remote upload** function
- Broadcast server implementation

## Version 2.0.19
#### Release date: 21. April 2022
- The switch button in archived plans is now hidden
- Fixed upload progressbar in mobile version
- Added Viet Nam language into the language editor

## Version 2.0.18
#### Release date: 19. April 2022
- Fixed issue with Google login button

## Version 2.0.17
#### Release date: 12. April 2022
- Added option to use FTP as VueFileManager file storage server

## Version 2.0.16
#### Release date: 8. April 2022
- UI enhancements & fixes

## Version 2.0.15
#### Release date: 6. April 2022
- The delay after first upload in file request when the interface wasn't showing was removed
- If adsense banner location isn't filled, the ads space won't be showed
- Fixed issue when in grid view you tried to move image into another folder
- Fixed issue when you can't move or delete items via mobile multiselect function
- You can now open searched file from spotlight in FilePreview mode to access file settings and functions

## Version 2.0.14
#### Release date: 5. April 2022
- Added option to set default max team members for new user registrations
- Added new app settings shortcuts findable by spotlight
- Now in 2fa set up challenge user is required to confirm his app setup with code

## Version 2.0.13
#### Release date: 4. April 2022
- Auto plan synchronization improvements.
- Fixed issue with thumbnails in grid preview type
- Fixed issue in mobile spotlight where you trying open searched image

## Version 2.0.12
#### Release date: 2. April 2022
- Added status column to the fixed plan table
- Ability to delete fixed plan if there isn't any subscribed user
- Improved error handling in subscription module

## Version 2.0.11
#### Release date: 1. April 2022
- Improved email setup in administration settings and setup wizard
- Ability to set custom s3 compatible service in administration settings and setup wizard
- Test s3 connection before set up in administration settings and setup wizard
- Test smtp connection before set up in administration settings and setup wizard

## Version 2.0.0 - 2.0.10
#### Release date: 31. March 2022
- You can now generate link for direct download via context menu in copy link input
- You can now upgrade from regular to extended license version via admin panel
- Fixed issue with .dwg file icon
- You can now set uploading chunk file size directly in your admin
- Team Folders and Shared With Me root folder has now disabled delete/move function
- When you invite someone to your team folder, all his usage (storage, bandwidth) will be on behalf of you, not the member
- Fixed issue when you are moving folders between your Team Folders and Private files and vice versa
- Fixed issue when downloading bandwidth doesn't write to the user total bandwidth stats
- Fixed issue with language strings which indicate limited/unlimited team members in fixed plans
- Fixed issue when you are trying delete user registered with only the first name
- Fixed issue with Adsense where banners wasn't placed correctly by their described location

## Version 2.0.0
#### Release date: 21. March 2022

**User Interface**
- Fullscreen mode can be set by double arrow icon on top of navigation sidebar in file page or by action in spotlight
- In mobile version you can now by opening image or document move seamlessly to another by swipe gesture
- Emoji picker was redesigned and now offer better experience to pick your favourite emoji for your folder icon
- Actions like create folder, upload files and any others was moved and grouped by 'Frequently used' and 'Others' category under single button
- User profile, Dashboard and other admin pages was redesigned
- Mac users can now switch between native emojis and twemojis
- New button to switch between dark/light mode was added under the main navigation in desktop
- Now when you undo in your browser, it goes back to the previous folder

**Spotlight**
- Search through your files and folders
- Can be used as quick navigation through your folders or app pages
- Ability to search actions like toggle emojis, toggle dark/light mode, creating file request, new user and many more
- Search your users by activating user filter with keyboard shortcut (u+space)
- Ability to call spotlight with cmd/ctrl + k from any location in app like admin or user profile
- Ability from any location in the app to show document, image or video in file preview component
- Ability to use keyboard shortcuts to navigate in spotlight like arrow up/down, enter

**Collaboration**
- New Team Folders and Shared with Me categories
- Ability to create new team folder and invite users by email invitation, or if user is app user, then push notification will be sent as well.
- Ability to convert existing folder into Team Folder and invite members into it.
- Ability to dissolve your team folder. All members permissions will be revoked and your folder will be moved into My Files category.
- Ability to leave folder if you are member of someone team folder
- Received invitation can be accepted or declined
- User avatar indicate in file icon who is the owner of the file
- New team heads icon in desktop and mobile toolbar to indicate team members in the team folder 

**Metered Billing**
- New metered billing where user can be charged by what he uses.
- Bandwidth, storage, flat fee and members are optional features which can be charged, not required
- Native balance system from which user is charger at the end of current billing period
- User can fund his balance by PayPal and Paystack single payment option
- If Stripe payment method is allowed, user can register his credit card and all future payments for billing period will be automatically charged. If there is any credit in balance and is sufficient, then this amount will be preferred instead of credit card charging
- User has ability to add/delete his payment methods (only Stripe)
- Admin has ability to increase user balance with certain amount
- Ability to set registration bonus for every new user registration
- User can set billing alert with certain amount. When this amount will be reached, the notification will be sent.
- New Usage Estimates widget in user profile which provide price estimates for current billing period
- New transactions widget in user profile with usage history

**Fixed Billing**
- Plans with yearly billing period is now supported
- New subscription widget with subscription details in user profile
- New Payment Method widget to manage user credit cards (available only for Stripe) 
- New popup component to subscribe or upgrade account plan

**Notification Center**
- Ability to see notifications by Unread and Read category
- Interactive notifications to seamlessly perform actions from it if needed
- If broadcasting is set, notifications will be received just in time and showed in bottom right corner of the app
- Ability to clear all notifications by button

**Zip**
- New on the fly zipping system zips files without additional storage usage 
- User can now select any files with any folders and zip them together

**Sharing**
- Redesigned sharing popup component for better user experience
- Shared video file (.mp4) has now ability to play video in shared page
- Ability to get share link via QR code
- Ability to generate embeddable code with shared item (beta)
- App logo was added into single file share pages

**File Request**
- User can generate file request by opening context menu over single folder or call file request from spotlight
- Ability to set custom folder name if file request will be filled
- Ability to leave a message for guest
- Ability to send file request by email for certain email recipient
- Full-fledged reach UI for guests to upload and manage their files directly in file request
- Push notification about filled file request will be received for user

**Folder Upload**
- Now user can upload their folders. The same folder structure will be recreated in the app

**User Settings**
- New appearance option was added where user can set his theme mode by dark, light or based by system option
- New default emoji option was added where Apple user can switch between native emojis or twemoji
- 2fa setup challenge option was added. User can store and generate backup keys.
- New Personal Access Token section was added where user can generate access token for API requests.
- New 'Current Password' input was added into change password functionality
- New widget to track the latest upload and download was added into the Storage tab
- Storage usage widget was redesigned
- New Billing tab with all subscription related items was added

**Login & Registration**
- Email confirmation for new account registrations can be required
- Integrated database with more than 550 disposable temporary email services to automatically deny new account registrations
- Users can now set up 2 factor verification with their favourite authenticator app
- reCaptcha was added to provide security for your registration and contact form
- Social authentication was implemented with Facebook, Google and GitHub drivers.

**Adsense**
- Adsense will be integrated into VueFileManager
- The ads are showing in 3 locations - File Viewport, Download Page and Homepage

**Setup Wizard**
- Server check before you running installation, it will show you if you had set up your server correctly
- Dark mode support
- Now you don't need to set up your subscription system in setup wizard

**Broadcasting**
- Pusher implementation for live communication
- Native websocket server as replacement for Pusher (more details soon)
- Live notification

**System**
- Database backups on daily basis
- After you upload image, additionals thumbnails will be generated to provide you faster browsign experience through your image gallery 
  
**Admin & Settings**

**Dashboard**
- New widget to track the latest upload and download was added
- New widget with the latest transactions was added into extended license version
- New earnings widget was added
- New alerts will tell you if you are missing plan or you don't have running cron correctly

**Settings / Server**
- Ability to see if cron job is running correctly
- Ability to download your server log from admin panel
- Ability to see latest 5 database backups
- Ability to check if writable permission for exact folders are set correctly
- Ability to check if you have correctly set php version and php.ini variables
- Ability to see if you have installed all required php extensions

**Settings / Environment**
- Ability to set Broadcasting from admin settings
- Ability to set Storage Driver from admin settings
- Ability to set Mail Driver from admin settings

**Settings / Appearance**
- Ability to change entire VueFileManager color scheme
- Ability to set dark mode logo for main and horizontal logo
- Ability to set your own OG Image
- Ability to set your own Touch Image

**Settings / Login & Registration**
- New option where you can require email verification was added
- New widgets to set up Facebook, Google and GitHub social authentication

**Settings / Application**
- New options to set up reCaptcha

**Settings / Adsense**
- Ability to manage Google Adsense

**Dev**
- PHP 8 support
- New DDD design for the backend
- Shipped with the latest version of Laravel 9.x
- Passport was replaced by Sanctum
- New artisan command that expressly installs the entire application
- New artisan command that expressly installs the entire application with the demo data
- ~80% Of the frontend code was migrated into Tailwind v3. We will continue to reach 100% tailwind friendly


## Version 1
#### Release date: 26. March 2021
- Official release
