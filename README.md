# NAME

Voson::Plugin::View::MicroTemplate - A plugin for Voson that provides template mechanism

# SYNOPSIS

    use Voson plugins => [
        'View::MicroTemplate' => +{
            include_path => [ qw/ view / ],
        },
    ];
    

    app {
        [200, [], render('index.html', { name => 'myapp' })];
    };

# DESCRIPTION

Voson::Plugin::View::MicroTemplate provides render DSL for rendering template.

# DSL

## render $template\_file \[, $hashref\];

Returns rendered content.

# LICENSE

Copyright (C) ytnobody.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

ytnobody <ytnobody@gmail.com>
