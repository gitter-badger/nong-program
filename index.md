---
layout: doc
is_home: true
title: Documentation
subtitle: เอกสารสำหรับผู้เริ่มต้นเป็นแฟนๆน้องโปรแกรม
---

# หน้าหลัก

ยินดีต้อนรับสู่ Documentation สำหรับผู้เริ่มต้นการเป็นโปรแกรมเมอร์ หรือผู้ที่สนใจเพื่อการศึกษาเพิ่มเติม โดยสามารถติดตามข้อมูลเพิ่มเติมได้ที่เพจเฟสบุ๊ก [Nong Program - เพจเพื่อแฟนๆของน้องโปรแกรม](https://www.facebook.com/777742965747869) สำหรับเนื้อหาที่น่าสนใจอื่นๆในรูปแบบ Infographic

## การรายงานเนื้อหาที่ผิดพลาด

สามารถเปิด Issues ใหม่ได้ที่ [https://github.com/ramut-group/nong-program/issues](https://github.com/ramut-group/nong-program/issues) เพื่อทำการรายงานและพูดคุยเกี่ยวกับเนื้อหาที่เกี่ยวข้อง ก่อนที่จะดำเนินการแก้ไขเนื้อหา
## ผู้มีส่วนร่วม

> คุณสามารถมีส่วนร่วมในการเขียนบทความได้ผ่านการ Pull Request หรือขอเป็นส่วนหนึ่ง Contributors โดยจะมีรูปแบบและวิธีการ Fork เพื่อนำไปพัฒนาต่อ รายละเอียดเพิ่มเติมใน [https://github.com/ramut-group/nong-program/readme.md](https://github.com/ramut-group/nong-program)

<div class="columns is-multiline">
  {% for contributor in site.data.contributors %}
    <div class="column is-6-desktop is-12-tablet">
      <div class="card">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <div class="image is-48x48">
                <img src="{{ contributor.image }}" alt="" style="border-radius: 50px;">
              </div>
            </div>
            <div class="media-content">
              <div class="title is-4">{{ contributor.realname_th }}</div>
              <div class="subtitle is-6">{{ contributor.realname_en }}</div>
            </div>
            <div class="media-right">
              {% if contributor.github %}
                <a target="_blank" href="{{ contributor.github | prepend: 'https://github.com/' }}">
                  <span class="icon">
                    <i class="fab fa-lg fa-github"></i>
                  </span>
                </a>
              {% endif %}
              {% if contributor.facebook %}
                <a target="_blank" href="{{ contributor.facebook | prepend: 'https://www.facebook.com/' }}">
                  <span class="icon">
                    <i class="fab fa-lg fa-facebook"></i>
                  </span>
                </a>
              {% endif %}
              {% if contributor.twitter %}
                <a target="_blank" href="{{ contributor.twitter | prepend: 'https://twitter.com/' }}">
                  <span class="icon">
                    <i class="fab fa-lg fa-twitter"></i>
                  </span>
                </a>
              {% endif %}
            </div>
          </div>
          <div class="content">
            <blockquote>
              {{ contributor.quote }}
            </blockquote>
          </div>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
