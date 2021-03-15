# programs
string caps

const addfun = (string) => {
      var sen = string.toLowerCase().split(" ");
      for(var i = 0; i< sen.length; i++){
         sen[i] = sen[i][0].toUpperCase() + sen[i].slice(1);
      }
   console.log(sentence.join(" "));
   return sentence;
   }
   addfun("guvi is one of best e-platforms");
