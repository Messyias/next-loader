#
# DO NOT EDIT
# This file is auto-generated by build utility
#
# Module Name:
#
#   GNUmakefile
#
# Abstract:
#
#   Auto-generated makefile for building modules, libraries or platform
#
    

#
# Platform Macro Definition
#
PLATFORM_NAME = Mde
PLATFORM_GUID = 082F8BFC-0455-4859-AE3C-ECD64FB81642
PLATFORM_VERSION = 1.05
PLATFORM_RELATIVE_DIR = MdePkg
PLATFORM_DIR = $(WORKSPACE)/MdePkg
PLATFORM_OUTPUT_DIR = Build/Mde

#
# Module Macro Definition
#
MODULE_NAME = BaseS3StallLib
MODULE_GUID = 498C6AC3-CC29-4821-BE6F-7C6F4ECF2C14
MODULE_VERSION = 1.0
MODULE_TYPE = BASE
MODULE_FILE = BaseS3StallLib.inf
MODULE_FILE_BASE_NAME = BaseS3StallLib
BASE_NAME = $(MODULE_NAME)
MODULE_RELATIVE_DIR = MdePkg/Library/BaseS3StallLib
PACKAGE_RELATIVE_DIR = Library/BaseS3StallLib
MODULE_DIR = $(WORKSPACE)/MdePkg/Library/BaseS3StallLib

MODULE_ENTRY_POINT = _ModuleEntryPoint
ARCH_ENTRY_POINT = _ModuleEntryPoint
IMAGE_ENTRY_POINT = _ModuleEntryPoint

INF_VERSION = 0x00010005
BASE_NAME = BaseS3StallLib
MODULE_UNI_FILE = BaseS3StallLib.uni
FILE_GUID = 498C6AC3-CC29-4821-BE6F-7C6F4ECF2C14
MODULE_TYPE = BASE
VERSION_STRING = 1.0

#
# Build Configuration Macro Definition
#
ARCH = X64
TOOLCHAIN = GCC49
TOOLCHAIN_TAG = GCC49
TARGET = RELEASE

#
# Build Directory Macro Definition
#
# PLATFORM_BUILD_DIR = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49
BUILD_DIR = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49
BIN_DIR = $(BUILD_DIR)/X64
LIB_DIR = $(BIN_DIR)
MODULE_BUILD_DIR = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib
OUTPUT_DIR = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/OUTPUT
DEBUG_DIR = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/DEBUG
DEST_DIR_OUTPUT = $(OUTPUT_DIR)
DEST_DIR_DEBUG = $(DEBUG_DIR)

#
# Shell Command Macro
#
RD = rm -r -f
RM = rm -f
MD = mkdir -p
CP = cp -f
MV = mv -f


#
# Tools definitions specific to this module
#

SYMRENAME =  echo
SYMRENAME_FLAGS = Symbol renaming not needed for

ASLDLINK =  ld
ASLDLINK_FLAGS = -nostdlib -n -q --gc-sections --script=$(EDK_TOOLS_PATH)/Scripts/gcc4.9-ld-script --entry ReferenceAcpiTable -u ReferenceAcpiTable -m elf_x86_64

TIANO =  TianoCompress
TIANO_GUID =  A31280AD-481E-41B6-95E8-127F4C984779




VFR =  VfrCompile
VFR_FLAGS = -l -n

PP =  gcc
PP_FLAGS = -E -x assembler-with-cpp -include $(DEST_DIR_DEBUG)/AutoGen.h

LZMAF86 =  LzmaF86Compress
LZMAF86_GUID =  D42AE6BD-1352-4bfb-909A-CA72A6EAE889



GENFW =  GenFw
GENFW_FLAGS = 


SLINK =  ar



RC =  objcopy
RC_FLAGS = -I binary -O elf64-x86-64 -B i386 --rename-section .data=.hii


ASM =  gcc
ASM_FLAGS = -c -x assembler -imacros $(DEST_DIR_DEBUG)/AutoGen.h -m64

ASL =  iasl
ASL_FLAGS = 
ASL_OUTFLAGS =  -p

RSA2048SHA256SIGN =  Rsa2048Sha256Sign
RSA2048SHA256SIGN_GUID =  A7717414-C616-4977-9420-844712A735BF

MTOC =  /usr/local/bin/mtoc

CC =  gcc
CC_FLAGS = -g -fshort-wchar -fno-strict-aliasing -Wall -Werror -Wno-array-bounds -ffunction-sections -fdata-sections -c -include AutoGen.h -DSTRING_ARRAY_NAME=$(BASE_NAME)Strings -m64 -fno-stack-protector "-DEFIAPI=__attribute__((ms_abi))" -DNO_BUILTIN_VA_FUNCS -mno-red-zone -Wno-address -mcmodel=large -Wno-address -Wno-unused-but-set-variable

VFRPP =  gcc
VFRPP_FLAGS = -x c -E -P -DVFRCOMPILE --include $(DEST_DIR_DEBUG)/$(MODULE_NAME)StrDefs.h



LZMA =  LzmaCompress
LZMA_GUID =  EE4E5898-3914-4259-9D6E-DC7BD79403CF


ASLCC =  gcc
ASLCC_FLAGS = -x c -m64


MAKE =  make

OPTROM =  EfiRom
OPTROM_FLAGS = -e

