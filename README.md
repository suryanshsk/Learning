<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learning Repository Contribution Guide</title>
    <style>
        :root {
            --color-primary: #FF0000; 
            --color-secondary: #1a1a1a; 
            --color-text: #333333;
            --color-background: #ffffff; 
            --color-light-gray: #f9f9f9;
            --color-border: #eeeeee;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--color-text);
            background-color: var(--color-background);
            margin: 0;
            padding: 20px;
        }
       .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--color-background);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        /* --- Header/Title --- */
        .header {
            text-align: center;
            padding-bottom: 20px;
            margin-bottom: 30px;
            border-bottom: 3px solid var(--color-primary);
        }
        .header h1 {
            color: var(--color-secondary);
            font-size: 2.2em;
            margin-bottom: 5px;
        }
        .header p {
            color: var(--color-primary);
            font-size: 1.1em;
            font-weight: bold;
        }
        /* --- Section Styling --- */
        .step-section {
            margin-bottom: 40px;
        }
        .step-section h2 {
            color: var(--color-primary);
            font-size: 1.8em;
            border-left: 5px solid var(--color-primary);
            padding-left: 15px;
            margin-bottom: 20px;
            background-color: var(--color-light-gray);
            padding: 10px 15px;
            border-radius: 4px;
        }
        /* --- Individual Step Styling (List) --- */
        .steps ol, .steps ul {
            list-style: none;
            padding: 0;
        }
        .steps li {
            background: var(--color-light-gray);
            margin-bottom: 15px;
            padding: 15px;
            border-radius: 6px;
            border: 1px solid var(--color-border);
            display: flex;
            align-items: flex-start;
        }
        .steps li strong {
            color: var(--color-primary);
            display: block;
            margin-bottom: 5px;
        }
        .step-number {
            font-size: 1.5em;
            font-weight: bold;
            color: var(--color-background);
            background-color: var(--color-secondary);
            border-radius: 50%;
            width: 30px;
            height: 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-shrink: 0;
            margin-right: 15px;
        }
        /* --- Code/Input Styling --- */
        code {
            background-color: #ffe8e8; /* Light Red/Pink for distinction */
            color: var(--color-primary);
            padding: 3px 6px;
            border-radius: 4px;
            font-family: 'Consolas', monospace;
            font-weight: bold;
        }
        /* --- Note/Callout Styling --- */
        .note {
            background-color: #fce8e8; /* Lighter red background */
            border-left: 4px solid var(--color-primary);
            padding: 15px;
            margin-top: 10px;
            border-radius: 4px;
            font-style: italic;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="header">
        <h1>Learning Repository Contribution Guide</h1>
        <p>A centralized repository containing every club member's learning goals and projects.</p>
    </div>
    <div class="step-section">
        <h2>🛠️ Creating Your Learning Folder</h2>
        <div class="steps">
            <ol>
                <li>
                    <span class="step-number">1</span>
                    <div>
                        <strong>Fork the Learning repository.</strong>
                        <br>(This creates a copy of the original repository on your own GitHub account where you can make changes.)
                    </div>
                </li>
                <li>
                    <span class="step-number">2</span>
                    <div>
                        Go to the **<kbd>+</kbd> button** next to **&lt;&gt; CODE**.
                    </div>
                </li>
                <li>
                    <span class="step-number">3</span>
                    <div>
                        Then click on **Create File**.
                    </div>
                </li>
                <li>
                    <span class="step-number">4</span>
                    <div>
                        Above Edit|Preview you see <code>Learning/[input box]</code>.
                    </div>
                </li>
                <li>
                    <span class="step-number">5</span>
                    <div>
                        In the Input box type <code>&lt;your_name&gt;/.gitignore</code>.
                    </div>
                </li>
            </ol>
        </div>
    </div>
    <div class="step-section">
        <h2>📝 Committing Your Changes</h2>
        <div class="steps">
            <ol start="6">
                <li>
                    <span class="step-number">6</span>
                    <div>
                        <strong>Add Your Files:</strong> In the editor area below, you can add content to your <code>.gitignore</code> file, or simply leave it blank for now.
                        <div class="note">
                            **Note:** The <code>.gitignore</code> file is used to specify intentionally untracked files that Git should ignore.
                        </div>
                    </div>
                </li>
                <li>
                    <span class="step-number">7</span>
                    <div>
                        Click the **Commit changes...** button at the top-right or bottom of the page.
                    </div>
                </li>
                <li>
                    <span class="step-number">8</span>
                    <div>
                        Type a short, descriptive **commit message** (e.g., "Add &lt;your\_name&gt; folder and .gitignore").
                    </div>
                </li>
                <li>
                    <span class="step-number">9</span>
                    <div>
                        Ensure the radio button is selected for **"Commit directly to the &lt;your\_branch\_name&gt; branch"** (your forked branch).
                    </div>
                </li>
                <li>
                    <span class="step-number">10</span>
                    <div>
                        Click **Commit changes**.
                    </div>
                </li>
            </ol>
        </div>
    </div>
    <div class="step-section">
        <h2>🚀 Create the Pull Request (PR)</h2>
        <div class="steps">
            <ol start="11">
                <li>
                    <span class="step-number">11</span>
                    <div>
                        Navigate back to the **main page of your forked repository**.
                    </div>
                </li>
                <li>
                    <span class="step-number">12</span>
                    <div>
                        Look for the banner indicating recent pushes and click the **"Compare & pull request"** button, or go to the **"Pull requests"** tab and click **"New pull request"**.
                    </div>
                </li>
                <li>
                    <span class="step-number">13</span>
                    <div>
                        <strong>Verify Branch Settings:</strong> Ensure the branches are correctly set:
                        <ul>
                            <li>**base repository:** The original club repository.</li>
                            <li>**base:** The branch in the original repo you want to merge into (likely <code>main</code> or <code>master</code>).</li>
                            <li>**head repository:** Your forked repository.</li>
                            <li>**compare:** The branch in your fork that has your changes.</li>
                        </ul>
                    </div>
                </li>
                <li>
                    <span class="step-number">14</span>
                    <div>
                        Give your Pull Request a clear and descriptive **Title** and **Description**. (The description should briefly explain what you added, e.g., "Adds my learning folder and initial .gitignore file").
                    </div>
                </li>
                <li>
                    <span class="step-number">15</span>
                    <div>
                        Click the **Create pull request** button.
                    </div>
                </li>
            </ol>
        </div>
        <div class="note" style="border-left-color: var(--color-secondary); background-color: var(--color-light-gray);">
            🎉 **Success!** Your Pull Request is now open. A maintainer will review your changes and then merge them into the main project.
        </div>
    </div>
</div>

</body>
</html>
