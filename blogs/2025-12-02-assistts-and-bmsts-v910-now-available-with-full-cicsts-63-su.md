---
title: "ASSIST/TS and BMS/TS v9.1.0 Now Available with Full CICS/TS 6.3 Support"
url: "https://www.adaptigent.com/blog/assist-ts-and-bms-ts-v9-1-0-now-available-with-full-cics-ts-6-3-support/?utm_source=rss&utm_medium=rss&utm_campaign=assist-ts-and-bms-ts-v9-1-0-now-available-with-full-cics-ts-6-3-support"
date: "Tue, 02 Dec 2025 18:49:43 +0000"
author: "Kira Payne"
feed_url: "https://www.adaptigent.com/feed/"
---
<h2>What are ASSIST/TS and BMS/TS and What&#8217;s New in Version 9.1.0?</h2>
<p><strong>ASSIST/TS</strong> and <strong>BMS/TS</strong> are Adaptigent solutions designed to enhance monitoring, administration, and operational control within IBM CICS Transaction Server environments, helping teams manage high-volume transaction systems with greater visibility and stability.</p>
<p><strong><a href="https://www.adaptigent.com/wp-content/uploads/2025/11/ASSIST-V9-Product-Brochure.pdf" rel="noopener" target="_blank">ASSIST/TS</a> and <a href="https://www.adaptigent.com/wp-content/uploads/2025/11/bmsts-product-brochure.pdf" rel="noopener" target="_blank">BMS/TS</a> Version 9.1.0 </strong>introduces <strong>full compatibility with IBM CICS/TS 6.3</strong> along with a set of product refinements designed to improve stability, automation, and administrative oversight. This update strengthens day to day operations for teams running high volume CICS environments and provides new tools for monitoring, validation, and secure administration.</p>
<h2>Compatibility and Operational Foundations</h2>
<p>Version 9.1.0 includes updated support executables for CICS/TS 6.3, replacing older modules that relied on WTO macros. These updates streamline installation and keep the GLUE environment aligned with modern CICS standards. Several new status and validation features also ensure teams can verify correct initialization across regions at both startup and on demand.</p>
<h3>ASSIST/TS v9.1.0 Enhancements</h3>
<p>ASSIST/TS introduces multiple refinements focused on accuracy and easier system validation.</p>
<ul>
<li>The final GLUE warning is now captured in the ASSIST/TS GWAREA and presented through the GTAS transaction in the GTASTAT IVP. This provides clearer traceability during system checks.</li>
<li>Preference Conversion and Runtime components are now part of the standard installer, simplifying deployment and reducing manual steps.</li>
<li>The GTAMAPH Help screen for the GTAH transaction is included in the GT$FILE XMIT File and becomes available after loading the *SYSTEM Monitor.</li>
<li>Updated CSD definitions include the correct executables for CICS/TS 6.3.</li>
<li>The optional GTA$AUSR module supports UserHelp Simulation when *ADMIN UHLP=Y, ensuring expected COMMAREA behavior for American Software Transactions.</li>
</ul>
<h3>BMS/TS v9.1.0 Enhancements</h3>
<p>BMS/TS introduces new display, monitoring, and administrative improvements.</p>
<ul>
<li>Support executables are now fully aligned with CICS/TS 6.3, with WTO macro references removed from older GLUE code.</li>
<li>The online memory display has been updated for CICS/TS 6.3, correcting internal GLUE command visuals for both z/OS and VSEn environments.</li>
<li>License expiration alerts are now surfaced through message B016 when SYSPASS approaches expiration. Alerts appear on the 3270 display and OS console for automated capture.</li>
<li>Administrator HTML pages and ELUA scripts now support usernames up to 8 characters and passwords up to 100 characters.</li>
<li>The GTBMAPH Help screen for GTBH is included in the GT$FILE XMIT File and becomes accessible once the *SYSTEM Monitor is loaded.</li>
<li>TCPIP Services now include attention messages and command line controls for refresh and status checks.</li>
</ul>
<h2>Shared Enhancements for ASSIST/TS and BMS/TS</h2>
<p>Both products now send automated startup status messages when GTASTAT or GTBSTAT runs as part of the CICS PLT. Automated operations can capture initialization results immediately, and teams can recheck status at any time using the GTAS or GTBS transactions.</p>
<h2>Upgrade Information</h2>
<p>Full installation instructions, updated CSD entries, and validation procedures can be found in the product documentation. Customers with questions or upgrade requirements can review the complete release details and download the update through the <a href="https://help.gtsoftware.com/hc/en-us/articles/46678534239123-Announcing-new-release-ASSIST-TS-and-BMS-TS-Version-9-1-0">Zendesk support portal</a>.</p>
<hr />
<h2>Frequently Asked Questions</h2>
<h4>What is the purpose of ASSIST/TS and BMS/TS in a CICS environment?</h4>
<p>ASSIST/TS and BMS/TS provide monitoring, validation, and administrative capabilities that help teams manage CICS environments more effectively. They improve visibility into system behavior, simplify troubleshooting, and support consistent operations across high-volume transaction systems.</p>
<h4>What are the key benefits of upgrading to Version 9.1.0?</h4>
<p>Version 9.1.0 delivers full compatibility with IBM CICS/TS 6.3, improved installation processes, enhanced validation and tracing features, and stronger administrative controls. These updates help reduce operational overhead while improving system reliability and visibility.</p>
<h4>How do the new enhancements improve system monitoring and control?</h4>
<p>The latest enhancements introduce automated startup status messaging, improved traceability of GLUE warnings, updated memory displays, and real-time alerts for license and system status. Together, these features give administrators more immediate insight into system health and enable faster response to issues.</p>
<hr />
<p>&nbsp;</p>
<p><span id="more-371083"></span></p>
<p>Learn more about <a href="https://www.adaptigent.com/products/assist-3270-help-screens/" rel="noopener">ASSIST/TS v9.1.0</a></p>
<p>Learn more about <a href="https://www.adaptigent.com/products/bms-mapping/">BMS/TS v9.1.0</a></p>
<p>&nbsp;</p>
<p>The post <a href="https://www.adaptigent.com/blog/assist-ts-and-bms-ts-v9-1-0-now-available-with-full-cics-ts-6-3-support/">ASSIST/TS and BMS/TS v9.1.0 Now Available with Full CICS/TS 6.3 Support</a> appeared first on <a href="https://www.adaptigent.com">Adaptigent</a>.</p>
