---
layout: page
title: CV
permalink: /cv/
---

You can download my CV: [Download CV](/assets/CV.pdf){:target="_blank"}

<p>If your download does not start automatically, <a id="manual-download" href="/assets/CV.pdf" download>click here to download the CV</a>.</p>

<script>
// Try to trigger download automatically. Most desktop browsers will respect the `download` attribute
// for same-origin files. If automatic download isn't possible, we fall back to navigating to the PDF.
(function(){
  var a = document.getElementById('manual-download');
  if(!a) return;
  try {
	// Attempt a programmatic click to start download
	a.click();
  } catch(e) {
	// ignore
  }
  // After a short delay, navigate to the PDF so mobile browsers that don't support programmatic download
  // will at least open the PDF for the user (they can then use the browser's download UI).
  setTimeout(function(){ window.location = '/assets/CV.pdf'; }, 800);
})();
</script>


