# Become the one of Nong Program Lover

> รับชมเว็บบล็อกออนไลน์ได้ที่ https://ramut-group.github.io/nong-program/

ยินดีต้อนรับทุกท่านสู่ Repository รูปแบบใหม่ที่อยากจะพัฒนาให้กลายเป็นศูนย์กลาง ของการเรียนรู้โปรแกรมเบื้องต้น โดยออกแบบเนื้อหาสำหรับผู้ที่เริ่มต้นใหม่หรือนักศึกษา/นักเรียนที่เรียนมีเนื้อหาที่เกี่ยวข้องกับการเขียนโปรแกรม

เราก็จะมีการใช้ชื่อเรียกว่า `น้องโปรแกรม` ให้เหมือนโปรแกรมมีตัวตนขึ้นมาจริงๆ เพราะความเชื่อที่ว่าหมาแมวทุกวันนี้อยู่รอดได้เพราะ `ความน่ารัก` เลยมีคนเลี้ยงดูอย่างดีราวกับเราเป็นทาสไปซะเอง ก็เลยอยากจะทำให้น้องโปรแกรมดูเหมือนมีตัวตนที่แฝงความน่ารักน่าชังจากความดื้อของเขา ไม่ว่าจะบัค จะเขียนโปรแกรมยากขนาดไหน ต้องป้อนอินพุทไปเท่าไหร่ถึงจะอิ่ม เราก็จะพยายามเพื่อเขา จนเรากลายเป็น `ทาสน้องโปรแกรม` ไปแบบไม่รู้ตัว

> ทางเรายินดีให้ใช้ Repository นี้เป็นส่วนหนึ่งของ Senior Project ของระดับอุดมศึกษา เพื่อการพัฒนาเนื้อหาการเรียนรู้ของการเขียนโปรแกรมต่อๆไป

## How to Countribute

