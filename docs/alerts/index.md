---
slug: /alerts
title: Sumo Logic Alerts
sidebar_label: Alerts
description: Create Monitors and Scheduled Searches to notify users of changing conditions.
---

import useBaseUrl from '@docusaurus/useBaseUrl';

<img src={useBaseUrl('img/icons/alerts.png')} alt="icon" width="50"/>

Sumo Logic offers several alerting features. See the topics below for details on how they work and your configuration options.

<div className="box-wrapper" markdown="1">
<div className="box box1 card">
  <div className="container">
  <h4><a href="/docs/alerts/monitors">Monitors</a></h4>
  <p>Configure alerting policies notify you about critical changes or issues affecting your production applications.</p>
  </div>
</div>
<div className="box box2 card">
  <div className="container">
  <h4><a href="/docs/alerts/scheduled-searches">Scheduled Searches</a></h4>
  <p>Create saved searches that are executed continuously on a schedule you set, monitoring your stack.</p>
  </div>
</div>
</div>

<div className="box boxwidebottom card">
  <div className="container">
  <h4><a href="/docs/alerts/difference-from-scheduled-searches">Monitors vs. Scheduled Searches</a></h4>
  <p>Learn about the feature differences between Monitors and Scheduled Searches.</p>
  </div>
</div>

:::note
You can configure Sumo Logic Monitors using [Terraform modules](https://registry.terraform.io/providers/SumoLogic/sumologic/latest/docs/resources/monitor).
:::
