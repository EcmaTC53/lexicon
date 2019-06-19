<dl url="https://EcmaTC53.github.io/lexicon">ECMA TC-53 Terms
<dt>Application
<dd>In the context of TC-53, an application is a software program designed to perform a specific function on a specific device. Applications may import libraries and providers in the form of modules.
<dt><a href="https://github.com/tc39/proposal-javascript-standard-library/">Built-in</a>
<dd>Built-ins are javascript modules that are bundled with the host.
<dt>Data Accuracy
<dd>How close a data measurement is to it's theoretical expected output.
<dt>Data Provenance
<dd>Knowing where data came from and how it arrived.
<dt>Data Timeliness
<dd>A measure of data timeliness. For example, how long did that "read" command take to execute? On embedded systems this could be a few ns. On a cloud based device it could be several seconds.
<dt>Data Trustworthiness
<dd>The combination of data provenance, timeliness an accuracy.
<dt>External provider
<dd>A downloadable module that provides a surface API that matches the GPIO API specified by TC-53.
<dt><a href="https://www.w3.org/TR/generic-sensor/">Generic Sensor API</a>
<dd>A framework for exposing sensor data to the Open Web Platform in a consistent way. 
<dt>Implementor
<dd>An implementor creates a provider. An implementor could be the creator of a host, or a 3rd party library.
<dt>Internal provider
<dd>A built-in module that provides a surface API that matches the GPIO API specified by TC-53.
<dt>IOCP
<dd>See I/O Class Pattern
<dt><a href="https://gist.github.com/phoddie/166c9c17b2f31d0beda9f2410a219268">I/O Class Pattern</a>
<dd>The I/O Class Pattern describes a logical superclass for various hardware interface types (Digital, Analog, Serial, I2C, etc).
<dt>Library
<dd>A library provides a surface API that abstracts away the GPIO API. For example, an LED library could provide an API with the methods on(), off(), blink() and toggle() that abstract away an application developers need to interact directly with a digital IO instance.
<dt>Maximally Minimal
<dd>The supposition that specifying a minimal API surface for base classes allows for greatest value realization and a reduced risk of painting oneself into a corner. A concept based on conversations around EcmaScript classes.
<dt><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import">Module</a>
<dd>Ecmascript code stored in an external file and imported via the ES6 import statement.
<dt><a href="https://developer.mozilla.org/en-US/docs/Glossary/Normative">Normative</a>
<dd>Things that have been standardized and must be followed as a rule.
<dt><a href="https://developer.mozilla.org/en-US/docs/Glossary/Protocol">Protocol</a>
<dd>A system of rules that define how data is exchanged between systems.
<dt>Provider
<dd>A provider is a module that provides a surface API that matches the GPIO API specified by TC-53.
<dt>Sleep
<dd>Sleep mode in embeddable systems is also known as low-power or power-down mode. Current data is retained, the core processor is still running and the system can respond to "wake" events on interrupt or other I/O.
<dt>Third-Party Libraries
<dd>Providers, libraries, or frameworks provided by a developer other than the Provider developer or the application developer.
<dt>W3C Sensor API
<dd>See "Generic Sensor API"
<dt><a href="https://iot.mozilla.org/wot/">Web Things</a>
<dd>A common data model and API for the Web of Things