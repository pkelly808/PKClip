function PKClip {

    Remove-Variable Clip -ea SilentlyContinue

    $Global:Clip = @()

    Get-Clipboard | Where-Object {$_ -ne ''} | ForEach-Object { $Global:Clip += $_ }
}
