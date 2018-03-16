---
layout: doc
is_home: true
title: nong-program Documentation
subtitle: เอกสารสำหรับผู้เริ่มต้นเป็นแฟนๆน้องโปรแกรม
---

# หน้าหลัก

ยินดีต้อนรับสู่ Documentation สำหรับผู้เริ่มต้นการเป็นโปรแกรมเมอร์ หรือผู้ที่สนใจเพื่อการศึกษาเพิ่มเติม โดยสามารถติดตามข้อมูลเพิ่มเติมได้ที่เพจเฟสบุ๊ก [Nong Program - เพจเพื่อแฟนๆของน้องโปรแกรม](https://www.facebook.com/777742965747869) สำหรับเนื้อหาที่น่าสนใจอื่นๆในรูปแบบ Infographic

## การรายงานเนื้อหาที่ผิดพลาด

สามารถเปิด Issues ใหม่ได้ที่ [https://github.com/nakorndev/nong-program/issues](https://github.com/nakorndev/nong-program/issues) เพื่อทำการรายงานและพูดคุยเกี่ยวกับเนื้อหาที่เกี่ยวข้อง ก่อน
## ผู้มีส่วนร่วมการเขียนบทความ

> คุณสามารถมีส่วนร่วมในการเขียนบทความได้ผ่านการ Pull Request หรือขอเป็นส่วนหนึ่ง Contributors โดยจะมีรูปแบบและวิธีการ Fork เพื่อนำไปพัฒนาต่อ รายละเอียดเพิ่มเติมใน [https://github.com/nakorndev/nong-program/readme.md](https://github.com/nakorndev/nong-program)

<div class="columns">
  {% for author in site.data.authors %}
    <div class="column is-3-widescreen is-4-desktop is-6-tablet is-12-mobile">
      <div class="card">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <div class="image is-48x48">
                <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
              </div>
            </div>
            <div class="media-content">
              <div class="title is-4">John Smith</div>
              <div class="subtitle is-6">@johnsmith</div>
            </div>
          </div>
          <div class="content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris. <a>@bulmaio</a>.
            <a href="#">#css</a> <a href="#">#responsive</a>
            <br>
            <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
          </div>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
