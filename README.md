# terraform-azurerm-rgsapip
module "sa" {
    source = //terraform-azurerm-rgsapip
    saname = "tesrerrtrpy"
    rgname = "mdorg"
    loc = "east us"
    act = "Standard"
    rt = "GRS"
}
