<h1>Bank Loan Analysis</h1><br>
This project analyzes a bank's loan portfolio to evaluate application trends, funding performance, repayment behavior, and default risks. It examines borrower profiles, loan tenure, income categories, regional distribution, and loan purposes to understand portfolio health and risk concentration. 
                    <br><br><strong><u>The goal of this project:</u></strong><ul>
                        <li> To assess overall loan performance and financial stability.
                        <li> To identify high-risk segments driving defaults.
                        <li> To improve credit decision-making and risk management.
                        <li> To support data-driven strategies for maximizing profitability while minimizing NPAs.</ul>
                    <br><strong><h3>🐱 Followed the steps :</h3></strong><hr>
                            ✅ Understood and collect the dataset from relevant source.
                        <br>✅ Loaded the raw datasets using pandas.
                        <br>✅ Handeled missing values appropriately.
                        <br>✅ Cleaned and preprocessed the datasets.
                        <br>✅ Performed EDA & applied Feature Engineering techniques.
                    <br><br><strong><h3>🐱 Key Analysis Performed :</h3></strong><hr><ol>
                    <li><strong>Loan Application Trend Analysis (2021) –</strong> Analyzed month-on-month loan applications to identify demand growth patterns.
                    <li> <strong>Funding & Payment Performance Analysis –</strong> Examined total funded amount ($435.76M) vs total amount received ($473.07M) to assess profitability and repayment health.
                    <li> <strong>Loan Status Distribution Analysis –</strong> Evaluated Fully Paid (83%), Charged Off (14%), and Active Loans (3%) to measure portfolio stability.
                    <li> <strong>Regional Performance Analysis –</strong> Compared loan applications, funding allocation, and default rates across states.
                    <li> <strong>Loan Term/Tenure Risk Analysis (36 vs 60 months) –</strong> Studied application volume, funded amounts, and default patterns by tenure.
                    <li> <strong>Borrower Profile Risk Analysis for Loans Defaults – Analyzed impact of: </strong> <ul>
                        <li>Work Experience
                        <li>Income Category
                        <li>Home Ownership
                        <li>Loan Purpose</ul></ol>
                    <br><br><strong><h3>🐱 Insights :</h3></strong><hr><ol>
                    <li><strong>Loan Application Trend (2021) –</strong> Applications increased steadily throughout the year, peaking at 4,314 in December, indicating rising demand for financial loans.
                        <li><strong>Funding & Recovery Performance –</strong>  Total funded amount reached $435.76M, while total amount received was $473.07M, showing strong repayment performance and positive portfolio returns.
                        <li><strong>Loan Status Distribution –</strong> 83% of loans are fully paid, 14% are charged off, and only 3% remain active, reflecting a stable and mature loan portfolio.
                        <li><strong>Regional Performance –</strong> California leads in both loan applications and funding, while Nebraska, Nevada, and Alaska show higher default percentages, indicating regional risk concentration.
                        <li><strong>Loan Tenure Analysis (36 vs 60 Months) –</strong> 36-month loan tenure dominate applications and funding (62%) and as well as default rate (57%) suggesting increased long-term risk, whereas 60-month loan tenure contribute a lesser proportion of defaults.
                        <li><strong>Work Experience Impact –</strong> Borrowers with 10+ years of experience submit the most applications, but default rates are slightly higher in 7 years and 10+ years categories, indicating tenure alone does not reduce risk.
                        <li><strong>Loan Purpose Risk Analysis –</strong> Debt consolidation accounts for the highest applications and funding, while Small Business, Renewable Energy, and Educational loans show higher default rates.
                        <li><strong>Home Ownership Analysis –</strong> Mortgage holders receive higher funded amounts and show the lowest default rate, whereas ‘OTHER’ and ‘RENT’ categories exhibit comparatively higher risk.
                        <li><strong>Income Category Impact –</strong> Lower Middle and Lower Class segments drive the highest application volume, while Upper Middle Class shows the highest default rate (17%), requiring focused risk management.</ol>
                    <br><br><strong><h3>🐱 Recommendations:</h3></strong><hr><ul>
                       <li> Strengthen credit evaluation for 60-month loans, as they show higher default risk compared to 36-month loans.
                       <li> Apply stricter screening criteria for Small Business, Renewable Energy, and Educational loans, since these purposes have higher default rates.
                       <li> Closely monitor lending in high-default states like Nebraska, Nevada, and Alaska, and implement region-specific risk controls.
                       <li> Focus expansion efforts in stable and high-performing markets like California, New York, and Florida.
                       <li> Encourage lending to Mortgage holders, as they show lower default rates and better financial stability.
                       <li> Implement tighter risk assessment for the Upper Middle Class segment, which shows a higher default percentage despite lower application volume.
                       <li> Improve risk scoring models by giving more weight to DTI ratio and financial indicators, rather than relying heavily on work experience.
                       <li> Promote responsible lending in the Lower Middle Class segment, as it contributes high volume but requires controlled risk management.</ul>
                  
