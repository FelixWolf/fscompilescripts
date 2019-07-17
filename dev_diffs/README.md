# NOT FOR PRODUCTION
# NOT FOR PRODUCTION
# NOT FOR PRODUCTION
# NOT FOR PRODUCTION
# NOT FOR PRODUCTION
**THESE SCRIPTS ARE DIRTY HACKS USED FOR SPEEDING UP BUILD TIME AND SHOULD NOT BE USED IN A PRODUCTION BUILD**
**USE AT YOUR OWN RISK**

# viewer_manifest.py.diff
This disables three things:
* Stripping
* Symbol saving
* Packaging(into a .tar.gz)

We don't need stripping since we are developing, we don't need to save symbols since we didn't strip symbols, and we don't need packaging because we are not sending it anywhere.
