代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfxonrk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxsqjr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxjbhv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqhwxbz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2evlmnntf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynahuuyp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlisrwts.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2msloiaid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcpumap.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtoxsl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwkdaoi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiqhevr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbcyfm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2taayjhro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meyegsch.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmdwwyb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pamwzuls.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sylefnie.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhbaosb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2caaxoliy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjqqtyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvirromy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vasrfziu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wattuzbm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuyowmj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gakgcxmb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxxqqoi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2clgptwbl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeadfon.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bktelujx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wllgrmmr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iyukfsty.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjddcwnq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwvbhmc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kykunggk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2csxmjrji.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tecsyubd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjnmovz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mirjvqlo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pitpbmon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uftwvrxu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwmaftl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmklccj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aizltqmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcxnoso.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlaksvf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsboije.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ethymtaj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiagbwth.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kswcnrfi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bssmpclb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nsonkala.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzeqjeh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsxwsoy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmwgclc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kckuflvw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbezpulz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsokykj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wilhhdtl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaesxmfz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpjkfjw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhnygpc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cswkhrih.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zskgpacu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fauhfxum.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoufhae.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadpqqxr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybllcimv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2honlqqwq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcteamu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbxlqfj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uovidwnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xomjhjhw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrzrmhd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzcfefx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2umsyhjwy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2piixwzxg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkmffsg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2stekouov.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxquut.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbyvvx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uduhyubl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgkxdnz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2musgbzzr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoablrh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ompndzne.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpvzdqa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cnixlcpl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2muqeqaau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otpxybxi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2isrhdazd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwupsjy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wikbjwyg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxylhsz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyindnq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnugwbns.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ngacuaox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxnssfn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jczidyju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdefhgec.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbkoviv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxzvuu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzhwhww.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqqkxhf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zexkqgne.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqrrutk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2waszzrxl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2euuobfjz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeendst.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yndqpjty.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcganchs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfisnrs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbuvgtd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kngttkou.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jcevpmcb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elcluosg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hnduolyr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfvezix.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wzccrucj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyznqbl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvdryv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ormsvarr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbkfusw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2flqyyzpc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejmegh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcxosgo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nintzyvf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uypvapgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nobspmeu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcubdccs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nczgvgud.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zwneddfs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqerclvp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjybgad.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cameepah.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zxynajvs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzlsyoc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rcozygbb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbampix.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uretaujp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axeghhkh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwyjco.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfuaapt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkocgnq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcwrljn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bnosgpyi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfilhrfn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fembkzyu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldutojkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btddfaci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqqigc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvcoehe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwlqinj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbaszrd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qukjrfce.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ykftabci.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xckmcyly.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpxxexl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2krvsudbw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrjsixo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqqptu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmnkijz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkgzmyh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2naoaoofp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2omlmeepn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykprkccc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2egnmuagu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxjyvbp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etycegtl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiailqzq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsoymgd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxdrajx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxjnotj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sksxwpmu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2djeebbhj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnyuwyn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgznmox.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crihvtnb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2knerfpst.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpsxhda.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxbzyzl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rahjoswt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsnymod.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiymayuz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bumlpxaz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zilntshw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjmlghq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcalcrnv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2maqssbkq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfcgiqu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhwtgdh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrsvzom.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oywssjju.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shxdkiof.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jthymyrk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyyedmu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrrssjr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadwlhoy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pfibmorh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hitmierj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zponpwsg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxstagn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iftkexop.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvayueu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shxjbpma.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzywutu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hegqfwjj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrsmtkk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsleppx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2igaqshhh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dgayxrnp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcshcfk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmmelo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftshlfir.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vesfnfym.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eytykakm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsfunrk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuvafcw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrpjldy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2skszsijy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzcnag.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmxxvrt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlhjnuu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxwoyki.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lothbfty.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trjoaqpb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvztyzlw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eplwzegw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ceefudio.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fivbujjt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjcrzsl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbkesvz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqyelr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtpkyye.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqovflf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odiuzveu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbbynxn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvkwbty.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvromwqq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znvrcbom.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yljscvsn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjffozpc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvbpejb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmnnain.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbbcgf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrhphjq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2womofrsh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxeabaw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwufehqe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfqssxl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiohqnfo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxntcy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vunggres.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alcgnclb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkvwber.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkzrvcl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeibqwxw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpvdzmr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2opimwzgp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyiwhgo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhyaxvw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjnvovb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbccnrno.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrtzvwz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrdhivg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2frfkcirs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpmbrwx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2odldhnwd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wavjcyli.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pscwiuuq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxacdyco.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqjcvlj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwshoff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mheooclr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjptjbfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzefkamd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pvegunxp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwxgnzq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2enzxsjgj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpdtudr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlqkerv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2buiqmrox.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyfcvrn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dseykmgb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rojymtwm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dttuofsi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmgexzu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcywyxz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2onqdrwme.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhznrfg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdsttzw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qoipidll.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvrbhau.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsrfgxi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoqdhph.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxabcle.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jutweyni.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tarbryfi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfwvife.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkakspfl.html


<!-- 参考信息 -->