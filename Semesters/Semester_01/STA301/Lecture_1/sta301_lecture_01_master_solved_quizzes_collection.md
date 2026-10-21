\documentclass[11pt,a4paper]{article}
\usepackage[utf8]{utf8}
\usepackage[margin=1in]{geometry}
\usepackage{amsmath,amssymb}
\usepackage{enumitem}
\usepackage{xcolor}
\usepackage{tcolorbox}
\usepackage{hyperref}

\definecolor{primary}{RGB}{30, 64, 175}
\definecolor{success}{RGB}{22, 101, 52}
\definecolor{error}{RGB}{153, 27, 27}

\title{\textbf{\Huge STA301: Introduction to Statistics}\\[0.5em] \Large Master Solved Quizzes Collection}
\author{Lecture 01 - Fundamental Concepts \& Measurement Scales}
\date{\today}

\begin{document}

\maketitle

\tableofcontents
\newpage

\section{Overview}
This document contains the complete set of all solved multiple-choice practice questions covering \textbf{STA301 Lecture 01}. For each question, options are provided along with the correct answer and a brief explanatory rationale.

\section{Quiz Set 1: Fundamental Principles Practice Quiz}

\begin{enumerate}[label=\textbf{Q\arabic*.}]

    \item A research study measures the exact weight in kilograms of 250 randomly selected newborn infants. How is the variable ``infant weight'' classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Quantitative discrete variable
        \item \textbf{Quantitative continuous variable}
        \item Qualitative ordinal variable
        \item Nominal attribute
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Quantitative continuous variable\\
        \textbf{Rationale:} Infant weight is determined by measuring and can assume any real value within a continuous numerical range depending on instrument precision.
    \end{tcolorbox}

    \item An analyst conducts a survey to evaluate voter preferences across 5 urban districts. During data entry, the analyst accidentally enters ``District 12'' for a participant from District 2. What type of error is this?
    \begin{enumerate}[label=(\Alph*)]
        \item Sampling error
        \item \textbf{Non-sampling error}
        \item Standard error
        \item Population bias
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Non-sampling error\\
        \textbf{Rationale:} Data transcription or clerical mistakes made during data processing are classic examples of non-sampling errors, which can happen in both sample surveys and complete censuses.
    \end{tcolorbox}

    \item Which level of measurement applies to temperatures measured on the Fahrenheit scale?
    \begin{enumerate}[label=(\Alph*)]
        \item Nominal scale
        \item Ordinal scale
        \item \textbf{Interval scale}
        \item Ratio scale
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (C) Interval scale\\
        \textbf{Rationale:} Fahrenheit temperature has equal intervals between degrees but lacks a true absolute zero point ($0^\circ\text{F}$ does not denote the complete absence of heat energy).
    \end{tcolorbox}

    \item A hospital administrator calculates the average length of stay for all $1{,}200$ patients admitted to a clinic during the previous month. How is this average value classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Sample statistic
        \item \textbf{Parameter}
        \item Inferential estimate
        \item Sampling variation
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Parameter\\
        \textbf{Rationale:} Because the calculation includes every single admitted patient in the specified target population, the computed metric is a population parameter.
    \end{tcolorbox}

    \item An economist downloads official quarterly inflation rates published by the State Bank of Pakistan to analyze currency trends. Relative to the economist's study, how is this dataset classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Primary data
        \item \textbf{Secondary data}
        \item Experimental data
        \item Qualitative data
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Secondary data\\
        \textbf{Rationale:} The dataset was originally compiled and published by an external agency prior to being retrieved by the economist for a new secondary analysis.
    \end{tcolorbox}

    \item A retail manager records customer rating ranks using the options: ``Very Unsatisfied'', ``Neutral'', and ``Very Satisfied''. Which measurement scale is being utilized?
    \begin{enumerate}[label=(\Alph*)]
        \item Nominal scale
        \item \textbf{Ordinal scale}
        \item Interval scale
        \item Ratio scale
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Ordinal scale\\
        \textbf{Rationale:} Customer satisfaction levels possess a clear, meaningful qualitative ranking, but precise numerical distances between adjacent categories cannot be calculated.
    \end{tcolorbox}

    \item A quality control engineer inspects a sample of 50 manufactured engine components and calculates that $4\%$ are defective. The engineer concludes that approximately $4\%$ of all engine components produced that week are defective. What branch of statistics is illustrated?
    \begin{enumerate}[label=(\Alph*)]
        \item Descriptive statistics
        \item \textbf{Inferential statistics}
        \item Mathematical probability
        \item Census analysis
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Inferential statistics\\
        \textbf{Rationale:} Using sample observations ($50$ inspected components) to generalize conclusions about a larger unobserved population (all weekly components) defines inferential statistics.
    \end{tcolorbox}

    \item Which of the following attributes is measured on a ratio scale?
    \begin{enumerate}[label=(\Alph*)]
        \item Calendar year
        \item Fahrenheit temperature
        \item \textbf{Annual household income}
        \item Academic rank position
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (C) Annual household income\\
        \textbf{Rationale:} Income possesses equal intervals and a true absolute zero point ($\$0$ represents the total absence of income), enabling valid ratio comparisons such as ``double the income''.
    \end{tcolorbox}

    \item A researcher records the total number of customer service calls received by a call center each hour. How is this variable classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Quantitative continuous variable
        \item \textbf{Quantitative discrete variable}
        \item Qualitative ordinal variable
        \item Nominal categorical variable
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Quantitative discrete variable\\
        \textbf{Rationale:} The total number of incoming phone calls is determined by counting whole units, resulting in discrete integer values with distinct gaps.
    \end{tcolorbox}

    \item Why does evaluating an entire target population through a complete census eliminate sampling error completely?
    \begin{enumerate}[label=(\Alph*)]
        \item \textbf{Because data is collected from every single unit in the population}
        \item Because all non-sampling errors are automatically corrected
        \item Because sample statistics completely replace population parameters
        \item Because measurement scale variations are standardized
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (A) Because data is collected from every single unit in the population\\
        \textbf{Rationale:} Sampling error arises solely from observing a subset rather than the entire group. Examining $100\%$ of population units removes sampling variability entirely.
    \end{tcolorbox}

