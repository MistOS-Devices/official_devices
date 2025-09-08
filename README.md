# official-devices

## 1. Introduction ##
In order for a device to be OTA compliant, there are a few things to know.

### 1.1 JSON structure ###
```
{
	"response": [
		{
			"maintainer": "Maintainer Name",
			"oem": "#OEM Name",
			"device": "#Device Name",
			"filename": "{file_name}.zip", #(This already generated don't change)
			"download": "https://sourceforge.net/projects/project-mistos/files/Android16/{Package_Type}/{file_name}/download", #(This already generated don't change)
			"timestamp": 1733597875, #(This already generated don't change)
			"md5": "90dbea6065c8553f32fee36c8a845374", #(This already generated don't change)
			"sha256": "efdc4df1863e9e817d559f5d7c61e96dbb04a0e19e9b44c67a29ae84edca4167", # (This is already generated don't change)
			"size": 2745037707, #(Don't change this)
			"version": "[Mist_Version]", #( don't change this)
			"buildtype": "Stable", #(don't change this)
			"forum": "",
			"gapps": "",
			"firmware": "",
			"modem": "",
			"bootloader": "",
			"recovery": "",
			"paypal": "https://www.paypal.com/paypalme/ShukakuZa?country.x=IN&locale.x=en_GB",
			"telegram": "t.me/MistOSDiscussion",
			"dt": "",
			"common-dt": "",
			"kernel": ""
		}
	]
}
```
## 2. How to ##

### Initial Support ###
After you contacted [ShukakuZa on Telegram](https://telegram.me/ShukakuZa), and have the approval, follow the below steps.
1. A file named *codename*.json is created in Official_devices/{packages_type} dir after you built.
2. Open the file and modify needed entries (see 1.1 for mandatory entries).
3. Upload your *codename*.json into official_devices/{package_type}.
