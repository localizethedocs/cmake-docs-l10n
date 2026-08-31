presets-file-arg
----------------

* :manual:`cmake(1)`, :manual:`ctest(1)`, and :manual:`cpack(1)` gained
  ``--presets-file`` arguments to support loading
  :manual:`presets <cmake-presets(7)>` from the specified file instead of
  ``CMakePresets.json`` and/or ``CMakeUserPresets.json``. See
  :option:`cmake --presets-file`,
  :option:`cmake --build --presets-file <cmake--build --presets-file>`,
  :option:`cmake --workflow --presets-file <cmake--workflow --presets-file>`,
  :option:`ctest --presets-file`, and :option:`cpack --presets-file` for details.
