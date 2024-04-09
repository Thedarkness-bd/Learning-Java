
## বাংলায় জাভা প্রোগ্রামিং 🍵

**লেখক পরিচিতি ✍️**

আসসালামু-আলাইকুম । আমি তাওসিফ তাসরিক । আমি বর্তমানে  কম্পিউটার সাইন্স এন্ড ইঞ্জিনিয়ারিং পড়ছি  ইউনিভার্সিটি অফ স্কলার্স  এ । আমার ১ম সেমিস্টার থাকাকালীন সময় এই বই লিখা শুরু করি। ছোট বেলা থেকেই আমি একজন কম্পিউটার এর খুবি বড় ভক্ত হয়ে আছি । ফাক পেলেই যে গেম খেলতাম সে জন্য আমি কত যে বকা খেয়েছি তা গুণতে শেষ হবে না । ওই গেম খেলা থেকে যেমন কীবোর্ড আয়ত্ত করেছি , তেমনি একদিন আমার মামার কাছ থেকে শুনা প্রোগ্রামিং শব্দ টা নিয়ে অনেক ঘাটাঘাটি করে শিখতে পেরেছি বেশ কয়েকটা প্রোগ্রামিং ল্যাঙ্গুয়েজ ।  এই বই টা উৎসর্গ করা হবে আমার প্রিয় মানুষদের  আমার মা , বাবা , বোন  , মামা , চাচ্চূ , নন্দিনী ।  লিস্ট অনেক বড় দুঃখিত ,কিন্তু এসব মানুষ এর জন্যই হয়ত এতদুর আসতে পারা । ১ম সেমিস্টার থেকেই যে এত কিছু করতে পারবো তা চিন্তা ভাবনার বাহিরে। আমার প্রোগ্রামিং যাত্রা শুরু হয় ২০১৬ সাল এ । মামার কাছে যখন প্রোগ্রামিং এর কথা শুনি তখন মামা বলেছিলেন যে " সি প্রোগ্রামিং " দিয়ে শুরু করো । আমি যথারীতি সি প্রোগ্রামিং লিখে ইউটিউব এ সার্চ দেই অনেক কিছুই এসে পরে কিছুই বুঝতে পারিনি , কোনটা ছেড়ে কোনটা দেখব । তখন পেলাম তামিম শাহরিয়ার সুবিন ভাই এর ভিডিও । এইতো তারপর থেকে শেখা শুরু করি এরপর থেকেই লেগে আছি । মাঝে অনেক বাধা বিপত্তি আসলেও টিকে আছি । আল্লাহ্‌ আলহামদুলিল্লাহ আমাাকে ভালো রেখেছেন ।  


**লেখার উদ্দেশ্য** 
মানুষের মাঝে জাভার যে ভয়ভীতি আছে তা দূর করা । বই বা Documentation  এ মানুষের আগ্রহ বাড়ানো । 

**একটা উপদেশঃ** প্রথম ল্যাঙ্গুয়েজ সি দিয়ে শুরু করেন । তাহলে আপনি এই জাভা প্রোগ্রামিং এর একদম বস হয়ে উঠবেন। সাথে আমার লেখা এই বই আপনার কাছে পানি ভাত মনে হবে । 

আমি ধরে নিব এই বই যারা পড়বেন তাদের আগে থেকেই সি প্রোগ্রামিং সম্পর্কে আইডিয়া আছে ।


## সূচিপত্র

