################################################################################
# Automatically-generated file. Do not edit!
################################################################################

CG_TOOL_ROOT := /home/keenan/ti/ccsv8/tools/compiler/ti-cgt-arm_18.1.3.LTS

GEN_OPTS += /home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/configPkg/compiler.opt
GEN_OPTS__FLAG := --cmd_file="/home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/configPkg/compiler.opt"
GEN_CMDS += /home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/configPkg/linker.cmd
GEN_CMDS__FLAG := -l"/home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/configPkg/linker.cmd"

ORDERED_OBJS += \
"./CC1350_LAUNCHXL.obj" \
"./CC1350_LAUNCHXL_fxns.obj" \
"./adcsinglechannel.obj" \
"./ccfg.obj" \
"./main_tirtos.obj" \
"../CC1350_LAUNCHXL_TIRTOS.cmd" \
-l"ti/display/lib/display.aem3" \
-l"ti/grlib/lib/ccs/m3/grlib.a" \
-l"third_party/spiffs/lib/ccs/m3/spiffs_cc26xx.a" \
-l"ti/drivers/rf/lib/rf_multiMode_cc13x0.aem3" \
-l"ti/drivers/lib/drivers_cc13x0.aem3" \
-l"ti/dpl/lib/dpl_cc13x0.aem3" \
$(GEN_CMDS__FLAG) \
-l"ti/devices/cc13x0/driverlib/bin/ccs/driverlib.lib" \
-llibc.a \

-include ../makefile.init

RM := rm -rf
RMDIR := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.out \

EXE_OUTPUTS__QUOTED += \
"adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.out" \

BIN_OUTPUTS += \
adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.hex \

BIN_OUTPUTS__QUOTED += \
"adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.hex" \


# All Target
all: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@$(MAKE) --no-print-directory -Onone "adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.out"

dependents:
	-cd /home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug && $(MAKE) all

# Tool invocations
adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS) /home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/tirtos_builds_CC1350_LAUNCHXL_release_ccs.lib
	@echo 'Building target: "$@"'
	@echo 'Invoking: ARM Linker'
	"/home/keenan/ti/ccsv8/tools/compiler/ti-cgt-arm_18.1.3.LTS/bin/armcl" -mv7M3 --code_state=16 --float_support=vfplib -me --define=DeviceFamily_CC13X0 -g --diag_warning=225 --diag_warning=255 --diag_wrap=off --display_error_number --gen_func_subsections=on -z -m"adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.map" -i"/home/keenan/ti/simplelink_cc13x0_sdk_2_30_00_20/source" -i"/home/keenan/ti/simplelink_cc13x0_sdk_2_30_00_20/kernel/tirtos/packages" -i"/home/keenan/ti/ccsv8/tools/compiler/ti-cgt-arm_18.1.3.LTS/lib" --diag_wrap=off --display_error_number --warn_sections --xml_link_info="adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2_linkInfo.xml" --rom_model -o "adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '

adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.hex: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: ARM Hex Utility'
	"/home/keenan/ti/ccsv8/tools/compiler/ti-cgt-arm_18.1.3.LTS/bin/armhex"  -o "adcsinglechannel_CC1350_LAUNCHXL_tirtos_ccs2.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "CC1350_LAUNCHXL.obj" "CC1350_LAUNCHXL_fxns.obj" "adcsinglechannel.obj" "ccfg.obj" "main_tirtos.obj" 
	-$(RM) "CC1350_LAUNCHXL.d" "CC1350_LAUNCHXL_fxns.d" "adcsinglechannel.d" "ccfg.d" "main_tirtos.d" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:
/home/keenan/workspace_v8/tirtos_builds_CC1350_LAUNCHXL_release_ccs/Debug/tirtos_builds_CC1350_LAUNCHXL_release_ccs.lib:

-include ../makefile.targets

