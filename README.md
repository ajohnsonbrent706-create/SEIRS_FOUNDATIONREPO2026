Due: Tuesday, October 20, 2026, at 12:00 PM Central Time.

Independently perform three separate successful EC2 launches, preferably reusing your saved launch template. For each deployment:

Launch a new EC2 instance.
Wait until it is ready.
Record its public IPv4 address.
Successfully connect through EC2 Instance Connect or SSH.
Show the SEIR dashboard or run seir-dashboard.
Capture a screenshot demonstrating your connection and dashboard.
Write a brief explanation of what you did, how you connected, and what the dashboard showed.
Terminate the instance after collecting evidence, unless the instructor specifically directs otherwise.
You must demonstrate three different public IPv4 addresses across the three deployments. Public IP addresses are assigned by AWS and can sometimes be reused, so do not assume a fresh launch guarantees a unique address. If an address repeats, record that observation and perform another launch until you have three distinct addresses. Do not purchase Elastic IP addresses to satisfy this requirement.

You may run the deployments sequentially. Three simultaneous running instances are not required. This reduces unnecessary costs.

Homework evidence table

Fill in this table in your own GitHub submission:

Deployment	Public IPv4 address	Connection method	Screenshot	Instance terminated?
1	YOUR_IP_1	EC2 Connect / SSH	screenshots/deployment-1.png	Yes / No
2	YOUR_IP_2	EC2 Connect / SSH	screenshots/deployment-2.png	Yes / No
3	YOUR_IP_3	EC2 Connect / SSH	screenshots/deployment-3.png	Yes / No
Screenshot guidance: Capture the SSH terminal and dashboard; include the instance's public IPv4 in your written explanation or an accompanying AWS Console screenshot. A terminal dashboard alone may not display the public IP. Do not expose private keys, passwords, AWS access keys, tokens, or other secrets.

Suggested GitHub submission structure

seir-foundations-homework/
└── module1/
    └── lab0_basics/
        ├── README.md
        └── screenshots/
            ├── deployment-1.png
            ├── deployment-2.png
            └── deployment-3.png
In your submission README, include:

The completed evidence table with three distinct public IPv4 addresses.
One short paragraph per deployment describing the launch, SSH connection, and dashboard.
What CPU, memory, disk, and uptime tell you about the instance.
One thing that became easier after repeating the process.
Any errors encountered and how you resolved them.
Confirmation that you retained the launch template and cleaned up practice instances.
Commit and push your screenshots and explanation to your GitHub repository. Submit the repository link through the instructor's designated submission channel by the deadline. Posting the first screenshot to Zoom during class does not replace the GitHub homework submission.
