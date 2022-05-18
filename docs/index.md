---
layout: default
title: Home
---

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
				<p>Open files in their standard program, <span class="text-bold">copy/paste sequences</span> into After Effects/Nuke or view directly in your favorite viewer.
				<span class="text-orange-bold">Fseq got you covered.</span></p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="assets/images/fseq-dated-folder.png" alt="" /></div>
			<div class="content">
				<h3 class="text-bold">Other neat features....</h3>
				<ul>
				<li>Create (YYMMDD) folder 🠒 <span class="text-blue-gradient">"{{ site.time | date: "%y%m%d" }}"</span></li>
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