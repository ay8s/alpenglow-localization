### alpenglow-localization
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

This is the community language repository for [Alpenglow](https://itunes.apple.com/app/id978589174).

If you want to see Alpenglow in another language that isn't already available and have some git-fu, feel free to submit a pull request to the repository.

If you don't know about git feel free to grab the [file here](https://github.com/ay8s/alpenglow-localization/blob/master/en.lproj/Localizable.strings) and send it over via the contact option on the [website](https://alpenglowapp.com).


### Structure
Languages are structured in folders as such:

`en.lproj/Localizable.strings`

Where `en` is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (`en`) version.

Please do not include any other files in a pull request.

### Localization

Strings are denoted as `"key"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"locationVC.title" = "Location";`

Where you see a `%@` or `%ld` token, this denotes a value that is replaced at runtime. The corresponding localized value must keep the token in the right place to provide the same meaning as the English value.

`"mainVC.predictions.inXHours" = "in %ld hours";`

`"mainVC.predictions.inXMinutes" = "in %ld minutes";`

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/cbdt"><img src="https://avatars0.githubusercontent.com/u/10958405?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Clément Baudet</b></sub></a><br /><a href="#translation-cbdt" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/insurgentnl"><img src="https://avatars3.githubusercontent.com/u/51951260?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Paul</b></sub></a><br /><a href="#translation-insurgentnl" title="Translation">🌍</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
