# py-cute

Hello po! Ito yung web app para sa PUP Study with Style. Simple lang to, ginawa gamit ang Python Flask at Dominate para sa pagbuo ng mga page kasi maarti prof niyo gusto pure Python haha so here di na nag django and no HTML/CSS file format.

## Ano Na Ba Meron Dito? (goods o bulok?)

*   **Login at Register:** Pwede ka gumawa ng account tapos mag-login.
*   **Tingin ng Products ni Red:** Makikita mo yung mga tinda, tulad ng lanyards at tote bags.
*   **Shopping Carts:** Pwede ka maglagay ng items sa cart (hindi yung Carts na hinihigop ah! haha).
*   **Checkout:** Simpleng proccess para "bilhin" yung nasa cart mo (pero placeholder lang muna).
*   **Profile:** Makikita mo basic info mo.
*   **Order History:** Listahan ng mga "na-order" mo (sample data lang din).
*   **Contact Us:** Pwede ka magsend ng message (sample lang din).
*   **Admin Inventory:** Para sa admin, makikita at (future) manage yung mga produkto.

## Paano Gagawin Ko Dito!? (Steps)

Sundan lang to para mapagana mo sa laptop mo benz (P.S. Di ako sure lalo't Windows and iyong OS).

**Kailangan Mo Muna:**

1.  **Python:** Dapat meron kang Python (version 3.8 pataas siguro okay na).
2.  **Pip:** Pang-install ng mga kailangan na packages.

**Mga Steps:**

1.  **Download or Clone:**
    *   Kung na-download mo as ZIP, i-extract mo.
    *   Kung Git, i-clone mo: `git clone https://github.com/Golgrax/py-cute.git` gawin mo yung ginagawa ko sa terminal.

2.  **Punta sa Folder:**
    *   Buksan mo yung terminal or command prompt.
    *   Pumunta ka sa `py-cute` folder. Example: `cd path/to/py-cute` (or back-slash kasi Windows ka, sorry IDK)

3.  **Install ng mga Kailangan (Dependencies):**
    *   Sa terminal, type mo to tapos Enter:
        ```bash
        pip install Flask dominate Werkzeug click
        ```
    *   Hintayin mo lang matapos mag-install.

4.  **Setup ng Database (Isang Beses Lang sa Simula):**
    *   Sa `py-cute` folder pa rin, type mo to sa terminal tapos Enter:
        ```bash
        flask --app pup_study_style:create_app init-db
        ```
    *   Gagawa yan ng database file at maglalagay ng ilang sample na produkto. Dapat may makita kang "Initialized the database" messages.

5.  **Patakbuhin ang App:**
    *   Sa terminal pa rin, type mo to tapos Enter:
        ```bash
        python run.py
        ```
    *   May makikita kang message na parang ganito: `* Running on http://127.0.0.1:5000/` (or same).

6.  **Buksan sa Browser:**
    *   Buksan mo yung web browser mo (Chrome, Firefox, etc.).
    *   Punta ka sa address na lumabas sa terminal, or shift+click`http://127.0.0.1:5000/`.
    *   Ayun! Dapat makita mo na yung login page.

## Mga Folder at Files (Para Alam Mo Lang)

*   `pup_study_style/`: Dito nakalagay yung mismong code ng app.
    *   `__init__.py`: Parang pinaka-setup ng app.
    *   `db.py`: Para sa database.
    *   `ui_utils.py`: Mga tulong sa paggawa ng itsura ng page.
    *   `*_routes.py`: Dito yung mga code para sa iba't ibang parte ng website (login, products, etc.).
    *   `static/`: Dito yung mga images (`assets/` [click mo 'to](https://github.com/Golgrax/py-cute/tree/main/pup_study_style/static/assets) ) at custom font (`RocaOne.ttf`).
*   `schema.sql`: Itsura ng database tables.
*   `run.py`: Pang-start ng app.
*   `README.md`: Ito yung binabasa mo ngayon. :)

## Sa Susunod (Future Improvements)

*   Mas ayusin yung style and pwede kalabasan ng webapp (next time gamit kayo wireframes and webframes like figma etc para di mahirap gayahin yung design and sure na possible).
*   Totoong cart at order processing sa shop ni red.
*   Functionality sa admin page.
*   ilagay lahat ng pics sa assets/ (or kayo na kasi nakakatamad haha.)

### GOOD LUCK GUYS!
