**Abstraction (အဘယ်ကြောင့် အရေးကြီးသလဲ)** Object-Oriented Programming (OOP) မှာ အဓိက အစိတ်အပိုင်းတစ်ခုက _Abstraction_ ဖြစ်ပါတယ်။ လူတွေဟာ အရာတွေကို တိကျစွာ အစိတ်အပိုင်းများအနည်းငယ်အနည်းငယ်နဲ့ မစဉ်းစားကြဘဲ အကျိုးရှိအောင် _အရာတစ်ခုလုံးကို အနက်ဖော်_ လုပ်ကြပါတယ်။

ဥပမာ—ကားကို စဉ်းစားတဲ့အခါ လူတွေဟာ engine, transmission, brake စတဲ့ အစိတ်အပိုင်းသောင်းချီကို တစ်ခုချင်းစီနဲ့ မစဉ်းစားကြဘဲ “ကား” ဆိုတဲ့ အရာတစ်ခုလုံးအနေနဲ့ သုံးကြပါတယ်။ ဒီလို _abstraction_ ကြောင့် ကားကို စက်ပစ္စည်းအများကြီးနဲ့ မအလွှမ်းမိုးဘဲ သုံးနိုင်တာဖြစ်ပါတယ်။

**Hierarchical Abstraction (အဆင့်လိုက် အနက်ဖော်မှု)** အရာတွေကို အဆင့်လိုက် ခွဲခြားဖို့ _hierarchical classification_ ကို သုံးနိုင်ပါတယ်။

- ကားကို အပြင်ဘက်က ကြည့်ရင် “ကား” တစ်လုံးပဲ ဖြစ်ပါတယ်။
    
- အတွင်းကို ဝင်ကြည့်ရင် steering, brakes, sound system, seat belts စတဲ့ subsystems တွေရှိပါတယ်။
    
- Sound system ကိုပဲ ထပ်ခွဲကြည့်ရင် radio, CD player, MP3 player စတဲ့ အစိတ်အပိုင်းတွေ ထပ်ထွက်လာပါတယ်။
    

ဒီလို အဆင့်လိုက် abstraction ကြောင့် စုံလင်တဲ့ စနစ်ကြီးကို အပိုင်းပိုင်း ခွဲပြီး နားလည်နိုင်ပါတယ်။

**Programming မှာ အသုံးချပုံ** Traditional process-oriented program (လုပ်ငန်းစဉ်အခြေခံ) ကို abstraction နဲ့ object-oriented program အဖြစ် ပြောင်းနိုင်ပါတယ်။

- လုပ်ငန်းစဉ်အဆင့်တွေကို object တွေကြား message ပေးပို့ခြင်းအဖြစ် ပြောင်းနိုင်ပါတယ်။
    
- Object တစ်ခုချင်းစီမှာ သူ့ကိုယ်ပိုင် behavior (အပြုအမူ) ရှိပါတယ်။
    
- Program ကို object တွေကို သီးခြား entity အဖြစ် သုံးပြီး message ပေးလိုက်ရင် တုံ့ပြန်စေပါတယ်။
    

ဒါဟာ OOP ရဲ့ အဓိက အချက်ပါ။

**Java နဲ့ Object-Oriented Concept** Java ရဲ့ အခြေခံမှာ OOP concept တွေပါဝင်ပါတယ်။ ဒီ concept တွေကို နားလည်ထားရင် software project တစ်ခုရဲ့ conception (စတင်), growth (တိုးတက်), aging (အဟောင်း) အဆင့်တွေမှာ အဆင်ပြေစွာ အသုံးချနိုင်ပါတယ်။

- Object တွေကို သေချာ define လုပ်ထားပြီး interface တွေကို သန့်ရှင်းစွာ တည်ဆောက်ထားရင် အဟောင်းစနစ်ထဲက အစိတ်အပိုင်းတွေကို အလွယ်တကူ ပြန်လဲနိုင်ပါတယ်။
    
- ဒီလိုနဲ့ OOP က အဆင့်မြင့်၊ သဘာဝကျတဲ့ programming paradigm ဖြစ်ပါတယ်။
    

👉 အကျဉ်းချုပ်—**Abstraction** ဆိုတာ အရာတစ်ခုလုံးကို အနက်ဖော်ပြီး အစိတ်အပိုင်းတွေကို မစဉ်းစားဘဲ အသုံးချနိုင်တဲ့ နည်းလမ်းဖြစ်ပြီး၊ OOP မှာ အရေးကြီးဆုံး အစိတ်အပိုင်းတစ်ခုပါ။

အမှန်တကယ် အသုံးချတဲ့ ဥပမာ တစ်ခုကို ပြောမယ်—

### Banking App (ဘဏ်အက်ပ်)  
ဘဏ်အက်ပ်တစ်ခုကို သုံးတဲ့အခါ သင်ဟာ abstraction ကို အလွန်ကြီးမားစွာ သုံးနေပါတယ်။

