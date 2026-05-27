# FTCScouterAppSupportContact
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>App Support</title>
    <style>
        :root {
            --primary-color: #007aff; /* iOS Blue */
            --text-color: #1c1c1e;
            --bg-color: #f2f2f7;
            --card-bg: #ffffff;
            --border-color: #e5e5ea;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
            padding-bottom: 40px;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            margin-top: 20px;
        }

        .app-icon {
            width: 80px;
            height: 80px;
            border-radius: 18px;
            margin-bottom: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        h1 {
            font-size: 24px;
            font-weight: 700;
            margin: 0 0 4px 0;
        }

        .version {
            font-size: 14px;
            color: #8e8e93;
            margin: 0;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }

        h2 {
            font-size: 18px;
            font-weight: 600;
            margin-top: 0;
            margin-bottom: 15px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
        }

        .btn {
            display: block;
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            text-decoration: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: 600;
            margin-top: 15px;
            transition: opacity 0.2s;
        }

        .btn:hover {
            opacity: 0.9;
        }

        .faq-item {
            margin-bottom: 15px;
        }

        .faq-item:last-child {
            margin-bottom: 0;
        }

        .faq-question {
            font-weight: 600;
            margin-bottom: 4px;
        }

        .faq-answer {
            color: #48484a;
            margin: 0;
            font-size: 15px;
        }

        footer {
            text-align: center;
            font-size: 13px;
            color: #8e8e93;
            margin-top: 30px;
        }

        footer a {
            color: var(--primary-color);
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header: App Branding -->
        <header>
            <!-- Replace with your actual app icon URL or local path -->
            <img src="https://placeholder.com" alt="App Icon" class="app-icon">
            <h1>Your App Name</h1>
            <p class="version">Version 1.0.0 Support</p>
        </header>

        <!-- Contact Section -->
        <div class="card">
            <h2>Contact Support</h2>
            <p>Have a question, bug report, or feature request? We are here to help you.</p>
            <!-- Replace with your actual support email -->
            <a href="mailto:support@://yourdomain.com" class="btn">Email Support</a>
        </div>

        <!-- FAQ Section -->
        <div class="card">
            <h2>Frequently Asked Questions</h2>
            
            <div class="faq-item">
                <div class="faq-question">How do I restore my purchases?</div>
                <div class="faq-answer">Open the App Settings menu inside the app and tap "Restore Purchases." Ensure you are signed in with the same Apple ID used for the original purchase.</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">How do I request a refund?</div>
                <div class="faq-answer">Apple processes all purchases and refunds directly. Please visit <a href="https://apple.com" target="_blank">://apple.com</a> to request a refund.</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">The app is crashing. What should I do?</div>
                <div class="faq-answer">Please ensure you have updated to the latest version of iOS and the app. If the issue persists, contact us via the email link above with your device model.</div>
            </div>
        </div>

        <!-- Footer Links -->
        <footer>
            <!-- Keep these links updated or point them to your respective files -->
            <p>© 2026 Your Name/Company. All rights reserved.</p>
            <p>
                <a href="privacy.html">Privacy Policy</a> | 
                <a href="terms.html">Terms of Service</a>
            </p>
        </footer>
    </div>

</body>
</html>