DLINK =  ld
DLINK_FLAGS = -nostdlib -n -q --gc-sections --script=$(EDK_TOOLS_PATH)/Scripts/gcc4.9-ld-script --entry $(IMAGE_ENTRY_POINT) -u $(IMAGE_ENTRY_POINT) -Map $(DEST_DIR_DEBUG)/$(BASE_NAME).map -melf_x86_64 --oformat=elf64-x86-64

NASMB_FLAGS = -f bin

VPDTOOL =  BPDG
VPDTOOL_GUID =  8C3D856A-9BE6-468E-850A-24F7A8D38E08

CRC32 =  GenCrc32
CRC32_GUID =  FC1BCDB0-7D31-49AA-936A-A4600D9DD083

ASLPP =  gcc
ASLPP_FLAGS = -x c -E -P

OBJCOPY_ADDDEBUGFLAG =  
OBJCOPY =  objcopy
OBJCOPY_FLAGS = 

APP_FLAGS = 

ASMLINK =  C:\WINDDK\3790.1830\bin\bin16\link16.exe
ASMLINK_FLAGS = /nologo /tiny

NASM =  nasm
NASM_FLAGS = -f elf64


MAKE_FILE = $(MODULE_BUILD_DIR)/GNUmakefile

#
# Build Macro
#
OBJECT_FILES =  \
    $(OUTPUT_DIR)/S3StallLib.obj

INC =  \
    -I$(WORKSPACE)/MdePkg/Library/BaseS3StallLib \
    -I$(DEBUG_DIR) \
    -I$(WORKSPACE)/MdePkg \
    -I$(WORKSPACE)/MdePkg/Include \
    -I$(WORKSPACE)/MdePkg/Include/X64

OBJECT_FILES_LIST = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/OUTPUT/object_files.lst


COMMON_DEPS = $(WORKSPACE)/MdePkg/Include/Library/S3BootScriptLib.h \
              $(WORKSPACE)/MdePkg/Include/Library/DebugLib.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/SmBus.h \
              $(WORKSPACE)/MdePkg/Include/Base.h \
              $(WORKSPACE)/MdePkg/Include/Library/TimerLib.h \
              $(WORKSPACE)/MdePkg/Include/X64/ProcessorBind.h \
              $(WORKSPACE)/MdePkg/Include/Library/BaseLib.h \
              $(DEBUG_DIR)/AutoGen.h \
              $(WORKSPACE)/MdePkg/Include/Library/S3StallLib.h \
              

#
# Overridable Target Macro Definitions
#
FORCE_REBUILD = force_build
INIT_TARGET = init
PCH_TARGET =
BC_TARGET = 
CODA_TARGET = /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/OUTPUT/BaseS3StallLib.lib \
              

#
# Default target, which will build dependent libraries in addition to source files
#

all: mbuild


#
# Target used when called from platform makefile, which will bypass the build of dependent libraries
#

pbuild: $(INIT_TARGET) $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# ModuleTarget
#

mbuild: $(INIT_TARGET) $(BC_TARGET) gen_libs $(PCH_TARGET) $(CODA_TARGET)

#
# Build Target used in multi-thread build mode, which will bypass the init and gen_libs targets
#

tbuild: $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# Phony target which is used to force executing commands for a target
#
force_build:
	-@

#
# Target to update the FD
#

fds: mbuild gen_fds

#
# Initialization target: print build information and create necessary directories
#
init: info dirs

info:
	-@echo Building ... $(MODULE_DIR)/$(MODULE_FILE) [$(ARCH)]

dirs:
	-@$(MD) $(DEBUG_DIR)
	-@$(MD) $(OUTPUT_DIR)


strdefs:
	-@$(CP) $(DEBUG_DIR)/AutoGen.h $(DEBUG_DIR)/$(MODULE_NAME)StrDefs.h

#
# GenLibsTarget
#
gen_libs:
	@cd $(MODULE_BUILD_DIR)

#
# Build Flash Device Image
#
gen_fds:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BUILD_DIR)/GNUmakefile fds
	@cd $(MODULE_BUILD_DIR)

#
# Individual Object Build Targets
#
$(OUTPUT_DIR)/BaseS3StallLib.lib : $(OBJECT_FILES)
	"$(SLINK)" -cr /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/OUTPUT/BaseS3StallLib.lib $(SLINK_FLAGS) @$(OBJECT_FILES_LIST)

$(OUTPUT_DIR)/S3StallLib.obj : $(MAKE_FILE)
$(OUTPUT_DIR)/S3StallLib.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)/S3StallLib.obj : $(WORKSPACE)/MdePkg/Library/BaseS3StallLib/S3StallLib.c
	"$(CC)" $(CC_FLAGS) -o /usr/local/UDK2014/MyWorkSpace/Build/Mde/RELEASE_GCC49/X64/MdePkg/Library/BaseS3StallLib/BaseS3StallLib/OUTPUT/./S3StallLib.obj $(INC) /usr/local/UDK2014/MyWorkSpace/MdePkg/Library/BaseS3StallLib/S3StallLib.c



#
# clean all intermediate files
#
clean:
	$(RD) $(OUTPUT_DIR)
	

#
# clean all generated files
#
cleanall:
	$(RD) $(DEBUG_DIR)
	$(RD) $(OUTPUT_DIR)
	$(RM) *.pdb *.idb > NUL 2>&1
	$(RM) $(BIN_DIR)/$(MODULE_NAME).efi

#
# clean all dependent libraries built
#
cleanlib:
	@cd $(MODULE_BUILD_DIR)

