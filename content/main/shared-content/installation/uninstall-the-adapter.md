---
uid: UninstallTheAdapter
---

# Uninstall the adapter

Complete the procedure corresponding to your specific operating system to uninstall the adapter:

## Windows

<<<<<<< HEAD
<<<<<<< HEAD
1. To delete the AVEVA adapter program files from a Windows device, use the Windows Control Panel uninstall application process.
=======
1. To delete the PI adapter program files from a Windows device, use the Windows Control Panel uninstall application process.
>>>>>>> parent of fe84c03 (Merge pull request #5 from osisoft/main)
=======
1. To delete the AVEVA adapter program files from a Windows device, use the Windows Control Panel uninstall application process.
>>>>>>> 6e64e0fc7b4fd589ee7219791ac8da0fdf5a2306

    **Note:** The configuration, data, and log files are not deleted by the uninstall process.

2. Optional: To delete data, configuration, and log files, delete the directory:

    _%ProgramData%\OSIsoft\Adapters\\[!include[product-name](../_includes/inline/component-type.md)]_
   
   This deletes all data processed by the adapter, in addition to the configuration and log files.

## Linux

1. To delete AVEVA Adapter software from a Linux device, open a terminal window and run the following command:

    ```bash
<<<<<<< HEAD
    sudo apt remove aveva.adapter.opcua 
=======
    sudo apt remove aveva.adapter.{adapter-name} 
>>>>>>> 6e64e0fc7b4fd589ee7219791ac8da0fdf5a2306
    ```

2. Optional: To delete data, configuration, and log files, run the following command:

    ```bash
    sudo rm -r /usr/share/OSIsoft/Adapters/OpcUa
    ```
    
    This deletes all data processed by the adapter, in addition to the configuration and log files.
