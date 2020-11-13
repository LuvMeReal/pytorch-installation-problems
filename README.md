# pytorch-installation-problems

输入nvidia-smi，未找到命令

输入 lspci | grep -i nvidia

显示VGA是NVIDIA Corporation Device 2187(rev a1)

通过 http://pci-ids.ucw.cz/mods/PC/10de?action=help?help=pci 查询到GPU版本为TU116 [GeForce GTX 1650 SUPER]

到官网查询对应的驱动版本并下载，命令行sudo bash NVIDIA-x86_64-440.44.run，出现错误“ERROR：You appear to be running an X server.”

