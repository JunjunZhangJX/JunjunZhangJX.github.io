---
layout: "post"
title: "This is the new title"
---

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://github.com/JunjunZhangJX/JunjunZhangJX.github.io/blob/master/assets/images/Junjun1_CV.pdf"}},
			metaData:{fileName: "Junjun1_CV.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>
  
  

