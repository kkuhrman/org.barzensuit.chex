# org.barzensuit.chex

Copyright (C) 2017 Kuhrman Technology Solutions LLC.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

# Overview

Part of the Barzensuit Project. Provides very basic environment configuration checks (see documentation for details on the Barzensuit Project).

# Requirements

@todo: libbzenc libbzencxx and dependencies

# Implementation

bzenchex is the simplest program under the Barzensuit Project. It is an adpation of Gnu Hello (https://www.gnu.org/software/hello/), which models Gnu coding standards (https://www.gnu.org/prep/standards/), Gnu maintainer practices (https://www.gnu.org/prep/maintain/) and otherwise an excellent introduction to autotools and the Gnu Build System (https://www.gnu.org/software/automake/manual/html_node/Autotools-Introduction.html).

bzenchex is mainly written in C but C++ extensions can be compiled by setting the --enable_cxx flag.

# Installation

It is highly recommend that Gnu make and gcc, lzip and m4 are installed in order to build the Barzensuit software and dependent libraries.
