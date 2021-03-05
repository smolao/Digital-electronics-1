# Vivado Tutorial

First you have to start Vivado and choose "Create Project" in Quick Start.

![Create Project](Images/1create_project.png)

In the next step click "Next".

![Click Next](Images/2next.png)

Then you have to type the name of project, for example "vivado_tutorial".

![vivado_tutorial](Images/3project_name.png)

Choose "RTL project".

![RTL project](Images/4rtl_project.png)

As a target language, simulator language and file type choose "VHDL". File name should match with your project name.

![VHDL](Images/5VHDL.png)

In constraints menu, just leave it empty.

![Constraints menu](Images/6constraints.png)

If you are going to need some parts or boards, choose the one you need, for example I chose the Nexys A7-50T board.

![Parts and boards](Images/7nexys_board.png)

Now click "Finnish" and wait until Vivado creates the project.

![Finnish](Images/8finnish.png)

There will appear a "Define Module", click "OK" and then "Yes".

![Define Module](Images/9ok_and_yes.png)

To find your created file go into "Design Sources" and doubleclick the created file.

![Design Sources](Images/10designsources.png)

If you need some testbench file choose menu "File" and there "Add Sources...".

![Add Sources](Images/11add_sources.png)

There choose "Add or create simulation sources" and click "Next".

![Add sources menu](Images/12add_or_create.png)

Then click "Create File".

![Create File](Images/13create_file.png)

Name the file using the project name and adding tb in the front (tb_vivado_tutorial).

![tb_vivado_tutorial](Images/14tb_vivado.png)

In the "Simulation Sources" double click you testbench file.

![Doubleclick testbench file](Images/15click_tb_vivado.png)

Now you see your project file and testbench file in the "PROJECT MANAGER".

![PROJECT MANAGER](Images/16vivado_and_tb.png)