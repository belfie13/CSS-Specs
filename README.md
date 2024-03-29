# CSS-Specs
Compilation of _CSS 2.1_ and W3C Recommendations that replace sections

* 1 About the _CSS 2.1_ Specification
    * 1 _CSS 2.1_ vs CSS 2
    * 2 Reading the specification
    * 3 How the specification is organized
    * 4 Conventions
        * 1 Document language elements and attributes
        * 2 CSS property definitions
            * 1 Value
            * 2 Initial
            * 3 Applies to
            * 4 Inherited
            * 5 Percentage values
            * 6 Media groups
            * 7 Computed value
        * 3 Shorthand properties
        * 4 Notes and examples
        * 5 Images and long descriptions
    * 5 Acknowledgments
* 2 Introduction to _CSS 2.1_
    * 1 A brief _CSS 2.1_ tutorial for HTML
    * 2 A brief _CSS 2.1_ tutorial for XML
    * 3 The _CSS 2.1_ processing model
        * 1 The canvas
        * 2 _CSS 2.1_ addressing model
    * 4 CSS design principles
* 3 Conformance: Requirements and Recommendations
    * 1 Definitions
    * 2 UA Conformance
    * 3 Error conditions
    * 4 The text/css content type
* 4 Syntax and basic data types
    * 1 Syntax ghg@4.1 = [CSS-SYNTAX-3]@
        * 1 Tokenization
        * 2 Keywords
            * 1 Vendor-specific extensions
            * 2 Informative Historical Notes
        * 3 Characters and case
        * 4 Statements
        * 5 At-rules
        * 6 Blocks
        * 7 Rule sets, declaration blocks, and selectors
        * 8 Declarations and properties
        * 9 Comments
    * 2 Rules for handling parsing errors ghg@4.2 = [CSS-SYNTAX-3]@
    * 3 Values
        * 1 Integers and real numbers
        * 2 Lengths
        * 3 Percentages
        * 4 URLs and URIs
        * 5 Counters
        * 6 Colors
        * 7 Strings
        * 8 Unsupported Values
    * 4 CSS style sheet representation ghg@4.4 = [CSS-SYNTAX-3]@
        * 1 Referring to characters not represented in a character encoding
* 5 Selectors
    * 1 Pattern matching
    * 2 Selector syntax
        * 1 Grouping
    * 3 Universal selector
    * 4 Type selectors
    * 5 Descendant selectors
    * 6 Child selectors
    * 7 Adjacent sibling selectors
    * 8 Attribute selectors
        * 1 Matching attributes and attribute values
        * 2 Default attribute values in DTDs
        * 3 Class selectors
    * 9 ID selectors
    * 10 Pseudo-elements and pseudo-classes
    * 11 Pseudo-classes
        * 1 _`:first-child`_ pseudo-class
        * 2 The link pseudo-classes: _`:link`_ and _`:visited`_
        * 3 The dynamic pseudo-classes: _`:hover`_, _`:active`_, and _`:focus`_
        * 4 The language pseudo-class: _`:lang`_
    * 12 Pseudo-elements
        * 1 The _`:first-line`_ pseudo-element
        * 2 The _`:first-letter`_ pseudo-element
        * 3 The _`:before`_ and _`:after`_ pseudo-elements
* 6 Assigning property values, Cascading, and Inheritance
    * 1 Specified, computed, and actual values
        * 1 Specified values
        * 2 Computed values
        * 3 Used values
        * 4 Actual values
    * 2 Inheritance
        * 1 The _`inherit`_ value
    * 3 The _`@import`_ rule
    * 4 The cascade
        * 1 Cascading order
        * 2 _`!important`_ rules
        * 3 Calculating a selector's specificity
        * 4 Precedence of non-CSS presentational hints
* 7 Media types
    * 1 Introduction to media types
    * 2 Specifying media-dependent style sheets
        * 1 The `@media` rule
    * 3 Recognized media types ghg@7.3 = [CSS3-MEDIAQUERIES]@
        * 1 Media groups
* 8 Box model
    * 1 Box dimensions
    * 2 Example of margins, padding, and borders
    * 3 Margin properties: _`margin-top`_, _`margin-right`_, _`margin-bottom`_, _`margin-left`_, and _`margin`_
        * 1 Collapsing margins
    * 4 Padding properties: _`padding-top`_, _`padding-right`_, _`padding-bottom`_, _`padding-left`_, and _`padding`_
    * 5 Border properties
        * 1 Border width: _`border-top-width`_, _`border-right-width`_, _`border-bottom-width`_, _`border-left-width`_, and _`border-width`_
        * 2 Border color: _`border-top-color`_, _`border-right-color`_, _`border-bottom-color`_, _`border-left-color`_, and _`border-color`_
        * 3 Border style: _`border-top-style`_, _`border-right-style`_, _`border-bottom-style`_, _`border-left-style`_, and _`border-style`_
        * 4 Border shorthand properties: _`border-top`_, _`border-right`_, _`border-bottom`_, _`border-left`_, and _`border`_
    * 6 The box model for inline elements in bidirectional context
