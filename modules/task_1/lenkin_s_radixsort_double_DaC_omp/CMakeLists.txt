set(PROJECT_NAME "lenkin_s_radixsort_double_DaC_omp")

if ( USE_OMP )
    project( ${PROJECT_NAME} )
    message( STATUS "-- " ${PROJECT_NAME} )
    add_executable( ${PROJECT_NAME} main.cpp )
else( USE_OMP )
    message( STATUS "-- ${PROJECT_NAME} - NOT BUILD!"  )
endif( USE_OMP )