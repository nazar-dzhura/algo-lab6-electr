# algo-lab6-electr

Electricians
    Your company operates an electrical network in the village of Vilshanka. The condition of the tender was the involvement of local craftsmen,
    and you had to agree to that. These masters are unique, and as a result you put / buried N
    poles / electrical supports that are at a distance w from each other. The problem is that the exact height of each
    support is unknown - you only know that the height of the support i is within [1, heights [i]], and connect the wire
    you can only to the top of the support (there is already installed the necessary equipment).

    You order an electric wire to connect the poles from China, and it will take a long time to go / swim.
    You do not know exactly how much wire you need (it depends on the specific heights of the supports), so you want to order exactly as much
    how much will be needed for the worst situation.

    (In other words, you need to find a sequence of support heights that the wire that connects their vertices will be the longest)

        Incoming data:
    The first line contains w - the distance between the supports. The second line contains N numbers that describe the maximum possible
    height for each support (ie it is an array of heights).

        Output data:
    The maximum required length of the wire is up to 2 decimal places.

    Limitation:
        w, heights [i] are integers in the range 1… 100
        N <50
    Of course, you should ignore the various physical limitations of wire sag or wire connection costs.