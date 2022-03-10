
### თბილისის ევოლუცია
<b> - პროექტის შესახებ - </b>

ეს ინტერაქტიული რუკა მომზადდა ილიას სახელმწიფო უნივერსიტეტთან თანამშრომლობით და მოიაზრება "თბილისი, როგორც ურბანული თანაკვეთის სივრცე" კვლევითი პროექტის ნაწილად, შოთა რუსთაველის ეროვნული სამეცნიერო ფონდის კვლევითი გრანტის ფარგლებში. 

რუკის მთავარ მიზანს წარმოადგენს თბილისის სივრცითი და სოციო-ფუნქციური ზრდის დოკუმენტირება. იგი შესაძლებელია გამოყენებულ იქნას როგორც ერთ-ერთი კვლევითი ინსტრუმენტი, როგორც ქალაქგანვითარების, არქიტექტურის თუ სოციალური გეოგრაფიის მიმართულებით, ისე სხვა მომიჯნავე პროფესიის წარმომადგენლების მიერ. ამასთანავე, ეს ინტერაქტიული პროექტი დაეხმარება თბილისის ისტორიული განვითარებით დაინტერესებულ პირებს მარტივად დააკვირდნენ ქალაქის სივრცე-დროით ევოლუციას რუკის შედარებითი ფუნქციის მეშვეობით. 

<b> - რატომ ეს კონკრეტული პერიოდი? - </b> 

ეს განპირობებულია რამდენიმე საკითხით. პირველ რიგში, 1970-80-იანი წლები არის პერიოდი, როდესაც თბილისის განაშენიანებული ტერიტორია განსაკუთრებით სწრაფად და ინტენსიურად გაიზარდა. ამასთანავე, თბილისის ურბანული ფორმისა და სოციო-ეკონომიკური ფუნქციების შესახებ ყველაზე დეტალური ისტორიული, სანდო და ხელმისაწვდომი ინფორმაცია შემონახულია საბჭოთა ტოპოგრაფიული რუკების სერიაში, `1:2000` მასშტაბით. რაც შეეხება დღევანდელ მდგომარეობას, რუკაზე დატანილი ინფორმაცია ნაწილობრივ ასახავს 2018 წლის მდგომარეობას, რუკის ნაწილის მონაცემები კი განახლებულია 2022 წლის თებერვლის მდგომარეობით. ეს, დაახლოებით ნახევარსაუკუნოვანი დაშორება, კი კარგად გვიჩვენებს ქალაქის რომელმა ნაწილმა როგორ შეიცვალა ფორმა, ფუნქციურობა თუ სიმჭიდროვე.

<b> - მონაცემები და მათი შეგროვების ხელსაწყოები - </b>

პორტალისთვის მონაცემები რამდენიმე განსხვავებული ფორმით შეგროვდა, მეტწილად დისტანციური ზონდირებისა და GIS გამოყენებით. მასშტაბურობიდან გამომდინარე, მონაცემების  შესაგროვებლად, პროექტის განმავლობაში გამოვიყენეთ ილიას სახელმწიფო უნივერსიტეტის არქიტექტურის სტუდენტების მიერ უკვე შექმნილი ისტორიული მონაცემები საბჭოთა ტოპოგრაფიული რუკიდან, `.dwg` ფორმატში. ამასთანავე, მონაცემების სრულყოფის მიზნით, პროექტში ჩართულ სტუდენტებს გავაცანით GIS მეთოდებისა და ხელსაწყოების გამოყენების სპეციფიკაციები.

პორტალი ეფუძნება ორ ძირითად წყაროს: 

1) 1970-80-იანი წლების საბჭოთა ტოპოგრაფიული რუკა `1:2000` მასშტაბით - `wmts` სერვერის ბმული - `http://mp1.napr.gov.ge/TOPO_2k_Cityes/wmts/1.0.0/WMTSCapabilities.xml`
2) საჯარო რეესტრის საკადასტრო მონაცემები და რეგისტრირებული შენობები - `wms` სერვერის ბმული - `https://nv.napr.gov.ge/geoserver/wms` --> `LR_BUILDINGS` ფენა  შენობებისა და მათი სართულიანობის შესახებ.

ორივე მონაცემთა წყაროს ჩატვირთვა შესაძლებელია GIS პროგრამული უზრუნველყოფის მეშვეობით. ამისთვის, ნებისმიერ GIS პროგრამაში უნდა დავამატოთ მონაცემთა ფენები `wmts` და `wms` სერვერბის გამოყენებით. შესაბამისი ბმულები მითითებულია წყაროების გასწვრივ.

<b> - შეზღუდვები - </b>

მიუხედავად იმისა, რომ პორტალი გვეხმარება შევაფასოთ ზოგადი სურათი ქალაქის ფიზიკური ფორმისა თუ სოციო-ეკონომიკური აქტივობების ცვლილების შესახებ, არსებობს რამდენიმე მეთოდოლოგიური და შინაარსობრივი შეზღუდვა, რომელიც უნდა გავითვალისწინოთ ამ პორტალის გამოყენებისა და ვიზუალური მასალის ინტერპრეტაციის დროს. 

მეთოდოლოგიური შეზღუდვა განპირობებულია მონაცემთა წყაროების ცდომილებიდან გამომდინარე. მაგალითისთვის, თვალსაჩინოა, რომ საბჭოთა ტოპოგრაფიულ რუკაზე დატანილი ინფორმაცია ფუნქციური გამოყენების შესახებ არასრულია. მასზე არ არის სრულყოფილად დატანილი ინფორმაცია სახელმწიფო უწყების შენობებისა თუ მნიშვნელოვანი ინფრასტრუქტურული ობიექტების შესახებ. ეს სავარაუდოდ განპირობებულია იმ პერიოდის სახელმწიფო უსაფრთხოებისა თუ სტრატეგიული მნიშვნელობის საკითხებით. საჯარო რეესტრის მონაცემებთან დაკავშირებით, ყველაზე მნიშვნელოვანია ვახსენოთ შეუსაბამობა რეალურად არსებულ და რეგისტრირებულ შენობა-ნაგებობებს შორის. ეს გარემოება, გარკვეულწილად აფერხებს მონაცემების შეგროვებას, რამეთუ ბაზის განახლება სხვა დამატებითი წყაროების (სატელიტური თუ ორთო ფოტოგადაღება, საკადასტრო ამონაწერი და ა.შ.) შემოწმებას საჭიროებს.

პორტალზე თავმოყრილი ინფორმაცია პერიოდულად განახლდება. 

გამოყენებისა და საავტორო უფლებების შესახებ იხილეთ `License` განყოფილება. 

პროექტის გუნდი მადლობას უხდის ყველა მონაწილეს!
