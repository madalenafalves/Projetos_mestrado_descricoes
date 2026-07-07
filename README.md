# Projetos_mestrado_descrição

Projeto_final_priv: There are many different ways to protect privacy. Some are required by law, some are recommended by law, and
some offer more protection than the law has yet to mandate. Depending on the amount of protection, a company
may lose the utility that the data they collected provides. At the same time, without enough protection and there
is bound to be a data breach, compliance investigations, and a public relations nightmare.
In this project your group will be implementing several different methods of protection, as well as attempting to
attack some. First you will go through simple de-identification of a dataset. Then you will attack it to see how
de-identification may not be enough. Then you will implement k-anonymity for the same dataset, and attempt the
attack again. Finally, you will implement a differential privacy middleware that will accept queries from clients and
respond using Laplace differential privacy.

Projeto_privacidade2: The goal of this project is to analyze and improve path selection in Tor circuits, focusing on geographic privacy.
The identified problem is that entire circuits can be located in the same country, increasing the risk of deanonymization by national authorities. The original Tor algorithm only avoids multiple nodes in the same /16 subnet, which does not guarantee protection against country-level adversaries. ->  https://github.com/madalenafalves/projeto_privacidade2  <-

Projeto1_ssc: The objective of this assignment is to design and implement a client–server system using
TCP sockets (as a possible primary solution), where the server provides a persistent, encrypted block
storage service for clients to store files as encrypted blocks. The system must guarantee the
confidentiality, integrity, and authenticity of stored file blocks while supporting basic file operations
and metadata-based search functionality, providing a solution for searchable encryption of
blockstorage contents when clients want to search files by using keywords used as metadata. This
assignment covers network programming, operating systems, file system management, and applied
cryptography, giving students experience in implementing secure client–server communication and
secure storage, with practical guarantees for confidentiality, integrity, and authenticity, including a
solution for searchable encryption.
->  https://github.com/madalenafalves/projeto_SSC  <-

Projeto_final_ssc: This project focuses on the design, implementation, and experimental evaluation of a
decentralized, oblivious Identity and Access Management (IAM) solution that must be
integrated with the secure and searchable block-storage service previously developed in
Project 1.
The solution is composed of two core components of the required Oblivious IAM
approach:
• Oblivious Authentication Server (OAS):
A persistent and concurrent server that manages user registration, relying solely on
anonymous identifiers and anonymized attributes associated with registered
anonymized identities.
• Oblivious Access Management Server (OAMS):
A persistent and concurrent server responsible for managing authorizations expressed
through anonymized access control, supporting the sharing of access for GET and
SEARCH operations in the Oblivious Block Storage service.
• Integration of the OAS and OAMS with the Oblivious Block Storage Server
(OBSS), a persistent and concurrent server based on the implementation from Project
1, providing support for the same operations already implemented there.
• Within this project, the OBSS functions as a specific resource service integrated
into the proposed IAM architecture. The solution to be designed and developed
must include the implementation of the OAS, the OAMS, their integration with the
OBSS, and a client capable of using the operations provided by these oblivious
servers.
• All components must operate as distributed servers within a decentralized
architecture.
->  https://github.com/Hlnsm/ssc-projeto2  <-

Cloud_computing: This project focuses on developing the backend for a cloud application that manages collections of Lego sets. The system allows users to register, store information about their Lego sets, create auctions to sell them, and share comments. The main goal is to understand how cloud computing services can be used to build applications that are scalable, reliable, and easy to maintain.
The backend was implemented using Azure, making use of services such as App Service for hosting the Rest API, Blob Storage for storing media files, and Cosmos DB for managing structured data. To improve performance, Redis Cache was added to handle frequently accessed information, and Azure Functions were used to automate certain tasks like updating auctions or periodic data processing. Overall, the project aims to apply cloud technologies to design a practical and efficient system for managing Lego collections.

IPM_project: Creation of a website called SYNC. 
SYNC is a web application designed to support university students and work teams in organizing and managing tasks, deadlines, communication, and study sessions. The application combines collaborative and individual elements, offering all the necessary functionalities for group coordination and academic planning in a single digital space. Its structure, inspired by the concept of servers and channels, aims to be intuitive, consistent, and suited to the real needs of users identified during the previous phases of the project.
->   https://github.com/JoaoGoncaloNunes13/IPM-SYNC   <-

Game: ia_75150_Madalena_Alves, Platform game with enemies and collectibles. Objective: Create a platform game that lasts 3 minutes and includes some obstacles along the way. Game name: Catnip.

QS_report: This is the specification for the report for QS2526p1. Two systems of non-trivial dimensions are to
be analyzed: (1) a system specific of each group selected by the students and registered at the
course’s wiki and (2) a system common to all groups (JHotDraw5.2) which will be used as
benchmark. You do not need to run the systems.
The report is intended to present 2 exploration fronts: (1, 2) reverse engineering analyses of the two
subject systems and (3) the exploration of one of the plugins for IntelliJ used for this assignment.
The concepts covered by the reverse engineering analyses include: (1) metrics and combinations of
metrics, with a focus on those covered in the Lanza book; (2) code smells and design disharmonies
covered in the Lanza and Fowler books; (3) duplicaton or code clones.
The report should include at the beginning a section with a short presentation of the specific subject
system, e.g., version numbers, application domain, whether is a full-fledged application or a
framework, mode of expected use (e.g., web, standalone), build tool used. There is no need to do
same for the common system. The report should also state de tools used. One paragraph should be
enough.
In case you have something useful to say about how the system analyzed it was mounted on
IntelliJ, technical obstacles overcame, or any prior “curating” that was required, please describe
it in the section presenting the system in a way that can be easily replicated (think of a material for a
practical session in future editions of QS). Fortunately, such issues seem less likely for IntelliJ
than for the Eclipse tools used in previous editions of QS.

Interactive_Gallery: Projeto em openFrameworks para uma galeria 3D de imagens e videos.
Requisitos
Visual Studio com suporte para C++.
openFrameworks para Visual Studio.
Addons:
ofxXmlSettings
ofxOpenCv
->   https://github.com/Hlnsm/Multimedia-Interactive-Gallery-   <-
