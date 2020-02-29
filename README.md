# Eigen_Bazel_Example1
How to build a simple Eigen Example with Bazel from Eigen Sources 

# Run 

## 1. Install Bazel if needed 

```
apt install curl
curl https://bazel.build/bazel-release.pub.gpg | sudo apt-key add -
echo "deb [arch=amd64] https://storage.googleapis.com/bazel-apt stable jdk1.8" | sudo tee /etc/apt/sources.list.d/bazel.list
apt update && sudo apt install bazel
```




## 2. Clone this repo 

```
git clone https://github.com/NicolaBernini/Eigen_Bazel_Example1/
```







## 3. Run Bazel Build 

```
cd Eigen_Bazel_Example1
bazel build //...:all
```




## 4. Test 

```
./bazel-bin/example/EigenDemo
```

Expected Result 

```
3  -1
2.5 1.5
```




