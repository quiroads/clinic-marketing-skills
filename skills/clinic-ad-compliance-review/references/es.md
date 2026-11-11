# Spain: health advertising rules for clinics

Reference file of the skill `clinic-ad-compliance-review`. Read it only for a clinic in Spain, after the SKILL.md. Certainty is high unless marked medium; the phrases to flag are in the blocks under each section, and the source codes are listed at the end with their full URLs.

Rules checked: November 2026

## 1. First: who the clinic is

- **Chiropractic and osteopathy are not regulated health professions in Spain.** The LOPS lists the regulated ones (medicine, pharmacy, dentistry, nursing, physiotherapy, podiatry and others), and neither is there [ES4 art. 2].
- **There is no chiropractic or osteopathy unit** in the national list of health-centre units [ES5 Annex II]. The nearest units need regulated professionals: U.59 Fisioterapia (a physiotherapist), U.48 Medicina estética and U.101 Terapias no convencionales (a physician). So a centre with only chiropractors or osteopaths generally can't be an authorised health centre (inference, medium).
- **Physiotherapy, dental and medical clinics** can be authorised for their units, and their professionals are regulated: they may use health terms for the units they're authorised for, with their registration number (S1), and also carry the duties of regulated professionals (S11).
- **Status unknown after asking once:** review it as a centre that is not authorised, and say so.

## 2. Health advertising (RD 1907/1996, RD 1277/2003, LOPS)

It covers advertising «directa o indirecta, masiva o individualizada» of services with a claimed health purpose [ES1 art. 1]: ads, landing pages, organic posts and one-to-one WhatsApp sales messages.

| # | Rule | Source |
|---|---|---|
| S1 | Only authorised health centres may use words that suggest health activity. Their ads keep to the authorised services and show the registration number from the regional health authority (or the number of a specific health-advertising authorisation). A centre that isn't authorised: flag every word that implies health activity. The law doesn't list the words: treat treatment, patient, diagnosis, therapy and named conditions as high risk (medium on the word list). | ES5 art. 6.2; ES8 (Madrid, Decreto 51/2006 art. 21 b)) |
| S2 | Advertising only the services covered by the authorisation; anything else needs prior authorisation from the health authority (also beauty, slimming and aesthetic centres). | ES1 art. 6 |
| S3 | No promise of certain relief or cure («seguridades de alivio o curación cierta»). | ES1 art. 4.4 |
| S4 | No testimonials from patients, real or supposed, from health professionals or from famous people. High in ads and sales messages; medium for review widgets on the clinic's own website. Remove them, don't just check them; offer neutral facts instead (years open, practitioners, qualifications). | ES1 art. 4.7 |
| S5 | A specific therapeutic or preventive claim needs evidence expressly recognised by the State health administration. Rule high. For chiropractic and osteopathy no such evidence has been recognised: the 2019 pseudotherapies plan lists both as still under evaluation, with no report since. That reading is medium, so for them S5 alone is «Riesgo»: describe the method and the assessment, not effects on conditions. | ES1 art. 4.16, ES6 |
| S6 | No claim to treat serious diseases: cancer, diabetes, insomnia, communicable diseases (art. 4.1); no slimming claims (art. 4.2); nothing that makes medicines unnecessary (art. 4.14) or replaces seeing a health professional (art. 4.15). | ES1 arts. 4.1, 4.2, 4.14, 4.15 |
| S7 | «Natural» never tied to a preventive or therapeutic effect. | ES1 art. 4.13 |
| S8 | No authorisation, approval or use in health centres shown as an endorsement; no claim of better physical or sports performance. The registration number of S1 is information, not a quality seal (medium on that boundary). | ES1 arts. 4.5, 4.6, 4.12 |
| S9 | Anyone who appears to be a health provider without being one is bound by the same bans; health professionals don't lend their name to such ads. | ES1 arts. 5.1, 5.3 |
| S10 | Agencies and media must not accept advertising that breaks the decree; breaches of its arts. 4 to 6 can be serious infringements. If the user works for an agency, tell them the agency is bound too. | ES1 arts. 7.2, 8.2; ES2 arts. 27, 30 |
| S11 | Regulated professionals (physio, dental, medicine) advertise objectively, prudently and truthfully, without false hopes; nothing without evidence of benefit, no «productos-milagro», no belief-based services. | ES4 art. 44 |
| S12 | No titles the practitioner doesn't hold, or names that could be confused with them. «Dr.» for a chiropractor isn't addressed in Spanish law (medium): ask before using it. | ES4 art. 4.2, DA 2ª |
| S13 | An ad that breaks these rules is unlawful advertising: cite this as the legal hook. | ES3 art. 3 |
| S14 | AUTOCONTROL's code (self-regulation, medium): true testimonials with written authorisation, proof of every claim, no exploiting fear or suffering, «garantía» not misleading, no aggressive or disguised advertising. Cite and link it; never paste its text. | ES14 |

