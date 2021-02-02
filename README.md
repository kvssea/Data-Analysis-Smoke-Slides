# Data-Analysis-Smoke-Slides

The files in this repository are part of a project that seeks to reduce smoke emissions from our products. 
A key barrier to product development for reduced smoke emissions in our products is the inability to quantify our smoke values 
to benchmark products as improved or reduced smoke performance.

To alleviate this problem, I have developed a smoke tester that measures the level of smoke that obstructs light between an LED and lux sensor
as described in the attached presentation.  The project is based on an arduino UNO that sends data back over serial to a VBA macro written in 
Excel VBA to track and plot data.  This data is then collected and cleaned to produce the data used within the notebook in this repository.

The 'Lux' column referenced in the dataframe is the area under the curve measured from sample testing as described in the attached powerpoint.  The notebook 
attached is the exploratory data analysis to determine if a latest formulation is in fact reduced in smoke vs. our intial competitor benchmark.  Data thus far indicates 
we are able to determine which formula components contribute to overall smoke emission and how to work around their inclusion or omission in the final
formulations. 
