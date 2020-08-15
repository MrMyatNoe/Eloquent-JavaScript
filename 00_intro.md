{{meta {load_files: ["code/intro.js"]}}}

# နိဒါန်း

# Introduction

{{quote {author: "Ellen Ullman", title: "Close to the Machine: Technophilia and its Discontents", chapter: true}

ကျွန်ုပ်တို့ဟာ ကွန်ပျူတာနည်းစနစ်တွေကို ကျွန်ုပ်တို့ရဲ့ ကိုယ်ပိုင်အမြင်တွေနဲ့ ဖန်တီးကြတယ်။ ထိုနည်းစနစ်တွေကို ကျွန်ုပ်တို့ ကိုယ်ပိုင်နည်းလမ်းဖြင့် ဖန်တီးထားတယ်လို့ ယုံကြည်ကြတယ်။... ဒါပေမဲ့ ကွန်ပျူတာတွေဟာ ကျွန်ုပ်တို့နဲ့ မတူညီကြဘူး။ သူတို့တွေဟာ ကျွန်ုပ်တို့ရဲ့ တစ်စိတ်တစ်ပိုင်း အဖြစ်သာ အရိပ်ပြန်ထင်ဟပ်မှုတွေသာဖြစ်တယ်။  ထိုအစိတ်အပိုင်းလေးတွေဟာ logic(ယုတ္တိဗေဒ)၊ order(အမိန့်)၊ rule(စည်းမျဉ်းစည်းကမ်း) နှင့် clarity(ရှင်းလင်းပြတ်သားမှု) ဆိုတဲ့ အချက်တွေကို လိုက်နာကြတယ်။

We think we are creating the system for our own purposes. We believe we are making it in our own image... But the computer is not really like us. It is a projection of a very slim part of ourselves: that portion devoted to logic, order, rule, and clarity.

quote}}

{{figure {url: "img/chapter_picture_00.jpg", alt: "Picture of a screwdriver and a circuit board", chapter: "framed"}}}

ဤစာအုပ်မှာ ကွန်ပျူတာတွေကိုဘယ်လို ညွှန်ကြားအသုံးချရမလဲဆိုတဲ့ အကြောင်းတွေပါမှာပါ။ ကွန်ပျူတာတွေဟာ အခုခေတ်အခါမှာ ဝက်အူလှည့်တွေပေါများသလို ပေါများနေပါပြီ၊ ဒါပေမဲ့ သူတို့တွေဟာ ပိုပြီးတော့ ရှုပ်ထွေးကြပါတယ်။ ထို့နောက် ကွန်ပျူတာတွေကို ကိုယ်လိုသလို ခိုင်းနိုင်ဖို့အတွက်ဆိုရင် အမြဲထင်သလောက် မလွယ်ကူလှပါဘူး။

This is a book about instructing ((computer))s. Computers are about as common as screwdrivers today, but they are quite a bit more complex, and making them do what you want them to do isn't always easy.

အကယ်၍ သင်က ကွန်ပျူတာကိုခိုင်းစေချင်တဲ့ အလုပ်က ပုံမှန်လုပ်နေကြအလုပ်မျိုး၊ တိတိကျကျခိုင်းနိုင်တဲ့အလုပ်မျိုး ဖြစ်တဲ့ အီးမေးလ်များစစ်ခြင်း၊ ကိန်းဂဏန်းများတွက်ချက်ခြင်း သာဖြစ်ခဲ့ရင် သက်ဆိုင်တဲ့ Application ကိုဖွင့်၍ လုပ်ဆောင်နိုင်ပါတယ်။ သို့ပေမဲ့ မတူညီတဲ့၊ ရလဒ်မသေချာတဲ့ အလုပ်များအတွက်တော့ ကြိုရေးထားတဲ့ Applicationများ မရှိတာများပါတယ်။

If the task you have for your computer is a common, well-understood one, such as showing you your email or acting like a calculator, you can open the appropriate ((application)) and get to work. But for unique or open-ended tasks, there probably is no application.

ထို့အတွက် programming ဆိုတာရှိနေခြင်းဖြစ်ပါတယ်။ *Programming* ဆိုတာ ကွန်ပျူတာကို တိကျတဲ့ လမ်းညွှန်ချက်တွေပေးပြီး ခိုင်းစေတဲ့နည်းတစ်ခုဖြစ်ပါတယ်။ ကွန်ပျူတာတွေဟာ အကုန်အသေးစိတ်လိုက်ခိုင်းနေရတဲ့ နုံအတဲ့ သတ္တဝါလေးလိုပါပဲ။ အဲ့ဒါကြောင့် programming ဟာ ငြီးငွေ့ပြီးတော့ စိတ်ရှုပ်ဖို့ကောင်းလှပါတယ်။

That is where ((programming)) may come in. *Programming* is the act of constructing a *program*—a set of precise instructions telling a computer what to do. Because computers are dumb, pedantic beasts, programming is fundamentally tedious and frustrating.

{{index [programming, "joy of"], speed}}

အကယ်၍ သင်သာထိုအချက်တွေကို ကျော်လွှားနိုင်ပြီးတော့ နုံအတဲ့စက်တွေ တွေးသလို လိုက်ပြီးတွေးခေါ်ရတာကို နှစ်ခြိုက်နိုင်ရင် programming ဆိုတာ သင့်အတွက်တော့ ဆုလာဘ်တစ်ခု ဖြစ်လာပါလိမ့်မယ်။ သင်ဟာ လက်နဲ့မပြီးတော့လောက်အောင် အကြာကြီးလုပ်နေရတဲ့အလုပ်တွေကို စက္ကန့်ပိုင်းအတွင်းမှာပြီးမြောက်အောင် လုပ်နိုင်လာပါလိမ့်မယ်။ သင်ဟာ ကွန်ပျူတာကို အရင်ကလုပ်လို့မရဘူးလို့ထင်ရတာတွေကို လုပ်နိုင်အောင် ခိုင်းတတ်လာပါလိမ့်မယ်။ ဤအရာဟာ သင့်အတွက် ခွဲခြမ်းစိပ်ဖြာပြီး တွေးခေါ်နိုင်စွမ်းတွေပေးမှာပါ။

Fortunately, if you can get over that fact, and maybe even enjoy the rigor
of thinking in terms that dumb machines can deal with, programming can
be rewarding. It allows you to do things in seconds that would take
_forever_ by hand. It is a way to make your computer tool
do things that it couldn't do before. And it provides a wonderful
exercise in abstract thinking.

