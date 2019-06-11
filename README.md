# Roblox-Discord-Bot
For peoples discord sever
<script type="text/javascript">

// Google Internal Site Search script II- By JavaScriptKit.com (http://www.javascriptkit.com)
// For this and over 400+ free scripts, visit JavaScript Kit- http://www.javascriptkit.com/
// This notice must stay intact for use

function Gsitesearch(curobj){
var domainroot=curobj.domainroot[curobj.domainroot.selectedIndex].value
curobj.q.value="site:"+domainroot+" "+curobj.qfront.value
}

</script>


<form action="http://www.google.com/search" method="get" onSubmit="Gsitesearch(this)">

<p>
<input name="q" type="hidden" />
<input name="qfront" type="text" style="width: 180px" /> <input type="submit" value="Search" /><br />
Search: 
<select name="domainroot">
<option value="www.javascriptkit.com" selected="1">JavaScript Kit</option>
<option value="www.dynamicdrive.com">Dynamic Drive</option>
<option value="www.freewarejava.com">FreewareJava.com</option>
</select>
</p>

</form>

<p style="font: normal 11px Arial">This free script provided by<br />
<a href="http://www.javascriptkit.com">JavaScript Kit</a></p>
