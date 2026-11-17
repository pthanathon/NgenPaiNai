---
name: เงินไปไหน (NgenPaiNai)
description: สมุดจดรายรับรายจ่ายส่วนตัวโหมดมืด สไตล์ street-pop ที่แผงเขียวมะนาวแผงเดียวตอบว่าเดือนนี้ใช้ได้อีกเท่าไร
colors:
  ground: "#0f0f0f"
  hatch: "rgb(255 255 255 / 0.03)"
  panel: "#1a1a1a"
  panel-2: "#242424"
  line: "#2e2e2e"
  ink: "#f4f4ee"
  muted: "#a6a69c"
  lime: "#d4ff2a"
  on-lime: "#0f0f0f"
  on-lime-2: "#ccff00"
  coral: "#ff5c5c"
  on-coral: "#1a0505"
  on-coral-2: "#5c1010"
  pill: "#f4f4ee"
  reel-black: "#000000"
  cat-food: "#ff9f43"
  cat-drink: "#d9b48f"
  cat-transport: "#4cc9f0"
  cat-shopping: "#ff7ab8"
  cat-bills: "#ffd43b"
  cat-home: "#a5abff"
  cat-health: "#63e6be"
  cat-fun: "#c39bff"
  cat-merit: "#ffb3a7"
  cat-other: "#b4b4ac"
  cat-salary: "#e9ff8a"
  cat-side: "#ffe066"
  cat-gift: "#ff9fbd"
  cat-refund: "#80c8ff"
  cat-other-in: "#d0d4d8"
typography:
  display:
    fontFamily: "Anton, Kanit, sans-serif"
    fontSize: "clamp(3.6rem, 17vw, 4.6rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "0.005em"
    fontFeature: "tnum"
  numeral-entry:
    fontFamily: "Anton, Kanit, sans-serif"
    fontSize: "3.1rem"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "0.01em"
  numeral-sm:
    fontFamily: "Anton, Kanit, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 400
    letterSpacing: "0.02em"
    fontFeature: "tnum"
  headline:
    fontFamily: "Kanit, Anuphan, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Kanit, Anuphan, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 600
    lineHeight: 1.35
  label:
    fontFamily: "Kanit, Anuphan, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
  body:
    fontFamily: "Anuphan, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: "Anuphan, system-ui, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  hole: "3px"
  tile-sm: "9px"
  tile: "10px"
  field: "12px"
  panel: "16px"
  sheet: "22px"
  pill: "999px"
spacing:
  xs: "4px"
  sm: "6px"
  md: "12px"
  lg: "16px"
  xl: "22px"
components:
  button-primary:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.on-lime}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "46px"
  button-secondary:
    backgroundColor: "{colors.panel-2}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "46px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "46px"
  button-ghost-hover:
    textColor: "{colors.ink}"
  button-danger:
    backgroundColor: "transparent"
    textColor: "{colors.coral}"
    rounded: "{rounded.pill}"
    padding: "0 12px 0 8px"
  fab:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.on-lime}"
    rounded: "{rounded.pill}"
    padding: "0 26px 0 20px"
    height: "58px"
  pill-track:
    backgroundColor: "{colors.panel}"
    rounded: "{rounded.pill}"
    padding: "4px"
  pill-tab:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    height: "40px"
  pill-tab-active:
    backgroundColor: "{colors.pill}"
    textColor: "{colors.on-lime}"
  chip:
    backgroundColor: "{colors.panel-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "2px 12px"
  chip-now:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.on-lime}"
  date-chip:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "40px"
  date-chip-active:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.on-lime}"
  answer-panel:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.on-lime}"
    typography: "{typography.display}"
    rounded: "{rounded.panel}"
    padding: "6px 18px 16px"
  answer-panel-over:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.on-coral}"
  panel:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
  category-tile:
    textColor: "{colors.on-lime}"
    rounded: "{rounded.tile}"
    size: "38px"
  field-input:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "9px 12px"
    height: "46px"
  sheet:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    width: "540px"
---

# Design System: เงินไปไหน (NgenPaiNai)

## Overview

**Creative North Star: "ป้ายไฟมะนาวในซอยมืด (The Acid Signal)"**

