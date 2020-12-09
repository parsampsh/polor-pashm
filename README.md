# polor-pashm
polor is simple **Terminal Color** library for _Pashmak_ programming language.

# preview
Version 1
```html
import 'polor.pashm'

use polor

println $FgBlue + 'Pashmak'
println $BgHiGreen + $FgHiBlack + 'programming' + $Reset
println $Bold + 'language'
```

Version 2 
```html
import 'polor.pashm'

use polor

println $ftc->['FgBlue'] + 'Pashmak'
println $bhitc->['BgHiGreen'] + $fhitc->['FgHiBlack'] + 'programming' + $ba->['>
println $ba->['Bold'] + 'language'
```

In the new update, Pashmak Structures were added and we also updated this library.
**Warning: Note that in the new version of this library, the speed has dropped very slowly**

the output is:
<div>
  <img 
    src="/data/polor-preview.png"
    alt="polor is a simple Terminal Color library for Pashmak programming language"
    style=""
  />
</div>

# Wiki
<p>For more examples click <a href="https://github.com/sami2020pro/polor-pashm/wiki">here</a></p>
