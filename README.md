# ![BDNS:](https://blockchain-dns.info/img/ext/icon-32.png) Blockchain-DNS

B-DNS addon for Chrome lets you surf Namecoin and Emercoin domains:

* *.bit* - such as http://nx.bit
* *.lib* - such as http://rutracker.lib, http://flibusta.lib
* *.emc*
* *.bazar*
* *.coin*

...as well as custom [OpenNIC TLDs](https://wiki.opennic.org/opennic/dot) - *.bbs*, *.chan* and a bunch of others.

-------

**Attention: Chrome requires `http://` prefix or a pathname**

If you type an address like `nx.bit` into the address bar and hit Enter - you will be taken to Google search page. You have to type `http://nx.bit` or add a slash at the end: `nx.bit/`. See [this issue for details](https://github.com/B-DNS/Chrome/issues/2).

-------

![Chrome screenshot](https://blockchain-dns.info/img/ext/chrome-nx.bit-640x400.png)

-------

B-DNS is a public web resolver. Read more at https://blockchain-dns.info (API description is [here](https://github.com/B-DNS/Resolver)).

[There](https://blockchain-dns.info/explorer/) you will also find a catalogue of existing domains in the supported blockchain name systems.

...And we're also [giving out NMC/EMC domains for free](https://blockchain-dns.info/giveaway).

--------

## Installing Debug Version

You can permanently load a debug (unsigned) extension into Chrome, i.e. it will survive restart.

**Disable existing BDNS extension, if installed, before installing its debug version!**

1. Open Extensions tab: click on the button with 3 dots, open _More tools_ submenu, then click on _Extensions_ item.
2. In the tab that has just opened, tick the checkbox named _Developer mode_, then click on _Load unpacked extension_ button that should have appeared.
3. Select the extension's directory. The directory should contain all files from the [Chrome GitHub repository](https://github.com/B-DNS/Chrome) and all PNG images from [this repository](https://github.com/B-DNS/Logos).
4. Once the open dialog is submitted, a new extension should appear in the Extensions tab. Click on _background page_ link (next to _Inspect views_) - this will open console window.
5. In a regular Chrome tab, navigate to a resource in question (e.g. `nx.bit/`) - you will notice the console window is populated with lines. Select them and copy to clipboard, or use the context menu's _Save as_ command to produce a log file. Then submit the log along with your [GitHub issue](https://github.com/B-DNS/Chrome/issues/new).

![Step 1](https://blockchain-dns.info/img/debug-load/chrome-1.png)
![Step 2](https://blockchain-dns.info/img/debug-load/chrome-2.png)
![Step 3](https://blockchain-dns.info/img/debug-load/chrome-3.png)
![Step 4](https://blockchain-dns.info/img/debug-load/chrome-4.png)
