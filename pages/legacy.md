---
layout: page
permalink: "/legacy/"
path: "legacy"
css: "legacy"
---
> Files are actually unavailable

## Old versions of the mod
Here are presented old versions of the mod that were found in web archives. They are not supported at all, but are placed here in case anyone wants to play on an older version

The earlier versions were written by Verdana until version 1.7. For those versions, they were ported by Rene_Z and thatapplefreak. Any later versions were ported by KillJoy

> **Note:** The 1.7 versions are ported from [VoxelModPack](http://voxelmodpack.com/modpacks.html){:target="_blank"}

[Changelog]({{ '/assets/downloads/legacy_changelog.txt' | relative_url }}){:target="_blank"}

### Mod types
- `litemod` - these require LiteLoader to run. They go in the `mods` folder
- `ModLoader` - loaded by ModLoader in the `mods` folder. Probably works with Forge/FML, too
- `Universal` - these can be installed either by putting them in the client jar or loaded by ModLoader in the `mods` folder
- `Normal` - these are installed by modifying the client jar

---

### Versions
{% for item in site.data.old_files -%}
- [{{ item.version }}](#{{ item.version | slugify }})
{% endfor %}

{% for item in site.data.old_files %}
### {{ item.version }} {#{{ item.version | slugify }}}
{% for asset in item.assets -%}
- **{{ asset.name }}**: {% for file in asset.files %}[{{ file.type }}]({{ '/assets/downloads/' | append: file.filename | relative_url }}){:download="true"}
{%- if forloop.last == false %}, {% endif %}{% endfor %}
{%- if asset.description %}\\
{{ asset.description }}{% endif %}
{% endfor %}{% endfor %}