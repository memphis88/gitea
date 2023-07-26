---
date: "2018-06-01T19:00:00+02:00"
title: "Pull Request"
slug: "pull-request"
sidebar_position: 13
toc: false
draft: false
menu:
  sidebar:
    parent: "usage"
    name: "Pull Request"
    sidebar_position: 13
    identifier: "pull-request"
---

# Pull Request

## "Work In Progress" pull requests

Marking a pull request as being a work in progress will prevent that pull request from being accidentally merged. To mark a pull request as being a work in progress, you must prefix its title by `WIP:` or `[WIP]` (case insensitive). Those values are configurable in your `app.ini` file :

```ini
[repository.pull-request]
WORK_IN_PROGRESS_PREFIXES=WIP:,[WIP]
```

The first value of the list will be used in helpers.

## Pull Request Templates

You can find more information about pull request templates at the page [Issue and Pull Request templates](issue-pull-request-templates).