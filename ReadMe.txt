. : 绿色vbox+linux+U盘==10秒钟让你用上Linux : . 

Description: Only start the Portable-VirtualBox.exe and all settings
             becomes automatically made. It must be nothing manuell
             edited.

Features of starter:

- downloader and extractor for the installation file contain
- SplashScreen to start and end (with it one sees, which pass
  something) 
- HotKeys (STRG+1 bis STRG+6)
- HotKeys can be now self selected
- Tray-Menu (multilanguage)
- settings and languages saved in *.ini-files
- hide of the VM and of the manager in tray
- change the homefolder, start-VM, hotkeys and language with
  mouseclick (multilanguage)
- start of VirtualBox-Manager with parameter (Portable-VirtualBox.exe
  "VM")
- all absolute paths in the VirtualBox.xml are replaced automatically
  by relative paths
- examined to VirtaulBox-files exists
- a.o.f.

Note: VirtualBox needs at least main user rights, there 4 Services
      (VBoxDRV, VBoxUSBMon and if not already installs VBoxUSB,
      the VBoxNetFLT and sun_VboxNetFLT) to be furnished and
      VirtualBox must in " Ring-3" - Mode is initiated. The drivers
      the network become with snetcfg.exe (from the ms DDK 2003)
      merged. So that they are loaded, must into that Attitudes of
      Portable-VirtualBox, under the rider " NET" , this to be
      selected. For security, which one installs, must for the
      installation be agreed. After terminating Portable-VirtualBox
      the drivers become and files again removes! 

      Thus the NAT network functions and thus those shared-folders,
      must be installed the guest-extensions.

      Who wants to save some more place, knows all language files
      except that you which necessarily and the documentation delete 
      Again approx. 9MB saves. The language files are in the folder:
      app..\nls and the documentation in the folder: app..\doc.

      If VM runs you must press "Host-Key" (right CTRL-Key) in order
      to be able to use the Hotkeys. Since the focus lies then on the
      VM!

Network support: 1. to download of Portable-VirtualBox
                 2. unpack from Portable-VirtualBox
                 3. start from Portable-VirtualBox
                 4. attitudes open (Tray --> attitudes, CTRL+5)
                    --> rider Network (Tab) --> VirtualBox with
                    network support start --> memory (save)
                 5. terminate from Portable-VirtualBox
                 6. start from Portable-VirtualBox
                 7. driver installation agree
                 8. wait
                 9. selection of a VM and the network map to host
                    interfaces stop
                 10. attitudes make
                 11. FINISHED 

Important: No files became of VirtualBox (http://www.virtualbox.org)
           modifies or otherwise changed. The files became only
           unpacked ones and with UPX (http://upx.sourceforge.net) or
           MPRESS (http://www.matcode.com/mpress.htm) packed, in
           order to save storage location!

Download and support:
http://www.german-winlite.de/wbb/index.php?page=Board&boardID=153

Languages of Launcher: english, german, portuguese, spanish, french,
                       italian

Changelog of Starter:

中文名称绿色Linux发行版   GreenLinux

V 6.4.5开始分支

Version 6.4.5
- Fixed minor bugs on compress