- [বেসিক প্রোগ্রামিং](#basic-java)
	- [১.কেন জাভা ?](#why-java)

	- [২.কোড লেখার জায়গা তৈরি](#setup-java)

	- [৩.প্রথম "Hello,World" লেখা](#helloworld)

	- [৪.ভ্যারিয়েবল এবং ডেটা টাইপ নিয়ে যত কথা](#variable-and-data-types)

	- [৫.শর্তের উপর শর্ত { কন্ডিশনাল স্টেটমেন্ট }](#if-else)

	- [৬.লুপ নিয়ে বাড়াবাড়ি](#loop)

	- [৭.চমৎকার মোজাইক ডিজাইন { প্যাটার্ন }](#pattern)

	- [৮.ফাংশন এবং মেথডস এর শুরু থেকে শেষ](#function-and-method)

	- [৯.অ্যাারে { জগাখিচুরি }](#array)

	- [১০.বেসিক সর্টিং অ্যালগরিদম](#sorting-algorithm)

	- [১১.দুই অ্যারে এর কথোপকথন { ২ডি অ্যারে }](#2d-array)

	- [১২.দুই কোটেশন কিনবা এক কোটেশন { স্ট্রিং }](#strings)

	- [১৩.বিট ম্যানুপুলেশন](#bit-manipulation)

	- [১৪.অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং { ওওপি }](#oop)

 - [প্রোগ্রামিং সমস্যা](#prog-problems)

<a name="why-java"></a>
# কেন জাভা ? 
জাভা শেখা বিভিন্ন কারণে উপকারী হতে পারে:

1. **বহুমুখিতা**: জাভা একটি বহুমুখী ভাষা যা ওয়েব ডেভেলপমেন্ট থেকে শুরু করে মোবাইল অ্যাপস (অ্যান্ড্রয়েড ডেভেলপমেন্ট), এন্টারপ্রাইজ সফ্টওয়্যার, বৈজ্ঞানিক অ্যাপ্লিকেশন এবং আরও অনেক কিছুতে ব্যবহৃত হয়।

2. **জনপ্রিয়তা**: জাভা বহু বছর ধরে সবচেয়ে জনপ্রিয় প্রোগ্রামিং ভাষাগুলির মধ্যে একটি। এর জনপ্রিয়তার অর্থ হল ডেভেলপারদের একটি বৃহৎ সম্প্রদায়, বিস্তৃত ডকুমেন্টেশন, এবং শেখার ও সমর্থনের জন্য উপলব্ধ অসংখ্য সংস্থান রয়েছে।

3. **চাকরির সুযোগ**: অনেক কোম্পানি, বিশেষ করে এন্টারপ্রাইজ সেক্টরে, তাদের সফ্টওয়্যার উন্নয়ন প্রকল্পের জন্য জাভা ব্যবহার করে। জাভা শেখা বিভিন্ন শিল্প ও প্রতিষ্ঠানে চাকরির সুযোগ খুলে দিতে পারে।

4. **প্ল্যাটফর্ম স্বাধীনতা**: জাভা তার "একবার লিখুন, যে কোনো জায়গায় চালান" দর্শনের জন্য পরিচিত, যার অর্থ জাভা ভার্চুয়াল মেশিন (JVM) আছে এমন যেকোনো ডিভাইসে জাভা প্রোগ্রাম চলতে পারে। এই প্ল্যাটফর্মের স্বাধীনতা জাভাকে ক্রস-প্ল্যাটফর্ম অ্যাপ্লিকেশন বিকাশের জন্য বিশেষভাবে উপযোগী করে তোলে।

5. **অবজেক্ট-ওরিয়েন্টেড প্রোগ্রামিং (OOP)**: জাভা একটি অবজেক্ট-ওরিয়েন্টেড প্রোগ্রামিং ভাষা, যা একটি বহুল ব্যবহৃত প্রোগ্রামিং প্যারাডাইম। জাভা শেখা আপনাকে OOP ধারণাগুলিকে কার্যকরভাবে বুঝতে এবং প্রয়োগ করতে সাহায্য করতে পারে, যা অন্যান্য অনেক প্রোগ্রামিং ভাষার ক্ষেত্রেও প্রযোজ্য।

6. **শক্তিশালী ইকোসিস্টেম**: জাভা-এর একটি শক্তিশালী ইকোসিস্টেম রয়েছে যার বিশাল অ্যারের লাইব্রেরি, ফ্রেমওয়ার্ক এবং টুল রয়েছে যা উন্নয়ন প্রক্রিয়াকে স্ট্রিমলাইন করতে পারে এবং উৎপাদনশীলতা বাড়াতে পারে।

7. **নিরাপত্তা**: Java এর অন্তর্নির্মিত সুরক্ষা বৈশিষ্ট্য রয়েছে যা এটিকে নিরাপদ অ্যাপ্লিকেশন বিকাশের জন্য একটি পছন্দের পছন্দ করে তোলে, বিশেষত ফিনান্স এবং ব্যাঙ্কিংয়ের মতো শিল্পগুলিতে যেখানে নিরাপত্তা অত্যন্ত গুরুত্বপূর্ণ৷

8. **স্কেলেবিলিটি**: জাভা স্কেলেবল অ্যাপ্লিকেশন তৈরির জন্য উপযুক্ত, এটি ছোট প্রকল্প এবং বড় আকারের এন্টারপ্রাইজ অ্যাপ্লিকেশন উভয়ের জন্য উপযুক্ত করে তোলে।

আপনি সফ্টওয়্যার ডেভেলপমেন্টে ক্যারিয়ার গড়তে আগ্রহী হন না কেন, আপনার নিজস্ব অ্যাপ্লিকেশন তৈরি করতে চান, বা কেবল আপনার প্রোগ্রামিং দক্ষতা প্রসারিত করতে চান, জাভা শেখা আপনার সময় এবং প্রচেষ্টার একটি মূল্যবান বিনিয়োগ হতে পারে।


<br/>

<a name="setup-java"></a>
# কোড লেখার জায়গা তৈরি
আসসালামু-আলাইকুম । আজকে এই লেখায় আমরা দেখবো কিভাবে আমরা আমাদের জাভা কোড লেখার জায়গা তৈরি করতে পারি । আমাদের অবশ্যই ইনটারনেট কানেকশন সহ একটি কম্পিউটার বা ল্যাপটপ থাকা জরুরি । আপানারা যদি কেউ মোবাইল দিয়ে করতে চান সে ক্ষেত্রে আমি বলবো অনলাইন কম্পাইলার ব্যবহার করতে । আমি নিচে বেশ কিছু কম্পাইলারের লিঙ্ক দিয়ে দিচ্ছি আপনারা দেখতে পারেন । 

অনলাইন কম্পাইলের লিঙ্কঃ 
1. https://www.jdoodle.com/online-java-compiler
2. https://www.programiz.com/java-programming/online-compiler/
3. https://www.online-java.com/


এই তিনটা তেই ইনশাআল্লাহ হয়ে যাওয়ার কথা । 

এবার আসা যাক উইন্ডোজ এর সেটাপ ইন্সট্রাকশন এ ।

**ধাপ-১:** আমাদের প্রথমে আমাদের নিজেদের ব্যবহার করা ব্রাউজার এ যেতে হবে । গিয়ে আমরা প্রথমে লিখব "Visual Studio Code" । 

**ধাপ-২:** এরপর আমরা দেখতে পাবো আমাদের সামনে এরকম কিছু 
<a href="https://i.ibb.co/qWW8Xy7/JwOs6fj.png">Image</a>

**ধাপ-৩:** এরপর আমরা সরাসরি ক্লিক করবো "Docs" এ । ক্লিক করার পর আমরা "Docs page" এর ওখানে দেখতে পাবো "Java" নামক একটি সেকশন । আমরা ওখানে ক্লিক করবো । 
<a href="https://i.ibb.co/HN5nfzP/ETf-FEe4f-Dv.png">Image</a>

**ধাপ-৪:** এরপর আমরা যদি Java তে এরপর যদি "Getting Started"  এ ক্লিক করি তাইলে আমরা এরকম কিছু একটা পাবো 
<a href="https://i.ibb.co/4J962L1/firefox-fv6-Zj-Jg-UGy.png">Image</a>
এরপর আমরা ওখানে থাকা " Install the Coding Pack for Java - Windows" এখানে ক্লিক করে আমাাদের কাঙ্ক্ষিত ফাইল টা ডাউনলোড করে নিব । 

**ধাপ-৫:** এরপর আমরা আমাদের ইন্সটলার ফাইল টি ওপেন করে আমাদের দুইটাই ইন্সটল দিতে হবে । প্রথম এ থাকবে জাভা jdk  এরপরের টা vs code দুইটাতে ইন্সটল ক্লিক করে চুপ করে বসে থাকেন । ইন্সটল শেষ হলে vs code ওপেন করুন এবার একটা নতুন ফাইল বানাইতে আপনারে চাপতে হবে `ctrl + n` এরপর `ctrl + s`চেপে আপনার পছন্দের একটা জায়গায় নির্বাচন করে ফাইল এর নাম দেন `HelloWorld.java`। এই যে .java হচ্ছে আমাদের জাভা ফাইলের এক্সটেনশ । এরপর আমাদের একটা কোড আসার কথা কিছুটা এমন 

    public class HelloWorld{
    
    } 
এরপর এই ফাকা জায়গায় আমরা লিখবো 

    public class HelloWorld{
    	public static void main(String args[]){
    	
    	}
    }

আমরা যদি  এখানে দেখতে পাই `Run | Debug` তাহলে বুঝবো আমাদের সেটআপ  আমাদের জাভা কোড লেখার জন্য তৈরি হয়ে আছে । 

    Run | Debug
    public static void main(String args[]){
        	
    }


<br />

# প্রথম "Hello,World!" লেখা

যেহেতু আমাদের কোড লেখার জায়গা তৈরি হয়ে আছে । আমি আশা করবো আপনাদের ফাইল বানানো এবং সেভ এর মধ্যে কোন সমস্যা নাই । আমাদের বানানো ফাইল টি যদি আমরা vscode  দিয়ে ওপেন করি তাইলে দেখতে পাবো  এরকম কিছু

*HelloWorld.java >>* 

    public  class  HelloWorld {
    
    public  static  void  main(String[] args) {
    
    }
    
    }
এবার আমরা এই  ফাঁকা জায়গার মধ্যে লিখবো  `System.out.println("Hello,World!);`

    public  static  void  main(String[] args) {
    
    System.out.println("Hello,World!);
    
    }
তাহলে আমাদের কোড টা হবে এরকম কিছুটা 

    public  class  HelloWorld {
    
	    public  static  void  main(String[] args) {
    
			    System.out.println("Hello,World!");
			}
    
    }
এবার আমরা যদি Run | Debug  এর ওখানে Run ক্লিক করলে । vscode  এ টার্মিনাল  ওপেন হয়ে দেখাবে

>  Hello,World!

যেহেতু আমরা দেখতে পেয়েছি কিভাবে আমরা স্ক্রিন এ আমাদের কোড এর অউটপুট দেখতে পাচ্ছি  তাই আমরা এবার আমাদের নাম , বাবার নাম ,  মা'র নাম এবং আমরা বর্তমানে কোন শ্রেণিতে আছি তাই প্রিন্ট করতে হবে । 

    public  class  HelloWorld {
    
    public  static  void  main(String[] args) {
    
    System.out.println("My name is: Tousif Tasrik");
    
    System.out.println("My father's name: father's name");
    
    System.out.println("My mother's name: Mother's name");
    
    System.out.println("I am studying CSE at international University of Scholars");
    
      
    
    }
    
    }

> output :  
> My name is: Tousif Tasrik <br/>
> My father's name: father's name <br/>
> My mother's name: Mother's name <br />
> I am studying CSE at international University of Scholars <br />

