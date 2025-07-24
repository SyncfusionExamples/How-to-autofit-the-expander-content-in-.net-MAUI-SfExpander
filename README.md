# How to Autofit the Expander Content in .NET MAUI SfExpander
This article demonstrates how to autofit the expander content in [.NET MAUI SfExpander](https://www.syncfusion.com/maui-controls/maui-expander). This example shows how the SfExpander automatically adjusts its size based on the content.

**XAML:**

Added Editor control to SfExpander content. To change the content size based on the text, set AutoSize as TextChanges for Editor control.

 ```xml
    <ContentPage.Content>
    <ScrollView BackgroundColor="#EDF2F5">
        <StackLayout>
            <syncfusion:SfExpander IsExpanded="True">
                <syncfusion:SfExpander.Header>
                    <Grid HeightRequest="50">
                        <Label Text="Veggie burger" VerticalTextAlignment="Center"/>
                    </Grid>
                </syncfusion:SfExpander.Header>
                <syncfusion:SfExpander.Content>
                    <Grid>
                        <Editor AutoSize="TextChanges" Text="Veggie burger, garden burger, or tofu burger uses a meat analogue, a meat substitute such as tofu, textured vegetable protein, seitan (wheat gluten), Quorn, beans, grains or an assortment of vegetables, which are ground up and formed into patties."/>
                    </Grid>
                </syncfusion:SfExpander.Content>
            </syncfusion:SfExpander>
        </StackLayout>
    </ScrollView>
</ContentPage.Content>
 ```

Download the complete sample from [GitHub](https://github.com/SyncfusionExamples/How-to-autofit-the-expander-content-in-.net-MAUI-SfExpander)