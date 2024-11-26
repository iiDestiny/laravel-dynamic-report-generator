
<h1>Laravel Dynamic Report Generator</h1>

<p>A dynamic report generator package for Laravel with a drag-and-drop interface. This package allows users to generate SQL queries by dragging and dropping tables and columns, and then displays the results.</p>
<h4>Drag-and-drop interface</h4>
<img src="https://github.com/md-sazzadul-islam/laravel-dynamic-report-generator/assets/26510351/e03d9679-5a16-4160-8804-4c76ad8c43ff" alt="Drag-and-drop interface">
<h4>Saved Reports</h4>
<img src="https://github.com/md-sazzadul-islam/laravel-dynamic-report-generator/assets/26510351/81ef2c87-14c6-4572-baf8-f8da31f6868c" alt="Saved Reports">
<h4>Display query results</h4>
<img src="https://github.com/md-sazzadul-islam/laravel-dynamic-report-generator/assets/26510351/889d3237-bdc3-40bb-a590-1433cff78c79" alt="Display query results">
<h2>Features</h2>
<ul>
    <li>Drag-and-drop interface for selecting tables and columns</li>
    <li>Join multiple tables using foreign key relationships</li>
    <li>Generate SQL queries dynamically</li>
    <li>Display query results in a table format</li>
</ul>

<h2>Installation</h2>
<p>To install the package, follow these steps:</p>
<ol>
    <li>Add the package to your Laravel project using Composer:
        <pre><code>composer require iidestiny/laravel-dynamic-report-generator</code></pre>
    </li>
    <li>If not automatically registered, add the service provider to <code>config/app.php</code>:
        <pre><code>'providers' => [
    // ...
    DevForest\\ReportGeneratorServiceProvider::class,
];</code></pre>
    </li>
    <li>Publish the package assets:
        <pre><code>php artisan vendor:publish --provider="DevForest\ReportGeneratorServiceProvider"</code></pre>
    </li>
    <li>Migrations:
        <pre><code>php artisan migrate</code></pre>
    </li>
</ol>

<h2>Usage</h2>
<p>After installing and setting up the package, you can access the report generator interface at:</p>
<p><code>http://your-app-url/report-generator</code></p>
<p>From here, you can:</p>
<ul>
    <li>Select tables from the list</li>
    <li>Drag columns to the selected columns area</li>
    <li>Configure table joins and conditions</li>
    <li>Generate and view the SQL query results</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Please feel free to submit a pull request or open an issue on GitHub.</p>

<h2>License</h2>
<p>This package is open-source software licensed under the MIT license.</p>