ทั้งแอปคือซอยกลางคืนที่มืด เงียบ และมีลายเส้นทแยงละเอียดบนพื้น มีป้ายไฟสีเขียวมะนาวป้ายเดียวที่ตะโกนคำตอบว่าเดือนนี้ใช้ได้อีกเท่าไร ภาษาภาพมาจาก street-pop แบบเว็บ Zenless Zone Zero ที่ผู้ใช้ปักหมุดไว้ (ใช้เฉพาะภาษาภาพ ไม่มีโลโก้ ตัวละคร หรือแอสเซ็ตของแบรนด์) ได้แก่ ตัวเลข condensed หนักมาก แผงมุมมนที่ถูกตัดเฉียงหนึ่งมุม แท็บหัวขอบเฉียง แถบฟิล์มมีรู และตัวควบคุมทรงเม็ดยาที่อันทำงานเป็นสีขาว

ความหนาแน่นเป็นแบบแอปมือถือคอลัมน์เดียว (กว้างสุด 540px) ใช้ในห้องแสงน้อยก่อนนอน จึงเป็นโหมดมืดเท่านั้น (`color-scheme: dark`) ความลึกมาจากชั้นโทนเทาถ่านมากกว่าเงา สีสดมีแค่สามกลุ่ม: มะนาวสำหรับคำตอบและการกระทำ คอรัลสำหรับเกินงบ และสีสติกเกอร์ของหมวด ที่เหลือคือเทากับขาวนวล

ภาพที่ปฏิเสธ (ยืนยันใน direction contract): การ์ดขาวมุมมนกับป้ายเขียว/แดงแบบแอปการเงินทั่วไป แอปธนาคารที่เย็นชา และความน่ารักแบบพาสเทลมาสคอต

**Key Characteristics:**
- โหมดมืดเท่านั้น พื้นเกือบดำมีลายทแยง 135° ความทึบ 3%
- มะนาวแสบเป็นป้ายไฟเดียวของหน้าจอ ไม่ใช่สีตกแต่ง
- ตัวเลขเงินทุกตัวที่เป็นพระเอกใช้ Anton condensed และตัวเลขแบบ tabular
- มุมมน 16px ที่ถูกตัดเฉียงหนึ่งมุม (มุมขวาบน) คือซิลูเอตประจำโลก
- ตัวควบคุมทุกชนิดเป็นเม็ดยา อันที่เลือกเป็นพื้นขาวนวลตัวดำ
- ไอคอนหมวดเป็นสติกเกอร์สีเต็มกับไอคอน SVG เส้นดำ 2px ที่วาดเอง

## Colors

ดำถ่านกับขาวนวลอมเหลือง มีมะนาวแสบเป็นเสียงเดียว และคอรัลเป็นสัญญาณเตือนเดียว

### Primary
- **มะนาวแสบ (Acid Lime)** (`lime`): ป้ายไฟของแอป ใช้กับหน้าแผงคำตอบ ปุ่มหลักและปุ่ม "จด" ชิป "วันนี้" ชิปวันที่ที่เลือก วงแหวนวันนี้บนแถบฟิล์ม ตัวเลขรายรับ เส้นโฟกัส เคอร์เซอร์ และ selection ตัวอักษรบนพื้นมะนาวใช้ `on-lime` (ดำ) และข้อความรองใช้ `on-lime-2` (เขียวมะกอกเข้ม)

### Secondary
- **คอรัลเตือน (Signal Coral)** (`coral`): ใช้เฉพาะความหมาย "เกิน": หน้าแผงคำตอบเมื่อเกินงบ (สลับ `--face` เป็นคอรัล ตัวอักษร `on-coral` / `on-coral-2`) รูของวันที่จ่ายเกินเพดานรายวัน ค่าที่เพิ่มขึ้นในหน้าสถิติ ข้อความผิดพลาด และปุ่ม/เมนูลบ

### Tertiary
- **สติกเกอร์หมวด (Category Stickers)** (`cat-*`): สีเต็มอิ่มกลางๆ สิบห้าสี หนึ่งสีต่อหนึ่งหมวด ใช้เป็นพื้นของ tile ไอคอนหมวดและแถบมิเตอร์ในหน้าสถิติเท่านั้น ไอคอนบนสติกเกอร์เป็นสีดำเสมอ

