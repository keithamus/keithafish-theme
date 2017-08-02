<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### keithafish
> A theme for [Oh My Fish][omf-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

## Install


```fish
$ omf install keithafish
```

## Features

* Exit status
* Job status
* User
* NPM project name & version
* Git
  * Current branch (or detatched)
  * Dirty working directory
  * Symbols for being in Rebase mode
  * How many commits behind/ahead
* Working directory

## Screenshot

<p align="center">
...soon
</p>

## Configuration

Everything is customisable! Here are the defaults
```fish
set -g _prompt_segment__color "NONE"
set -g _prompt_segment_separatorglyph \uE0B0' '
set -g _prompt_segment__color $argv[1]
set -g _prompt_segment_finishglyph ' '
set -g _prompt_segment__color "NONE"
set -g _prompt_exitstatus_enabled 1
set -g _prompt_exitstatus_backcolor black
set -g _prompt_exitstatus_badglyph \u2716' '
set -g _prompt_exitstatus_badcolor red
set -g _prompt_exitstatus_goodglyph ''
set -g _prompt_exitstatus_goodcolor green
set -g _prompt_jobstatus_enabled 1
set -g _prompt_jobstatus_backcolor black
set -g _prompt_jobstatus_jobsglyph \u2699
set -g _prompt_jobstatus_jobscolor cyan
set -g _prompt_jobstatus_nojobsglyph ''
set -g _prompt_jobstatus_nojobscolor cyan
set -g _prompt_user_enabled 1
set -g _prompt_user_backcolor 42530C
set -g _prompt_user_color white
set -g _prompt_user_showhostname 1
set -g _prompt_user_defaultuser 'keith'
set -g _prompt_git_enabled 1
set -g _prompt_git_color white
set -g _prompt_git_backcolor 004000
set -g _prompt_git_backcolordirty 400000
set -g _prompt_git_backcolorrebase A1630D
set -g _prompt_git_detatchedglyph \u254F' '
set -g _prompt_git_branchglyph \uE0A0' '
set -g _prompt_git_rebaseglyph \u21DE' '
set -g _prompt_git_showsync 1
set -g _prompt_git_topushglyph \u2191
set -g _prompt_git_topullglyph \u2193
set -g _prompt_git_topushpullglyph ' '\u21F5' '
set -g _prompt_npm_enabled 1
set -g _prompt_npm_backcolor 990000
set -g _prompt_npm_color white
set -g _prompt_sudostatus_enabled 1
set -g _prompt_sudostatus_backcolor 384656
set -g _prompt_sudostatus_sudoglyph '#'
set -g _prompt_sudostatus_sudocolor FF9000
set -g _prompt_sudostatus_nosudoglyph '$'
set -g _prompt_sudostatus_nosudocolor FF9000
```

# License

[MIT][mit] © [Keith Cirkel][author] et [al][contributors]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/keithamus
[contributors]:   https://github.com/keithamus/theme-keithafish/graphs/contributors
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
