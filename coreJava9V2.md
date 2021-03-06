# Core Java® Volume II Contents	 
 
## 1. Streams and Files	 
	1.1. Streams	 
		1.1.1. Reading and Writing Bytes	
		1.1.2. The Complete Stream Zoo	 
		1.1.3. Combining Stream Filters	 
	1.2. Text Input and Output	
		1.2.1. How to Write Text Output	
		1.2.2. How to Read Text Input	
		1.2.3. Saving Objects in Text Format	
		1.2.4. Character Sets	
	1.3. Reading and Writing Binary Data	
		1.3.1. Random-Access Files	
	1.4. ZIP Archives	
	1.5. Object Streams and Serialization	
		1.5.1. Understanding the Object Serialization File Format	 
		1.5.2. Modifying the Default Serialization Mechanism	 
		1.5.3. Serializing Singletons and Typesafe Enumerations	 
		1.5.4. Versioning	
		1.5.5. Using Serialization for Cloning	 
	1.6. Working with Files	
		1.6.1. Paths	
		1.6.2. Reading and Writing Files	
		1.6.3. Copying, Moving, and Deleting Files	
		1.6.4. Creating Files and Directories	
		1.6.5. Getting File Information	
		1.6.6. Iterating over the Files in a Directory	
		1.6.7. ZIP File Systems	
	1.7. Memory-Mapped Files	
		1.7.1. The Buffer Data Structure	
		1.7.2. File Locking	
	1.8. Regular Expressions	
## 2. XML	
	2.1. Introducing XML	
		2.1.1. The Structure of an XML Document	
	2.2. Parsing an XML Document	
	2.3. Validating XML Documents	
		2.3.1. Document Type Definitions	
		2.3.2. XML Schema	
		2.3.3. A Practical Example	
	2.4. Locating Information with XPath	30
	2.5. Using Namespaces	
2.6. Streaming Parsers	
	2.6.1. Using the SAX Parser	
	2.6.2. Using the StAX Parser	
2.7. Generating XML Documents	
	2.7.1. Documents without Namespaces	
	2.7.2. Documents with Namespaces	
	2.7.3. Writing Documents	
	2.7.4. An Example: Generating an SVG File	
	2.7.5. Writing an XML Document with StAX	
2.8. XSL Transformations	
## 3. Networking	
	3.1. Connecting to a Server	
		3.1.1. Socket Timeouts	
		3.1.2. Internet Addresses	
	3.2. Implementing Servers	40
		3.2.1. Serving Multiple Clients	
		3.2.2. Half-Close	
	3.3. Interruptible Sockets	
	3.4. Getting Web Data	
		3.4.1. URLs and URIs	
		3.4.2. Using a URLConnection to Retrieve Information	
		3.4.3. Posting Form Data	
	3.5. Sending E-Mail	
## 4. Database Programming	
	4.1. The Design of JDBC	
		4.1.1. JDBC Driver Types	
		4.1.2. Typical Uses of JDBC	
	4.2. The Structured Query Language	
	4.3. JDBC Configuration	
		4.3.1. Database URLs	
		4.3.2. Driver JAR Files	
		4.3.3. Starting the Database	50
		4.3.4. Registering the Driver Class	
		4.3.5. Connecting to the Database	
	4.4. Executing SQL Statements	
		4.4.1. Managing Connections, Statements, and Result Sets	
		4.4.2. Analyzing SQL Exceptions	
		4.4.3. Populating a Database	
	4.5. Query Execution	
		4.5.1. Prepared Statements	
		4.5.2. Reading and Writing LOBs	
		4.5.3. SQL Escapes	
		4.5.4. Multiple Results	
		4.5.5. Retrieving Autogenerated Keys	
	4.6. Scrollable and Updatable Result Sets	
		4.6.1. Scrollable Result Sets	
		4.6.2. Updatable Result Sets	
	4.7. Row Sets	
		4.7.1. Constructing Row Sets	
		4.7.2. Cached Row Sets	60
	4.8. Metadata	
	4.9. Transactions	
		4.9.1. Save Points	
		4.9.2. Batch Updates	
		4.9.3. Advanced SQL Types	
	4.10. Connection Management in Web and Enterprise Applications	
## 5. Internationalization	
	5.1. Locales	
	5.2. Number Formats	
		5.2.1. Currencies	
	5.3. Date and Time	
	5.4. Collation	
		5.4.1. Collation Strength	
		5.4.2. Decomposition	
	5.5. Message Formatting	
		5.5.1. Choice Formats	
	5.6. Text Files and Character Sets	70
		5.6.1. Character Encoding of Source Files	
	5.7. Resource Bundles	
		5.7.1. Locating Resource Bundles	
		5.7.2. Property Files	
		5.7.3. Bundle Classes	
	5.8. A Complete Example	
