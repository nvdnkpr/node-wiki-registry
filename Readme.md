
# Wiki registry

  Build registries out of Github wiki pages like [Clib](https://github.com/clibs/clib/wiki/Packages)
  or [Component](https://github.com/component/component/wiki/Components).

## Installation

    $ npm install wiki-registry

## Example

  For example scraping an early version of https://github.com/clibs/clib/wiki/Packages
  resulted in:

```js
{ Utilities: 
   { 'clibs/hash': 
      { name: 'clibs/hash',
        url: 'https://github.com/visionmedia/hash.c',
        description: 'hash library built on zhash' },
     'clibs/rgba': 
      { name: 'clibs/rgba',
        url: 'https://github.com/visionmedia/rgba.c',
        description: 'rgba color string parser' },
     'clibs/unlikely': 
      { name: 'clibs/unlikely',
        url: 'https://github.com/visionmedia/unlikely.c',
        description: 'gcc branch prediction macros' },
     'clibs/timestamp': 
      { name: 'clibs/timestamp',
        url: 'https://github.com/visionmedia/timestamp.c',
        description: 'millisecond resolution timestamps' },
     'clibs/commander': 
      { name: 'clibs/commander',
        url: 'https://github.com/visionmedia/commander.c',
        description: 'expressive argument parser' },
     'clibs/ms': 
      { name: 'clibs/ms',
        url: 'https://github.com/visionmedia/ms.c',
        description: 'millisecond parser / formatter util' },
     'clibs/bytes': 
      { name: 'clibs/bytes',
        url: 'https://github.com/visionmedia/bytes.c',
        description: 'byte' },
     'clibs/term': 
      { name: 'clibs/term',
        url: 'https://github.com/visionmedia/term.c',
        description: 'terminal utilities' },
     'clibs/buffer': 
      { name: 'clibs/buffer',
        url: 'https://github.com/visionmedia/buffer.c',
        description: 'tiny c' },
     'nami-doc/trim.c': 
      { name: 'nami-doc/trim.c',
        url: 'https://github.com/Nami-Doc/trim.c',
        description: 'doc/trim.c' },
     'nami-doc/strlen.c': 
      { name: 'nami-doc/strlen.c',
        url: 'https://github.com/Nami-Doc/strlen.c',
        description: 'doc/strlen.c' },
     'jwerle/url.h': 
      { name: 'jwerle/url.h',
        url: 'https://github.com/jwerle/url.h',
        description: 'Parse URLs in C much like Node\'s url module.' },
     'jwerle/progress.h': 
      { name: 'jwerle/progress.h',
        url: 'https://github.com/jwerle/progress.h',
        description: 'Progress display lib for c' },
     'jwerle/fs.h': 
      { name: 'jwerle/fs.h',
        url: 'https://github.com/jwerle/progress.h',
        description: 'File system API much like Node\'s fs module' },
     'jwerle/path.h': 
      { name: 'jwerle/path.h',
        url: 'https://github.com/jwerle/path.h',
        description: 'Split a delimited path string into a char array like the $PATH variable' },
     'stephenmathieson/trim.c': 
      { name: 'stephenmathieson/trim.c',
        url: 'https://github.com/stephenmathieson/trim.c',
        description: 'string trim with left and right support' },
     'stpehenmathieson/case.c': 
      { name: 'stpehenmathieson/case.c',
        url: 'https://github.com/stephenmathieson/case.c',
        description: 'string case conversion' } },
  Executables: 
   { 'visionmedia/watch': 
      { name: 'visionmedia/watch',
        url: 'https://github.com/visionmedia/watch',
        description: 'periodically execute commands' },
     'visionmedia/every': 
      { name: 'visionmedia/every',
        url: 'https://github.com/visionmedia/every',
        description: 'simple crontab alternative' },
     'visionmedia/mon': 
      { name: 'visionmedia/mon',
        url: 'https://github.com/visionmedia/mon',
        description: 'simple process monitoring' },
     'visionmedia/histo': 
      { name: 'visionmedia/histo',
        url: 'https://github.com/visionmedia/histo/issues/2',
        description: 'display histograms from static or streaming input' } } }

```

# License

  MIT
