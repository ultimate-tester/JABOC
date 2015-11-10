# JBOC
Just a Bunch of Clouds

JBOC is basically the idea of creating a "JBOC" using as much as possible clouds or storage providers (think about Dropbox, Google Drive, Mega, Flickr, etc.). They all offer limited (free) space, so the plan is to bundle all this free space and get a total *huge* amount of space. Data will be automatically spread across the providers just like JBOD will do with hard drives. For simplicity there will be no redundancy, no fault tolerance and no performance gain.

There will be one main JBOC application that knows a few interfaces. These interfaces can be implemented by creating a "dynamically linked library" or "shared object". One DLL or SO will be the equivalent of 1 storage provider and it's extension should be jboc.

I am hoping that people will help on the project by creating shared objects for their favorite storage provider.
As soon as the interfaces that are required by the main program are done, the creation of shared objects can begin.
