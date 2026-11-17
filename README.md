# PayME-Miniapp/Specs

CocoaPods spec repo for the **PayME Miniapp iOS SDK** (`PayME-Miniapp` pod).

CocoaPods trunk stops accepting new versions on 2 December 2026. New versions of `PayME-Miniapp` are published here; every version already on trunk is mirrored here too, so pinned versions keep resolving.

## Usage

Put this repo **before** the CocoaPods CDN in your `Podfile` (CocoaPods takes a pod from the first source that has it):

```ruby
source 'https://github.com/PayME-Miniapp/Specs.git'
source 'https://cdn.cocoapods.org/'
```

Then keep using `pod 'PayME-Miniapp', '<version>'` as before. See the [native-ios README](https://github.com/PayME-Miniapp/native-ios) for the full setup, including the required `post_install` block.

React Native (`payme-mini-app`) and Flutter (`payme_miniapp_flutter`) users do not need this repo.

---

Repo podspec CocoaPods của **PayME Miniapp iOS SDK** (pod `PayME-Miniapp`). Từ 02/12/2026 CocoaPods trunk không nhận phiên bản mới; các bản mới phát hành ở đây, các bản cũ trên trunk cũng được chép lại đầy đủ. Đặt repo này **trước** CDN trong `Podfile` như ví dụ trên.
