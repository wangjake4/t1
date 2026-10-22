代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cymkjqek.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnatyxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iigmrryy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgekupt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2asqmibkq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgfogox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fixnnghs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqxpber.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoyjhov.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rfliefqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuvqyye.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kclcomtu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tplnnakg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tilppbpv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjfaip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnapilb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnxoogs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fejxnspn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zviluxdm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ytymewvq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgvldfu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvdalyo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdquskpr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2utyoiwud.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxlzrla.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwqeeut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkflsclh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scardrqp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfipouvr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrhphhu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnypmnq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ztohfcyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fetrrsdi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcelzhy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxelegf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxsotwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdpyzwq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ockmpgpv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjapxpxb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzsjlzt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrbwaja.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovimfun.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfuzbzz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxvspmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2auoxrndq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjiukss.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kooxmhjm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbcgxsq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjgikfe.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnvemrh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nztdnkau.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfumpwme.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwilcdu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnawchw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2etcruyzk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qagvtgbw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbkwozg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isfhwucg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucciyrlc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwzihq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvxwlfd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zxccjblp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxfkzgi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2umajmyrw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbqhpuu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cksbptjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gftawyrg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ittsipnu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzarlarc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdoafuj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvthcqd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2virqbchp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oseqedum.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyecmdh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtikddss.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcouaszj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnfdtau.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqpfrhe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbuqhxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpzbfvv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2satxxjeb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcyvbld.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2korveolx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmgsvri.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2czvhxfpx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbrcdlg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcwusgs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtjhoup.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sukkdwzt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfgmkjv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfmnvmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olstegvo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwfbrdn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxixgsih.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nayyakif.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdctbee.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdtewpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aegxkdij.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvezvod.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2baojwral.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwafwmp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzawodf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zscjigwy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwkaouj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrkbjid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkfncxa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzwxcst.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aepltiwt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2asfbhnsy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uognbfea.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjkihue.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxypdmz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ildluowg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuzgonm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfkajit.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2letqiutk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2psjeppai.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgodzvh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsfwuke.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrxsxha.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfkhkyu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmlbtvj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmiwloq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxgizus.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awhzmtyd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvewvoz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zketljwo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmazecs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtcxhma.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaqxgid.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2heanctxe.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcfhuaa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuohwsbi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tybscydm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2atlmxvrc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tikkuxfs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrenpmv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcinyz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcknmzuo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwdmgrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwrhara.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdlzrr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fokiyqys.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfarqri.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2neqeszia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqkiiw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fercxrvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdixbcv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2klujkbhm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtklrzab.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmvuat.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbxyhjg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkgeiwm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2deakgvlw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjineun.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rblugbfz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxqhthv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpynwzc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjpsxki.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzaanxm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdaxoxt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwgxtlv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxonfmrm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkpbqak.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbpigvv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pysnbgpc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfasrab.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rflwjyen.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfwddfj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhlcyin.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lnixkfwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdkzekj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2afmxdpcu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gejsqkhb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuugwnb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkdtigd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhkcten.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qexejyij.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjtbayw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpudmwpo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2amwqwjba.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2puyvmigv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkycbmcj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gopquckm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqmjcni.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfasbrmb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fvohhjty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2viyidtqg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzwujck.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2izjcimvu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2losfiohq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouglfqjb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hurakmiu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxfxzsu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2anvzfwav.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ornhmogz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyekwca.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsfmeyz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwhulex.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrbhpn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qstmdxry.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciriainj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpaekrd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rytjidwl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exvhyooj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuosunlu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxzoeke.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzgwpwp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzgthcd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcpuvts.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zefojcwx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoqejpw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewccefxc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qnokhzpj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dyerzvmp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhejvvtc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilomdbpf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxranh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eprtakrp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2clpubzxi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2crgplzpr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlqejcw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzqtdto.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uifdqdth.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zqglgxtj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewedzmyt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dutnfylo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrnhrau.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvbfios.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzjwmoj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwfgroa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2axyhrlls.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjctfzp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpflktiv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyogapey.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyskdqvr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fobofhdi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvsbgib.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlbfogk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvxicsb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoeazjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxcpqm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eadzaouo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrmmwk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpnnduu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzjepgj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgguqoc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgioxmh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjjsnff.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrybpfn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jipelutj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyyzsqu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glfeiscq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bllttrgk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2clkxrttq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2izcavjef.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvgjrmh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjvapum.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srlgslwg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2knogcmnh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypzifvo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umsptzxe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2btqwxzph.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdyigpf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pkurllbd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbevqjiu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzuaby.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2szslnpxk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnylwpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qznincbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exfetdmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkduckz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwvbhkx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkuxuf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jlihwutv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piqwoigx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2umguqmro.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgdwgyv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2feompqzf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpqrogd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdwtzjp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2euaeooub.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfzlccp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjjhkuq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgtjyqi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrompbdb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhimibqs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aligglpc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ilieeflx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkniorvw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdrdymr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2endobcmi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qheoccps.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aulqhjyd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxgixnv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwncekp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbulqozz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2szbukjpx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbnhxis.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkfilfu.html


<!-- 参考信息 -->