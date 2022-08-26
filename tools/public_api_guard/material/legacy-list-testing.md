## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseHarnessFilters } from '@angular/cdk/testing';
import { ComponentHarness } from '@angular/cdk/testing';
import { ComponentHarnessConstructor } from '@angular/cdk/testing';
import { ContentContainerComponentHarness } from '@angular/cdk/testing';
import { DividerHarnessFilters } from '@angular/material/divider/testing';
import { HarnessPredicate } from '@angular/cdk/testing';
import { MatDividerHarness } from '@angular/material/divider/testing';
import { MatLegacyListOptionCheckboxPosition } from '@angular/material/legacy-list';

// @public (undocumented)
export interface LegacyActionListHarnessFilters extends BaseHarnessFilters {
}

// @public (undocumented)
export interface LegacyActionListItemHarnessFilters extends LegacyBaseListItemHarnessFilters {
}

// @public (undocumented)
export interface LegacyBaseListItemHarnessFilters extends BaseHarnessFilters {
    // (undocumented)
    text?: string | RegExp;
}

// @public (undocumented)
export interface LegacyListHarnessFilters extends BaseHarnessFilters {
}

// @public (undocumented)
export interface LegacyListItemHarnessFilters extends LegacyBaseListItemHarnessFilters {
}

// @public (undocumented)
export interface LegacyListOptionHarnessFilters extends LegacyBaseListItemHarnessFilters {
    // (undocumented)
    selected?: boolean;
}

// @public (undocumented)
export interface LegacyNavListHarnessFilters extends BaseHarnessFilters {
}

// @public (undocumented)
export interface LegacyNavListItemHarnessFilters extends LegacyBaseListItemHarnessFilters {
    // (undocumented)
    href?: string | RegExp | null;
}

// @public (undocumented)
export interface LegacySelectionListHarnessFilters extends BaseHarnessFilters {
}

// @public (undocumented)
export interface LegacySubheaderHarnessFilters extends BaseHarnessFilters {
    // (undocumented)
    text?: string | RegExp;
}

// @public
export class MatLegacyActionListHarness extends MatLegacyListHarnessBase<typeof MatLegacyActionListItemHarness, MatLegacyActionListItemHarness, LegacyActionListItemHarnessFilters> {
    static hostSelector: string;
    // (undocumented)
    _itemHarness: typeof MatLegacyActionListItemHarness;
    static with(options?: LegacyActionListHarnessFilters): HarnessPredicate<MatLegacyActionListHarness>;
}

// @public
export class MatLegacyActionListItemHarness extends MatLegacyListItemHarnessBase {
    blur(): Promise<void>;
    click(): Promise<void>;
    focus(): Promise<void>;
    static hostSelector: string;
    isFocused(): Promise<boolean>;
    static with(options?: LegacyActionListItemHarnessFilters): HarnessPredicate<MatLegacyActionListItemHarness>;
}

// @public
export class MatLegacyListHarness extends MatLegacyListHarnessBase<typeof MatLegacyListItemHarness, MatLegacyListItemHarness, LegacyListItemHarnessFilters> {
    static hostSelector: string;
    // (undocumented)
    _itemHarness: typeof MatLegacyListItemHarness;
    static with(options?: LegacyListHarnessFilters): HarnessPredicate<MatLegacyListHarness>;
}

// @public
export class MatLegacyListItemHarness extends MatLegacyListItemHarnessBase {
    static hostSelector: string;
    static with(options?: LegacyListItemHarnessFilters): HarnessPredicate<MatLegacyListItemHarness>;
}

// @public
export const enum MatLegacyListItemSection {
    // (undocumented)
    CONTENT = ".mat-list-item-content"
}

// @public
export class MatLegacyListOptionHarness extends MatLegacyListItemHarnessBase {
    blur(): Promise<void>;
    deselect(): Promise<void>;
    focus(): Promise<void>;
    getCheckboxPosition(): Promise<MatLegacyListOptionCheckboxPosition>;
    static hostSelector: string;
    isFocused(): Promise<boolean>;
    isSelected(): Promise<boolean>;
    select(): Promise<void>;
    toggle(): Promise<void>;
    static with(options?: LegacyListOptionHarnessFilters): HarnessPredicate<MatLegacyListOptionHarness>;
}

// @public
export class MatLegacyNavListHarness extends MatLegacyListHarnessBase<typeof MatLegacyNavListItemHarness, MatLegacyNavListItemHarness, LegacyNavListItemHarnessFilters> {
    static hostSelector: string;
    // (undocumented)
    _itemHarness: typeof MatLegacyNavListItemHarness;
    static with(options?: LegacyNavListHarnessFilters): HarnessPredicate<MatLegacyNavListHarness>;
}

// @public
export class MatLegacyNavListItemHarness extends MatLegacyListItemHarnessBase {
    blur(): Promise<void>;
    click(): Promise<void>;
    focus(): Promise<void>;
    getHref(): Promise<string | null>;
    static hostSelector: string;
    isFocused(): Promise<boolean>;
    static with(options?: LegacyNavListItemHarnessFilters): HarnessPredicate<MatLegacyNavListItemHarness>;
}

// @public
export class MatLegacySelectionListHarness extends MatLegacyListHarnessBase<typeof MatLegacyListOptionHarness, MatLegacyListOptionHarness, LegacyListOptionHarnessFilters> {
    deselectItems(...filters: LegacyListItemHarnessFilters[]): Promise<void>;
    static hostSelector: string;
    isDisabled(): Promise<boolean>;
    // (undocumented)
    _itemHarness: typeof MatLegacyListOptionHarness;
    selectItems(...filters: LegacyListOptionHarnessFilters[]): Promise<void>;
    static with(options?: LegacySelectionListHarnessFilters): HarnessPredicate<MatLegacySelectionListHarness>;
}

// (No @packageDocumentation comment for this package)

```