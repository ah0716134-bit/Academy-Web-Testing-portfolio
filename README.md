# Academy-Web-Testing-portfolio
Manual testing and UI/UX assessment for AcademyBugs website, including detailed bug reports and console log analysis.
## Test cases
ID | Description | Steps | Expected result | status
| :--- | :--- | :--- | :--- | :--- |
TC-1 | verify Of format the products images | 1. Open the Academy Bugs <br> 2. click on "find bugs" in the navigation bar <br> 3.Click on "Dark Grey Jeans" | the product images fills the box | Fail

## Bug Report
# Bug-001 : the image is not completely displayed.
* Severity : Medium
* Issue type : visual
* Steps : 1. Open the Academy Bugs <br> 2. click on "find bugs" in the navigation bar <br> 3.Click on "Dark Grey Jeans"
* Expected result : the product images fills the box
* Actual result : The image has a white space on the right
* ## Attachment<img width="1667" height="937" alt="6" src="https://github.com/user-attachments/assets/2edb44b8-6c1f-4e41-b6d7-04e5637e6ace" />
### 📋 Console Logs

<details>
<summary>Click to view full logs</summary>

```javascript
01:27:52.343 Navigated to https://academybugs.com/store/dark-grey-jeans/
01:27:52.435 jquery-migrate.js?ver=3.4.1:104 JQMIGRATE: Migrate is installed with logging active, version 3.4.1
01:27:52.531 dark-grey-jeans/:452  GET https://cdn.polyfill.io/v2/polyfill.min.js net::ERR_NAME_NOT_RESOLVED
01:27:52.680 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.resize() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ tinytools.tourtip.js?ver=1.7.3:730
(anonymous) @ tinytools.tourtip.js?ver=1.7.3:735
01:27:52.680 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ tinytools.tourtip.js?ver=1.7.3:730
(anonymous) @ tinytools.tourtip.js?ver=1.7.3:735
01:27:52.708 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.click() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:39
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.708 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:39
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.708 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.change() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:91
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.709 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:91
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.709 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.submit() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:408
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.709 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:408
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.710 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.mousemove() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:733
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.710 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:733
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.710 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.hover() is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:749
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.710 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:749
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.720 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.size() is deprecated and removed; use the .length property
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:6510
each @ jquery.js?ver=3.7.1:383
each @ jquery.js?ver=3.7.1:205
accordion @ ec-store.js?ver=5_7_9:6509
(anonymous) @ ec-store.js?ver=5_7_9:6491
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.720 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ ec-store.js?ver=5_7_9:6510
each @ jquery.js?ver=3.7.1:383
each @ jquery.js?ver=3.7.1:205
accordion @ ec-store.js?ver=5_7_9:6509
(anonymous) @ ec-store.js?ver=5_7_9:6491
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.731 site.js?defer&ver=1.21.0:1 init popups ✔
01:27:52.744 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.scroll() event shorthand is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ square-custom.js?ver=1.7.3:57
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.745 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ square-custom.js?ver=1.7.3:57
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.746 jquery-migrate.js?ver=3.4.1:136 JQMIGRATE: jQuery.fn.bind() is deprecated
migrateWarn @ jquery-migrate.js?ver=3.4.1:136
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ complianz.js?ver=4.7.51780780370:172
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.746 jquery-migrate.js?ver=3.4.1:138 console.trace
migrateWarn @ jquery-migrate.js?ver=3.4.1:138
(anonymous) @ jquery-migrate.js?ver=3.4.1:170
(anonymous) @ complianz.js?ver=4.7.51780780370:172
mightThrow @ jquery.js?ver=3.7.1:3489
(anonymous) @ jquery.js?ver=3.7.1:3557
setTimeout
(anonymous) @ jquery.js?ver=3.7.1:3602
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
fire @ jquery.js?ver=3.7.1:3361
fire @ jquery.js?ver=3.7.1:3223
fireWith @ jquery.js?ver=3.7.1:3353
ready @ jquery.js?ver=3.7.1:3844
completed @ jquery.js?ver=3.7.1:3854
01:27:52.747 complianz.js?ver=4.7.51780780370:651 opt-in
01:27:52.749 complianz.js?ver=4.7.51780780370:533 fire cmplz_event_functional
01:27:52.754 mystickymenu.min.js?ver=2.7.4:1 myStickymenu: Entered Sticky Class does not exist, change it in Dashboard / Settings / myStickymenu / Sticky Class.

</p>
</details>
