<p align="center">
  <a href="https://themes.lekoarts.de">
    <img alt="Gatsby Theme" src="https://img.lekoarts.de/gatsby/gatsby-themes-illustration.png" />
  </a>
</p>
<h1 align="center">
  @lekoarts/gatsby-theme-emma-core
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-themes/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="@lekoarts/gatsby-theme-emma-core is released under the MIT license." />
  </a>
  <a href="https://www.npmjs.org/package/@lekoarts/gatsby-theme-emma-core">
    <img src="https://img.shields.io/npm/v/@lekoarts/gatsby-theme-emma-core.svg" alt="Current npm package version." />
  </a>
  <a href="https://npmcharts.com/compare/@lekoarts/gatsby-theme-emma-core?minimal=true">
    <img src="https://img.shields.io/npm/dm/@lekoarts/gatsby-theme-emma-core.svg" alt="Downloads per month on npm." />
  </a>
  <a href="https://npmcharts.com/compare/@lekoarts/gatsby-theme-emma-core?minimal=true">
    <img src="https://img.shields.io/npm/dt/@lekoarts/gatsby-theme-emma-core.svg" alt="Total downloads on npm." />
  </a>
  <a href="https://www.lekoarts.de?utm_source=emma&utm_medium=Theme">
    <img alt="Website" src="https://img.shields.io/badge/-website-blue">
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=lekoarts_de">
      <img src="https://img.shields.io/twitter/follow/lekoarts_de.svg?label=Follow%20@lekoarts_de" alt="Follow @lekoarts_de" />
    </a>
</p>

Core Theme for [`@lekoarts/gatsby-theme-emma`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-emma). This theme implements the `Project` and `Page` node interfaces and exports templates (+ queries) which you can shadow.

Also be sure to check out other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de) and my [Personal Website](https://www.lekoarts.de?utm_source=emma&utm_medium=Theme).

## Installation

```sh
npm install @lekoarts/gatsby-theme-emma-core
```

## Usage

### Theme options

| Key            | Default Value      | Description                                                                                                 |
| -------------- | ------------------ | ----------------------------------------------------------------------------------------------------------- |
| `basePath`     | `/`                | Root url for the theme                                                                                      |
| `projectsPath` | `content/projects` | Location of projects                                                                                        |
| `pagesPath`    | `content/pages`    | Location of additional pages (optional)                                                                     |
| `mdx`          | `true`             | Configure `gatsby-plugin-mdx` (if your website already is using the plugin pass `false` to turn this off)   |
| `sharp`        | `true`             | Configure `gatsby-plugin-sharp` (if your website already is using the plugin pass `false` to turn this off) |
| `formatString` | `DD.MM.YYYY`       | Configure the date format for Date fields                                                                   |

The usage of `content/pages` is optional. If no page/MDX file is found the navigation will be hidden.

### Shadowing

Please read the guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/) to understand how to customize the theme! You can also have a look at [`@lekoarts/gatsby-theme-emma`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-emma) to see it in action. Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-emma-core/` to shadow/override files.

## 🌟 Supporting me

Thanks for using this project! I'm always interested in seeing what people do with my projects, so don't hesitate to tag me on [Twitter](https://twitter.com/lekoarts_de) and share the project with me.

Please star this project, share it on Social Media or consider supporting me on [Patreon](https://www.patreon.com/lekoarts) or [GitHub Sponsor](https://github.com/sponsors/LekoArts)!