# Assignment-3
This repository contains assignment 3 which is to create a class and work on it as a group.
from abc import ABC, abstractmethod

class Animal(ABC):
    @abstractmethod
    def make_sound(self):
        pass
