<Window x:Class="BindingApp.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:BindingApp"
        mc:Ignorable="d"
        Title="MainWindow" Height="250" Width="300">
    <StackPanel>
        <TextBox x:Name="myTextBox" Height="30" />
        <TextBlock x:Name="myTextBlock" Text="{Binding ElementName=myTextBox,Path=Text}" Height="30" />
    </StackPanel>
</Window>
