---
colorSchema: light
favicon: /public/images/diracx-logo-square.png
color: orange-light
layout: cover
routerMode: hash
title: The LHCb case
theme: neversink 
neversink_string: "The 11th DIRAC Users' Workshop"
---

One more workshop conclusions

**Federico Stagni** <Email v="federico.stagni@cern.ch" />
**Andrei Tsaregorodtsev** <Email v="atsareg@in2p3.fr" />

September 19th 2025
__ <a href="https://indico.cern.ch/e/duw11" class="ns-c-iconlink"><mdi-open-in-new />The 11th DIRAC Users' Workshop</a>  


---
layout: top-title
color: gray-light
align: c
title: what
---

:: title ::

# what we did

:: content ::

We have been around 15 (sometimes 20) in the room, and another dozen online.

3 days of "hackathon" and presentations. Results: 
- we did not hack much at the end
- we certainly discussed
- we sorted specific issues
- in general, seems to me we did useful work

we will have more hacking (probably discussing) tomorrow

---
layout: top-title
color: gray-light
align: c
title: what2
---

:: title ::

# We also

:: content ::

- for most of us, we visited a new city and a new country
- had a good time
- (from a europen perspective) we ate well and way too much


---
layout: top-title
color: gray-light
align: c
title: take-aways
---

:: title ::

# Few take-aways

:: content ::

- we have again a site, [https://diracgrid.org](diracgrid.org), now including DIRAC and diracx docs, and the helm chart
  - we should, from now on, stick to that as "the" reference for DIRAC(X)
- DiracX landed
- we (the so-called "experts") are still failing to explain what are the best practices for using DIRAC



---
layout: top-title
color: gray-light
align: c
title: functions
---

:: title ::

# What is DiracX used for in LHCb?

:: content ::

- JobStateUpdate
- ISBs
- lhcbdiracx-web




---
layout: top-title
color: gray-light
align: c
title: IT
---

:: title ::

# Standing on the shoulders

:: content ::

CERN IT provides all needed services:

- MySQL 8.4 [on-demand](https://dbod-user-guide.web.cern.ch/)
- [IaM](https://lhcb-auth.cern.ch/)
- [Opensearch](https://opensearch.docs.cern.ch/)
- [Openshift](https://paas.docs.cern.ch) for hosting k8 projects
- [Object storage](https://clouddocs.web.cern.ch/object_store/index.html) compatible with S3, built upon Ceph
- [Grafana instance](https://monit.docs.cern.ch/grafana/description/) 
- OTEL

Each of the above services come its with own monitoring (and sometimes we have look at it)


---
layout: top-title
color: gray-light
align: c
title: chart
---

:: title ::

# The helm chart

:: content ::

show lhcbdiracx chart


---
layout: top-title
color: gray-light
align: c
title: client
---

:: title ::

# The client

:: content ::

how the client is installed and deployed on CVMFS

including which env variables?


---
layout: top-title
color: gray-light
align: c
title: LHCbDiracX
---

:: title ::

# lhcbdiracx

:: content ::


---
layout: top-title
color: gray-light
align: c
title: LHCbDiracXWeb
---

:: title ::

# lhcbdiracx-web

:: content ::


---
layout: top-title
color: gray-light
align: c
title: monitoring
---

:: title ::

# monitoring

:: content ::


---
layout: top-title
color: gray-light
align: c
title: OTEL
---

:: title ::

# infrastructure monitoring via OpenTelemetry

:: content ::


---
layout: top-title
color: gray-light
align: c
title: LHCbDIRACCommon
---

:: title ::

# LHCbDIRACCommon

:: content :: 


---
layout: top-title
color: gray-light
align: c
title: CI
---

:: title ::

# What we do in gitlab-CI

:: content :: 


---
layout: top-title-two-cols
align: cm-cm-lm
color: orange-light
columns: is-4
title: summary
--- 
:: title ::

# Summary

:: left :: 

![LHCb](/public/images/LHCb.png)


:: right ::

- We have been running (LHCb)DiracX(-Web) in production since April
- It works!
  - but we relied heavily on the internal knowledge
- LHCb have always been and will keep being a Dirac(X) supporter


---
layout: credits
color: navy
loop: true
speed: 1.0
title: credits/people
---


<div class="grid text-size-4 grid-cols-3 w-3/4 gap-y-10 auto-rows-min ml-auto mr-auto">
    <div class="grid-item text-center mr-0- col-span-3">
        <strong>People</strong><br> 
    </div>
    <div class="grid-item text-right mr-4 col-span-1">
        <strong>Current Developers, maintainers, supporters</strong>
    </div>
    <div class="grid-item col-span-2">
        Chris Burr <i>CERN</i><br/>
        Christophe Haen <i>CERN</i><br/>
        Alexandre Boyer <i>CERN</i><br/>
        Ryunosuke O'Neil (Wada) <i>CERN</i><br/>
        Federico Stagni <i>CERN</i><br/>
        Vladimir Romanovskiy <i>Cincinnati</i>
    </div>
</div>

&nbsp;
&nbsp;
&nbsp;

<div class="grid-item col-span-3 text-center mt-180px mb-auto font-size-1.5rem">
    <strong>Questions?</strong>
</div>
