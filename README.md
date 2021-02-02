# YonseiStressImageDatabase

## Notice

Database storage was moved due to database capacity issues. If you want to download the database, please go to the address below and download it.

https://ieee-dataport.org/open-access/yonsei-stress-image-database



## Abstract

`YonseiStressImageDatabase` is a database built for image-based stress recognition research. We designed an experimental scenario consisting of steps that cause or do not cause stress; Native Language Script Reading, Native Language Interview, Non-native Language Script Reading, Non-native Language Interview. And during the experiment, the subjects were photographed with Kinect v2. We cannot disclose the original image due to privacy issues, so we release feature maps obtained by passing through the network. We used ResNet-18 as the network for extracting the feature maps and released feature maps after the 3rd block out of a total of 4 blocks. The input to the network is a 112×112×3 face RGB image and the size of the feature maps is 7×7×256 (height×width×channel). This database consists of 50 subjects and 2,020,556 data. There are two tasks that can be done with this data. First, there is 4 class classification that classifies the data of each experimental stage, and there is 3 class classification that put the data of the two 'Script Reading' stages as one class.



## Database Structure

- YonseiStressImageDatabase
  - Subject Number (01~50)
    - Data Acquisition Phase (Native Language Script Reading, Native Language Interview, Non-native Language Script Reading, Non-native Language Interview)
      - Data (*.npy, the filename is set to the time the data was acquired; YYYYMMDD_hhmmss_ms)

In the case 'Non-native_Language_Interview' data of subject 26, it was not acquired due to equipment problems.



## Citing YonseiStressImageDatabase

If you use `YonseiStressImageDatabase` in a scientific publication, we would appreciate references to the following paper:

**Now Reviewing.**



## Usage Policy

Copyright © 2019 AI Hub, Inc., [https://aihub.or.kr/](https://aihub.or.kr/)

AI data provided by AI Hub was built as part of a business National Information Society Agency's 'Intelligent information industry infrastructure construction project' in Korea, and the ownership of this database belongs to National Information Society Agency.

Specialized field AI data was built for artificial intelligence technology development and prototype production, and can be used for research purposes in various fields such as intelligent services and chatbots.

# YonseiStressImageDatabase
