# supernova
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tech Student Survival Guide</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        /* ===== GENERAL STYLES ===== */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            background-color: #f4f6f8;
            color: #333;
        }

        h1, h2, h3 {
            color: #2c3e50;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        /* ===== HEADER & NAV ===== */
        header {
            background-color: #1f2933;
            color: white;
            padding: 15px 20px;
            position: sticky;
            top: 0;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* ===== HERO SECTION ===== */
        .hero {
            background-color: #e3f2fd;
            text-align: center;
            padding: 60px 20px;
        }

        .hero button {
            padding: 12px 20px;
            background-color: #1976d2;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        .hero button:hover {
            background-color: #125aa3;
        }

        /* ===== TOPICS ===== */
        .topic {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .topic ul {
            margin-left: 20px;
        }

        /* ===== FAQ ===== */
        .faq {
            background-color: #ffffff;
            border-radius: 8px;
            padding: 20px;
        }

        .faq-question {
            cursor: pointer;
            font-weight: bold;
            margin-top: 15px;
        }

        .faq-answer {
            display: none;
            margin-top: 5px;
        }

        /* ===== FOOTER ===== */
        footer {
            background-color: #1f2933;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<!-- ===== HEADER / NAVIGATION ===== -->
<header>
    <nav>
        <h3>Tech Student Survival Guide</h3>
        <div>
            <a href="#overview">Overview</a>
            <a href="#email">Email</a>
            <a href="#files">Files</a>
            <a href="#cloud">Cloud</a>
            <a href="#safety">Safety</a>
            <a href="#docs">Google Docs</a>
            <a href="#faq">FAQs</a>
        </div>
    </nav>
</header>

<!-- ===== START / HERO ===== -->
<section class="hero">
    <h1>Welcome to the Tech Student Survival Guide</h1>
    <p>Simple, step-by-step help to make technology less scary and more useful.</p>
    <button onclick="scrollToSection('overview')">Get Started</button>
</section>

<!-- ===== OVERVIEW ===== -->
<section id="overview">
    <h2>What This Guide Is About</h2>
    <p>
        This website is designed for students who are new to technology or want to improve their basic digital skills.
        Each topic is explained using simple language and clear steps.
    </p>
    <ul>
        <li>Using email professionally</li>
        <li>Managing files on your computer</li>
        <li>Understanding cloud storage</li>
        <li>Staying safe online</li>
        <li>Using Google Docs</li>
    </ul>
</section>

<!-- ===== KEY TOPICS ===== -->

<section id="email" class="topic">
    <h2>Using Email Professionally</h2>
    <p>Email is one of the main ways students communicate with teachers and classmates.</p>
    <ol>
        <li>Use a clear subject line</li>
        <li>Start with a polite greeting</li>
        <li>Write your message clearly</li>
        <li>End with your name</li>
    </ol>
    <p><strong>Example Subject:</strong> Question About Assignment 2</p>
</section>

<section id="files" class="topic">
    <h2>Managing Files</h2>
    <p>Keeping your files organized helps you save time and reduce stress.</p>
    <ul>
        <li>Create folders for each class</li>
        <li>Name files clearly</li>
        <li>Delete files you no longer need</li>
    </ul>
    <p><strong>Tip:</strong> Use names like <em>English_Essay_Final.docx</em></p>
</section>

<section id="cloud" class="topic">
    <h2>Understanding Cloud Storage</h2>
    <p>
        Cloud storage lets you save files online so you can access them anywhere.
    </p>
    <ul>
        <li>Google Drive</li>
        <li>OneDrive</li>
        <li>Dropbox</li>
    </ul>
    <p>Cloud storage also helps protect your files if your computer breaks.</p>
</section>

<section id="safety" class="topic">
    <h2>Staying Safe Online</h2>
    <ul>
        <li>Create strong passwords</li>
        <li>Do not click suspicious links</li>
        <li>Never share personal information</li>
    </ul>
    <p><strong>Warning:</strong> Schools will never ask for your password by email.</p>
</section>

<section id="docs" class="topic">
    <h2>Using Google Docs</h2>
    <p>Google Docs is a free tool for writing assignments and working with others.</p>
    <ol>
        <li>Go to Google Docs</li>
        <li>Click "Blank document"</li>
        <li>Name your document</li>
        <li>Share it with classmates if needed</li>
    </ol>
</section>
