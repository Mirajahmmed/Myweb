<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programming Languages</title>
    <style>
        /* পৃষ্ঠা এর স্টাইলিং */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: orange;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: black;
            overflow: hidden;
        }
       nav a  {
            color: white;
            padding: 14px 15px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: green;
            color: white;
            text-align: center;
            padding: 1px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h2 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
    </style>
</head>
<body>

    <!-- হেডার -->
    <header>
        <h1>Programming Languages</h1>
    </header>

    <!-- নেভিগেশন বার -->
    <nav>
        <a href="#C">C</a>
        <a href="#Cpp">C++</a>
        <a href="#Python">Python</a>
        <a href="#Java">Java</a>
        <a href="#JavaScript">JavaScript</a>
    </nav>
    <aside>
    <!-- C সেকশন -->
    <section id="C">
        <h2>C Language</h2>
        <p>
        <strong>আবিষ্কারক:</strong> ডেনিস রিচি (Dennis Ritchie)<br>
            <strong>উদ্ভাবনের সময়:</strong> 1972<br>
            <strong>উদ্ভাবনের স্থান:</strong> AT&T Bell Labs, যুক্তরাষ্ট্র<br>
            <strong>মূল উদ্দেশ্য:</strong> Unix অপারেটিং সিস্টেম তৈরি ও উন্নত করা।<br>
            <strong>বৈশিষ্ট্য:</strong><br>
            1. স্ট্রাকচারাল প্রোগ্রামিং<br>
            2. লো-লেভেল মেমরি অ্যাক্সেস<br>
            3. উচ্চ পারফরম্যান্স<br>
            4. পোর্টেবিলিটি<br>
            <strong>উপযোগিতা:</strong> অপারেটিং সিস্টেম এবং সফটওয়্যার তৈরি।<br>
        </p>
    </section>

    <!-- C++ সেকশন -->
    <section id="Cpp">
        <h2>C++ Language</h2>
        <p>
            <strong>আবিষ্কারক:</strong> বিজার্ন স্ট্রউস্ট্রুপ (Bjarne Stroustrup)<br>
            <strong>উদ্ভাবনের সময়:</strong> 1983<br>
            <strong>উদ্ভাবনের স্থান:</strong> AT&T Bell Labs, যুক্তরাষ্ট্র<br>
            <strong>মূল উদ্দেশ্য:</strong> C ভাষার উপর ভিত্তি করে Object-Oriented Programming সুবিধা যুক্ত করা।<br>
            <strong>বৈশিষ্ট্য:</strong><br>
            1. Object-Oriented Programming<br>
            2. Multi-Paradigm Support<br>
            3. High Performance<br>
            4. Backward Compatibility<br>
        </p>
    </section>

    <!-- Python সেকশন -->
    <section id="Python">
        <h2>Python Language</h2>
        <p>
            <strong>আবিষ্কারক:</strong> গুইডো ভ্যান রসাম (Guido van Rossum)<br>
            <strong>উদ্ভাবনের সময়:</strong> 1991<br>
            <strong>উদ্ভাবনের স্থান:</strong> নেদারল্যান্ডস<br>
            <strong>মূল উদ্দেশ্য:</strong> সহজ ও পাঠযোগ্য একটি প্রোগ্রামিং ভাষা তৈরি করা।<br>
            <strong>বৈশিষ্ট্য:</strong><br>
            1. ডায়নামিক টাইপিং<br>
            2. ইন্টারপ্রেটেড<br>
            3. মাল্টি-পারপাস<br>
            4. সহজ সিনট্যাক্স<br>
        </p>
    </section>

    <!-- Java সেকশন -->
    <section id="Java">
        <h2>Java Language</h2>
        <p>
            <strong>আবিষ্কারক:</strong> জেমস গসলিং (James Gosling)<br>
            <strong>উদ্ভাবনের সময়:</strong> 1995<br>
            <strong>উদ্ভাবনের স্থান:</strong> Sun Microsystems<br>
            <strong>মূল উদ্দেশ্য:</strong> "Write Once, Run Anywhere" ধারণা বাস্তবায়ন।<br>
            <strong>বৈশিষ্ট্য:</strong><br>
            1. Object-Oriented<br>
            2. প্ল্যাটফর্ম-ইন্ডিপেন্ডেন্ট<br>
            3. সিকিউরিটি ফোকাসড<br>
        </p>
    </section>

    <!-- JavaScript সেকশন -->
    <section id="JavaScript">
        <h2>JavaScript Language</h2>
        <p>
            <strong>আবিষ্কারক:</strong> ব্রেন্ডন আইচ (Brendan Eich)<br>
            <strong>উদ্ভাবনের সময়:</strong> 1995<br>
            <strong>উদ্ভাবনের স্থান:</strong> Netscape Communications<br>
            <strong>মূল উদ্দেশ্য:</strong> ওয়েব পেজ ইন্টারঅ্যাকটিভ করা।<br>
            <strong>বৈশিষ্ট্য:</strong><br>
            1. Client-Side এবং Server-Side প্রোগ্রামিং<br>
            2. ইভেন্ট-ড্রিভেন<br>
            3. ডায়নামিক এবং ফ্লেক্সিবল<br><br>
        </p>
    </section>

    <!-- ফুটার -->
    <footer>
        <p>&copy; 2024 Programming Languages.</p>
    </footer>

</body>
</html>
