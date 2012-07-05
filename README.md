CleanCSS-Formatting-Templates
=============================

Custom templates for cleaning up your CSS using <a href="http://csstidy.sourceforge.net/" target="_blank">CSSTidy</a>.

Paste snippets into "Custom" field on <a href="http://www.cleancss.com/" target="_blank">CleanCSS</a>

## Standard ##

    <span class="at">|</span> <span class="format">{</span>
    |<span class="selector">|</span> <span class="format">{</span>
    |  <span class="property">|</span> <span class="value">|</span><span class="format">;</span>
    |<span class="format">}</span>|
    
    |
    <span class="format">}</span>
    
    ||</span> <span class="format">{</span>
    |

### Output ######
  
    .selector {  
      property: value;  
    }
    

## Condensed ##

    <span class=\"at\">|</span> <span class=\"format\">{ </span>|<span class=\"selector\">|</span><span class=\"format\"> {</span> |<span class=\"property\"> |</span><span class=\"value\"> |</span><span class=\"format\">;</span>|<span class=\"format\"> }</span>
    ||<span class=\"format\">}
    </span>||</span> <span class=\"format\">{</span>|

### Output ######
  
    .selector { property: value; }
    