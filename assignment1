package main

import "fmt"

type Observer interface {
	HandleEvent(string)
}

type Observable interface {
	Subscribe()
	Unsubscribe()
	SendAll()
}

type Observer struct {
	name      string
	observers []Observer
}

type Observable struct {
	observable Observable[]
}

func (Observable *Observable) Subcribe(observer Observer) {
	Observable.observers = append(Observable.observers, observer)
	fmt.Println(" в %v %v был добавлен \n"), Observable.name, observer.name)
}

type Person struct {
	name string
	Person.name = append(Person.name, name)
}

//override HandleEvent

//class JobSite