Programming အများစုဟာ programming languages(ဘာသာစကားမျိုးစုံ)ဖြင့် လုပ်ဆောင်နိုင်ပါတယ်။ Programming language တစ်ခုဟာ ကွန်ပျူတာတွေကို ခိုင်းစေဖို့အတွက် ပြုလုပ်ဖန်တီးထားခြင်းဖြစ်ပါတယ်။ ကွန်ပျူတာတွေနဲ့ ချိတ်ဆက်ဖို့ အဆင်ပြေဆုံးနည်းလမ်းဟာ ကျွန်ုပ်တို့ လူတွေအချင်းချင်း ဆက်သွယ်တဲ့နည်းနဲ့ အတော်များများ တူညီနေတာဟာ စိတ်ဝင်စားစရာလေးပါ။ လူတွေပြောဆိုအသုံးပြုတဲ့ ဘာသာစကားတွေလိုပါပဲ Computer Languages (ကွန်ပျူတာ ဘာသာစကား)တွေမှာ words(စကားလုံးတွေ)၊ phrases(စာပိုဒ်တွေ) ကို တစ်မျိုးတစ်ဖုံဖွဲ့စည်းထားပြီးတော့ သဘောတရားအသစ်တွေ တွေးခေါ်နည်းအသစ်တွေ ဖြစ်ပေါ်လာစေပါတယ်။

Most programming is done with ((programming language))s. A _programming
language_ is an artificially constructed language used to instruct
computers. It is interesting that the most effective way we've found
to communicate with a computer borrows so heavily from the way we
communicate with each other. Like human languages, computer languages
allow words and phrases to be combined in new ways, making it possible to
express ever new concepts.

{{index [JavaScript, "availability of"], "casual computing"}}

အရင် ၁၉၈၀ - ၁၉၉၀ ကာလတွေမှာ Language-based Interfaces(စာသားအခြေခံသုံး စနစ်) ဖြစ်တဲ့ BASIC နဲ့ DOS တို့က ကွန်ပျူတာတွေကို ခိုင်းစေဖို့သုံးတဲ့ အဓိက နည်းလမ်းတွေဖြစ်ခဲ့ကြတယ်။ နောက်ပိုင်းမှာ သူတို့ကို visual interfaces(ရုပ်ပုံအခြေခံသုံး စနစ်) တွေနဲ့ ပြောင်းသုံးလာကြတယ်။ သုံးရတာပိုလွယ်လာပေမဲ့ ကွန်ပျူတာတွေကို အပြည့်အဝထိန်းချုပ်ပိုင်ခွင့် နည်းပါးလာတယ်။ ကွန်ပျူတာဘာသာစကား တွေကရှိနေတုန်းပါပဲ၊ ဘယ်မှာရှာရမလဲဆိုတာကို သိဖို့ပဲလိုတာပါ။ အဲ့လို့ ဘာသာစကားတွေထဲက တစ်ခုဖြစ်တဲ့ Javascript ကတော့ အခုကာလ Web Browser တွေမှာအသုံးပြုဖို့ ဖန်တီးထားပါတယ်။ Web Browser တွေအတွက် ဖန်တီးထားတာကြောင့် စက်တိုင်းနီးပါးမှာ တွေ့နိုင်ပါတယ်။

At one point language-based interfaces, such as the BASIC and DOS
prompts of the 1980s and 1990s, were the main method of interacting with
computers. They have largely been replaced with visual interfaces,
which are easier to learn but offer less freedom. Computer languages
are still there, if you know where to look. One such language,
JavaScript, is built into every modern web ((browser)) and is thus
available on almost every device.

{{indexsee "web browser", browser}}

ဤစာအုပ်မှာ သင့်ကို Javascript နှင့် အသုံးဝင်တာတွေ၊ စိတ်ဝင်စားစရာကောင်းတာတွေလုပ်တဲ့ထိ ရင်းနှီးသွားအောင် လမ်းပြပေးသွားပါမယ်။

This book will try to make you familiar enough with this language to
do useful and amusing things with it.

## Programming အကြောင်း

## On programming

{{index [programming, "difficulty of"]}}

Javascript ကို မရှင်းပြခင်မှာ Programming အကြောင်းအခြေခံ အရင်ရှင်းပြပါမယ်။ Programming ဟာ တကယ်တော့ခက်ခဲပါတယ်။ အခြေခံစည်းမျဉ်းတွေက လွယ်ကူပေမဲ့ ဒီအခြေခံ စည်းမျဉ်းတွေပေါ် မူတည်ပြီး ဖန်တီးထားတဲ့ program တွေ တောင် အချိန်နဲ့အမျှ ရှုပ်ထွေးလာတတ်ပြီးတော့ ကိုယ်ပိုင်စည်းမျဉ်းစည်းကမ်းတွေ ထပ်ဖြစ်ပေါ်လာတတ်ပါတယ်။ တစ်နည်းအားဖြင့် သင်ဟာ သင့်ရဲ့ကိုယ်ပိုင် ဝင်္ကပါကို ဖန်တီးနေတာပါ။ ထိုဝင်္ကပါထဲမှာ သင်ကိုယ်တိုင်ပြန်ပြီးတော့ လမ်းပျောက်နိုင်ပါတယ်။

Besides explaining JavaScript, I will introduce the basic
principles of programming. Programming, it turns out, is hard. The
fundamental rules are simple and clear, but programs built on top of
these rules tend to become complex enough to introduce their own rules
and complexity. You're building your own maze, in a way, and you might
just get lost in it.

{{index learning}}

ဤစာအုပ်ကိုဖတ်ရင်းနဲ့ စိတ်ညစ်လာတဲ့အချိန်တွေလည်းရှိလာနိုင်ပါတယ်။ အကယ်၍ သင်ဟာ programming ကို ပထမဆုံးအကြိမ်လေ့လာတာဆိုရင်တော့ လေ့လာစရာတွေအရမ်းများနေပါလိမ့်မယ်။ သင်ဒီမှာလေ့လာခဲ့တာတွေ တော်တော်များများက နောက်ထပ်သင့်ကိုလမ်းသစ်တွေ ရှာတွေ့အောင်ကူညီပေးပါလိမ့်မယ်။

There will be times when reading this book feels terribly frustrating.
If you are new to programming, there will be a lot of new material to
digest. Much of this material will then be _combined_ in ways that
require you to make additional connections.

