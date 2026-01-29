---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Garv Airi} \\ \vspace{1pt}
    \small 540-522-6267 $|$ \href{mailto:x@x.com}{\underline{garvairi01@icloud.com}} $|$ 
    \href{https://linkedin.com/in/...}{\underline{linkedin.com/in/garv-airi/}} $|$ 
    {\small{Culpeper, VA}}
\end{center}
%-----------Objective-----------
\section{Objective}
    \resumeSubHeadingListStart
    \resumeItem
    {Third year Computer Engineering student with Hands on experience through projects. Seeking opportunity to apply my current skills in real practice and develop further skills through targeted mentorship in a team environment.}
%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Virginia Tech}{Blacksburg, VA}
      {Bachelor of science in Computer Engineering}{Aug. 2023 -- May 2027}
      \resumeItem {Cumulative GPA: 3/4.0}
      
   
    \resumeSubheading
      {Germanna Community College}{Culpeper, VA}
      {Associate's in Arts and Sciences}{Aug. 2021 -- May 2023}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Work Experience}
  \resumeSubHeadingListStart

  %----------Bald Top-------------
     \resumeSubheading
    {Bar-Back and Runner}{June 2025--present}
    {Bald Top Brewery}{Madison, VA}
    \resumeItemListStart
    \resumeItem{Ensured Guest expectations were met and exceeded, while maintaining proper team work is ensured}
    \resumeItem{Worked on a Point of sale system and ensured efficient transactions and proper guest interactions}
    \resumeItemListEnd
    
%-----------Target-----------
 
    \resumeSubheading
      {On-Demand Guest Advocate}{June 2021 -- Aug 2024}
      {Target}{Culpeper, VA}
      \resumeItemListStart
        \resumeItem{Provided exceptional customer service to clients in fast-paced retail environment.}
        \resumeItem{Learned on-the-fly to adapt to a fast paced culture and an ever growing business.}
       
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
%    \resumeSubSubheading
%     {Software Engineer I}{Oct 2014 - Sep 2016}
%     \resumeItemListStart
%        \resumeItem{Apache Beam}
%          {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
%     \resumeItemListEnd
%    \resumeSubHeadingListEnd
%-------------------------------------------
%-----------Boston Store-----------
    \resumeSubheading
      {Boston General store assistant}{June. 2021 -- Present}
      {Boston General Store}{Boston, VA}
      \resumeItemListStart
        \resumeItem{Learned how to provided a base for a growing community and deepened interpersonal skills as well as guest relations to provide an inviting atmosphere.}
      
    \resumeItemListEnd

    
  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Design Team} $|$ \emph{VT, CRO- Beamforming Subteam Lead}}{Feb 2025 -- June 2025}
          \resumeItemListStart
            \resumeItem{Programming Raspberry Pi Pico firmware with PIO, DMA, and SPI/I2C for phased-array beamforming}
            \resumeItem{Combining MAX586X DAC/ADC and MAX2822 RF ICs for RF-digital conversion}
            \resumeItem{Collaborating with RF/PCB teams to develop SDR-based phased array with analog frontend}
            \resumeItem{Using Wireshark to analyze digital beamformed output for WiFi conversion}
            \resumeItem{Researching OSI model \& GR-GSM for efficient RF-to-network transmission}
            \resumeItem{Managing proper communication and ensuring manageable goals and timelines are met.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Drone Simulator} $|$ \emph{C++}}{May 2023}
          \resumeItemListStart
            \resumeItem{Created a drone simulator in C++ by using given libraries using a functional programming language for pathfinding and flight dynamics. }
          \resumeItemListEnd
    \resumeSubHeadingListEnd



%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    \textbf{Certifications}{: CompTIA Security+ Cert Id: 3G82JV8YN2E1Q2C2}
    \\
     \textbf{Languages}{: , Python, C/C++, HTML/CSS, Verilog, VHDL} \\
     \textbf{CyberSecurity Tools}{: Wireshark, Metasploit, Kali Linux, Nmap} \\
     \textbf{Hardware Skills}{: Intel Quartus,  LTSpice, FPGA Design, Verilog, } \\
      \textbf{General Skills}{: Computer Skills( Powerpoint, Word, Sheets), Customer Service, Photoshop  } \\
     \textbf{Languages Spoken}{: Converstational in Hindi and Punajbi, and a Basic understanding of Spanish}
    }}
 \end{itemize}

 %-----------PROGRAMMING SKILLS-----------
\section{Extracurriculars}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    \textbf{TaeKwonDo}{: For 7 years I did taekwondo under an instructor, and then 6 years as a taekwondo instructor.}
    \\
\textbf{Track And Field}{: I ran track and field for 4 years and spent 2 of those years as a captain for the team, helping lead workouts and provide a foundation of good standing with coaches and athletes.}
\end{itemize}

%-------------------------------------------
\end{document}
