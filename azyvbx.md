代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2egjxkjdz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2spiidxut.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btnjyoyd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvpsahv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkgdmkh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yaclecry.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blbmpbuj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtajxtsb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaofkitv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xprdfhxh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjtoon.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcjcwgy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2odzxcqct.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wybacisz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uetwbgmj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtlnsbt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkmqcva.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tzciqwrd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kengmxkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgzgfub.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoccvwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glxioooh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqxowpl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hapxssrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgttwfyl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2klgzslcc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tybettvy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgzoosy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpwhkaa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwaudoc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qagehxuw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvythtm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnodycv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvymyqh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iaivsgbt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxgkxgo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2klcmhmtr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ytugnmec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhubnuu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfizwtte.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjldnru.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2djmrgvbq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2potmmnpb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscmdos.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2agygytvj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2umqftydw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsgmsa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiebtrof.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdwnqqy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpiczxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhstnrk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlhhqts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2abeisosm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iquaokib.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fddwpmih.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vewwrpmi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpndwpfq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zztarqqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoeuizn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awiytuyk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgexyucl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtacuxo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiqmtog.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2candpbuv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glplxxkd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cshehffw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mynhdxgj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2enbjrpcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekdpanq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmmvtsl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmkgxvn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oigxjvmb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqgvjkd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2koribyyo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hakucdif.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qasveypb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uccfgwhu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgesldh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwuxvtt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oraxpaut.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggldrpoe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssftxxqq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmrdofm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pyafspyq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmfbbxv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cefvqtjp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfotepr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uytrhmfn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2toxepqen.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpiolz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcczunqx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aesmzoxu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2suiivqco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiyulgf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbgdrfs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtpcspt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hefusekc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfsvoen.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzsopbz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfryrtz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfwjdzr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyphmge.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfvnyov.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvigeohu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crruezsc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2quvtvpce.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjnglbe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhwwilt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfaocyu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbbdeck.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esogcdxx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjutnwkh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjahmyg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sznazvgc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2siuwhtra.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybibemff.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgkyouu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvtcidx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgnvfgi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoobeva.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hxisydfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginvrurb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyldbcn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhmyevy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaawadw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsxjaur.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yizyzygh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyxlqxw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrzgehm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvijrcoc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkgcikq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrplvll.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odyiecau.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzrqqfk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nicjztmw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdhxfmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmzriml.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkpbvko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxipkbck.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzlhjuc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqshiepb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mupfhsgy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfswyeoq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdqoscz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbbhvsz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xeboabgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpolnigb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiumxql.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2njkortpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usmxxqrp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmmlpfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uanoszmm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smhmxxly.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvknzdp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbghbnn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aimoddfo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpmsmgp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxqykjp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzvarlx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oopmavus.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmemoau.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zcndlrmd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqlxddh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyleydy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpobhdoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxisnsj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rioejwcq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqimcnkk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqrmlfa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2liufxdha.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2slzlgoqt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2evoulfdq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vykoftbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wslhvrhf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xegvkswj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmydjk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqkxcmc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2niceqqaw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2udivskqe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnnlulc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pczzmrge.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqffeisr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rexzfqgy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oktmxhap.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofilkp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlfpmdx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxyombd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgcyyhm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2labkzgsq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqgxly.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvgubp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtarirc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkmqrqi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfqtdej.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hibdkrho.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqvwuy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcygknae.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivtiwo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eychtdbq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgveupdn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhgiupk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxuzsws.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjaxjmj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zushnbcd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxoijvn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszdjupu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ulllitvf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kupygnob.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsbkzfv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2urngrvlf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uocjnsze.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkxfnh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwvzidt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qijqfikp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hccrphgg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qlikzfrc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vebwljnl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2edcqeydu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnirxyhb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iskcekof.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdnoyvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2knpzrivh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtehfqxg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qulvjojn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cudajtth.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2grjszpgi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2maaqkkyj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvytbigb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcpzlld.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbceejrz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvdeiwp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkhnzan.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kommqoxc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmvhleb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsjccje.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfwdkdh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvbznkj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fanmbqsi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdynsce.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdzbclv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvvtjeq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thrjwqcu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfgenyy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdscttbv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrvnwbz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbymwkkx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2naxsipsg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxlomum.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itesinvh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lypkgujb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtivuob.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pknsnlzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luyygawz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eznrobfp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaitpzw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dckjveob.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuyciza.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyneosc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyjmtyk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuhcccr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnzlmag.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejinsetl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwxvlcb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfttetpz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjkfefs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzyctcx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalouzxz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jawwvqfe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbppmqb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmivcnn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpipmghq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2igkecrpm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsyfjrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmbaqfr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2offamyba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyqxhmp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qofzdsch.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtgstzy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rydbzhhi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugubyqyx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdigwigw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkkyoby.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbohmop.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqlozuu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzouzjm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyalvxbm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2muysntly.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxycnltp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bppvxtqx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2leolomhi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gleetgbe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2chepolmx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkaujyb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrttsduw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eoldfwld.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehroqcbl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2knjkonya.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgefspa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiiruyi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmrqksd.html


<!-- 参考信息 -->