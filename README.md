# ProgrammingTerms
List and description of programming terms

<dl>
        <dt>Atwood's Law</dt>
	<dd>any application that can be written in JavaScript, will eventually be written in JavaScript.</dd>
	
	<dt>Error-First Callback</dt>
	<dd>callbacks takes an error object as their first parameter.
	 null if no error, otherwise will contain an object defining the error. This is a standard so we know in what order to place our parameters for our callbacks.</dd>

	<dt>Chunk</dt>
	<dd>A piece of data being sent through a stream</dd>

	<dt>Abstract (Base) Class</dt>
	<dd>A type of constructor you never work directly with, but inherit from</dd>

	<dt>Pipe</dt>
	<dd>Connecting two streams by writing to one stream what is being read from another</dd>

	<dt>Method Chaining</dt>
	<dd>A method returns an object so we can keep calling more methodsm but when returning the parent object, it is called Cascading</dd>

	<dt>PROTOCOL</dt>
	<dd>A SET OF RULES TWO SIDES AGREE ON TO USE WHEN COMMUNICATING. Both the client and server are programmed to understand and use that particular set of rules. It's similar to two people from different countries agreeing on a language to speak in.</dd>

	<dt>PORT</dt>
	<dd>ONCE A COMPUTER RECEIVES A PACKER, HOW IT KNOWS WHAT PROGRAM TO SENT IT TO. When a program is setup on the operating system to receice packets from a particular port, it is said that the program is 'listening' to that port.</dd>

	<dt>HTTP</dt>
	<dd>A SET OF RULES (AND A FORMAT) FOR DATA BEING TRANSFERRED ON THE WEB. Stands for 'HyperText Transfer Protocol'. It's a format (of various) defining data being transfered via TCP/IP.</dd>

	<dt>MIME type</dt>
	<dd>A STATNDARD FOR SPECIFYING THE TYPE OF DATA BEING SENT. Stands for 'Multipurpose Internet Mail Extensions'. Examples: application/json, text/html, image/jpeg</dd>

	<dt>Monkey Patching</dt>
	<dd>A monkey patch is a way for a program to extend or modify supporting system software locally (affecting only the running instance of the program). Ex. <a href="http://me.dt.in.th/page/JavaScript-override/">http://me.dt.in.th/page/JavaScript-override/<a></dd>
	
	<dt>Open Close Principle</dt>
	<dd>Open Close Principle is one of the Robust Software Design principle. It says "Your system is open for extensions but close to breaking changes". It relies on Interface Contract.</dd>
	
	<dt>Classical Inheritance</dt>
	<dd>Is like buying a un-assembled furniture. If any peice go wrong, you are not going to get the furniture</dd>
	
	<dt>Composition</dt>
	<dd>Is like buying a LEGO box, you can create variety of furnitures</dd>
	
	<dt>Functor</dt>
	<dd>A functor is a function, given a value and a function, unwraps the values to get to its inner value(s), call the given function with the inner value(s), wraps the returned values in a new structure, and returns the new structure. Ex. Array.map is a function, Array.filter is a functor. Mathematically a  function F is a functor, when for two composable ordinary function f and g,   F (f  . g) = F(f). F(g)</dd>
	
	<h3>Software Quality External Factors</h3>
	<dt>Correctness</dt>
	<dd>Correctness is the ability of software products to perform their exact tasks, as defined by their specification.</dd>
	
	<dt>Robustness</dt>
	<dd>Robustness is the ability of software systems to react appropriately to abnormal conditions.<em>There will always be cases that the specification does not explicitly address. The role of robustness requirement is to make sure that if such cases do arise, the system does not cause catastrophic events; it should produce appropriate error messages, terminate its execution cleanly, or enter a so-called "graceful degradation" mode.</em></dd>
	
	<dt>Extendibility<dt>
	<dd>Extendibility is the ease of adapting software products to changes of specification. <em>Two principles for imporving extendibility. 1. Design simplicity : a simple architecture will always be easier to adapt to changes than a complex one. 2. Decentralization: the more autonomous the modules, the higher the likelihood that a simple change will affect just one module, or a small number of modules, rather than triggering off a chain reaction of changes over the whole system.</em> </dd>
	
	<dt>Reusability</dt>
	<dd>Reusability is the ability of software elements to serve for the construction of many different applications.</dd>
	
	<dt>Compatibility<dt>
	<dd>Compatibility is the ease of combining software elements with others.</dd>
	
	<dt>Efficiency</dt>
	<dd>Efficiency is the ability of a software system to place as few demands as possible on hardware resouces, such as processor time, space occupied in internal and external memories, bandwidth used in communication devices.</dd>
	
	<dt>Portability</dt>
	<dd>Portability is the ease of transferring software products to various hardware and software environments.</dd>
	
	<dt>Ease of use</dt>
	<dd>Ease of use is the ease with which people of various backgrounds and qualifications can learn to use software products and apply them to solve problems. It also covers the ease of installation, operation and monitoring.</dd>
	
	<dt>User Interface Design principle</dt>
	<dd>Do not pretend you know the user; you don't</dd>
	
	<dt>Functionality</dt>
	<dd>Functionality is the extend of possibilities provided by a system.</dd>
	
	<dt>Timeliness</dt>
	<dd>Timeliness is the abilitity of a software system to be released when or before its users want it.</dd>
</dl>
