# Introduction

This project is for multilingualization of symbols-tools.com applications.

# Folder structure

    resources/  
      |-- web/                                        *Arrange common language settings for HTML files.
      |     |-- tool/                                 *Place the language setting of the HTML file under Tool.　　
      |     |     |-- label.properties                *Default language file. (English)　　
      |     |     |-- label_**.properties             *[locale] language file.
      |     |  
      |     |-- label.properties                      *Default language file. (English)　　
      |     |-- label_**.properties                   *[locale] language file.　
      |  
      |-- app.properties                              *Individual configuration file. Default language file.(English)  
      |-- app_**.properties                           *Individual configuration file. [locale] language file.  
      |-- appMessages.properties                      *Messages configuration file. Default language file.(English)  
      |-- appMessages_**.properties                   *Messages configuration file. [locale] language file.  
