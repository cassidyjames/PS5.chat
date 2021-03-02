# PS5.chat

<div class="not-ps" markdown="1">
This site enables quick access to the built-in PlayStation 5 web browser. Just send a message to someone with [PS5.chat](https://ps5.chat) in it, and then you both can open the Internet browser from the message.
</div>

<div class="ps-large" markdown="1">
Select **Options** →  **Pin to Side** to keep pinned. Press ![PS](ps.svg) to switch away instead of _○_, which sometimes goes back.
</div>

<div class="ps-small" markdown="1">Press ![PS](ps.svg) and choose **Internet browser** to return to this screen.
</div>

- [DuckDuckGo Search](https://duckduckgo.com/?kae=d&kt=n&ks=t&k7=17181d&ko=s&ka=n&k18=1&t=elementary)
- [E.ggTimer](https://e.ggtimer.com/)
- [Twitch](https://twitch.tv)
- [Twitter](https://twitter.com)
- [YouTube](https://youtube.com)
- [Donate](https://cassidyjames.com/pay)

<!--
- [Local Development](http://192.168.86.76:4000)
-->

## More tips:

DRM is not enabled, so music streaming services (e.g. YouTube Music) won't work.

Settings can be found in the PS5 **Settings** → **System** → **Web Browser**.

<!--
_△_ _○_ _×_ _□_
-->

<style>
:root {
  --bg: #17181d;
  --fg: white;
  --faint: rgba(255, 255, 255, 0.1);
  --font-size: 24px;
}

:root,
html,
body {
  background-color: var(--bg);
  color: var(--fg);
  font-size: var(--font-size);
  font-weight: 100;
}

.hidden {
  display: none;
}

.not-ps {
  background: #fff394;
  color: #ad5f00;
  margin: 2em auto;
  padding: 1em;
}

.not-ps p {
  font-size: 1em;
  margin: 0;
}

.not-ps a {
  color: inherit;
  font-weight: bold;
}

@media (min-width: 641px) {
  .ps-small {
    display: none;
  }
}

@media (max-width: 640px) {
  .ps-large {
    display: none;
  }
}

.markdown-body h1,
.markdown-body h2 {
  border-bottom-color: var(--faint);
}

.markdown-body ul {
  margin: 3em auto;
  padding: 0;
}

li {
  list-style: none;
}

p {
  font-size: var(--font-size);
}

li a {
  border: 1px solid transparent;
  border-bottom-color: var(--faint);
  color: inherit;
  display: inline-block;
  font-size: var(--font-size);
  padding: 0.67em;
  transition: all 150ms ease;
  width: 100%;
}

em {
  background: var(--fg);
  border-radius: 999px;
  color: var(--bg);
  display: inline-block;
  font-style: normal;
  font-weight: 900;
  line-height: 1;
  opacity: 0.75;
  text-align: center;
  text-shadow:
    1px 0 var(--bg),
    -1px 0 var(--bg),
    0 1px var(--bg),
    0 -1px var(--bg);
  vertical-align: text-bottom;
  margin: 0 0.25em;
  min-width: 1.5rem;
  padding: 0.25em;
}

li:last-child a {
  border-bottom-color: transparent;
}

li:last-child a:hover {
  border-bottom-color: var(--fg);
}

a:hover {
  background: var(--faint);
  border-radius: 0.125em;
  border-color: var(--fg);
  text-decoration: none;
}

img[alt=PS] {
  background: white;
  border-radius: 999px;
  margin: 0 0.25em;
  opacity: 0.75;
  padding: 0.125em;
  vertical-align: text-bottom;
  width: 1.25em;
}
</style>

<script>
if (navigator.userAgent.indexOf("PlayStation") > -1) {
  document.getElementsByClassName("not-ps")[0].classList.add("hidden");
}
</script>
