# Laravel Colletive Forms + Bootstrap Snippets for Sublime Text

Handy [Sublime Text 3](http://www.sublimetext.com/3) snippets to create forms inputs for [Laravel Collective Forms](http://laravelcollective.com/docs/5.0/html) with [Twitter's Bootstrap 3](http://getbootstrap.com/).

## Usage
When you're editing your view in Sublime Text, type the snippet shortcut then press `tab` key.

## Installation

- Via [Package Control](https://packagecontrol.io/): search for `Laravel Forms Bootstrap Snippets` then click/tap…wait a sec and tadam!

- Via Git clone this repository into your Packages folder:

    git clone https://github.com/redgluten/laravel_forms_boostrap.git


Or download the snippets zip file and unzip it into your Packages folder.

## Available snippets

| Shortcut  | Result |
|-----------|--------|
| ext		| @extends('`name`') |
| lay		| @layout('`name`')  |
| sec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @endsection    |
| secy		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @yield_section |
| yl		| @yield('`section`', '`default`') |
| lsec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @show |
| par		| @parent	|
| !!		| {!! $`var` !!}	|
| }}		| {{ `escaped output` }}	|
| inc		| @include('`view.name`', `array('some' => 'data')`)  |
| if		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @endif   |
| ife		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @else <br /> **{{-- expr --\}\}** <br /> @endif  |
| foreach	| @foreach(`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforeach  |
| fore		| @forelse (`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforelse  |
| for		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /> **{{-- expr --\}\}** <br /> @endfor  |
| each		| @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| trans		| {{ trans('`language.line`') }}	|
| route		| {{ route('`name`') }}	|
| asset		| {{ asset('`path`') }}	|
| while		| @while (`condition`) <br /> **{{-- expr --\}\}** <br /> @endwhile  |
| unless	| @unless (`condition`) <br /> **{{-- expr --\}\}** <br /> @endunless  |
| choise	| @choice('`language.line`', $`number`)  |
| comment	| {{-- `comment` --}}	|
| lang		| @lang('`language.line`', array('`variable` => '`replacement`'))  | 
