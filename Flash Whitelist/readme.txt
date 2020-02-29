Note: This applies to all user accounts.

How to whitelist a Flash Website:
1. Open the "Flash Whitelist.reg" file using Notepad.
2A. You can remove sites by deleting them from the file, BUT YOU MUST SET THE NUMBERS ("x") AS SUCH.
2B. You can edit sites by editing their link, but make sure to keep "http://" or "https://" on them. If they have no subdomain, put "www".
2C. You can add sites by pasting this on a new line:
"x"="your://site.ishere.com"
3. When done, apply them to the registry by double-clicking, allowing admin, then allowing it to change.

Note 2: If it says your browser is managed by a organization, that is normal! This is pretending that a company has forced these settings on for you.
Note 3: If you put a website in a whitelist, you can't disable Flash on that site. You will have to remove the site using the registry editor.

How to un-whitelist a Flash Website:
1. Press Win+R on your keyboard.
2. Type "regedit".
3. Accept admin priveleges.
4. Go to HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Chromium\PluginsAllowedForUrls.
5. Delete the website you don't want.
6. The website is now removed!

NOTE 4: I AM NOT RESPONSIBLE IF YOU BREAK ANYTHING IF YOU DON'T DO THE STEPS TOLD.