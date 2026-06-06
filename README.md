# onyxboox-volta4-stock-rom
RU: Прошивка для электронной книги Onyxboox Volta 4 для EDL, не рекомендую использовать Driver_assistant из архива, лучше сами поставьте 9008 драйвера с оффициального сайты qualcomm.

EN: Firmware for the Onyx Boox Volta 4 e-reader for EDL. I do not recommend using Driver_assistant from the archive; it's better to install the 9008 drivers yourself from Qualcomm’s official website.

## Flash guide 
1. Download and extract Volta4_flashing.zip from releases page
2. Install PLatform-tools and QPST
3. open QFIL
4. reboot e-book to EDL
   ```
    adb reboot edl
   ```
1. click "Select port" and select "Qualcomm HS-USB QDLoader 9008"
2. open the settings menu and enable the "Reset after Download" and "Erase all before Download" checkboxes
3. set "Flat build" in "Select Build Type"
4. Enter the path to prog_firehose_ddr.elf in "Programmer Path" \
    and path to folder "Content_VOLTA4_user_ebb130047_2022-12-02" in "Search Path"
5. Select “rawprogram_unsparse0.xml” and “patch0.xml” in Load XML
6. Click Download!
