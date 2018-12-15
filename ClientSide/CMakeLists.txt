#
# Copyright 2018 Vladimir Balun
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

cmake_minimum_required (VERSION 3.8)

project (RacingWorld)

set (CMAKE_CXX_STANDARD 17)
set_property (GLOBAL PROPERTY USE_FOLDERS ON)

set (PROJECT_ROOT_DIR ${CMAKE_CURRENT_SOURCE_DIR})
set (PROJECT_CMAKE_DIR ${CMAKE_CURRENT_SOURCE_DIR}/CMake)
set (PROJECT_BUILD_DIR ${CMAKE_CURRENT_SOURCE_DIR}/Build)
set (PROJECT_LIBS_DIR ${CMAKE_CURRENT_SOURCE_DIR}/Libs)
set (PROJECT_BIN_DIR ${CMAKE_CURRENT_SOURCE_DIR}/Bin)
set (PROJECT_DEPENDENCIES_DIR ${CMAKE_CURRENT_SOURCE_DIR}/Dependencies)

add_subdirectory (Dependencies)
add_subdirectory (Sources)