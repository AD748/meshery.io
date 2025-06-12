---
permalink: /community/handbook/security-vulnerabilities/
title: Security Vulnerabilities
description: Reporting security vulnerabilities in Meshery.
layout: default
---

<div class="page-header-section">
    <h1 style="text-align: center;">Security Vulnerabilities</h1>
    <p style="text-align: center;" >Report Meshery security issues responsibly — we investigate every report.</p>
</div>

<div class="page-section">
    <div class="container">
        <div class="content">
            <p>We are very grateful to the security researchers and users that report security vulnerabilities. We investigate each report thoroughly.</p>
            <p>To make a report, send an email to the private <a href="mailto: security@meshery.io">security@meshery.io</a>  mailing list with the vulnerability details. For normal product bugs unrelated to latent security vulnerabilities, please head to the appropriate repository and submit a <a href="https://github.com/meshery/meshery.io/issues/new/choose">new issue</a> .</p>
            <p>Note that the Meshery community spans two GitHub organizations:</p>
            <ul class="project-org-list">
                <li>
                    <a href="https://github.com/meshery">
                        <img
                            src="/apple-touch-icon-precomposed.png"
                            alt="Meshery organization logo"/>
                        Meshery
                    </a>
                        - established community with MeshMates, a catch-all org.
                </li>
                <li>
                    <a href="https://github.com/meshery/meshery.io">
                        <img
                            src="/apple-touch-icon-precomposed.png"
                            alt="Meshery.io site logo"
                        />
                        Meshery.io
                    </a>
                        - Site for Meshery, the cloud native manager.
                </li>
            </ul>
            <p>You can find the list of all the Meshery project repositories <a href="https://github.com/meshery">here</a></p>
            <h3>When to report a security vulnerability?</h3>
            <p>Send us a report whenever you:</p>
            <ul>
                <li>Think Meshery projects have a potential security vulnerability.</li>
                <li>Are unsure whether or how a vulnerability affects the project.</li>
                <li>Think a vulnerability is present in another project that Meshery projects depends on (Docker for example).</li>
            </ul>
            <h3>When not to report a security vulnerability?</h3>
            <p>Don't send a vulnerability report if:</p>
            <ul>
                <li>You need help tuning Meshery project components for security.</li>
                <li>You need help applying security related updates.</li>
                <li>Your issue is not security related.</li>
            </ul>
            <p>Instead, join the community <a href="https://slack.meshery.io/">Slack</a>  and ask questions.</p>
            <h3>Evaluation</h3>
            <p>The Meshery team acknowledges and analyzes each vulnerability report within 10 working days.</p>
            <p>Any vulnerability information you share with the Meshery team stays within the respective Meshery project. We don't disseminate the information to other projects. We only share the information as needed to fix the issue.</p>
            <p>We keep the reporter updated as the status of the security issue is addressed.</p>
            <h3>Fixing the issue</h3>
            <p>Once a security vulnerability has been fully characterized, a fix is developed by the Meshery team. The development and testing for the fix happens in a private GitHub repository in order to prevent premature disclosure of the vulnerability.</p>
            <h3>Early disclosures</h3>
            <p>The Meshery project maintains a mailing list for private early disclosure of security vulnerabilities. The list is used to provide actionable information to close Meshery partners. The list is not intended for individuals to find out about security issues.</p>
            <h3>Public disclosures</h3>
            <p>On the day chosen for public disclosure, a sequence of activities takes place as quickly as possible:</p>
            <ul>
                <li>Changes are merged from the private GitHub repository holding the fix into the appropriate set of public branches.
                </li>
                <li>Meshery team ensures all necessary binaries are promptly built and published.</li>
                <li>Once the binaries are available, an announcement is sent out on the following channels:
                    <ul>
                        <li>The <a href="https://meshery.io/blog/">Meshery blog</a></li>
                        <li>The <a href="https://x.com/mesheryio">Meshery Twitter feed</a></li>
                        <li>The <a href="https://mesheryio.slack.com/archives/CSF3PSZT9">#announcements</a> channel on community <a href="https://slack.meshery.io/">Slack</a></li>
                    </ul>
                </li>
            </ul>
            <p>As much as possible this announcement will be actionable, and include any mitigating steps customers can take prior to upgrading to a fixed version.</p>
            <!--Security Slam-->
            <div class="blog-post-section">
                <div class="blog-post-header">
                    <h2><a href="/blog/2025/03/2025-03-27-meshery-at-kubecon-eu-2025-security-slam/"> Meshery to Participate in Security Slam</a></h2>
                </div>
                    <a href="/blog/category/kubecon/" class="btn" > kubecon </a>
                    &nbsp; <a href="/blog/category/events/" class="btn" > events </a>
                    &nbsp; <a href="/blog/category/security/" class="btn" > security </a>
                <img class="featured-image" src="/assets/images/posts/2025-03-27-meshery-at-kubecon-eu-2025/kubecon-eu-2025.png" alt="Meshery at KubeCon EU 2025 Security Slam announcement banner">
                <div class="blog-post-excerpt">
                    <p>We're thrilled to announce that Meshery has been selected as one of four CNCF projects to take part in the Security Slam at KubeCon EU 2025! This is a fantastic opportunity for the Meshery community to come together and make significant strides in enhancing the security of our project.</p>
                </div>
                <a href="/blog/2025/03/2025-03-27-meshery-at-kubecon-eu-2025-security-slam/" class="btn" > Read More </a>
            </div>
            <h2>List of Announced Vulnerabilities:</h2>
            <div class="table-container">
                <table>
                    <thead>
                        <tr>
                            <th>DATE ANNOUNCED</th>
                            <th>CVE ID</th>
                            <th>DESCRIPTION</th>
                            <th>AFFECTED COMPONENT</th>
                            <th>VULNERABLE VERSION</th>
                            <th>PATCHED VERSION</th>
                            <th>FIX DETAILS</th>
                            <th>LINKS</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>2021-04-28</td>
                            <td>CVE-2021-31856</td>
                            <td><!-- TODO: Add actual description for CVE-2021-31856 -->A detailed description of the vulnerability and its impact should be provided here.</td>
                            <td>Dummy</td>
                            <td>Dummy</td>
                            <td>Dummy</td>
                            <td><a href="#link-to-fix-pull-request">fix pull</a></td> <!-- TODO: Update with actual link -->
                            <td><a href="#link-to-mitre">mitre</a>, <a href="#link-to-details">details</a></td> <!-- TODO: Update with actual links -->
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</div>

<script>
    if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
      document.body.classList.add('dark-mode');
    }
</script>