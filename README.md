# Wireless Compatibilty Chart for macOS
This repository is an initial draft for an extensive collection of wireless devices compatible with macOS

For usability, you can check this document for the latest support info first, open an issue or a PR editing [this file](https://github.com/1alessandro1/Wireless-Compatibilty-Chart-for-macOS/blob/main/Wi-Fi%20Compatibility%20Table%20-%20Pci-Express%2C%20Mini%20Pci-Express%20and%20M.2%20(NGFF)%20for%20macOS.csv) with your favorite editor and export that again in csv for the PR.

https://docs.google.com/spreadsheets/d/1Rc66yvbW2-llykxt5AL03HSHZ9PDa4SQqJrglJ1bMKE/edit#gid=0

since from that I will convert the data to markdown format (so that it can be copied inside guides or wikis which are currently using `.md` format)

## Note: 
Many cards have incorrect information regarding macOS support, Device-ID fixes, and bluetooth support. Please report that with an issue and I'll fix that, the template with the necessary data required is this one:


Sample Table

| Data Type  | Value  |
|:----------------|:----------:|
| **Commercial name** | `Fenvi T919`|
| **Card model**| `BCM94360CD` |
| **Card device-id**    | `14e4:43a0` |
| **Device-id Spoof required**    | `No` |
| **Card Form factor**    | `PCIe X1` |
| **2.4 GHz Speed** | `450Mbps` |
| **5 GHz Speed** | `1300Mbps` |
| **802.11 Support**  | `a/b/g/n/ac`|
| **Bluetooth version**  | `4.0`|
| **Is BcrmPatchRAM required**| `No` |
| **Is ExtendBTFeatureFlags required**| `No` |
| **Antennas max count**| `4` |
| **Minimum macOS support (no patches)**| `10.12` |
| **Maximum macOS support (no patches)**| `Current` |
| **Additional kexts/injectors required from AirportBrcmFixup**| `No` |

I will made an issue template soon. Thanks for your contribution.


## Credits:
- Skvo for the original table which can be found [here](https://docs.google.com/spreadsheets/u/0/d/1Yxlvo-vK_zupMiR1Ua_NZ1X0j6BSXoICCEgB7wvAQsM/htmlview)
