---

# 🚀 BurpDroid: One-Shot Automated Mobile Penetration Testing Environment

በሞባይል መሳሪያዎች (Termux/PRoot Distro) እና በ Kali Linux ላይ የላቁ የደህንነት ፍተሻዎችን በሚያደርጉበት ጊዜ የ Burp Suite Professional አካባቢን በእጅ ማዋቀር፣ የፍቃድ ፋይሎችን መትከል እና ተደጋጋሚ የአነሳስ ቅደም ተከተሎችን መከተል እጅግ አሰልቺ እና አድካሚ ሂደት ነው።

**BurpDroid** ይህንን ችግር ሙሉ በሙሉ ይፈታል! ሁሉንም አስፈላጊ የሆኑ የጀርባ አግብሮቶች፣ የፓች ወኪሎች (Java Agents) እና የንብረት ፋይሎችን ወደ አንድ ነጠላ ፓኬጅ (`BurPro.jar`) በመጠቅለል፣ ያለምንም የፍቃድ ጥያቄ መስኮት **በአንድ ጠቅታ (One-Click)** ሙሉውን የPro ስሪት ወዲያውኑ ለአገልግሎት ዝግጁ ያደርጋል።

---

## ✨ ዋና ዋና ባህሪያት (Key Features)

* **ቅጽበታዊ አነሳስ (Instant Pro Activation):** ምንም ዓይነት የ Community/Pro ምርጫ ወይም የፍቃድ ማስገቢያ መስኮት ሳይመጣ በቀጥታ ወደ Pro Workspace ይገባል።
* **ሙሉ በሙሉ የተሟላ (Zero-Configuration):** የፓች ወኪሎችን ማዋቀር ወይም የፖሊሲ ፋይሎችን በእጅ ማስተካከል አይጠበቅብዎትም።
* **ራስገዝ ዝመና (Transparent Auto-Updates):** መተግበሪያው በተነሳ ቁጥር አዳዲስ ማሻሻያዎችን ከ GitHub ላይ በራሱ በመፈተሽ ያዘምናል።
* **ለሞባይል የተመቻቸ (Mobile-First Architecture):** በሊኑክስ ስልኮች፣ በ Termux አካባቢዎች እና በንፁህ የ Kali ስሪቶች ላይ ያለ እንከን እንዲሰራ ተደርጎ የተገነባ ነው።

---

## 🛠️ ቅድመ-ሁኔታዎች (Prerequisites)

ይህ መተግበሪያ በተሻለ አፈጻጸም እንዲሠራ በሲስተምዎ ላይ **Java 25** መጫን አለበት። ጃቫ ካልተጫነ የሚከተሉትን ትዕዛዞች በተርሚናልዎ ላይ በማሄድ መጫን ይችላሉ።

### 1️⃣ በ Kali Linux ላይ Java 25 ለመጫን፦


# የሲስተም ፓኬጆችን ማደስ
```
sudo apt update && sudo apt upgrade -y
```
# Java 25 OpenJDK መጫን
```
sudo apt install openjdk-25-jdk openjdk-25-jre -y
```
# ስሪቱን ማረጋገጥ
```
java -version

```

### 2️⃣ በ Termux (Kali PRoot) ላይ ለመጫን፦

```bash
apt update && apt upgrade -y
apt install openjdk-25 -y
java -version

```
# Or Install the default 
```
apt install -y default-jdk 
```
---

## 🚀 አጠቃቀም (How to Use)

ምንም አይነት ተጨማሪ ፋይል ወይም መቼት ማስተካከል አይጠበቅብዎትም! የሚከተሉትን ሁለት ትዕዛዞች ብቻ በተርሚናልዎ ላይ ያሂዱ፦

# 1. ማጠራቀሚያውን መቅዳት
```bash
wget 
```
# 2. መተግበሪያውን ማስነሳት
```
java -jar BurPro.jar

```

---

## 📸 የእይታ ማሳያ (Visual Showcase)

ፕሮጀክቱ በሚነሳበት እና በሚሰራበት ጊዜ ያለው የሂደት ሂደት በሚከተሉት ምስሎች ተደራጅቷል (ምስሎቹን በ ማከማቻዎ ውስጥ `assets/screenshots/` በሚለው ፎልደር ስር ያስቀምጧቸው)፦

### 1. የስርዓት መነሳት እና ማረጋገጫ (Boot & Verification Sequence)

መተግበሪያው ሲነሳ የኮር አውቶሜሽን ባነር፣ የ GitHub አውቶ-አፕዴት ፍተሻ እና ንብረቶችን የማዘጋጀት ስራዎችን በአስተማማኝ ሁኔታ ያከናውናል።


### 2. ፈጣን የፕሮጀክት ጠንቋይ (Instant Project Wizard)

ያለምንም የፍቃድ ወይም የኮሚዩኒቲ ምርጫ ጥያቄ፣ መተግበሪያው ወዲያውኑ የባለሙያ መለያ ፍቃዱን አረጋግጦ አዲስ ፕሮጀክት እንዲከፍቱ ያዘጋጅልዎታል።


### 3. ሙሉ የባለሙያ ዳሽቦርድ (Active Professional Dashboard)

ሁሉም የላቁ የፍተሻ ክፍሎች (Scanner, Intruder, Repeater) ሙሉ በሙሉ እንደነቁ የሚያሳይ የቀጥታ ስራ ቦታ አካባቢ።


---

## 🔄 አውቶሜትድ አፕዴት (Self-Updating System)

በየጊዜው ተርሚናል ላይ `java -jar BurPro.jar` በምትሉበት ሰዓት፦

* መተግበሪያው በመጀመሪያ ከ GitHub የሊንክ አውታረ መረብ ላይ አዲስ ማሻሻያ መኖሩን ያያል።
* አዲስ ስሪት ካገኘ የቅርብ ጊዜውን ፋይል በራሱ አውርዶ በጀርባ ይተካል።
* ተጠቃሚው ሁልጊዜ የሚያገኘው የቅርብ ጊዜውን እና የተስተካከለውን የ Pro ስሪት ይሆናል።

---

## 🧹 ሲስተሙን ሙሉ በሙሉ እንደ አዲስ ለማጽዳት (Reset Cache)

መተግበሪያውን ሙሉ በሙሉ አጥፍተው መሸጎጫዎችን (Cache) በማጽዳት ልክ እንደ አዲስ ለመጀመር ከፈለጉ ይህንን ትዕዛዝ በተርሚናልዎ ላይ ያሂዱ፦

```bash
rm -rf ~/.BurPro_internal_cache ~/.java/.userPrefs/burp

```

---

**ማሳሰቢያ፦** ይህ መተግበሪያ ለትምህርት፣ ለደህንነት ምርምር እና ህጋዊ ለሆኑ የፔኔትሬሽን ቴስቲንግ ስራዎች ብቻ እንዲያገለግል የተዘጋጀ ነው።
