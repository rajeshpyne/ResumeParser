# ResumeParser
Parsing a Resume in Python

1. Create a virtual environment with Python 2.7 ( virtualenv -p python2 env )
2. Activate the environment ( source env/bin/activate )
2. Install the packages mentioned in requirements.txt( pip install -r requirements.txt )
3. Run parser.py

Sample Output:-

Enter file name / path : resume.pdf
processing..... 
please wait....
tokenizing the given file ......
removing the stop words....
Cleaning the resumes....
Extracting Text .......
['JonSnowEmail', 'ashaywalke', 'iitkgp.ac.inhttp', '//ashaywalke.github.ioMobile', '+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis', 'FunctionalAnalysis', 'MathematicalMethodsProjectsMovieRecommendationEngine', 'DevelopedamovierecommendationengineinPythonusingpopularcollaborativelteringtechniquesPrimarilybasedontheresearchdoneonSingleValueDecompositionmethodduringthePrizecompetitionImplementedandtestedothermachinelearningtechniqueslikeBaselinepredictorandk-NearestNeighborModelInformationExtractionfromnewsarticles', 'StatisticallyAnalyzedSentencesfromtheknowledgebaseandidentherelationbeingdescribedusingkeywordsandAssignedscorestocountrynumberpairsusingGaussiandistribution']
Name : JonSnowEmail ashaywalke
Email : ashaywalke@iitkgp.ac.inhttp
Mobile : +91993399569
Parsed Resume in plain Text :  JonSnowEmail ashaywalke iitkgp.ac.inhttp //ashaywalke.github.ioMobile +91993399569344West22ndStreet NewYork NY12345EducationIndianInstituteofTechnology KharagpurKharagpur India5yearIntegratedMastersinMathematicsandComputing GPA:6.41July.2014 presentDharampethScienceCollegeNagpur IndiaHigherSecondarySchoolate 87.9 2014MontfortHigherSecondarySchoolBallarpurBallarpur IndiaAllIndiaSeniorSchoolateExamination GPA10.02012ExperienceUniversityofScience MalaysiaPenang MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra UsedSACKinPython acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK -SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting locatingandtheoptimumpathforreachingthetargetsContourProperties LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages Python C C++ JavaLibraries OpenCV Scikit-learn Matplotlib Numpy ScipyDatabase MySQLSoftwares MicrosoftAdobeSuite MATLAB GITCourseworkInformationComputerScience ProgrammingandDataStructures SystemsProgramming DesignandAnalysisofAlgorithms ObjectOrientedSystemsDesign SwitchingandFiniteAutomata TheoryofCompilerDesign Mathematics LinearAlgebra ModernAlgebra OperationsResearch ProbabilityandStatistics MeasureTheory RealAnalysis FunctionalAnalysis MathematicalMethodsProjectsMovieRecommendationEngine DevelopedamovierecommendationengineinPythonusingpopularcollaborativelteringtechniquesPrimarilybasedontheresearchdoneonSingleValueDecompositionmethodduringthePrizecompetitionImplementedandtestedothermachinelearningtechniqueslikeBaselinepredictorandk-NearestNeighborModelInformationExtractionfromnewsarticles StatisticallyAnalyzedSentencesfromtheknowledgebaseandidentherelationbeingdescribedusingkeywordsandAssignedscorestocountrynumberpairsusingGaussiandistribution
Shingles for the resume :  [('JonSnowEmail', 'ashaywalke', 'iitkgp.ac.inhttp', '//ashaywalke.github.ioMobile', '+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014'), ('ashaywalke', 'iitkgp.ac.inhttp', '//ashaywalke.github.ioMobile', '+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur'), ('iitkgp.ac.inhttp', '//ashaywalke.github.ioMobile', '+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate'), ('//ashaywalke.github.ioMobile', '+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9'), ('+91993399569344West22ndStreet', 'NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur'), ('NewYork', 'NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination'), ('NY12345EducationIndianInstituteofTechnology', 'KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience'), ('KharagpurKharagpur', 'India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang'), ('India5yearIntegratedMastersinMathematicsandComputing', 'GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops'), ('GPA:6.41July.2014', 'presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra'), ('presentDharampethScienceCollegeNagpur', 'IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython'), ('IndiaHigherSecondarySchoolate', '87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops'), ('87.9', '2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK'), ('2014MontfortHigherSecondarySchoolBallarpurBallarpur', 'IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai'), ('IndiaAllIndiaSeniorSchoolateExamination', 'GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis'), ('GPA10.02012ExperienceUniversityofScience', 'MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting'), ('MalaysiaPenang', 'MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties'), ('MalaysiaUndergraduateResearcherMay2017-June2017MoufangLoops', 'theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques'), ('theproofofequivalenceofMoufangIdentitiesbyextensivelyapplyingtheconceptsofModernAlgebraandPermutationtheknownproofwascumbersomeandrequiredtheknowledgeofautotopismApplicationofprogramminginAbstractAlgebra', 'UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore'), ('UsedSACKinPython', 'acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack'), ('acommand-lineprogramfordoingelementarycomputationsonsmallgroupsandprintingtheircayleytablesNonassociativititeloops', 'Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement'), ('Provedthatthereisnonon-associativeloophavingorderlessthan5withthehelpofSACK', '-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages'), ('-SimpleAbstractAlgebraCalculatorinPythonMathminersMumbai', 'IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python'), ('IndiaRemoteDataScienceInternDec2016DroneandQuad-copterAnalysis', 'ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C'), ('ExtensivelyinvolvedtheuseoftheopenCVlibraryinpythonfordetecting', 'locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++'), ('locatingandtheoptimumpathforreachingthetargetsContourProperties', 'LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries'), ('LeveragedtheuseofcontourpropertiesoftshapeswhichhelpedinsavingthetrainingofcomplicatedmachinelearningmodelsVideoEnhancementTechniques', 'AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV'), ('AppliedthevideoenhancementtechniquestohighlightthedetailswhichareobscuredinvolvingchangingbrightnessandcolorcontrastHackerearthBangalore', 'IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn'), ('IndiaMarketAnalysisInternMay2016-July2016SanFranciscoSlashHack', 'Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib'), ('Preparedstatusreportsandproposednewbusinessstrategiesfor/hackwhichwitnessedover900developersandkeynotespeakersRelationshipManagement', 'BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy'), ('BoostedthenumberofOutbondcallsbyhelpingthemanagertoidentifyactivepartnerspartnerswithgoodbusinesspotentialProgrammingSkillsLanguages', 'Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase'), ('Python', 'C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares'), ('C', 'C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite'), ('C++', 'JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB'), ('JavaLibraries', 'OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience'), ('OpenCV', 'Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures'), ('Scikit-learn', 'Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming'), ('Matplotlib', 'Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms'), ('Numpy', 'ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign'), ('ScipyDatabase', 'MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata'), ('MySQLSoftwares', 'MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign'), ('MicrosoftAdobeSuite', 'MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics'), ('MATLAB', 'GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra'), ('GITCourseworkInformationComputerScience', 'ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra'), ('ProgrammingandDataStructures', 'SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch'), ('SystemsProgramming', 'DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics'), ('DesignandAnalysisofAlgorithms', 'ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory'), ('ObjectOrientedSystemsDesign', 'SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis'), ('SwitchingandFiniteAutomata', 'TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis', 'FunctionalAnalysis'), ('TheoryofCompilerDesign', 'Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis', 'FunctionalAnalysis', 'MathematicalMethodsProjectsMovieRecommendationEngine'), ('Mathematics', 'LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis', 'FunctionalAnalysis', 'MathematicalMethodsProjectsMovieRecommendationEngine', 'DevelopedamovierecommendationengineinPythonusingpopularcollaborativelteringtechniquesPrimarilybasedontheresearchdoneonSingleValueDecompositionmethodduringthePrizecompetitionImplementedandtestedothermachinelearningtechniqueslikeBaselinepredictorandk-NearestNeighborModelInformationExtractionfromnewsarticles'), ('LinearAlgebra', 'ModernAlgebra', 'OperationsResearch', 'ProbabilityandStatistics', 'MeasureTheory', 'RealAnalysis', 'FunctionalAnalysis', 'MathematicalMethodsProjectsMovieRecommendationEngine', 'DevelopedamovierecommendationengineinPythonusingpopularcollaborativelteringtechniquesPrimarilybasedontheresearchdoneonSingleValueDecompositionmethodduringthePrizecompetitionImplementedandtestedothermachinelearningtechniqueslikeBaselinepredictorandk-NearestNeighborModelInformationExtractionfromnewsarticles', 'StatisticallyAnalyzedSentencesfromtheknowledgebaseandidentherelationbeingdescribedusingkeywordsandAssignedscorestocountrynumberpairsusingGaussiandistribution')]
