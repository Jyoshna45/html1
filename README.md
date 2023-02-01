<!DOCTYPE html>
<html>
<head>
<title>Document</title>
<style>
    
    .holdingcontainer{
        width:100%;
        display:flex;
        background:pink;
        box-sizing:border-box;
        flex-direction:row;
        margin:0 auto;
    }
   .internalcontainerL{
            flex:1;
        background:orange;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
        
    }
    .internalcontainerM{
            flex:1;
        background:white;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    } .internalcontainerR{
            flex:1;
        background:green;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    }
    @media  screen and(max-width:760px) {
        .holdingcontainer{
            flex-direction: column-reverse;
        }
        
        
    }   
    .holdingcontainer1{
        width:100%;
        display:flex;
        background:pink;
        box-sizing:border-box;
        flex-direction:second row;
        margin:0 auto;
    }
   .internalcontainerL1{
            flex:1;
        background: orange;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    }
    .internalcontainerM1{
            flex:1;
        background:white;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    } .internalcontainerR1{
            flex:1;
        background:green;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    }
    @media  screen and(max-width:760px) {
        .holdingcontainer{
            flex-direction: column-reverse;
        }
        
        
    }   
    .holdingcontainer2{
        width:100%;
        display:flex;
        background:pink;
        box-sizing:border-box;
        flex-direction:third row;
        margin:0 auto;
    }
   .internalcontainerL2{
            flex:1;
        background:orange;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    }
    .internalcontainerM2{
            flex:1;
        background:white;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    } .internalcontainerR2{
            flex:1;
        background: green;
        padding:30px;
        font-size:12px;
        font-family: 'roboto',sans-serif;
        margin:3px;
    }
    @media  screen and(max-width:760px) {
        .holdingcontainer{
            flex-direction: column-reverse;
        }
        
        
    }  
    #Header{
        width: 100%;
        top:0px;
        left: 0px;
        background-image: linear-gradient(90deg,orange,white,green);
        position:fixed;
        
    } 
    #Footer{
        width: 100%;
        bottom:0px;
        left:0px;
        background-image: linear-gradient(90deg,orange,white,green);
        position: fixed;
        padding: 2px;
        margin: 0px;
        font-size: 12px;   
    }
    </style>
