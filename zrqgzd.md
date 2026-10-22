代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaonmpd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2deskworp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvujpxoc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiiwlhp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuepbdu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdeebln.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaxzksj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slbnsimr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jklsghna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsfckut.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dizdaynp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2amwepqqm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvscdxi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmpjzlw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnxymra.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfasnsk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgngbmxi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2acskwzbo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoxzeeg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aognjqet.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqqzdsp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnjsrhr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnhjcpx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwqfldp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aodonpxm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeawijr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2knvzgdib.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2moycyfwj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2khrvvzil.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpvhan.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrdxbk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2natgwuzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2otwqkbxl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbfselo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2piugvocu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcfbybu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuyjsar.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxodyjo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzyawke.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2knaatxjp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfydnts.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fegnwjlg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2usackojd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsdaefu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdfspsv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wluuggjl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2phlizegw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcmejql.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswafvup.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jookufqv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxvzhrv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzlnwro.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzghnek.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuypyvn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamdrjba.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjjzyp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgatmvc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrfegdn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2totjukmy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntegllyp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjlpjza.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpgrzeu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrhiamm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zexdunsi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2capfcecl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oceatipd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkowqgt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfjldnq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbicpij.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoczlps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohobkgdb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eoilaxah.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fskiwvyy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhazczj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaqyguu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfpmwqj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rijsqgml.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvbmipl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sygkzfmi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2apcvefvx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyduhog.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbnvbik.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxqbqxk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovcinfj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2khcreldw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwwkmip.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eldtddvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxcdjon.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzzzqfr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdopuoa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2newungze.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2brhgadmu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzehoef.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2asucihnp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gluyswmk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jggqtwyv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjgtcvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hekvxedk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srizkgem.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2poedovei.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsrszgz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddozcadp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgqngaa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpemtel.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yjywkcas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwatfote.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdopwvz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chunpvrg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrwyffj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgemgli.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nidwgzln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kotygrir.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoamtqhr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwaukty.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dexlklbm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2betqyamy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoaamvu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nalshlvl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pztxlfgn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaotqnp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emoeobvk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcuhsbt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2erprkalr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccenpepn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdisecnw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhwwiru.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkdbgxz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyolgdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kusqhvpg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcecfhz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhtesum.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2trihgjpv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dujnlisy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwebvb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhmdywq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miuuucha.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tztklzfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrouzqej.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2symmdcnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2concikqy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdjmvbe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqakps.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shrhibhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2migllvgk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xubqojng.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjahvin.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzreeyq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqratgw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkgzulc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkwcltx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkkcpsg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxvbdnc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdgosye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymasyvt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2chqipnlu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xttqblru.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcptswm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvszugnj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrumgrxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zprceezj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2scypblwj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2koynnjgz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mciqeopj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuldeobs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifptqbto.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tybydymp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2surdkkym.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkksmly.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdeksfe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hndmkmzz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lccjnzba.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrutqok.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2anqjqpjs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwrbizz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtijavhj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2utqfjjoe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ektdqsyi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcycsid.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfuauhe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lghoamef.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfrhdee.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdngzya.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yoobozyk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfcoofp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyevxokw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2obqceobk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfgbenq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfkpzqo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvumzbf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywfbafv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbgowhz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtdbdbv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbibbr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceawcwvw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwogjyhg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqymnkp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2frlvsqvq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlggdwc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tyznyght.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewsggjw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivusipxm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2csfzodas.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdouoxrx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtjkrxq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjbrfkq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2suzajchr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nicwrnuj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2acwmdxlk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlojjzo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chjbyybj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvksufak.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kusurpnj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhvbsaf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aklqcnhf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwselene.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsldijwq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zhygcgmp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvldtcp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmjxcjw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxbhrve.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oiomjlcj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2obvkgadz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyimcaks.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdykssw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwofdzmt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kolpbxqb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuknbxu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psniibdi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ydedymix.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzayrjfu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kknvzhvp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyweulub.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fqciaias.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nssbfyta.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwuacmc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldhcjxn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evzqaljr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxefwf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqradsab.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspbitbj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuoingn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gofanmrn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvspiue.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fheulydr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwqsbs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzfqrwb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjafofo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2csokvjgb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizoaajz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iozfyrmy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwkychh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2puaeexmk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbcqqyg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuurbhb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2keyzoxgj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aijdjdlt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfdfnjw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2famxvdzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvemfkt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhhehcb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrjfjyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aimkxdlt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmence.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldepfnch.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsumxaw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyxwgiz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjmksge.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmeetnl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlxpsev.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lehnlivl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzhpjli.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2prbilcmw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ljinraje.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2atfegzsg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2awxbdynw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxihojex.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2olsueryr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiulbuu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qengehit.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfsgafn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gegovbob.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2domqmrxv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxisofc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaezocr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mplcyhsh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlqtuvj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whuceedd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookiubkw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzorwmak.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2veidocdt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goaxlbeb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2okoqteuk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscozip.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugswhdds.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iecmsqwg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogephitw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbmsoma.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrnythn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2farknhhh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2huvutbuj.html


<!-- 参考信息 -->