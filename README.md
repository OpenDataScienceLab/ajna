

AJNA

Agya (Sanskrit: आज्ञा, IAST: Agya, English: “command”), or Third-eye Chakra, is the sixth primary Chakra or energy point in the body, according to Hindu tradition. It is a part of the brain which can be made more powerful through repetition, like a muscle, and signifies the conscience.



Application
The platform Ajna is a functional prototype to help in the process of Exploratory Data Analysis. New functionalities and applications are comming soon. If you would like to see a functionality implemented, please feel free to fork the project or open an issue into the github project. 

So far there is no target audience (business users, data analysts, etc.). It was created in the spare time during the last 2 days to explore R Shiny with Bootstrap. I think I will define the target on-the-fly. I just wanted to take it from the idea stage, implement and share as a skeleton, so people can build upon. 

To test the tool, I suggest downloading and using this file: wine.csv 

The file upload is limited to a size of 10MB because of my current hosting plan in Shinyapps. Therefore, I tested with files bigger than 500MB without crashes and freezes.


Assumption
1. We assume the file is in .csv format;
2. We assume that the first row in the file is the header;
3. We assume the data is already cleaned and converted to numerical, although categorical will be identified too. The descriptive statistics is fully functional for numerical data and perhaps the graphs will not work properly with categorical, text, unstructured data and so on.


Acknowledgement
Thanks to Jo-fai Chow’s Maps of R User Groups Around the World project, who inspired and provided the idea and code base to use Bootstrap and R Shiny.

Thanks to Plotly, for the state of the art in data viz, dashboards, and collaborative analysis.

The RStudio team has provided the community two very powerful tools: Shiny and ShinyApps. These tools allow R users to quickly develop and to host web applications.

The R developers that has provided the community very powerful libraries: Markdown, Data Table, Corrplot, DT, GGally.

The website White Crow Yoga, where I found the beautiful image of Ajna Chakra 96 Petal Lotus. 
License
This app comes with the MIT License (MIT).
