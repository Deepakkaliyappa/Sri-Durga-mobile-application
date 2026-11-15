after coding...

building apk in android studio:-
1) create folder = sd-billing-apk
	    inside-create folder = www
		                 * paste- all yourcode
    *in sd-billing-apk folder- package.json, package-lock.json, capacitor.config.json this three package should be there
    *if ready to build- goto step 2

2) in the same sd-billing-apk path
	*run-commands:-
		(optional)	npm init -y 	
		(optional)	npm install @capacitor/core @capacitor/cli @capacitor/android 	@capacitor/app 
		(optional)	npx cap init "Sri Durga Billing" com.sridurga.billing --web-dir=www
			npm install	
			npx cap add android
			npx cap sync
			npx cap open android
   *android studio opens (if you downloaded alredy or else download)
   *In right side bottom importing everything- wait untill its completes
   *after finish file structure comes like apps, capocitor android, capocitor app....etc

3) create logo icon:-

                step1:- Open the project (npx cap open android) and wait for the import to finish.
	step2:- In the left panel, right-click the app folder (top of the list).
	step3:- Choose New → Image Asset.
	step4:- For Icon Type, leave Launcher Icons (Adaptive and Legacy).
	step5:- On the Foreground Layer tab, set Asset type to Image. Click the folder icon next to Path and choose icon-foreground.png.
	step6:- Open the Background Layer tab. Set Asset type to Color and choose white (FFFFFF).
	step7:- Check the preview. The logo should sit inside the circle with a small margin. If the edges are cut off, go back to the Foreground tab and lower Resize a little.
	step8:- Click Next, then Finish. If it asks about overwriting the existing icon files, click Yes.
	step9:- Rebuild with Build → Generate App Bundles or APKs → Generate APKs.
	step10:-Uninstall the old app from your phone and install the new APK. Android sometimes keeps the old icon until you do that.

4) Build app:

	step1:- Click on threee lines, select Build
	step2:- In that Generate App Bundles or APKs
	step3:- Generate APKs (wait untill its completes)
	step4:- after finish locate file location
	step5: copy and paste apk to mobiles
	step6: finished