# TASK_2
# FIGMA-TASK_-1
**COMPANY**:CODETECH IT SOLUTIONS
**NAME**:KAVI PRIYA S
**INTERN ID**:CT08FSG
**DOMAIN**:UI/UX
**DURATION**:4 WEEKS
**MENTOR**:NEELA SANTOSH
**CODE**:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Webpage</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background: #007bff;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            background: #333;
            color: white;
            padding: 0.5rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .container {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }

        .container p {
            font-size: 1.2rem;
        }

        .certificate {
            margin-top: 2rem;
            padding: 2rem;
            border: 2px dashed #007bff;
            text-align: center;
            background: white;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        /* Media Queries */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                text-align: center;
            }

            .container p {
                font-size: 1rem;
            }

            .certificate {
                padding: 1rem;
                font-size: 1rem;
            }
        }

        @media (max-width: 480px) {
            header h1 {
                font-size: 1.5rem;
            }

            nav ul li {
                margin: 10px 0;
            }

            .container {
                padding: 1rem;
            }

            .certificate {
                font-size: 0.9rem;
            }

            footer p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Responsive Webpage Design</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <p>Welcome to the responsive webpage design tutorial. This page adjusts to various screen sizes using HTML, CSS, and JavaScript. Follow the instructions below to complete your internship project successfully.</p>

        <div class="certificate">
            <h2>Completion Certificate</h2>
            <p>Your completion certificate will be issued on your internship end date.</p>
            <p><strong>CodTech</strong></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 CodTech. All rights reserved.</p>
    </footer>
</body>
</html>
**DESCRIPTION**:
This code is for a responsive webpage designed using HTML and CSS, with responsiveness achieved through media queries. Its purpose is to provide a seamless user experience across different devices, such as desktops, tablets, and mobile phones.
HTML Structure
The HTML section forms the structural backbone of the webpage:
Document Declaration and Metadata:
The <!DOCTYPE html> specifies the document type as HTML5.
The <html lang="en"> sets the language to English for accessibility.
Inside <head>, metadata such as <meta charset="UTF-8"> ensures proper character encoding for all text. The <meta name="viewport" content="width=device-width, initial-scale=1.0"> ensures the webpage scales properly on all screen sizes. The <title> defines the name of the webpage shown in the browser tab.
Page Content:
The <body> contains the main content divided into:
Header (<header>): Displays the page title, “Responsive Webpage Design,” with a blue background and white text.
Navigation Bar (<nav>): Contains a horizontal list of links (Home, About, Contact). The links are styled to remove underlines and align evenly.
Main Content Area (.container): Includes a welcome message and a section styled to look like a certificate. The certificate section has a dashed border, centered text, and some padding.
Footer (<footer>): Displays a copyright message centered at the bottom of the page.
CSS Styling
The CSS is embedded within the <style> tags and defines the webpage's layout and appearance. It ensures that the page is visually appealing and adjusts dynamically to screen size.
Global Reset:
The * selector removes default padding and margin from all elements (margin: 0; padding: 0) and ensures consistent box-sizing with `box-sizing'
**OUTPUT**:
![Image](https://github.com/user-attachments/assets/19c85072-faeb-4680-8344-a884abcc7141)
