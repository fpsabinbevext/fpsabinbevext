```php
<?php
namespace App\Http\Drupal;

use Desevolvedor\FullStack\Drupal as Desenvolvedor;

class SobreMim extends Desenvolvedor {
  const NOME = 'Fernando Pereira dos Santos'
  const AREA = 'Especialista em Drupal e Laravel';
  const TRABALHO = 'Contass e Mazzatech';
  const LOCAL = 'João Pessoa, Paraíba, BR';

  public function pegaMiniBio() {
    return "Olá, meu nome é: " . self::NOME . "." . "Sou " . self::AREA . "." .
    "Trabalho hoje nas empresas: " . self::TRABALHO . "." .
    "Estou morando hoje em " . self::LOCAL . ".";
  }
}
```

<p align="left">
  <a href="https://www.linkedin.com/in/ferox/" alt="LinkedIn">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=LINK-DO-SEU-LINKEDIN" /></a>
</p>