## 6. Advanced Swing	
	6.1. Lists	
		6.1.1. The JList Component	
		6.1.2. List Models	
		6.1.3. Inserting and Removing Values	
		6.1.4. Rendering Values	
	6.2. Tables	
		6.2.1. A Simple Table	
		6.2.2. Table Models	
		6.2.3. Working with Rows and Columns	
			6.2.3.1. Column Classes	80
			6.2.3.2. Accessing Table Columns	
			6.2.3.3. Resizing Columns	
			6.2.3.4. Resizing Rows	
            6.2.3.5. Selecting Rows, Columns, and Cells	
            6.2.3.6. Sorting Rows	
            6.2.3.7. Filtering Rows	
            6.2.3.8. Hiding and Displaying Columns	
            6.2.4. Cell Rendering and Editing	
                6.2.4.1. Rendering the Header	
                6.2.4.2. Cell Editing	
                6.2.4.3. Custom Editors	
    6.3. Trees	
                6.3.1. Simple Trees	
                    6.3.1.1. Editing Trees and Tree Paths	
                6.3.2. Node Enumeration	
                6.3.3. Rendering Nodes	
                6.3.4. Listening to Tree Events	90
                6.3.5. Custom Tree Models	
    6.4. Text Components	
                6.4.1. Change Tracking in Text Components	
                6.4.2. Formatted Input Fields	
                    6.4.2.1. Integer Input	
                    6.4.2.2. Behavior on Loss of Focus	
                    6.4.2.3. Filters	
                    6.4.2.4. Verifiers	
                    6.4.2.5. Other Standard Formatters	
                    6.4.2.6. Custom Formatters	
                6.4.3. The JSpinner Component	
                6.4.4. Displaying HTML with the JEditorPane	
    6.5. Progress Indicators	
                6.5.1. Progress Bars	
                6.5.2. Progress Monitors	
                6.5.3. Monitoring the Progress of Input Streams	
    6.6. Component Organizers and Decorators	a0
                6.6.1. Split Panes	
                6.6.2. Tabbed Panes	
                6.6.3. Desktop Panes and Internal Frames	
                6.6.4. Cascading and Tiling	
                6.6.5. Vetoing Property Settings	aa
                    6.6.5.1. Dialogs in Internal Frames	ac
                    6.6.5.2. Outline Dragging	ae
                    6.6.6.3. Layers	ag
## 7. Advanced AWT	ak
	7.1. The Rendering Pipeline	am
	7.2. Shapes	ao
		7.2.1. Using the Shape Classes	aq
	7.3. Areas	as
	7.4. Strokes	au
	7.5. Paint	aw
	7.6. Coordinate Transformations	ay
	7.7. Clipping	b0
	7.8. Transparency and Composition	
	7.9. Rendering Hints	
	7.10. Readers and Writers for Images	
		7.10.1. Obtaining Readers and Writers for Image File Types	
		7.10.2. Reading and Writing Files with Multiple Images	ba
	7.. Image Manipulation	bc
		7..1. Constructing Raster Images	be
		7..2. Filtering Images	bg
	7.. Printing	bi
		7..1. Graphics Printing	bk
7..2. Multiple-Page Printing	bo
7..3. Print Preview	bq
7..4. Print Services	bs
7..5. Stream Print Services	bu
7..6. Printing Attributes	bw
7.. The Clipboard	by
	7..1. Classes and Interfaces for Data Transfer	c0
	7..2. Transferring Text	
	7..3. The Transferable Interface and Data Flavors	
	7..4. Building an Image Transferable	
	7..5. Transferring Java Objects via the System Clipboard	
	7..6. Using a Local Clipboard to Transfer Object References	ca
7.. Drag and Drop	cc
	7..1. Data Transfer Support in Swing	ce
	7..2. Drag Sources	cg
	7..3. Drop Targets	ci
7.. Platform Integration	ck
	7..1. Splash Screens	cm
	7..2. Launching Desktop Applications	co
	7..3. The System Tray	cq
## 8. JavaBeans Components	cu
	8.1. Why Beans?	cw
	8.2. The Bean-Writing Process	cy
	8.3. Using Beans to Build an Application	d0
		8.3.1. Packaging Beans in JAR Files	
		8.3.2. Composing Beans in a Builder Environment	
	8.4. Naming Patterns for Bean Properties and Events	
	8.5. Bean Property Types	
		8.5.1. Simple Properties	da
		8.5.2. Indexed Properties	dc
		8.5.3. Bound Properties	de
		8.5.4. Constrained Properties	dg
	8.6. BeanInfo Classes	di
	8.7. Property Editors	dk
		8.7.1. Writing Property Editors	dm
			8.7.1.1. String-Based Property Editors	do
			8.7.1.2. GUI-Based Property Editors	dq
	8.8. Customizers	ds
		8.8.1. Writing a Customizer Class	du
	8.9. JavaBeans Persistence	dw
		8.9.1. Using JavaBeans Persistence for Arbitrary Data	dy
			8.9.1.1. Writing a Persistence Delegate to Construct an Object	e0
			8.9.1.2. Constructing an Object from Properties	
			8.9.1.3. Constructing an Object with a Factory Method	
			8.9.1.4. Postconstruction Work	
			8.9.1.5. Transient Properties	
		8.9.2. A Complete Example for JavaBeans Persistence	ea
