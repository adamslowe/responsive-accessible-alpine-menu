- Project Setup
- Structure & Markup
- Styling
- WP Actions
- Main Menu Dropdown
- Mobile Menu Dropdown
- Mobile Panel

--- Limitations ---
- aria-controls does not work

--- Main Menu Dropdown ---
- li action 
    - Hide submenu on mouse leave
    - Hide submenu by esc key
    - Show submenu on mouseenter
    - Show Submenu Actions 
        - SUBMENU -> Opactity 1
        - SUBMENU -> rcls hidden
        - BUTTON -> aria-expanded = true
        - LI -> acls menu-opened
    - Hide Submenu Actions
        - SUBMENU -> Opactity 0
        - SUBMENU -> acls hidden
        - BUTTON -> aria-expanded = false
        - LI -> rcls menu-opened

- Button action 
    - Show submenu on click or enter key
    - Hide submenu by kbd top menu item

- Submenu 
    - Hide at start