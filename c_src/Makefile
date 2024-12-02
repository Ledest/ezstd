PROJECT_NIF_NAME=ezstd_nif

include nif.mk

CXX = c++
CC = c++
CXXFLAGS += -DNDEBUG -g -O2 -Wextra -Werror -Wno-missing-field-initializers -fno-exceptions -fno-rtti -std=c++11 $(shell pkg-config --cflags libzstd)
LDFLAGS += $(shell pkg-config --libs libzstd)
