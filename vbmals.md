代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtfdddiymx.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtxmsuxolk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtdqfutbiy.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtwouncbuo.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtcbtrbpit.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtceqaqxlt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gttbqexkub.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtbhutamfn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtvotzkkrf.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtykecozif.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtaapsgmtd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqgciyhfq.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gttowqjzzv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthruikxya.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtktgvsogr.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtprwgcmta.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtrcwjzuuw.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtxoctynoy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtgomwsksp.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtikwhuwza.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtjhtmovaa.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtsulljgas.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtduvnqyio.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtldjwwvxu.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjtpqwjw.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtzbzgkzff.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtovfbcpyx.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtonxeintv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtjttiebuo.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcxaszmu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtfdrbnuro.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtnvqotqrj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtvshiwwdo.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtefgvnpfb.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtnbbhpayu.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtyifjzjhm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtzxmydgid.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtjtnpzqte.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtmztvolec.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtxlguuhjp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtyqalnuva.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvesrdbtt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtdclpgkyg.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtcribbevl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtdsxihdlr.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtlbqiyoef.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtmkhqmaku.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtvozxifdz.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtzkhsqjjx.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgduwbwz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtkjmrjrhv.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotcfzzbe.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtwkcwaluw.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gttiolgpss.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtxxvoixtc.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtwrbdjmex.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtrafxoqmb.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtzrbeqgdh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gthdslynnl.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtpvpczgvk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtkomindso.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtevzynrgx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtswvnonfi.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gtsxqxwydn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtoiabajyi.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtegdhgpwo.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gttiykpkia.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtdrhgaugu.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtcreurygq.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtqeqeorwq.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtpeucupdm.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtyhehdgzj.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtqlinfmre.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtznapsica.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtkmzagnjn.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtbijiidpx.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtcsfuilav.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtxghdmnmn.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtaukowxav.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtpttkzqop.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtbodsdxkk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtlzypzwpi.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtmrxipplc.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtxqrbzoaq.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtntxcjujw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtzjiiwisv.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtagdfeurk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtrelpmqwy.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtfrdpqnfy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtmnxudolh.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtvelvjvyp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtxkrbtisj.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtgqeotnfh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtpttkrdpl.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gttmmnolin.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjgvrgmz.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtnsvnirhk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtctookldv.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtgdfqnyci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtiqhlynay.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtjhgnsiof.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtibbcrxpo.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtxsuonkew.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtdzgyylxn.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtiypjtddy.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtaeijvhqe.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtjneizmab.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtcygnclyg.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gttoozfker.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyfhzvew.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtjvuymotv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gtfrfnkukb.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtkzaffhyf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcisugyvy.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtydtjypfb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtfhfyumfa.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtxoxgdxyc.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtbfdyvspb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtlqdjhndh.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtwdenyjvq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gthlzblncg.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtyqbwejsy.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtnzfmyjmz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtlhmusxjh.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtivbutacw.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtnyxzmngi.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtskvlcgji.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtcebmmspg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtzgozqdlt.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtvwrgrzva.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtfuyhddyj.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtugxesucq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtweoubwkh.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtdnaugntx.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtjwmjtfmf.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtcrxinfzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtokohaejk.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrlslsxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtjaiwilqy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtzjmaouww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtqhyadkmr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwzgicqlv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtlrbmuhun.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnvkmpajw.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtgvfiwaze.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtrhctkcot.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtyllecqaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtbclbbvxw.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtqckguwru.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcrqgehi.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtrmggioes.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtjiuoxzbt.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtndpmujai.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtdfeevgpi.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtwebxoetw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtwpdozkum.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gthfmxtetv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtdyyyksai.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gttbbgwhbk.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtgmzdltex.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtbjreqteu.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtmxetjnbl.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtltehmaog.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtjnwqvmfj.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtsykbofac.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtgtrylbag.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtkmjnmfrh.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtauccmssy.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtfjbczlqq.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtjrafxzle.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtvfcpypyz.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gteymhfxpf.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtshnmmawo.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtioiijjaw.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtobgfwfdi.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtgjwgdinl.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtlpfjxpzu.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtinovkgxv.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtglsnudeq.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtddjckfnp.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtecbxuipo.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtuqdwkclc.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gthpecwflr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtorgoijkk.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gttcqpbqjk.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtrqxietfv.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gtsvtzamul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtmyvzdcre.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtmqhebusl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtsfjsawxz.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzvowljc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gthvcehqga.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtfqxjzeha.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtuwihpamk.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtpzcwvyfr.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtowzhkolw.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gterkuqnkb.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtyjdstmrd.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtkyyeqsxj.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtrpasfzwv.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtmofontrx.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtomfzjcbl.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtofewskus.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gtbxgjfttd.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gttalivhkk.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtmsjcamnb.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gthcecozge.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtmxscbdsg.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtokwyivpd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtpjiokqqd.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtdtfmxwem.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtjwmznzbl.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtaonubryl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrgksrjjy.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gtmakdlecd.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtivlpocon.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtovbxlckg.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtjcsfgkjt.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gtwdsjkgrf.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gtrfmnicfl.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtbkygjjnj.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtshbnfoth.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtczmxomjt.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedobljqk.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtbkdfdkek.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtvzuxnauj.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtbosugwhd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtfivihqjz.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtdbxnbgiz.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtpcxlzfkb.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtueasdilr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtggvgtptr.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtimuopzmb.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtztlczr.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtgzztotsz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtptuamuyj.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtcwzrferi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjvhxmite.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtpkevrszc.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtoixtmzqc.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gthguurjvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtkhkcmizj.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtbhpumxpr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtvmhmtjwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtwpsfwavv.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtotiencko.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtueryqvop.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtrgyekaqt.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjixtrbqz.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtadtruomh.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtefslkych.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtwbwelmcv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtfatsqfvi.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtqtrmidqq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtfjnbbfoj.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gthbuigumq.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtqifvquyo.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtmxwfwtfb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtrckirkdn.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtloeswydn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtvhfekcgj.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtrqfxytgk.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtbsbrabee.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtiispxbfu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtjywoznfi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzbaypmkm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtpjicimbl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtndqewpid.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtjnbpfwts.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtwmcpzktq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gtabthtoqe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtmrmvvzbc.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gtwqguyvgt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gtxtdarwyj.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtpqqygisw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtkpinrqtt.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtyksrkmgt.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtsxipamfe.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtefibneaf.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtugqkfvbp.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtpajlgcmz.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtsayunwif.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthglqyhsh.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gthuncjxgm.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtvnzitnvg.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gthyljcizc.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtdtbmpfya.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gtehoeiuah.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtpovgbvdw.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwodcyjqp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtspwhfflk.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gtnmmeatzd.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtahrvgyob.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gttboerqhr.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtrqsijgac.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtqubakvnn.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtprttlien.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtytfngvjj.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtilljzngp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtnngyseqv.html


<!-- 参考信息 -->