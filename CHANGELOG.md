# 0.5.0 (2015-10-06)
* BREAKING (for npm users only): Use dist files when installing through npm. You will now need to require the `angular-bootstrap-confirm/src/ui-bootstrap-position` file or the full `angular-ui-bootstrap` module first (See the readme for an example)

# 0.4.2 (2015-10-04)
* Ignore bower source files

# 0.4.1 (2015-10-02)
* Allow handle-focus to be set to false if set as an attribute.

# 0.4.0 (2015-09-28)
* Auto focus the confirm button when opening the popover. Thanks to @andreptb! 

# 0.3.1 (2015-08-29)
* Make `is-open` optional for angular 1.3 compatibility

# 0.3.0 (2015-07-28)
* Add is-open property to control the visibility of the popover

# 0.2.0 (2015-07-12)
* BREAKING: Replace the confirmationPopover provider with a much simpler confirmationPopoverDefaults value
* Remove the off click dependency
* Build with webpack and publish to npm

# 0.1.1 (2015-06-22)
* Mark angular sanitize as a dependency and not a dev dependency
* Ensure angular 1.4 compatibility

# 0.1.0 (2015-05-09)
_Very first, initial release_
