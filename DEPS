use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'effcee_revision': '35912e1b7778ec2ddcff7e7188177761539e59e0',
  'googletest_revision': 'd9bb8412d60b993365abb53f00b6dad9b2c01b62',
  're2_revision': 'd2836d1b1c34c4e330a85a1006201db474bf2c8a',
  'spirv_headers_revision': '85a1ed200d50660786c1a88d9166e871123cce39',
}

deps = {
  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}