## 9. Security	ee
	9.1. Class Loaders	eg
		9.1.1. The Class Loader Hierarchy	ei
		9.1.2. Using Class Loaders as Namespaces	ek
		9.1.3. Writing Your Own Class Loader	em
	9.2. Bytecode Verification	eo
	9.3. Security Managers and Permissions	eq
		9.3.1. Java Platform Security	es
		9.3.2. Security Policy Files	eu
		9.3.3. Custom Permissions	ew
		9.3.4. Implementation of a Permission Class	ey
	9.4. User Authentication	f0
		9.4.1. JAAS Login Modules	
	9.5. Digital Signatures	
		9.5.1. Message Digests	
		9.5.2. Message Signing	
		9.5.3. Verifying a Signature	fa
		9.5.4. The Authentication Problem	fc
		9.5.5. Certificate Signing	fe
		9.5.6. Certificate Requests	fg
	9.6. Code Signing	fi
		9.6.1. JAR File Signing	fk
		9.6.2. Software Developer Certificates	fm
	9.7. Encryption	fo
		9.7.1. Symmetric Ciphers	fq
		9.7.2. Key Generation	fs
		9.7.3. Cipher Streams	fu
		9.7.4. Public Key Ciphers	fw
## 10. Scripting, Compiling, and Annotation Processing	g0
	10.1. Scripting for the Java Platform	
		10.1.1. Getting a Scripting Engine	
		10.1.2. Script Evaluation and Bindings	
		10.1.3. Redirecting Input and Output	
		10.1.4. Calling Scripting Functions and Methods	ga
		10.1.5. Compiling a Script	gc
		10.1.6. An Example: Scripting GUI Events	ge
	10.2. The Compiler API	gg
		10.2.1. Compiling the Easy Way	gi
		10.2.2. Using Compilation Tasks	gk
		10.2.3. An Example: Dynamic Java Code Generation	gm
	10.3. Using Annotations	go
		10.3.1. An Example: Annotating Event Handlers	gq
	10.4. Annotation Syntax	gs
	10.5. Standard Annotations	gu
		10.5.1. Annotations for Compilation	gw
		10.5.2. Annotations for Managing Resources	gy
		10.5.3. Meta-Annotations	h0
	10.6. Source-Level Annotation Processing	
	10.7. Bytecode Engineering	
		10.7.1. Modifying Bytecodes at Load Time	
## . Distributed Objects	ha
	.1. The Roles of Client and Server	hc
	.2. Remote Method Calls	he
		.2.1. Stubs and Parameter Marshalling	hg
	.3. The RMI Programming Model	hi
		.3.1. Interfaces and Implementations	hk
		.3.2. The RMI Registry	hm
		.3.3. Deploying the Program	ho
		.3.4. Logging RMI Activity	hq
	.4. Parameters and Return Values in Remote Methods	hs
		.4.1. Transferring Remote Objects	hu
		.4.2. Transferring Nonremote Objects	hw
		.4.3. Dynamic Class Loading	hy
		.4.4. Remote References with Multiple Interfaces	i0
		.4.5. Remote Objects and the equals, hashCode, and clone Methods	
	.5. Remote Object Activation	
## . Native Methods	
	.1. Calling a C Function from a Java Program	ia
	.2. Numeric Parameters and Return Values	ic
		.2.1. Using printf for Formatting Numbers	ie
	.3. String Parameters	ig
	.4. Accessing Fields	ii
		.4.1. Accessing Instance Fields	ik
		.4.2. Accessing Static Fields	im
	.5. Encoding Signatures	io
	.6. Calling Java Methods	iq
		.6.1. Instance Methods	is
		.6.2. Static Methods	iu
		.6.3. Constructors	iw
		.6.4. Alternative Method Invocations	iy
	.7. Accessing Array Elements	j0
	.8. Handling Errors	
	.9. Using the Invocation API	
	.10. A Complete Example: Accessing the Windows Registry	
		.10.1. Overview of the Windows Registry	
		.10.2. A Java Platform Interface for Accessing the Registry	ja
		.10.3. Implementation of Registry Access Functions as Native Methods	jc