- สามารถร่วมเขียนบทความได้โดยทำการ `Fork` จากนั้นทำการ `Push` ขึ้น `Branch` ใดๆก็ตาม และทำการ `Pull Request` เพื่อให้ทาง Contributor สามารถรีวิวและตอบถามความเห็นได้ก่อน
- สามารถร่วมเขียนบทความอีกทางได้ โดยการเข้าร่วมเป็นส่วนหนึ่งของ Contributor จาก [ramut-group](https://github.com/ramut-group) ได้โดยการส่งเมลพูดคุยกับเจ้าของได้ที่ `nakorndev@gmail.com`
- สามารถร่วมแก้ไขบทความที่มีความผิดพลาด โดยไม่ต้องทำการ Pull Request โดยการเปิด `Issues` ใหม่ เพื่อพูดคุยกันก่อนทำการแก้ไขปัญหาของเนื้อหา

## Usage

เราใช้ [Jekyll](jekyllrb.com) และ [GitHub Pages](https://pages.github.com) ในการเขียนบล็อกขึ้นมา เพื่อให้รองรับการแก้ไขจากผู้อื่น และยังเป็นการเขียนบทความที่เหมาะแก่โปรแกรมเมอร์อย่างมากด้วยการใช้ `Markdown` หรือ `HTML` ในการเขียนเนื้อหา ดังนั้นการใช้งานจึงควรมีพื้นฐานการใช้งาน `Jekyll` ด้วย

> ศึกษาเพิ่มเติมได้ที่ https://jekyllrb.com/docs/quickstart/

## Requirement

- [Ruby](https://rubyinstaller.org/downloads/) >= 2.2.5
- ruby2.3-dev
- [RubyGems](https://rubygems.org/pages/download) >= 2.7.6
- [Jekyll](https://jekyllrb.com/) >= 3.7.3
- [Bundler](http://bundler.io/) >= 1.16.1
- GCC และ Make

> สำหรับระบบ Windows อาจจะไม่มี GCC หรือ Make สามารถใช้ http://www.mingw.org/ และ http://gnuwin32.sourceforge.net/packages/make.htm

## Installation

หลังจาก Clone เข้าสู่เครื่องแล้ว ใช้คำสั่ง `bundle` เพื่อติดตั้ง Package ที่จำเป็นของ Jekyll

```bash
$ bundle install
```

จากนั้นทำการ `serve` ไปยัง http://127.0.0.1:4000/nong-program โดยใช้คำสั่งนี้

```bash
$ jekyll serve
```

หรือ

```bash
$ bundle exec jekyll serve
```

> หากมีปัญหาใดๆ ลองตรวจสอบได้ที่ https://jekyllrb.com/docs/installation/ หรือ https://jekyllrb.com/docs/troubleshooting/

## Rules & Formatting

ในส่วนนี้จะเป็นวิธีการแก้ไขหรือเพิ่มเติมข้อมูล โดยเราจะมีส่วนที่อนุญาตหรือไม่อนุญาตในการแก้ไข ดังนั้นกรุณาอ่านให้ละเอียดก่อนทำการแก้ไขเนื้อหาและทำการ Pull Request เพื่อให้การรีวิวเนื้อหาเป็นไปได้อย่างรวดเร็ว

โดยเราจำกัดขอบเขตบางอย่างเพียงเพื่อให้มีความเรียบร้อยของ Repository แต่ส่วนของเนื้อ และวิธีการอธิบาย หรือแม้กระทั่งการใช้เชิงพานิชย์เชื่อมโยงไปยังลิงก์ที่เกี่ยวข้องที่มีประโยชน์ เราก็ยินดีมอบให้แก้ไขอย่างอิสระเสรี แต่ก็ต้องดูไม่น่าเกลียดมากเกินไป

- Read only หมายถึงอนุญาตให้เรียกใช้หรืออ่านไฟล์ได้อย่างเดียว
- Edit only หมายถึงอนุญาตให้แก้ไขได้ แต่ไม่ให้เพิ่มไฟล์ (สำหรับ Directory)
- Editable หมายถึงอนุญาตให้แก้ไขได้ (สำหรับ File)
- Full access หมายถึงอนุญาตให้แก้ไข เพิ่มเติม และลบไฟล์ได้

### Markdown

ทุกๆไฟล์ `.md` ที่แก้ไขจะต้องมีโค้ดดังต่อไปนี้อยู่บนส่วนหัวสุด ตามตัวอย่างไฟล์อื่นๆ เพื่อให้ Jekyll ทำการ Build เอกสารออกมาอย่างถูกต้อง โดยไม่จำเป็นต้องเพิ่ม Variable ใดๆ เนื่องจากเราได้ตั้งไว้บน `_config.yml` ไว้เรียบร้อยแล้ว

```
---
---
```

### Editor

กรุณาเลือกใช้ Text Editor ที่รองรับ [EditorConfig](http://editorconfig.org/) โดยทางเราแนะนำให้เลือกใช้ [Visual Studio Code](https://code.visualstudio.com/) ร่วมกับ Extension: [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) เพื่อให้ทุกส่วนของเนื้อหามีโครงสร้างและรูปแบบการเขียนที่ตรงกันกับทุกคน

### Directory

| Directory | Meaning | Usage | Permit |
| --- | --- | --- | --- |
| `/_awesome/` | Awesome Pages | สำหรับเก็บ Awesome Lists โดย ramut และบุคคลที่สนใจลงลิงก์ที่มีประโยชน์ | Edit only |
| `/_data/` | Global YAML data | สำหรับเก็บข้อมูลและตัวแปร ที่จำเป็นนำมาใช้กับบล็อก | Read only |
| `/_docs/` | Documentation Pages | สำหรับเก็บ Documentation หลักโดย URL จะถูกเรียกเป็น `/docs/:path/` และบังคับให้ `.md` เป็นหลัก โดยใช้ชื่อไฟล์เป็นภาษาอังกฤษเท่านั้น และต้องมีความหมายตรงกับเนื้อหา | Full access |
| `/_includes/` | Components | สำหรับใช้งานเป็น Components ที่ถูกเรียกใช้งานในหน้าอื่นๆผ่าน `{% include filename.html %}` | Read only |
| `/_layouts/` | Layout, Template | สำหรับเรียกใช้งาน Layouts ผ่านตัวแปล `layout` ใน `YAML` | Read only |
| `/_news/` | News Pages | สำหรับเขียนข่าวสารในรูปแบบ Posts โดยต้องมีไฟล์ชื่อ `YYYY-MM-DD-TITLE.md` ที่ถูกต้อง และมี `date` ภายใน `YAML` ถูกกำกับตาม Timezone ที่ถูกต้องเป็น `YYYY-MM-DD HH:MM:SS +0700` | Read only |

### File

| File | Meaning | Usage | Permit |
| --- | --- | --- | --- |
| `/_awesome/*.md` | Awesome file | สำหรับเนื้อหาลิงก์ที่มีประโยชน์ทั้งหมด โดยจะถูกแบ่งหัวข้อไว้ตาม Filename | Editable |
| `/_data/contributors.yml` | Contributors list | สำหรับเก็บข้อมูลผู้เขียน เพื่อเก็บไว้เป็น Credit บนหน้าแรก | Editable |
| `/_data/docs.yml` | Documents list | สำหรับเก็บข้อมูล และ URL ที่เข้าถึง Documentation กับการจัดลำดับของเนื้อหา | Editable |
| `/_docs/*/*.md` | Document file | สำหรับเนื้อหาเอกสารทั้งหมด โดยจะถูกเรียงหัวข้อใหญ่ไว้ตาม Directory และหัวข้อรองเป็น Filename | Editable |

> ทุกๆไฟล์ที่ไม่ได้อยู่ในรายการ จะไม่อนุญาตให้แก้ไขได้

สำหรับ `contributors.yml`

```yml
- realname_th: # ชื่อจริง เป็นภาษาไทย ไม่ต้องมีคำนำหน้า
  realname_en: # ชื่อจริง เป็นภาษาอังกฤษ ไม่ต้องมีคำนำหน้า
  quote: # พื้นที่สำหรับอธิบายตัวตนของคุณ อนุญาตให้ใช้ HTML ได้บางส่วน เช่น a tag
  image: # ที่อยู่รูปภาพของ Avatar เป็นรูปแบบพร้อม http:// หรือ https:// ที่ถูกต้อง (แนะนำให้ใช้ Gravatar ตามตัวอย่างบนไฟล์)
  github: # ID GitHub (ไม่จำเป็น)
  facebook: # ID Facebook (ไม่จำเป็น)
  twitter: # ID Twitter (ไม่จำเป็น)
  penname: # ชื่อเพื่อแสดงผลชื่อผู้ใช้หรือนามปากกาที่คุณใช้เป็นหลัก
```

> Gravatar จะต้องใช้ Email ที่ได้รับการ Hash MD5 สามารถใช้ http://www.md5online.org/md5-encrypt.html และใช้ URL เป็น `https://www.gravatar.com/avatar/yourMD5Hashed`

สำหรับ `docs.yml`

```yml
- title: # ชื่อหัวข้อ
  url: # URL of directory name (อนุญาตเฉพาะ a-z, 0-9 และ - เท่านั้น)
  docs:
  - title: # ชื่อหัวข้อรอง 1
    url: # URL of Filename (อนุญาตเฉพาะ a-z, 0-9 และ - เท่านั้น และไม่ต้องมี .md หรือ .html)
  - title: # ชื่อหัวข้อรอง 2
    url: # URL of Filename (อนุญาตเฉพาะ a-z, 0-9 และ - เท่านั้น และไม่ต้องมี .md หรือ .html)
    # ...
```

> การจัดเรียงจะมีผลต่อลำดับเนื้อหาเอกสาร ดังนั้นจำเป็นต้องใช้เนื้อหาที่เหมาะแก่ผู้เรียนรู้ตามลำดับ

## License

เนื้อหาทั้งหมดจะถูกคุ้มครองลิขสิทธิ์ในรูปแบบ [MIT license](https://www.gnu.org/licenses/lgpl-3.0.en.html) โดยทางเราอนุญาตให้คัดลอก ทำซ้ำ ดัดแปลงเนื้อหาได้อย่างอิสระ แต่ทางเราจะไม่มีการรับประกันใดๆจากเนื้อหาที่มีทั้งหมด
