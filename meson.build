project('psflib', 'cpp', version: '0.0.1', license: 'MIT',
        default_options: ['optimization=g',
                          'warning_level=3',
                          'cpp_std=c++20',
                          'c_std=c2x',
                          'default_library=static',
                          'b_coverage=true'])


inc = include_directories('include')


run_target('sonarqube_report',
           command: 'scripts/sonarqube_report.sh')


subdir('src')
