
# 🚀 BurPro One-Shot Automated Environment

ይህ ፕሮጀክት የ **Burp Suite Professional Edition** አካባቢን በማንኛውም የ Kali Linux ወይም Termux (PRoot Distro) ላይ ያለምንም አሰልቺ ቅደም ተከተሎች (Steps) በ "One-Shot" ለመጫን እና ለማስነሳት የተዘጋጀ አውቶሜትድ መተግበሪያ ነው።

---

## 🛠️ ቅድመ-ሁኔታዎች (Prerequisites)

ይህ መተግበሪያ እንዲሠራ በሲስተምህ ላይ **Java 25** መጫን አለበት። ጃቫ ካልተጫነ ወይም የድሮ ስሪት ከሆነ የሚከተሉትን ትዕዛዞች በተርሚናልህ ላይ በማሄድ በነፃ መጫን ትችላለህ።

### 1️⃣ በ Kali Linux ላይ Java 25 የመጫኛ መንገዶች፦
ተርሚናልህን ክፈትና የሚከተሉትን ትዕዛዞች በቅደም ተከተል አስነሳ፦

```bash
# የሲስተም ፓኬጆችን ማደስ
apt update && apt upgrade -y
```
```
# Java 25 OpenJDK መጫን
apt install openjdk-25-jdk openjdk-25-jre -y
```
```
# በትክክል መጫኑን ማረጋገጫ (ስሪቱ 25 መሆኑን እይ)
java -version

```

### 2️⃣ በ Termux (Kali PRoot) ላይ ለመጫን፦

```bash
apt update && apt upgrade -y
apt install openjdk-25 -y
java -version

```

---

## 🚀 አጠቃቀም (How to Use)

ምንም አይነት ተጨማሪ ፋይል ወይም Settings ማስተካከል አይጠበቅብህም!

1. ከዚህ GitHub ሪፖዚቶሪ ላይ `BurPro.jar` የሚለውን ፋይል ብቻ አውርድ።
``bash
git clone https://github.com/ANK-369/BurpDroid.git
cd BurpDroid
``
3. ወደ ወረደበት ፎልደር በተርሚናል ግባና የሚከተለውን ነጠላ ትዕዛዝ ብቻ አስነሳ፦

```bash
java -jar BurPro.jar

```

---

## 🔄 አውቶሜትድ አፕዴት (Self-Updating System)

ይህ መተግበሪያ በራሱ የሚደስስ (Self-Updating) ሎጂክ አለው። በየጊዜው ተርሚናል ላይ `java -jar BurPro.jar` በምትልበት ሰዓት፦

* መተግበሪያው በመጀመሪያ ከዚህ የ GitHub ገጽ ላይ አዲስ ማሻሻያ መኖሩን በራሱ ያያል።
* አዲስ ስሪት ካገኘ የቅርብ ጊዜውን ፋይል በራሱ አውርዶ ይተካል።
* አንተ ሁልጊዜ የምታገኘው የቅርብ ጊዜውን እና የተስተካከለውን የ Pro ስሪት ይሆናል።

---

## 🧹 ሲስተሙን ሙሉ በሙሉ እንደ አዲስ ለማጽዳት (Reset)

መተግበሪያውን ሙሉ በሙሉ አጥፍተህ ልክ እንደ አዲስ ስልክ መሞከር ከፈለግክ ይህንን ትዕዛዝ ተጠቀም፦

```bash
rm -rf ~/.BurPro_internal_cache ~/.java/.userPrefs/burp

```
