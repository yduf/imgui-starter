project('Lindirstat', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3'])

# Import dependancies
sdl2_dep = dependency('sdl2', fallback:['sdl2', 'sdl2_dep'])
imgui_dep = dependency('imgui', fallback:['imgui', 'imgui_dep'])


exe = executable('lindirstat', 'lindirstat.cc',
dependencies: [ imgui_dep, sdl2_dep],
  install : true)

test('basic', exe)