* 9 Visual formatting model
    * 1 Introduction to the visual formatting model
        * 1 The viewport
        * 2 Containing blocks
    * 2 Controlling box generation
        * 1 Block-level elements and block boxes
            * 1 Anonymous block boxes
        * 2 Inline-level elements and inline boxes
            * 1 Anonymous inline boxes
        * 3 Run-in boxes
        * 4 The _`display`_ property
    * 3 Positioning schemes
        * 1 Choosing a positioning scheme: _`position`_ property
        * 2 Box offsets: _`top`_, _`right`_, _`bottom`_, _`left`_
    * 4 Normal flow
        * 1 Block formatting contexts
        * 2 Inline formatting contexts
        * 3 Relative positioning
    * 5 Floats
        * 1 Positioning the float: the _`float`_ property
        * 2 Controlling flow next to floats: the _`clear`_ property
    * 6 Absolute positioning
        * 1 Fixed positioning
    * 7 Relationships between _`display`_, _`position`_, and _`float`_
    * 8 Comparison of normal flow, floats, and absolute positioning
        * 1 Normal flow
        * 2 Relative positioning
        * 3 Floating a box
        * 4 Absolute positioning
    * 9 Layered presentation
        * 1 Specifying the stack level: the _`z-index`_ property
    * 10 Text direction: the _`direction`_ and _`unicode-bidi`_ properties
* 10 Visual formatting model details
    * 1 Definition of "containing block"
    * 2 Content width: the _`width`_ property
    * 3 Calculating widths and margins
        * 1 Inline, non-replaced elements
        * 2 Inline, replaced elements
        * 3 Block-level, non-replaced elements in normal flow
        * 4 Block-level, replaced elements in normal flow
        * 5 Floating, non-replaced elements
        * 6 Floating, replaced elements
        * 7 Absolutely positioned, non-replaced elements
        * 8 Absolutely positioned, replaced elements
        * 9 _`inline-block`_, non-replaced elements in normal flow
        * 10 _`inline-block`_, replaced elements in normal flow
    * 4 Minimum and maximum widths: _`min-width`_ and _`max-width`_
    * 5 Content height: the _`height`_ property
    * 6 Calculating heights and margins
        * 1 Inline, non-replaced elements
        * 2 Inline replaced elements, block-level replaced elements in normal flow, _`inline-block`_ replaced elements in normal flow and floating replaced elements
        * 3 Block-level non-replaced elements in normal flow when _`overflow`_ computes to _`visible`_
        * 4 Absolutely positioned, non-replaced elements
        * 5 Absolutely positioned, replaced elements
        * 6 Complicated cases
        * 7 _`auto`_ heights for block formatting context roots
    * 7 Minimum and maximum heights: _`min-height`_ and _`max-height`_
    * 8 Line height calculations: the _`line-height`_ and _`vertical-align`_ properties
        * 1 Leading and half-leading
* 11 Visual effects
    * 1 Overflow and clipping
        * 1 Overflow: the _`overflow`_ property
        * 2 Clipping: the _`clip`_ property
    * 2 Visibility: the _`visibility`_ property
* 12 Generated content, automatic numbering, and lists
    * 1 The _`:before`_ and _`:after`_ pseudo-elements
    * 2 The _`content`_ property
    * 3 Quotation marks
        * 1 Specifying quotes with the _`quotes`_ property
        * 2 Inserting quotes with the _`content`_ property
    * 4 Automatic counters and numbering
        * 1 Nested counters and scope
        * 2 Counter styles
        * 3 Counters in elements with 'display: none'
    * 5 Lists
        * 1 Lists: the _`list-style-type`_, _`list-style-image`_, _`list-style-position`_, and _`list-style`_ properties
* 13 Paged media
    * 1 Introduction to paged media
    * 2 Page boxes: the _`@page`_ rule
        * 1 Page margins
        * 2 Page selectors: selecting left, right, and first pages
        * 3 Content outside the page box
    * 3 Page breaks
        * 1 Page break properties: _`page-break-before`_, _`page-break-after`_, _`page-break-inside`_
        * 2 Breaks inside elements: _`orphans`_, _`widows`_
        * 3 Allowed page breaks
        * 4 Forced page breaks
        * 5 "Best" page breaks
    * 4 Cascading in the page context
* 14 Colors and Backgrounds
    * 1 Foreground color: the _`color`_ property
    * 2 The background
        * 1 Background properties: _`background-color`_, _`background-image`_, _`background-repeat`_, _`background-attachment`_, _`background-position`_, and _`background`_
