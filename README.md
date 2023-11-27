## Ats

     Application Tracking System:
           An applicant tracking system (ATS) is software for recruiters to track candidates throughout the recruiting and hiring process.
           In this app,
                * JobOrder contains job role details needed by companies along with their needed skill set.
                * Candidate Listing contains Candidates details along with their skill set.
                * Company Listing contains Company details along with no.of open roles.

## App Featues

     * The recruiter to check with existing job orders and match with the candidates profile, let's give him a recommended candidates from the list.
     * Once the JobOrder from one company is completed,then the Jobcount in company list get decrease.

## App installation process

     step 1: In your bench directory using command
             ```
             bench get-app ats 
             ```
             to download the app in your apps folder
     step 2: Once the app is downloaded, Install the ats in your site by using
             ```
             bench --site sitename install-app ats
             ```

#### License

MIT
