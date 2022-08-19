# MCA Architecture
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Section-1

- [Section-1a](section-1/section-1a)
- [Section-1b](section-1/section-1b)

## Section-2

- [Section-2a](section-2/section-2a)
- [Section-2b](section-2/section-2b)

## Section-3

{% assign section-3_groups = site.pages
  | where: "section-3", true %}

{% for section-3 in section-3_groups %}
- [{{ section-3.title }}]({{ section-3.url | relative_url }})
{% endfor %}

## Section-4

{% assign section-4_groups = site.pages
  | where: "section-4", true %}

{% for section-4 in section-4_groups %}
- [{{ section-4.title }}]({{ section-4.url | relative_url }})
{% endfor %}

## Section-5 ##

- [Section-5a](section-5/)

## Section-6

- [section-6a](section-6/section-6a)

## Section-7

- [External links here](https://www.gov.uk/government/organisations/maritime-and-coastguard-agency)
