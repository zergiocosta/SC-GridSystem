# SC Grid System 
#### Made with SASS 

A WordPress plugin where you can manage column sizes with shortcodes.
It is a 12 columns Grid System (from 1 to 12, where 12 is 100% width)


## To specify the column size of your element, just follow the exemple bellow

```css
[sc_gs_col_6]
	{{content}}
[/sc_gs_col_6]
/* If you want to use the 6-column grid, for example */

[sc_gs_col_12]
	{{content}}
[/sc_gs_col_12]
/* If you want to use the 12-column grid, for example */

/* Pattern */
[sc_gs_col_{n}]
	{{content}}
[/sc_gs_col_{n}]
/* Where {n} is your column size from 1 to 12 and {{content}} could be whatever you want to show inside the column element */
```


## License
[![WTFPL](wtfpl-badge.png "WTFPL")](https://github.com/zergiocosta/SC-GridSystem/blob/master/LICENSE)