### Neutral
- **พื้นซอย (Alley Ground)** (`ground`): พื้นหลังของ body พร้อมลายทแยง (`hatch`) และพื้นของช่องกรอก ชิปวันที่ และปุ่มหมวดภายในแผ่น
- **ถ่าน (Charcoal Panel)** (`panel`): แผงรายการ แผงสถิติ ร่องของตัวควบคุมเม็ดยา และพื้นแผ่น (sheet)
- **ถ่านอ่อน (Charcoal Lift)** (`panel-2`): hover ของแถวและปุ่มไอคอน ชิปวันที่ทั่วไป ปุ่มรอง และราง meter
- **เส้นแบ่ง (Seam)** (`line`): เส้นคั่นแถวรายการ ขอบช่องกรอก และเส้นใต้ช่องจำนวนเงิน
- **ขาวนวล (Bone Ink)** (`ink`, `pill`): ข้อความหลัก และพื้นของเม็ดยาที่ถูกเลือกและ toast
- **เทาหิน (Stone Muted)** (`muted`): ข้อความรอง ป้ายช่องกรอก แท็บที่ไม่ได้เลือก
- **ดำฟิล์ม (Reel Black)** (`reel-black`): พื้นแท้ของแผงคำตอบ เห็นเป็นแท็บหัวและแถบฟิล์มด้านล่าง

### Named Rules
**The One Signal Rule.** มะนาวแสบมีหน้าที่เดียวคือบอกคำตอบหรือการกระทำที่ทำได้ตอนนี้ ห้ามใช้เป็นสีตกแต่ง เส้นขอบลอยๆ หรือพื้นหลังของส่วนที่ไม่มีความหมาย แผงคำตอบเป็นพื้นที่มะนาวขนาดใหญ่เพียงพื้นที่เดียวของหน้า

**The Coral Means Over Rule.** คอรัลแปลว่า "เกิน" หรือ "ทำลาย" เท่านั้น รายจ่ายปกติเป็นสีขาวนวล ไม่ใช่สีแดง แอปไม่ทำให้รู้สึกผิดเวลาใช้เงิน

**The Black Glyph Rule.** สติกเกอร์หมวดทุกสีใช้ไอคอนสีดำ ไม่ใช้ไอคอนสีขาวหรือไอคอนสีตามหมวดบนพื้นเทา

## Typography

**Display Font:** Anton (ตกไป Kanit) สำหรับตัวเลข
**Heading Font:** Kanit 600 / 800 / 800 italic (ตกไป Anuphan)
**Body Font:** Anuphan 400 / 500 (ตกไป system-ui)

**Character:** Anton ให้ตัวเลขผอมสูงหนักแบบป้ายโฆษณาริมถนน Kanit หนักให้หัวข้อไทยที่ห้าวและเป็นกันเอง Anuphan เป็นเนื้อความไทยที่อ่านง่ายและเงียบ ฟอนต์ทั้งหมดโฮสต์เองเป็น woff2 แยก subset ไทยกับละติน

### Hierarchy
- **Display** (Anton 400, clamp(3.6rem, 17vw, 4.6rem), 1.05): ยอดเงินบนแผงคำตอบเท่านั้น สัญลักษณ์ ฿ ใช้ Kanit 800 ขนาด 0.55em ยกขึ้น
- **Numeral Entry** (Anton 400, 3.1rem, 1.15): ช่องกรอกจำนวนเงินในแผ่นจด (ช่องงบใช้ 2rem)
- **Numeral Small** (Anton 400, 1.15–1.35rem, letter-spacing 0.02em): ยอดรวมรายวันและตัวเลขในหัวบล็อกสถิติ
- **Headline** (Kanit 800 italic, 1.5rem, 1.2, -0.01em): ชื่อแอปบนแถบ ตามด้วยบล็อกมะนาวเอียง skewX(-18deg) ขนาด 10px
- **Title** (Kanit 600, 1.05–1.2rem, 1.35): หัวแผ่น หัวบล็อกสถิติ หัวกลุ่มเมนู หัวสถานะว่าง
- **Label** (Kanit 600, ขนาดตามบริบท 0.85–1rem): ตัวควบคุมทุกชนิด: ปุ่ม แท็บ เม็ดยาเดือน ชิป และแท็บหัวแผงคำตอบ (0.95rem) ปุ่ม "จด" ใช้ Kanit 800 italic 1.2rem
- **Body** (Anuphan 400, 16px, 1.5): ข้อความทั่วไป ชื่อรายการใช้ 500 ยอดเงินในแถวใช้ 600 แบบ tabular
- **Caption** (Anuphan 400, 0.72–0.92rem, สี muted): บรรทัดรอง ป้ายช่องกรอก legend ป้ายหมวดในแผ่น

