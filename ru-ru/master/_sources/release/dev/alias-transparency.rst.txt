alias-transparency
------------------

* The :command:`set_property` and :command:`set_target_properties` commands
  now accept :ref:`Alias Targets`. Properties are set on the target which
  the alias references.

* The :command:`target_compile_definitions`, :command:`target_compile_features`,
  :command:`target_compile_options`, :command:`target_include_directories`,
  :command:`target_link_directories`, :command:`target_link_libraries`,
  :command:`target_link_options`, :command:`target_precompile_headers`,
  and :command:`target_sources` commands now accept :ref:`Alias Targets`.
  The command operates on the target which the alias references.

* The :command:`add_dependencies` command now accepts :ref:`Alias Targets`.
  Dependencies are added to the target which the alias references.

* The :prop_tgt:`ALIASED_TARGET` target property is now read-only.