</head>
<body>
  <div class="holdingcontainer">
    <div class="internalcontainerL" >
     <h1>TajMahal</h1>
     <img  src="https://tse1.mm.bing.net/th?id=OIP._vkywyPP0Hr4EnPyVo65wwHaFn&pid=Api&P=0" alt="text goes here" width="400px">
     <p>The Taj Mahal was commissioned by Shah Jahan in 1631, to be built in the memory of his wife Mumtaz Mahal, who died on 17 June that year,
     while giving birth to their 14th child, Gauhara Begum.[12][13] Construction started in 1632,[14] and the mausoleum was completed in 1648,
     while the surrounding buildings and garden were finished five years later.[15] The imperial court documenting Shah Jahan's grief after 
     the death of Mumtaz Mahal illustratesthe love story held as the inspiration for the Taj Mahal.
     <a href="https://en.wikipedia.org/wiki/Origins_and_architecture_of_the_Taj_Mahal"  class="btn">click here</a> 
     </p>
   </div>
        <div class="internalcontainerM">
            <h1>LotusTemple</h1>
            <img src="https://tse2.mm.bing.net/th?id=OIP.tC9BH9wrdOlR9iYruQ3JuAHaE8&pid=Api&P=0" height="400px" width="100%">
            <p>The Lotus Temple, located in Delhi, India, is a Baháʼí House of Worship that was dedicated in December 1986.
             Notable for its flowerlike shape, it has become a prominent attraction in the city. Like all other Bahái Houses of
             Worship, the Lotus Temple is open to all, regardless of religion or any other qualification. The building is composed 
             of 27 free-standing marble-clad "petals" arranged in clusters of three to form nine sides,with nine doors opening onto
             a central hall with a height of slightly over 34 meters[1] and a capacity of 1,300 people.
             <a href="https://en.wikipedia.org/wiki/Lotus_Temple" class="btn">click here</a>
             </p>

        </div>
        <div class="internalcontainerR">
            <h1>Charminar</h1>
            <img src="https://tse3.mm.bing.net/th?id=OIP.sBxn9egMbynimDjI3-UXdAHaKK&pid=Api&P=0" height="500px" width="400px">
            <p>The Charminar  constructed in 1591, is a monument located in Hyderabad, Telangana, India. The landmark has become known
             globally as a symbol of Hyderabad and is listed among the most recognised structures in India. It has also been officially 
             incorporated as the Emblem of Telangana[3] The Charminar's long history includes the existence of a mosque on its top floor 
             for more than 425 years.
             <a href="https://en.wikipedia.org/wiki/Charminar" class="btn" >click here</a>
            </p>

        </div>
       
    </div>
    <div class="holdingcontainer1">
        <div class="internalcontainerL1">
            <h1>QutubMinar</h1>
            <img src="https://tse4.mm.bing.net/th?id=OIP.9L6flf_LAfcDE3a_6DHkZAHaE7&pid=Api&P=0" width="100%">
            <p>Qutb-ud-din Aibak, a deputy of Muhammad of Ghor, who founded the Delhi Sultanate after Muhammad of Ghor's death, started
            construction of the Qutb Minar's first story in 1199. Aibak's successor and son-in-law Shamsuddin Iltutmish completed a further
             three stories.[15] After a lightning strike in 1369 damaged the then top story, the ruler at the time, Firuz Shah Tughlaq, replaced 
             the damaged story and added one more.
             <a href="https://en.wikipedia.org/wiki/Qutb_Minar" class="btn" >click here</a>
            </p>
        </div>
        <div class="internalcontainerM1">
            <h1>RedFort</h1>
        <img src="https://tse3.mm.bing.net/th?id=OIP.Qz6IWI0w3-H_1ishg6aVkgHaE9&pid=Api&P=0" >
         <p>The Red Fort or Lal Qila  is a historic fort in Old Delhi, Delhi in India that served as the main residence of the Mughal Emperors.
             Emperor Shah Jahan commissioned construction of the Red Fort on 12 May 1638, when he decided to shift his capital from Agra to Delhi. 
            Originally red and white, its design is credited to architect Ustad Ahmad Lahori, who also constructed the Taj Mahal.
            <a href="https://en.wikipedia.org/wiki/Red_Fort" class="btn">click here</a>
         </p>
        </div>
        <div class="internalcontainerR1">
            <h1>AkshardhamTemple</h1>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/New_Delhi_Temple.jpg/330px-New_Delhi_Temple.jpg" width="100%">
            <p>Swaminarayan Akshardham is a Hindu temple, and spiritual-cultural campus in Delhi, India. The temple is close to the border with 
            Noida. Also referred to as Akshardham Temple or Akshardham Delhi, the complex displays millennia of traditional and modern Hindu culture,
           spirituality, and architecture. Inspired by Yogiji Maharaj and created by Pramukh Swami Maharaj, it was constructed by BAPS
           <a href="https://en.wikipedia.org/wiki/Swaminarayan_Akshardham_(Delhi)" class="btn">click here</a>
        </p>
        </div>
    </div>
    <div class="holdingcontainer2">
        <div class="internalcontainerL2">
        <h1>FatehPurSikri</h1>
        <img src="https://tse2.mm.bing.net/th?id=OIP.WyzCVWceG83aGEP34r7A_gHaFL&pid=Api&P=0" width="100%" height="50%">
        <p>Fatehpursikri is a town in the Agra District of Uttar Pradesh, India. Situated 35.7 kilometers from the district headquarters
        Agra,[3] Fatehpur Sikri itself was founded as the capital of Mughal Empire in 1571 by Emperor Akbar, serving this role from 1571
         to 1585, when Akbar abandoned it due to a campaign in Punjab and was later completely abandoned in 1610.
         <a href="https://en.wikipedia.org/wiki/Fatehpur_Sikri" class="btn">click here</a>
         </p>
        </div>
        <div class="internalcontainerM2">
            <h1>HawaMahal</h1>
            <img src="https://tse4.mm.bing.net/th?id=OIP.O7wdepLMkrrL-AyFPvAplAHaDS&pid=Api&P=0" width="100%">
            <p>The Hawa Mahal is a palace in the city of Jaipur, India. Built from red and pink sandstone, it is on the edge of the City Palace, Jaipur, 
            and extends to the Zenana, or women's chambers.The structure was built in 1799 by the Maharaja Sawai Pratap Singh, grandson of Maharaja Sawai 
            Jai Singh, the founder of the city of Jaipur, India.He was so inspired by the unique structure of Khetri Mahal that he built this grand and
             historical palace.
             <a href="https://en.wikipedia.org/wiki/Hawa_Mahal#:~:text=The%20Hawa%20Mahal%20is%20a,the%20Zenana%2C%20or%20women's%20chambers." class="btn">click here</a>
            </p>
        </div>
        <div class="internalcontainerR2">
            <h1>Victoria Memorial</h1>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Victoria_Memorial_Pano_5.jpg/860px-Victoria_Memorial_Pano_5.jpg" width="100%">
            <p>The Victoria Memorial is a large marble building in Central Kolkata, which was built between 1906 and 1921.
             It is dedicated to the memory of Queen Victoria, Empress of India from 1876 to 1901. It is now a museum under the auspices of the Ministry
             of Culture, and is the largest monument in the world which is dedicated to a royal.[2] The memorial lies on the Maidan and is one of
             the famous monuments of Kolkata.
             <a href="https://en.wikipedia.org/wiki/Victoria_Memorial,_Kolkata" class="btn">click here</a>
            </p>
        </div>
    </div>
    
    <div id="Header" align="center">
        <h1>Historical Places In India</h1>
    </div>
    <div id="Footer" align="center">
        <h1>Designed and Developed By Jyoshna...</h1>
        <h2>Thank You!.....</h2>
    </div>
</body>
</html>
