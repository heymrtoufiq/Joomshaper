# Joomshaper
**Frequently question answer of Template &amp; Extensions joomshaper product**

# Onepage Template (Qubic)
[Qubic](https://www.joomshaper.com/joomla-templates/qubic) Onepage Template (Qubic)

1. No-scroll uses procedure 


## Problems during installation of joomshaper template
1. Go to below path
installation\sql\mysql\sample_data.sql
2. Open sample_data.sql in sublime or any editor
3. Find out InnoDB and replace all InnoDB to MyISAM

## How to install helix3 quickstart pack
[video](https://www.youtube.com/embed/n11cN3NcbDs) Installation process of Helix3 quickstart

##Added dropdown menu item but link not working
#Go to the below location
templates\shaper_qubic\index.php

#Find out below code
$doc->addScriptdeclaration( "\nvar onePageUrl = '".JURI::base(true) . "';\n" );

#And replace with this code 
$doc->addScriptdeclaration( "\nvar onePageUrl = '".JURI::base(true) . "';\n" );

#Add this class inside of Helix menu options > sidebar > Custom CSS Class > no-scroll