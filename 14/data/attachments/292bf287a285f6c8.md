# Page snapshot

```yaml
- generic [ref=e3]:
  - banner [ref=e4]:
    - generic [ref=e5]:
      - img "Logo" [ref=e7] [cursor=pointer]
      - button [ref=e8] [cursor=pointer]:
        - img [ref=e9]
  - generic [ref=e12]:
    - generic [ref=e13]:
      - heading "Attendee List" [level=1] [ref=e14]
      - paragraph [ref=e15]: Browse all event attendees and send invitations
    - generic [ref=e17]:
      - generic [ref=e19]:
        - img [ref=e21]
        - textbox "Search by name, company, job title, or country..." [ref=e23]
        - group
      - generic [ref=e24]:
        - generic [ref=e25]: Per Page
        - generic [ref=e26]:
          - combobox "Per Page" [ref=e27] [cursor=pointer]: "20"
          - textbox: "20"
          - img
          - group:
            - generic: Per Page
    - progressbar [ref=e29]:
      - img [ref=e30]
```