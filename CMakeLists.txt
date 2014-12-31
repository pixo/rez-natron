CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

include(RezBuild)

FILE(GLOB_RECURSE all_files "*.*")

rez_install_files(
	${all_files}
	RELATIVE .
	DESTINATION .
)