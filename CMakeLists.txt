#  Ⓒ Copyright 2013 Jeremy Carter
# 
#  This file is part of eternal-void-engine.
# 
#  eternal-void-engine is free software: you can redistribute it and/or modify
#  it under the terms of the GNU General Public License version 3, as published 
#  by the Free Software Foundation.
# 
#  eternal-void-engine is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
#  GNU General Public License for more details.
# 
#  You should have received a copy of the GNU General Public License
#  along with eternal-void-engine. If not, see <http://www.gnu.org/licenses/gpl-3.0.txt>.
# 
#  CMakeLists.txt
# 
#  Created on: 2013-05-18
#      Author: Jeremy Carter
#       Email: Jeremy [at] JeremyCarter [dot] ca
#

cmake_minimum_required (VERSION 2.6)

file (TO_NATIVE_PATH "src/" src_dir)

project (eternal-void-engine)

add_executable(eternal-void-engine ${src_dir}main.cpp)