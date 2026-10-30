# Kerckhoffs's principle: why should a cipher's design be public?

*Week 2 · Essay 2 · October 30, 2026 · 148 words*

In 1883, the Dutch cryptographer Auguste Kerckhoffs published an essay, "La Cryptographie Militaire", in which he set out six principles. His second principle states that a cipher system "must not require secrecy, and it must be able to fall into the hands of the enemy without inconvenience." For example, everyone knows how a door lock works, but without the right key, the door cannot be opened. Similarly, people's assets must stay secure even if the algorithm behind a banking app is known. This is possible only if security relies on the key, not on the algorithm. The reason is simple: it is hard to keep an algorithm secret, but it is easy to change a key if it leaks. In fact, several secret algorithms, such as A5/1, CSS and MIFARE Classic, were broken. In short, Kerckhoffs's principle is important for system architects because it keeps today's systems secure.
