Build a Windows Server 2019 VM template for VMware workstation + VMWare Tools
base on W2K19 Evaluation : 17763.3650.221105-1748.rs5_release_svc_refresh_SERVER_EVAL_x64FRE_en-us.iso

-Create W2K19 + mount vmwaretools on drive: E

 packer init  "C:\W2K19\W2K19-GUI.json"

 packer validate  "C:\W2K19\W2K19-GUI.json"

 packer build  "C:\W2K19\W2K19-GUI.json"

