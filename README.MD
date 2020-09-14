# Wellisson Ribeiro 🧔🏻💻

```php
<?php

class Wribeiiro extends FullstackDeveloper {

    public function __construct() {
        parent::__construct();

        $this->fullname = "Wellisson Luiz Antunes Ribeiro";
        $this->username = 'wribeiiro';

        $this->aboutme = "I'm 24 years old, from Curitiba-PR, but I've lived in Mafra-SC since my birth, married, and father of two children. Graduated in Analysis and Systems Development at UNOPAR. Developer with some years of experience developing applications for web and desktop.";

        $this->links = [
            "linkedin" => "@wellisson-ribeiro",
            "facebook" => "@wellissonribeiiro",
            "website"  => "wribeiiro.com",
            "email"    => "welleh10@gmail.com"
        ];
        
        $this->technologies = [
            "current_working" => [
                "backend"  => ["PHP (Code Igniter 3)", "C#", "Visual Basic 5"],
                "frontend" => ["Html", "Javascript (Jquery)", "Bootstrap"],
                "database" => ["Mysql", "MSAccess"],
                "mobile"   => "Ionic"
            ],
            "current_learning" => [
                "backend"  => ["Codeigniter 4", "Laravel", "Lumen"],
                "frontend" => ["VueJS", "React"]
            ],
            "tools" => ["Github", "Bitbucket", "Git"],
            "architecture" => ["MVC", "Webservices", "APIs"]
        ];
    }
}

$me = new Wribeiiro();
