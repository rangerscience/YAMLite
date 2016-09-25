# YAMLite
Super light implementation of YAML in C#, specifically compatible with Unity3d.

Depreciated in favor of [Maptionary](https://github.com/narfanator/maptionary), which does everything YAMLite did, and more, and better

Maptionary is:

* Better named - reduces confusion with the relationship to the YAML format (since it also handles XML and JSON)
* More features - has better handling of mixed formats (JSON in XML, for example), and more!
* Suuuuper faster - Maptionary avoids the recursion and temporary strings of YAMLite's implementation, which drastically improves performance.

On that last point - YAMLite's performance issues were due to the *garbage collection* of all the temporary strings. Maptionary avoids this by re-using strings. Interesting!
