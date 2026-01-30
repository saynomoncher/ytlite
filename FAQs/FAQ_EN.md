# FAQ (Frequently Asked Questions)

[✓] 🇺🇸 English FAQ | [🇷🇺 ЧаВо на Русском](FAQ_RU.md) | [🇮🇹 FAQ in Italiano](FAQ_IT.md) | [🇵🇱 FAQ po Polsku](FAQ_PL.md)

<details>
  <summary>What iOS versions does YouTube Plus support?</summary>
    <p>YouTube Plus supports iOS 14 and above. <strong>However</strong>, if you're sideloading it on a non-jailbroken device, you must also consider the YouTube app's compatibility with your iOS version. Below is a list of the latest supported YouTube versions per iOS:</p>
    <li><strong>iOS 14</strong>: YouTube v19.20.2</li>
    <li><strong>iOS 15</strong>: YouTube v20.21.6</li>
    <li><strong>iOS 16+</strong>: Any version, as supported by YouTube</li>
</details>
<br>
<details>
  <summary>My iOS version is no longer supported by the latest YouTube app. What can I do?</summary>
    <p>Here are some possible options:</p>
    <li><a href="https://ios.cfw.guide/get-started/">Jailbreak your device</a>, install the latest supported YouTube version from the App Store, and <a href="http://dvntm0.github.io/#jb">install YouTube Plus as a tweak</a></li>
    <li><a href="https://ios.cfw.guide/installing-trollstore/">Install TrollStore</a>, then <a href="https://github.com/Lessica/TrollFools/releases/">TrollFools</a>, install the latest supported YouTube version from the App Store, and inject <a href="https://github.com/dayanch96/YTLite/releases/">YouTube Plus</a> using TrollFools</li>
    <li>Find a compatible IPA version online and <a href="../README.md#how-to-build-a-youtube-plus-app-using-github-actions">build a YouTube Plus app using Github actions</a></li>
</details>
<br>
<details>
  <summary>Cast stopped working on sideloaded YouTube Plus. What should I do?</summary>
    <p>Until this issue is resolved, it is recommended to use YouTube version 20.14.1 or below.</p>
</details>
<br>
<details>
  <summary>When I try to play a video, I get <strong><em>Something went wrong. Refresh and try again later.</em></strong></summary>
    <p>Before jumping to conclusions, let’s clarify a few things:</p>
    <ol>
      <li><strong>This is NOT</strong> caused by ad blocking</li>
      <li><strong>This is NOT</strong> because your account was magically flagged</li>
      <li><strong>This is NOT</strong> due to your account being secretly blacklisted</li>
    </ol>
    <br>
    <p>The issue seems to lie somewhere in the sideloading process itself, even without any tweaks applied. It might be related to an invalid or missing VisitorID or VisitorData, as suggested <a href="https://github.com/pepeloni-away/userscripts/issues/6#issuecomment-2860641610">here</a>. This error has become more frequent due to YouTube’s stricter anti-download measures.</p>
    <br>
    <p><strong>Possible temporary workaround:</strong></p>
    <ol>
      <li>Sign out of your current account (or all accounts) completely: Go to the <em>You tab → Switch account → Manage accounts on this device → Remove from this device</em></li>
      <li>Watch a few full-length videos without being signed in. Stay signed out for a few hours.</li>
      <li>Sign back into the account that was having issues</li>
    </ol>
</details>
<br>
<details>
  <summary>I can't find the Settings option to enable GitHub Actions permissions. Where is it?</summary>
    <p>If you're having trouble finding the Settings option on your forked repository, here's a detailed guide:</p>
    <ol>
      <li><strong>Make sure you're on YOUR forked repository</strong>, not the original repository. The URL should look like <code>github.com/YOURUSERNAME/YTLite</code>, not <code>github.com/dayanch96/YTLite</code></li>
      <li>At the top of your repository page, you'll see several tabs: Code, Issues, Pull requests, Actions, Projects, Wiki, Security, Insights, <strong>Settings</strong></li>
      <li>Click on the <strong>Settings</strong> tab (it's the last tab on the right)</li>
      <li>In the left sidebar, scroll down until you find the "Code and automation" section</li>
      <li>Under "Code and automation", click on <strong>Actions</strong>, then click on <strong>General</strong></li>
      <li>Scroll all the way down to the <strong>Workflow permissions</strong> section</li>
      <li>Select the <strong>Read and write permissions</strong> radio button</li>
      <li>Click the <strong>Save</strong> button</li>
    </ol>
    <p><strong>Still can't find it?</strong> You can access it directly by going to: <code>github.com/YOURUSERNAME/YTLite/settings/actions</code> (replace YOURUSERNAME with your GitHub username)</p>
    <p><strong>Note:</strong> If you don't see the Settings tab at all, it means you're viewing the original repository, not your fork. Go to your GitHub profile and find your forked copy of YTLite.</p>
</details>