### Named Rules
**The Anton Is Money Rule.** Anton ใช้กับตัวเลขเงินเท่านั้น ไม่ใช้กับคำไทยหรือหัวข้อ (Anton ไม่มีอักษรไทย) และตัวเลขเงินทุกที่ใช้ `font-variant-numeric: tabular-nums`

**The Italic Is Voice Rule.** Kanit 800 italic สงวนไว้กับชื่อแอปและปุ่ม "จด" ซึ่งเป็นเสียงตะโกนของแบรนด์ ไม่ใช้กับหัวข้อทั่วไป

## Layout

คอลัมน์เดียวกึ่งกลาง กว้างสุด 540px ขอบข้าง 16px ขอบล่างเผื่อ 120px + safe-area ให้ปุ่มลอย ลำดับจากบนลงล่าง: แถบชื่อแอป ตัวสลับเดือน แผงคำตอบ บรรทัด legend และรับ/จ่าย แท็บเม็ดยา "รายการ | เงินไปไหน" แล้วเนื้อหาของแท็บ ช่วงห่างหลักระหว่างกลุ่มคือ 22px ภายในกลุ่มใช้ 4/6/12/14px

ปุ่ม "จด" ลอยล่างขวาใต้นิ้วโป้ง ยึดกับขอบขวาของคอลัมน์ 540px บนจอกว้าง แผ่น (sheet) เลื่อนขึ้นจากล่างบนมือถือ กว้างเต็ม สูงสุด 94dvh และกลายเป็นกล่องกลางจอกว้าง 480px ตั้งแต่ 640px ขึ้นไป แถวในแผ่นหมวดเป็นกริด 5 คอลัมน์ ช่องห่าง 6px เป้าสัมผัสขั้นต่ำ 40px สำหรับเม็ดยาและ 44px สำหรับปุ่มไอคอน

## Elevation & Depth

ระบบแบนและใช้ชั้นโทน: `ground` (มีลายทแยง) ต่ำสุด `panel` ยกขึ้นหนึ่งชั้น `panel-2` คือ hover หรือชั้นในแผง ภายในแผ่นพื้นของตัวควบคุมกลับไปเป็น `ground` เพื่อเจาะลงไปแทนการยกขึ้น เงาใช้เฉพาะสิ่งที่ลอยเหนือเนื้อหาจริงๆ

### Shadow Vocabulary
- **Float** (`box-shadow: 0 8px 24px rgb(0 0 0 / 0.55)`): ปุ่ม "จด" ที่ลอยทับรายการ (toast ใช้ 0.5)
- **Scrim** (`background: rgb(0 0 0 / 0.66)`): ฉากหลังของแผ่น
- **Inset Ring** (`box-shadow: inset 0 0 0 2px lime`): ปุ่มหมวดที่ถูกเลือก (เป็นเส้นขอบ ไม่ใช่เงา)

### Named Rules
**The Float Only Rule.** แผง การ์ด และแถวไม่มีเงา เงานุ่มใช้กับองค์ประกอบที่ลอยทับเนื้อหาเท่านั้น (ปุ่มลอยและ toast)

## Shapes

ภาษารูปทรงมีสองแบบที่อยู่ด้วยกัน: เม็ดยามนเต็ม (999px) สำหรับทุกสิ่งที่กดได้ และแผงมุมมน 16px ที่ถูก clip-path ตัดเฉียงมุมขวาบน (แผงทั่วไปตัด 18px แผงคำตอบตัด 18px × 1.6) ความเฉียงยังโผล่ในแท็บหัวแผงคำตอบ (ขอบซ้ายของส่วนเติมสีเฉียง 16px) และบล็อกมะนาวหลังชื่อแอป (skewX -18deg) สติกเกอร์หมวดเป็นสี่เหลี่ยมมุมมน 10px (9px ในแผ่น) ช่องกรอกและปุ่มหมวด 12px แผ่น 22px เฉพาะมุมบนบนมือถือ รูของแถบฟิล์ม 3px

**The One Cut Rule.** แผงหนึ่งแผงมีมุมตัดเฉียงหนึ่งมุมเสมอ ที่มุมขวาบน ไม่ตัดหลายมุมและไม่ย้ายมุม

## Components

