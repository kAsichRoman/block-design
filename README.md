#float еряет свои параметри висота = 0, в родительском блоке.
Решение:
name_of_parent_element::after {
	content: "";
	clear: both;
	display: block;
}
