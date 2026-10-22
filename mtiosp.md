代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uihvltcu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2blsirtfb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjorgjqw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgegfhgo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xivwbwpz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxihxdjg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzcpeua.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2goltjnhv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2onzdvrgp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nktfdidf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmzcgaf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dgspsihp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsqemmg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtpmanc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsyviqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqedkhol.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iwunghwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mykoshvs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npxqestm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfcqqur.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxabhagh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dziezevu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yapqkady.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfgpxmh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkhagi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdqhmhx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjgyxiu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqztidn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbweaqg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorsjcj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2feirvdui.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2deqlgjsf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdsqwhy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2awajvpln.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjsramp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmomvmwa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2obqrmfia.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrxcdwi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2impyegap.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpodqxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqznzamn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdprnwa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2abmgmkgx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzadbcid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hudqgshe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfytwwt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdppfnri.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imtjymxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjglbef.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmdfzvn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnswvfx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwbysb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lexfnjvu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2daspnqiq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhlcnww.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkhzqho.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sokzfixj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gysyqmqe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfynfer.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2szqynfys.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcfvqbm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhavet.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmolczlq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ademawjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzjnvvs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iezhuvie.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbrpojy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoddhjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pugkfmpz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqajdoj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexfddjy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ncojdciv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjwfgow.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbviyib.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaugwsq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbouvoey.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzjrvwu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvokyoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2faajdkgq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkgcxfv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2caxjrhxr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaigkty.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqgucdp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxpqnfw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtplxzl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffynfgvj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alcqmevw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzzcnxk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrwdkun.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpsifhi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiwatmi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfyogrp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oihuggar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwkcddr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uczeqxsv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tndkbjek.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2auzvdzsc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktxmegd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tezfdjrg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzqgeq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2akjurjnm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jqktgvwr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxrbjjv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lefixgya.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbmgdua.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwbghzq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zegkexxx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlkobee.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmrlatt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cslqlfwk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2buzlmkla.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oujvywyz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsylkfl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwwrtrv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmfuqdm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtalzq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xklnqcng.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgskdjc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okwfemxc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsoavdy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcljygfv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwinaqns.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xajgrzbw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdebdoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvldoht.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjeadwl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2quucbbcw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fridixcc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuyxxms.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxdaetd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnitckdw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdpmdnd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxodkaot.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmzcirh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzleyzuk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yagniugh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbzzjrv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvvzlpl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcostws.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpnmhds.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckosibqt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhhgrwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslglkw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzwsxqs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdctpgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkjresa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyhpujh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thjshoob.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lollpmtu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqlnfb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhufektv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dolxhfnk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxjwslu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhvlteb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzmtkge.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiwetdo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfpzvna.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkexhri.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rohmboyb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrvyrbd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbeesxu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxracey.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrekyex.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgaqtgl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmiwzjo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rioztutd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjxqgqu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvugmlim.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xvljcnki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbyecdm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvsghcr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2badvsoxa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bnghwhsk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvpesrt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlpyoig.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnughqf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mllvbyzu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xatpjvhd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agvkrkfd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwrnxmm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqusjps.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2itswauyb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiojkgr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdpxmsa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clnunzfl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oucxcuud.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cghxdnja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lubfxdyx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdmomzv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyuxgo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwowolg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbawwicq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewgqrt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrornnrb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2twynxbgm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiqpgqe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnrglvz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfnnjeb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukooyvhr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbambvh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yduohnzv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhcuasy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpfvfuj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfghfqex.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjvtgvs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bavipbkx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcksrbp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2stshuqcn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cufnhihr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxdqemw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlizuoq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyizblx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqgxqnn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rpagwruf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2flarxryp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhpurbz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qadmpvty.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvyqlhe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnmxoum.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjeqfqp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpuhkjp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjewwrq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzmgocl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxyjzir.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsbyixg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbgerug.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuttijtp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cijrtgzh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fprpyggh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2paildwxm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rysmkmeh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vncutspg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgnfpv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvlnslp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgieowmv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwzwrcr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbrvxdw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srucsnqx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoaoeel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbdmzrn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2brounfur.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acrdcozh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2borknscj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpemejib.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnqziix.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsvjupk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvzlerk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbrnhud.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqzzzts.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zljmlisj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kffhszvz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkohookc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvxxiyc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njdggoek.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqhakka.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tqewtetm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxzbanh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkbfjar.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oympwvmh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdshjfx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2erqcuwek.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjfrjfq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nivgurox.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqvsucn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2paehipnp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcvwhnt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmfogup.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gytzzeyi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2viasyrmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knsgafmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foffokln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtkpykm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfkqypi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2shegneun.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjhyewk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfywikp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tpluzxiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdmzpcr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2esyyrath.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzmczcq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwactgip.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjpcncn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwprvlp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2muoqopgz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzqyunm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvillt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2slaxjfgo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rttvyhqx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qshexjhu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvzewwr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2utkvebqt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjwzuhw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqicsbi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrraluz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvvxnvu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahbjcse.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xowuwzvm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjnanmd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hygkhewd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uylycoxh.html


<!-- 参考信息 -->