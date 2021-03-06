---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: https://github.com/shirosaidev/diskover/blob/master/docs/_pages/heatmap.png?raw=true
  cta_label: "<i class='fa fa-download' aria-hidden='true'></i> Install Now"
  cta_url: "https://github.com/shirosaidev/diskover/releases/latest"
  caption:
excerpt: '<img src="https://github.com/shirosaidev/diskover/raw/master/docs/diskover.png?raw=true" style="width: 183px; float: left; margin: 0px 30px 10px 0px;">File system crawler, storage search engine and analytics software powered by Elasticsearch to help visualize and manage your disk space usage.<br /> <small><a href="https://github.com/shirosaidev/diskover/releases/tag/v1.5.0-rc8">Latest release v1.5.0-rc8</a></small><br /><br />
{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=shirosaidev&repo=diskover&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=shirosaidev&repo=diskover&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
feature_row:
  - url: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-filetree-screenshot.png?raw=true
    image_path: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-filetree-screenshot.png?raw=true
    alt: "file system crawler"
    title: "File System Crawler"
    excerpt: "diskover crawls your storage servers over nfs/smb and scrapes file/directory meta data into Elasticsearch."
    url: "https://github.com/shirosaidev/diskover"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - url: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-dashboard-screenshot.png?raw=true
    image_path: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-dashboard-screenshot.png?raw=true
    alt: "analyze metadata"
    title: "Visualize Your Storage"
    excerpt: "Identify old and unused files and give better insights into data change, duplicate files and wasted disk space."
    url: "https://github.com/shirosaidev/diskover"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - url: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-treemap-screenshot.png?raw=true
    image_path: https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-treemap-screenshot.png?raw=true
    alt: "open-source"
    title: "Open Source"
    excerpt: "Built using Python + PHP + HTML5 + Javascript + D3.js. diskover runs on Linux and macOS."
    url: "https://github.com/shirosaidev/diskover"
    btn_class: "btn--primary"
    btn_label: "Learn More"
github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=shirosaidev&repo=diskover&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=shirosaidev&repo=diskover&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
intro:
  - excerpt: 'Support the development&nbsp;[<i class="fa fa-heart" aria-hidden="true"></i> Sponsor Patreon](https://www.patreon.com/diskover){: .btn .btn--primary}&nbsp;[<i class="fa fa-credit-card" aria-hidden="true"></i> Donate PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CLF223XAS4W72){: .btn .btn--primary}&nbsp;[<i class="fa fa-shopping-cart" aria-hidden="true"></i> Buy PRO](https://www.patreon.com/diskover){: .btn .btn--primary}'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<p><strong>diskover</strong> is an open source file system crawler and disk usage software that uses <strong>Elasticsearch</strong> to index and manage data across heterogeneous storage systems. Using diskover, you are able to more effectively search and organize files and system administrators are able to manage storage infrastructure, efficiently provision storage, monitor and report on storage use, and effectively make decisions about new infrastructure purchases.</p>
<p>As the amount of file data generated by business' continues to expand, the stress on expensive storage infrastructure, users and system administrators, and IT budgets continues to grow.</p>
<p>Using diskover, users can identify old and unused files and give better insights into data change, file duplication and wasted space.</p>
<div align="center"><img src="https://github.com/shirosaidev/diskover/blob/master/docs/diskover-diagram1-dark.png?raw=true" alt="diskover diagram" width="800" height="525"/></div>
<h2>diskover community edition vs PRO</h2>
<table border="0">
  <tr>
    <td>&nbsp;</td><td><strong>diskover community edition</strong></td><td><strong>diskover PRO</strong></td>
  </tr>
  <tr>
    <td>max worker bots</td><td>8</td><td>unlimited</td>
  </tr>
  <tr>
    <td>duplicate file finder</td><td>no</td><td>yes</td>
  </tr>
  <tr>
    <td>multiple index data comparison</td><td>no</td><td>yes</td>
  </tr>
  <tr>
    <td>vmware/vbox ova's</td><td>no</td><td>yes</td>
  </tr>
  <tr>
    <td>open source</td><td>yes</td><td>yes</td>
  </tr>
</table>
<p>To purchase a license for diskover PRO, please visit Patreon for <a href="https://www.patreon.com/diskover">pricing and license options</a>. Licenses can also be purched using PayPal.</p>
<div align="center">diskover PRO hot dirs analytics screenshot<br /><img src="https://github.com/shirosaidev/diskover-web/blob/master/docs/diskover-web-hotdirs-screenshot.png?raw=true" alt="diskover-web hotdirs" width="800" /></div>
<h2>Works with Amazon AWS or fully hosted on diskover-cloud</h2>
<p><img src="https://github.com/shirosaidev/diskover/blob/master/docs/_pages/amazon_web_services_logo_aws.jpg?raw=true" alt="diskover aws" align="left" width="178" height="117" hspace="20"/>diskover works on AWS using EC2 and Elasticsearch instances so you can get up and running quickly in the cloud. Crawl bots can run locally and push file system meta data into your AWS Elasticsearch. From there you can use EC2 to run diskover-web to view your data. To have all this set up for you, there is the option for fully managed diskover-cloud on AWS.</p>
<h2>diskover ova's for VMware, etc</h2>
<p><img src="https://github.com/shirosaidev/diskover/blob/master/docs/_pages/vmware_logo_1.png?raw=true" alt="diskover vmware" align="left" width="156" height="153" hspace="20"/>If you want to get diskover up and running quickly and easily, please <a href="mailto:cpark16@gmail.com">contact me</a> for ova pricing and download link. The ova files can be imported into VMware esxi, etc to get you crawling your storage in less than an hour.</p>
<br/>
<h2>diskover multi-threaded crawling (gource videos)</h2>
{::nomarkdown}<iframe width="560" height="315" src="https://www.youtube.com/embed/qKLJjZ0TMqA?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>{:/nomarkdown}<br />
{::nomarkdown}<iframe width="560" height="315" src="https://www.youtube.com/embed/InlfK8GQ-kM?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>{:/nomarkdown}
