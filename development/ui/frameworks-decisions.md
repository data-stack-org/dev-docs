# Frameworks decisions

## Defining main UI framework

**Note**: Bold is better. If no bold text on line, then there is no strict decision what is better.

| Feature \ Lib | Vue 2 | Angular 2 |
| - | - | - |
| **General** |
| Forces App Structure | **No** | Yes |
| Components | Yes | Yes |
| Virtual DOM | No | No |
| Dev-language | JS, TypeScript | JS, TypeScript |
| ES version | **ES5 by default, but ES6 is ok** | ES6 required |
| Single file components | **Yes** | No |
| Server side rendering | Yes | Yes |
| **Plugins and intergations** |
| Custom Plugins | **Yes** | No (only as simple modules) |
| Modules (by default) | No (only as big plugins) | Yes |
| HTTP service | No (only as plugin) | **Yes** |
| Routing + Views | Plugin | **Yes** |
| Tables | **Less plugins, more self-development** | Big count of non (or small) customizable plugins |
| Graphs/Diagrams wrappers | **Echarts**, ChartJS | d3, ChartJS |
| Admin frameworks | Exists | Exists |
| Forms and handling | **Yes, schema-based** | Default aproach is too complex |
| File uploading | **Yes** | Yes, but little bit complex |
| Shared state | **Yes** | No (only via events) |
| **Performance** |
| [Performance](https://rawgit.com/krausest/js-framework-benchmark/master/webdriver-ts/table.html) <br> Only faster is written | create<br>create many rows<br>clear rows<br>startup time<br>slowdown | update<br>select<br>delete<br>append rows<br>partial update |
| Memmory allocation | **Better** | Worse |
| Framework size (minify + gzip) | **23kb** | 119kb |
| **Popularity** |
| Github Contributors | 84 | 408 |
| Github Watchers | 2644 | 2334 |
| Github Stars | **46213** | 21553 |
| Github Issues open / closed (percent of open) | **56 / 3973 (1.38)** | 1098 / 8234 (11.76) |

### Result

It seems that **Vue2** is easier to work with and it is more customizable. Also it is more lightweight and has no restrictions about project structure. There is exists dynamic plugin management system, so it will be easier to build some extensions.
