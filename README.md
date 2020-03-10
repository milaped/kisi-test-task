# Basic Kisi Concepts

## Using the Kisi Reader Pro vs. Using the Kisi app
When unlocking with Kisi, there are three ways you can gain access:

1. **Swiping the button in the Kisi app** - by sliding the button `[COMMENT: Screenshot på knappen eller förklaring av hur knappen ser ut ex. den "röda" knappen skulle tydliggöra vad läsaren ska leta efter i appen]` to the right, our app will send a signal via the cloud to the Kisi Controller Pro, which will trigger the relay and unlock your door.
1. **Using the tap-to-unlock feature  with a Kisi Reader Pro** - The tap-to-unlock feature allows you to hold your phone up to the Kisi Reader Pro like you would a key card, and the reader will read your phone's Bluetooth (iPhone) or NFC (Android) signal to allow access.  When your phone's signal is authenticated, the reader will send a signal via the cloud to the Kisi Controller Pro, which will trigger the relay and unlock your door.
1. **Using a Kisi card/tag/fob or 3rd party card with a Kisi Reader Pro** - When a user is assigned a Kisi card/tag/fob or 3rd party card, that user is able to hold their item up to the reader to gain access. 
_**Note**_ - Each Kisi card/tag/fob must be assigned by and admin and then activated by the user.  Each 3rd party card will need to be scanned and added by an Android device.
`[COMMENT: Eftersom första meningen i Note:n innehåller en länk till mer information så skulle andra meningen också kunna innehålla en länk till mer information]`

`[COMMENT: Här skulle man även kunna få in en "which one to use depends on..." förklaring för att hjälpa läsaren att hitta vilken metod som passar deras behov bäst]`
Unlocking with the Kisi app has no bearing on unlocking with the Kisi Reader Pro. The Kisi app communicates with the Kisi controller Pro independently from the Kisi Reader Pro, and vice versa.

## Users vs. Members vs. Shares 

When you add a member to your place, the email address associated with that member is the defining criteria Kisi uses to create a **User Profile**. Once a profile is created within Kisi, that profile can be shared access to any number of Kisi places. The **User Profile** does not belong to the place, but rather to the email address used to create it.`[COMMENT: Här skulle man kunna förtydiga vad en user är och hur det är relaterat till en user profile]`

The **Share** is what allows access to Kisi.  Access can be broken down to the Kisi default group "Entire Place" or to any custom group you create for your place.  The Share will follow the access permissions you set up for your place / groups.

`[COMMENT: Här skulle man kunna förtydiga vad en member är]`
**Members** are added to a place by the place admin.  Typically, when a member is added they are also issued a Share.  Members can exist in a place without having an active share, meaning they can be added to any group at any time without having to be added again as a member.  

## Types of Kisi Users  
`[COMMENT: Oförändrad förutom tagit bort inledande raden i och med att titeln på kapitlet redan beskriver innehållet bra]`
1. **Basic** - This user can unlock any door to which he/she is shared access.
1. **Observer** -This user can unlock any door to which he/she is shared access and can view events logs for the group(s) to which he/she is a member.
1. **Manager** - This user can unlock any door to which he/she is shared access and can view events logs for the group(s) to which he/she is a member, as well as being able to add members to the group(s) to which he/she is a member.
1. **Administrator** -This user can unlock any door to which he/she is shared access and can view events logs for the group(s) to which he/she is a member, as well as being able to add/delete members to the group(s) to which he/she is a member. This user can also configure the Kisi devices, add/delete doors, add/delete integrations, add/delete groups and set security restrictions.

## Security Restrictions
`[COMMENT: Jag funderade på att ta bort numreringen, men kom fram till att i det fall en support ska hänvisa till en specifik punkt i hjälpdokumentet så är det kanske lättare att hänvisa med hjälp av ett kapitel och ett nummer]`
1. **Geofence Restriction** - This restriction only allows unlocks to made when the user is within a 300 meter (0.2 mile) radius of the building (basically on the same block). `[COMMENT: satte ihop två meningar till en eftersom den senare meningen var inom en fristående parentes. Inte nödvändigt, men kanske lite lättare läsmässigt att hänga med]` This restriction is mainly used by Kisi users who want a location restriction, but do not have Kisi Readers.
1. **Primary Device Restriction** - This restriction only allows a user to be logged into one device at a time.  It prevents users from sharing their login credentials with other people to allow multiple logins at the same time.
1. **Reader Restriction** - This restriction is a location restriction that is defined by the user's proximity to the Kisi reader.  Essentially, the user must be standing within the Bluetooth/NFC radius (about 2 feet) of the reader.
 1. **Time Restriction** - This restriction sets the time period you wish to allow users to access your building.  For example, if you wish to allow access only between the hours of 9am - 5pm, Monday - Friday, you would set your restrictions for those days/times and that would be when your users would be able to unlock the doors.  Outside of those hours, no one will be granted access.

## Bluetooth vs. NFC
Bluetooth (BLE) is the primary communication technology used with iPhones, NFC (Near Field Communication) and BLE is used with Android devices.  To be able to communicate with the Kisi readers, users must have these functions enabled on their phones.  If there is a location restriction, i.e. - Geofence or Reader, the user must also have location services enabled within the Kisi app. 
