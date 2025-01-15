
## Graphics Formats
- Two main types: raster and vector graphics
- Raster graphics are composed of pixels (dot-square of color)
- Vector graphics are composed of paths
- Resolution measured by columns/rows or total pixels
- Pixel density measured in dots/pixels per inch (PPI)

### Color Systems
- Raster formats: monochrome, palletized, grayscale, full color
- RGB: Red, Green, Blue (additive)
- CMYK: Cyan, Magenta, Yellow, Black (subtractive)
- RGBA: Includes alpha channel for opacity
- Color spaces standardize hues of primaries
- Dithering achieves color combinations from primary colors

### Compression Methods
#### Lossless Compression
- Run length coding: encodes sequences of same pixels
- Block wise coding: identifies squares of same color
- Quad tree coding: splits into quadrants
- Huffman coding: common values get shortest bit sequences
- Examples: GIF, PNG

#### Lossy Compression
- Discrete cosine transformation: converts image to frequency domain
- Chroma subsampling: reduces color information while maintaining brightness
- Quantization: rounds DCT values to fewer levels

## Audio Processing
### Pulse-Code Modulation (PCM)
1. Sampling: measures signal at regular intervals (e.g., 44.1 kHz)
2. Quantization: maps values to discrete amplitude levels
3. Encoding: converts to binary numbers

## Data Formats

### Key-Value Formats
- Properties: Java-specific hash table, used for configurations
- INI files: 2-level hash table, human readable
- TOML: Human readable, maps to hash table
- YAML: Supports nested structures

### Text Document Formats
- Plain text (.txt)
- Rich text: simple formatting
- HTML: web standard
- Markdown: human-readable markup
- LaTeX: for academic documents and complex formatting

### Data Description Frameworks
#### RDF (Resource Description Framework)
- Graph-based data model using triples (subject-predicate-object)
- Uses URIs for resource identification
- Supports blank nodes and prefixes
- RDFS defines vocabularies and hierarchies

#### SPARQL
- Query language for RDF data
- Supports functions like COUNT, SUM, AVG, MIN, MAX
- Uses WHERE clauses and FILTERS

#### Labeled Property Graph (LPG)
- Oriented multi-graph
- Nodes have labels and properties
- Edges have labels and properties
- Queried using Cypher language

### XML Technologies
- DOM: loads entire document in memory
- SAX: processes as stream of events
- StAX: similar to SAX but with pull-based parsing
- XML Schema for validation
- XPath for navigation
- XSLT for transformation

## Standards and Vocabularies
- RFC (Request for Comments) for internet standards
- Dublin Core (dcterms) for metadata
- SKOS for knowledge organization
- Good Relations (gr) for e-commerce
- Wikidata for structured facts
