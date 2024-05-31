This is a collection of utility apps which run in a windows based electron app.

## Apps
- Interlock Mapper - Small tool used to quickly get interlock SVG coordinates
- Config-builder - Tool used to generate and update asset configs
 
<br>
<br>


## Adding a new application or window

1.  Add new entry point in 'forge.config.js' (take note of 'name' field)
2.  Add variables in 'main.js' for the new entry points.  These use the name field above (see 'WEB APPS & EXTERNAL SITES' section).
3.  Add menu option in 'main.js' for the new application (see 'MENU' section )
4.  Create new folder in 'webapps' directory.
5.  Copy in 'app.jsx', 'index.css', 'index.html', 'mainPage.jsx', 'preload.js', 'renderer'.js' from another folder.

<br>
<br>

## Future Enhancements

1.  Add static image assets to webpack (currently can't get any images in the project to load)



## Resources

- https://www.electronjs.org/docs/latest/api/browser-window