sources = ['bitwise.c', 'framing.c']

libogg = library('ogg',
    sources,
    config_types_h,
    include_directories : incdir,
    build_by_default : not meson.is_subproject(),
)

libogg_dep = declare_dependency(
    link_with : libogg,
    include_directories : incdir
)
