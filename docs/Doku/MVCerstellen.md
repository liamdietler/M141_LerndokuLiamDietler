# MVC Erste Schritte:

> * Model

* Als erstes Model erstellen. Beispiel:

```php

    class Lernender{
        public $name;
        public $klasse;

    }


```

> * Controller

* Als nächstes muss der Controller erstellt werden. Beispiel:

```php

class lernende extends Controller{

    public function index()
    {
        echo 'contact/index';
    }


    public function create($pName, $pKlasse)
    {
        $lernender = $this->model('Lernender');
        $lernender->name = $pName;
        $lernender->klasse = $pKlasse;

        $this->view('lernender/index', ['name'=> $lernender->name, 'klasse'=>$lernender->klasse]);
    }

}
```
