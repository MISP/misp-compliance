# misp-compliance

Legal, procedural and policies document templates for operating MISP and information sharing communities following existing regulations, laws or policies.

This repository is a collaborative effort to improve the state of information sharing and exchange within and outside the MISP Project.

## Information sharing and cooperation enabled by GDPR

The General Data Protection Regulation (GDPR) aims to reduce legal uncertainty and limit the interpretations by setting out clear rules and conditions for the processing and sharing of personal data as well as t
he protection of natural persons with regard to the processing of personal data. Organisations must ensure that, they process only the minimum amount of personal data necessary to achieve their lawful processing
 purposes. To this end, the GDPR distinguishes the roles and obligations of data processors and data controllers, provides precise definitions of personal data and establishes the conditions under which informat
 ion can be shared.

National and governmental Computer Security Incident Response Team (n/g CSIRTs) are teams that serve the government of a country by helping with Critical Information Infrastructure Protection (CIIP). They coordinate incident management with the relevant stakeholders at national level, and cooperate with the national and governmental teams in other countries.

 The [Malware Information Sharing and Threat Intelligence Sharing Platform (MISP)](https://www.misp-project.org/) is a software for sharing, storing and correlating indicators of compromise of targeted attacks, cybersecurity threats and financial fraud indicators, among which SHA1 hashes (a cryptographic function to fingerprint files), threat actor names and Bitcoin addresses. The MISP data model is composed of "events", which usually represent threats or incidents, which in turn are composed of a list of "attributes" (e.g. IP addresses, domain names etc..). Other data models exist in MISP such as "objects", which allow advanced combinations of attributes and "galaxies" which enable a deeper analysis and categorisation of events.

Information sharing communities are enabled using tools like MISP. As a Computer Security Incident Response Team for the private sector communes and non-governmental entities in Luxembourg, [CIRCL](https://www.circl.lu/) created and operates several communities to automate information sharing at national, European and international levels.

- [Document in Markdown format](./GDPR/information_sharing_and_cooperation_gdpr.md)

## MISP as supporting platform for sharing information, following ISO/IEC 27010:2015

Threat intelligence sharing comes with its own caveats and presents a few challenges. For example, organisations may end up with raw, unevaluated data, which adds an extra burden to the security team of the organisations by increasing the number of events and alerts rather than decreasing them. Moreover, some security vendors loath to share information to avoid losing the competitive edge.

Some of these issues are dealt by the ISO/IEC 27000-series (also known as the 'ISMS Family of Standards' or 'ISO27k' for short) of standards. It comprises information security standards published jointly by the International Organisation for Standardisation (ISO) and the International Electro technical Commission (IEC). The ISO/IEC 27000 series of standards provides best practice recommendations on information security management.
The series is deliberately broad in scope, covering more than just privacy, confidentiality and cybersecurity issues. It is applicable to organisations of all shapes and sizes. All organisations are encouraged to assess their information risks, then treat them  according to their needs, using the guidance and suggestions where relevant (typically using information security controls).

One of such standards is ISO/IEC 27010:2015, covering ‘Information security management for inter-sector and inter-organisational communications’, a supplement to ISO/IEC 27001:2013 and ISO/IEC 27002:2013 for use by information sharing communities.

Standard ISO/IEC 27010 (hereafter, the standard) is particularly relevant for MISP because it provides controls and guidance specifically relating to initiating, implementing, maintaining, and improving information security in inter-organisational and inter-sector communications. Moreover, it provides guidelines and general principles on how the specified requirements can be met using established messaging and other technical methods.

The standard is applicable to all forms of exchange and sharing of sensitive information, both public and private, nationally and internationally, within the same industry or market sector or between sectors. In particular, it may be applicable to information exchanges and sharing relating to the provision, maintenance and protection of an organisation or nation state's critical infrastructures. It is designed to support the creation of trust when exchanging and sharing sensitive information, thereby encouraging the international growth of information sharing communities.

- [Document in Markdown format](./ISO_IEC_27010/misp-sharing-information-following-ISO-IEC-27010.md)

# Contributing

If you see any errors in the documents or would like to propose changes or updates, feel free to open an issue.

You can also directly update the documents by forking the project and then update the documents and finally do a pull-request.

# Contributors and Funding

These documents were partially funded by CEF (Connecting Europe Facility) funding under CEF-TC-2016-3 - Cyber Security ***Improving MISP as building blocks for next-generation information sharing***.
Complementary funding was from the CIRCL Computer Incident Response Center Luxembourg CSIRT activities.
