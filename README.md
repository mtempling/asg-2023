# asg-2023
This is an [OWEL](https://github.com/Ericsson/ove) for [All Systems Go! 2023](https://cfp.all-systems-go.io).

# The oneliner

    curl -sSL https://raw.githubusercontent.com/Ericsson/ove/master/setup | bash -s asg2023 https://github.com/mtempling/asg-2023

The above oneliner is short for:

    mkdir -p asg2023
    cd asg2023
    git clone https://github.com/Ericsson/ove.git .ove
    git clone https://github.com/mtempling/asg-2023
    ln -s asg-2023 .owel
    ln -s .ove/ove ove

# Setup the environment

    source ove

# Watch one talk

    ove asg2023 <tab><tab>

# Watch them all

    ove asg2023-all
