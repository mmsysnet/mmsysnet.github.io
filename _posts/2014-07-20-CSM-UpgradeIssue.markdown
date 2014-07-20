---
layout: post
title: "ePO Manual Update"
---

Basically, ePO is designed to update automatically via McAfee FTP or McAfee website. But we may need to update manually in some situation.

In this scenario, our client do not want to connect their ePO Server to the internet. So, we have to configure the ePO to update the DAT (Virus Definition File) file manually. To do this, McAfee Agent is the most important to understand between the ePO server and it’s client workstation. Here is the step-by-step about how to update the DAT file locally.


**Engine**

First, you need to install and run the Engine. The Engine can be download from McAfee Website.

[<a href="http://www.mcafee.com/apps/downloads/security-updates/security-updates.aspx" target="_blank">DAT Engine</a>]

<b>McAfee Agent</b>

McAfee Agent is to provides policy enforcement, product deployments and updates, and reporting on your managed systems. Client workstations need to install Agent to communicate with ePO Server for virus definition update. <b></b>

<b>Generate Agent for Client</b>

To generate the Agent, go to Menu &gt; System &gt; System Tree.

<a href="http://mmsysnet.files.wordpress.com/2013/04/agent1.png"><img style="background-image: none; padding-left: 0; padding-right: 0; display: inline; padding-top: 0; border-width: 0;" title="agent1" src="http://mmsysnet.files.wordpress.com/2013/04/agent1_thumb.png" alt="agent1" width="609" height="381" border="0" /></a>

Under the System Tree Page, go to “System Tree Action &gt; New System” at the lower left corner of the page.

<a href="http://mmsysnet.files.wordpress.com/2013/04/agent2.png"><img style="background-image: none; padding-left: 0; padding-right: 0; display: inline; padding-top: 0; border-width: 0;" title="agent2" src="http://mmsysnet.files.wordpress.com/2013/04/agent2_thumb.png" alt="agent2" width="611" height="383" border="0" /></a>

In the “New System” Page, choose “Create and download agent installation package”. Uncheck “Use Credentials” and click “OK”.

<a href="http://mmsysnet.files.wordpress.com/2013/04/image2.png"><img style="background-image: none; padding-left: 0; padding-right: 0; display: inline; padding-top: 0; border-width: 0;" title="image" src="http://mmsysnet.files.wordpress.com/2013/04/image_thumb2.png" alt="image" width="494" height="220" border="0" /></a>

Next page, click on the <b>FramePkg</b> and save in your system.

<a href="http://mmsysnet.files.wordpress.com/2013/04/image3.png"><img style="background-image: none; padding-left: 0; padding-right: 0; display: inline; padding-top: 0; border-width: 0;" title="image" src="http://mmsysnet.files.wordpress.com/2013/04/image_thumb3.png" alt="image" width="410" height="114" border="0" /></a>

<b>Manually Download &amp; Update the Virus Definition File (DAT)</b>
<ol>
	<li>Go to the McAfee Website from the following links</li>
</ol>
<a href="http://www.mcafee.com/apps/downloads/security-updates/security-updates.aspx">http://www.mcafee.com/apps/downloads/security-updates/security-updates.aspx</a>

<a href="http://mmsysnet.files.wordpress.com/2013/04/image4.png"><img style="background-image: none; padding-left: 0; padding-right: 0; display: inline; padding-top: 0; border-width: 0;" title="image" src="http://mmsysnet.files.wordpress.com/2013/04/image_thumb4.png" alt="image" width="434" height="190" border="0" /></a>
<div id="__tbSetup"></div>


![](https://528dee25940c6567ca66c19c0f4de0048e296760.googledrive.com/host/0B_eZ_lamvEnUVlE3LUlOc1FpVlU/e20.jpg)