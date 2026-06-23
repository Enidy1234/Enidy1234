# Component specs (summary)

This file summarizes the core components used across the prototype and maps them to CSS/Tailwind tokens for handoff.

## Buttons

- Primary `.btn-primary`
  - Height: 40px; padding: 0 16px; border-radius: 8px
  - Background: `colors.primary` (#0B67FF); color: white
  - Hover: `primary-600` (#0959D9)
  - Shadow: `0 6px 14px rgba(11,103,255,0.12)`

- Secondary `.btn-secondary`
  - Background: transparent; border: 1px solid #E6E9F2; color: #0B67FF

## Inputs

- `.input`
  - Height: 44px; border-radius: 8px; border: 1px solid #E6E9F2; padding: 12px
  - Focus: border-color #0B67FF; box-shadow: 0 6px 12px rgba(11,103,255,0.08)

## Cards

- `.card`
  - Border-radius: 12px; padding: 16px; background: #fff; box-shadow: 0 8px 20px rgba(11,27,43,0.06)

## Table

- Header height: 56px; row height: 56px
- Row hover: background #F6F8FF
- Grid lines: #F1F3F8

## Tailwind token suggestions

- `--color-primary: #0B67FF`
- `--color-border: #E6E9F2`
- `--text-primary: #0B1B2B`
- `--space-1: 8px` (base unit)

