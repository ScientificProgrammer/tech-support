# Installing LibreOffice v24.8.4 for Debian

## Installation Steps

1. Set an environment variable to for a tmp install dir.

```bash
TMPLIBREOFFICEINSTALLDIR=/tmp/20250102_143614.install_libre_office/LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS
```

2. Create the tmp install dir.

```bash
mkdir -p "${TMPLIBREOFFICEINSTALLDIR:-}"
```

3. Change to the tmp install dir.

```bash
cd "${TMPLIBREOFFICEINSTALLDIR:-}"
```

4. Use `curl` to download the archive.

Note: `wget` would work too. However, when something goes wrong, I find `curl` more useful.

```bash
curl -O -L https://download.documentfoundation.org/libreoffice/stable/24.8.4/deb/x86_64/LibreOffice_24.8.4_Linux_x86-64_deb.tar.gz
```

5. Unzip the archive.

```bash
tar -zxvf LibreOffice_24.8.4_Linux_x86-64_deb.tar.gz
```

6. Change to the installer directory.

```
cd LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/
```

7. Install the packages.

```bash
sudo apt install ./*.deb
```

8. Verify Your Installation

```bash
libreoffice --version
```

## Sample Output

The time required to download on your connection will vary from the values shown here.

```bash
eric@envy:/tmp/20250102_143614.install_libre_office$ curl -O -L https://download.documentfoundation.org/libreoffice/stable/24.8.4/deb/x86_64/LibreOffice_24.8.4_Linux_x86-64_deb.tar.gz
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   437  100   437    0     0    603      0 --:--:-- --:--:-- --:--:--   603
100  199M  100  199M    0     0   9.8M      0  0:00:20  0:00:20 --:--:-- 11.0M
```

```bash
eric@envy:/tmp/20250102_143614.install_libre_office$ ls -l
total 204692
-rw-rw-r--  1 eric eric 209561263 2025-01-02 14:42 LibreOffice_24.8.4_Linux_x86-64_deb.tar.gz
```

```bash
eric@envy:/tmp/20250102_143614.install_libre_office$ tar -zxvf LibreOffice_24.8.4_Linux_x86-64_deb.tar.gz
LibreOffice_24.8.4.2_Linux_x86-64_deb/
LibreOffice_24.8.4.2_Linux_x86-64_deb/readmes/
LibreOffice_24.8.4.2_Linux_x86-64_deb/readmes/README_en-US
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-mediawiki-publisher_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-ure_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-dict-es_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-postgresql-sdbc_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-xsltfilter_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-math_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-report-builder_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-images_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-javascript-script-provider_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-pyuno_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-draw_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-kde-integration_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-debian-menus_24.8.4-2_all.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-onlineupdate_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-librelogo_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-python-script-provider_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-core_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-ogltrans_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-impress_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-math_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-calc_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-libreofficekit-data_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-graphicfilter_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-nlpsolver_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-ooolinguistic_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-base_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-en-us_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-dict-en_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-draw_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-impress_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-writer_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-firebird_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-writer_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-gnome-integration_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-en-us_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libreoffice24.8-dict-fr_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-beanshell-script-provider_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-extension-pdf-import_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-calc_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-ooofonts_24.8.4.2-2_amd64.deb
LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/libobasis24.8-base_24.8.4.2-2_amd64.deb
```

```bash
eric@envy:/tmp/20250102_143614.install_libre_office$ cd LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS/
```

I deleted the output for this command because it was very long.

```bash
eric@envy:.../20250102_143614.install_libre_office/LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS$ sudo apt install ./*.deb
sudo apt install ./*.deb
```

```bash
eric@envy:.../20250102_143614.install_libre_office/LibreOffice_24.8.4.2_Linux_x86-64_deb/DEBS$ libreoffice --version
LibreOffice 7.3.7.2 30(Build:2)
```
