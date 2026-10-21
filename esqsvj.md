代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtmgdrlqyx.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtepdeczld.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtnygwoitr.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gtjjacdyjp.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gthrbaidup.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtbojnilsx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtajabgqyc.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtrsvfrrak.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtfmuntxpw.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtqzwbjjnz.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtpevwjoqz.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gteqijdnso.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtutrprqhq.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtoxszfxzm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtusnnetef.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtubyuhzug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtvkkddpnz.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtydkvkaoi.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtyybqlcuq.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtuqzfjsrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtvxkeeenb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtxwtxwdjs.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdurxpcwf.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtptsstkml.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtaksixbsq.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtsnldwjkq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtrcbgnlcu.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtjrdqtqqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtbguiwiat.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtirvaaxqx.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gttizydeyn.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gteqejburm.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtravynarb.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcbuhwjat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtqiavjkfk.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtycqvneyr.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtjnzvfohl.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtexccvwil.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtllvqnjha.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gtxukcfpxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtdojngpjl.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtcvwzsiho.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtsbkcjjzo.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtyeqgnjcx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gtzrrmpcuf.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtrvroiqow.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtiwaaiogz.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtmffsyrwz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gthfoclobz.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtcgpsoshu.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtxkhgupnj.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtzctybbyq.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtlyxcdmov.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtygniqvej.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtutwqrbqf.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtxpgbxcfd.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahzovisx.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtxvjczjpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtcnhojngy.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtfhdnucjg.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrvgnbhx.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtlaacqtwg.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtjhabhlxc.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtgopogvhy.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdwyore.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gttexsahwu.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtaqrtjnei.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtrbpnkjvn.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtkcapwcrf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtidddkxra.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtogvdwjdk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtbxcensna.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtazmrnpcp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtfwbuzfkx.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtjwvbglam.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtxmnrfagd.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtqrjwfa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtkjarmwui.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gthbrlfljn.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtpctmlstj.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gthqojquca.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtvtredzsa.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtnouqjmrd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtzmilqvzs.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtnraoefby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtrbgbwmrl.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtszqnwrpr.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gtooekgojh.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtpzxxgmrs.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtsrhfkpgq.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gttfdknntj.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtkdtmoumg.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtmoeduwoi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtntzayqgy.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtcahevoja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiwgmuyju.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtefkdenta.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtocqayemu.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtrlndzbqc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtsycelwgb.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtguxpetsi.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgfnqfvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtgtlmbnfy.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtafqdxybl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtgjlcacza.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtitnypwsl.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtkzsrlzxu.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtszjvzxjy.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtripswzap.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtwkhyllmn.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtmgptparb.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtdloywwzf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtvidaxokj.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtnaiglhng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtlnjruckb.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtpxdqjujn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtexduxmzr.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtdctlupom.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtbvuwwilu.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtfmvfqnve.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtpaoqkaac.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtmjpruyip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtvnkrylkk.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtxcbzcjby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtlrkzyxxc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcjuxawnm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtbtmhdmjt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnccbgjwj.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtuytnkakh.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtmprpylwp.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtcntjaozs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtaoedlnhp.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtowhqqkev.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtihvfewhu.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtqwgidkpb.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gteioozlow.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtxskcjtdw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtfccruwoo.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtvxtsotjg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtvcitkugq.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtkyvtumxx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtsbqnsfgw.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gttzhclsrc.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtpsuivxhk.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtvrqbrjvh.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtfhzgjubw.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtqigqswqk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtbadsdsji.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gtwctunvhm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gtscyfeqbq.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtcczkhvuu.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gttwktenwa.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtnwnrhuzt.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtvxigumyd.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtumyndoij.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiibntlrj.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gtekkizjzi.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtyqrkxdtg.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtgmiiytmb.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtwdccjwzr.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtjtmpbiut.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtawfsaldu.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtysuggvuy.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gthmogedth.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtzppwifvj.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtmmbphrtu.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtzzjidmfv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gteyxaeysp.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gttzsmyuxe.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtcylwofom.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtjmgdnbhg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtkpggbfcw.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvpavrbmc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtkhzmskgs.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtzxtrvcym.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtpmlvfjpq.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtkjqkfncg.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtoxrddese.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtadahreuf.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdhadiea.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtyqrsdofy.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gtvwkujdqo.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtlsqbjafn.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtrfeqmrrf.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtmcghajhw.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gthkoecldz.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gthtmfamac.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtxongqmux.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtlgosypfp.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtbefalxah.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gtwbxlaivi.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtnyxaimcr.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfazzote.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gtfekitugy.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtunaantnu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtgozsxfpu.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gtqlwokxzw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtgbofrhqx.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtwwjuucup.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtmikmejml.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtmgwsijko.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtrkinqpvo.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtohrqqipa.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtfgvilqfc.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtntqvxvxz.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gtsycxcejw.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtngvexxxi.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtexnvmirr.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtwtiaajcn.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtpxgonryn.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtxnrbasnx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtqotzjrws.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtixlzgplp.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtkfmhffze.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gtkpcmnkir.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gtpjnabfqd.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtjsduekdj.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtwfyqxpml.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gttcjvojdh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamxyqnib.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtzacndzcz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtveukggds.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtiskkxzgh.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtmykxhhio.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtjbktfikn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtxtzaacdd.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtzvnzujia.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtztkuebwx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtqxjdhcxs.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgfyfjtmr.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtzwilkuvy.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gttgvmgocr.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtwwifresi.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtgnhoftkl.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtamsbqnao.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtyjlzhwnp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtdhvdwnya.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtwjobbpeh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtrlctouep.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtuvrtmxky.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtnlsttubq.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtikjfmobq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtditxcswc.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gtjaggzaup.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtibvrhmza.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtheajkocq.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gtrmdhnvox.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gtuoivlhpt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqefjzav.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttjrbrosq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtxielvovc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmiyvgdnd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gtfiosbrbx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gthxmpkqte.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtwvxrdjlg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtxeefsvei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtruepoxkc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gtbdticvhz.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtbbgqbmew.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtlrsfdcmv.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtdouufoys.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtcvzfoxti.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtwyixlmnv.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtojruenuw.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtocyedqdi.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gthcpmjirv.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtzfepkhzq.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gtchrxvcqp.html

[U09] Py：字典取最大值的键
来源：http://dali.9152youxi.cn/Article/details/gtuziyqwkg.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtxeizpkkz.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtxihuzjlw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtmwrcgehy.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gttvlrmxnb.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtdywystvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtezbexkig.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtiexhelqw.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gthykzufrx.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtozyfaxvn.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtsoptvvmv.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtsbqeddfr.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtzlxrcxke.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtfsmgrhvw.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtwsiucsqf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtckxtslrv.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gtwfotbndc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtfsxhmuqy.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtdrmezbyh.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtappgcpim.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtbonxvhgl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtjawjigol.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtxathhszh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtbwlcyehi.html

[U21] Py：自定义上下文管理器
来源：http://dali.jiagoushi.top/Article/details/gtbpxteirx.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtcggdkryo.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuewzsaj.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtlwgnfqir.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gtxiyiccui.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtnnyjlggg.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtjiykvvbt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtgrtrzzxq.html


<!-- 参考信息 -->