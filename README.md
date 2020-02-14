# COVID-19 South Korea

Public line list and summaries of the COVID-19 outbreak in South Korea. Translated and transcribed by Sang Woo Park.

Sources:
* KCDC press release: https://www.cdc.go.kr/board/board.es?mid=a20501000000&bid=0015
* Official Website of the Seoul Metropolitan Government: http://news.seoul.go.kr/welfare/archives/513105

contact: swp2@princeton.edu
twitter: @sang_woo_park

# Spreadsheet

Google sheets:

Last updated at 3:14 PM EST February 14, 2020 

### Sheet 1 -- Line list

* `case`: case identifier
* `ncontact`: number of contactees
* `nquaratine`: number of contactees that are under quarantine
* `age`: age
* `sex`: sex
* `date_contact_min`: minimum date on which a patient could have been infected (e.g., after their infectors were imported, etc.)
* `date_contact_max`: maximum date on which a patient could have been infected (e.g., before symptom onset, before self-quarantine, before their infectors were confirmed to be infected, etc.)
* `date_import`: date of import
* `date_onset`: date of symptom onset
* `date_qurantine`: the first date of quarantine
* `date_self_qurantine`: the first date of self-quarantine
* `date_home_before_quarantine`: date on which a patient stayed home all day before they were quarantined; KCDC uses 'stayed home all day' with 'self-quarantine' interchangably in some cases.
* `date_confirm`: date of confirmation
* `source`: sources of infection
* `import_source`: sources of importation
* `date_recovery`: date on which a patient recovered
* `symptoms`: symptoms reported prior to confirmation
* `preexisting_conditions`: preexisting conditions prior to infection
* `KCDC_no`: article number on the KCDC website: https://www.cdc.go.kr/board/board.es?mid=a20501000000&bid=0015
* `date_last_accessed`: date on which articles were last accessed and the information was modified

### Sheet 2 -- Cumulative case counts

* `date`: date
* `suspected cases`: cumulative number of suspected cases
  * 2020-01-20 --- 2020-01-25: anyone who develops fever or respiratory symptoms within 14 days of returning from Wuhan
  * 2020-01-26 --- 2020-02-06: ianyone who develops pneumonia (based on radiological evidence) within 14 days after returning from China
  * 2020-02-07 --- now:
    * Anyone who develops fever or respiratory symptoms within 14 days of returning from China
    * Anyone who develops fever or respiratory symptoms within 14 days of having a close contact with a confirmed case
    * Anyone suspected of COVID-19 by a clinician based on travel history and clinical symptoms
* `positive`: cumulative number of positive cases
* `negative`: cumulative number of negative cases
* `unknown`: number of individuals still under a test
* `KCDC_no`: article number on the KCDC website: https://www.cdc.go.kr/board/board.es?mid=a20501000000&bid=0015
* `note`: miscellaneous notes

### Sheet 3 -- Important dates

* `date`: date
* `event`: event
* `note`: miscellaneous notes
* `KCDC_no`: article number on the KCDC website: https://www.cdc.go.kr/board/board.es?mid=a20501000000&bid=0015

# Summary figures

### Epidemic curves

![Epidemic curves](https://github.com/parksw3/COVID19-Korea/blob/master/figure_epidemic.png)

### Summaries

![Summaries](https://github.com/parksw3/COVID19-Korea/blob/master/figure_patient_summary.png)
