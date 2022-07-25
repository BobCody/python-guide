# MY GUIDE FOR PYTHON DEV

## MODULES

```pip install package-name```

```pip uninstall package-name```

список пакетов:
```pip list```

### PIP
установка:
```sudo dnf install python3 python3-wheel```  
обновить: 
```pip install -U pip```

### ENV

Создание новой виртуальной среды внутри каталога: 
```python3 -m venv myenv```

```
├── bin
│   ├── activate
│   ├── activate.csh
│   ├── activate.fish
│   ├── easy_install
│   ├── easy_install-3.5
│   ├── pip
│   ├── pip3
│   ├── pip3.5
│   ├── python -> python3.5
│   ├── python3 -> python3.5
│   └── python3.5 -> /Library/Frameworks/Python.framework/Versions/3.5/bin/python3.5
├── include
├── lib
│   └── python3.5
│       └── site-packages
└── pyvenv.cfg
```
bin – файлы, которые взаимодействуют с виртуальной средой; 

include – С-заголовки, компилирующие пакеты Python; 

lib – копия версии Python вместе с папкой «site-packages», в которой  установлена каждая зависимость.

```source env/bin/activate```

```deactivate```

### JUPITER