လိုအပ်တဲ့ လုပ်အားကိုစိုက်ထုတ်ရမှာကတော့ သင်ကိုယ်တိုင်ရဲ့ တာဝန်သာဖြစ်ပါတယ်။ စာအုပ်ကိုဖတ်မှတ်ရင်းနဲ့ အခက်အခဲတစ်ခုခုနှင့် ကြုံတွေ့ခဲ့ရင် ကိုယ့်ဘာသာကိုယ် ထင်သလို ကောက်ချက်မချလိုက်ပါနဲ့။ အခက်အခဲကြုံတွေ့တာဟာ ပြဿနာမဟုတ်ပါဘူး အဲ့အတိုင်းပဲခဏထားထားလိုက်ပါ။ ခဏအနားယူလိုက်ပါ။ ပြီးရင် ပြန်ဖတ်ကြည့်ပါ။ နမူနာရေးနည်းတွေ၊ လေ့ကျင့်ခန်းတွေကို သေချာနားလည်လားဆိုတာကို ပြန်လည်စမ်းစစ်ကြည့်ပါ။ တစ်ခုခုကိုလေ့လာရတာဟာ အမြဲခက်ခဲပါတယ် ဒါပေမဲ့ သင်လေ့လာတာတွေအကုန်လုံးက သင့်ရဲ့ကိုယ်ပိုင်တွေကြီးပါပဲ။ အဲ့ဒါတွေက သင်နောက်ထပ်လေ့လာတာတွေကို ပိုမိုလွယ်ကူစေပါလိမ့်မယ်။

It is up to you to make the necessary effort. When you are struggling
to follow the book, do not jump to any conclusions about your own
capabilities. You are fine—you just need to keep at it. Take a break,
reread some material, and make sure you read and understand the
example programs and ((exercises)). Learning is hard work, but
everything you learn is yours and will make subsequent learning
easier.

{{quote {author: "Ursula K. Le Guin", title: "The Left Hand of Darkness"}

{{index "Le Guin, Ursula K."}}

သင့်လုပ်ရပ်တွေက အကျိုးမရှိဘူးဆိုရင် သတင်းအချက်လက်တွေကိုစုဆောင်းပါ၊ စုဆောင်းထားတဲ့ သတင်းအချက်လက်တွေက အကြိုးမရှိဘူးဆိုရင်တော့ အိပ်လိုက်ပါ။

When action grows unprofitable, gather information; when information
grows unprofitable, sleep.

quote}}

{{index [program, "nature of"], data}}

Program တစ်ခုဆိုတာဟာ အမျာကြီးဖြစ်နိုင်ပါတယ်။ အဲ့ဒါဟာ Programmer တစ်ယောက် ရေးထားတဲ့ စာတစ်စုဖြစ်နိုင်ပါတယ်။ အဲ့ဒါဟာ ကွန်ပျူတာတစ်ခုကို ပုံမှန်အတိုင်းအလုပ်လုပ်နေအောင် ထိန်းချုပ်ပေးနေတဲ့ program တစ်ခုလည်းဖြစ်နေနိုင်ပါတယ်။ အဲ့ဒါဟာ ကွန်ပျူတာရဲ့ မှတ်ဉာဏ်ထဲက အချက်အလက်လေးတစ်ခုလည်းဖြစ်နေနိုင်ပါတယ်။ အဲ့လိုပဲ ကွန်ပျူတာ မှတ်ဉာဏ်ကို ထိန်းချုပ်ပေးနေတဲ့ program တစ်ခုလည်းဖြစ်နေနိုင်ပါတယ်။ ကျွန်ုပ်တို့ သိပြီးသားအရာတွေနဲ့ Program တစ်ခုကိုနှိုင်းယှဉ်ဖို့ဆိုတာမဖြစ်နိုင်ပါဘူး။ အပေါ်ယံတူညီတာကို ပြပါဆိုရင်တော့ စက်တစ်ခုနဲ့ နှိုင်းယှဉ်ကောင်နှိုင်းယှဉ်နိုင်ပါလိမ့်မယ်။ စက်တစ်ခုမှာ မတူညီတဲ့ အစိတ်အပိုင်းလေးတွေ များစွာက စက်တစ်ခုလုံးအလုပ်လုပ်နိုင်အောင်ဆောင်ရွက်ပေးပါတယ်။ ထိုအစိတ်အပိုင်းလေးတွေက တစ်ခုနှင့်တစ်ခု ချိတ်ဆက်ပြီးတော့ စက်ရဲ့ လုပ်ငန်းဆောင်တာကို လုပ်ဆောင်ပေးပါတယ်။

A program is many things. It is a piece of text typed by a programmer,
it is the directing force that makes the computer do what it does, it
is data in the computer's memory, yet it controls the actions
performed on this same memory. Analogies that try to compare programs
to objects we are familiar with tend to fall short. A superficially
fitting one is that of a machine—lots of separate parts tend to be
involved, and to make the whole thing tick, we have to consider the
ways in which these parts interconnect and contribute to the operation
of the whole.

ကွန်ပျူတာဆိုတာ ဒီတိုင်းအသုံးပြုလို့မရတဲ့ အစိတ်အပိုင်းလေးတွေထည့်ထားသော စက်ကိရိယာတစ်ခုသာဖြစ်ပါတယ်။ ကွန်ပျူတာချည်းပဲ သပ်သပ်ဆိုရင် အရမ်းလွယ်ကူတဲ့ လူတိုင်းလုပ်နိုင်တဲ့ လုပ်ဆောင်ချက်တွေကိုသာ လုပ်ဆောင်ပေးပါလိမ့်မယ်။ ကွန်ပျူတာတွေ အသုံးဝင်နေရတဲ့ အကြောင်းရင်းကတော့ ထိုလုပ်ဆောင်ချက်တွေကို အရမ်းမြန်ဆန်တဲ့ နှုန်းနှင့်လုပ်ဆောင်ပေးနိုင်ခြင်းပဲဖြစ်ပါတယ်။ Program တစ်ခုဟာ အလွန်များပြားတဲ့ လွယ်ကူသောလုပ်ငန်းလေးတွေကို တစ်ပြိုင်ထဲလုပ်ဆောင်ပြီးတော့ ရှုပ်ထွေးသော လုပ်ငန်းဆောင်တာများကို လုပ်ဆောင်ပေးနိုင်ပါတယ်။

A ((computer)) is a physical machine that acts as a host for these immaterial
machines. Computers themselves can do only stupidly straightforward
things. The reason they are so useful is that they do these things at
an incredibly high ((speed)). A program can ingeniously combine an
enormous number of these simple actions to do very
complicated things.

{{index [programming, "joy of"]}}

Program တစ်ခုဟာ အတွေးအခေါ်တွေ ပေါင်းစပ်၊ဖွဲ့စည်းထားတာပဲဖြစ်ပါတယ်။ Program တစ်ခုဟာ ကုန်ကျစရိတ်မရှိပါဘူး၊ အလေးချိန်လည်းမရှိပါဘူး၊ ကျွန်ုပ်တို့ရဲ့ စာရိုက်နေတဲ့ လက်ထဲမှာတင်ပဲ လွယ်လွယ်ကူကူ ကြီးထွားလာနိုင်ပါတယ်။

A program is a building of thought. It is costless to build, it is
weightless, and it grows easily under our typing hands.

