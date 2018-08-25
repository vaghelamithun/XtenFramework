public abstract class CoreBaseActivity extended AppCompatActivity

Contain dailly basis uses methods and easy setup of fab button, progressbar and managing replace fragment related functions 

#### Public Methods

 | `protected void onFabClick(View view)`  | Handlle the FloatingActionButton click event                                |
 | Content Cell                          | Content Cell                                                                |

| protected void onFabClick(View view) | Handlle the FloatingActionButton click event |
| protected int getFabId() | To initialize the fab button, return fab resource id |
| public <T extends View> T _findViewById(int viewId) | finding view by resource id, no need to cast |
| protected abstract int getLayout() | Return layout resource id to set content view | 
| public abstract View getRootView() | Return root view id to visible snackbar | 
| public int getProgressBarId() | Return progressbar id |
| public void replaceFragment(Fragment fragment) | Call to replace and add to back stack fragment |
| protected int getFragmentContainer() | Return fragment container view id | 
| public void showSnackbar(@StringRes int resId, View.OnClickListener listener) | Visible the Snackbar, resId is text message |  
