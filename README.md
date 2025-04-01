# Tiny Theme for Micro.blog

![Tiny Theme for Micro.blog Logo](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog/blob/main/screenshot.jpg?raw=true)

## Description
Tiny Theme is developed for use with the Micro.blog platform. It is designed to be as fast as possible while still supporting all features of the platform and popular plugins. It is the easiest theme to customize on the platform and the first to use Microhooks.

**Demo and Docs:** [tiny.micro.blog](https://tiny.micro.blog).

## Credits

Tiny Theme is created and maintained by Matt Langford ([follow on Micro.blog](http://micro.blog/mtt?remote_follow=1)). If you have bug reports or feature requests, you can submit them [Github](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog) (make sure you star the repo) or [contact Matt directly](https://mattlangford.com/about/#contact).

## Do you value this theme?

Tiny Theme and its plugins are provided free of charge to Micro.blog users. I do not receive payment from Micro.blog in any way. If you'd like to help offset expenses and ensure the future of Tiny Theme and its plugins, please consider supporting its development.

<!-- Donation Widget -->
<div id="donation-widget">
  <h3>Support Themes by Matt Langford</h3>
  <p class="donation-subtext">
	Help fund ongoing work on Tiny, Sumo, and Bayou — clean, fast themes for Micro.blog.
	Your support keeps them updated and free for everyone. <em>Plus, get access to custom ChatGPT powered support.</em>
  </p>
  <div class="donation-buttons">
	<a href="https://donate.stripe.com/7sI28l5dCdvA0Mg6oq" class="donate-btn one-time">One-Time (Any Amount)</a>
	<a href="https://donate.stripe.com/dR6aER8pO2QWdz29AD" class="donate-btn recurring">Monthly $5</a>
  </div>
</div>
<style>
  #donation-widget {
	all: revert;
	border: 1px solid #ddd;
	padding: 20px;
	border-radius: 8px;
	max-width: 400px;
	margin: 20px auto;
	text-align: center;
	font-family: system-ui, sans-serif;
	background: #f9f9f9;
	animation: fadeIn 0.6s ease-in-out;
  }
  #donation-widget * {
	box-sizing: border-box;
  }
  @keyframes fadeIn {
	from { opacity: 0; transform: translateY(10px); }
	to { opacity: 1; transform: translateY(0); }
  }
  #donation-widget h3 {
	margin-top: 0;
	font-size: 1.2em;
  }
  .donation-subtext {
	font-size: 0.95em;
	color: #555;
	margin-bottom: 16px;
  }
  .donation-buttons {
	display: flex;
	flex-wrap: wrap;
	gap: 10px;
	justify-content: center;
  }
  .donate-btn {
	display: inline-block;
	padding: 10px 16px;
	text-decoration: none;
	border-radius: 6px;
	font-size: 0.95em;
	min-width: 130px;
	text-align: center;
	color: #fff;
	background-color: currentColor;
	transition: background 0.3s ease, transform 0.2s ease;
	cursor: pointer;
  }
  .donate-btn:hover {
	transform: scale(1.05);
  }
  .one-time { background: #635bff; }
  .recurring { background: #00bfa5; }
  .one-time:hover { background: #5146ff; }
  .recurring:hover { background: #009e88; }
</style>
<!-- End Donation Widget -->