* 15 Fonts
    * 1 Introduction
    * 2 Font matching algorithm
    * 3 Font family: the _`font-family`_ property
        * 1 Generic font families
            * 1 _`serif`_
            * 2 _`sans-serif`_
            * 3 _`cursive`_
            * 4 _`fantasy`_
            * 5 _`monospace`_
    * 4 Font styling: the _`font-style`_ property
    * 5 Small-caps: the _`font-variant`_ property
    * 6 Font boldness: the _`font-weight`_ property
    * 7 Font size: the _`font-size`_ property
    * 8 Shorthand font property: the _`font`_ property
* 16 Text
    * 1 Indentation: the _`text-indent`_ property
    * 2 Alignment: the _`text-align`_ property
    * 3 Decoration
        * 1 Underlining, overlining, striking, and blinking: the _`text-decoration`_ property
    * 4 Letter and word spacing: the _`letter-spacing`_ and _`word-spacing`_ properties
    * 5 Capitalization: the _`text-transform`_ property
    * 6 White space: the _`white-space`_ property
        * 1 The _`white-space`_ processing model
        * 2 Example of bidirectionality with white space collapsing
        * 3 Control and combining characters' details
* 17 Tables
    * 1 Introduction to tables
    * 2 The CSS table model
        * 1 Anonymous table objects
    * 3 Columns
    * 4 Tables in the visual formatting model
        * 1 Caption position and alignment
    * 5 Visual layout of table contents
        * 1 Table layers and transparency
        * 2 Table width algorithms: the _`table-layout`_ property
            * 1 Fixed table layout
            * 2 Automatic table layout
        * 3 Table height algorithms
        * 4 Horizontal alignment in a column
        * 5 Dynamic row and column effects
    * 6 Borders
        * 1 The separated borders model
            * 1 Borders and Backgrounds around empty cells: the _`empty-cells`_ property
        * 2 The collapsing border model
            * 1 Border conflict resolution
        * 3 Border styles
* 18 User interface
    * 1 Cursors: the _`cursor`_ property
    * 2 System Colors
    * 3 User preferences for fonts
    * 4 Dynamic outlines: the _`outline`_ property
        * 1 Outlines and the focus
    * 5 Magnification



# todo

Replaces: `=`
Extends and supersedes: `+`
not: `!`

- [x] CSS2§4.1 = [CSS-SYNTAX-3]
- [x] CSS2§4.2 = [CSS-SYNTAX-3]
- [x] CSS2§4.4 = [CSS-SYNTAX-3]
CSS Syntax Level 3 b@[CSS-SYNTAX-3]@
    Replaces p@CSS2§4.1@, p@CSS2§4.2@, p@CSS2§4.4@, and CSS2§G, redefining how CSS is parsed.
CSS Style Attributes bhb@[CSS-STYLE-ATTR]@
    Defines how CSS declarations can be embedded in markup attributes.
Media Queries Level 3 bhb@[CSS3-MEDIAQUERIES]@
    Replaces p@CSS2§7.3@ and expands on the syntax for media-specific styles.
- [x] CSS2§7.3 = [CSS3-MEDIAQUERIES]
CSS Conditional Rules Level 3 bhb@[CSS-CONDITIONAL-3]@
    Extends and supersedes p@CSS2§7.2@, updating the definition of `@media` rules to allow nesting and introducing the `@supports` rule for feature-support queries.
- [ ] CSS2§7.2 = [CSS-CONDITIONAL-3]
Selectors Level 3 bhb@[SELECTORS-3]@
    Replaces p@CSS2§5@ and p@CSS2§6.4.3@, defining an extended range of selectors.
- [ ] 5 = [SELECTORS-3]
- [ ] 6.4.3 = [SELECTORS-3]
CSS Namespaces bhb@[CSS3-NAMESPACE]@
    Introduces an @namespace rule to allow namespace-prefixed selectors.
CSS Cascading and Inheritance Level 4 bhb@[CSS-CASCADE-4]@
    Extends and supersedes p@CSS2§1.4.3@ and p@CSS2§6@, as well as bhb@[CSS-CASCADE-3]@. Describes how to collate style rules and assign values to all properties on all elements. By way of cascading and inheritance, values are propagated for all properties on all elements.
- [ ] 1.4.3 + [CSS-CASCADE-4]
- [ ] 6 + [CSS-CASCADE-4]
- [ ] [CSS-CASCADE-3] + [CSS-CASCADE-4]
CSS Values and Units Level 3 bhb@[CSS-VALUES-3]@
    Extends and supersedes p@CSS2§1.4.2.1@, p@CSS2§4.3@, and CSS2§A.2.1–3, defining CSS’s property definition syntax and expanding its set of units.
