---
title: Scientific Computing Supported Resources
last_modified_at: 2018-09-14
---

>NOTE: This article is a work in progress. If you have suggestions or would like to contribute email `sciwiki`.  

A description of computational and storage resources from Scientific Computing for grant writers can be found [here.](/computing/grants_publications/)

## Self Service Resources
Jupyterhub, RStudio, db4sci, Galaxy, etc.

## Available Resources
VMs, shiny, rancher, data transfer

## Community Resources (not specifically supported by IT)
Are there things people use that we don't really support?



## Auto-generated Table
This table is auto-generated based on the yaml in _data/scicomp_resources.yaml:

Name|Type|Authentication|Authorization|Location
---|---|---|---|---
{% for resource in site.data.scicomp_resources -%}
{{ resource.name }}|{{ resource.type }}|{{ resource.access[0].type }}|{{ resource.access[0].auth }}|{{ resource.location }}
{%- endfor -%}
