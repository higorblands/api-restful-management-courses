# DRF-API-RESTFul API for management courses with View


### Some Case Scenarios

* Tested API authentication endpoint validations.
* Tested authenticated user authorization. 
* Create with API.
* Update with API.
* Update with API.
* Delete with API.
* Get list for a user.
* Override Update to record the atualization Cursos field.
* Pagination.

### API Endpoints


* **api/v1/** (API V1 Version)
* **api/v2/** (API V2 Versiond)

* **/api/v1/cursos/** (Endpoint API V1 to access Cursos)
* **/api/v2/cursos/** (Endpoint API V2 to access Cursos)
* **/api/v1/avaliacoes/** (Endpoint API V1 to access Avaliacoes)
* **/api/v2/avaliacoes/** (Endpoint API V2 to access Avaliacoes)


### Install 

    pip install -r requirements.txt
    SET DJANGO_SETTINGS_MODULE=escola.settings
    python manage.py makemigrations
    python manage.py migrate
	
### Usage

    python manage.py runserver
    
Enjoyt it !
