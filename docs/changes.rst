Changes
=======

v0.2.2
------
  - Suppress console logging from `rubberband`

v0.2.1
------

  - Improved error handling when `rubberband` fails to execute.

v0.2.0
------

  - Removed dependency on librosa in favor of pysoundfile
    (`PR #4 <https://github.com/bmcfee/pyrubberband/pull/4>`_).
  - Stereo/mono interface now matches pysoundfile instead of librosa: t
    he first axis now corresponds to time rather than channel number.

