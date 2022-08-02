
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# Stereology Excel Automation
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

In unbiased stereology cell counting for multiple animals with different stains (NeuN, PV, FJB, and others), it can lead to spending many hours collecting and organize data into a single document. This is one of the issues that our lab must deal with when working with large amounts of histology data. This python script written in a Jupiter notebook hopes to fix these issues by taking in all the excel files produced from Visiopharm NewCast, our lab’s stereology system, and formatting it into a single organized excel sheet. The full protocol for our lab’s histology approach is linked down below under reference one ([1]). However, this python script can be retrofitted for any stereology system by adjusting it based on the location and structure of the data.



## 🚀 About Me
Second year; BS Neuroscience Cellular and Molecular Biology undergraduate student at The Texas A&M University.

Curiosity about the intersection of the medicine and biotechology industries.

#### Want to get in contact with me?
- GitHub: [@Taha-Repo](https://www.github.com/Taha-Repo)
- LinkedIn: [Taha Qamari](https://www.linkedin.com/in/taha-qamari-b08676178)
- Email: Taq2021@tamu.edu
## Demo

Insert gif or link to demo

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Installation
#### Order of input Data
examples of input Data are included in this project. The format of the input data excel files are important for the program to work properly.

B series (folder) -> b1-control-pv (folder) -> b1-control-pv-ca1-sd1-cd (folder) -> b1-control-pv-ca1-sd1-cd (excel) 

excel name format: animal code - treatment type - stain type - hipp. region - slide number - cell density(cd) or volume(vol) code

(1) Clone the project in terminal

```bash
  git clone https://github.com/Taha-Repo/Stereology-Excel-Automation.git
```

(2) Go to the project directory or open the file through file directory app on the computer

```bash
  cd Stereology-Excel-Automation
```

(3) Move Jupiter(Python script) file into a separate folder along with the data folder

(4) open it with an IDE or anything that supports Jupiter notbook (Prefer: Visual Studio Code)

(5)Install Packages using pip or Anaconda

(6) Run code and write title when prompted 

(7) You are done! YAY!! 🎇


## Roadmap

- Additional Excel Formats

- Add graphing functions


## Feedback

If you have any feedback, please reach out to us at Taq2021@tamu.edu


## Acknowledgements*

 - PI: Dr.Samba Reddy
 - Edited by: 
## Appendix/Resources*

[1] [Neurostereology protocol for unbiased quantification of neuronal injury and neurodegeneration](https://www.)


