project('cJSON',
    'c',
    default_options: [
        'c_std=c89',
    ],
)

cjson_files_dep = declare_dependency(
    sources: files('cJSON.c', 'cJSON.h'),
    link_args: ['-lm'],
    include_directories: [
        include_directories('.'),
        include_directories(is_system: true),
    ],
)
