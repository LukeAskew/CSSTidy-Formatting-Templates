CleanCSS-Formatting-Templates
=============================

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

    <span class=\"at\">|</span> <span class=\"format\">{ </span>|<span class=\"selector\">|</span><span class=\"format\">{</span> |<span class=\"property\"> |</span><span class=\"value\">|</span><span class=\"format\">;</span>|<span class=\"format\"> }</span>
    ||<span class=\"format\">}
    </span>||</span> <span class=\"format\">{</span>|

### Output ######
  
    .selector { property: value; }
    