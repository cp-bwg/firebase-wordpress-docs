.. raw:: html

    <style> .red {color:red} </style>

IF-PRO Plugin Configuration
=============

.. role:: red

:red:`Please deactivate and remove the Free plugin before installing the Integrate Firebase PRO version.`

Download the Integrate Firebase PRO plugin
----------------------------------

There is a FREE version of this `Firebase WordPress integration plugin <https://wordpress.org/plugins/integrate-firebase/>`_ that you can find in WordPress plugin site. You can give it a try, however, the application is very limited. If you only want to interact with Firebase through WordPress frontend only, then the free version would be sufficient enough.

So, if you want a more secured and advanced feature of the plugin, support the development of `Integrate Firebase PRO <https://firebase.dalenguyen.me>`_ version.

Prepare Firebase Credentials
----------------------------------
Before using the plugin, we need have the credentials from Firebase Console. You can get it by logging into https://console.firebase.google.com. 

After signning in, you can navigate to **Project Overview > Project Settings**.

.. figure:: /images/firebase-project-settings.png
    :scale: 70%
    :align: center

    General configuration

In General tab, you can get the config at the bottom. If you don't have any app ready, you can create a new one. 

.. figure:: /images/firebase-create-web-app.png
    :scale: 70%
    :align: center

    Create a Web app

After creating a web app for you project, you can save your credentials for later usage.

.. figure:: /images/firebase-credentials.png
    :scale: 70%
    :align: center

    Firebase Credentials
    
    If you forget to write these down, or need to see them again, this is how you can find them again:
.. figure:: https://public.boxcloud.com/api/2.0/internal_files/700605394260/versions/744341976660/representations/jpg_paged_2048x2048/content/1.jpg?access_token=1!73BGNokya1YhUElCkWDOiEQpCUdGdzcxJGTs3s3oDKoEPI5PRfGgz7l-ydkiPzTerDifhYwFoyJSs_koJGArWkHT9uiqjKR9saCpjgXoktzDqim-Nnh-u21XuMRc22Uh8jyuMiR_W7pS4gvOxdzE9V1mQPCY7Nhz3r99odhzZmbLcXPLutrhv9tEdCnw5UyBC88hxCVqjUXTm0LqAUV4jLnrg7RRtEr3Sv3_IeoevQwUV4AmJ_0RS7MzLGtQYMqOmkxDV_WqhkYLJESJ1Ys9ejpbpESyD42KFAD794uon3qzSG7CkRHzxlSkdBUgnx2uweVhjgzzObor729qZKfs9_EVZ689-kT-V7_OYZj6UbbS5pEX5iV-Fwe5DOZh9urwd3ymY8I_mWinL9sad_gX5L6rjK2VBxGRQ0cRvgCzgyr2CgL5buStO1qFCICzx_S7qRQhexDxxVVxlOWm7VfEQtSYPaMcbSS4Aw_cVms4qh8f21vS7kXwD3l9iGdV4foOXsz2SK0Ouw0FCfYYAz3JXKzsqX2v_75biPA1lZB-z19sYrwioATwH4mkIAt0ehw.&shared_link=https%3A%2F%2Fapp.box.com%2Fs%2Fme26nq9pny8rqcx5btdqk1r8h7ukd3bg&box_client_name=box-content-preview&box_client_version=2.48.1
    :scale: 70%
    :align: center

Installation Process
----------------------------------

After you have downloaded the plugin, uncompress the zip file in order to install the plugin file (**integrate-firebase-PRO.zip**). You can use default installation process in order to install the plugin. Otherwise, you can always manually upload the plugin to your plugin folder through FTP client.

After you activate the plugin, you need to enter the Firebase credentials in the **Dashboard > Firebase**.

.. figure:: /images/general.png
    :scale: 70%
    :align: center

    General configuration

After that, you can create login form, show data, show logout button… on WordPress frontend.

Select Firebase Services - Optimization
----------------------------------

With the new update since v1.1.0 you have to pick the services (General Tab) for optimization purposes. I have choose either Realtime / Firestore or both of them in order to interact with Firebase Database on the frontend.

.. figure:: /images/general/firebase-optimization.png
    :scale: 70%
    :align: center

    Firebase Optimization
