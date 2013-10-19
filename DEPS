# GClient is a part of Google's depot tools
# http://www.chromium.org/developers/how-tos/install-depot-tools

# the biggest DEPS example is a Chromium's one
# http://src.chromium.org/chrome/trunk/src/DEPS 

use_relative_paths = True

vars = {
  "root_dir": "virt2real-sdk",

  # GtiHb project root to be used as 'Var("github_root") + "sub-project.git",
  "github_root": "https://github.com/virt2real/"
}

# NOTE: Prefer revision numbers to tags for svn deps. Use http rather than
# https; the latter can cause problems for users behind proxies.
deps = {
    "kernel":
        Var("github_root") + "linux-davinci.git",
    "dvsdk":
        Var("github_root") + "DVSDK.git",

    "fs":
        Var("github_root") + "v2r_buildroot.git",

    "adminka":
        Var("github_root") + "admin_panel.git",

    "uboot":
        Var("github_root") + "v2r_uboot.git",
}

deps_os = {
}

hooks = [
]