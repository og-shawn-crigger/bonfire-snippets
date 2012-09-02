# Bonfire Snippets for Sublime Text Editor
 
Just a random collection of Snippets I use for [CI-Bonfire](http://cibonfire.com) development in Sublime Text Editor.

Feel free to fork and add your own to the mix

## Installation 

Currently installation is manual via GIT,  Sorry I have no clue where Windows stored it's Packages but I'm sure a quick google search will find it for you.

- Mac Installation 

	git clone git@github.com:svizion/bonfire-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/bonfire-snippets

- Linux Installation

	git clone git@github.com:svizion/bonfire-snippets.git ~/.config/sublime-text-2/Packages/bonfire-snippets



## Current Snippets

These are the current snippets I've included, left hand side is the trigger, right hand side is what happens.

## Template and Assets
<table>
	<tr><td>set_data</td><td>Template::set();</td></tr>
	<tr><td>render</td><td>Template::render();</td></tr>
	<tr><td>toolbar_title</td><td>Template::set('toolbar_title', '');</td></tr>
	<tr><td>clear_cache</td><td>Assets::clear_cache();</td></tr>
	<tr><td>add_js</td><td>Assets::add_js();</td></tr>
	<tr><td>add_css</td><td>Assets::add_css();</td></tr>
	<tr><td>add_mod_js</td><td>Assets::add_module_js();</td></tr>
	<tr><td>add_mod_css</td><td>Assets::add_module_css();</td></tr>
</table>

## Various Randoms

<table>
<tr><td>cur_user</td><td>$this->current_user->?;</td>
<tr><td>bf_model</td><td>Generates Bonfire Model Skeleton Structure</td>
<tr><td>auth_controller</td><td>Generates Authenticated_Controller Skeleton Structure</td>
<tr><td>haz_perm</td><td>PHP If Wrapper for has_permission check</td></tr>
<tr><td>restrict</td><td>$this->auth->restrict();</td></tr>
<tr><td>log_activity</td><td>$this->activity_model->log_activity($this->current_user->user_id(), '', 'module');</td></tr>
<tr><td>settings_set</td><td>$this->settings_lib->set();</td></tr>
<tr><td>settings_delete</td><td>$this->settings_lib->delete();</td></tr>
<tr><td>enable_profiler</td><td>$this->output->enable_profiler(FALSE);</td></tr>
</table>


## Follow me else where

 - [Twitter](http://twitter.com/svizion)
 - [My Blog](http://blog.shawnc.org) 