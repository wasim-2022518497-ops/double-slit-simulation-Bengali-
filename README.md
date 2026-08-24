দ্বি-চিড় পরীক্ষা — ইন্টারেক্টিভ সিমুলেশন
Double-Slit Experiment — Interactive Simulation
   
বাংলা ভাষায় কণা-তরঙ্গ দ্বৈততার (wave-particle duality) একটি পরীক্ষাগতভাবে সঠিক, ইন্টারেক্টিভ ব্রাউজার-ভিত্তিক সিমুলেশন।
An experimentally accurate, interactive browser-based simulation of wave-particle duality in Bengali.
________________________________________
🔗 লাইভ ডেমো / Live Demo
👉 সিমুলেশনটি চালু করুন (Click to Run)
PC, মোবাইল এবং ট্যাবলেটে সরাসরি ব্রাউজারে চলবে।
________________________________________
📖 পরিচিতি / Introduction
এই সিমুলেশনটি কোয়ান্টাম মেকানিক্সের সবচেয়ে বিখ্যাত পরীক্ষা — দ্বি-চিড় পরীক্ষা (Double-Slit Experiment) — এর তিনটি ভিন্ন সেটআপ দেখায়:
This simulation demonstrates the three classic setups of the Double-Slit Experiment:
সেটআপ	Setup	কী ঘটে	What Happens
১	Control	দুটি চিড় খোলা, কোনো ডিটেক্টর নেই	Both slits open, no detector
২	Which-Way (One Detector)	একটি চিড়ে ডিটেক্টর	Detector at one slit
৩	Full Decoherence	উভয় চিড়ে ডিটেক্টর	Detectors at both slits
________________________________________
🧪 পদার্থবিজ্ঞান / Physics
সেটআপ ১ — নিয়ন্ত্রণ (Control)
তরঙ্গ ফাংশনের সুপারপজিশনে ব্যতিচার (interference) ঘটে। পর্দায় তীব্রতা:
I(θ) = I₀ (sin β / β)² cos² γ

যেখানে:
  β = (πa / λ) sin θ    → একক-চিড় বিবর্তন (single-slit diffraction)
  γ = (πd / λ) sin θ    → দ্বি-চিড় ব্যতিচার (double-slit interference)
ফলাফল: কেন্দ্রীয় ব্যান্ড সবচেয়ে উজ্জ্বল, পার্শ্ব ব্যান্ডগুলো ক্রমশ ক্ষীণ হয় — ব্যতিচার ফ্রিঞ্জ (interference fringes) তৈরি হয়।
সেটআপ ২ — একটি চিড়ে ডিটেক্টর (Which-Way)
চিড়-এ তে ডিটেক্টর কণার পথ নির্ণয় করে। কণা ডিটেক্টরের সাথে জড়িয়ে (entangles) যায় এবং তরঙ্গ ফাংশন ডিকোহের (decoheres) হয়। সুপারপজিশন ভেঙে যায়:
I = |ψₐ|² + |ψᵦ|²
ফলাফল: কেবল একক-চিড় বিবর্তনের প্রশস্ত কেন্দ্রীয় ব্যান্ড — কোনো ফ্রিঞ্জ নেই।
সেটআপ ৩ — উভয় চিড়ে ডিটেক্টর (Full Decoherence)
প্রতিটি কণার পথ নিশ্চিতভাবে পরিমাপ হয়। তরঙ্গ ফাংশন সম্পূর্ণভাবে কোলাপ্স করে। দুটি চিড়ের অবদানের অসমন্বিত যোগফল (incoherent sum) একটি মসৃণ, প্রশস্ত কেন্দ্রীয় ব্যান্ড তৈরি করে।
________________________________________
⚙️ ব্যবহার / Usage
1.	উপরের ট্যাব থেকে যেকোনো সেটআপ সিলেক্ট করুন
2.	চালু করুন বোতামে চাপ দিন
3.	পর্দায় আঘাতের বিন্যাস ধীরে ধীরে গড়ে ওঠা দেখুন
4.	বিরতি বা রিসেট বোতাম ব্যবহার করুন
________________________________________
📊 পরীক্ষাগত মান / Experimental Parameters
প্যারামিটার	Parameter	মান	Value
তরঙ্গদৈর্ঘ্য	Wavelength (λ)	500 nm	500 nm
চিড়ের প্রস্থ	Slit width (a)	0.08 mm	0.08 mm
চিড়ের ব্যবধান	Slit separation (d)	0.40 mm	0.40 mm
চিড় থেকে পর্দা	Slit-to-screen (L)	1.0 m	1.0 m
ফ্রিঞ্জ ব্যবধান	Fringe spacing	~1.25 mm	~1.25 mm
________________________________________
🛠️ স্থানীয়ভাবে চালান / Run Locally
# Clone the repository
git clone https://github.com/wasim-2022518497-ops/double-slit-simulation-Bengali-.git

# Navigate to the folder
cd double-slit-simulation-Bengali-



________________________________________
📱 সাপোর্টেড ডিভাইস / Supported Devices
•	✅ ডেস্কটপ (Chrome, Firefox, Safari, Edge)
•	✅ মোবাইল ফোন (Android / iOS)
•	✅ ট্যাবলেট (iPad / Android Tablet)
টাচ সাপোর্ট সহ সম্পূর্ণ রেসপন্সিভ ডিজাইন।
________________________________________
🎓 শিক্ষাগত উদ্দেশ্য / Educational Purpose
এই সিমুলেশনটি শিক্ষার্থীদের জন্য তৈরি যারা কোয়ান্টাম মেকানিক্সের মৌলিক ধারণাগুলো — যেমন: - তরঙ্গ-কণা দ্বৈততা (wave-particle duality) - সুপারপজিশন (superposition) - ডিকোহেরেন্স (decoherence) - কোপেনহেগেন ব্যাখ্যা (Copenhagen interpretation)
— বাংলা ভাষায় সহজভাবে বুঝতে চান।
________________________________________
📝 লাইসেন্স / License
এই প্রজেক্টটি MIT License-এর অধীনে লাইসেন্সকৃত।
This project is licensed under the MIT License.
________________________________________
👤 তৈরি করেছেন / Created By
Wasim Kamal
M.Sc. Theoretical Physics, University of Dhaka
📧 wasim-2022518497@tphy.du.ac.bd
________________________________________
“কোয়ান্টাম মেকানিক্সে, পর্যবেক্ষণই বাস্তবতা গঠন করে।”
“In quantum mechanics, observation creates reality.”
