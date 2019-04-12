
cfg = configuration_data()
cfg.set('INCLUDE_INTTYPES_H', 0)
cfg.set('INCLUDE_STDINT_H', 1)
cfg.set('INCLUDE_SYS_TYPES_H', 0)
cfg.set( 'SIZE16',  'int16_t')
cfg.set('USIZE16', 'uint16_t')
cfg.set( 'SIZE32',  'int32_t')
cfg.set('USIZE32', 'uint32_t')
cfg.set( 'SIZE64',  'int64_t')
cfg.set('USIZE64', 'uint64_t')

config_types_h = configure_file(
    configuration : cfg,
    input : 'config_types.h.in',
    output : 'config_types.h',
)
