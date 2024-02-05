# Bug Weight

## Installation for Google Chrome:
1. Download the repository
2. Open [chrome://extensions/]()
3. Enable developer mode
4. Press "Install unpacked extension"
5. Select the folder with the application

The weight (priority) is calculated using the formula: mass * critical * block, where:

#### Mass - how massive the problem is..
- 1 - single cases of error reproduction
- 2 - affects a group of users
- 3 - affects a large number of users

#### Critical - how critical is the area of the application where the bug was found.
- 1 - not critical
- 2 - Normal
- 3 - critical

#### Block - насколько баг блокирует юзер флоу
- 1 - does not block
- 2 - blocks, but there is a workaround
- 3 - blocks, no workaround solution

Maximum weight - 27, minimum weight - 1
