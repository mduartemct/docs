---
title: Auth0 AngularJS Tutorial
default: true
description: This tutorial demonstrates how to use the Auth0 with AngularJS applications.
topics:
  - quickstarts
  - spa
  - angular
github:
  path: 01-Login
contentType: tutorial
useCase: quickstart
---
<%= include('../../../_includes/_callback_url') %>

If you are following along with the downloadable sample projects for this tutorial directly, the **Callback URL** should be set to

```bash
http://localhost:3000/callback
```

<%= include('../_includes/_install_auth0js') %>

<%= include('_includes/_install_angular_auth0') %>

<%= include('_includes/_centralized_login') %>