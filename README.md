# Hardening-a-Desktop-using-Group-Policy

## Objective

 We will be hardening the desktop using a group policy in Windows. System hardening is collection of tools, techniques, and best practices that help to improve IT security and minimize a system's attack surface.


### Skills Learned

- Configuring the group policy in Windows.

### Tools Used

- Windows 10


## Steps
1. Press <kbd>Windows</kbd> and <kbd>R</kbd> keys for the **Run** command. Insert **gpedit.msc** to use the **Group Policy Object Editor**.
2. Navigate to the **Windows Start** button and open up the **Control Panel**.
3. Go back to the **Group policy object editor**->**Administrative Template** ->**Control Panel**.
4. Double click on **Prohibit access to control panel and PC settings** click **Enable** then **Ok**
5. Go back to the **Control Panel** and notice that you now do not have access. We just created a group policy that prohibits the user from acccessing the control panel. 
