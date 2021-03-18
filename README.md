# vi-hafta-odev

- JavaScript'te nesne(object) örnekleri yaratarak örnekler içerisinde metodlarla birlikte kullanmaya çalışınız.
> `var dolap={width:"90",hight:"50",color:"Yellow"};
  console.log(dolap.width+"*"+ dolap.hight+" "+"Renk: "+dolap.color);`
  
> `var pc={ram:"8gb",processor:"i5-2450M",model:"Asus-ZenBook 14 UX435"};
  console.log(pc.model+": "+pc.ram+" - Ram  "+pc.processor+" - CPU ");`
- 'return' ve 'console.log' arasındaki farkı açıklayınız. Örneklerle destekleyiniz.


  Bir değer döndümek istiyor isek **return** kullanmamız daha uygundur.
  

  Fakat konsola elimizdeki bir sonucu yazdırmak istediğimizde **console.log** kullanmamız gerekmektedir.
  

  > function func()   
   {    
       return (5 * 19);  
   }       
       console.log(func()); 
   
   
  Örnek kodlamada return ile 2 değere işlem yaptırıyoruz ve bu işlemden çıkan sonucu console.log kullanarak ekrana yazdırıyoruz.
  
  
- JavaScript'te primitive types ve reference types kavramlarını araştırınız. Bu sınıflandırmalara dahil olan türleri sıralayınız.
  # Primitive Types Türleri
  + null
  + undefined
  + Boolean
  + Number
  + String
  # Reference Types Türleri
  + Array
  + Object
  + Function
  ## Kaynak
  https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c#primitive-types
  
  
  https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0
- 'for in' ve 'for of' döngülerini açıklayınız ve örneklerle destekleyiniz.
    # for...of 

    Nesnenin değerleri arasında döngü gerçekleştirir.

   > var array = ['a','b','c','d'];for (var i of array){console.log(i);}       
   

    Bu örnekte değişken tanımlaması yapılıyor (array), değişkene değer tanımlanıyor (a,b,c,d), değerler for of döngüsü kullanılarak konsola yazılıyor. 

    Konsol çıktısıda bu şekilde olucaktır. 
    > a
      b
      c
      d  
    # for...in

     Nesne özellikleri arasında döngü gerçekleştirir.
    
     Sıralı bir listeye erişilemeye bilir. 

   > const obj = {
     a: 1,
     b: 2,
     c: 3,
     d: 4
      }
     for (const key in obj) {
     console.log( obj[key] )
      }


    Konsol çıktısıda bu şekilde olucaktır. 
    > 1
      2
      3
      4
             
   

- 'for' ve 'while' döngüleri ile ilgili örnekler yapınız.
