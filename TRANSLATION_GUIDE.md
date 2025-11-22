# Translation Guide for Hanzo Technologies Website

## 🎯 Strategy

Due to the comprehensive nature of professional translation (861 lines × 12 languages), here's the recommended approach:

### Phase 1: Priority Languages (DO FIRST)
1. ✅ **English** - Complete (with language selector)
2. 🇯🇵 **Japanese** - CRITICAL (Claude creating full version)
3. 🇪🇸 **Spanish** - High priority (large market)
4. 🇨🇳 **Chinese** - Important (Asian expansion)

### Phase 2: Secondary Languages
5-12. French, Arabic, Korean, Vietnamese, German, Hindi, Tibetan, Hawaiian

## 📋 What Needs Translation

### Critical Sections (Translate These First):
- Navigation menu
- Hero section (main headline + description)
- About section
- Project titles and descriptions
- Contact section
- Footer

### Technical Terms (Keep in English or Transliterate):
- Hanzo (ハンゾー in Japanese, keep as-is in others)
- M.E.C, C.E.M, R.A.I (robot model names - keep acronyms)
- Email addresses (keep as-is)
- Technical specs (can be translated but verify accuracy)

## 🔧 How to Use This System

### Option A: Professional Translation Service
1. Export English content to a spreadsheet
2. Send to translation service (Gengo, SDL, Smartling)
3. Import translated content back into HTML templates
4. Cost: ~$0.10-0.20 per word × 5,000 words × 11 languages = $5,500-11,000

### Option B: AI-Assisted Translation (Budget-Friendly)
1. Use Claude, ChatGPT, or DeepL for initial translation
2. Have native speaker review and refine
3. Focus on cultural appropriateness, not just word-for-word
4. Cost: ~$500-1,500 for review

### Option C: DIY with Templates (What We're Providing)
1. Use the provided Japanese version as reference
2. Copy HTML structure
3. Replace English text with translations
4. Test on native speakers before publishing

## 📝 Translation Checklist for Each Language

### Before You Translate:
- [ ] Understand target market culture
- [ ] Research local competitors
- [ ] Check if technical terms have established translations
- [ ] Verify contact information makes sense for that market

### While Translating:
- [ ] Keep HTML tags intact
- [ ] Don't translate: email addresses, URLs, brand names
- [ ] DO translate: all visible text, meta descriptions, alt tags
- [ ] Maintain consistent terminology across the site

### After Translation:
- [ ] Test all links work
- [ ] Check mobile responsiveness
- [ ] Verify special characters display correctly
- [ ] Have native speaker review
- [ ] Test language selector switches correctly

## 🌐 Language-Specific Notes

### Arabic (AR)
- **RTL Layout:** Entire page needs right-to-left direction
- **Font:** Use Arabic web fonts (Noto Sans Arabic)
- **HTML:** Add `dir="rtl"` to `<html>` tag
- **Navigation:** Mirror/flip the layout

### Japanese (JA)
- **Mix scripts:** Hiragana, Katakana, Kanji
- **Formal language:** Use です/ます form (desu/masu)
- **Company name:** ハンゾーテクノロジーズ (Hanzō Tekunorojīzu)
- **Emphasis:** Tokyo operations and Japanese market fit

### Chinese (ZH)
- **Simplified vs Traditional:** Use Simplified for broader reach
- **Font:** Ensure proper Chinese font rendering
- **Company name:** 半藏科技 (Bànzàng Kējì)

### Korean (KO)
- **Formal language:** Use 합니다 (hamnida) form
- **Company name:** 한조 테크놀로지스 (Hanjo Teknolojiseu)

### Hindi (HI)
- **Devanagari script:** Proper font required
- **Mix with English:** Tech terms often kept in English
- **Company name:** हान्ज़ो टेक्नोलॉजीज़

### Tibetan (BO)
- **Special fonts:** Tibetan Unicode fonts required
- **Limited tech vocabulary:** Many terms stay in English
- **Cultural sensitivity:** Buddhist cultural considerations

### Hawaiian (HAW)
- **Special characters:** ʻOkina (ʻ) and macrons (ā, ē, ī, ō, ū)
- **Limited vocabulary:** Modern tech terms usually use English
- **Cultural respect:** Avoid appropriation, use respectfully

## 📦 Files You Need to Create

For each language (XX = language code):

```
/XX/index.html
```

Each file should have:
1. Language-specific `<html lang="XX">` tag
2. Translated `<title>` and meta tags
3. All visible text translated
4. Language selector pointing to correct paths
5. Same CSS/styling as English version

## 🔗 URL Structure After Translation

English: `yourusername.github.io/hanzo-website/`
Spanish: `yourusername.github.io/hanzo-website/es/`
Japanese: `yourusername.github.io/hanzo-website/ja/`
etc.

## ⚡ Quick Start: Japanese Version

Claude is creating a complete Japanese version for you because it's critical for your Tokyo operations. Use this as your template for other languages.

## 🎨 Design Considerations

### Don't Change:
- Colors (black background, red accent #C41E3A)
- Logo (HANZŌ •)
- Layout structure
- Contact emails
- Social media links

### DO Adapt:
- Text content
- Cultural references
- Examples relevant to that market
- Date/time formats if mentioned
- Phone number formats (when you add them)

## 💡 Pro Tips

1. **Start with hero section:** Most important first impression
2. **Keep it simple:** Don't over-translate; clarity > literal translation
3. **Test early:** Get feedback from native speakers ASAP
4. **Update together:** When English changes, update all languages
5. **Use translation memory:** Keep a glossary for consistency

## 📞 Need Help?

- For Japanese: Your Japanese Operations Manager (hire requirement)
- For Spanish: Many affordable translation services
- For others: Consider Upwork, Fiverr freelance translators

Budget estimate: $2,000-5,000 for professional translation of all 11 remaining languages.

## ✅ Priority Order for Translation

1. Japanese - CRITICAL (Claude creating now)
2. Spanish - Very important (large global market)
3. Chinese - Important (Asian expansion)
4. Korean - Important (nearby market to Japan)
5. French - Good (European presence)
6. German - Good (European business)
7. Vietnamese - Good (growing SE Asian market)
8. Arabic - Moderate (requires RTL work)
9. Hindi - Moderate (large but complex market)
10. Tibetan - Low (niche, cultural/philosophical interest)
11. Hawaiian - Low (niche, US local interest)

---

**Remember:** Quality over speed. Better to have 3 languages done perfectly than 12 done poorly!
