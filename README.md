# WPF-Subscription-Manager
A WPF MVVM application for managing subscriptions and payment reminders.
# Subscription Manager

A desktop application built with WPF and MVVM architecture to help users manage and track recurring subscriptions and billing reminders.

---

## Features

- Add new subscriptions
- Track subscription costs
- Choose billing cycle (Monthly / Yearly)
- Enable or disable auto-renew
- Display next billing date
- Payment reminder system
- Automatic UI updates using Data Binding

---

## Technologies Used

- C#
- WPF
- MVVM Architecture
- ObservableCollection
- ICommand / RelayCommand
- Data Binding
- DispatcherTimer

---

## Project Structure

- Models
  - Subscription.cs

- ViewModels
  - SubscriptionViewModel.cs

- Views
  - MainWindow.xaml
  - AddSubscriptionWindow.xaml

- Commands
  - RelayCommand.cs

---

## How It Works

1. The user opens the application.
2. Active subscriptions are displayed in the main window.
3. The user can add a new subscription using the Add Subscription form.
4. Subscription data is stored in an ObservableCollection.
5. The application automatically updates the UI using Data Binding.
6. A reminder system checks billing dates periodically.

---

## Architecture

This project follows the MVVM (Model-View-ViewModel) design pattern.

- Model → Stores subscription data
- View → User Interface
- ViewModel → Handles application logic and commands

---

## Requirements Implemented

- MVVM architecture
- Two forms/windows
- ObservableCollection
- INotifyPropertyChanged
- Data Binding
- Shared ViewModel between windows
- ShowDialog() navigation
- Reminder system using DispatcherTimer

---

## Future Improvements

- Edit subscriptions
- Delete subscriptions
- Save data to database
- Search and filtering
- Notification popups

---

## Author

Developed as a WPF MVVM course project.
