```php
<?php

class Wribeiiro extends PHPDeveloper {

    public function __construct() {
        parent::__construct();

        $this->fullname = "Wellisson Luiz Antunes Ribeiro";
        $this->username = 'wribeiiro';

        $this->aboutme = "I'm 25 years old, from Curitiba-PR, but I've lived in Mafra-SC since my birth, married, and father of two children. Graduated in Analysis and Systems Development at UNOPAR. Developer with some years of experience developing applications for web and desktop.";

        $this->links = [
            "linkedin" => "@wellisson-ribeiro",
            "website"  => "wribeiiro.com",
            "email"    => "welleh10@gmail.com"
        ];
        
        $this->technologies = [
            "current_working" => [
                "backend"  => ["PHP", "Codeigniter 4"],
                "frontend" => ["HTML", "CSS", "Javascript", "Jquery", "Bootstrap"],
                "database" => ["MySQL", "MariaDB", "Postgres"]
            ],
            "current_learning" => [
                "backend"  => ["Laravel", "Lumen", "Python"],
                "frontend" => ["VueJS", "React"]
            ],
            "tools" => ["Github", "Bitbucket", "Git", "Gulp"],
            "architecture" => ["MVC", "Webservices", "APIs"]
        ];
    }
}

$me = new Wribeiiro();

print_r($me);
