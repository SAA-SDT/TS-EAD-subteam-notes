This folder will be providing access to various documents in relation to the major revision of EAD. During the two calls for comments (one in spring through mid-summer 2024 and one in late autumn/early winter 2024), more documents will be added here or linked form here step by step. 

- The [Infograph](https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/Infograph.pdf) highlights the benefits of EAD 4.0 at a glance.
- The [Editorial](https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/Editorial_ChangesInEAD4.0.pdf) discusses the main strands of changes that can be found in EAD 4.0 compared to the predecessor version EAD3. It includes examples and links to GitHub issues for more details, but doesn't cover each and every dot of the draft for the new version.
- The draft version of the [EAD 4.0 Revision Notes](https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/RevisionNotesEAD4.0.pdf) details the changes suggested in EAD 4.0 in comparison to the predecessor version EAD3 in textual form. This includes some general statistics about these changes and groups elements and attributes affected by the same type of change. 
- The draft version of the [EAD 4.0 schema](https://github.com/SAA-SDT/eas-schemas/releases/tag/v0.1.0-alpha) provides a technical entry point into the new version, which can be read as information in itself, but can also be used e.g. in trying to adapt existing EAD 2002 or EAD3 files to the new version.
  - We do not have an official transformation script to convert to EAD 4.0 yet, but e.g. manual adaptation in an XML editor is possible when associating existing files with the draft schema.
  - The draft schema is available in three formats: XSD, RNG (included in the source code packages linked from the pre-release page above), and NVDL (which allows for an integrated testing and joint validation of the XHTML embedding options in EAD 4.0).
  - The package also includes a draft schematron for EAD 4.0 for specific validation scenarios, e.g. against the ISO standard 8601 for dates if used for normalised dates in your EAD files.
- The [Transformation Routes](https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/FromEAD3toEAD4.0_TransformationRoutes.pdf) spreadsheet gives a detailed overview of what would need to be changed for each EAD3 element, its sub-elements (if applicable) and its attributes to be transformed into EAD 4.0.
- The [Changes in the Schema](https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/FromEAD3toEAD4.0_ChangesInTheSchema_Elements.pdf) spreadsheet provides these same details, but from the perspective of how the EAD 4.0 schema differs from the EAD3 (deprecated) schema; i.e. this spreadsheet also includes notes about new elements that will be available in EAD 4.0, new optional sub-elements and new optional attributes, which offer new extended possibilities when starting fresh in EAD 4.0, but do not necessarily play a role when transforming from previous versions
- We have started to create [Example files](https://github.com/SAA-SDT/EAS-Best-Practices/tree/examples/_examples/ead4-call-for-comments) in EAD 4.0 and will make more of these available for illustration throughout the call for comments phase.
  - The ead4-starter-file.xml can be used as a basis when you want to get to know EAD 4.0 by creating a file from scratch. It has been pre-associated with both the draft schema and schematron.
  - The file APE_BL_EAD2002exampleAdapted.xml has been adapted manually from EAD 2002 using the Oxygen XML editor. The EAD 2002 XML file used was provided to Archives Portal Europe in September 2019 and follows the EAD 2002 application profile as defined for the portal, see https://www.archivesportaleurope.net/schemas/ead/apeEAD.xsd
  - The file LoC_EAD3exampleAdapted.xml has been adapted manually from EAD3 using the Oxygen XML editor. The EAD3 file used was downloaded from the Library of Congress' catalogue on 24 January 2024.

Throughout the Call for Comments phase, we will hold several open drop-in sessions to present various aspects of the revision and the new version of EAD and to allow the community to ask questions, e.g. in preparation to submitting comments. The slide decks used during these sessions are also added to this folder here:

- 1st Open Session[https://github.com/SAA-SDT/TS-EAS-subteam-notes/blob/master/ead-subteam/major-revision_2021-2025_documents/20240424_EAD4CallForComments_Session1.pdf] on 24 April 2024, 10am UTC and 4pm UTC (both iterations with the same content)

Furthermore, we are running a 5-piece series together with the colleagues of the SAA Description Section on their blog "Descriptive Notes". Follow along for a more general introduction into the main aspects of this current revision.

- 1st blog post[https://saadescription.wordpress.com/2024/03/05/shape-the-future-of-ead-a-call-to-action-part-i/] from 5 March 2024 about the why and how of the revision
- 2nd blog post[https://saadescription.wordpress.com/2024/04/22/shape-the-future-of-ead-a-call-to-action-part-ii/] from 22 April 2024 focussing on the alignment between EAD and its sibling standard EAC-CPF