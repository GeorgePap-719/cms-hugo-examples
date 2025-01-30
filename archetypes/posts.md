+++
date = '{{ .Date }}'
draft = false
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
author = ''
description = ''
notes = ''
+++

## Pre intro
The {{< param author >}} wrote a post about {{< param title >}}

## Intro

{{< param description >}}

## Notes

{{< param notes >}}
