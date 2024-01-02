---
cssclasses: cards, cards-1-1
---

>## **FAMIGLIARI**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM #famiglia AND #vivo
>SORT file.name asc
>```

>## **PARTNER**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM #partner AND #vivo
>SORT file.name asc
>```

>## **ALLEATI**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM #alleato AND #vivo
>SORT file.name asc
>```

>## **NEMICI**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM #nemico AND #vivo
>SORT file.name asc
>```

>## **NEMICI SCONFITTI**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM #nemico AND #defunto 
>SORT file.name asc
>```

>## **DEFUNTI**
>```dataview 
>TABLE WITHOUT ID
>image as Image,
>"**"+ file.link + "**" AS "Column Name"
>FROM -#nemico AND #defunto 
>SORT file.name asc
>```