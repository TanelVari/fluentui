## API Report File for "@fluentui/react-button"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentProps } from '@fluentui/react-utilities';
import { ObjectShorthandProps } from '@fluentui/react-utilities';
import * as React from 'react';
import { ShorthandProps } from '@fluentui/react-utilities';

// @public
export const Button: React.ForwardRefExoticComponent<import("@fluentui/react-utilities").ComponentProps & React.ButtonHTMLAttributes<HTMLElement> & {
    icon?: import("@fluentui/react-utilities").ShorthandProps<React.HTMLAttributes<HTMLSpanElement>>;
    disabled?: boolean | undefined;
    iconOnly?: boolean | undefined;
    iconPosition?: "after" | "before" | undefined;
    primary?: boolean | undefined;
    size?: "small" | "large" | undefined;
} & React.RefAttributes<HTMLElement>>;

// @public (undocumented)
export type ButtonProps = ComponentProps & React.ButtonHTMLAttributes<HTMLElement> & {
    icon?: ShorthandProps<React.HTMLAttributes<HTMLSpanElement>>;
    disabled?: boolean;
    iconOnly?: boolean;
    iconPosition?: 'before' | 'after';
    primary?: boolean;
    size?: 'small' | 'large';
};

// @public
export const buttonShorthandProps: string[];

// @public (undocumented)
export interface ButtonState extends ButtonProps {
    // (undocumented)
    children?: ObjectShorthandProps<React.HTMLAttributes<HTMLSpanElement>>;
    // (undocumented)
    icon?: ObjectShorthandProps<React.HTMLAttributes<HTMLSpanElement>>;
    // (undocumented)
    ref: React.RefObject<HTMLButtonElement>;
}

// @public (undocumented)
export type ButtonStyleSelectors = {
    disabled?: boolean;
    iconOnly?: boolean;
    primary?: boolean;
    size?: string;
};

// @public (undocumented)
export type ButtonTokens = {
    height: string;
    paddingX: string;
    paddingY: string;
    minWidth: string;
    maxWidth: string;
    fontSize: string;
    fontWeight: number;
    lineHeight: string;
    iconWidth: string;
    iconHeight: string;
    iconSpacing: string;
    color: string;
    content2Color: string;
    background: string;
    backgroundHover: string;
    backgroundPressed: string;
    backgroundActive: string;
    borderColor: string;
    borderColorHover: string;
    borderColorActive: string;
    borderWidth: string;
    borderRadius: string;
    shadow: string;
    shadowPressed: string;
};

// @public (undocumented)
export type ButtonVariants = 'base' | 'disabled' | 'iconOnly' | 'primary' | 'small' | 'large' | 'primaryDisabled' | 'iconOnlySmall' | 'iconOnlyLarge';

// @public (undocumented)
export type ButtonVariantTokens = {
    [variant in ButtonVariants]: Partial<ButtonTokens>;
};

// @public
export const renderButton: (state: ButtonState) => JSX.Element;

// @public
export const useButton: (props: ButtonProps, ref: React.Ref<HTMLElement>, defaultProps?: ButtonProps | undefined) => ButtonState;

// @public
export const useButtonState: (draftState: ButtonState) => void;

// @public (undocumented)
export const useButtonStyles: (state: ButtonState, selectors: ButtonStyleSelectors) => void;


// (No @packageDocumentation comment for this package)

```
