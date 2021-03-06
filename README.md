# ng-zorro-antd VSCode Snippets

![Plugin in action](help.gif)

[中文](README.zh-CN.md)

## Links

- [issues](https://github.com/cipchk/ng-zorro-vscode/issues)
- If ng-alain users need additional installation [ng-alain-vscode](https://marketplace.visualstudio.com/items?itemName=cipchk.ng-alain-vscode)

## Usage

Typing the beginning of `nz-` will automatically appear in the intellisense list; no more!

- `nz-` prefix is complete fragment
- `nz` (not `-`) prefix is attribute fragment

> To ensure ng-zorro-antd snippets suggestions are always on top in the suggestion list, add the following settings `"editor.snippetSuggestions": "top"`.

## Document


### General

Trigger | Description
--- | ---
nz-button.block | Block Button
nz-button | Button
nz-button.group | Button group
nz-button.icon-text-left | Button with icon and text on left
nz-button.icon-text-right | Button with icon and text on right
nzBlock | Button Property: option to fit button width to its parent width
nzGhost | Button Property: make background transparent and invert text and border colors
nzShape | Button Property: can be set to &#x60;circle&#x60; or omitted
nz-button.type | Button include type
nz-icon.custom | Custom icon
nz-icon | Icon
nz-icon.iconfont | Use iconfont.cn
nz-icon.spin | Rotate icon
nz-icon.twotone | Two-tone icon and colorful icon

### Layout

Trigger | Description
--- | ---
nz-grid.col | Grids System: column
nz-grid | Grids System
nzAlign | Grid Property: the vertical alignment of the flex layout
nzFlex | Grid Property: flex layout mode
nzGutter | Grid Property: spacing between grids
nzJustify | Grid Property: horizontal arrangement of the flex layout
nzLg | Grid Property: ≥992px
nzMd | Grid Property: ≥768px
nzOffset | Grid Property: the number of cells to offset Col from the left
nzOrder | Grid Property: raster order, used in &#x60;flex&#x60; layout mode
nzPull | Grid Property: the number of cells that raster is moved to the left
nzPush | Grid Property: the number of cells that raster is moved to the right
nzResponsive | Grid Property: A full responsive attributes
nzSm | Grid Property: ≥576px
nzSpan | Grid Property: raster number of cells to occupy, 0 corresponds to &#x60;display: none&#x60;
nzXl | Grid Property: ≥1200px
nzXs | Grid Property: &lt;576px
nzXXl | Grid Property: ≥1600px
nz-grid.responsive | Responsive grid system
nz-grid.row-flex | Responsive grid system flex layout
nz-grid.row | Grids System: row
nz-layout.content | layout layout content()
nz-layout | Layout
nz-sider | Sider
nzBreakpoint | Sider Property: breakpoints of the responsive layout
nzCollapsed | Sider Property: the collapsed status can be double binding
nzCollapsedWidth | Sider Property: width of the collapsed sidebar, by setting to 0 a special trigger will appear
nzCollapsible | Sider Property: whether can be collapsed
nzReverseArrow | Sider Property: reverse direction of arrow, for a sider that expands from the right
nzWidth | Sider Property: width of the sidebar

### Navigation

Trigger | Description
--- | ---
nz-affix | Affix
nzOffsetBottom | Affix Property: Pixels to offset from bottom when calculating position of scroll
nzOffsetTop | Affix Property: Pixels to offset from top when calculating position of scroll
nz-affix.target | Affix includes target
nz-breadcrumb | Breadcrumb
nz-breadcrumb.icon | Breadcrumb includes icon
nz-breadcrumb.item | Breadcrumb includes item
nzAutoGenerate | Breadcrumb Property: Auto generate breadcrumb
nzSeparator | Breadcrumb Property: Custom separator
nz-dropdown.button | Dropdown button style
nz-dropdown.button.style | Dropdown button style
nz-dropdown | Dropdown
nzClickHide | Dropdown Property: Whether hide menu when click
nz-menu | Menu
nz-menu.group | Menu group
nz-menu.item-divider | Menu item divider
nz-menu.item | Menu includes item
nzInlineCollapsed | Menu Property: specifies the collapsed status when menu is inline mode
nzInlineIndent | Menu Property: indent px of inline menu item on each level
nzMode | Menu Property: type of the menu
nzSelectable | Menu Property: allow selecting menu items
nzTheme | Menu Property: color theme of the menu
nz-menu.submenu | Menu includes submenu
nz-pagination | Pagination
nzHideOnSinglePage | Pagination Property: Whether to hide pager on single page
nz-steps.custom-dot | Steps: Custom dot
nz-steps | Steps
nzStartIndex | Steps Property: To specify the starting number
nz-steps.step-icon | Steps inlcudes step and icon
nz-steps.step | Step in stepds

### Data Entry

Trigger | Description
--- | ---
nz-autocomplete.custom-label | Autocomplete includes custom label
nz-autocomplete.data-source | Autocomplete includes data source
nz-autocomplete | Autocomplete
nz-cascader | Cascader
nz-checkbox | Checkbox
nz-checkbox.group | Checkbox group
nz-checkbox.layout | Checkbox use with Grid
nz-date | Date picker
nz-date.month | Month picker
nzDateRender | Date Property: custom rendering function for date cells (Not support by month-picker/year-picker)
nzDisabledDate | Date Property: specify the date that cannot be selected (Not support by year-picker)
nzRenderExtraFooter | Date Property: render extra footer in panel
nzShowTime | Date Property: to provide an additional time selection
nzShowToday | Date Property: whether to show &#x27;Today&#x27; button
nz-date.range | Date range picker
nz-date.week | Week picker
nz-form.control-responsive | Form: Control is responsive
nz-form.control | Form: Control
nz-form | Form
nz-form.explain-error | Form: A error message and only one
nz-form.explain | Form: Validation message and only one
nz-form.extra | Form: The extra prompt message. It is similar to help.
nz-form.item | Form: Used to separate the item in forms, contains label(optional) and control field.
nz-form.label-responsive | Form：The label of the form item.
nz-form.label | Form: The label of the form item, optional.
nzFormLayout | From Property: Form layout
nzHasFeedback | From Property: Used with &#x60;nzValidateStatus&#x60;, this option specifies the validation status icon. Recommended to be used only with Input.
nzValidateStatus | From Property: Will generate status based on FormControl
nz-form.split | Form: The split icon of &#x60;-&#x60;
nz-form.text | Form: Text in &#x60;nz-form-control&#x60;
nz-input.addon-icon | Input: addon icon
nz-input.addon-text | Input: addon text
nz-input | Input
nz-input.group | Input group
nzAddonAfterIcon | Input Property: The label icon&#x27;s ngClass displayed after
nzAddonBeforeIcon | Input Property: The label icon&#x27;s ngClass displayed before
nzCompact | Input Property: Whether use compact style
nzPrefix | Input Property: The prefix icon for the Input
nzSuffix | Input Property: The suffix icon for the Input
nz-input.prefix | Input includes prefix
nz-input.search | Input includes search
nz-input.suffix | Input includes suffix
nz-input-number | Input Number
nz-input-number.full | Input Number inclues min,max,step etc
nzFormatter | Input Number Property: Specifies the format of the value presented
nzParser | Input Number Property: Specifies the value extracted from nzFormatter
nzPrecision | Input Number Property: precision of input value
nz-mention | Mention
nz-radio.button | Radio button style
nz-radio | Radio
nz-radio.simple | Radio
nz-rate | Rate
nzAllowHalf | Rate Property: whether to allow semi selection
nz-select | Select
nzDropdownClassName | Select Property: className of dropdown menu
nzDropdownMatchSelectWidth | Select Property: Whether dropdown&#x27;s with is same with select
nzDropdownStyle | Select Property: style of dropdown menu
nzMaxMultipleCount | Select Property: Max selected option can be selected
nzMode | Select Property: Set mode of Select
nzNotFoundContent | Select Property: Specify content to show when no result matches
nzOnSearch | Select Property: Callback function that is fired when input changed
nzServerSearch | Select Property: nz-option will not be filtered when set to true
nzShowSearch | Select Property: Whether show search input in single mode
nz-select.option-group | Select option group
nz-select.option | Select option
nz-skeleton | Skeleton
nz-skeleton.full | Skeleton includes all properties
nz-slider | Slider
nz-switch | Switch
nz-switch.icon | Switch includes icon
nz-switch.text | Switch includes text
nz-textarea | Textarea
nzAutosize | Textarea Property: Only used for &#x60;textarea&#x60;, height autosize feature, can be set to boolean or an object &#x60;{ minRows: 2, maxRows: 6 }&#x60;
nz-time | Time picker
nzAllowEmpty | Time Property: allow clearing text
nzHourStep | Time Property: interval between hours in picker
nzMinuteStep | Time Property: interval between minutes in picker
nzSecondStep | Time Property: interval between seconds in picker
nz-transfer | Transfer
nz-tree-select | Tree Select
nz-upload | Upload
nz-upload.drag | Upload of drag
nzBeforeUpload | Upload Property: Hook function which will be executed before uploading. Uploading will be stopped with false or a Observable. Warning：this function is not supported in &#x60;IE9&#x60;. NOTICE: Muse be use &#x60;&#x3D;&gt;&#x60; to define the method.
nzCustomRequest | Upload Property: override for the default xhr behavior allowing for additional customization and ability to implement your own XMLHttpRequest. NOTICE: Muse be use &#x60;&#x3D;&gt;&#x60; to define the method.
nzDirectory | Upload Property: Support upload whole directory 
nzFileList | Upload Property: List of files, two-way data-binding
nzFileType | Upload Property: limit file type, e.g: &#x60;image/png,image/jpeg,image/gif,image/bmp&#x60;
nzFilterLimit | Upload Property: limit single upload count when &#x60;nzMultiple&#x60; has opened. &#x60;0&#x60; unlimited
nzFilterSize | Upload Property: limit file size (KB). &#x60;0&#x60; unlimited
nzListType | Upload Property: Built-in stylesheets
nzMultiple | Upload Property: Whether to support selected multiple file. IE10+ supported. You can select multiple files with CTRL holding down while multiple is set to be true
nzShowButton | Upload Property: Show upload button
nzShowUploadList | Upload Property: Whether to show default upload list, could be an object to specify &#x60;showPreviewIcon&#x60; and &#x60;showRemoveIcon&#x60; individually
nzWithCredentials | Upload Property: ajax upload with cookie sent

### Data Display

Trigger | Description
--- | ---
nz-avatar | Avatar
nz-avatar.icon | Avatar includes icon
nz-avatar.text | Avatar includes text
nz-badge | Badge
nz-badge.dot | Badge dot
nzBadgeStatus | Badge Property: Set &#x60;nz-badge&#x60; as a status dot
nzOverflowCount | Badge Property: Max count to show
nzShowZero | Badge Property: Whether to show badge when &#x60;count&#x60; is zero
nz-calendar | Calendar
nz-card | Card
nz-card.extra | Card includes extra
nz-card.meta | Card includes meta
nzHoverable | Card Property: Lift up when hovering card
nzTypeInner | Card Property: inner card style
nz-card.simple | Card
nz-card.tab | Card includes tab
nz-carousel | Carousel
nz-collapse | Collapse
nzAccordion | Collapse Property: Accordion mode
nzShowArrow | Collapse Property: Display arrow or not
nz-list | List
nz-list.item-meta | List includes item and meta
nz-list.item | List includes item
nz-list.loadmore | List includes loadmore
nzGrid | List Property: The grid type of list. You can set grid to something like &#x60;{gutter: 16, column: 4}&#x60;
nzItemLayout | List Property: The layout of list, default is &#x60;horizontal&#x60;, If a vertical list is desired, set the itemLayout property to &#x60;vertical&#x60;
nzLoadMore | List Property: Shows a load more content
nzPagination | List Property: Shows a pagination content
nzRenderItem | List Property: Custom item renderer
nz-list.simple | List
nz-popover | Popover
nz-table | Table
nzExpand | Table Property: Current expand status, double binding
nzFilterMultiple | Table Property: Whether filter multiple mode
nzFrontPagination | Table Property: Whether paginate data in front side，should set to &#x60;false&#x60; if you want to paginate data in server side or display all data in table
nzLeft | Table Property: Left pixels, used to fixed column to left
nzNoResult | Table Property: Custom no result content
nzPageIndex | Table Property: pageIndex , double binding
nzPageSize | Table Property: pageSize, double binding
nzRight | Table Property: Right pixels, used to fixed column to right
nzShowCheckbox | Table Property: Whether add nz-checkbox
nzShowExpand | Table Property: Whether show expand icon
nzShowFilter | Table Property: Whether show filter
nzShowPagination | Table Property: Whether show pagination component in bottom of the table
nzShowQuickJumper | Table Property: Determine whether you can jump to pages directly
nzShowRowSelection | Table Property: Whether show selections
nzShowSizeChanger | Table Property: Determine whether &#x60;nzPageSize&#x60; can be changed
nzShowSort | Table Property: Whether show sort
nzSort | Table Property: define current sort order
nzWidth | Table Property: Specify the column width, can not used when grouping columns
nz-table.static-no-pager | Table not pagination
nz-tabs | Tabs
nzAnimated | Tabs Property: Whether to change tabs with animation
nzTabPosition | Tabs Property: Position of tabs
nzTabsType | Tabs Property: Basic style of tabs
nz-tabs.tab | Tabs includes tab
nz-tag | Tag
nzColor | Tag Property: Color of the Tag
nzTagMode | Tag Property: Mode of tag
nz-timeline | Timeline
nz-timeline.item-custom-dot | Timeline: Custom dot of item
nz-timeline.item | Timeline includes item
nz-timeline.pending | Timeline includes pending
nz-tooltip | Tooltip
nzMouseEnterDelay | Tooltip Property: Delay in seconds, before tooltip is shown on mouse enter
nzMouseLeaveDelay | Tooltip Property: Delay in seconds, before tooltip is hidden on mouse leave
nz-tooltip.template | Tooltip curstom template
nz-tree | Tree

### Feedback

Trigger | Description
--- | ---
nz-alert.body | Alert custom body
nz-alert | Alert
nzAlertType | Alert Property: Type of Alert styles
nzBanner | Alert Property: Whether to show as banner
nzClosable | Alert Property: Whether Alert can be closed
nzMessage | Alert Property: Content of Alert
nzShowIcon | Alert Property: Whether to show icon
nz-drawer | Drawer
nz-modal | Modal
nz-popconfirm.button | Popconfirm button style
nz-popconfirm | Popconfirm
nzCondition | Popconfirm Property: Whether to directly emit &#x60;onConfirm&#x60; without showing Popconfirm
nz-progress.circle | Progress includes circle
nz-progress.dashboard | Progress includes dashboard
nz-progress | Progress
nz-progress.line | Progress includes line
nzProgressStatus | Progress Property: to set the status of the Progress
nz-spin | Spin
nzDelay | Spin Property: specifies a delay in milliseconds for loading state
nzSpinning | Spin Property: whether Spin is spinning
nzTip | Spin Property: customize description content when Spin has children

### Other

Trigger | Description
--- | ---
nz-anchor | Anchor
nz-anchor.link | Anchor includes link
nz-back-top | Back to Top
nz-divider | Divider
nz-divider.full | Divider

### General Property

Trigger | Description
--- | ---
nzActions | General Property: The action list
nzAllowClear | General Property: whether allow clear
nzAutoFocus | General Property: get focus when component mounted
nzBordered | General Property: Set border style
nzCancelText | General Property: Text of the Cancel button
nzChange | General Property: Callback for when component is changed
nzChecked | General Property: Checked status, double binding
nzClassName | General Property: Whether class name
nzClick | General Property: a click callback function
nzDescription | General Property: The description
nzDisabled | General Property: Whether disabled
nzExtra | General Property: The extra content
nzHeader | General Property: The header renderer
nzIndeterminate | General Property: set the status of indeterminate
nzLoading | General Property: set the loading status
nzMax | General Property: max value
nzMin | General Property: min value
nzName | General Property: name vlaue
nzOkText | General Property: Text of the OK button
nzOnClose | General Property: a close callback function
nzPlaceHolder | General Property: set the placeholder text
nzPlacement | General Property: set the placement
nzPopupStyle | General Property: to customize the style of the popup
nzSelect | General Property: a select callback
nzSelectChange | General Property: a select callback function
nzShape | General Property: the shape
nzSize | General Property: the size
nzStep | General Property: step value
nzTotal | General Property: total value
nzTrigger | General Property: specify the customized trigger
nzType | General Property: the type value
nzValue | General Property: the value
nzVisible | General Property: Whether the component is visible or not.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
