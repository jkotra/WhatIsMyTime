project('com.github.jkotra.whatismytime' , 'c', 
        version: '0.1.0',
        meson_version: '>= 0.50.0',
        default_options:  [ 'warning_level=2',
                            'c_std=gnu11',
                          ],
)

i18n = import('i18n')
prefix = get_option('prefix') # should be /usr
bindir = get_option('bindir') # should be bin
datadir = get_option('datadir') # should be /usr/share
icondir = join_paths(datadir, 'icons/hicolor')

add_project_arguments([
  '-I' + meson.build_root(),
], language: 'c')

subdir('src')