<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Kirungi okusooka okuteeka nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) , n'oluvannyuma `direnv allow` oluvannyuma lw'okuyingira mu dayirekita ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ejja kukolebwa mu ngeri ey'otoma oluvannyuma lw'okuyingira mu dayirekita).

Amakulu ge gano: Okuvvuunula Oluchina mu lulimi Olujapani, Olukorea, Olungereza, Olungereza mu nnimi endala zonna. Bw’oba ​​oyagala okuwagira Oluchina n’Olungereza lwokka, osobola okuwandiika `zh: en` .

Amakulu ge gano: Okuvvuunula Oluchina mu lulimi Olujapani, Olukorea, Olungereza, Olungereza mu nnimi endala zonna. Bw’oba ​​oyagala okuwagira Oluchina n’Olungereza lwokka, osobola okuwandiika `zh: en` .

* [koodi ey’omu maaso](https://github.com/xxai-art/web)
* [Language packs for omukutu okutwaliza awamu](https://github.com/xxai-art/web/tree/main/i18n)
* [Paka z'olulimi eza modulo z'okuyingira](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Omukutu gwa yintaneeti Ebiwandiiko by’ennimi nnyingi](https://github.com/xxai-doc)

Olulimi lwa pulogulaamu olw'omu maaso luli [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , olugattako ebimu ku bikozesebwa okusinziira ku nsengeka ya coffeescript, laba [./coffee_plus.md](./coffee_plus.md) .

## Okufuula emikutu gy’empuliziganya n’ebiwandiiko mu nsi yonna

Zimba ku pulojekiti zino wammanga 3

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Enkomerero ye `.mdt` , osobola okukozesa ensengeka efaananako ne `<+ ./coffee_plus/import.js>` okujuliza fayiro ez'ebweru, n'okukola markdown n'enkomerero `.md` .

* [@w5/trmd nga bwe](https://www.npmjs.com/package/@w5/trmd)

  Okuvvuunula kwa Markdown tekujja kuvvuunula koodi na links, era kujja kutereka sentensi ezivvuunuddwa. Singa enkyusa ekyusibwa naye ng’ekiwandiiko ekyasooka tekikyusiddwa, okuddamu okukikola tekijja kuwandiika ku nkyukakyuka mu nkyusa.

* [@w5/i18n nga bwe kiri](https://www.npmjs.com/package/@w5/i18n)

  Fayiro z'olulimi ez'okuvvuunula emikutu gya `yaml` egyakolebwa.

### Ebiragiro by’okuvvuunula ebiwandiiko mu ngeri ey’obwengula

Laba etterekero lya koodi [xxai-art/doc](https://github.com/xxai-art/doc)

Kirungi okusooka okuteeka nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) , n'oluvannyuma `direnv allow` oluvannyuma lw'okuyingira mu dayirekita ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ejja kukolebwa mu ngeri ey'otoma oluvannyuma lw'okuyingira mu dayirekita).

Okusobola okwewala omusingi gwa koodi omunene ogwavvuunulwa mu bikumi n’ebikumi by’ennimi, nnakola ekifo eky’enjawulo ekya koodi ku buli lulimi era ne nkola ekitongole okutereka omusingi gwa koodi

Okuteeka enkyukakyuka y'obutonde `GITHUB_ACCESS_TOKEN` n'oluvannyuma okuddukanya [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) kijja kutondawo etterekero lya koodi mu ngeri ey'otoma.

Kya lwatu nti osobola n’okugiteeka mu kifo ekiyitibwa code base.

Ekiwandiiko ky'okuvvuunula ekijuliziddwa [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Koodi y’ebiwandiiko evvuunulwa bweti:

[bunx](https://bun.sh/docs/cli/bunx) kidda mu kifo kya npx, nga kino kyangu. Kya lwatu, bw'oba tolina bun installed, osobola okukozesa `npx` mu kifo ky'ekyo.

`bunx mdt zh` alaga `.mdt` mu zh directory nga `.md` , laba fayiro 2 eziyungiddwa wansi

* [kaawa_nga kwogasse.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [kaawa_nga kwogasse.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ye code enkulu ey'okuvvuunula (bw'oba olina `nodejs` zokka eziteekeddwa, naye `bun` ne `direnv` teziteekeddwa, osobola n'okuddukanya `npx i18n` okuvvuunula).

Kijja kusengejja [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , ensengeka ya `i18n.yml` mu kiwandiiko kino eri bweti:

```
en:
zh: ja ko en
```

Amakulu ge gano: Okuvvuunula Oluchina mu lulimi Olujapani, Olukorea, Olungereza, Olungereza mu nnimi endala zonna. Bw’oba ​​oyagala okuwagira Oluchina n’Olungereza lwokka, osobola okuwandiika `zh: en` .

Ekisembayo ye [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , eggyamu ebirimu wakati w'omutwe omukulu n'omutwe omutono ogusooka ogwa buli lulimi `README.md` okukola okuyingira `README.md` . Code nnyangu nnyo, osobola okugitunuulira ggwe kennyini.

Google API ekozesebwa okuvvuunula okw’obwereere. Bw’oba ​​tosobola kuyingira ku Google, nsaba otegeke era oteekewo proxy, gamba nga:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Ekiwandiiko ky'okuvvuunula kijja kukola cache evvuunuddwa mu `.i18n` directory, nsaba okebere n'embeera `git status` era ogiyongere mu tterekero lya koodi okwewala okuvvuunula okuddiŋŋana.

Nsaba okole `bunx i18n` buli lw'okyusa mu nkyusa okulongoosa cache.

Singa ebiwandiiko eby’olubereberye n’enkyusa bikyusibwa mu kiseera kye kimu, cache ejja kutabulwa, kale bw’oba ​​oyagala okukyusa, osobola okukyusa emu yokka, n’oluvannyuma okole `bunx i18n` okulongoosa cache.
