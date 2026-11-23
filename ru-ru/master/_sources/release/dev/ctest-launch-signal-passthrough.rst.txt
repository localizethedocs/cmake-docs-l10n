ctest-launch-signal-passthrough
-------------------------------

* When CTest build launchers are enabled (see the :module:`CTestUseLaunchers`
  module), a build rule that is terminated by a signal is now reported as a
  build failure.  Previously such a rule was reported as success, so a crashed
  compiler, linker, or custom command could be recorded as a passing build on
  the dashboard.
