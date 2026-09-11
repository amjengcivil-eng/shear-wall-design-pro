# Shear Wall Boundary Element Design Tool - Professional Edition

## المميزات الرئيسية

### ✅ التحسينات الجديدة

1. **فحص تفاعل الانحناء والضغط (P-M Interaction Diagram)**
   - رسم مخطط التفاعل الكامل
   - التحقق من نقطة التصميم

2. **فحص التحنيب (Buckling Check)**
   - للتسليح الطولي في العناصر الحدية
   - حساب الطول الفعال والقيود

3. **تصدير AutoCAD (DXF Format)**
   - مقطع طولي للجدار
   - مقاطع عرضية متعددة
   - تفاصيل التسليح والأبعاد
   - جاهز للتنفيذ مباشرة

4. **التحقق من صحة المدخلات**
   - فحص شامل للبيانات
   - رسائل خطأ واضحة

5. **حفظ واستعادة المشاريع**
   - حفظ بصيغة JSON
   - استعادة المشاريع السابقة

6. **جداول مقارنة وملاحظات التصنيع**
   - مقارنة بين طريقتي الحساب
   - ملاحظات للمقاول

## المتطلبات

```bash
pip install PyQt6 matplotlib python-docx reportlab ezdxf
```

## الاستخدام

```bash
python shear_wall_design_pro.py
```

## الملفات الرئيسية

- `shear_wall_design_pro.py` - التطبيق الرئيسي
- `dxf_exporter.py` - أداة تصدير AutoCAD
- `pm_interaction.py` - فحص تفاعل P-M
- `buckling_check.py` - فحص التحنيب
- `input_validator.py` - التحقق من المدخلات

## المعايير المطبقة

- ACI 318-14, 318-19, 318-25
- ISO Drawing Standards
- وحدات القياس: cm (سنتيمتر)
