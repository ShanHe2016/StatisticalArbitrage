
% 5.tex
\documentclass[letterpaper,11pt]{article}

\setlength{\oddsidemargin}{0.2in}
\setlength{\textwidth}{16.2cm}
\setlength{\topmargin}{-0.8in}
\setlength{\textheight}{9in}
\setlength{\parskip}{1em}
\setlength{\baselineskip}{15pt}
\setlength{\parindent}{12pt}
\setlength{\skip\footins}{0.8cm} % space between text body and footnote
\usepackage{indentfirst}
\usepackage{amsfonts,amsmath,verbatim,graphicx, subfigure,longtable}
\usepackage{amssymb,amsthm,amscd}
%\usepackage{pdfsync}
%\usepackage{hyperref}
\usepackage[pdfstartview=FitH,bookmarks=false,unicode=false,pdftoolbar=true,pdfmenubar=true,]{hyperref}
\usepackage{pstricks}
\usepackage{epstopdf}
\usepackage{color}
\usepackage{transparent}
\usepackage{tikz}


\usetikzlibrary{fit, positioning}
\newtheorem{thm}{Theorem}[section]
\newtheorem{cor}[thm]{Corollary}
\newtheorem{prop}[thm]{Proposition}
\newtheorem{lem}[thm]{Lemma}
\newtheorem{definition}[thm]{Definition}
\newtheorem{assumption}[thm]{Assumption}
\newtheorem{conjecture}[thm]{Conjecture}
\newtheorem{claim}[thm]{Claim}
\newtheorem{open}[thm]{Open Problem}
\newtheorem{example}[thm]{Example}
\newtheorem{remark}[thm]{Remark}
\newcommand{\qn}{\noindent{\bf Question: \,}}
\newenvironment{pf}{\noindent\emph{Proof \,}}{\mbox{}\qed}

\newcommand{\Var}{\operatorname{Var}}
\newcommand{\tr}{\operatorname{tr}}
\newcommand{\supp}{\operatorname{supp}}
\newcommand{\toL}{\,{\buildrel \mathcal{L} \over \longrightarrow}\,}
\newcommand{\equalL}{\,{\buildrel \mathcal{L} \over =}\,}

\def\wh{\widehat}

\numberwithin{equation}{section}
\def\AA{{\mathbb A}}     % State space
\def\R{{\mathbb R}}     % Real numbers
\def\Z{{\mathbb Z}}     % Integers
\def\P{{\mathbb P}}     % Probability
\def\Q{{\mathbb Q}}     % Probability
\def\E{{\mathbb E}}     % Expectation
\def\D{{\mathcal E}}    % Dirichlet form
\def\F{{\mathcal F}}    % Domain of Dirichlet form
\def\G{{\mathcal G}}    % Domain of Dirichlet form
\def\H{{\mathcal H}}    %
\newcommand{\PP}{\mathbf{P}}
\newcommand{\EE}{\mathbf{E}}

\def\X{{\mathfrak X}}   % Empirical process
\def\Y{{\mathcal Y}}   % Fluctuation process

\def\bX{{\bar{\mathfrak X}}}   % Empirical_\bar{X} for RBMs without annihilation
\def\bY{{\bar{\mathcal Y}}}   % Fluctuation_\bar{Y} for RBMs without annihilation
\def\ZZ{{\mathcal Z}}
\def\A{{\mathcal A}}   % Generator of a reflected diffusion
\def\L{{\mathfrak L}}   % Generator of \eta

\def\eps{\varepsilon}
\def\<{{\langle}}
\def\>{{\rangle}}
\def\1{{\bf 1}}         % Indicator

\newcommand{\ip}[1]{\langle #1 \rangle}
\newcommand{\TODO}[1]{\textbf{#1}}
\renewcommand{\bar}{\overline}
\renewcommand{\abstractname}{Executive Summary}
\begin{document}
\allowdisplaybreaks

\title{\Large \bf
ORIE 4741 Course Project Proposal\\
Application of Machine Learning Techniques in Statistical Arbitrage
 }

\author{{\bf Zicheng Men, Sheng Zhang, Shan He} }
\date{\today}
\maketitle


% Shift F8 = Synchronize

\section*{\centering{Executive Summary}}
	In this project, we propose to apply machine learning techniques we learned from the course ORIE 4741 to the topic of statistical arbitrage. The central question we would like to answer is: \emph{how to decide if an arbitrage opportunity appears in the stock market?} To answer this question, we would like to generate trading signals to alert investors of potential arbitrage opportunities by using supervised learning method and Principal Component Analysis. 
	
	Statistical arbitrage is defined as the automated trading strategy that identifies statistical mispricing of one or more assets (stock in our case) according to its historical expected value. It relies heavily on statistical analysis and data mining techniques. Since arbitrage opporunity is considered as riskless profit for investors or traders, topic of statistical arbitrage can be very important for trading and investment companyies, especially algorithmic trading company. Statistical arbitrage coupled with high-speed automated trading systems can generate enormous profits for algo-trading companies. It also helps to reinforce the efficiency of the market, since it can lay pressure upon the stock price to return to its "true" value by continously capturing stocks mispricing. Moreover, it is also valuable for non-profit purpose. The trading signals generated from our model can be used as benchmark for investors' own stock analysis.   
	
	Since we focus on stock arbitrage opportunities in this project, the dataset we plan to use is the stock closing price of the companies listed in Russel 2000 index over a 10-year period. Since companies from Russel 2000 are identified as small-cap companies, which, generally speaking, receive less attention from the public, therefore are more likely to be mispriced. An alternative approach to determine the dataset is to select stocks with low volumes.    
	


 




\end{document}



