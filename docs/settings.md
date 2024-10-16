## Settings

QuestSystem ships with some settings that may come handy.

![Settings](assets\settings\settings.png)

| Name                                            | Default Value                                 | Description                                                                                        |
|-------------------------------------------------|-----------------------------------------------|----------------------------------------------------------------------------------------------------|
| quest_system/config/check_for_updates_on_startup | `true` | Automatically check for updates on startup |
| quest_system/config/autoload_script_path        | `res://addons/quest_system/quest_manager.gd`   | The path of the autoload script. |
| quest_system/config/available_quest_pool_path   | `res://addons/quest_system/available_pool.gd` | The path to the Available Quest Pool. Edit this field to override it with your custom one.         |
| quest_system/config/active_quest_pool_path      | `res://addons/quest_system/active_pool.gd`    | The path to the Active Quest Pool. Edit this field to override it with your custom one.            |
| quest_system/config/completed_quest_pool_path   | `res://addons/quest_system/completed_pool.gd` | The path to the Completed Quest Pool. Edit this field to override it with your custom one.         |
| quest_system/config/additional_pools            | `[]`                                          | An array that contains the paths for additional pools that will be added when running the project. |
| quest_system/config/require_objective_completed | `true`                                        | Whether `objective_completed` has to be set to true to complete a quest.                           |
| quest_system/config/allow_repeating_completed_quests| `true`                                    | Whether it's possible to start an already completed quest |