သို့ပေမဲ့ သေချာထိန်းသိမ်းမှုမရှိခဲ့ရင်တော့ program တစ်ခုရဲ့ ပမာဏနဲ့ ရှုပ်ထွေးမှုဟာ ပိုမိုကြီးထွားလာပြီးတော့ ထိန်းချုပ်ရတာ ခက်ခဲလာပါလိမ့်မယ်။ သူ့ကို ဖန်တီးတီထွင်ခဲ့သူကိုတောင် ရှုပ်ထွေးစေပါလိမ့်မယ်။ Program တွေအများကြီးကို မရှုပ်ထွေးသွားအောင် ထိန်းသိမ်းရတာဟာ programming ရဲ့ အဓိက ပြဿနာပဲဖြစ်ပါတယ်။ Program တစ်ခုအလုပ်လုပ်ရင် အဲ့ဒါဟာ လှပသောအရာတစ်ခုပါ။ Programming အနုပညာဆိုတာ ရှုပ်ထွေးမှုကို ထိန်းချုပ်နိုင်စွမ်းဖြစ်ပါတယ်။ Program ကောင်းတစ်ခုမှာ ရှုပ်ထွေးမှုကို ရိုးရှင်းအောင်ပြုလုပ်ထားပါတယ်။

But without care, a program's size and ((complexity)) will grow out of
control, confusing even the person who created it. Keeping programs
under control is the main problem of programming. When a program
works, it is beautiful. The art of programming is the skill of
controlling complexity. The great program is subdued—made simple in
its complexity.

{{index "programming style", "best practices"}}

ရှုပ်ထွေးမှုကို သေးငယ်ပြီးတော့ နားလည်ရလွယ်တဲ့ လုပ်ထုံးလုပ်နည်းတွေနဲ့ ထိန်းသိမ်းနိုင်တယ်လို့ တချို့ programmer တွေကယုံကြည်ကြပါတယ်။ သူတို့တွေက တင်းကြပ်တဲ့ program တစ်ခုအတွက် အကောင်းဆုံးဖြစ်နိုင်သော စည်းမျဉ်းစည်းကမ်းတွေ("best practices")ကို သတ်မှတ်ကြကာ ထိုစည်းမျဉ်းစည်းကမ်းများကိုသာ လိုက်နာပြီးတော့ လုပ်ဆောင်ကြပါတယ်။

Some programmers believe that this complexity is best managed by using
only a small set of well-understood techniques in their programs. They
have composed strict rules ("best practices") prescribing the form
programs should have and carefully stay within their safe little
zone.

{{index experiment}}

ထိုအရာဟာ ပျင်းရိဖို့ကောင်းရုံသာမက ထိရောက်မှုလည်းမရှိပါဘူး။ ပြဿနာအသစ်တွေမှာ ဖြေရှင်းချက်အသစ်တွေလိုအပ်နိုင်ပါတယ်။ Programming နယ်ပယ်ဟာ သက်တမ်းနုနယ်ပြီးတော့ အလျင်အမြန် တိုးတက်နေဆဲဖြစ်ပါတယ်။ တူညီတဲ့ ရလဒ်တွေကိုလည်း မတူညီတဲ့ဖြေရှင်းနည်းတွေနဲ့ ဖြေရှင်းနိုင်ပါတယ်။ Programming မှာ အလွန်ဆိုးရွားလှတဲ့ အမှားတွေရှိပါတယ်။ သင်ဟာ ထိုအမှားတွေကို စမ်းလုပ်ကြည့်ပြီးတော့ နားလည်အောင်လုပ်ထားသင့်ပါတယ်။ Program ကောင်းတစ်ခုဆိုတာဟာ ထပ်ခါထပ်ခါလေ့ကျင့်ပြီးတော့ ရလာတဲ့ရလဒ်ပါ၊ စည်းမျဉ်းစည်းကမ်းတွေကနေ သင်ယူရတာမျိုးလုံးဝမဟုတ်ပါဘူး။

This is not only boring, it is ineffective. New problems often
require new solutions. The field of programming is young and still
developing rapidly, and it is varied enough to have room for wildly
different approaches. There are many terrible mistakes to make in
program design, and you should go ahead and make them so that you
understand them. A sense of what a good program looks like is
developed in practice, not learned from a list of rules.

## ကွန်ပျူတာ ဘာသာစကား အရေးကြီးရသော အကြောင်းအရင်း

## Why language matters

{{index "programming language", "machine code", "binary data"}}

ကွန်ပျူတာတွေပေါ်ခါစမှာ programming တွေဆိုတာမရှိခဲ့ပါဘူး။ ထိုအချိန်က Programming ဆိုတာဒီလိုပုံစံတွေမျိုးပါ။

In the beginning, at the birth of computing, there were no programming
languages. Programs looked something like this:

```{lang:
00110001 00000000 00000000
00110001 00000001 00000001
00110011 00000001 00000010
01010001 00001011 00000010
00100010 00000010 00001000
01000011 00000001 00000000
01000001 00000001 00000001
00010000 00000010 00000000
01100010 00000000 00000000
```

{{index [programming, "history of"], "punch card", complexity}}

အထက်မှာပြထားတဲ့ ကိန်းဂဏန်းတွေဟာ ၁ ကနေ ၁၀ ထိ ပေါင်းတဲ့ ရလဒ် `၁ + ၂ + ... + ၁၀ = ၅၅` ကိုရှာတဲ့ program ပါ။ ထို program ကို တွေ့ရာစက်တိုင်းမှာ အသုံးပြုနိုင်ပါတယ်။ ထိုခေတ်အခါက ကွန်ပျူတာတွေကို program ရေးတော့မယ်ဆိုရင် ကြီးမားရှည်လျားတဲ့ ခလုပ်တွေကို မှန်ကန်တဲ့ နေရာမှာလိုက်ထားပြီးတော့ သို့မဟုတ် လျှပ်စစ်ဘုတ်ပြားတွေကို သတ်ဆိုင်ရာနေရာတွေမှာ အပေါက်တွေဖောက်ပြီးတော့ ကွန်ပျူတာတဲ့ ထည့်ပြီးအသုံးပြုရပါတယ်။ ဤနည်းလမ်းဟာ အလွန် လက်ပေါက်ကပ်ပြီးတော့ အမှားများနိုင်တာကို သင်တွေးကြည့်ရုံနဲ့သိနိုင်ပါတယ်။ အလွန်လွယ်ကူတဲ့ program တစ်ခုကိုတောင်မှ တော်တော်ကျွမ်းကျင်ပြီး အကြိမ်ကြိမ်လုပ်ဖူးနေမှ ရေးနိုင်ပါလိမ့်မယ်။ ရှုပ်ထွေးတဲ့ program တွေသာဆိုရင်တော့ မတွေးဝံ့စရာပါပဲ။

