# Let's Get **Started**

---

### Add Some Slide Candy

![IMAGE](assets/img/presentation.png)

## Customize the Layout

---

#### Engage your Audience

- You will be amazed
- What you can achieve
- With a **little imagination**
- And GitPitch Markdown


---


```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```



