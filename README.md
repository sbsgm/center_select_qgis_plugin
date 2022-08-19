# center_select_qgis_plugin
Plugin for centering and selecting features in Qgis


### Installation instructions

1. Make sure you have pb tool install on your system python or environment.
```
pip install pb-tool
```
2. Search for the plugin_path on the pb_tool.cfg file and modify if needed.
```
# Full path to where you want your plugin directory copied. If empty,
# the QGIS default path will be used. Don't include the plugin name in
# the path.
plugin_path: your/home/path/to/QGIS/user/python/plugins/directory

```
3. Open a terminal on the center_select folder.
4. Deploy the plugin to QGIS plugin path directory.
```
pb_tool deploy
```