That is a program to add the numbers from 1 to 10 together and print
out the result: `1 + 2 + ... + 10 = 55`. It could run on a simple,
hypothetical machine. To program early computers, it was necessary to
set large arrays of switches in the right position or punch holes in
strips of cardboard and feed them to the computer. You can probably
imagine how tedious and error-prone this procedure was. Even writing
simple programs required much cleverness and discipline. Complex ones
were nearly inconceivable.

{{index bit, "wizard (mighty)"}}

သို့ပေမဲ့လည်း ဒီလိုမျိုး ကိုယ်တိုင် ၁ နဲ့ ၀ တွေ လိုက်ထည့်နေရတာဟာ programmer တွေအတွက်တော့ မှော်ဆရာတစ်ယောက်လို တချို့သောအမြင်တွေပွင့်လန်းစေပါတယ်။ ထို့နောက် အဲ့လိုလုပ်ရကျိုးနပ်တဲ့ စိတ်ကျေနပ်မှုကိုလည်း ပြန်ရစေပါတယ်။

Of course, manually entering these arcane patterns of bits (the ones
and zeros) did give the programmer a profound sense of being a mighty
wizard. And that has to be worth something in terms of job
satisfaction.

{{index memory, instruction}}

ခုနက program မှာ ကွန်ပျူတာကို ညွှန်ကြားချက်တွေ တစ်ကြောင်းချင်းစီ ပါဝင်ပါတယ်။ ထိုညွှန်ကြားချက်တွေကို အင်္ဂလိပ်လို အောက်မှာပြထားတဲ့အတိုင်းပြန်ရေးနိုင်ပါတယ်။

Each line of the previous program contains a single instruction. It
could be written in English like this:

1. Store the number 0 in memory location 0.
2. Store the number 1 in memory location 1.
3. Store the value of memory location 1 in memory location 2.
4. Subtract the number 11 from the value in memory location 2.
5. If the value in memory location 2 is the number 0,
   continue with instruction 9.
6. Add the value of memory location 1 to memory location 0.
7. Add the number 1 to the value of memory location 1.
8. Continue with instruction 3.
9. Output the value of memory location 0.

{{index readability, naming, binding}}

အထက်မှာရေးခဲ့တာတွေဟာ bits(၀ နဲ့ ၁ တွေ) ထက်တော့ဖတ်ရတာ ပိုပြီးနားလည်လွယ်ပေမဲ့ နည်းနည်းရှုပ်ထွေးနေတုန်းပါပဲ။ မှတ်ဉာဏ်အခန်းနံပါတ်တွေ၊ ညွှန်ကြားချက်နံပါတ်တွေ သုံးမယ့်အစား နာမည်တွေသာ သုံးမယ်ဆိုရင် ပိုပြီးလွယ်ကူမှာပါ။

Although that is already more readable than the soup of bits, it is
still rather obscure. Using names instead of numbers for the
instructions and memory locations helps.

```{lang:
 Set “total” to 0.
 Set “count” to 1.
[loop]
 Set “compare” to “count”.
 Subtract 11 from “compare”.
 If “compare” is zero, continue at [end].
 Add “count” to “total”.
 Add 1 to “count”.
 Continue at [loop].
[end]
 Output “total”.
```

{{index loop, jump, "summing example"}}

အခုဆိုရင် program တွေအလုပ်လုပ်ပုံကို သင်သဘောပေါက်လာပြီလို့ထင်ပါတယ်။ ပထမ နှစ်ကြောင်းမှာ မှတ်ဉာဏ်အခန်း ၂ ခု ထဲကို ကိန်းဂဏန်းတွေ အစပျိုးအနေနဲ့ထည့်လိုက်ပါတယ်။ `total` ကို နောက်ဆုံးအဖြေထုတ်ဖို့အတွက်အသုံးပြုပြီးတော့ `count` ကိုတော့ လက်ရှိတွက်ချက်တဲ့ ကိန်းဂဏန်းတွေကို မှတ်ဖို့အသုံးပြုပါတယ်။ `compare` ကို အသုံးပြုတဲ့ တစ်ကြောင်းကတော့ နည်းနည်းကြောင်တောင်တောင်ဖြစ်နေမယ်ထင်ပါတယ်။ program က `count` ထဲရှိတဲ့နံပါတ်က ၁၁ လားဆိုတာကို စစ်ချင်တာပါ၊ အကယ်၍ ၁၁ သာဖြစ်ခဲ့ရင် program ကိုရပ်နိုင်အောင်လို့ပါ။ ဘာလို့ဒီလိုလုပ်ရလဲဆိုတော့ စက်တွေဟာ ငတုံးငအတွေပါ၊ သူတို့ဟာ ကိန်းဂဏန်းတစ်ခုကို ၀ ဖြစ်လားမဖြစ်လားပဲ စစ်ပြီးတော့ပဲ ဆုံးဖြတ်ချက်တွေချနိုင်ပါတယ်။ ထို့ကြောင့် `compare` လို့နာမည်တပ်ထားတဲ့ မှတ်ဉာဏ်အခန်းကို သုံးပြီးတော့ `count - 11` ရဲ့ရလဒ်ကို တွက်ချက်ပါတယ်။ ထို့နောက် ထွက်လာတဲ့ရလဒ်ပေါ်မူတည်ပြီး ဆုံးဖြတ်ချက်ချရပါတယ်။ နောက်ထပ်နှစ်ကြောင်းမှာကတော့ `count` မှာရှိတဲ့ ဂဏန်းကို `total` ထဲကိုပေါင်းထည့်ပြီးတော့ program က `count` ထဲကကိန်းဂဏန်း ၁၁ မရောက်သေးသ၍ `count` ကို ၁ ထပ်တိုးပါတယ်။

အဲ့ဒါကို Javascript မှာ အောက်ပါအတိုင်းရေးနိုင်ပါတယ်။

Can you see how the program works at this point? The first two lines
give two memory locations their starting values: `total` will be used
to build up the result of the computation, and `count` will keep track
of the number that we are currently looking at. The lines using
`compare` are probably the weirdest ones. The program wants to see
whether `count` is equal to 11 to decide whether it can stop
running. Because our hypothetical machine is rather primitive, it can
only test whether a number is zero and make a decision based
on that. So it uses the memory location labeled `compare` to compute
the value of `count - 11` and makes a decision based on that value.
The next two lines add the value of `count` to the result and
increment `count` by 1 every time the program has decided that `count`
is not 11 yet.

Here is the same program in JavaScript:

```
let total = 0, count = 1;
while (count <= 10) {
  total += count;
  count += 1;
}
console.log(total);
// → 55
```

{{index "while loop", loop, [braces, block]}}

