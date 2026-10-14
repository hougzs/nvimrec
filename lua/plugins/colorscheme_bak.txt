-- lua/plugins/theme.lua
return {
  {
    "rose-pine/neovim",
    name = "rose-pine",
    lazy = false,
    opts = {
      styles = {
        transparency = true, -- 开启透明
      },
    },
  },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "rose-pine",
    },
  },
}
