# Deploying 
INSTALL
https://cloud.ibm.com/docs/cli?topic=cli-install-ibmcloud-cli
https://github.com/cloudfoundry/cli/wiki/V6-CLI-Installation-Guide

1. Git clone existing repo - DONE 

2. Delete package-lock and yarn.lock - DONE

3. Create .env .cfignore manifest.yml - DONE

4. Update model pointer - DONE 

5. Delete package-lock.json and yarn.lock and npm install - DONE

6. Build app - DONE
    npm run build

7. Log into ibmcloud cli - DONE
    ibmcloud login  
    ibmcloud target --cf
    ibmcloud target -r au-syd
    ibmcloud cf push tensorflowapp 

9. Login create VCAP variables - DONE
    
    ibmcloud cf logs tfcvapp