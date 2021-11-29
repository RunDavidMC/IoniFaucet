# [IoniFaucet](http://faucet.ionibyte.com/)'s Public Changelog

**Versioning goes as follows:** ``Macro.Major.Minor:Mini``.
A number for mini will not always be included

## 1.0.4:1
Added URL for referral link to dashboard for easy of use.

## 1.0.4
Added 3 new questions to quiz.

## 1.0.3
Fixed SLD gifting.

## 1.0.2
Fixed a bug that would log their address and IP as used before checking if the gift was successful.

## 1.0.1:1
Fixed a bug that only allowed most recently obtained name to be checked when uploading.

## 1.0.1
Fixed a bug that didn't allow uploading names with ``r`` or ``n`` in them.

## 1.0.0:3
Fixed a bug that broke codes

## 1.0.0:2
Fixed a bug that broke referrals

## 1.0.0:1
Fixed bug that would not allow users to claim names.

# 1.0.0
User pages are now live! Configure them at ``/userpages``, view them at ``/u/[rCode]``

## 0.5.3:3
Users with username ``root``, ``admin``, or ``ionifaucet`` will have any non-referred uses count towards their referrals.

## 0.5.3:2
``/dashboard`` now leads to ``/dash``.

## 0.5.3:1
Users rank 0 or higher can now access ``/dash``. Negative rank levels will restrict permissions.

## 0.5.3
``/u`` now shows an under construction site.

## 0.5.2:2
Usernames now must follow URL-friendly rules. ``^[a-zA-Z0-9_-]+$``

## 0.5.2:1
Trailing slashes no longer matter.
Ex. ``/dash/`` and ``/dash`` now show the same page, rather than ``/dash/`` returning a 404 error.

## 0.5.2
``/dash`` now shows referral code and amount of referrals a user has.

## 0.5.1
When a user uses a referral code then claims a TLD, that is considered a referral for the referring user (will be implemented more later on).

## 0.5.0
Using a referral code now makes the **Don't have a Namebase account? Sign up now!** have the referrer's link (must be manually set by an admin for now).

## 0.4.3
Accessing ``/r/[code]`` will put a cookie in the user's browser and redirect them to the main site. Rerferral codes for users default to being usernames.

## 0.4.2
Users above rank 0 can now access ``/dashboard``

## 0.4.1:1
3 new SLDs added to ``/sld``
- customsld
- shortsld
- faucetsld

## 0.4.1
After logging in, user token is saved for 30 days.

## 0.4.0
Added login system! Use ``/login`` and ``/register`` to setup an account.

## 0.3.1
Quiz now requries user to put at least 10 characters in the text fields.

## 0.3.0:1
Updated quiz questions

## 0.3.0
Created a quiz that must be filled out before a name is given.

## 0.2.2:1
Updated [blocked-email-keywords.txt](blocked-email-keywords.txt). Many of the first ones are ones I've noticed spamming the console, the rest are found from sources online. If you believe there are any mistakes, please open an issue.

## 0.2.2
Started a public changelog.
