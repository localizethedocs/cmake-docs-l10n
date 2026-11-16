swift-ninja-separate-swiftmodule-edge
-------------------------------------

* The :ref:`Ninja Generators` gained the
  :prop_tgt:`Swift_SEPARATE_MODULE_EMISSION` target property, initialized by
  the :variable:`CMAKE_Swift_SEPARATE_MODULE_EMISSION` variable, to control
  whether importable Swift targets emit ``.swiftmodule`` from a dedicated
  build edge.  Policy :policy:`CMP0215` enables this by default.

* The default :prop_tgt:`Swift_MODULE_NAME` now replaces hyphens with
  underscores, since hyphens are not valid in Swift module identifiers.
