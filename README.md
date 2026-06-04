# 🚀 BurPro One-Shot Automated Environment

ይህ ፕሮጀክት የ **Burp Suite Professional Edition** አካባቢን በማንኛውም የ Kali Linux ወይም Termux (PRoot Distro) ላይ ያለምንም አሰልቺ ቅደም ተከተሎች (Steps) በ "One-Shot" ለመጫን እና ለማስነሳት የተዘጋጀ አውቶሜትድ መተግበሪያ ነው።

---

## 🛠️ ቅድመ-ሁኔታዎች (Prerequisites)

ይህ መተግበሪያ እንዲሠራ በሲስተምህ ላይ **Java 25** መጫን አለበት። ጃቫ ካልተጫነ ወይም የድሮ ስሪት ከሆነ የሚከተሉትን ትዕዛዞች በተርሚናልህ ላይ በማሄድ በነፃ መጫን ትችላለህ።

### 1️⃣ በ Kali Linux ላይ Java 25 የመጫኛ መንገዶች፦
ተርሚናልህን ክፈትና የሚከተሉትን ትዕዛዞች በቅደም ተከተል አስነሳ፦

```bash
# የሲስተም ፓኬጆችን ማደስ
sudo apt update && sudo apt upgrade -y

# Java 25 OpenJDK መጫን
sudo apt install openjdk-25-jdk openjdk-25-jre -y

# በትክክል መጫኑን ማረጋገጫ (ስሪቱ 25 መሆኑን እይ)
java -version
