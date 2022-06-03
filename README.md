
Assessment 2 

Queensland Shark Control Program catch statistics for Great Barrier Reef Marine Park

https://www.data.qld.gov.au/dataset/qld-shark-control-program-catch-statistics-great-barrier-reef-marine-park

Temperature
http://www.bom.gov.au/jsp/ncc/cdio/weatherData/av?p_nccObsCode=122&p_display_type=dailyDataFile&p_startYear=2016&p_c=-334807539&p_stn_num=040913

solar exposure
http://www.bom.gov.au/jsp/ncc/cdio/weatherData/av?p_nccObsCode=193&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=040913

How weather condition could affect QLD Shark Survivibility


##### Video resources

wk7
26/Apr/2022
https://qut.zoom.us/rec/share/otHlJfjxJSCQCQp5_Gil8zEaaVm-tEYGaWTn7QHRwITsL9lpu38c6OPnQYyRHKIl.7kuvfkrgKsI7Jlt2
Passcode: %Y84^3dQ

01:00:00

The videos should be watched in the following order:
Introduction to Naive Bayes: https://youtu.be/cqfWAIHd-OA
Naive Bayes Jupyter Notebook: https://youtu.be/KedxB7Ci4UU
Introduction to Bayesian Networks: https://youtu.be/0F3FRP-Kw8o
Bayesian Nets Jupyter Notebook Part 1: https://youtu.be/udrg09wpy6U
Bayesian Nets Jupyter Notebook Part 2: https://youtu.be/vUcPCxOYe7Q


wk8
3/May/2022
Topic Modelling: https://mediahub.qut.edu.au/media/t/0_1sp0uwgj


Stream A
Video 1 - https://youtu.be/lbqSQoqbZ14
Video 2 - https://youtu.be/VtwuoS7dCrI
Video 3 - https://youtu.be/IWAEckB-8zM



data ethics
https://mediahub.qut.edu.au/media/t/0_03ihr62d

wk10 - Neural Network
https://qut.zoom.us/rec/share/1UFaN1FEj6qtjlXCLaVYxmtooFIoyFAjoGCSjIdQMDd8auJeLUqiWC5dsSiuSJe0.O6glnqvlxD5A1MWh
Passcode: GB?!*x^4

neural network
https://youtu.be/Q_RmqP9Pcgk

Stanford Sexual Orientation Prediction Paper: https://www.gsb.stanford.edu/faculty-research/publications/deep-neural-networks-are-more-accurate-humans-detecting-sexual


wk11 - LIME
https://qut.zoom.us/rec/share/3FYIx34u4wtC7_Jw-_gM49RK45_NBjGjGoiuN6Nitvo-Vr9afY-1zSwJLOpnPcLK.s1iX0xu8VJ6lPTx0
Passcode: 37M#BV0j

Explainable ML 
https://www.xami-lab.org/0

Wk12 - PCA
https://qut.zoom.us/rec/share/7pmh7e8xJzWKoqJZkQ4UpbAKPh3R9bOzU_I5RPbMTKuCTAYdE5LQBEfm8rvdNfbq.n2QuD7ljdPHfEQsN
Passcode: A5fR%ufu



##### Wk7 - pre Bayesian analysis / Bayesian analysis

    Visualize table -> correlation
    
    Dimensional reduction -> you lose information

    could Apply PCI , cannot interpret what those principal components mean

    -> measure correlations between Var, plot variable 

    2 Clan -> 
        - what are the process generated the data

    
    e.g.
        Distribute Height 

    For real data scientist -> 
        1. Soft Clustering <- Gussian Models / Expectation Minisation 

    K-means


        resources link : 
        Intro Bayesian -  https://www.youtube.com/watch?v=cqfWAIHd-OA&ab_channel=CatarinaMoreira  
        Bayesian Networks - https://www.youtube.com/watch?v=0F3FRP-Kw8o&ab_channel=CatarinaMoreira

    Naive Bayes Classifier

        Tumor - Features
            F1. Radius
            F2. Texture 

            Bengin / Malignant ->  True / False

            |Radius|Textures|Diagnosis|
            |30cm|22|1|
            |22cm|10|0|

                Which Bengin / Malignant ?

            Predict : Diagnosis -> Bengin / Maligant 

            ***Assumption*** -> Variables are independent



            Pr(H|E1, E2, E3, En) = Pr(H)x Pr(E1,E2,... En) / Pr(E1, E2,...)             

            Diagnosis -> Training data / Test data 

            Pr(H|E) = Pr(H).Pr(E|H) / Pr(E)

            Hypothesis Given Evidence
        H -> Hypothesis 
        E -> Evidence

        Gussian distribution

        func_plot_gaussian(data,(5,42),())

    - Uncertainty and Data

    
    Conditionally dependent  

    Pr(Tumor:Mal|Radious-22cm) -> > 

        They are Directed Acyclic Graph

        1. You can go from one note and go backward, to form a cicrcule

        2. 

    Baysian Networks 
        - Uncentainty 
        - No need the full Knowledge 
            -> Feed as much parameters as possible


    What causes the wet Grass -> sprinkler / Rainning?

    Random Variable -> RV
        RV -> toss of a coin (result) 
        Edges -> Features what causes -->  (WetGrass -> RV (True / False))
        Conditional Pr
        
##### Wk7 - Bayesian analysis

    convulted Neural Network

    CNN : https://www.youtube.com/watch?v=Q_RmqP9Pcgk&t=6s&ab_channel=CatarinaMoreira


    Coding - given a completely different patient

    patient = [[34, 12]]

    res = model_base.predict(patient)

    if res >= 0.5:
        print()
    else:
        print() 

=========================
#### Trial 500 
    The last part trial function is to 
        train the model with many different results
        and test it with different test set

    so to find an average how this method performs

    -> and then visualize the results of 500

Bayesian -> probabilitics

BernoukkiNB() -> is like flipping a coin

    Neural Network -> Billion of data
        --> Big dataset use Neural Network 

Bayesian Network
    F1 - C
    F2 /


##### Wk8 - NLP 

TF/IDF as better term frequency
LDA for topic modelling

`packages`
gensim for topic modelling
pyLDAvis for interactive visualisation

##### Wk10 - Neural Network, ML bias, data ethics & ML limitation
##### Jupyter-notebook -> Week10-module7
    Training set -> learning system(0)[Has assumaption input] -> Model, h(param0) -> prediction 
                                                            |
                                                            V
    test set                                         Error y_hat - y 

    Validation Set  -> Only use for training set 
    [F1]  [Class1]  