ဒီတစ်ခါမှာတော့ ပိုပြီးတော့ တိုးတက်မှုတွေ တွေ့ရမှာပါ။ အရေးကြီးဆုံးက program ကို ဘယ်ကနေဘယ်ကိုသွားပါ ဆိုတာတွေ ညွှန်ကြားစရာမလိုတော့ဘူး။ `while` ဆိုတဲ့ အသုံးလေးက ထိုအရာကို လုပ်ဆောင်ပေးသွားတာပါ။ သူက စစ်ဆေးခိုင်းထားတဲ့ စည်းမျဉ်းနဲ့ကိုက်ညီနေသ၍ သူ့အထဲမှာရှိတဲ့ ညွှန်ကြားချက်(တွန့်ကွင်းနဲ့ဝိုက်ထားတာ) ကိုဆက်လုပ်နေမှာပါ။ ထိုစည်းမျဉ်းကတော့ `count <= 10` ဖြစ်ပါတယ်၊ ဆိုလိုတာကတော့ "*count* is less than or equal to 10" ဖြစ်ပါတယ်။ စိတ်ဝင်စားစရာမကောင်းတဲ့ ၀ ဖြစ်မဖြစ် စစ်ဆေးဖို့ကို ခေတ္တခဏ သိုလှောင်ဖို့အတွက် စီစဉ်စရာမလိုတော့ပါဘူး။ Programming ရဲ့အားသာချက်ကတော့ ထိုကဲ့သို့ စိတ်ဝင်စားစရာမကောင်းတဲ့ အသေးစိတ်ကိစ္စလေးတွေကို ကြားထဲကလုပ်ဆောင်ပေးနိုင်တာပဲဖြစ်ပါတယ်။

This version gives us a few more improvements. Most important, there
is no need to specify the way we want the program to jump back and
forth anymore. The `while` construct takes care of that. It continues
executing the block (wrapped in braces) below it as long as the
condition it was given holds. That condition is `count <= 10`, which
means “_count_ is less than or equal to 10”. We no longer have to
create a temporary value and compare that to zero, which was just an
uninteresting detail. Part of the power of programming languages is
that they can take care of uninteresting details for us.

{{index "console.log"}}

Program ရဲ့နောက်ဆုံးမှာတော့ `while` ထဲက လုပ်ဆောင်ချက်တွေအားလုံးပြီးသွားတဲ့အခါမှာ `console.log` ဆိုတဲ့ ညွှန်ကြားချက်နဲ့ အဖြေကို ထုတ်ပြလိုက်တာပါ။

At the end of the program, after the `while` construct has finished,
the `console.log` operation is used to write out the result.

{{index "sum function", "range function", abstraction, function}}

အကယ်၍သာ program ကို သက်သက်သာသာရေးလို့ရမယ့် `range` နဲ့ `sum` တို့လို လုပ်ဆောင်နိုင်စွမ်းတွေသာရှိမယ်ဆိုရင် ကျွန်ုပ်တို့ရဲ့ program ကအောက်ကလိုမြင်ရမှာပါ။ အောက်ကရေးနည်းမှာ နံပါတ်တွေကို သူ့ဘာသူ ပေးထားတဲ့ အကွာအဝေးအတိုင်း အစဉ်လိုက်ပြုလုပ်သွားပြီးတော့ တွက်ချက်သွားတာကို တွေ့မြင်ရမှာပါ။

Finally, here is what the program could look like if we happened to
have the convenient operations `range` and `sum` available, which
respectively create a ((collection)) of numbers within a range and
compute the sum of a collection of numbers:

```{startCode:
console.log(sum(range(1, 10)));
// → 55
```

{{index readability}}

အခုဖော်ပြသွားတာတွေကို ကောက်ချက်ချလိုက်ရင်တော့ တူညီတဲ့ program တစ်ခုကို တိုတိုလေးဖြစ်စေ၊ အရှည်ဖြစ်စေ၊ ဖတ်လို့မရသောနည်းဖြစ်စေ၊ ဖတ်လို့ရတဲ့နည်းနဲ့ဖြစ်စေ ကြိုက်သလိုရေးလို့ရတာကိုတွေ့မြင်ရမှာပါ။ ပထမဆုံး ရေးနည်းကတော့ တော်တော်ကို ဖတ်လို့မရတာထင်ရှားပါတယ်။ ထို့အတူနောက်ဆုံးနည်းလမ်းမှာကတော့ `range` ၁ ကနေ ၁၀ ထိကို `sum` ပြီးတော့ `log` ထုတ်ပြပါ ဆိုပြီးတော့ ပုံမှန်စကားပြောတဲ့နီးပါး ဖတ်လို့ရနေပါတယ်။ (ကျွန်ုပ်တို့တွေ [နောက်လာမဲ့အခန်းတွေမှာ](data) `sum` နဲ့ `range` တို့လိုမျိုးတူညီတာမျိုးတွေရဲ့ သုံးနည်းတွေကို တွေ့မြင်လာရမှာပါ။)

The moral of this story is that the same program can be expressed in
both long and short, unreadable and readable ways. The first version of the
program was extremely obscure, whereas this last one is almost
English: `log` the `sum` of the `range` of numbers from 1 to 10. (We
will see in [later chapters](data) how to define operations like `sum`
and `range`.)

{{index ["programming language", "power of"], composability}}

ကောင်းမွန်တဲ့ programming language ဟာ programmer ကို လွယ်ကူမြင်သာစေတဲ့ ညွှန်ကြားမှုမျိုးတွေနဲ့ ကွန်ပျူတာကို ခိုင်းစေနိုင်အောင်ကူညီပေးပါတယ်။ အခြေခံလုပ်ဆောင်ချက်တွေဖြစ်တဲ့ `while` နဲ့ `console.log` တို့လို လုပ်ဆောင်ချက်တွေပေးပါတယ်။ ထို့လုပ်ဆောင်ချက်တွေဟာ `sum` နဲ့ `range` တို့လို့တူညီတဲ့ လုပ်ဆောင်နိုင်စွမ်းတွေကို သင်ကိုယ်တိုင်ဖန်တီးတဲ့နေရာမှာအသုံးပြုနိုင်ပါတယ်။

A good programming language helps the programmer by allowing them to
talk about the actions that the computer has to perform on a higher
level. It helps omit details, provides convenient building blocks
(such as `while` and `console.log`), allows you to define your own
building blocks (such as `sum` and `range`), and makes those blocks
easy to compose.

## JavaScript ဆိုတာဘာလဲ?

## What is JavaScript?

{{index history, Netscape, browser, "web application", JavaScript, [JavaScript, "history of"], "World Wide Web"}}

{{indexsee WWW, "World Wide Web"}}

{{indexsee Web, "World Wide Web"}}