**Severity in Spain.** S1's word list, S5 for chiropractic and osteopathy, S12's «Dr.» and S14 are medium: a phrase that breaks only those is «Riesgo». It is «Impide publicar» when a high rule also applies to it (S3, S4, S6, S7, S15, or a high platform rule such as P1).

<!-- flag-examples:start -->
- S1: «tratamiento», «paciente», «diagnóstico», «terapia», «clínica médica»
- S3: «elimina tu dolor», «solución definitiva», «resultados garantizados», «100 %»
- S4: «Ana volvió a correr gracias a nosotros»
- S5: «corregimos tu columna», «corregimos la hernia», «la quiropráctica soluciona la ciática»
- S6: «sin fármacos», «deja los analgésicos», «evita el quirófano», «no necesitas ir al médico», «alternativa al fisio», «adelgaza», «duerme sin insomnio»
- S7: «tratamiento natural para…», «forma natural de curar»
- S8: «avalado por Sanidad», «técnica usada en hospitales», «mejora tu rendimiento deportivo»
- S9, S12: «Dr.», «fisioterapeuta», «médico», «sanitario»
- S11: «milagro», «energía», «sanación»
- S14: «¿Tu espalda se está degenerando?»
<!-- flag-examples:end -->

S1's words count for a centre that isn't authorised. S4 also covers a patient's story, star-rating quotes and patient videos. S9 and S12 also cover a white coat with medical cues, and «Dr.», «fisioterapeuta», «médico» or «sanitario» used for a chiropractor or osteopath without that title.

## 3. Consumer law, reviews and lead forms

| # | Rule | Source |
|---|---|---|
| S15 | Falsely claiming that a service can cure illnesses, dysfunctions or malformations is always unfair. | ES17 art. 23.3; EU1 Annex I no. 17 |
| S16 | No false «limited time» claim: «solo hoy», countdowns and «últimas plazas» only if true, with evidence. | ES17 art. 23.4 |
| S17 | «Gratis», «regalo» or «sin coste» only if the patient pays nothing: a free first visit that charges for X-rays or tests, or depends on buying a bono, breaks it. | ES17 art. 22.5 |
| S18 | A stated price is the full final price, taxes and extra charges included, with the essential characteristics; a bono shows sessions, validity and key conditions next to the price; nothing material hidden in small print. Art. 20.1 c) has new wording from RDL 32/2026, whose approval by Congress wasn't verified. | ES16 art. 20; ES17 arts. 5, 7 |
| S19 | A page that shows reviews says whether and how the clinic checks they come from real patients. Since 28/12/2025, reviews must be about services used in the previous 30 days (high on the text, medium on enforcement). Fake, commissioned or distorted reviews are always unfair. In ads, S4 still bans patient testimonials. | ES16 art. 20.4; ES17 arts. 27.7, 27.8 |
| S20 | Content that patients or influencers were paid for, in money or free sessions, is labelled as advertising. | ES17 art. 26 |
| S21 | A lead form that asks about pain or symptoms collects health data: make those fields optional or remove them, and add a separate, unticked explicit-consent box. The health-care exception doesn't cover marketing (for chiropractic and osteopathy it's unlikely to fit at all: medium). | EU2 art. 9; ES20 art. 9; EU3 |

