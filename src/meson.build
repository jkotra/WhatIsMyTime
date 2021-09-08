deps = [
  dependency('gio-2.0', version: '>= 2.50'),
  dependency('gtk4', version: '>= 4.2'),
  dependency('gmodule-2.0', version: '>=2.0'),
]


incdir = include_directories('C:/msys64/mingw64/include/', 'C:/msys64/mingw64/lib/glib-2.0/include/', 'C:/msys64/mingw64/lib/graphene-1.0/include')

executable('whatismytime', 'whatismytime.c',
  dependencies: deps,
  include_directories : incdir,
  install: true,
)