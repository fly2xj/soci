###############################################################################
#
# This file is part of CMake configuration for SOCI library
#
# Copyright (C) 2011 Denis Chapligin
# Distributed under the Boost Software License, Version 1.0.
# (See accompanying file LICENSE_1_0.txt or copy at
# http://www.boost.org/LICENSE_1_0.txt)
#
###############################################################################
soci_backend(DB2
  DEPENDS DB2
  HEADERS soci-db2.h
  DESCRIPTION "SOCI backend for DB2 Universal Database"
  AUTHORS "Denis Chapligin"
  MAINTAINERS "Denis Chapligin")

add_subdirectory(test)
