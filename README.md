[![Build Status](https://travis-ci.org/TheMagoo73/codepen-embed.svg?branch=master)](https://travis-ci.org/TheMagoo73/codepen-embed)

## &lt;codepen-embed&gt;

`codepen-embed` allows simple embedding of pens created in [Codepen](www.codepen.io "Codepen"). This element allows the height, theme and initial state of the pen to be set when it is initially rendered. Note- after initial rendering the pen cannot be manipulated using the elements properties due to the nature of the Codepen scripting that is invoked.

Example:

``` html
<codepen-embed penId="ab123r"></codepen-embed>

<coedpen-embed penId="ab123r" height="450"></codepen-embed>
```
