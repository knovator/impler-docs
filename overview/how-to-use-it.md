---
description: It just takes 3 steps to remove all the hassle!
---

# 🧿 How to Use it?

Impler is built around configuring your import once and letting the user import spreadsheets data every time using Widget.

### Let's Configure your Import

Impler is organized in the structure of `Project`, `Template` and `Columns`. To **Create Project**, **Add a Template** to it and **Specify Columns** you can use Swagger UI or can directly call the API from the steps mentioned in [configure-import.md](../api/configure-import.md "mention").

### Let's Embed Import Widget in your App

Once you have configured what you want to import you can embed an `Widget` in your application that allows users to import data.

If your application is built using React, you can add a Widget using [react-component.md](../widget/react-component.md "mention") or You can use [iframe-embed.md](../widget/iframe-embed.md "mention").

Now your App is ready to import files, The imported data will get sent to the API endpoint you specified while creating the project.
