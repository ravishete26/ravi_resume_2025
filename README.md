%-------------------------
% Resume in Latex
% Author : Abey George
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
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}




\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}






%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}


% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}




% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}


% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}


\urlstyle{same}


\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}


% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
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


\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}


\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
     
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
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}


\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}


\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}




\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}


%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%




\begin{document}


%----------HEADING----------




\begin{center}
    {\Huge \scshape Ravi Babasaheb Shete} \\ \vspace{1pt}
    Pune,Maharashtra\\ \vspace{1pt}
    \small \href{tel:+91- 8208350797}{ \raisebox{-0.1\height}\faPhone\ \underline{+91 8208350797} ~} \href{mailto:ravishete261999@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{Ravishete261999@gmail.com}} ~
    \href{https://linkedin.com/in/ravishete26}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{linkedin.com/in/ravishete26}}  ~
    \href{https://github.com/ravishete26}{\raisebox{-0.2\height}\faGithub\ \underline{https://github.com/ravishete26}} ~
    
  \href{https://Kaggle.com/ravishete261999}{\raisebox{-0.2\height}\faGithub\ \underline{https://www.kaggle.com/ravishete261999}} ~    \href{https://www.hackerrank.com/yourid}
    {\raisebox{-0.2\height}\faHackerrank\ \underline{}} ~

    \vspace{-8pt}
\end{center}




%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
    {I.B.M.R.D. Ahmednager.}{07 2023 -- 06 2025}
    {M.C.A. (Master of Computer Applications)- \textbf{CGPA :- 7.46} \textbf{}}{Ahmednager, Maharashtra}
  \resumeSubHeadingListEnd

  \resumeSubHeadingListStart
    \resumeSubheading
    {Yeshwant College of IT, Parbhani.}{05 2019 -- 06 2021}
    {B.C.A. (Bachelor of Computer Applications)- \textbf{CGPA} - \textbf{9.03}}{Parbhani, Maharashtra}
  \resumeSubHeadingListEnd
  
 
  \resumeSubHeadingListStart
    \resumeSubheading
      {D.S.M, Parbhani.}{05 2016 -- 07 2018}
      {HSC - Commarce  - \textbf{Percentage} - \textbf{70.77\%}}{Parbhani, Maharashtra}
  \resumeSubHeadingListEnd


%------RELEVANT COURSEWORK-------
\section{COURSEWORK / SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item Database Management System (DBMS)
                
                \item OOPS Concept
                \item Web Development
                \item Artificial Intelligence
                \item Python 
                \item Operating Systems
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd






%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
       \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{HR Analytics Dashboard}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Python,Numpy,Pandas,Microsoft Power Bi, IDE - Jupyter}}}{05 2023}
          \resumeItemListStart
            \resumeItem{\normalsize{About project \textbf{• In the modern workplace, data-driven decisions are crucial, especially when it comes to managing and optimizing our human resources. Our new HR Analytics Dashboard provides invaluable insights that empower HR professionals and decision-makers to make informed choices that drive organizational growth and employee satisfaction.}.}}


            \resumeItem{\textcolor{accent} {\href{Live Project Link} {\underline{\normalsize{}}}}}
          \resumeItemListEnd
          \vspace{-13pt}
        
%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    \textbf{\normalsize{Programming Languages:-}}{ \normalsize{Python}} \\
    \textbf{\normalsize{Database:-}}{ \normalsize{My SQL}} \\
    \textbf{\normalsize{Data manipulation :-}}{ \normalsize{Numpy , Pandas, Excel}} \\
    \textbf{\normalsize{Data Visualization :-}}{ \normalsize{Matplotlib , Seaborn , Plotly}} \\
    \textbf{\normalsize{Business Intelligence:-}}{ \normalsize{Microsoft Power BI}} \\
    \textbf{\normalsize{Data Analysis using:-}}{ \normalsize{Microsoft Excel}} \\     
 \end{itemize}
 \vspace{-15pt}

%-----------INVOLVEMENT---------------
\section{EXTRACURRICULAR}
    \resumeSubHeadingListStart
        \resumeSubheading{IBMRD \href{Certificate Proof link}{\raisebox{-0.1\height}\faExternalLink } }{02 2022 -- 03 2022}{\underline{volunteer }
        }
        {Ahmednager}
            \resumeItemListStart
                \resumeItem{\normalsize{Professional tone:- \textbf{Proud to have honed my leadership and organizational skills through volunteer work and team leadership roles. These experiences have taught me the value of teamwork, responsibility, and making a positive impact}}}


            \resumeItem{\normalsize{Personal touch:- \textbf{From volunteering to team leadership, every role taught me the power of collaboration and responsibility. Excited to bring these experiences into my professional journey!}}}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
 \vspace{-11pt}
 
 %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}

$\sbullet[.75] \hspace{0.2cm}${\href{https://www.linkedin.com/posts/ravishete26_infosysspringboard-activity-7228068862309670913-9chW?utm_source=share&utm_medium=member_desktop}{Infosys (Python)}} \hspace{1cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{SQL}} 
\hspace{0.2cm}

$\sbullet[.75] \hspace{0.1cm}$ {\href{https://www.linkedin.com/posts/ravishete26_aws-cloudcomputing-certification-activity-7198891908100739072--weT?utm_source=share&utm_medium=member_desktop}{AWS}} 
\hspace{0.2cm}

$\sbullet[.75] \hspace{0.2cm}${\href{https://www.linkedin.com/posts/ravishete26_cyber-security-activity-7224366907481550848-8ruq?utm_source=share&utm_medium=member_desktop} {NATIONAL INSTITUTE OF ELECTRONICS & INFORMATION TECHNOLOGY (NIELIT),Cyber Security}}\\
\hspace{0.2cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{https://www.cloudskillsboost.google/public_profiles/cf0a73e8-fb1b-4097-a95d-438eb11694cf?qlcampaign=+EDUCR-GCAF24Facilitators-IN%3A%3ATpkUC50Y4DHGoo-o6kVBwg+}{GOOGLE CLOUD ARCADE FACILITATOR PROGRAM}} 
\hspace{0.2cm}

\end{document}





