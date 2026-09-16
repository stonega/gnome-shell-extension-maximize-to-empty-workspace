# gnome-shell-extension-maximize-to-empty-workspace
New and maximized windows will be moved to empty workspaces. Supports multiple monitors.

Supports GNOME Shell 45–50. GNOME 49 and newer use `Meta.Window.is_maximized()`;
older releases use `get_maximized()`.

To install the extension locally, run `sh deploy.sh`, then log out and back in
so GNOME Shell loads the updated JavaScript. Enable **Maximize To Empty Workspace**
in the Extensions app if needed.

Maximize To Empty Workspace is based on [Maximize To Workspace With History](https://github.com/raonetwo/MaximizeToWorkspace)
