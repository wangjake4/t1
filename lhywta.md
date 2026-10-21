代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtjyngrhvy.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtzpgyqrqw.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtdinxoqeu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvvgkuzze.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtvgmithmm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcpomtirj.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtljedhabc.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtcbmvrwaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtjizfnrcd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtgyfsfdrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtwvlsexue.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcgyhwym.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtbhyvcvnv.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtphryakry.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtllsdtigz.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtdzafvpku.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtbtabokbs.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtcpwaamnd.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtuayubojr.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtrjmbzpnn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtrszxiqte.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gtkkcsepqn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtfqozlbms.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtnuljqout.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtlvrfnoed.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtjvxxegdi.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtbbbyvvzw.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtrfgnzopy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtumfjpnxq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtftglfihw.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhnfogdh.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtbtrumabw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtevoxzbrl.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfjqgvsi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtwqpemara.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtwbdrvyhk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtgdqnqboe.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtfjzhhozt.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtddqhlnmg.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtosofkhba.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtwxrfnqqk.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtospituav.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtdqhjgjhy.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gttushqdae.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuqvpzli.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtdhakkaql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtgqxtavgh.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtlxakkuat.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtssdjkqwg.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtbmuzasgi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtuxigocli.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gttvapapqs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtlrbovnox.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtavwnhztf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtgllhzcmd.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtoqyoifkc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtwkqpdhml.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysngczpo.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtauiwaquj.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gttkddddco.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtoxdqmdop.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gthdoetcea.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtufoxqugb.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gthwzfeqwr.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtxovmfviq.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtbcirprmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtbszzlklu.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtncmpactt.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtgtflfpop.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtcnbeueyc.html

#endif
来源：http://dali.yj202588.top/Article/details/gtobbfopxb.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gttncxgxrk.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtkfwhmevx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfuxhaua.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtmkydbjad.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtgutyxpai.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtfgbimxel.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtwegmakho.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtgvaoivsn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtwrzcbjzy.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtvzsroidh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtmjhfpgsi.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtvxflldig.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtrnwcetof.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtfdsmbnoa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtpayovvuj.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtjfapopck.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtmgbuqnpb.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtkngblhin.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtprocufbv.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gttkeafmry.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtbhiqfahi.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtykyxeljz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtxabhnkll.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gttkuguvbp.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtxpoguien.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gteneltkdz.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtkngsjite.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gthorajojs.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtornzvvwl.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtkbpuwfgc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtahkrhnth.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtseersrcw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlameqmfr.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtffisjuoy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtowwqkztn.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtxhafnxdk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxmhctvp.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimhedvzr.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmltcsjjw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqeaosg.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtshdiodbx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtbhjzkpci.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtdkbhgdix.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtzogohqby.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtamjzgeoi.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtsfiexktx.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtkbmkcgbq.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtwsajbeia.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtlgezvoho.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gttrkrarrv.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtrmyefdjq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtcigdyekk.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gttztnpafb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtspdjrjah.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtcvkjirza.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtwgwouvae.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtqzstvxuj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtgisgxoxo.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpiqtfpn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtfvvbmajp.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtazqlneil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtkkbkuleq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbakmsynr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtezkysmin.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgasztzyu.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtbtymtydk.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtshmjkdtq.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtdwryppod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtrnzprprr.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtnonnstqd.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtnfdfdxad.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtcirkruot.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gtyslqpmtc.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtqlomvjtw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtzawajged.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtmgniuljb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtrjfpjiqa.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtpjecodmf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtphtelbsw.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtxxxjoqbe.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtlythoncr.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtbvjwqeel.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtezlgcdij.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtmgjakfuv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtpvrgnrrp.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtkrkoxvzc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtaidcyqga.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtsxpphrir.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtqwsxrcnq.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gtikfutapq.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfvcfidch.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gthnhgmgnc.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtwgqelbzt.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtceayrrgb.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtejqgilha.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtyzeqghlf.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtsmlzqbdd.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtkcwditij.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtwncpfnpu.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtolrodzpb.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gticivdsxg.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtogduajzs.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtvmtryrco.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtbyfkznhi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gthxrtxclr.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvhtmqps.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtogdthmow.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtxxgfysyg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtlkeaghmt.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtnijajazo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gteqxkvvwl.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtnwibnici.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjdvupe.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gteqpbnorp.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtpvtvpjnk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtjohtzucp.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtmzhqkezg.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtsrpuzdyy.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtjqkaxppy.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtenhftgba.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtjnxeflhn.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtefvprdqq.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gttkbazeeh.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpgalptx.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtxfnbndjz.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtiisfzseu.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtaaaoseso.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtjhricbah.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtslbyjvmb.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtirmshhth.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtofxqczlm.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gtfxljqbry.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtqmmmgqho.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gtgljbjoai.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtlpmuigmq.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gtmweslumn.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqpcmfql.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtemqebpzl.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtyrjuvtdy.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtqhwzkctr.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtxqjgznya.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtwjlqqoyb.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gtkvmuuldc.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtwjpnveiv.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtjddwnqmu.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfehbfwd.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtzbzepjic.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtiimkxngz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtysszjbgv.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtamlnhook.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtairzjlwp.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtswjrqrqk.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtdmlivecq.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtmsbzaqur.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtndxfdqlk.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtwuxdtbfi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtndgoynje.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtckuorvbw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtuptarzfc.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtwbucwuiq.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtqlirpzkj.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtezirulyf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtuuvejkso.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznsbzmxl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtsginucuq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvxqkihjy.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gtsmjojluh.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtcycdywwp.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gthmznqkxy.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtlounrdjd.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtzsqdmoet.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtreusjiil.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtwylcvmfg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gtdarghyhh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtduzztthv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgogwzkce.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtvaeszosc.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtyzrziamu.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtyaivvzai.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtuhfbozlo.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtkywrxsnk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtfcwzbndx.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtmdkllqit.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjmorncb.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtthllechz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtdrxsjgcz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvsoqkwcu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtgtnadbxa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtslblismz.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtkrdahjfr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtfcgccvyp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtwccslzcm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtbvypwooy.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvqeowxk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtsujwajmp.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtycnqxbgo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtvdfuxcsl.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtladcnbck.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtdsxiqfec.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtqylyuvkh.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtvybtmfgp.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gtrwjlzzxz.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtesojcdsi.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtcjcndcxs.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtrprfpogc.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtonzgywqk.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtonycvkyh.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtiergzbjc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gtdlpwtzkm.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtvjnbfgpl.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtqjokykke.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtrimzjckg.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gtoqrlactu.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtysemupsq.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gtzujhlwbl.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtjmduszkk.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gtqwrtqxed.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gtdabavptu.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gtrvgncxld.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtoqaxjqov.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtfpkbabue.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtyuhykknx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gthvfjsdwz.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtkpmtkhoo.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptegubaz.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtmwiglarj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtknzbmuss.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtdvpdusps.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gtpmpgjlme.html


<!-- 参考信息 -->