- **User Side (အသုံးပြုသူဘက်)**  
သင်ဟာ “ငွေထည့်မယ်”, “ငွေထုတ်မယ်”, “ငွေလွှဲမယ်” ဆိုတဲ့ function တွေကိုသာ တွေ့ရပါတယ်။

Engine, database, encryption, server connection စတဲ့ အစိတ်အပိုင်းတွေကို သင်မစဉ်းစားပါဘူး။

- **System Side (စနစ်အတွင်းဘက်)**  
ငွေလွှဲ function တစ်ခုထဲမှာပဲ အများကြီး subsystem တွေရှိပါတယ်—

  - Authentication (password, OTP စစ်ဆေး)

  - Transaction processing (ငွေထည့်/ထုတ် စစ်ဆေး)

  - Notification system (SMS, email ပို့)

  - Database update (account balance ပြောင်း)

ဒီလိုနဲ့ သုံးသူအနေနဲ့ သင်ဟာ “ငွေလွှဲ” ဆိုတဲ့ object တစ်ခုကိုသာ သုံးပြီး အတွင်းက အစိတ်အပိုင်းတွေကို မစဉ်းစားဘဲ အဆင်ပြေစွာ အသုံးချနိုင်ပါတယ်။

👉 ဒီလိုနဲ့ abstraction က လူတွေကို အစိတ်အပိုင်းတွေကို မစဉ်းစားဘဲ အရာတစ်ခုလုံးကို သုံးနိုင်စေပြီး၊ programmer တွေကိုလည်း အဆင့်လိုက် ခွဲခြားပြီး စနစ်ကြီးကို အလွယ်တကူ တည်ဆောက်နိုင်စေပါတယ်။


### Facebook Example (အနက်ဖော်မှု)  
Facebook ကို သုံးတဲ့အခါ သင်ဟာ အစိတ်အပိုင်းတွေကို မစဉ်းစားဘဲ “App တစ်ခုလုံး” အနေနဲ့ သုံးနေပါတယ်။

- **User Side (အသုံးပြုသူဘက်)**  

သင်ဟာ “Post တင်မယ်”, “Like နှိပ်မယ်”, “Comment ပေးမယ်”, “Message ပို့မယ်” ဆိုတဲ့ function တွေကိုသာ တွေ့ရပါတယ်။
Server architecture, database storage, AI algorithm, security encryption စတဲ့ အစိတ်အပိုင်းတွေကို သင်မစဉ်းစားပါဘူး။


- **System Side (စနစ်အတွင်းဘက်)**  

“Post တင်ခြင်း” ဆိုတဲ့ action တစ်ခုထဲမှာပဲ အများကြီး subsystem တွေရှိပါတယ်—

  - Authentication (သင့် account ကို စစ်ဆေး)

  - Content storage (post ကို database ထဲသိမ်း)

  - News Feed algorithm (ဘယ်သူတွေကို ပြမလဲ ဆုံးဖြတ်)

  - Notification system (မိတ်ဆွေတွေကို အသိပေး)

  - Security system (spam, fake account စစ်ဆေး)

ဒီလိုနဲ့ သုံးသူအနေနဲ့ သင်ဟာ “Post တင်ခြင်း” ဆိုတဲ့ object တစ်ခုကိုသာ သုံးပြီး အတွင်းက အစိတ်အပိုင်းတွေကို မစဉ်းစားဘဲ အဆင်ပြေစွာ အသုံးချနိုင်ပါတယ်။

👉 အကျဉ်းချုပ်—Facebook ကို သုံးတဲ့အခါ သင်ဟာ abstraction ကို အပြည့်အဝ သုံးနေပြီး၊ programmer တွေကတော့ အဆင့်လိုက် abstraction နဲ့ subsystems တွေ ခွဲပြီး တည်ဆောက်ထားတာကြောင့် စနစ်ကြီးကို အဆင်ပြေစွာ ထိန်းချုပ်နိုင်ပါတယ်။


Java ကို အသုံးပြုပြီး abstraction ကို ပြသတဲ့ အမှန်တကယ် code ဥပမာ တစ်ခုကို ပြပေးမယ်။

```java
// Abstraction Example in Java

// Abstract class
abstract class Messenger {
    // abstract method (no body)
    public abstract void sendMessage(String message);

    // normal method
    public void connect() {
        System.out.println("Connecting to server...");
    }
}

// Concrete class 1
class FacebookMessenger extends Messenger {
    @Override
    public void sendMessage(String message) {
        System.out.println("Sending via Facebook Messenger: " + message);
    }
}

// Concrete class 2
class WhatsAppMessenger extends Messenger {
    @Override
    public void sendMessage(String message) {
        System.out.println("Sending via WhatsApp: " + message);
    }
}

// Main class
public class AbstractionDemo {
    public static void main(String[] args) {
        // Using abstraction: we don't care HOW it sends, just that it sends
        Messenger messenger1 = new FacebookMessenger();
        messenger1.connect();
        messenger1.sendMessage("Hello from Facebook!");

        Messenger messenger2 = new WhatsAppMessenger();
        messenger2.connect();
        messenger2.sendMessage("Hello from WhatsApp!");
    }
}

```
