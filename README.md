# Business-Recovery-Measurement-Database
Business Recovery Measurement Database

Measuring business recovery after a disaster is a complex task due to the diverse range of circumstances that can affect the recovery process. The type of business, its size, and sector, as well as economic conditions, can all influence the speed and effectiveness of recovery. Furthermore, the type and severity of the disaster itself can also impact the recovery trajectory, with different disasters presenting unique challenges and opportunities for businesses. The Business Recovery Measurement Database compiles categorical and context specific information for each of the studies reviewed in NIST TN 2347 - A Review of Measurement Methods for the Recovery of Businesses After Disasters: An Annotated Bibliography. The database can be searched and filtered by relevant keywords and categories, providing a valuable resource for researchers and practitioners seeking to identify relevant studies, compare methodologies, and access key findings related to business recovery after disasters.

  Principal Investigator Contact Information
        Name: Kurtis Goad
           Institution: National Institute of Standards and Technology
           Email: kurtis.goad@nist.gov


  Associate or Co-investigator Contact Information
        Name: Jennifer Helgeson
           Institution: National Institute of Standards and Technology
           Email: jennifer.helgeson@nist.gov


Associated Files:
1. Business Recovery Data Set --> Business Recovery Data Set.csv
This is the database itself.

2. Database Interface --> Business Recovery Database Interface Script.Rmd
The Interface Script file provides R code to open a user interface that allows user friendly interaction with the data base. The data can be filtered by specific categories and searched using keywords. The file is in markdown format, and the code contains some written instructions and explanations. For more information on R and the associated software, RStudio, visit the following links:
R: https://www.r-project.org/
RStudio: https://posit.co/downloads

NOTE: Ensure 'Business Recovery Data Set.csv' is saved in the working directory where your R session is running. Check with getwd()

Data-Specific Information:
The following are descriptions of each of the categories within the Business Recovery Data Set. Each row is associated with one study reviewed in NIST TN 2347, and each column is associated with a single category. To view the complete reviews for each study and for more information and specific details regarding methodology of the bibliography, please view the full publication of NIST TN 2347 here: https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.2347.pdf

Bibliography Number: The number associated with where the review of a specific study exists within the written bibliography (NIST TN 2347).
Article Title: The title of the article reviewed.
Study Purpose: The objectives or goals of the study.
Type of Business: Information on the businesses included, such as sector, industry, or size.
Disaster: A single-word description of the disaster type affecting the businesses (e.g., Hurricane, Earthquake, Flood, Pandemic).
Built Environment: Indicates whether aspects of the built environment  were included in the recovery measurement (Yes/No).
Timeframe Measured: The period after the disaster during which business recovery was assessed.
Time Point Measured: The specific point(s) in time when data was collected.
Measurement of Recovery: The specific approach or metric(s) used to evaluate business recovery.
Data Method: The method of data collection used in the study.
Methodology: The specific research methods and/or analyses employed in the study.
Validation: The steps taken to verify or validate the measurement approach or model.


Disclaimers:
This data/work was created by employees of the National Institute of Standards and Technology (NIST), an agency of the Federal Government. Pursuant to title 17 United States Code Section 105, works of NIST employees are not subject to copyright protection in the United States.  This data/work may be subject to foreign copyright.

Since the database is comprised of bibliography items, not measurements, there is no measurement uncertainty associated with the database.  Measurement uncertainty in the methods described in the references may be discussed in the individual articles.
 
The data/work is provided by NIST as a public service and is expressly provided â€œAS IS.â€ NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR STATUTORY, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT AND DATA ACCURACY. NIST does not warrant or make any representations regarding the use of the data or the results thereof, including but not limited to the correctness, accuracy, reliability or usefulness of the data. NIST SHALL NOT BE LIABLE AND YOU HEREBY RELEASE NIST FROM LIABILITY FOR ANY INDIRECT, CONSEQUENTIAL, SPECIAL, OR INCIDENTAL DAMAGES (INCLUDING DAMAGES FOR LOSS OF BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF BUSINESS INFORMATION, AND THE LIKE), WHETHER ARISING IN TORT, CONTRACT, OR OTHERWISE, ARISING FROM OR RELATING TO THE DATA (OR THE USE OF OR INABILITY TO USE THIS DATA), EVEN IF NIST HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
 
To the extent that NIST may hold copyright in countries other than the United States, you are hereby granted the non-exclusive irrevocable and unconditional right to print, publish, prepare derivative works and distribute the NIST data, in any medium, or authorize others to do so on your behalf, on a royalty-free basis throughout the world.
 
You may improve, modify, and create derivative works of the data or any portion of the data, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the data and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the data:  Data citation recommendations are provided at https://www.nist.gov/open/license.
 
Permission to use this data is contingent upon your acceptance of the terms of this agreement and upon your providing appropriate acknowledgments of NISTâ€™s creation of the data/work.
 
Certain equipment, instruments, software, or materials are identified in this paper in order to specify the dataset adequately.  Such identification is not intended to imply recommendation or endorsement of any product or service by NIST, nor is it intended to imply that the materials or equipment identified are necessarily the best available for the purpose.
