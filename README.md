# cnsm-submission

## dfoh-cases
The [dfoh-cases](https://gitlab.utwente.nl/m7714476/cnsm-submission/-/tree/main/dfoh-cases?ref_type=heads) directory contains DFOH's daily inferences as published on their [website](https://forge.icube.unistra.fr/tholterbach/dfoh_runner/-/blob/main/README.md?ref_type=heads).

## preprocesed.cases
The [preprocesed.cases](https://gitlab.utwente.nl/m7714476/cnsm-submission/-/tree/main/preprocesed.cases?ref_type=heads) directory contains two subdirectories:<br>
**sus**: contains all the suspicious inferred cases. <br>
**leg**: contains all the legitimate inferred cases. <br>
***Note***: The above directories currently including all the rows (inferences) as provided on the DFOH website but it seems have some level of redundancy.

## Description of the columns: 
- [DFOH Inference Files Documentation](https://forge.icube.unistra.fr/tholterbach/dfoh_runner/-/blob/main/README.md?ref_type=heads)

**date**: Extracted date from the DFOH reported case<br>
**status**: DFOH's inferred new edges as ***sus*** for suspicious and ***leg*** for legitimate<br>
**attacker**: The supposedly attackers<br>
**victim**: The supposedly victims;<br>
**leg_infrence_cnts**: Inferences counts that classify this new edge as legimitate;<br>
**sus_infrence_cnts**: Inferences counts that classify this new edge as suspicious;<br>
**path_cnts**: AS paths counts used for the inferencing<br>
***Additional attributes***:<br>
**type**: Hijacking types (type 1, 2 etc);<br>
**valid_origin**: True if the origin of the route with the new edge is valid, False otherwise;<br>
**recurrent**: True if its a recurrent case; <br>
**local,inference_id**: Created from the inference sequences;<br>
**leg_flag**: Not sure what these mean yet; **sus_flag**: Not sure what these mean yet
