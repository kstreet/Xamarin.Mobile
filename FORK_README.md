# kstreet fork notes:
*Last Updated January 15, 2014*

**What Is This Fork In Here For?**

This fork is in the kstreet GitHub account because the fork is the copy that is referenced and currently used with:

- `Street.MvxPlugins.Contacts` needs to review code changes in `Cheesebaron.MvxPlugins.AppId` to keep itself current
- That plugin is an Mvx-ized plugin of the `Xamarin.Mobile.Contacts` functionality that is provided in the [Xamarin.Mobile](https://github.com/xamarin/Xamarin.Mobile) component.  The goal is to make that functionality more "naturally consumable" in a solution that prefers the MvvmCross PCL approach over linked or duplicated source code files.


**How Fresh Is This?**

- The code in this repo was current/similar to the `Xamarin.Mobile.Contacts` repo up through [this December 12, 2013 commit](https://github.com/xamarin/Xamarin.Mobile/commit/3f4730cd131c8eae89a6efc560c554a0a9c56058).



**Status**

- Initial Port of the core of Xamarin.Mobile.Contacts for Droid, iOS, and WP8 is done, as of freshness date
- Android code for Xamarin.Mobile.Contacts should be ported over as of freshness date (except for the client sample app)
- iOS code for Xamarin.Mobile.Contacts should be ported over as of freshness date (but only basic iOS client sample app)
- WP8 code and sample for Xamarin.Mobile.Contacts should be ported over as of freshness date


**TODO**

- .


**Not In Scope Right Now**

- Intentionally NOT porting over the "thumbnail"/image for a contact functionality yet.  There are some issues with the current Xamarin implementation that need to be worked out before I can abstract them in a PCL xplat way.  I do not need this functionality in my own apps yet, so this will remain out of scope until I need it (or someone contributes it.) :) 
- WindowsRT port (will do when/if needed - Xam original seems partially done as well)
- Windows Phone 7 will not be ported