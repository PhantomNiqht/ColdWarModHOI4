# ColdWarModHOI4

This README will go over all steps in order to add new nations, from start to finish. Do NOT edit any of the below marked GLOBAL FILE without first immediately pulling the most recent version of the repository, and as soon as you have made all applicable changes, immediately commit them and publish them. If two people edit the same global file without adhering to these steps, one person's work will be potentially erased. All Global Files have been separated with each person having their own. Lead Dev will periodically compile all contributions into the master file (emptying the contributor files with the exception of one)

# Files to Edit
` common\countries\colors.txt (GLOBAL FILE, PHANTOM ONLY)`  
` common\countries\01_colors.txt` (CROSSFIRE ONLY, in RGB. First is for the border colors, second is for the color of the units when unit nationality is on)  
` common\countries\02_colors.txt` (SKIDDY ONLY, in RGB. First is for the border colors, second is for the color of the units when unit nationality is on)  
` common\countries\COUNTRY NAME.txt`  
` common\country_tags\00_countries.txt` (GLOBAL FILE, PHANTOM ONLY)  
` common\country_tags\01_countries.txt` (CROSSFIRE ONLY)  
` common\country_tags\02_countries.txt` (SKIDDY ONLY)  
` history\countries\TAG - COUNTRY NAME.txt` (Copy `TMP - Template.txt` and adjust capital state for easy nation design)  
` history\states\XXX - STATE NAME.txt` (Edit all that are applicable to your nation)  
` localisation\english\countries_l_english.yml` (GLOBAL FILE, PHANTOM ONLY)  
` localisation\english\01_countries_l_english.yml` (CROSSFIRE ONLY)  
` localisation\english\02_countries_l_english.yml` (SKIDDY ONLY)  
` common\decisions\01_form_nations.txt` (CROSSFIRE ONLY, use `00_form_nations_TEMPLATE.txt` as a reference)  
` common\decisions\02_form_nations.txt` (SKIDDY ONLY, use `00_form_nations_TEMPLATE.txt` as a reference)  


# State Template Data
Remove all cores, and claims aside from the new owning tag. Buildings in the capital state are as follows:  
```
		buildings = {
			infrastructure = 3
			arms_factory = 2
			industrial_complex = 3
			air_base = 1
		}
```
Buildings in all other states are as follows:  
```
		buildings = {
			infrastructure = 1
		}
```