### Buttons
ห้าว นูนด้วยสี ไม่ใช่ด้วยเงา
- **Shape:** เม็ดยามนเต็ม (999px) สูง 46px
- **Primary:** พื้นมะนาว ตัวดำ Kanit 600 padding 0 22px hover สว่างขึ้น `brightness(1.06)`
- **Secondary:** พื้น `panel-2` ตัวขาวนวล
- **Ghost / Danger:** พื้นใส ตัว muted (hover เป็น ink) หรือตัวคอรัลสำหรับลบ
- **Floating "จด":** เม็ดยามะนาวสูง 58px Kanit 800 italic 1.2rem ไอคอนบวกเส้น 3px hover ยกขึ้น 2px กดย่อเป็น 0.96
- **Focus:** เส้นมะนาว 2px ห่าง 2px ทุกองค์ประกอบ

### Pill Tabs & Segmented Controls
- **Style:** รางเม็ดยาพื้น `panel` (ในแผ่นใช้ `ground`) padding 4px ข้างในเป็นเม็ดยาสูง 40px Kanit 600 สี muted
- **Active:** พื้นขาวนวล ตัวดำ ใช้กับเม็ดยาเดือน แท็บมุมมอง และสวิตช์รายจ่าย/รายรับ เมื่อเลือก "รายรับ" เม็ดที่เลือกเปลี่ยนเป็นมะนาว

### Chips
- **Day chip:** เม็ดยาพื้น `panel-2` Kanit 600 0.85rem "วันนี้" เป็นพื้นมะนาวตัวดำ
- **Date chip (ในแผ่น):** พื้น `ground` ตัว muted สูง 40px ที่เลือกเป็นพื้นมะนาว
- **New tag:** เม็ดยาเส้นมะนาว 1.5px ตัวมะนาว 0.72rem กำกับรายการที่เพิ่งจดในรอบนี้
- **Fixed chip ("ประจำ"):** เม็ดยาแบบใส มีเส้นใน `muted` 1.5px และตัวอักษร `ink` ใช้เป็นหัวกลุ่มรายจ่ายประจำท้ายรายการของเดือน ต้องไม่ใช้สีมะนาว เพราะรายจ่ายประจำเป็นของที่หักไปแล้ว ไม่ใช่สิ่งที่ต้องกดหรือสนใจตอนนี้

### Cards / Containers
- **Corner Style:** 16px พร้อมมุมตัดเฉียง 18px ที่มุมขวาบน
- **Background:** `panel`
- **Shadow Strategy:** ไม่มี (ดู Elevation & Depth)
- **Border:** ไม่มี แถวภายในคั่นด้วยเส้น `line` 1px
- **Internal Padding:** แถว 12px 14px สูงอย่างน้อย 60px บล็อกสถิติ 18px 16px 16px

### Inputs / Fields
- **Style:** พื้น `ground` เส้น `line` 1.5px มุม 12px สูง 46px
- **Amount:** ไม่มีกล่อง เป็น ฿ Kanit 800 สี muted ตามด้วยตัวเลข Anton ใหญ่บนเส้นใต้ `line` 2px ตอนรายรับตัวเลขเป็นมะนาว
- **Select:** หน้าตาเหมือนช่องกรอก (พื้น `ground` เส้น `line` 1.5px มุม 12px สูง 46px) ใช้ตัวเลือกพื้นฐานของระบบ ไม่ทำ dropdown เอง
- **Focus:** เส้นขอบหรือเส้นใต้เปลี่ยนเป็นมะนาว
- **Error:** ข้อความใต้ฟอร์มเป็นคอรัล ข้อความยืนยันเป็นมะนาว

### Navigation
แถบบนมีชื่อแอปซ้ายและปุ่มเมนูจุดสามจุด (44px เส้นหนา 3.2) ขวา ตัวสลับเดือนเป็นรางเม็ดยาที่มีลูกศรสองข้างและเม็ดยาขาวตรงกลาง เดือนอื่นที่ไม่ใช่เดือนนี้แสดงเม็ดยาแบบใส เมนูเปิดเป็นแผ่นจากล่าง แถวเมนูสูง 50px มุม 12px hover เป็น `panel-2`

### Category Sticker Tile
สี่เหลี่ยมมุมมน 38px (32px ในแผ่น) พื้นสีเต็มของหมวด ไอคอน SVG ที่วาดเองจาก sprite ในหน้า เส้นดำ 2–2.1px ปลายมน ในแผ่นจด ปุ่มหมวดเป็นช่องพื้น `ground` มุม 12px ที่เลือกมีวงมะนาว inset 2px และป้ายเปลี่ยนเป็น ink ตัวหนา

