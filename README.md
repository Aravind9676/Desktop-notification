# Desktop-notification
from notifypy import Notify

notification = Notify()
notification.title = "TechSnap"
notification.message = "choose your carrer and start your project now"
notification.send()
