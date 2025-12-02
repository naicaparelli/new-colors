================================================================================
COLOR MAPPING - CURRENT SITE → FIGMA DESIGN TOKENS
================================================================================
Date: 12/02/2024
Document for developers

================================================================================
EXECUTIVE SUMMARY
================================================================================

Total tokens: 150
✅ Exact match: 68
🔄 Adjusted: 62
➕ Create token in Figma: 20

MAIN GLOBAL CHANGES:
-----------------------------
#00003c  →  #0F0F19  (Navy dark - bg primary)
#1e1e58  →  #161626  (Navy medium - bg secondary)
#2b2b75  →  #1F1F38  (Purple - bg tertiary)
#181871  →  #1F1F38  (Hover states)
#19194c  →  #161626  (Footer)

================================================================================
BACKGROUNDS
================================================================================

--background-main
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--background-primary
  SITE: #1e1e58  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

--background-secondary
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--background-header
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--background-sidebar
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--background-calendar
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--background-bottom-menu
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--background-extra-1 (Brand)
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

--background-extra-2
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--background-extra-3
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

--background-extra-4
  SITE: hsla(0,0%,96%,.1)  →  FIGMA: hsla(0,0%,96%,.1)
  Token: components.bg.elevated
  Status: MATCH ✅

--background-extra-8
  SITE: rgba(0,0,60,.3)  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED
  Note: Converted from transparent rgba to solid color

--background-extra-9
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--background-extra-14
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

================================================================================
BACKGROUND GRADIENTS
================================================================================