### Answer Panel (Signature)
แผงพื้นดำ (`reel-black`) ตัดมุมขวาบน มุมมน 16px สีหน้าถูกกำหนดผ่านตัวแปร `--face` (มะนาวปกติ คอรัลเมื่อเกินงบ เปลี่ยนสีด้วย transition 0.4s) ส่วนหัวคือแท็บดำที่เขียนคำถามด้วยสีหน้า ตามด้วยส่วนเติมสีหน้าที่ขอบซ้ายเฉียง ตัวแผงแสดงยอดเงิน Display และบรรทัด "อีก N วัน · ใช้ได้วันละ ฿…" ด้านล่างเป็นแถบฟิล์มดำ หนึ่งรูต่อหนึ่งวัน สูง 13px ห่าง 3px สถานะรู: `ok` ขาวนวล (จ่ายไม่เกินเพดานรายวัน), `hi` คอรัล (เกินเพดาน; บนหน้าคอรัลใช้ชมพูอ่อน), `none` รูกลวงเส้นเทา, `future` รูกลวงเส้นจางมาก, `today` วงแหวนสีหน้า มี legend ใต้แผงอธิบายรูเสมอ

**Motion:** เมื่อบันทึก ยอดเงินหมุนนับจากค่าเดิมไปค่าใหม่ 450ms (exponential ease-out) และรูวันนี้เด้งในแนวตั้งหนึ่งครั้ง (scaleY 1.7, 0.5s) แผ่นเข้าด้วย `sheet-in` 0.32s เลื่อนขึ้น 40px พร้อม fade ทุกการเคลื่อนไหวใช้ `cubic-bezier(0.16, 1, 0.3, 1)` และเมื่อผู้ใช้ตั้ง reduced-motion ทุก animation และ transition ถูกปิด ค่าใหม่แสดงทันที

## Do's and Don'ts

### Do:
- **Do** ใช้พื้น `ground` พร้อมลายทแยง 135° ความทึบ 3% (เส้น 1px ทุก 7px) เป็นพื้นของทั้งแอป มันคือพื้นผิวของโลกนี้
- **Do** ให้หน้าจอหนึ่งมีพื้นที่มะนาวใหญ่เพียงแผงคำตอบ ปุ่มหลักและสถานะทำงานเป็นมะนาวขนาดเล็ก
- **Do** ใช้เม็ดยามนเต็มกับทุกตัวควบคุม และให้อันที่เลือกเป็นพื้นขาวนวลตัวดำ (ยกเว้นบริบทรายรับและวันที่ ที่ใช้มะนาว)
- **Do** ตัดมุมขวาบนของแผงด้วย clip-path และคงมุมมน 16px ไว้ที่มุมอื่น
- **Do** ใช้ Anton กับตัวเลขเงินที่เป็นพระเอก และตัวเลขแบบ tabular ทุกที่ที่มีเงิน
- **Do** วาดไอคอนใหม่เป็น SVG ใน sprite เดิม viewBox 24 เส้น 2px ปลายมน สีตาม currentColor
- **Do** ใส่ทางเลือก reduced-motion ให้ทุกการเคลื่อนไหวใหม่

### Don't:
- **Don't** ทำการ์ดขาวมุมมนกับป้ายเขียว/แดงแบบแอปการเงินทั่วไป
- **Don't** เพิ่มโหมดสว่าง ระบบนี้เป็นโหมดมืดเท่านั้น
- **Don't** ใช้คอรัลกับรายจ่ายปกติ คอรัลแปลว่าเกินหรือลบเท่านั้น
- **Don't** ใช้โลโก้ ตัวละคร ชื่อ หรือแอสเซ็ตของ Zenless Zone Zero ใช้ได้เฉพาะภาษาภาพ
- **Don't** ใส่เงาให้แผง แถว หรือชิป เงามีไว้ให้สิ่งที่ลอยเท่านั้น
- **Don't** ใช้ Anton กับข้อความภาษาไทย หรือใช้ Kanit italic กับหัวข้อทั่วไป
- **Don't** ใช้ไอคอนฟอนต์ อีโมจิ หรือไอคอนสีขาวบนสติกเกอร์หมวด
