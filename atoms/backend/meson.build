pkgdatadir = join_paths(get_option('prefix'), get_option('datadir'), meson.project_name())
backenddir = join_paths(pkgdatadir, 'atoms/backend')

subdir('models')
subdir('params')
subdir('wrappers')
subdir('exceptions')
subdir('entities')
subdir('utils')

bottles_sources = [
  '__init__.py',
  'atoms.py',
]

install_data(bottles_sources, install_dir: backenddir)