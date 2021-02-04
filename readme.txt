This modification original plugin for Codeblocks 20.03 in linux, original plugin not work.

Arm none eabi Wizard Plugin
----------------------------
A Code::Blocks Plugin to provide a project template wizard for new gcc-arm-none-eabi Project.

NOTE: templates.7z and jlinkdevices.csv in plugin come from emIDE Embedded Application Wizard.


Author:    YWX (wxFortranIndent@163.com)
Created:   2014-5-28
Copyright: (c) YWX <wxFortranIndent@163.com>
License:   GNU General Public License, version 3

Support available for ARM7,Cortex-M0/M0+/M1/M3/M4 and Renesas RX targets.

Send bug reports and questions to YWX <wxFortranIndent@163.com>, or see http://www.emide.org/

Please notice that often trying to correct the bug yourself is the
quickest way to fix it. Even if you fail to do it, you may
discover valuable information allowing us to fix it while doing
it. We also give much higher priority to bug reports with patches
fixing the problems so this ensures that your report will be
addressed sooner.

To get the source code, please visit https://github.com/ywx/cbArmNoneEabiWizard
Get a local copy of the Arm none eabi Wizard Plugin repository with this command:
git clone git://github.com/ywx/cbArmNoneEabiWizard.git cbArmNoneEabiWizard-ReadOnly

For information on Git，please see http://git-scm.com/ or https://github.com/git/git
For information on Git for Windows，please see https://git-for-windows.github.io

Keep source code for project only in master branch. Download prebuilt ArmNoneEabiWizard.cbplugin from https://github.com/ywx/cbArmNoneEabiWizard/releases .

Compilers and Options ( for Linux )
=====================================
1, Install wxBase, wxGTK and xterm for Code::Blocks.
2, Please download Code::Blocks for Linux, to set up develop IDE.
3, Install gcc-g++, wxGTK-devel, codeblocks-devel and codeblocks-contrib-devel to build Code::Blocks Plugin.
4, Please download Arm none eabi Wizard Plugin source code, open ArmNoneEabiWizard-unix.cbp to build in Code::Blocks under "Unix Release" or "Unix Debug" Build targer.

For information on Fedora, please see http://www.fedoraproject.org
For information on Deian, please see http://www.debian.org
For information on gcc, please see http://gcc.gnu.org
For information on wxWidgets, please see http://www.wxwidgets.org
For information on Code::Blocks, please see http://www.codeblocks.org
For information on Code::Blocks Plug-In development, please see http://wiki.codeblocks.org/index.php?title=Developer_documentation
For information on emIDE, please see http://www.emide.org/


Setup and Use
=====================================

Before Code::Blocks Release 17.12
-------------------------------------
1, Download A Extended Scripted Wizard Plugin for Code::Blocks source code, Build the scriptedwizard.cbplugin
   or Download prebuilt scriptedwizard.cbplugin from https://github.com/ywx/cbScriptedWizardPlugin/releases
2, Download Arm none eabi Wizard Plugin for Code::Blocks source code, Build the ArmNoneEabiWizard.cbplugin
   or Download prebuilt ArmNoneEabiWizard.cbplugin from https://github.com/ywx/cbArmNoneEabiWizard/releases
3, Download and Install GNU Tools for ARM Embedded Processors, Set "GNU GCC Compiler for ARM" for GNU Tools for ARM Embedded Processors in Code::Blocks Compiler settings Dialog
4, Disable the Scripted wizard in Code::Blocks Manage plugins Dialog, Uncheck "Install system-wide,for all users of this machine (requires administrative rights)" and "Ask for confirmation if conflicts arise", Install the scriptedwizard.cbplugin and ArmNoneEabiWizard.cbplugin, Close Code::Blocks
5, Extract the templates.7z in the Code::Blocks Data folder in user's dir
6, Reboot Code::Blocks, Enable the Scripted wizard in Code::Blocks Manage plugins Dialog
7, Now New Project, Arm Embedded App will appear in New from template Dialog


For Code::Blocks Release 17.12 or Later
-------------------------------------
1, Download Arm none eabi Wizard Plugin for Code::Blocks source code, Build the ArmNoneEabiWizard.cbplugin
   or Download prebuilt ArmNoneEabiWizard.cbplugin from https://github.com/ywx/cbArmNoneEabiWizard/releases
2, Download and Install GNU Tools for ARM Embedded Processors, Set "GNU GCC Compiler for ARM" for GNU Tools for ARM Embedded Processors in Code::Blocks Compiler settings Dialog
3, Uncheck "Install system-wide,for all users of this machine (requires administrative rights)" and "Ask for confirmation if conflicts arise" in Code::Blocks Manage plugins Dialog, Install ArmNoneEabiWizard.cbplugin, Close Code::Blocks
4, Extract the templates.7z in the Code::Blocks Data folder in user's dir
5, Reboot Code::Blocks
6, Now New Project, Arm Embedded App will appear in New from template Dialog

For information on A Extended Scripted Wizard Plugin for Code::Blocks, please see https://github.com/ywx/cbScriptedWizardPlugin
For information on ARM, please see http://www.arm.com/
For information on GNU Tools for ARM Embedded Processors, please see https://launchpad.net/gcc-arm-embedded
For information on Renesas, please see http://www.renesas.com/
For information on KPIT GNU Tools, please see http://www.kpitgnutools.com/

Code::Blocks Data folder in user's dir:
On Windows
C:\Users\user\AppData\Roaming\CodeBlocks\share\codeblocks codeblocks.exe
Or <codeblocks install dir>\AppData\codeblocks\share\codeblocks CbLauncher.exe
On Linux
/home/user/.local/share/codeblocks


Last updated: January 17th 2018
