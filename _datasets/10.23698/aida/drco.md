---
datacite:
  "@context": "http://schema.org"
  "@type": "Dataset"
  "@id": "https://doi.org/10.23698/aida/drco"
  name: "Colon data from the Visual Sweden project DROID"
  about: "Pathology"
  url: "https://datasets.aida.medtech4health.se/10.23698/aida/drco"
  author:
    - name: "Karin Lindman"
      "@id": "https://orcid.org/0000-0003-1298-517X"
      "@type": "Person"
    - name: "Martin Lindvall"
      "@id": "https://orcid.org/0000-0002-7014-8874"
      "@type": "Person"
    - name: "Caroline Bivik Stadler"
      "@id": "https://orcid.org/0000-0001-7250-234X"
      "@type": "Person"
    - name: "Claes Lundstrom"
      "@id": "https://orcid.org/0000-0002-9368-0177"
      "@type": "Person"
    - name: "Darren Treanor"
      "@id": "https://orcid.org/0000-0002-4579-484X"
      "@type": "Person"
  publisher:
    "@type": "Organization"
    name: "AIDA"
  copyrightYear: 2019
  copyrightHolder:
    - name: "Linköping University"
      url: "https://liu.se/"
      "@type": "Organization"
    - name: "Claes Lundström"
      "@id": "https://orcid.org/0000-0002-9368-0177"
      "@type": "Person"
  provider:
    - name: "Karin Lindman"
      email: "Karin.Lindman@regionostergotland.se"
      "@id": "https://orcid.org/0000-0003-1298-517X"
      "@type": "Person"
    - name: "Claes Lundstrom"
      email: "claes.lundstrom@liu.se"
      "@id": "https://orcid.org/0000-0002-9368-0177"
      "@type": "Person"
    - name: "Caroline Bivik Stadler"
      email: "caroline.bivik.stadler@liu.se"
      "@id": "https://orcid.org/0000-0001-7250-234X"
      "@type": "Person"
    - name: "Joel Hedlund"
      email: "joel.hedlund@liu.se"
      "@id": "https://orcid.org/0000-0001-6443-3604"
      "@type": "Person"
  dateCreated: "2019-01-09"
  datePublished: "2019-01-09"
  dateModified: "2019-01-09"
  keywords: "Pathology, Colon, Whole slide imaging, Annotated"
  version: "1.0"
  description: |
    The dataset consist of 101 colon whole slide images (WSI): 52 abnormal and
    49 benign.
  license:
    - name: "Restricted access"
      id: "https://datasets.aida.medtech4health.se/10.23698/aida/drco#license"
      "@type": "CreativeWork"
  citation:
    #- "@type": "CreativeWork"
    #  "@id": "https://doi.org/..."
    #  name: "Title of paper goes here"
other:
  shortName: "DRCO"
  status: "Completed"
  annotation: |
    One physician was responsible for the manual annotations controlled by a
    second pathologist. Accurate annotations were made over the whole tissues.
    1238 separate annotations were made.

    Following abnormal findings were annotated for the malign cases: acute and
    chronic inflammation, acute inflammation, adenocarcinoma, atrophy, chronic
    inflammation, diverticula, diverticulitis, dysplasia, edema, fibrosis,
    granulations tissue, hemorrhage, hyalinization, hyperplasia, hyperplastic
    polyp, inflammation, lymphoma, mucinous adenocarcinoma, necrosis, serrated
    adenoma, stasis, tubular adenoma, tubulovillous adenoma and ulceration.

    Other areas annotated: abnormal, artifact, cecum, colon, colonic mucous
    membrane, colonic muscularis propria, colonic submucosa, colonic subserosa,
    descending colon, ileum, normal, rectum, sigmoid colon and transverse colon.

    For the benign cases following areas were annotated: artifact, cecum, colon,
    colonic mucous membrane, colonic muscularis propria, colonic submucosa,
    colonic subserosa, descending colon, ileum, normal, rectum, sigmoid colon
    and transverse colon.
  download:
    links:
      - text: ""
        url: ""
  organ:
    - name: "Colon"
      sctid: 71854001 # SNOMED-CT https://termbrowser.nhs.uk/?perspective=full&conceptId1=%s
  age-span: "22-90 years"
  bytes: 49227210891
  numberOfScans: 101
  numberOfAnnotations: 1238
  resolution: "40X single plane"
  modality:
    - "SM"
  scanner:
    - "Scanscope AT (Aperio, US)"
    - "NanoZoomer XR (Hamamatsu, Japan)" # FIXME: is this same as "Hamamatsu NanoZoomer-XR C12000 series 2013"?
    - "NanoZoomer XRL (Hamamatsu, Japan)" # FIXME: is this same as "Hamamatsu NanoZoomer 2.0 HT C9600 series 2013"
  stain: "H&E (hematoxylin and eosin)"
  phase:
  exampleImage:
    - title: "Overview of whole slide imaging."
      url: "/assets/images/10.23698/aida/drco/wsi.jpeg"
      thumbnail-url: "/assets/images/10.23698/aida/drco/wsi-thumbnail.jpeg"
    - title: "Overview of annotations."
      url: "/assets/images/10.23698/aida/drco/annotations.jpeg"
      thumbnail-url: "/assets/images/10.23698/aida/drco/annotations-thumbnail.jpeg"
    - title: "Overview of carcinoma whole slide imaging."
      url: "/assets/images/10.23698/aida/drco/carcinoma.jpeg"
      thumbnail-url: "/assets/images/10.23698/aida/drco/carcinoma-thumbnail.jpeg"
    - title: "Overview of carcinoma annotations."
      url: "/assets/images/10.23698/aida/drco/carcinoma-annotations.jpeg"
      thumbnail-url: "/assets/images/10.23698/aida/drco/carcinoma-annotations-thumbnail.jpeg"
    - title: "To-scale view of pixel resolution in original whole slide imaging data."
      url: "/assets/images/10.23698/aida/drco/to-scale.jpeg"
      thumbnail-url: "/assets/images/10.23698/aida/drco/to-scale-thumbnail.jpeg"
---
## License
Copyright
{{ page.datacite.copyrightYear }}
{{ page.datacite.copyrightHolder | map: "name" |  join: ", " }}

Permission to use, copy, modify, and/or distribute this data within Analytic
Imaging Diagnostics Arena ([AIDA](https://medtech4health.se/aida)) for any
purpose with or without fee is hereby granted, provided that the above copyright
notice and this permission notice appear in all copies, and that publications
resulting from the use of this data cite the following works:

{{ page.datacite.author | map: "name" | array_to_sentence_string }}
({{ page.datacite.datePublished | date: "%Y" }})
{{ page.datacite.name }}
[doi:{{ page.datacite['@id'] | remove: "https://doi.org/" }}]({{ page.datacite["@id"] }}).

THE DATA IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD
TO THIS DATA INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN
NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR
CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA
OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS
ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR CHARACTERISTICS OF THIS
DATA.
