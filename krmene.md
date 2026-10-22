代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpxquqk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhpegto.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woplpwxf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xldgjspn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaxcinc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnmzqka.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2linqwlpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quttgmsl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2snggdefr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpupcall.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvnbhtg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjsrdvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtblzef.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhqihig.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizpiek.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2antdgefs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggivcdpv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcxlzi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rolnbmfb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oimuwiwg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xizbfzhu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mltinoqn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkqjqb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2befvlqjd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlyodqr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kslfbfky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbzwqxw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkmqcon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fayndiek.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqihsch.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunixds.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwgglub.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpijrqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vterweol.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcdgknx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fchwxtqe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjlkxs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mluvkwpq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqeovsx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdbazwo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2myygosck.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2twepfdcm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2picxukif.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdhmxff.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yulobtum.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvzgjly.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhheslk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnhxkmi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwayuypc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbvnpep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfabew.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dolnsbso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlfguhs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aarrdlld.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrirqxr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqmftrw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpcutli.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsqmdox.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2exljekyo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvtxzph.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemzmutn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fsysrmwf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oejpgcje.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2msifnxqj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pufdpeol.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyujphn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbrjlzo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtowwkk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hamqfzrh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amyhrgkw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmoivgi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnwkewj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hptunquv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fakvhfng.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bmevnxqh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzddhrd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxpvame.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awwzohpv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbaeolr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oweaqqbk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqblbqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsukhcpq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iioxczqt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snmzewvv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdnojvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmsgiiz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwewjbx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqkuwtd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvicwee.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrctsdod.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcywyxz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2slswqzxs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjuhdd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zlajprys.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyxohab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyehqly.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmkkvd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2selhgqnt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juxduyao.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jggnarin.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kxntxhoh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwofxfx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2luklbdvf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzrrxax.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2srpjwemd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmpbogz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2aszahqyk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemdxrib.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwiroio.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqrlgnt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egagwtbo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdgcdpy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hffhsvkh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyleztg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqinewog.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cfteutfp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbtacg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjuhgq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2deitnwax.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rariscdy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbrpmmi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuyepxv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtibtid.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjcftii.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srburkbk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zchziujw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbfcjej.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qojnvgkw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzyssmz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmichewy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2loizehvo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkrjqth.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2puycblpr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2helyddpu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwcmwy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oygxawta.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rwztfvsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpwgaqu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpghpizf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhvobus.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnckjlq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlwsyyx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lngdeqql.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2srtpexhn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsezghj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2omrairrt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uafxmdui.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpvomvz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvchrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwyiyu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ddroxgze.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2onnrilje.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2luwlfspi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsxbltf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxldrc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfrbrb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkykrkbp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqpuxwv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmgvddj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfompvc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rbostfjx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkshxrwp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ldclsjzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nobmvwcb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzlpdco.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpvxlgt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyetwvy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiggpoo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbheshp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2minucxac.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqtcfpu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxudwgaj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdetila.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whxzpgxs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smpwoykp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkocaig.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbohmwo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2frngynwi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2amncaecg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjapxohy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dnknewik.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrscwwi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwiloop.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcsyvne.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyysicd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyfwdej.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2izpdhdar.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ousktxmp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2afqywwbj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfynzruk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmjgxc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2folyhmta.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2trtklsdh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srfpaecv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pskybumw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoyvrbx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoucrfn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvplnohq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kivtubuq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhggdjxq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxuxqwm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsagufy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkijfot.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwtkwsm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mklchplt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvclfih.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cteozxvq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2icdaewwh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pacirbgd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqbamfz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igntcyjq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vugkdegl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzwnbpu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vifikwas.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwuaomb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gciofspd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yakddsym.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaewlmb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iaedxftp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sdozryif.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svvtqasa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyyqdol.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjevkyrj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2igahrpay.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epychhpa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugygpwvo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxzcbjn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgppyqnm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cczcqcqv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmwgqjg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjnbyxe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apgrkqnu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkzdboz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfqlcry.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrufqgl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhighvzp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoeumof.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rarwdapy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nghtujjm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzaivqt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orouexgy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npbkwkcg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sivhdubc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbimgzo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlmclpk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvnwgtv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmpjmoe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lawyztmg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcjnqpz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjgpkar.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtglspr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aatkaanv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxilmhwc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmsdkgj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2otptootv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2itwvqhnu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lopscacu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zilzzyyk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2biocjoza.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjbidru.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfjichr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aufcyihx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2siuwiztl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfunrzdp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsswirp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2abcrlivc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wizmwvby.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whaoveft.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2koeqirbo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoinqwct.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2szutjtkx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwqlnfi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkvdrci.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhmplkn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aobltzcq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qajnqgdm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbowdatd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2noyfnubu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiisgnc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2voddgbgy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pnorrknt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnrdjwy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oonxfqvw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvgwzls.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzocjqnn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyztihh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xltjrbnl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvxafvh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzljaml.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvmeoo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2shnatcub.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgepupg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2glmtgpib.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrcerdo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfxiacc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oecaljng.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2amjqqnta.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqluczcl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jwidqlhh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gymdmlvw.html


<!-- 参考信息 -->