﻿![अच्छे प्रथम अंक](./assets/github/social-preview.png)

#अच्छे प्रथम अंक

**गुड फ़र्स्ट इश्यूज़** लोकप्रिय परियोजनाओं से आसानी से चयन करने की एक पहल है, ताकि जिन डेवलपर्स ने कभी भी ओपन-सोर्स में योगदान नहीं दिया है, वे जल्दी से शुरुआत कर सकें।

वेबसाइट: [good-first-issues.github.io](https://good-first-issues.github.io)

यह वेबसाइट मुख्य रूप से उन डेवलपर्स पर लक्षित है जो ओपन सोर्स सॉफ़्टवेयर में योगदान देना चाहते हैं लेकिन यह नहीं जानते कि कहां या कैसे शुरू करें।

ओपन-सोर्स अनुरक्षक हमेशा अधिक लोगों को शामिल करना चाहते हैं, लेकिन नए डेवलपर्स आमतौर पर सोचते हैं कि योगदानकर्ता बनना चुनौतीपूर्ण है। हमारा मानना ​​है कि डेवलपर्स को बेहद आसान मुद्दों को ठीक करने से भविष्य के योगदान के लिए बाधाएं दूर हो जाती हैं। यही कारण है कि *अच्छे प्रथम अंक* मौजूद हैं।

## एक नया प्रोजेक्ट जोड़ना

*गुड फ़र्स्ट इश्यूज़* में एक नया प्रोजेक्ट जोड़ने के लिए आपका स्वागत है, बस इन चरणों का पालन करें:

- *अच्छे प्रथम अंक* में परियोजनाओं की गुणवत्ता बनाए रखने के लिए, कृपया सुनिश्चित करें कि आपका GitHub रिपॉजिटरी निम्नलिखित मानदंडों को पूरा करता है:

     - इसमें 'अच्छा पहला अंक' लेबल के साथ कम से कम तीन अंक हैं। यह लेबल डिफ़ॉल्ट रूप से सभी रिपॉजिटरी पर पहले से मौजूद है।

     - इसमें प्रोजेक्ट के लिए विस्तृत सेटअप निर्देशों के साथ `README.md` शामिल है

     - इसे सक्रिय रूप से बनाए रखा गया है (अंतिम अपडेट 1 महीने से भी कम समय पहले)

- [repositories.json](https://github.com/gomzyakov/good-first-issue/blob/main/repositories.json) में अपने रिपॉजिटरी का पथ (प्रारूप 'मालिक/नाम' और लेक्सिकोग्राफ़िक क्रम में) जोड़ें।

- एक नया पुल-अनुरोध बनाएं। कृपया पीआर विवरण में रिपॉजिटरी के मुद्दे पृष्ठ पर लिंक जोड़ें। एक बार पुल अनुरोध मर्ज हो जाने पर, परिवर्तन [good-first-issues.github.io](https://good-first-issues.github.io) पर लाइव होंगे।

## यह कैसे काम करता है?

- फर्स्ट *गुड फर्स्ट इश्यूज* एक स्थिर वेबसाइट है जो HTML फ़ाइलें उत्पन्न करने के लिए [PHP](https://www.php.net)` का उपयोग करती है।
- हम [repositories.json](https://github.com/gomzyakov/good-first) में सूचीबद्ध रिपॉजिटरी से मुद्दे लाने के लिए [GitHub REST API](https://docs.github.com/en/rest) का उपयोग करते हैं -इश्यू/ब्लॉब/मेन/रिपॉजिटरीज.जेसन)।
- समय-समय पर मुद्दों पर विचार करने के लिए (दिन में दो बार), हम [GitHub वर्कफ़्लो](https://docs.github.com/en/actions/using-workflows) का उपयोग करते हैं।

## हमें बढ़ने में मदद करें

शुरुआती और अनुभवी योगदानकर्ताओं के लिए ओपन-सोर्स परियोजनाओं को नेविगेट करना काफी भारी हो सकता है। *गुड फ़र्स्ट इश्यूज़* एक ऐसा प्लेटफ़ॉर्म प्रदान करके इस समस्या को हल करना चाहता है जो ओपन-सोर्स के साथ शुरुआत करने वालों या किसी नए प्रोजेक्ट में शामिल होने के इच्छुक लोगों के लिए शुरुआती बिंदु के रूप में कार्य करता है।

जितने अधिक लोग [good-first-issues.github.io](https://good-first-issues.github.io) के बारे में जानेंगे, उतना बेहतर होगा। ऐसे कई तरीके हैं जिनसे आप हमें आगे बढ़ने में मदद कर सकते हैं: उदाहरण के लिए, आप 'अद्भुत' सूचियों में योगदान कर सकते हैं, हमारे बारे में ब्लॉग कर सकते हैं, ब्लॉगर्स, तकनीकी प्रभावों, डेवलपर और ट्विटर और यूट्यूब पर ओपन-सोर्स तक पहुंच सकते हैं। कोशिश करें और किसी वीडियो या ट्वीट में [good-first-issues.github.io](https://good-first-issues.github.io) का उल्लेख करें!

## सुझाव और शुभकामनाएं

यदि आपके कोई प्रश्न या सुझाव हैं (या कोई बग मिला है), तो आप हमेशा [issues](https://github.com/good-first-issues/good-first-issues.github.io/issues) पर लिख सकते हैं।

## लाइसेंस

यह [MIT लाइसेंस](https://github.com/good-first-issues/good-first-issues.github.io/blob/main/LICENSE) के तहत लाइसेंस प्राप्त ओपन-सोर्स सॉफ़्टवेयर है।