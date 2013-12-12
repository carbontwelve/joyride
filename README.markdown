```bash
bower install jquery-joyride=https://github.com/stefansundin/joyride.git --save
```

This fork contains [one fix](https://github.com/zurb/joyride/pull/164) to the official joyride repo. The changes is in my unofficial `v2.1.1` tag.

This repo also correctly tags `v2.1.0` so it can be used with bower.

New in 2.1.1 - December 9, 2013 - **UNOFFICIAL VERSION**
* Make `scroll` possible to use on a per-tip basis. E.g: `data-options="scroll:false"`.
* Calculate tip position correctly if the tip has `position:fixed;`. Set `position: fixed !important;` on your `<li>` items.


####Carbontwelve Update

New in 2.1.2 - December 12, 2013 - **UNOFFICIAL VERSION**
* Added previous button functionality enabled via setting `prevButton: true`
* Added per tip button disabling via `data-options="disableNext:true"` and `data-options="disablePrev:true"`
* Fixed +1 error as per https://github.com/zurb/joyride/issues/165
* Added method for enabling buttons during run time via `$('#chooseID').joyride('set_button_active', { button: 'prev', enabled: false})`

Updates that I am working on

```
[x] Added Previous button
[x] Added per tip button disabling
[x] Fixed +1 error as per https://github.com/zurb/joyride/issues/165
[x] Incremented version number to v2.1.2
````