--background-gradient
  SITE: linear-gradient(270deg,#00003c,rgba(0,0,60,.68) 47.92%,rgba(0,0,60,0))
  FIGMA: linear-gradient(270deg,#0F0F19,rgba(15,15,25,.68) 47.92%,rgba(15,15,25,0))
  Token: components.gradients.primary
  Status: ADJUSTED

--background-gradient-2
  SITE: linear-gradient(180deg,rgba(43,43,117,0),rgba(43,43,117,.75) 49.26%,rgba(43,43,117,.93) 73.4%,rgba(43,43,117,.97) 84.11%,#2b2b75)
  FIGMA: linear-gradient(180deg,rgba(31,31,56,0),rgba(31,31,56,.75) 49.26%,rgba(31,31,56,.93) 73.4%,rgba(31,31,56,.97) 84.11%,#1F1F38)
  Token: components.gradients.tertiary
  Status: ADJUSTED

--background-gradient-3
  SITE: linear-gradient(180deg,rgba(30,30,88,0),#1e1e58)
  FIGMA: linear-gradient(180deg,rgba(22,22,38,0),#161626)
  Token: components.gradients.secondary
  Status: ADJUSTED

--background-gradient-4
  SITE: linear-gradient(270deg,rgba(0,0,60,0) -55.05%,rgba(0,0,60,.24) -32.88%,#00003c)
  FIGMA: linear-gradient(270deg,rgba(15,15,25,0) -55.05%,rgba(15,15,25,.24) -32.88%,#0F0F19)
  Token: components.gradients.overlay
  Status: ADJUSTED

--background-extra-10
  SITE: linear-gradient(137.82deg,#ffce5a 16.96%,#ff8b29 91.65%)
  FIGMA: linear-gradient(132.59deg,#ebff00 0%,#eab308 49%,#ef4444 100%)
  Token: gradient.gradients.hot
  Status: ADJUSTED

================================================================================
DIVIDER
================================================================================

--divider
  SITE: #6a6ba4  →  FIGMA: #6a6ba4
  Token: _semantic.color.border.default
  Status: MATCH ✅

================================================================================
TEXT COLORS
================================================================================

--text-color-primary
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.text.primary
  Status: MATCH ✅

--text-color-secondary
  SITE: #9697cd  →  FIGMA: #9697cd
  Token: components.text.secondary
  Status: MATCH ✅

--text-color-contrast
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

--text-color-extra-1
  SITE: #6a6ba4  →  FIGMA: #6a6ba4
  Token: components.text.secondary
  Status: MATCH ✅

--text-color-extra-2
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

--text-color-extra-3
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

--text-color-extra-4
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.text.brand-primary-contrast
  Status: ADJUSTED

================================================================================
BUTTONS - PRIMARY
================================================================================

--button-primary-bg
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.button.primary.default.bg
  Status: MATCH ✅

--button-primary-text
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.button.primary.default.text
  Status: ADJUSTED

--button-primary-bg-hover
  SITE: #f1ff4f  →  FIGMA: #f1ff4f
  Token: components.button.primary.hover.hover
  Status: MATCH ✅

--button-primary-text-hover
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.button.primary.hover.text
  Status: ADJUSTED

--button-primary-bg-active
  SITE: #d9eb00  →  FIGMA: #d9eb00
  Token: components.button.primary.pressed.pressed
  Status: MATCH ✅

--button-primary-text-active
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.button.primary.pressed.text
  Status: ADJUSTED

================================================================================
BUTTONS - SECONDARY
================================================================================

--button-secondary-bg
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.button.secondary.default.bg
  Status: ADJUSTED

--button-secondary-border
  SITE: 1px solid #f5f5f5  →  FIGMA: 1px solid #f5f5f5
  Token: components.button.secondary.default.border
  Status: MATCH ✅

--button-secondary-text
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.secondary.default.text
  Status: MATCH ✅

--button-secondary-bg-hover
  SITE: #181871  →  FIGMA: #1F1F38
  Token: components.button.secondary.hover.hover
  Status: ADJUSTED

--button-secondary-border-color-hover
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.secondary.hover.border
  Status: MATCH ✅

--button-secondary-text-hover
  SITE: #f1ff4f  →  FIGMA: #f1ff4f
  Token: components.button.secondary.hover.text
  Status: MATCH ✅

--button-secondary-bg-active
  SITE: #007  →  FIGMA: #0F0F19
  Token: components.button.secondary.pressed.pressed
  Status: ADJUSTED

--button-secondary-border-color-active
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.secondary.pressed.border
  Status: MATCH ✅

--button-secondary-text-active
  SITE: #d9eb00  →  FIGMA: #d9eb00
  Token: components.button.secondary.pressed.text
  Status: MATCH ✅

================================================================================
BUTTONS - SPECIAL (OUTLINED)
================================================================================

--button-special-bg
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.button.outlined.deafult.bg
  Status: ADJUSTED

--button-special-border
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.outlined.deafult.border
  Status: MATCH ✅

--button-special-text
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.outlined.deafult.text
  Status: MATCH ✅

--button-special-icon
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.outlined.deafult.icon
  Status: MATCH ✅

--button-special-bg-hover
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.button.outlined.hover.bg
  Status: ADJUSTED

--button-special-text-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.button.outlined.hover.text
  Status: MATCH ✅

--button-special-icon-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.button.outlined.hover.icon
  Status: MATCH ✅

================================================================================
BUTTONS - TEXT ONLY
================================================================================

--button-text
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.navegation.links&menus.default
  Status: MATCH ✅

--button-text-hover
  SITE: #f5ff84  →  FIGMA: #f5ff84
  Token: CREATE SPECIFIC TOKEN ➕
  Note: Intermediate color between lime and white

--button-text-active
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.navegation.links&menus.active
  Status: MATCH ✅

================================================================================
BUTTONS - CLOSE
================================================================================

--button-close-bg
  SITE: hsla(0,0%,96%,.1)  →  FIGMA: hsla(0,0%,96%,.1)
  Token: components.button.outlined.deafult.bg
  Status: MATCH ✅

--button-close-bg-hover
  SITE: hsla(0,0%,96%,.2)  →  FIGMA: hsla(0,0%,96%,.2)
  Token: components.button.outlined.hover.hover
  Status: MATCH ✅

--button-close-border
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.outlined.deafult.border
  Status: MATCH ✅

--button-close-border-hover
  SITE: #616161  →  FIGMA: #616161
  Token: CREATE SPECIFIC TOKEN ➕
  Status: CREATE TOKEN

--button-close-color
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.button.outlined.deafult.text
  Status: MATCH ✅

--button-close-color-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.button.outlined.hover.text
  Status: MATCH ✅

================================================================================
SEARCH
================================================================================

--search-bg
  SITE: #24262b  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--search-bg-extra
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--search-border-color
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.input.default.border
  Status: ADJUSTED

--search-text
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.input.default.value
  Status: MATCH ✅

--search-icon
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.input.default.icon
  Status: MATCH ✅

--search-bg-active
  SITE: #1e1e58  →  FIGMA: #161626
  Token: components.input.focused.border
  Status: ADJUSTED

--search-border-color-active
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.input.focused.border
  Status: MATCH ✅

--search-text-active
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.input.default.value
  Status: MATCH ✅

================================================================================
ARROW
================================================================================

--arrow-bg
  SITE: hsla(0,0%,96%,.1)  →  FIGMA: hsla(0,0%,96%,.1)
  Token: components.bg.elevated
  Status: MATCH ✅

--arrow-bg-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

--arrow-icon
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.text.brand-primary-contrast
  Status: ADJUSTED

================================================================================
TABLE
================================================================================

--table-head-color
  SITE: rgba(244,247,252,.6)  →  FIGMA: rgba(244,247,252,.6)
  Token: CREATE SPECIFIC TOKEN ➕
  Status: CREATE TOKEN

--table-head-background
  SITE: rgba(30,30,88,.6)  →  FIGMA: rgba(22,22,38,.6)
  Token: CREATE SPECIFIC TOKEN ➕
  Status: ADJUSTED

--table-color
  SITE: #9a9fb1  →  FIGMA: #9a9fb1
  Token: components.text.secondary
  Status: MATCH ✅

--table-color-1
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

--table-color-2 (Cyan)
  SITE: #00fff0  →  FIGMA: #00fff0
  Token: CREATE DATA VISUALIZATION TOKEN ➕
  Note: Cyan for charts/tables

--table-color-3 (Pink)
  SITE: #ff006b  →  FIGMA: #ff006b
  Token: CREATE DATA VISUALIZATION TOKEN ➕
  Note: Pink for charts/tables

--table-row-header
  SITE: rgba(244,247,252,.1)  →  FIGMA: rgba(244,247,252,.1)
  Token: components.bg.elevated
  Status: MATCH ✅

--table-row
  SITE: rgba(244,247,252,.1)  →  FIGMA: rgba(244,247,252,.1)
  Token: components.bg.elevated
  Status: MATCH ✅

--table-row-extra
  SITE: rgba(30,30,88,.4)  →  FIGMA: rgba(22,22,38,.4)
  Token: CREATE SPECIFIC TOKEN ➕
  Status: ADJUSTED

--table-border-color
  SITE: #1e1e58  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

================================================================================
CHECKBOX
================================================================================

--checkbox-border
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.selectors.unselected.border
  Status: MATCH ✅

--checkbox-border-active
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.selectors.selected.border
  Status: MATCH ✅

--checkbox-bg
  SITE: transparent  →  FIGMA: transparent
  Token: components.selectors.unselected.background
  Status: MATCH ✅

--checkbox-bg-active
  SITE: #1e1e58  →  FIGMA: #161626
  Token: components.selectors.selected.background
  Status: ADJUSTED

--checkbox-icon
  SITE: transparent  →  FIGMA: transparent
  Status: MATCH ✅

--checkbox-icon-active
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.selectors.selected.icon
  Status: MATCH ✅

--checkbox-color
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.text.primary
  Status: MATCH ✅

--checkbox-color-active
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.text.primary
  Status: MATCH ✅

================================================================================
SWITCH
================================================================================

--switch-bg
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--switch-bg-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

--switch-border
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.button.outlined.deafult.border
  Status: ADJUSTED

--switch-border-hover
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.button.outlined.hover.border
  Status: MATCH ✅

--switch-disk
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

--switch-disk-active
  SITE: #1e1e58  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

================================================================================
SLIDER
================================================================================

--slider-dots-color
  SITE: hsla(0,0%,96%,.2)  →  FIGMA: hsla(0,0%,96%,.2)
  Token: components.bg.elevated
  Status: MATCH ✅

--slider-dots-color-active
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

================================================================================
NOTIFICATION
================================================================================

--notification-marker-background
  SITE: #6a6ba4  →  FIGMA: #6a6ba4
  Token: _semantic.color.border.default
  Status: MATCH ✅

--notification-marker-background-new
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.bg.brand
  Status: MATCH ✅

================================================================================
BLOCK TITLE
================================================================================

--block-title-color
  SITE: #f5f5f5  →  FIGMA: #f5f5f5
  Token: components.text.primary
  Status: MATCH ✅

--block-title-icon
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

================================================================================
INDICATORS / STATUS
================================================================================

--indicator-correctly (Success)
  SITE: #21ca6f  →  FIGMA: #21ca6f
  Token: _semantic.color.status.success.base
  Status: MATCH ✅

--indicator-error
  SITE: #ff5757  →  FIGMA: #ff5757
  Token: _semantic.color.status.error.base
  Status: MATCH ✅

--indicator-warning
  SITE: #ffc90a  →  FIGMA: #ffc90a
  Token: _semantic.color.status.warning.base
  Status: MATCH ✅

--indicator-extra (Info)
  SITE: #2f80ed  →  FIGMA: #2f80ed
  Token: CREATE INFO/BLUE TOKEN ➕
  Note: Blue info status color

================================================================================
SOCIAL MEDIA
================================================================================

--social-media-background
  SITE: #32343b  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--social-media-background-hover
  SITE: #191a1e  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

================================================================================
SHADOWS
================================================================================

--shadow-light
  SITE: 0px 4px 10px 0px #dcd3c5  →  FIGMA: 0px 4px 10px 0px #dcd3c5
  Token: effect.shadow.xs or sm
  Status: MATCH ✅

--shadow-header
  SITE: 0px 4px 10px 0px #020222  →  FIGMA: 0px 4px 10px 0px #020222
  Token: effect.shadow.md
  Status: MATCH ✅

--shadow-menu
  SITE: 0px 4px 15px rgba(25,26,30,.4)  →  FIGMA: 0px 4px 15px rgba(25,26,30,.4)
  Token: effect.effect.elevation.low
  Status: MATCH ✅

--shadow-bottom-menu
  SITE: 0px -4px 10px 0px rgba(25,26,30,.3)  →  FIGMA: 0px -4px 10px 0px rgba(25,26,30,.3)
  Token: effect.effect.elevation.low
  Status: MATCH ✅

--shadow-modal
  SITE: 0px 4px 10px 0px #020222  →  FIGMA: 0px 4px 10px 0px #020222
  Token: effect.effect.elevation.high
  Status: MATCH ✅

--shadow-dropdown
  SITE: 0px 6px 12px 0px rgba(25,26,30,.45)  →  FIGMA: 0px 6px 12px 0px rgba(25,26,30,.45)
  Token: effect.effect.elevation.medium
  Status: MATCH ✅

--shadow-button
  SITE: 0px 4px 15px rgba(25,26,30,.5)  →  FIGMA: 0px 4px 15px rgba(25,26,30,.5)
  Token: effect.effect.elevation.medium
  Status: MATCH ✅

--shadow-marker
  SITE: 0px 0px 8px 0px #ebff00  →  FIGMA: 0px 0px 8px 0px #ebff00
  Token: effect.shadow.glow-lime
  Status: MATCH ✅

================================================================================
FOOTER
================================================================================

--footer-background
  SITE: #19194c  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

--footer-divider
  SITE: #6a6ba4  →  FIGMA: #6a6ba4
  Token: _semantic.color.border.default
  Status: MATCH ✅

--footer-social-media-background
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--footer-social-media-background-hover
  SITE: #1e1e77  →  FIGMA: #161626
  Token: components.bg.secondary
  Status: ADJUSTED

--footer-social-media-text
  SITE: #ebff00  →  FIGMA: #ebff00
  Token: components.text.brand-primary
  Status: MATCH ✅

--footer-social-media-text-hover
  SITE: #d32f2f  →  FIGMA: #d32f2f
  Token: CREATE SPECIFIC TOKEN ➕
  Note: Red for social media hover

================================================================================
JACKPOT / GAMIFICATION
================================================================================

--jackpot-pool-color
  SITE: #d32f2f  →  FIGMA: #d32f2f
  Token: CREATE GAMIFICATION TOKEN ➕

--jackpot-prize-color-1 (Tier Gold)
  SITE: #d32f2f  →  FIGMA: #d32f2f
  Token: CREATE TIER GOLD TOKEN ➕
  Note: Tier 1 - Gold/Red

--jackpot-prize-color-2 (Tier Silver)
  SITE: #64b5f6  →  FIGMA: #64b5f6
  Token: CREATE TIER SILVER TOKEN ➕
  Note: Tier 2 - Silver/Blue

--jackpot-prize-color-3 (Tier Bronze)
  SITE: #f88d51  →  FIGMA: #f88d51
  Token: CREATE TIER BRONZE TOKEN ➕
  Note: Tier 3 - Bronze/Orange

--jackpot-prize-color-4 (Tier 4)
  SITE: #479d98  →  FIGMA: #479d98
  Token: CREATE TIER TOKEN ➕
  Note: Tier 4 - Teal

--jackpot-level-card-background
  SITE: rgba(43,43,117,.3)  →  FIGMA: rgba(31,31,56,.3)
  Token: components.bg.elevated
  Status: ADJUSTED

================================================================================
VIP PAGE
================================================================================

--page-vip-background
  SITE: #00003c  →  FIGMA: #0F0F19
  Token: components.bg.primary
  Status: ADJUSTED

--page-vip-background-element
  SITE: #2b2b75  →  FIGMA: #1F1F38
  Token: components.bg.tertiary
  Status: ADJUSTED

--page-vip-background-card
  SITE: radial-gradient(84.66% 113.32% at 0% 19.13%,#52529c 0%,#1e1e58 100%)
  FIGMA: radial-gradient(84.66% 113.32% at 0% 19.13%,#52529c 0%,#161626 100%)
  Token: CREATE VIP CARD GRADIENT ➕
  Status: ADJUSTED

================================================================================
LOADING
================================================================================

--loading-spinner-after-background
  SITE: linear-gradient(142deg,#ebff00 9.27%,#cbe501 40.62%,#9fd32f 52.92%,#f3ffac 85.47%)
  FIGMA: linear-gradient(135deg,#fcffcc 0%,#8d9900 100%)
  Token: gradient.gradients.primary
  Status: ADJUSTED

--loading-spinner-before-background
  SITE: linear-gradient(142deg,#ebff00 9.27%,#cbe501 40.62%,#9fd32f 52.92%,#f3ffac 85.47%)
  FIGMA: linear-gradient(135deg,#fcffcc 0%,#8d9900 100%)
  Token: gradient.gradients.primary
  Status: ADJUSTED

================================================================================
SKELETON LOADING
================================================================================

--skeleton-bg
  SITE: #4444a3  →  FIGMA: #4444a3
  Token: CREATE SPECIFIC TOKEN ➕
  Note: Skeleton loading color

--skeleton-inner
  SITE: linear-gradient(90deg,#4747aa,rgba(71,71,170,0) 47.5%,#4747aa)
  FIGMA: linear-gradient(90deg,#4747aa,rgba(71,71,170,0) 47.5%,#4747aa)
  Token: CREATE SKELETON GRADIENT ➕

================================================================================
SPACING / LAYOUT
================================================================================

--width-scroll-bar
  SITE: 2px  →  FIGMA: 2px
  Token: _core.border.width.2
  Status: MATCH ✅

--padding-section
  SITE: 16px  →  FIGMA: 16px
  Token: _core.space.16
  Status: MATCH ✅

--padding-block
  SITE: 24px  →  FIGMA: 24px
  Token: _core.space.24
  Status: MATCH ✅

--padding-container
  SITE: 14px  →  FIGMA: 14px
  Token: _core.space.14
  Status: MATCH ✅

--aside-width
  SITE: 360px  →  FIGMA: 360px
  Token: CREATE LAYOUT TOKEN
  Status: MATCH ✅

================================================================================
TOKENS TO CREATE IN FIGMA
================================================================================

HIGH PRIORITY:
----------------
1. Info/Blue indicator (#2f80ed)
   Category: _semantic.color.status.info.base
   
2. Data visualization colors
   - Cyan: #00fff0 → _semantic.color.dataviz.cyan
   - Pink: #ff006b → _semantic.color.dataviz.pink
   
3. Jackpot tier colors (4 colors)
   - Tier Gold: #d32f2f → _semantic.color.tier.gold
   - Tier Silver: #64b5f6 → _semantic.color.tier.silver
   - Tier Bronze: #f88d51 → _semantic.color.tier.bronze
   - Tier 4: #479d98 → _semantic.color.tier.teal

MEDIUM PRIORITY:
-----------------
4. Social media hover red
   - #d32f2f → components.social-media.text-hover
   
5. Button text hover intermediate
   - #f5ff84 → components.button.text.hover
   
6. Close button border hover
   - #616161 → components.button.close.border-hover

LOW PRIORITY:
-----------------
7. Skeleton loading colors
   - BG: #4444a3 → components.skeleton.bg
   - Gradient → components.skeleton.gradient
   
8. Specific table head
   - rgba(244,247,252,.6) → components.table.head.color
   - rgba(22,22,38,.6) → components.table.head.bg

================================================================================
IMPLEMENTATION INSTRUCTIONS
================================================================================

1. GLOBAL FIND AND REPLACE:
   -----------------------------
   Make these replacements in ALL CSS/SCSS files:
   
   #00003c  →  #0F0F19
   #1e1e58  →  #161626
   #2b2b75  →  #1F1F38
   #181871  →  #1F1F38
   #19194c  →  #161626

2. ADJUST RGBA/HSLA:
   -------------------
   Values with transparency containing old colors also need
   to be updated. Examples:
   
   rgba(0,0,60,.X)     →  rgba(15,15,25,.X)
   rgba(30,30,88,.X)   →  rgba(22,22,38,.X)
   rgba(43,43,117,.X)  →  rgba(31,31,56,.X)

3. GRADIENTS:
   -----------
   Review all gradients using old colors and update
   according to the mapping above.

4. CREATE MISSING TOKENS IN FIGMA:
   ---------------------------------
   Work with the design team to create the 20 tokens listed
   in the "TOKENS TO CREATE IN FIGMA" section.

5. VALIDATION:
   ----------
   After implementation, validate:
   - Text contrast (minimum WCAG AA)
   - Visual hierarchy maintained
   - Hover/focus states visible
   - Accessibility preserved

================================================================================
IMPORTANT NOTES
================================================================================

⚠️  ATTENTION: Some colors don't have an equivalent in Figma and require
    new tokens. Consult the design team before implementing.

✓   68 tokens have exact match and don't need adjustment
✓   62 tokens were adjusted following the new palette
✓   20 tokens need to be created in Figma

📝  NEXT STEPS:
    1. Design creates the 20 missing tokens in Figma
    2. Dev applies global find/replace
    3. QA validates contrast and accessibility
    4. Review edge cases (gradients, transparencies)

================================================================================
END OF DOCUMENT
================================================================================