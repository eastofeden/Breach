**Healthcare Analytics: Focus on clinic efficiency**       
    *HIPAA BREACHES* &
    *NO-SHOW ANALYSIS*


The motivation with this project is to increase clinic efficiency and focus into resources that will be most beneficial. 
Besides patient care, one of the lead things that effects clinic efficiency is the way data is controlled. When HIPAA is breached then clinical efficiency goes down. **Can we predict if there will be a data breach?** Are there characteristics that are likely to lead to a breach in data? Which is the **most insecure** way to have information stored?

I acquired data from data.world:
    [HIPAA Breaches](https://data.world/health/health-data-breaches)
     
     
   
This data is tabulated and I used both R and Python to extract insight. The first thing I did after the initial data cleaning in R was begin the EDA by mapping out the amount of breaches by the year.
![hipaayear](https://user-images.githubusercontent.com/23061309/31903069-9bc27be8-b7ec-11e7-85e9-02b3683329c7.png)
This EDA was proven useful because you can visualize the current trend. The next thing that I did in R was an EDA of which establishments are the most likely to report a HIPAA data breach.
![hipaaEntityType](https://user-images.githubusercontent.com/23061309/31903419-a423e564-b7ed-11e7-9bac-c2f71ea75051.png)
As you can see, healthcare providers are the most vulnerable. I wanted to also do an EDA of the breach type or the way that the breach occured. This was also done in R.
![hipaaBreachType](https://user-images.githubusercontent.com/23061309/31903567-1a619dd4-b7ee-11e7-9de9-35bc90ec9ea3.png)
Now that I was able to get a quick glimpse, I switched to python on the jupyter platform to do some extended EDA. Below is the extended type of HIPAA breach in descending order. 
![extendedhipaaBreachType](https://user-images.githubusercontent.com/23061309/31904005-9796071c-b7ef-11e7-8ecc-f670cc3d3fbe.png)
I also wanted to see the location of all of the places that the HIPAA breaches occured.
![locationofhipaabreach](https://user-images.githubusercontent.com/23061309/31904160-0be786fe-b7f0-11e7-9fb2-db6e89eaebe7.png)
Surprisingly, the laptop and server locations weren't number one. In clinical environments there often is a hesitance about technology because of fear of it being not as secure as paper. This chart helps to clearly ascertain the true top vulnerable location.

Include figures or tables if needed. When you post an image put correct path (directory, filename) for your git (or local directory your md file is in). The example below works when there is a folder "images" which has "example.png" in the directory where this md file is in. The github should also include those correctly to render correctly on the web.

example EDA visualization
Figure 1: example graph title
Example 	a 	b 	c 	d
0 	0.85 	0.88 	0.86 	192
1 	0.83 	0.94 	0.89 	196
2 	0.99 	0.84 	0.91 	212
Analysis methods

Describe your analysis methods and brief explanations on your assumption. Include figures or tables as needed.
When writing analysis method, also explicitly mention which tools and libraries you used (imagine this is your portfolio to your future employer- you want to be as impressive as possible) Results from your analysis.
Analysis 2 (optional)

Describe your analysis methods. Include figures or tables as needed.
Analysis results
Results

You can make model(s) comparison if you have multiple approaches. You may include any tables or graphs that summarizes your result(s). Your conclusion, any discussions on difficulties (why some approach didn't work), and any ideas how you may overcome those. If you have external demo website, you can include a link your webapp.
Summary (optional)

Summarize your work and highlight your takeaways. You may include ideas on how you may improve the analysis, or future steps.
References

(list any reference such as journal papers, articles, or other's project repo you referenced for your project)

    example resource
    example resource
