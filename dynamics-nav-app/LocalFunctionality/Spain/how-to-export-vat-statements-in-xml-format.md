---
    title: How to Export VAT Statements in XML Format 
    description: You can export a VAT statement in XML format and then submit it electronically to the tax authorities.
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2017"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

---
# How to: Export VAT Statements in XML Format
You can export a VAT statement in XML format and then submit it electronically to the tax authorities.  
  
 For more information, see the [Spanish Tax Agency](http://go.microsoft.com/fwlink/?LinkID=238181) website.  
  
### To export a VAT statement in XML format  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Statement**, and then choose the appropriate link.  
  
2.  Select the required VAT statement, and then, on the **Actions** tab, choose **Telematic VAT**, and then choose **Generate XML file**.  
  
    > [!IMPORTANT]  
    >  The VAT statement name must be of the template type **One Column Report**.  
    >   
    >  In the standard version of [!INCLUDE[navnow](../../includes/navnow_md.md)], the VAT statement name for the 392 telematic statement is of the type **One Column Report**.  
  
3.  In the **XML VAT Declaration** window, on the **ADD INCLUDE<!--[!INCLUDE[bp_optionsheading](../../includes/bp_optionsheading_md.md)]-->** FastTab, fill in the fields as described in the following table.  
  
    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**VAT entries included**|Specify if the VAT statement must include open entries, closed entries, or both open and closed entries.|  
    |**VAT entries included**|Specify if the VAT statement must include only entries from the period that is specified in the **Date Filter** field, or also entries from previous periods.|  
    |**Additional Currency**|Select to display the report amounts in the additional reporting currency.|  
  
4.  On the **VAT Statement Line** FastTab, specify a value for the **Date Filter** field.  
  
     Optionally, select additional filters.  
  
5.  Choose the **OK** button.  
  
6.  In the **XML Transference Format** window, verify that the VAT statement is set up as required, and then choose the **OK** button.  
  
 You can open or save the generated XML file. You can now submit the VAT statement to the tax authorities.  
  
## See Also  
 [How to: Create Templates for Telematic VAT Statements in XML File Format](how-to-create-templates-for-telematic-vat-statements-in-xml-file-format.md)   
 [How to: Export VAT Statements in Text Format](how-to-export-vat-statements-in-text-format.md)   
 XML VAT Declaration