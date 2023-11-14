

---

<div align="center">

# NoSQLProbe

![Version](https://img.shields.io/badge/any_text-you_like-blue)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat)


🔍 **A Powerful Tool for NoSQL Injection Testing**

![NoSQL Injection](https://example.com/path_to_your_gif.gif) <!-- Replace with a relevant GIF link -->

</div>

## Description
NoSQLProbe is a specialized tool designed for security professionals and ethical hackers. It facilitates the testing of NoSQL databases against blind NoSQL injection vulnerabilities, focusing on password recovery. This tool is intended for use in penetration testing and ethical hacking scenarios to assess and improve the security of web applications utilizing NoSQL databases.

## Features
- **🔑 Blind NoSQL Injection for Password Recovery:** Efficiently tests NoSQL databases for blind injection vulnerabilities.
- **⚙️ Customizable Parameters:** Tailor attacks with customizable request parameters for targeted vulnerability assessment.
- **💻 Cross-Platform Compatibility:** Works seamlessly across different operating systems.
- **📊 Detailed Reporting:** Generates comprehensive reports of the testing process, including timestamps, actions, and responses.

## Installation
Use the following commands to install NoSQLProbe:

```bash
# Clone the repository
git clone https://github.com/qil50/NoSQLProbe.git

# Navigate to the NoSQLProbe directory
cd NoSQLProbe/

# Install required libraries
pip install -r requirements.txt
```

## Usage

```bash
# Basic usage
python3 NoSQLProbe.py -u [URL] -uf [Username Field] -pf [Password Field] -b [Body JSON] [Other Options]

# For detailed usage instructions and options
python3 NoSQLProbe.py -h
```

### Example
```bash
python3 NoSQLProbe.py -u https://example.com/login -uf 'username' -pf 'password' -rn 'admin' -b '{"username":"", "password":""}' -sc 200 -f "Invalid credentials"
```

## Contributing

We welcome contributions to NoSQLProbe! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
![Discord](https://img.shields.io/discord/1170142610887815308)

## Disclaimer
NoSQLProbe is developed for ethical hacking purposes only. The authors and contributors are not responsible for any misuse or damage caused by this tool.

---
