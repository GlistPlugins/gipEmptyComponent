# gipEmptyComponent
This is a baseplate for all the GlistEngine components and should be cloned under `~dev/glist/glistplugins` whenever developing a new plugin for the engine.

The developer should put his external precompiled library files into the component's libs folder.

- Windows developers should not forget to add
```
${workspace_loc}\..\..\..\..\glistplugins\gipYourPluginName\libs\bin
```
directory to the GlistApp project's PATH list.
(Project->Properties->C/C++ Build->Environment->PATH)
