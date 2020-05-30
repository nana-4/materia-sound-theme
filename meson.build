project(
  'materia-sound-theme',
  version: '0.1',
  license: 'GPLv3',
  meson_version: '>= 0.46.0',
  default_options: ['prefix=/usr'],
)

theme_dir = join_paths(get_option('datadir'), 'sounds', 'Materia')

install_data(
  'index.theme',
  install_dir: theme_dir,
)

subdir('material_product_sounds')
