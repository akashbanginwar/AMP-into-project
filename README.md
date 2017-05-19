# AMP-into-project
Accelerated Mobile Pages using AMP documentation

AMP HTML documents MUST:


Start with the doctype <!doctype html>.
Contain a top-level <html ⚡> tag (<html amp> is accepted as well).
Contain <head> and <body> tags (They are optional in HTML).
Contain a <meta charset="utf-8"> tag as the first child of their <head> tag.
Contain a <script async src="https://cdn.ampproject.org/v0.js"></script> tag as the second child of their <head> tag (this includes and loads the AMP JS library).
Contain a <link rel="canonical" href="$SOME_URL" /> tag inside their <head> tag that points to the regular HTML version of the AMP HTML document or to itself if no such HTML version exists.
Contain a <meta name="viewport" content="width=device-width,minimum-scale=1"> tag inside their <head> tag. It's also recommended to include initial-scale=1.
Contain the following in their <head> tag:
<style amp-boilerplate>body
    {-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}
    @-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    @-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    @-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    @-o-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    @keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    </style><noscript>
    <style amp-boilerplate>body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}
    </style></noscript>
