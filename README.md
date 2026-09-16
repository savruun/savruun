<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&duration=3000&pause=1200&color=7A58E0&center=true&vCenter=true&width=460&lines=hi%2C+i'm+andrew;i+build+compilers;i+build+game+systems" alt="hi, i'm andrew" />

**Language design, Luau tooling, and whatever else fits in a Rust binary.**

<img src="https://komarev.com/ghpvc/?username=savruun&label=views&color=7a58e0&style=for-the-badge" alt="Profile views" />
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fsearch%2Fissues%3Fq%3Dauthor%3Asavruun%2Btype%3Apr%2Bis%3Amerged&query=%24.total_count&label=merged%20PRs&color=7a58e0&style=for-the-badge" alt="Merged pull requests" />
<img src="https://img.shields.io/badge/here%20since-2020-7a58e0?style=for-the-badge" alt="Joined 2020" />
<a href="https://alloy-luau.github.io"><img src="https://img.shields.io/crates/v/alloy-luau?color=7a58e0&label=alloy&style=for-the-badge" alt="Alloy" /></a>
<a href="https://ko-fi.com/savruun"><img src="https://img.shields.io/badge/ko--fi-support-ff5e5b?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi" /></a>

</div>

---

## What I work on

- **[Alloy](https://alloy-luau.github.io)** is a strict superset of Luau that compiles to plain Luau, line for line. Written in Rust. It ships a compiler, a language server, and a VS Code extension.
- **[Ingots](https://github.com/alloy-luau/ingots)** are compiler plugins for Alloy. An ingot runs as its own process and talks to the compiler over a framed pipe. The first one, `enamel`, turns Tailwind class names on `.alx` elements into Roblox properties.
- **[larvae](https://github.com/larvae-luau/larvae)** formats, lints, and ships Luau from one parallel Rust binary.
- **[ember](https://luaupm.com)** is a package manager for Luau. The command is `embr`.
- Ask me about Luau type solving, parser design, or getting Rust and Roblox to agree on anything.

## Projects

| Project | What it is | Language | Last commit |
| --- | --- | --- | --- |
| [alloy](https://github.com/alloy-luau/alloy) | A strict superset of Luau. Compiles to plain Luau, line for line. | Rust | <img alt="" src="https://img.shields.io/github/last-commit/alloy-luau/alloy?style=flat&label=&color=7a58e0" /> |
| [ingots](https://github.com/alloy-luau/ingots) | Official compiler plugins for Alloy. | Rust | <img alt="" src="https://img.shields.io/github/last-commit/alloy-luau/ingots?style=flat&label=&color=7a58e0" /> |
| [larvae](https://github.com/larvae-luau/larvae) | Format, lint, and ship Luau. One binary. | Rust | <img alt="" src="https://img.shields.io/github/last-commit/larvae-luau/larvae?style=flat&label=&color=10e694" /> |
| [ember](https://github.com/ember-luau/ember) | One CLI for your Luau dependencies, tools, and scripts. | Rust | <img alt="" src="https://img.shields.io/github/last-commit/ember-luau/ember?style=flat&label=&color=f23c1b" /> |

## Tools

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img alt="Alloy" src="https://img.shields.io/badge/Alloy-1A1A1A?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACcAAAAoCAMAAABKKxPSAAABX1BMVEUbEDceEj4fEkAhE0UkFUsnFlEoF1UrGFsuGmIpGFcwG2Y7JW8yHGtJMYV4WrhCK3xyVLaZde9kSKVQNY2Rb%2BObd%2FeLaNlFLIM1HXM5IHZ0VL2YdPOZdPRtULI3IHVVOJaRbOaYc%2FRLMYs3HnhCJ4Z7WcY6IH05H3tZPJ%2BSbeqXcfSWcfNTNpd9WsyUb%2FN4V8Q8IYNbPaWOauqRbPBFKY1iQq1GLJJ%2BXNSQa%2FEpF1iPafCNaOyRbOtKLZOAXdaFYeZmRcWGYupkRbOMZ%2B5sS81LKaVwTtGKZe2BXuZVM7NJJ6FMKah8Wtp6V99RL6xTM6x8WuRhP79mSLVJLo15VtSCX%2BlzU9VGJppJJ590VN1aPLRHKJlDJJNtTdE4H3VBJI1aPayCYNtfQK14V%2BFOMqE%2FIolPMZ1zUM5KK5t3VuBiQ7xfQbxQM5tsTMNTNaJWO6lwT9lHMINUOKVXOrBmSMhOqTFXAAADA0lEQVQ4y4XV%2FVvSUBQH8AFuwJrZi8VQMhHaEpOuooAQxgbERM3Fm00xSKTC197%2B%2F6dzz93Y0p6n88vuts%2B%2BG9y7M47z%2BQOBwBQUz%2FOCp2CXp4fhrN%2FHcT5mBCGIFXKK7VJOrY%2FzY5IQdpF4T%2FRQBv1cAJmjREkSp%2B%2FPSLBxJMIAOJdJWA8ePsKtKDJJITjGWBatx7NPnkbY0AO5KZuhkmU5Ojcfm3%2B2ACNbIgTnMpnW88V4LDa7hGMXggt7WSL5Ig4Vm1MSXhgG52Gqqr5cTq2spOKLr2DsgTzHUzdhydV0egUq%2FppMoOMwjjJFIWvrmTSVqeU1oigM0kCeE4L2XVVVIRurmQyF6XRqdYOQCQwKnGDHUUY21zOs0mkIBKfagehYHLBsLp%2FPOzLnBlK3xeISKqFxBYD5IuI3m3CEBYZCW1zQuS0hpe0iVOZtWaM6s51lgfiAEwe31dcrFYDV2rsCzS3qjpPQsdsqEFev1ysFY6exY%2BQLxUJhuwQugTf2Or2OVa7t7laLFSg30OPU0p6mAdt%2FX9utHZgVekmupN7JI7oGVdc%2BNBq1RqOsYXaTeBz7Ha12pwOwWzv82Ggc1ix6lZYrJdzfgS6qG4bR0YyjQ1ZHBsKm4vwvOB%2By3Gqbpml0qse9Hqhe7%2FikA6XttZz%2Fmc3bJ92ktX%2FQBzIA3D8wO4ZhGs0Fe97YOoh00ZX7%2FX5P%2FzyATb%2BMR%2FZaku3wAU%2BHw6FpWmdkNPrSNr%2BWRiPyzULYlNm6ous0FOmOxyDPYeaT5%2FRkEkYX6NpLIVyndN1Lp5ZljYfdLCyGSwuC25cwE1n2LE0J1z28R8FI1aLwCNZl8gpyx%2BZVEl6PgQXDYXsaBL6X4hpl1skG%2FN04HI%2Bta5hXgpcPdRHfS0GY6aK7oW%2Fs2XeE3RLu4Lj9QxCwb8zcYCk4LwO85hrXe%2FTngJ6IhLG%2F8OFJT4NSLoD9kid9iLYN2oe8fQ0l%2BW1dRG%2B3q8DtPgk0e07s5uftk3f7rrTwr7773z4%2Bxfr4X9%2BF2x8G97vwB9q1zRpJ082ZAAAAAElFTkSuQmCC" />
  <img alt="Luau" src="https://img.shields.io/badge/Luau-1A1A1A?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAoCAYAAACM%2FrhtAAAHzUlEQVRYw82YW2wU1xnHf9%2BM18ZXwOZqA6bcajCXYCAlxIhL1wTqECCS26q0VZJeHtrmpaqqSlUq8pKXVm0e2r6klYKqSmmjKvBACXgBc7FDsYEkBJOAMQaCMb5i8N275%2BvDzOzOrncNKAnJkVZz5syZc37z%2F77zfecsfMWLPEynhVtqKlBZErG1rjm3%2FRxvfzvylQFc%2FMyJsohIA6ioAmi3qh5VlZCtVvXl0PrmLxWwZNupVxV%2BB6AoKKiqc%2BfUm1FCRgiNmPDRW0eCXY9Xwcq6OtCnXPXwXxNAUcUo5ryiIQsNmbB9qqVm09AXBrhg2%2Bm8jDTtVCUQhVNFPShHTh%2BgJrYNqmqtqgkhGrpx7L3zsMd8boDLtv9vp4q%2BM756PsAoXAJ07NeBao0aQhETPnS7rvL6gwDTxntoWRI0gAioxq7grwugxNdSlqkKVWpplYjNzPKDzcZoSNSEBm1Cvaee7XkkBVfsqv8Y5evRxTHGzMnUTK2g8d8bk%2FgsrEbrFa2WiO7raNhxflzANTvOzB61rRvgAbjXKKgPLg44%2BS8KZx7mmVFVU9FVv%2BuIlQownJZWYVkWIoIlzlVEEEtidRGsJG2JP7w6wis%2FW8Tu7bMoLspKeOa4jTgVUctaOq4P2iJBFdevXOcSxFkIj1AUEPeVubMy%2BXHVnOiz662DnGzo5NjpTg6eaIuOLAqWai1ACgVVxLY2OYpZKZSyHqie80mx%2B%2FWrC%2BJmKS7M5PvPzeb13y6LjQNYQk9n8fD5lAqu%2BV7jCjEyw1uVjoq%2BJcwDVqy67yV4ePmqyUm7157rdi3kzgMhL98nBUxTU6EiY6AeCKee%2FomrT7Et4cnlk5ICnmzoQkSi7qCioShL0jcsOyhqYjA%2B0KRwUeeJKR7fSyhdmMPEnOTT1Z7rdhaLOjKqEAW0EzuXVl1Mz0yTvyCSHlXBtdXYmBRr0TFQbrvbNDBk6OgexhhlWn4GgYDj%2Fq3tQ%2Fz%2B71djbystbbWVe1IqWDDBLjei2X5Vov6RwqYx1RIMq963KX0DYfbua%2BXNd25h2%2FBESS5Pr5xMZ8%2Bwz7yKCof8Y4zVXKRC4sLL%2BMFFSaJsdJHEvtIPG44o9Rd6OfPhXYzfdUSwkJB%2FqDGAYltB8RI%2FMDHHpvd%2B%2BOHgXDBEo4rGcreXjZxQgjiZyKk7EohijD1S4x8yLg5%2B84eXChDKYhnD4o09xby4a0rq7ODLBIiXDZz4BxLLDr57r7NIbLmL8%2FLZ1prtnSkV1EDGZhu1VBwpiqYFmDk1wKXmYTfwJlHOy9MepNfkqagSZ%2B6xCgrefAJx5h0DaNkE1cTcfXVpFuGwcuHKUBQwLoxoNLC6MOoL0BIHqm6%2B9G%2FTJA4SjEaqEwHjTCxYQbHctCYWq5Zk8VHTEMMjroe75vr5d6exsiQ7LtG7jhandMy0SczsGTZqYgYys0xdSsBtP70xX0TmWe4ktg0rSzI52zgY8y2E3Cyb72zNJzc7DREoX5nLb34yKw405oPJIBkD6Qb4k00HvzWc0sRqWUEREw12i4ozyM22OHtp0FHFtW3ZkmwA3v%2B4HxA2PplH4dR0ALauz2fLuon03Avz1sF2Gq%2F0O6tTkpuYqO8JImP9L05BsQlavlVZtjiT4VHlTmckuiNBYPWSLC41D9E36PjWmqU5nPmoj6wMi41rJvLeB%2Fdpuj7I3tdKmD8nE0uEF3fNZFp%2BgISgFHdnqVQnA0wDqKpSe0BaN%2FuD8d0%2Bw43WUf71h9k03Rih4eIA%2B4%2F1Mn9OBhevDiHA7MIMphcEOHOhDyzheH0vRpXLLQP8QmHBnEwCafDLF%2BZQU9%2FDna4RtpZPAZQDxzv8KrZfO7bpw5SAQ4VtZWIk31ulKByq7ePdU%2FfJyRSeKJlA2eIJ2Bbc7gjz1IpsPm2bxNoVOdzvj%2FDJtSH%2B%2BspcAmnC8YZeng8WkB4QGpv7Ca6dzJ2uEZpvDiICP9hRyJWWfhfQUdEoodi2NgmgqKzDO7m5AcnzmXsDhuMN%2FdTU92HU8Po%2F2tmxeSJfm5VBXrbN2cZ%2BjFEWz8vitTc%2B5UBNF4E0YfqUdG7eHuYby%2FM4%2Ff49AHKybJYvymHvvlvxfmZxhBTFAbTlokZUnR2Pf3cwNg8PDBn%2BeaAbVYOgZGc6bvy3%2F9zh1y8VsbtyCnOLJvDfE90ALF2YzYHjTnJYvTQPseD0B3fjdh9i2dXjAu7%2F0%2FTQcy%2FfWmVgp6IVwBoecGYGMAZ6%2B5w%2Fuvbu72D%2F0W4yAlCxbhKdPaPOBw1GWF2ax%2BWWfnY%2FO4PGpv743K58crV6w81UcyQ9dm75VVu29A8%2FZYwJKgQ1omWqRox7NDRqokdE455xvaOj8c67br%2FSBVn86PmZBALC0oU5vP1uG398swUTO2L%2B%2BWr1ppcfCTCxbHzh2gzLDq%2BPGA2qUqlqihyA2AE8ETQeWlE1FBdOYGAowu32wSggJrKzKbR5%2F2cCTCzlL12ex2gkqGqCxugzRjVP1cRU8VROqHugvnrYmNEpzaGK3s8VME7djcfSBgsLVqghaIwGVc0GY0wgOZwD6KvXNR3e%2BPR4439mwMRSWnUxJ90MrwUTDEfMdlSXRN0hHg5V82rT4U17HitgYllWWT8vYpkKNBJUo5uNar4LqhhWNYU2nP9SAeNK1b%2FtRfeLylTD64xy4erhDUcf6%2FxfRPk%2FKL%2FnrA9fUeIAAAAASUVORK5CYII%3D" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img alt="Arch Linux" src="https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" />
</p>

## Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=savruun&show_icons=true&hide_border=true&bg_color=0D1117&title_color=7A58E0&icon_color=7A58E0&text_color=C9D1D9&hide=issues" />
  <img src="https://github-readme-stats.vercel.app/api?username=savruun&show_icons=true&hide_border=true&title_color=7A58E0&icon_color=7A58E0&hide=issues" alt="GitHub stats" height="165" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=savruun&layout=compact&hide_border=true&langs_count=6&bg_color=0D1117&title_color=7A58E0&text_color=C9D1D9" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=savruun&layout=compact&hide_border=true&langs_count=6&title_color=7A58E0" alt="Top languages" height="165" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/savruun/savruun/output/snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/savruun/savruun/output/snake.svg" alt="Contribution snake" />
</picture>

</div>

## Reach me

- **Ko-fi**: [ko-fi.com/savruun](https://ko-fi.com/savruun)
