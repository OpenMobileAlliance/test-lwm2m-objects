# LwM2M-Objects
This repository is dedicated to the development of LwM2M Objects.

# Object Validation Tool

  * [OMNA Validation Tool](http://devtoolkit.openmobilealliance.org/OEditor/OMNAVerify)
  
# Validation Process
## Validation of a single Object
 0. Go to the [OMNA Validation Tool](http://devtoolkit.openmobilealliance.org/OEditor/OMNAVerify).
 1. Find the "raw" link to Object to validate, by looking the Object in GitHub.
    * e.g. to validate [OMA-SUP-XML_LWM2M_Access_Control-V1_0_2.xml](https://github.com/OpenMobileAlliance/LwM2M-Objects/blob/development/ACL/OMA-SUP-XML_LWM2M_Access_Control-V1_0_2.xml)
 2. In In the GitHub page for the Object click in the **Raw** button to obtain the link to the document.
 3. Insert this link in the **Single Object** text box in the Validation tool
 4. Then click in the button **Single Object** to validate. 
    * If there is any problem with the validation you will see the number of the Object in the right-hand-side column 
 5. To identify the error codes please visit: [Error Codes](https://wiki.openmobilealliance.org/display/TOOL/Validation+Criteria+for+OMNA+LwM2M+Registry)
 
 ## Validation of the DDF.xml & Common.xml files
  0. Go to the [OMNA Validation Tool](http://devtoolkit.openmobilealliance.org/OEditor/OMNAVerify).
  1. Find the "raw" links to the *DDF.xml* and *Common.xml* file by looking in the GitHub repository.
     * Please be aware which link you are validating: Development, Master or a Pull Request
  2. Insert the the "raw" links in the respective:
     * **DDF.xml**, and
     * **Common.xml** text boxes
  3. Click in the **Validate without download** button
     * Note: If you validate with the **Validate** button the validation will take long time.
  4. To identify the error codes please visit: [Error Codes](https://wiki.openmobilealliance.org/display/TOOL/Validation+Criteria+for+OMNA+LwM2M+Registry)
  
  
