 # 👋 Hi, I'm Sank (a.k.a sankworks)

Civil Servant 🇰🇷 → Future Developer 🌎
Learning to build software and smart homes — step by step.

## 🧭 About Me
- 📘 Currently learning Python
- 🏡 Interested in Smart Home automation (long-term business plan)
- 💬 Dreaming of working abroad with my family
- 📫 Email: sankworks@gmail.com

## 🏅 Certificates

### 📘 Introduction to Python (SoloLearn)

![Python Certificate](https://api2.sololearn.com/v2/certificates/CC-YFA79XZB/image/png?t=638809300487453370)

- **Platform**: [SoloLearn](https://www.sololearn.com/)
- **Date**: April 22, 2025
- **Certificate ID**: CC-YFA79XZB

---

## 🛠️ Mini Python Projects

### 1. Terminal Login System (Practice)

```python
id = 'sankworks'
password = '1234'
attempt = 3

while attempt > 0:
    input_id = input('ID: ')
    if input_id != id:
        print('Wrong ID')
    else:
        input_pw = input('Password: ')
        if input_pw == password:
            print('Welcome!')
            break
        else:
            print('Wrong password')
    attempt -= 1

if attempt == 0:
    print('Access denied')


> “Code is not just for computers. It’s a language for your future.”
