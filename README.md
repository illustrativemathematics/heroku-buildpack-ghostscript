# Heroku Buildpack for Ghostscript

## WARNING
* This buildpack is not intended for casual joyriding.
* Currently, it installs Ghostscript 9.55 at Heroku.
* This does NOT add this version to the system path, since Heroku includes a more
modern version (10.02 as of this writing).
* For details see [this Linear story](https://linear.app/illustrativemathematics/issue/PE-2303/tikz-not-working-properly).
