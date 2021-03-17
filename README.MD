```php
<?php

class Wribeiiro extends PHPDeveloper {

    public function __construct() {
        parent::__construct();

        $this->fullname = "Wellisson Luiz Antunes Ribeiro";
        $this->username = 'wribeiiro';

        $this->aboutme = "Hi Devs 🖖! I'm Wellisson Ribeiro. I'm 25 years old, married, and father of two little girls. Graduated in Analysis and Systems Development at UNOPAR. Developer with some years of experience developing applications with different technologies, but with a focus on PHP (Code Igniter, Laravel, Lumen, VueJS, Frameworks). I am currently work a software engineer at SoftExpert.";

        $this->links = [
            "linkedin" => "@wellisson-ribeiro",
            "website"  => "wribeiiro.com",
            "email"    => "welleh10@gmail.com"
        ];
        
        $this->technologies = [
            "current_working" => [
                "backend"  => ["PHP", "Codeigniter 4"],
                "frontend" => ["HTML", "CSS", "Javascript", "React"],
                "database" => ["MySQL", "SqlServer", "MariaDB", "Postgres", "Oracle"]
            ],
            "current_learning" => [
                "backend"  => ["Laravel"],
                "frontend  => ["VueJS", "React"]
            ],
            "tools" => ["Github", "Bitbucket", "Gitlab", "Jira", "Git"],
            "architecture" => ["MVC", "Webservices", "APIs"]
        ];
    }
}

$me = new Wribeiiro();

print_r($me);