- [ ] 1.4.2.1 + [CSS-VALUES-3]
- [ ] 4.3 + [CSS-VALUES-3]
- [ ] A.2.1–3 + [CSS-VALUES-3]
CSS Custom Properties for Cascading Variables Module Level 1 bhb@[CSS-VARIABLES-1]@
    Introduces cascading variables as a new primitive value type that is accepted by all CSS properties, and custom properties for defining them.
CSS Box Model Level 3 bhb@[CSS-BOX-3]@
    Replaces p@CSS2§8.1@, p@CSS2§8.2@, p@CSS2§8.3@ (but not p@CSS2§8.3.1@), and p@CSS2§8.4@.
- [ ] 8.1 = [CSS-BOX-3]
- [ ] 8.2 = [CSS-BOX-3]
- [ ] 8.3 !8.3.1 = [CSS-BOX-3]
- [ ] 8.4 = [CSS-BOX-3]
CSS Color Level 4 bhb@[CSS-COLOR-4]@
    Extends and supersedes p@CSS2§4.3.6@, p@CSS2§14.1@, and p@CSS2§18.2@, also extends and supersedes bhb@[CSS-COLOR-3]@, introducing an extended range of color spaces beyond sRGB, extended color values, and CSS Object Model extensions for color. Also defines the opacity property.
- [ ] 4.3.6 + [CSS-COLOR-4]
- [ ] 14.1 + [CSS-COLOR-4]
- [ ] 18.2 + [CSS-COLOR-4]
- [ ] [CSS-COLOR-3] + [CSS-COLOR-4]
CSS Backgrounds and Borders Level 3 bhb@[CSS-BACKGROUNDS-3]@
    Extends and supersedes p@CSS2§8.5@ and p@CSS2§14.2@, providing more control of backgrounds and borders, including layered background images, image borders, and drop shadows.
- [ ] 8.5 + [CSS-BACKGROUNDS-3]
- [ ] 14.2 + [CSS-BACKGROUNDS-3]
CSS Images Level 3 bhb@[CSS-IMAGES-3]@
    Redefines and incorporates the external 2D image value type, introduces native 2D gradients, and adds additional controls for replaced element sizing and rendering.
CSS Fonts Level 3 bhb@[CSS-FONTS-3]@
    Extends and supersedes p@CSS2§15@ and provides more control over font choice and feature selection.
- [ ] 2§15 + [CSS-FONTS-3]
CSS Writing Modes Level 3 bhb@[CSS-WRITING-MODES-3]@
    Defines CSS support for various international writing modes, such as left-to-right (e.g. Latin or Indic), right-to-left (e.g. Hebrew or Arabic), bidirectional (e.g. mixed Latin and Arabic) and vertical (e.g. Asian scripts). Replaces and extends p@CSS2§8.6@ and p@CSS2§9.10@.
- [ ] 8.6 = [CSS-WRITING-MODES-3]
- [ ] 9.10 = [CSS-WRITING-MODES-3]
CSS Multi-column Layout Level 1 bhb@[CSS-MULTICOL-1]@
    Introduces multi-column flows to CSS layout.
CSS Flexible Box Module Level 1 bhb@[CSS-FLEXBOX-1]@
    Introduces a flexible linear layout model for CSS.
CSS User Interface Module Level 3 bhb@[CSS-UI-3]@
    Extends and supersedes p@CSS2§18.1@ and p@CSS2§18.4@, defining cursor, outline, and several new CSS features that also enhance the user interface.
- [ ] 18.1 + [CSS-UI-3]
- [ ] 18.4 + [CSS-UI-3]
CSS Containment Module Level 1 bhb@[CSS-CONTAIN-1]@
    Introduces the contain property, which enforces the independent CSS processing of an element’s subtree in order to enable heavy optimizations by user agents when used well.
CSS Transforms Level 1 bhb@[CSS-TRANSFORMS-1]@
    Introduces coordinate-based graphical transformations to CSS.
CSS Compositing and Blending Level 1 bhb@[COMPOSITING]@
    Defines the compositing and blending of overlaid content and introduces features to control their modes.
CSS Easing Functions Level 1 bhb@[CSS-EASING-1]@.
    Describes a way for authors to define a transformation that controls the rate of change of some value. Applied to animations, such transformations can be used to produce animations that mimic physical phenomena such as momentum or to cause the animation to move in discrete steps producing robot-like movement.
CSS Counter Styles Level 3 bhb@[CSS-COUNTER-STYLES-3]@
    Introduces the `@counter-style` rule, which allows authors to define their own custom counter styles for use with CSS list-marker and generated-content counters bhb@[CSS-LISTS-3]@. It also predefines a set of common counter styles, including the ones present in CSS2 and CSS2.1.