JavaScript ကို ၁၉၉၅ တုန်းက Netscape Navigator browser မှာ web page တွေအတွက် program တွေထည့်နိုင်တဲ့ နည်းလမ်းတစ်ခုအနေနဲ့ စတင်မိတ်ဆက်ခဲ့တယ်။ အဲ့ဒီကနေစပြီးတော့ JavaScript ကို major graphical web browsers တွေကနေ လိုက်သုံးလာကြတယ်။ အဲ့ကနေစပြီးတော့ page တွေကို reload လုပ်စရာမလိုပဲနဲ့ interact လုပ်လို့ရနိုင်တဲ့ modern web application တွေစတင်လာခဲ့ပါတယ်။ Javascript ကို ပုံမှန် website တွေမှာပါ website ကို ပိုမိုပြီး အသုံးပြုရလွယ်အောင်၊ သုံးရတဲ့သူ စိတ်ကျေနပ်စေတဲ့ အတွေ့အကြုံတွေပေးနိုင်အောင်လို့ အသုံးပြုကြပါတယ်။

JavaScript was introduced in 1995 as a way to add programs to web
pages in the Netscape Navigator browser. The language has since been
adopted by all other major graphical web browsers. It has made modern
web applications possible—applications with which you can interact
directly without doing a page reload for every action. JavaScript is also
used in more traditional websites to provide various forms of
interactivity and cleverness.

{{index Java, naming}}

ဒီမှာအထူးသတိပြုရမှာကတော့ JavaScript နဲ့ Java လို့ခေါ်တဲ့ programming language နဲ့ ဘာမှပတ်သတ်မှုမရှိဘူးဆိုတာကိုပါပဲ။ နာမည်ဆင်သယောင်ဖြစ်နေရတာကတော့ marketing အမြင်နဲ့ နာမည်ပေးခဲ့ကြလို့ဖြစ်ပါတယ်။ JavaScript ကိုစပြီးတော့ မိတ်ဆက်ခဲ့တုန်းက Java language က လူသိများနေပြီးတော့ ကြော်ညှာအားကောင်းတဲ့ language တစ်ခုဖြစ်နှင့်နေပြီးသားပါ။ တစ်ယောက်ယောက်က Java နဲ့ အောင်မြင်မှုနဲ့ ကပ်ပြီးတော့ အောင်မြင်အောင်လုပ်တာ ကောင်းမယ်လို့ အကြံရပြီးလုပ်ခဲ့တာဖြစ်ပါလိမ့်မယ်။ အခုတော့ ကျွန်ုပ်တို့တွေ ဒီနာမည်နဲ့ပဲ တောက်လျောက်နေရပါတော့မယ်။

It is important to note that JavaScript has almost nothing to do with
the programming language named Java. The similar name was inspired by
marketing considerations rather than good judgment. When JavaScript
was being introduced, the Java language was being heavily marketed and
was gaining popularity. Someone thought it was a good idea to try to
ride along on this success. Now we are stuck with the name.

{{index ECMAScript, compatibility}}

Netscape အပြင် တခြားသူတွေလိုက်သုံးဆွဲကြအပြီးမှာတော့ JavaScript language ဘယ်လိုအလုပ်လုပ်သင့်တယ် စံစနစ်ကို စတင်ပြီးတော့ သတ်မတ်ရေးသားခဲ့ကြပါတယ်။ ဘာကြောင့်လဲဆိုတော့ တခြား JavaScript ကို ထောက်ပံ့ပေးပါတယ်ဆိုတဲ့ software တွေကလည်း အမှန်တော့ JavaScript ကိုပဲပြောနေကြလို့ပါပဲ။ ထိုစံစနစ်ကို Ecma လို့ခေါ်တဲ့ စံစနစ်တွေကို သတ်မှတ်ပေးနေတဲ့ international organization ကိုအဆွဲပြုပြီးတော့ ECMAScript စံစနစ်လို့ ခေါ်ခဲ့ပါတယ်။ တကယ်လက်တွေ့မှာတော့ JavaScript ကို ECMAScript လို့လည်းခေါ်ဝေါ်သုံးဆွဲနိုင်ပါတယ်။ Language တစ်ခုအတွက် နာမည်နှစ်ခုရှိနေခြင်းသာဖြစ်ပါတယ်။

After its adoption outside of Netscape, a ((standard)) document was
written to describe the way the JavaScript language should work so
that the various pieces of software that claimed to support JavaScript
were actually talking about the same language. This is called the
ECMAScript standard, after the Ecma International organization that
did the standardization. In practice, the terms ECMAScript and
JavaScript can be used interchangeably—they are two names for the same
language.

{{index [JavaScript, "weaknesses of"], debugging}}

JavaScript နဲ့ဆိုင်တဲ့ တော်တော်ဆိုးရွားတဲ့ မကောင်းကြောင်းတွေ တချို့ကပြောပါလိမ့်မယ်။ ထိုအထဲကတော်တော်များများ မှန်နေတာကိုလည်း တွေ့ရပါလိမ့်မယ်။ စာရေးသူ JavaScript နဲ့တစ်ခုခုရေးဖို့ ပထမဆုံးအကြိမ် ကြုံလာခဲ့တုန်းက စာရေးသူကိုယ်တိုင် JavaScript ကို ချက်ချင်းမနှစ်ခြိုက်ခဲ့ပါဘူး။ လိုရင်းအတိုင် ရလဒ်ထွက်အောင်မရေးနိုင်ခဲ့ပါဘူး။ အဲ့ဒါဟာ စာရေးသူကိုယ်တိုင် သေချာနားမလည်ပဲ ရေးခဲ့တာနဲ့အများကြီးဆိုင်ပါတယ်။ ဒါပေမဲ့ JavaScript မှာ ပြဿနာတစ်ခုရှိတာက မယုံနိုင်အောင်ကို လွတ်လွတ်လပ်လပ် လုပ်ကိုင်နိုင်တာဖြစ်ပါတယ်။ အဲ့လိုလုပ်ထားရတဲ့ နောက်ကွယ်က ရည်ရွယ်ချက်ကတော့ စတင်လေ့လာသူတွေ နားလည်ရလွယ်ကူစေဖို့ဖြစ်ပါတယ်။ တကယ့်လက်တွေ့ရေးသားတဲ့အချိန်မှာတော့ ပြဿနာတစ်ခုခုကြုံတိုင်းမှာ ရှာရတာပိုမိုခက်ခဲသွားစေပါတယ်။ ဘာကြောင့်လဲဆိုတော့ system ကနေပြီးတော့ ပြဿနာကို ထောက်မပြနိုင်လို့ဖြစ်ပါတယ်။

