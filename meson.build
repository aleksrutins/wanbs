project('wanbs', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3',
                     'cpp_std=c++17'])

exe = executable('wanbs', 
  [
    'wanbs.cpp',
    'target.cpp',
  ],
  install : true)

test('basic', exe)