<!-- flag-examples:start -->
- S16: «solo hoy», «últimas plazas», «oferta limitada»
- S17: «primera visita gratis», «gratis al contratar tu bono»
<!-- flag-examples:end -->

S16's phrases are a problem only when they aren't true; S17's first one, when something is charged (X-rays, tests) or a bono must be bought.

## 4. Regional rules

| Region | Rule | Source |
|---|---|---|
| Euskadi | Every health ad needs prior authorisation, including ads from centres that aren't health centres; the authorisation number appears on every ad. A health centre shows the qualification of the professional responsible; any other centre says «CENTRO NO SANITARIO». Don't let it launch until the clinic gives its number. Decreto 550/1991 itself wasn't read: its scope comes from the procedure page. | ES12 |
| Cataluña | Decret 203/2026 (DOGC 5 November 2026, in force 20 days after publication; Decret 151/2017, which it repeals, had equivalent rules): authorised centres advertise only their authorised activity and include their registry code; any other advertising is evaluated and authorised beforehand, except advertising about activities that aren't health activities; the trade name doesn't mislead about the authorised activities; shared multi-practitioner spaces don't present themselves as one health centre. | ES10 art. 5 |
| Madrid | Show the registration number (Decreto 51/2006 art. 21 b), quoted on the regional page); advertising beyond the authorisation needs prior authorisation. A draft decree that would add a health-advertising commission is pending, not approved. | ES8; ES9 |
| Andalucía | Show the registration number; a misleading ad, or one beyond the authorisation, is a serious infringement (original 2008 text; later amendments not checked). | ES11 |
| Comunitat Valenciana | No regional pre-approval of medical advertising since 2014 (medium: the regional health law wasn't read); the state rules apply. | ES13 |
| Other regions | Not checked: apply the state rules and say the region wasn't checked. | — |

## 5. What a Spanish chiropractic or osteopathy ad can say (medium)

The practical reading of S1 to S12 for a centre that isn't authorised:

- what the first visit includes, who the practitioner is and their real qualification, the price and conditions, the place and how to book;
- no condition claims, promises, testimonials, «natural» or medicines and surgery made to look unnecessary;
- the authorisation or registration number where one exists; in Euskadi, the «CENTRO NO SANITARIO» label.

## 6. High-risk words in Spanish chiropractic ads

Two groups, presented differently.

**Internal criterion, not law.** These four words are kept out of Spanish chiropractic ads by this skill's own criterion, not law. In the report call it «lista de palabras de riesgo alto (criterio interno, no es ley)» and grade it «Riesgo».

<!-- flag-examples:start -->
- «dolor», «dolores», «migraña», «migrañas»
<!-- flag-examples:end -->

**High risk under S1 and S5.** For a centre that isn't authorised, these words suggest health activity (S1, medium on the word list); next to a promise or a condition they make a therapeutic claim (S5). Cite S1 or S5 for them, not the internal criterion.

<!-- flag-examples:start -->
- «curar», «cura», «curación», «sanar», «enfermedad», «enfermedades», «diagnóstico», «diagnosticar», «ciática», «hernia», «hernias», «lumbalgia», «cervicalgia», «escoliosis», «contractura», «contracturas», «lesión», «lesiones»
<!-- flag-examples:end -->

An authorised centre may use health terms for its own units, although condition promises are still banned (S3, S5). Alternatives: «molestias», «bienestar», «moverte mejor»; «plan de cuidados» instead of «tratamiento».

## 7. Safer patterns in Spanish

| Type | Safer pattern |
|---|---|
| Promise or condition claim | «En la primera visita valoramos tu caso y te explicamos las opciones.» |
| Testimonial | «[años] en [ciudad] · [número] profesionales · [titulación].» |
| «Sin fármacos», «sin cirugía» | Remove it; if needed, «Complementa, no sustituye, la atención médica.» |
| Question about a condition | «Quiropráctica en [ciudad]: primera visita con valoración postural, [precio].» |
| «Natural» | «Ajustes manuales, sin aparatos.» (only if true) |
| Free visit | «Primera visita sin coste: incluye [qué]; no hace falta contratar nada más.» (only if true) |
| Mandatory line | «Nº de registro sanitario: [número]» (authorised centre); «CENTRO NO SANITARIO» (Euskadi). |

## 8. Not verified

- No reform of RD 1907/1996 confirmed; the BOE text is unchanged since 1996.
- Whether its art. 4 applies to the services of an authorised centre (and not only to «métodos») isn't confirmed by case law; this file treats it as applying.
- Before-and-after images: no explicit state rule found; they fall under S3 and S4.
- Professional codes of physiotherapists, dentists and doctors on advertising weren't read.
- Regions other than those in section 4, and regional case law on chiropractic ads.

## Sources

- [ES1] Real Decreto 1907/1996 (publicidad con pretendida finalidad sanitaria): https://www.boe.es/eli/es/rd/1996/08/02/1907/con
- [ES2] Ley 14/1986, General de Sanidad: https://www.boe.es/eli/es/l/1986/04/25/14/con
- [ES3] Ley 34/1988, General de Publicidad: https://www.boe.es/eli/es/l/1988/11/11/34/con
- [ES4] Ley 44/2003, de ordenación de las profesiones sanitarias (LOPS): https://www.boe.es/eli/es/l/2003/11/21/44/con
- [ES5] Real Decreto 1277/2003 (autorización de centros sanitarios): https://www.boe.es/eli/es/rd/2003/10/10/1277/con
- [ES6] Ministerio de Sanidad, Plan de protección frente a las pseudoterapias (2019): https://www.sanidad.gob.es/gabinete/notasPrensa.do?id=4527
- [ES8] Comunidad de Madrid, vigilancia de publicidad sanitaria: https://www.comunidad.madrid/salud/vigilancia-publicidad-sanitaria
- [ES9] Comunidad de Madrid, proyecto de decreto (pending): https://www.comunidad.madrid/transparencia/proyecto-decreto-regimen-juridico-y-procedimiento-autorizacion-y-registro-centros-y-servicios
- [ES10] Decret 203/2026, Generalitat de Catalunya: https://dogc.gencat.cat/ca/document-del-dogc/?documentId=1058477
- [ES11] Decreto 69/2008, Junta de Andalucía: https://www.juntadeandalucia.es/boja/2008/52/14
- [ES12] Gobierno Vasco, autorización de publicidad sanitaria: https://www.euskadi.eus/autorizacion/autorizacion-publicidad-sanitaria/web01-tramite/es/
- [ES13] Decreto 157/2014, Generalitat Valenciana: https://dogv.gva.es/datos/2014/10/07/pdf/2014_9092.pdf
- [ES14] AUTOCONTROL, Código de Conducta Publicitaria (cite and link only): https://www.autocontrol.es/app/uploads/codigo-de-conducta-publicitaria-autocontrol.pdf
- [ES16] TRLGDCU, Real Decreto Legislativo 1/2007: https://www.boe.es/buscar/act.php?id=BOE-A-2007-20555
- [ES17] Ley 3/1991, de Competencia Desleal: https://www.boe.es/buscar/act.php?id=BOE-A-1991-628
- [ES20] Ley Orgánica 3/2018 (LOPDGDD): https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673
- [EU1], [EU2], [EU3]: the UCPD, the GDPR and CJEU C-21/23, listed in the SKILL.md's Sources.
