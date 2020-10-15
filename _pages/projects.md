---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

<ul>
<li><strong>Network visibility at Scale</strong> - SwitchPointer [<a href="https://www.usenix.org/system/files/conference/nsdi18/nsdi18-tammana.pdf">NSDI'18</a>], PathDump [<a href="https://www.usenix.org/conference/osdi16/technical-sessions/presentation/tammana">OSDI'16</a>] CherryPick [<a href="/publications/cherrypick.pdf">SOSR'15</a>]  SpiderMon [<a href="/publications/spidermon.pdf">SOSR'20</a>]. In collaboration with researchers from The Univ. of Edinburgh and Cornell University.</li>
</ul>
<p style="padding-left: 40px;">Network failures and performance issues in large-scale data center networks are inevitable causing major outages followed by services to go down. While troubleshooting, it is important to understand what is going on in the network through a telemetry system. However, building a telemetry system that answers a diverse set of queries is expensive and technically challenging mainly because of overhead incurred while collecting and processing a huge amount of data. To address this problem, we developed tools that look across the network entities (e.g., hosts, network core) for right division of labor to get fine-grained information on short timescales and understand what is going on in the network.</p>

<ul>
<li><strong>Cross-layer Analysis</strong> - Scout [<a href="/publications/scout.pdf">ICDCS'18</a>], P4Track [<a href="/publications/track-p4">SOSR'20</a>]. In collaboration with Cisco Systems, San Jose, USA and Princeton University, USA</li>
</ul>

<p style="padding-left: 40px;"> Toward the kind of automation we need in Software-Defined Networking (SDN), it is also important to identify bugs by doing analysis across layers present in SDN and systematically track down their root cause. Errors that lurk during either policy translation (e.g., bugs, memory overflow, hardware failure, etc) or delivery (e.g., communication problems), may lead to the incorrect deployment of a large number of low-level rules in network devices. A single error can cause serious damage such as outage to business-critical services. Understanding which part of the layer in the stack has been affected is extremely challenging as the network operators have to examine tens of thousands of low-level rules. In this work, we design and develop dataplane primitives and applications on top of the primitives which enable detection and localization of errors causing the mismatch between expected and actual network behavior.</p>



<ul>
<li><strong>Control-loop Automation</strong> - Contra [<a href="/publications/contra.pdf">NSDI'20</a>], DASH [<a href="/publications/dash-final">SOSR'20</a>]. In collaboration with researchers from Princeton and Rice University.</li>
</ul>

<p style="padding-left: 40px;"> Network control is largely derived based on measurement, but today measurement remains decoupled from the control with the human in the middle of control-loop introducing uncertainty and the possibility of errors. In contrast, operators could use fine-grained measurements to automate network control at scale. Based on this observation, my goal is to get the humans out of the way by deriving and tightly integrating measurement, inference, and control operations. Such derived operations monitor metrics relevant to a high-level policy goal (e.g., traffic engineering, routing), perform necessary analysis, and execute the decisions. In this work, I close the control-loop by synthesizing distributed low-level operations to realize high-level policy. This push is towards not just making things work correctly with debugging, but also by automating the division of labor among network entities. </p>



