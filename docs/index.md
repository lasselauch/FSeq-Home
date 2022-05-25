---
layout: default
title: Home
---
<!-- Header -->
  <header id="header">
    <div class="content">
      <h1><a href="#">{{ site.title }}</a></h1>
      <h2>A sequence and file browser&nbsp;<u>that just works!</u></h2>
      <ul class="actions">
        <a href="https://lasselauch.lemonsqueezy.com/checkout/buy/97df2b03-e6e2-4af8-ac66-f3286a75501c?media=0&logo=0&embed=1" class="button special icon fa-download lemonsqueezy-button">Get FSeq</a><script src="https://app.lemonsqueezy.com/js/checkout.js" defer></script>
        <li><a href="#features" class="button scrolly">Show Features</a></li>
      </ul>
    <h5 style="opacity: 50%;">{{ site.time | date_to_string: "ordinal" }} | v{{ site.version }} | <u>Windows 10 & macOS 10.15</u></h5>
    </div>
    <div class="image phone big-shadow"><img src="assets/images/fseq.png" alt="FSeq. A sequence and file browser for Windows and macOS" />
    <div class="inner">...from the developer of:&nbsp;&nbsp;<a target="_blank" rel="noopener noreferrer" href="https://aescripts.com/aec4d/">AEC4D-PRO</a></div></div>
  </header>

<!-- One -->
<section id="one" class="wrapper style2 special">
	<header class="major">
	    <h1><a href="#features" class="scrolly small-shadow">{% include logo.html %}</a></h1>
		<h2><u class="text-orange">Don't waste time searching</u> through hundreds of folders.<br />
		Have the files you're looking for under your fingertips.</h2>
	</header>
</section>

<!-- Two -->
<section id="features" class="wrapper">
	<div class="inner alt">
		<div class="content" style="text-align: center;">
			<h3 class="text-blue-gradient" >Browse Image Sequences...</h3>
			<div class="image small-shadow">{% include video-sequences.html %}</div>
			<p style="margin-top: 1.5em;"><b>Search through multiple subfolders for image sequences.</b> Detect missing or broken sequences and import/open them directly in your favorite tool.</p>
			<h3 class="text-orange-bold">Recursive and filtered search...</h3>
			<div class="image small-shadow">{% include video-filter.html %}</div>
			<p style="margin-top: 1.5em;">Imagine you could <i>"google"</i> through your project folders and entire hierarchies...<br /> <b>Search through multiple subfolders for files</b> based on a given filter. e.g. <code>*.c4d, *.hip*</code></p>
		</div>
		<section class="spotlight">
			<div class="image"><img src="assets/images/fseq-export.png" alt="" /></div>
			<div class="content">
				<h3 class="text-bold"><span class="text-blue-gradient">Open / Edit / Import</span> to your tools</h3>
				<p>Open files in their standard program, <span class="text-bold">copy/paste sequences</span> into After Effects/Nuke or view directly in your favorite viewer.<br />
				<span class="text-orange-bold">FSeq got you covered.</span></p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="assets/images/fseq-dated-folder.png" alt="" /></div>
			<div class="content">
				<h3 class="text-bold">Other neat features....</h3>
				<ul>
				<li>Create (YYMMDD) folder 👉 <span class="text-blue-gradient">"{{ site.time | date: "%y%m%d" }}"</span></li>
				<li>Light/Dark mode</li>
				<li>Simple <span class="text-orange-bold">BUT</span> useful Settings</li>
				</ul>
			</div>
		</section>
		<div class="image small-shadow"><img src="assets/images/fseq-settings.gif" alt="" /></div>
		<section class="special">
			<ul class="icons labeled">
				<li><img style="padding-right:.5em;" src="assets/icons/sequence_active.svg" height="24px"><span class="label">Browse Image Sequences</span></li>
				<li><img style="padding-right:.5em;" src="assets/icons/search_active.svg" height="24px"><span class="label">Recursive filtered search</span></li>
				<li>
				<img style="padding-right:.5em;" src="assets/icons/ae.svg" height="24px">
				<span class="label">Import to After Effects, Nuke, <span class="_50percent">Fusion ( soon )</span></span>
				</li>
				<li><img style="padding-right:.5em;" src="assets/icons/play.svg" height="24px"><span class="label">Open in default viewer</span></li>
				<li><img style="padding-right:.5em;" src="assets/icons/film_broken.svg" height="24px"><span class="label">Detect missing or broken Sequences</span></li>
				<li><img style="padding-right:.5em;" src="assets/icons/fav_active.svg" height="24px"><span class="label">Save favorite folders</span></li>
				<li><img style="padding-right:.5em;" src="assets/icons/light.svg" height="24px"><span class="label">Toggle Light/Dark</span></li>
			</ul>
		</section>
	</div>
</section>