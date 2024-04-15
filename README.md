<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scholarly Document</title>
</head>
<body>

<nav>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <ul>
            <li><a href="#scope">1.4 Product Scope</a></li>
            <li><a href="#references">1.5 References</a></li>
        </ul>
        <li><a href="#overall-description">Overall Description</a></li>
        <ul>
            <li><a href="#functions">2.2 Product Functions</a></li>
            <li><a href="#user-classes">2.3 User Classes and Characteristics</a></li>
            <li><a href="#environment">2.4 Operating Environment</a></li>
            <li><a href="#assumptions">2.7 Assumptions and Dependencies</a></li>
        </ul>
        <li><a href="#system-features">System Features</a></li>
        <ul>
            <li><a href="#feature-1">4.1 System Feature 1</a></li>
            <li><a href="#feature-2">4.2 System Feature 2 (and so on)</a></li>
        </ul>
        <li><a href="#nonfunctional-requirements">Other Nonfunctional Requirements</a></li>
        <ul>
            <li><a href="#safety">5.2 Safety Requirements</a></li>
        </ul>
        <li><a href="#other-requirements">Other Requirements</a></li>
        </ul>
</nav>

<h1>Development of a Web Tool for Anonymous Feedback Collection</h1>

<p><strong>Authors:</strong> Panaite Alexandra-Mihaela, Ghența Ana-Maria </p>

<h2 id="introduction">1 Introduction </h2>
<h3 id="product-scope">1.4 Product Scope</h3>

<p>The web tool aims to facilitate anonymous feedback collection for various entities, including events, persons, geographic locations, products, services, artistic artifacts, etc. Feedback is captured in the form of emotions specified according to the Plutchik model. The application, accessible via a REST/GraphQL API, manages the entities to be evaluated and the specific responses received for each entity. Feedback collection requests are editable by the initiator, and statistics are generated after the collection period, providing insights based on recorded emotions and various criteria such as user demographics, time periods, subcategories, and positive/negative characteristics.</p>

<h2 id="references">1.5 References</h2>

<p><a href="https://edu.info.uaic.ro/web-technologies/">https://edu.info.uaic.ro/web-technologies/</a></p>
<p><a href="https://profs.info.uaic.ro/andrei.panu/courses/web/lab/webprojects.html">https://profs.info.uaic.ro/andrei.panu/courses/web/lab/webprojects.html</a></p>
<p><a href="https://www.figma.com/files/recents-and-sharing/recently-viewed?fuid=1360963838874921099">https://www.figma.com/files/recents-and-sharing/recently-viewed?fuid=1360963838874921099</a></p>

<h2 id="overall-description">2 Overall Description</h2>

<h3 id="product-functions">2.2 Product Functions</h3>

<p>The web tool encompasses the following key functions:</p>

<ol>
    <li>Create and manage feedback collection requests for different entities.</li>
    <li>Edit and update feedback collection details, including the entity to be evaluated, duration of the collection period, and specified emotions.</li>
    <li>Analyze collected feedback data to generate comprehensive statistics and insights.</li>
    <li>Present reports containing aggregated data on recorded emotions, considering multiple criteria such as user groups, evaluation time periods, subcategories of entities, and characteristics deemed positive/negative based on shared emotions.</li>
</ol>

<h3 id="user-classes-and-characteristics">2.3 User Classes and Characteristics</h3>

<p>The web tool caters to the following user classes:</p>

<ul>
    <li><strong>Initiators:</strong> Users who create and manage feedback collection requests. They have the authority to edit request details and monitor progress.</li>
    <li><strong>Respondents:</strong> Users who provide feedback for specific entities anonymously. They interact with the tool to submit their emotions.</li>
    <li><strong>Administrators:</strong> Users responsible for overall system management and administration, including user roles and permissions.</li>
</ul>

<h3 id="environment">2.4 Operating Environment</h3>

<p>The web tool will be designed to operate in a standard web environment, utilizing common web technologies such as HTML, CSS, JavaScript, and a backend programming language (e.g., Python, Node.js, PHP). It will be compatible with modern web browsers such as Chrome, Firefox, Safari, and Edge.</p>

<h3 id="assumptions">2.7 Assumptions and Dependencies</h3>

<hr>


</body>
</html>
