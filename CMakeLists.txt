
list (APPEND vmec_sources
	${CMAKE_CURRENT_SOURCE_DIR}/abscab/abscab.f90
	${CMAKE_CURRENT_SOURCE_DIR}/abscab/mod_cel.f90
	${CMAKE_CURRENT_SOURCE_DIR}/abscab/mod_compsum.f90
	${CMAKE_CURRENT_SOURCE_DIR}/abscab/mod_kinds.f90
)

set (vmec_sources "${vmec_sources}" PARENT_SCOPE)
