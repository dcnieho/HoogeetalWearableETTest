This repository contains the experiment data and eye model used and
developed for the article _[Hooge, I.T.C., Niehorster, D.C., Hessels, R.S.,
Benjamins, J.S. & Nyström, M. (2022). How robust are wearable eye trackers to
slow and fast head and body movements? Behavior Research Methods. doi:
10.3758/s13428-022-02010-3](https://doi.org/10.3758/s13428-022-02010-3)_

When using the data in this repository in your work, please cite Hooge et al.
(2022).

For more information or questions, e-mail: i.hooge@uu.nl /
dcnieho@gmail.com. The latest version of this repository is available
from www.github.com/dcnieho/HoogeetalWearableETTest

The data are licensed under the Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 (CC NC-BY-SA 4.0) license.

Contents:
- `data`: this folder contains the data reported in Hooge et al. (2022). Each
  file contains gaze and target data, resampled to the frequency of the scene
  camera. In case of the SeeTrue, it is resampled to 30 Hz. This data is not
  corrected for initial offsets (for explanation, see the section "Accuracy,
  precision and data loss" and Figure 4, box 11 in the article). Resolutions
  and frequencies of the scene cameras can be found in the article (Table 1).

  Each data file contains the following columns:
  - `etime(s)`: timestamp in seconds
  - `ex`: horizontal component of the gaze position in the scene camera image (pixels)
  - `ey`: vertical component of the gaze position in the scene camera image (pixels)
  - `tx`: horizontal component of the target position in the scene camera image (pixels)
  - `ty`: vertical component of the target position in the scene camera image (pixels)
  - `dx`: horizontal distance between gaze position and target position in the scene camera image (pixels)
  - `dy`: vertical distance between gaze position and target position in the scene camera image (pixels)
  - `ds`: distance between gaze position and target position in the scene camera image (pixels)
- `eye tracker scene camera calibrations`: folder containing scene camera
  calibrations for the six eye trackers used in the study.

## Version History
N.B.: complete details of changes made are available on
[github](https://github.com/dcnieho/HoogeetalWearableETTest)
### Version 1.0
- initial release




## Data disclaimer, limitations and conditions of release
By downloading this data set, you expressly agree to the following conditions of release and acknowledge the following disclaimers issued by the authors:

### A. Conditions of Release
Data are available by permission of the authors. Use of data in publications,
either digital or hardcopy, must be cited as follows: [Hooge, I.T.C.,
Niehorster, D.C., Hessels, R.S., Benjamins, J.S. & Nyström, M. (2022). How
robust are wearable eye trackers to slow and fast head and body movements?
Behavior Research Methods. doi:
10.3758/s13428-022-02010-3](https://doi.org/10.3758/s13428-022-02010-3)

### B. Disclaimer of Liability
The authors shall not be held liable for any improper or incorrect use or application of the data provided, and assume no responsibility for the use or application of the data or interpretations based on the data, or information derived from interpretation of the data. In no event shall the authors be liable for any direct, indirect or incidental damage, injury, loss, harm, illness or other damage or injury arising from the release, use or application of these data. This disclaimer of liability applies to any direct, indirect, incidental, exemplary, special or consequential damages or injury, even if advised of the possibility of such damage or injury, including but not limited to those caused by any failure of performance, error, omission, defect, delay in operation or transmission, computer virus, alteration, use, application, analysis or interpretation of data.

### C. Disclaimer of Accuracy of Data
No warranty, expressed or implied, is made regarding the accuracy, adequacy, completeness, reliability or usefulness of any data provided. These data are provided "as is." All warranties of any kind, expressed or implied, including but not limited to fitness for a particular use, freedom from computer viruses, the quality, accuracy or completeness of data or information, and that the use of such data or information will not infringe any patent, intellectual property or proprietary rights of any party, are disclaimed. The user expressly acknowledges that the data may contain some nonconformities, omissions, defects, or errors. The authors do not warrant that the data will meet the user’s needs or expectations, or that all nonconformities, omissions, defects, or errors can or will be corrected. The authors are not inviting reliance on these data, and the user should always verify actual data.


