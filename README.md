```kotlin
data object StepanSamutichev {
	val name: String = "Stepan"
	val surname: String = "Samutichev"
	val telegram: String = "@Samutichev"
	val email: String = "stepan@fuco.cc"

	override fun toString() = "$name $surname"
}

fun main() {
	println(StepanSamutichev)
}

```
