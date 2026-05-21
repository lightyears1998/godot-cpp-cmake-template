# Godot C++ CMake Template

A template for GDExtension plugins based on godot-cpp. It uses CMake buildsystem and is compatible with vcpkg.

## Adding document for the plugin

``` shell
# Inside the `project` folder:
godot --doctool ../ --gdextension-docs
# The command above generates XML files inside the `doc_classes` folder.
```

---

## Useful Link

- <https://docs.godotengine.org/en/stable/tutorials/scripting/cpp/build_system/cmake.html#secondary-build-system-working-with-cmake>
- <https://docs.godotengine.org/en/latest/tutorials/scripting/cpp/gdextension_docs_system.html>