\end{enumerate}

\newpage
\section{Quiz Set 2: General Concepts \& Definitions}

\begin{enumerate}[label=\textbf{Q\arabic*.}, start=11]

    \item What is the primary objective of inferential statistics?
    \begin{enumerate}[label=(\Alph*)]
        \item Collecting raw data from every single census unit
        \item Organizing data into frequency tables and bar charts
        \item \textbf{Generalizing from a sample to a population}
        \item Eliminating all sources of non-sampling error
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (C) Generalizing from a sample to a population\\
        \textbf{Rationale:} Inferential statistics uses sample data to draw general conclusions or estimates about an entire population.
    \end{tcolorbox}

    \item Which of the following best defines a ``population'' in statistical analysis?
    \begin{enumerate}[label=(\Alph*)]
        \item \textbf{The entire collection of items of interest}
        \item A small representative subset selected for testing
        \item A summary statistic calculated from observed sample data
        \item A single individual measured in a scientific study
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (A) The entire collection of items of interest\\
        \textbf{Rationale:} A population represents the complete universe of all subjects or items under study.
    \end{tcolorbox}

    \item What distinguishes a parameter from a statistic?
    \begin{enumerate}[label=(\Alph*)]
        \item Parameters apply to qualitative data; statistics apply to quantitative data.
        \item \textbf{Parameters describe populations; statistics describe samples.}
        \item Statistics are exact values; parameters are always estimates.
        \item Parameters are calculated from samples; statistics come from censuses.
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Parameters describe populations; statistics describe samples.\\
        \textbf{Rationale:} Parameters are numerical values summarizing a whole population, while statistics summarize sample subsets.
    \end{tcolorbox}

    \item Why is sampling generally preferred over a complete census in most practical research scenarios?
    \begin{enumerate}[label=(\Alph*)]
        \item It eliminates all forms of non-sampling human error.
        \item \textbf{It is more cost-effective and time-efficient.}
        \item It produces exact population parameters directly.
        \item It avoids using probability principles in analysis.
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) It is more cost-effective and time-efficient.\\
        \textbf{Rationale:} Studying a representative sample saves time, money, and labor compared to surveying every single unit in a large population.
    \end{tcolorbox}

    \item Which branch of statistics is primarily concerned with graphical summaries, tables, and calculating averages?
    \begin{enumerate}[label=(\Alph*)]
        \item Inferential statistics
        \item \textbf{Descriptive statistics}
        \item Predictive modeling
        \item Hypothesis testing
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Descriptive statistics\\
        \textbf{Rationale:} Descriptive statistics deals with methods of organizing, summarizing, and presenting dataset characteristics clearly.
    \end{tcolorbox}

    \item What is a variable in the context of statistical data collection?
    \begin{enumerate}[label=(\Alph*)]
        \item A fixed numerical value that never changes
        \item \textbf{A characteristic that varies from one object to another}
        \item The total size of a target population
        \item A mathematical error occurring during survey sampling
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) A characteristic that varies from one object to another\\
        \textbf{Rationale:} A variable is any attribute or characteristic that can take on different values across different subjects or elements.
    \end{tcolorbox}

    \item Which of the following represents a quantitative (numerical) variable?
    \begin{enumerate}[label=(\Alph*)]
        \item Preferred brand of mobile phone
        \item \textbf{Daily commute time in minutes}
        \item Eye color category
        \item Marital status
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Daily commute time in minutes\\
        \textbf{Rationale:} Commute time is a numerical quantity resulting from measurement, making it a quantitative variable.
    \end{tcolorbox}

    \item What does a sample represent relative to its parent population?
    \begin{enumerate}[label=(\Alph*)]
        \item The margin of error calculated during hypothesis testing
        \item \textbf{A representative subset used to draw inferences}
        \item An exhaustive list of all population parameters
        \item A collection of non-sampling errors
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) A representative subset used to draw inferences\\
        \textbf{Rationale:} A sample is a portion or subset selected from a population to represent the whole in research studies.
    \end{tcolorbox}

    \item Which scenario is an example of descriptive statistics rather than inferential statistics?
    \begin{enumerate}[label=(\Alph*)]
        \item \textbf{Calculating the average GPA of students in a specific classroom}
        \item Predicting next year's inflation rate using sample market indicators
        \item Testing a vaccine on $100$ mice to claim safety for all mammals
        \item Estimating total national voter turnout from early exit poll samples
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (A) Calculating the average GPA of students in a specific classroom\\
        \textbf{Rationale:} Computing the exact mean of an observed group simply summarizes the available data without making generalizations beyond that classroom.
    \end{tcolorbox}

    \item Why is random sampling important when conducting statistical research?
    \begin{enumerate}[label=(\Alph*)]
        \item It eliminates the need to collect quantitative data.
        \item \textbf{It helps minimize selection bias and ensures representativeness.}
        \item It guarantees that non-sampling errors will not occur.
        \item It turns sample statistics directly into exact population parameters.
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) It helps minimize selection bias and ensures representativeness.\\
        \textbf{Rationale:} Randomization gives every member of the population an equal chance of selection, reducing selection bias and forming a representative sample.
    \end{tcolorbox}