There are those who will say _terrible_ things about JavaScript. Many
of these things are true. When I was required to write something in
JavaScript for the first time, I quickly came to despise it. It would
accept almost anything I typed but interpret it in a way that was
completely different from what I meant. This had a lot to do with the
fact that I did not have a clue what I was doing, of course, but there
is a real issue here: JavaScript is ridiculously liberal in what it
allows. The idea behind this design was that it would make programming
in JavaScript easier for beginners. In actuality, it mostly makes
finding problems in your programs harder because the system will not
point them out to you.

{{index [JavaScript, "flexibility of"], flexibility}}

သို့ပေမဲ့လည်း ဒီလိုမျိုး လိုသလိုသုံးလို့ရနေတာဟာလည်း သူ့ရဲ့အားသာချက်တွေအများကြီးရှိပါတယ်။ လွတ်လွတ်လပ်လပ် ရေးလို့မရတဲ့ language တွေမှာမဖြစ်နိုင်တဲ့ လုပ်ပုံလုပ်နည်းတွေကို လုပ်ဆောင်နိုင်တာတွေ့ရပါလိမ့်မယ် (နမူနာ [Chapter ?](modules))။ TODO:

This flexibility also has its advantages, though. It leaves space for
a lot of techniques that are impossible in more rigid languages, and
as you will see (for example in [Chapter ?](modules)), it can be used
to overcome some of JavaScript's shortcomings. After ((learning)) the
language properly and working with it for a while, I have learned to
actually _like_ JavaScript.

{{index future, [JavaScript, "versions of"], ECMAScript, "ECMAScript 6"}}

There have been several versions of JavaScript. ECMAScript version 3
was the widely supported version in the time of JavaScript's ascent to
dominance, roughly between 2000 and 2010. During this time, work was
underway on an ambitious version 4, which planned a number of radical
improvements and extensions to the language. Changing a living, widely
used language in such a radical way turned out to be politically
difficult, and work on the version 4 was abandoned in 2008, leading to
a much less ambitious version 5, which made only some uncontroversial
improvements, coming out in 2009. Then in 2015 version 6 came out, a
major update that included some of the ideas planned for version 4.
Since then we've had new, small updates every year.

The fact that the language is evolving means that browsers have to
constantly keep up, and if you're using an older browser, it may not
support every feature. The language designers are careful to not make
any changes that could break existing programs, so new browsers can
still run old programs. In this book, I'm using the 2017 version of
JavaScript.

{{index [JavaScript, "uses of"]}}

Web browsers are not the only platforms on which JavaScript is used.
Some databases, such as MongoDB and CouchDB, use JavaScript as their
scripting and query language. Several platforms for desktop and server
programming, most notably the ((Node.js)) project (the subject of
[Chapter ?](node)), provide an environment for programming JavaScript
outside of the browser.

## Code, and what to do with it

{{index "reading code", "writing code"}}

_Code_ is the text that makes up programs. Most chapters in this book
contain quite a lot of code. I believe reading code and writing ((code))
are indispensable parts of ((learning)) to program. Try to not just
glance over the examples—read them attentively and understand them.
This may be slow and confusing at first, but I promise that you'll
quickly get the hang of it. The same goes for the ((exercises)). Don't
assume you understand them until you've actually written a working
solution.

{{index interpretation}}

I recommend you try your solutions to exercises in an actual
JavaScript interpreter. That way, you'll get immediate feedback on
whether what you are doing is working, and, I hope, you'll be tempted
to ((experiment)) and go beyond the exercises.

{{if interactive

When reading this book in your browser, you can edit (and run) all
example programs by clicking them.

if}}

{{if book

{{index download, sandbox, "running code"}}

The easiest way to run the example code in the book, and to experiment
with it, is to look it up in the online version of the book at
[_https://eloquentjavascript.net_](https://eloquentjavascript.net/). There,
you can click any code example to edit and run it and to see the
output it produces. To work on the exercises, go to
[_https://eloquentjavascript.net/code_](https://eloquentjavascript.net/code),
which provides starting code for each coding exercise and allows you
to look at the solutions.

if}}

{{index "developer tools", "JavaScript console"}}

If you want to run the programs defined in this book outside of the
book's website, some care will be required. Many examples stand on their
own and should work in any JavaScript environment. But code in later
chapters is often written for a specific environment (the browser or
Node.js) and can run only there. In addition, many chapters define
bigger programs, and the pieces of code that appear in them depend on
each other or on external files. The
[sandbox](https://eloquentjavascript.net/code) on the website provides
links to Zip files containing all the scripts and data files
necessary to run the code for a given chapter.

## Overview of this book

This book contains roughly three parts. The first 12 chapters discuss
the JavaScript language. The next seven chapters are about web
((browsers)) and the way JavaScript is used to program them. Finally,
two chapters are devoted to ((Node.js)), another environment to
program JavaScript in.

Throughout the book, there are five _project chapters_, which describe
larger example programs to give you a taste of actual programming. In
order of appearance, we will work through building a [delivery
robot](robot), a [programming language](language), a [platform
game](game), a [pixel paint program](paint), and a [dynamic
website](skillsharing).

The language part of the book starts with four chapters that introduce
the basic structure of the JavaScript language. They introduce
[control structures](program_structure) (such as the `while` word you
saw in this introduction), [functions](functions) (writing your own
building blocks), and [data structures](data). After these, you will
be able to write basic programs. Next, Chapters [?](higher_order) and
[?](object) introduce techniques to use functions and objects to write
more _abstract_ code and keep complexity under control.

After a [first project chapter](robot), the language part of the book
continues with chapters on [error handling and bug fixing](error),
[regular expressions](regexp) (an important tool for working with
text), [modularity](modules) (another defense against complexity), and
[asynchronous programming](async) (dealing with events that take
time). The [second project chapter](language) concludes the first part
of the book.

The second part, Chapters [?](browser) to [?](paint), describes the
tools that browser JavaScript has access to. You'll learn to display
things on the screen (Chapters [?](dom) and [?](canvas)), respond to
user input ([Chapter ?](event)), and communicate over the network
([Chapter ?](http)). There are again two project chapters in this
part.

After that, [Chapter ?](node) describes Node.js, and [Chapter
?](skillsharing) builds a small website using that tool.

{{if commercial

Finally, [Chapter ?](fast) describes some of the considerations that
come up when optimizing JavaScript programs for speed.

if}}

## Typographic conventions

{{index "factorial function"}}

In this book, text written in a `monospaced` font will represent
elements of programs—sometimes they are self-sufficient fragments, and
sometimes they just refer to part of a nearby program. Programs (of
which you have already seen a few) are written as follows:

```
function factorial(n) {
  if (n == 0) {
    return 1;
  } else {
    return factorial(n - 1) * n;
  }
}
```

{{index "console.log"}}

Sometimes, to show the output that a program produces, the
expected output is written after it, with two slashes and an arrow in
front.

```
console.log(factorial(8));
// → 40320
```

Good luck!
