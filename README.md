<h1 align="center">
  <img src="https://rawtherapee.com/images/rt-logo-white.svg" alt="Rawtherapee">
  <br />
  Rawtherapee
</h1>

<p align="center">RawTherapee is a powerful, cross-platform raw photo processing program, released as libre software under the GNU General Public License Version 3. It is written mostly in C++ using a GTK+ front-end. It uses a patched version of dcraw for reading raw files, with an in-house solution which adds the highest quality support for certain camera models unsupported by dcraw and enhances the accuracy of certain raw files already supported by dcraw. It is notable for the advanced control it gives the user over the demosaicing and development process.</p>

<p align="center">
<a href="https://snapcraft.io/rawtherapee">
  <img alt="enpass" src="https://snapcraft.io/rawtherapee/badge.svg" />
</a>
<a href="https://snapcraft.io/rawtherapee">
  <img alt="enpass" src="https://snapcraft.io/rawtherapee/trending.svg?name=0" />
</a>
</p>



<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Install

    sudo snap install rawtherapee

## Snap configuration

Rawtherapee snap package by default does not have access to removable media like usb disks. If you want to enable this, run the following command.
    sudo snap connect rawtherapee:removable-media


([Don't have snapd installed?](https://snapcraft.io/docs/core/install))