\end{enumerate}

\newpage
\section{Quiz Set 3: Focused Conceptual Review}

\begin{enumerate}[label=\textbf{Q\arabic*.}, start=21]

    \item A research analyst measures daily low temperatures recorded in degrees Fahrenheit across 10 meteorological stations. Which measurement scale best applies to these temperature values?
    \begin{enumerate}[label=(\Alph*)]
        \item Nominal scale
        \item Ordinal scale
        \item \textbf{Interval scale}
        \item Ratio scale
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (C) Interval scale\\
        \textbf{Rationale:} Temperatures on Fahrenheit or Celsius scales have equal unit differences but lack an absolute zero point, placing them on the interval scale.
    \end{tcolorbox}

    \item A national election board audits all $2{,}500{,}000$ cast ballots in a city election and reports that exactly $54\%$ voted for Candidate A. How is this $54\%$ value classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Sample statistic
        \item \textbf{Parameter}
        \item Sampling error
        \item Inferential estimate
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Parameter\\
        \textbf{Rationale:} Since all ballots cast across the entire target population were audited, $54\%$ represents a true population parameter.
    \end{tcolorbox}

    \item While conducting a health survey, an interviewer mistakenly enters a subject's height as $175$ meters instead of $175$ centimeters into the database. What type of statistical error has occurred?
    \begin{enumerate}[label=(\Alph*)]
        \item Sampling error
        \item \textbf{Non-sampling error}
        \item Random sampling variability
        \item Parameter deviation
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Non-sampling error\\
        \textbf{Rationale:} Operational errors such as data entry mistakes or mistranscriptions are classified as non-sampling errors.
    \end{tcolorbox}

    \item An academic investigator downloads economic datasets published in the World Bank Annual Report to evaluate inflation trends. Relative to the investigator's project, how is this dataset classified?
    \begin{enumerate}[label=(\Alph*)]
        \item Primary data
        \item \textbf{Secondary data}
        \item Continuous variable
        \item Discrete attribute
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Secondary data\\
        \textbf{Rationale:} Data gathered, organized, and published previously by another institution (the World Bank) represents secondary data to the investigator.
    \end{tcolorbox}

    \item A clinical trial evaluates a new medication on $400$ trial volunteers and concludes that the medication reduces blood pressure for all hypertensive adults nationwide. Which branch of statistics is illustrated?
    \begin{enumerate}[label=(\Alph*)]
        \item Descriptive statistics
        \item \textbf{Inferential statistics}
        \item Census tabulation
        \item Ordinal measurement
    \end{enumerate}
    \begin{tcolorbox}[colback=green!5!white,colframe=success,title=Answer \& Rationale]
        \textbf{Correct Answer:} (B) Inferential statistics\\
        \textbf{Rationale:} Extending results from a sample of 400 trial participants to form a conclusion about all nationwide adults is an inferential leap.
    \end{tcolorbox}

\end{enumerate}

\end{document}