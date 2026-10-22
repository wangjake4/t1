代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtsugwkmlx.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtwhurhamk.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtaxjguslb.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtknssqpel.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtfbkojlje.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtwvajtrgi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtyduzhhaj.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtbzrizdzs.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtauxzftbf.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtjrovyneu.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtifddtwbz.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gttglfjghq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gttvtcishd.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtrseacbjv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gtskidacfh.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhzggcma.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtkwtaswwa.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtebwhdony.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtjynlmbuw.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtxhnwwdpm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtbrygurxd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtnuqozbde.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtcfsavbkl.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtivqazsvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gttcujkrfy.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtfdxfbjia.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtdaiedrgw.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtncegkppi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtaqcikeis.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtkjvwpvss.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtfxxnrewu.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtsvzapmka.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtymwyucvy.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtljekekvk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtsbfoznbw.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwdhvzyau.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtwzzjmkqo.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtlpkberpx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtjdoxbwxo.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtfmjexgjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtxfucazpq.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtdpijjdtu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtujwgepgi.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtdsldtbmb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtrcimjbcv.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtfyicgpqz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtonttvppk.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtuoqwynpj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtgbdzfwcm.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtpwwexobb.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtxfkrruzw.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtspuzxqnm.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gtnsrleqkf.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtavfyiddr.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtatqcoftw.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtswigcjmg.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtuqjxnatx.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtezwxghke.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtbfeycjvr.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtaaxaoydq.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtbwrrodvr.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtclnncwjq.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtkfdwyyjc.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtfoorthds.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtsnkcelui.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtfbcfjdnd.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtxdbaqmgy.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtuqjwcmol.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtehabbnod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtkaactrvz.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtzrrqdkxm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtisanzlho.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gtgdcniaey.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrilbvbfs.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gthcpkxulm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtjqaogofn.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtqgadopsr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfcxtzyy.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtrffykuei.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gteltjprzn.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtjuuhgbhy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtxiqwydow.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtpwmnsffn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtomjrlhqq.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtiksoknfj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtnlpxeooo.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtrrbuwzou.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtakiigypc.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtmgumhgze.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtziklwipb.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxolcjze.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtwikzjpvc.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtdqgcwivg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtuhdkhpem.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtigjygkcs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtzrgsxlbp.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtxolhvrbs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltgwubt.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtepprzbfi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtqujlnrkt.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtinnqmmua.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcuvjyhjf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtkiybulid.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtuywflqal.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtqghmimdm.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtshomwshz.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtpvxzbqfa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtzogrzsmu.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtibpobwgg.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtpvwmnhdg.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtuixrwber.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtkhbtwbis.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtbhyabrpl.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtzlmymobv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtnydytzjb.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtwbuisqgu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtjbvmxswz.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtoyqqpzro.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtgsxiybnz.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnffktxf.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtqtljqufh.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtgopaatzx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtyhaqwdmf.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtidasapuh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gthckfglzg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrkhczjse.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtjfhlrlvn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkobpiluv.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtkczdhypk.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gttuhjmdmh.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtvsdqgyam.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtnpouzrws.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtyenkumhl.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtoxgknzke.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtphnwgqox.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtspcxjoxo.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtmqugkvwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gttscmmrpc.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtjlilkohq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtojioamio.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtiuugcbon.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtppjiilmf.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtcvnaaocq.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtvvokrkls.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtnrrehchv.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtixkmdeup.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtbkhhcejk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtsgldjepp.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtntjrtvpl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtqsxoegef.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtkrqhipwn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtepnhjria.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtdzpynwhk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtfdrizmuo.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtxghvnwnb.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtdvsrwhdj.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtdxzigaag.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtwcspktba.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtfhhfbyeg.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtnssukmee.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtndhvzprf.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtjjrggdpj.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtorhfexea.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtqohgebed.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtjrnrqqdp.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtnvjkndhe.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gtecatwazr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtpsjecftf.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtktlpszya.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtczzltwpn.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtncohlohm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gttljgxhgp.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gteaukzops.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtrpgwyjmh.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtpksgcebk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtcrizbaxb.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtjowfvlwq.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtxxoaysde.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtdyblynrl.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtqjrrnfbv.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtjmszpddy.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gtczthtkry.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtugaepzxn.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpcbhkfc.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtiqpdnrxj.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtulyyygke.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtyfwnueow.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtzgzkyyig.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtvrjjujyx.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtqrghyqdr.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtkcemelbe.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdesfimss.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtdthxxtrf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtofbwabeq.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtmnuvoapg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtnvhtuafu.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtpwjbqrkd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtattuyevs.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtegtzpuwj.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gthwlsbgaq.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtjpotjebm.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftvmvges.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtqekitkhh.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gthfkwzwig.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtlqwviztf.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtffdafilx.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtklftnyuw.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtcpxtmotg.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtwzyeysfw.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gthpmmufdu.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtfqnjrifv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtpstawvgk.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtaisulvrn.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gtndzzztql.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtwoltegvc.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtsnuilsur.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnarrhxho.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcwgppmj.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqppgrcz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtnchggfxh.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtvejjlamh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtutswswas.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtezziqaus.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtqrkbeyle.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtwyhdrvdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtpeqwlvos.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtsvxthmmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtqfsjkyaj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtqrxtpaad.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gteudublzy.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtgymgrdkx.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtdjhiplwo.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtslpyfuvm.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuvdcspx.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtkyomavwb.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsmglcjt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthlfgrcyu.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtcymufvxs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtkkbxxibt.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtfuqzjivq.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gtyhyhtikj.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtrekwhtrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtmhvvuqia.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtwkvulueo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtfyfalcir.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtpztyhijs.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtbcpiuddi.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtraqcuiab.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gttzgdafba.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbsbaxjzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtujqycucr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvfzccjly.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gtaqanfuib.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gtdrqdlrof.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtvktsmvqr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtjpshttum.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtchddmaxj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtzdlgfybn.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtilmdplmi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexpnwhpw.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtvlocfjnh.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtzcscxtty.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gttocteskl.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gthgkciocd.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrdzasfh.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtreguruak.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtzlktjzpz.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtqeehwnen.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gttrhnahiu.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtxcgulbgk.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtpofjtjaj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtcenyhgid.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtkiijqmyx.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtrzlpgmqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujhjsisk.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gttqxlxlnf.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwbbxlaqx.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtawgypflq.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtixcuppqz.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gtmgfxrnvc.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtmjbzlmgz.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtnnggfuoa.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtuhkfnwoo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtxoklfxzl.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtpepvsnih.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtrmhsjyjo.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gtqixhuois.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtvdyiqyxt.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtgwygzzqj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gtpwrjamjz.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gtpmeotpjh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtkingjrng.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtnnvdlyrm.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtrmdwxgyb.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gtewmlbziu.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gtqzeaxhrj.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpxkvuuv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gtwlxzpnmn.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gtesfsgfsa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gteyeuxbmd.html


<!-- 参考信息 -->