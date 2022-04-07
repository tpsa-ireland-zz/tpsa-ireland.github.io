<!--
<ul class="navbar">
  <li><label class="collapse" for="_1">About</label></li>
  <li><label class="collapse" for="_2">Committee</label></li>
</ul> 
<p>

<input id="_2" type="radio" name="c1"  display="none">
<div>Content 2 data</div>

<input id="_1" type="radio" name="c1" display="none">
<div class=hidable>
  {% capture index %}
  {% include_relative about/index.md %}
  {% endcapture %}
  
  {{ index | markdownify }}
</div>
</input>
</p>
--->

  {% capture index %}
  {% include_relative about/index.md %}
  {% endcapture %}
  
  {{ index | markdownify }}

<!--

### Conor Ryan - Auditor - 4th year TP
Charged with keeping the long and short term planning in order to ensure the vision and goals of the association are achieved.

### Seán S. Ffrench - Secretary - 4th year TP
Coördinates all aspects of the association, schedules events and handles other administrative tasks required as required.

### Ruaidhrí Campion - Treasurer - 3rd year TP
In charge of the associations finances and ensuring due diligence is taken.

### Jan Becker & Josh Mooney Mercadal - Lecture Series Coördinator
In charge of creating new material for our online library that's currently under construction.

### Mitchell - Weekly seminar director & founder - 4th year TP
Founder and currently running the weekly seminars.

### Pratheek Kishore - ITPO Captain - 4th year TP
In charge of preparing a team to eventually compete in the ITPO.

### Oisín O'Sullivan - Maths Student Representative - 3rd Year Maths
Represents the interest of students of pure mathematics.

### Luke Johnston - PRO
Our public relations officer, in charge of managing our social media and other public communications.
--->
