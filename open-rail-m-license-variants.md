# Open RAIL-M license variations

This document analysues the differences between the different variants of the Open RAIL-M license family that we have encountered during our analysis of licenses used on huggingface.ai. It is not a complete overview of all veriants of the Open RAIL-M licenses, since other variants may be in use on other platforms. 

1. **BigScience RAIL License v1.0** (19-05-2022)
    
    Precurser of the Open RAil licenses. Compared to the subsequent versions it contains some language that explicitly refers to the BigScience BLOOM model. For the rest the differences between this license and the Open RAIL licenses are smaller linguistic tweaks.
    
2. **BigScience Open RAIL-M License** (original 18-08-2022)
    
3. **CreativeML Open RAIL-M License** (this is the original Stable Digffusion license from 22-08-2022) 
       
    Compated to the original this license drops the following two use restrictions from the Appendix A: 
    
    `You agree not to use the Model or Derivatives of the Model:
    To generate or disseminate information and/or content (e.g. images, code, posts, articles), and place the information and/or content in any context (e.g. bot generating tweets) without expressly and intelligibly disclaiming that the information and/or content is machine generated;
    To impersonate or attempt to impersonate (e.g. deepfakes) others without their consent;`
    
4. **OpenRAIL++-M License** (this is the license used by Stable Diffusion 2.0) 
     
    Compared to the CreativeML Open RAIL-M this license removes the following part from Point 7 in the Other provisions section: 
    
    `Updates and Runtime Restrictions. To the maximum extent permitted by law, Licensor reserves the right to restrict (remotely or otherwise) usage of the Model in violation of this License~~, update the Model through electronic means, or modify the Output of the Model based on updates. You shall undertake reasonable efforts to use the latest version of the Model~~.`
    
    This makes the license slightly less invasive for the licensee and limits the power of the licensor to enforce remote updates.
    
⚠️ The three following variants all contain language limiting the allowed uses to non-commercial use. As of writing they are only used by individual projects and not in widespread use. Note that they are all very recent (end of nov / early dec 2022)
     
5. **OpenRAIL++-M-NC License** (we found at least [one project on 🤗 that uses this license](https://huggingface.co/alfredplpl/cool-japan-diffusion-for-learning-2-0/blob/main/LICENSE-MODEL) which is dated 11-12-2022)
     
    Compared to the OpenRAIL++-M License this license adds one condition to the use restrictions in Appendix A: 
    
    `You agree not to use the Model or Derivatives of the Model:
    (a) For commercial purposes except for news reporting about image generated AI;`
    
6. **OpenRAIL++-M (modified, dreamlike-1)** (we found this in use by [one project on 🤗.](https://huggingface.co/dreamlike-art/dreamlike-diffusion-1.0) The license is dated from 27-11-2022)
    
    Compared to the OpenRAIL++-M License this license adds 3 additional conditions to the Distribution and Redistribution provision in point 4 of the license:
    
    `a. You can't host the model or it's derivatives on websites/apps, from which you earn, or plan to earn revenue. If you want to, please email us at contact@dreamlike.art 
    b. You are free to host the model or it's derivatives on non-commercial websites/apps. Please state the full model name (Dreamlike Photoreal) and include a link to the model card ([https://huggingface.co/dreamlike-art/dreamlike-photoreal-1.0](https://huggingface.co/dreamlike-art/dreamlike-photoreal-1.0))
    c. You are free to use the model or it's derivatives for commercial purposes in teams of 10 or less`
    
     It also adds one condition to the use restrictions in Appendix A: 
    
    `You agree not to use the Model or Derivatives of the Model:
    (l) To generate NFTs`
    
7. **OpenRAIL++-M (modified, dreamlike-2)** (we found this in use by [one project on 🤗.](https://huggingface.co/dreamlike-art/dreamlike-photoreal-1.0) The license is dated from 11-12-2022)
     
    Compared to the OpenRAIL++-M License this license adds 4 additional conditions to the Distribution and Redistribution provision in point 4 of the license:
    
    `a. You can't host or use the model or its derivatives on websites/apps/etc., from which you earn, will earn, or plan to earn revenue. If you want to, please email us at contact@dreamlike.art
    b. You are free to host the model card and files (Without any actual inference or finetuning) on both commercial and non-commercial websites/apps/etc. Please state the full model name (Dreamlike Diffusion 1.0) and include a link to the model card ([https://huggingface.co/dreamlike-art/dreamlike-diffusion-1.0](https://huggingface.co/dreamlike-art/dreamlike-diffusion-1.0))
    c. You are free to host the model or its derivatives on completely non-commercial websites/apps/etc. Please state the full model name (Dreamlike Diffusion 1.0) and include a link to the model card ([https://huggingface.co/dreamlike-art/dreamlike-diffusion-1.0](https://huggingface.co/dreamlike-art/dreamlike-diffusion-1.0))
    d. You are free to use the model or its derivatives for commercial purposes in teams of 10 or less`
    
    It also adds one condition to the use restrictions in Appendix A: 
    
    `You agree not to use the Model or Derivatives of the Model:
    (l) To generate NFTs`
