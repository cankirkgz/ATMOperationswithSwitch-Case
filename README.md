<h1>ATM Operations with Switch-Case</h1>
   <p>This Java program simulates ATM operations such as depositing money, withdrawing money, checking balance, and exiting the system. It prompts the user to enter their username and password, and if the credentials are correct, it allows them to perform various banking operations.</p>

   <h2>Features</h2>
   <ul>
        <li>Secure login system using username and password</li>
        <li>Deposit money into the account</li>
        <li>Withdraw money from the account (if sufficient balance is available)</li>
        <li>Check account balance</li>
        <li>Graceful system exit</li>
    </ul>

   <h2>Getting Started</h2>
   <h3>Prerequisites</h3>
   <ul>
        <li>Java Development Kit (JDK) installed on your system</li>
    </ul>

   <h3>How to Run</h3>
   <ol>
        <li>Clone the repository or download the source code files.</li>
        <li>Open a command prompt or terminal and navigate to the project directory.</li>
        <li>Compile the Java file using the following command:<br><code>javac Main.java</code></li>
        <li>Run the program using the following command:<br><code>java Main</code></li>
        <li>Follow the prompts on the screen to enter your username, password, and perform ATM operations.</li>
    </ol>

   <h2>Usage</h2>
   <ol>
        <li>Enter your username and password when prompted.</li>
        <li>Upon successful login, choose from the available options:
            <ul>
                <li>Enter <code>1</code> to deposit money into your account. Provide the amount to deposit.</li>
                <li>Enter <code>2</code> to withdraw money from your account. Provide the amount to withdraw.</li>
                <li>Enter <code>3</code> to check your account balance.</li>
                <li>Enter <code>4</code> to exit the system.</li>
            </ul>
        </li>
        <li>Continue performing operations until you choose to exit.</li>
    </ol>

   <h2>Notes</h2>
   <ul>
        <li>The default username is "patika" and the default password is "dev123". Modify the source code to change these values if needed.</li>
        <li>The program provides a limited number of login attempts before the account is blocked. In this example, the user has 3 attempts. Modify the code to change the number of attempts if desired.</li>
    </ul>

   <h2>License</h2>
   <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
