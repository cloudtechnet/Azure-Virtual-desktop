# AVD Golden Image Preparation Notes

#### 1. Create an Image from Azure VM

#### 2. Take Your First Snapshot
- **Details**: Capture the state of the VM at this stage to ensure you have a restore point before making any customizations.

#### 3. Customize Your VM
- **Actions**: 
  - Install required software and updates.
  - Configure system settings and preferences.
  - Apply necessary security patches.
  - Make any other necessary changes specific to your environment and use case.

#### 4. Take Final Snapshot
- **Details**: Capture the state of the VM after all customizations are complete. This snapshot will serve as the basis for your golden image.

#### 5. Run Sysprep
- **Steps**:
  1. **Reboot Once**: Ensure the VM is restarted to apply all changes properly.
  2. **Cleanup Temp Files**: Delete temporary files in the system storage to reduce clutter and save space.
  3. **Optimize the Driver**: Ensure that all drivers are up-to-date and optimized for the VM.
  4. **Remove Any User Profiles**: Delete user profiles to maintain a clean and standardized image.

By following these steps, you will have a customized and optimized AVD golden image ready for deployment.
