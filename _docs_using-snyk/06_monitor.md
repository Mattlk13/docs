---
title: Monitor
---

<p>With <a href="#test"><code>test</code></a> and <a href="#protect"><code>protect</code></a>, you’re well set up to address currently known vulnerabilities. However, new vulnerabilities are constantly disclosed - which is where <code>monitor</code> comes in.</p>

<div class="highlight"><pre><code class="language-console" data-lang="console"><span class="go">cd ~/projects/myproject/</span>
<span class="go">snyk monitor</span></code></pre></div>

<p>Just before you deploy, run <code>snyk monitor</code> in your project directory. This will take a snapshot of your current dependencies, so we can notify you about newly disclosed vulnerabilities in them, or when a previously unavailable patch or upgrade path is created. If you take multiple snapshots of the same project, we will only alert you to new information about the latest one.</p>

<p>Log in and go to <a href="https://snyk.io/monitor/">snyk.io/monitor</a> to see the lastest snapshot and history of your project.</p>

<div class="screenshot">
<h3 class="screenshot__label">Example output</h3>
<pre class="code">$ snyk monitor
Captured a snapshot of this project's dependencies. Explore this snapshot at https://snyk.io/monitor/1a53f19a-f64f-44ab-b122-74ce82c1c34b
Notifications about newly disclosed vulnerabilities related to these dependencies will be emailed to you.</pre>
</div>

<h3>Monitor a Maven project with variables</h3>
<p>You can pass variables to <code>snyk monitor</code> running on Maven projects. This is useful when you want to monitor a specific profile, or pass system properties. This is done by sending flags after a double-dash option when running <code>snyk monitor</code>. Note that all flags after the double-dash option will be used as Maven flags.</p>
<p>For example, suppose you want to monitor a specific Maven profile: <code>prod</code>. Running the following will monitor this profile:</p>
<div class="highlight"><pre><code class="language-console" data-lang="console"><span class="go">snyk monitor -- -Pprod</span></code></pre></div>
<p>In another example, if you use a system property in your pom.xml file, e.g: <code>&lt;version&gt;${pkg_version}&lt;/version&gt;</code>, you can define the system property in <code>snyk monitor</code> as follows:
<div class="highlight"><pre><code class="language-console" data-lang="console"><span class="go">snyk monitor -- -Dpkg_version=1.4</span></code></pre></div>
