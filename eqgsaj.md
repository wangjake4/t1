代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtlcmouxrx.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtpwzocqdq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtqqvdziut.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtuellypdc.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtygzrkcsi.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtsiciiveu.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtdsyvzelw.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtegrpsfam.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtycbnjlsc.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtrllyhcja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gteiojophu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtaxkvpzyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gthjssbtra.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gttkbzflxs.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gttwrijktj.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtloqzoyjr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtfchvhnms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtvswicmjp.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtbzvuwmge.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtkedafgxs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtbvdfxsbf.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtrvylrsrx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtounmujls.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtfulpgubr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtowoqklbo.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtwleqqnoa.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtbuqcvmdz.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtrvwjytjc.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqjjafhm.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gttdnhrmsp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtdldyhhjz.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtiylvpngp.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtcwsyytwf.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtpewaeamw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtdpmgeqjb.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtahtarpqg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtftatoelp.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gttllsohzn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtirnqnjst.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtjldrlipe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gttqqifozo.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtrebuwuxv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtrrddzstr.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gthpeflcdi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtarfjdihb.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtmnjpdako.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtedebeerq.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtzlmyjhtg.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtyzfljorc.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtmgdwmxwi.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtqozauluu.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtpjeoxdiq.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtwfpgxfkw.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gttsymatpp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtiokuxsbn.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtpcqriggs.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtywjwpptk.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtbfkdbgow.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtvinvpaxp.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtwekvamye.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtlpgjqxol.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtxxlsdcbu.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjrdsvka.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtnwozapfw.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtygdrsjxk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtloywwcet.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtgeepbdvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzliaawav.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtzuhxpkrq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtqgkzpjat.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtmtyfbysd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtzpziadka.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtiaejubjn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzafqboo.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gthwgajwny.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtffnnmqkt.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtziszekgy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtqcnjooaj.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtcyaussgj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtzyufzocg.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtiznxgxeu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtdvuunhjv.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtljssizpi.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtgloayvnw.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gttfoiwstk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gttbumsupq.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtuvbfoyrh.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtxczwdyfe.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gtwwibanba.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtrsqjszbe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtnnscnuet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtmdzpvpwj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtzqregiko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjifngyoq.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtopqwyxom.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gthfhyaapn.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtlxynoalk.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtnkolnktn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gthigdytvr.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtzjvppkbj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtgibqcztd.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtrepcbkfx.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtqhpndaov.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtetecwzsr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtezvrxkce.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtnrhaeagj.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtquzsgqeb.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtwflyndhk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtcnpfgcuj.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gthopejgxt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtgygmckcn.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtpjqauzcf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtueivifct.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gttgswejdm.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gticvnbxsf.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtpvumfefk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtvoqmrlxu.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtfknsaxrc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtrcnvyaem.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtistyjgmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtxgwibrgo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwqrkefiv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtxxnaypyb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmxsubpgm.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtycjinrja.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtymznmypt.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtqjxnnaix.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gttwpnixzt.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtmenyhgdm.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtlbvgoglk.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtzcqrrrca.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtadafaofu.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gterzrqbiw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtstyykhli.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtzxxkhyjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtfvjhgqgc.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtvzdibkqy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtcyotrumi.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtgudwkaze.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtazuhysol.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtdxxzthcu.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtthirezlw.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtoajxdgon.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtsrjjsjva.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtedhdogmp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gtshcxgsxi.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtagwadlij.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtxvdfibds.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrmkdwnf.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtcspaqgyt.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtxpzzofjc.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtnxbaltbh.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtsjosphkz.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtjmvhghjc.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtqzinfodg.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtclfnvysa.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gteeljknzz.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtxavdejqc.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtajufdcmn.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtfzwzssuc.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gttohtekbw.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbmdhlbs.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gttsqpbvfm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gtfspsbted.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtlbtghlid.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtnbrbgpdp.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtedvcsqpg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtqlpqiyyg.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtobpssxxx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtqzhlvgcj.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gtydoqdyoe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gttjqxtujs.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtkddmacpg.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtceoixoar.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gtedurodzj.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtkjaucvdj.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtgizqaqlw.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtrdenfbkm.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gtrjwdsrmi.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gttuoqtphh.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtyvnipbna.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtfpkuxolm.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtvldneayg.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gttodofhgt.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtqcrbgknm.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtsfnvjsdi.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gteuzyimul.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gthhwnnuqs.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtvatibqio.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtsjxmwark.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtsviifsdr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtzvjprvad.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtmrhddmcf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gttonjfxaf.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtsalwbpan.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtjinkhajt.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtovpbvgkt.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtbwmlkkzv.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtxfavvvay.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtwcardxrc.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtmgflhzct.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtalrobtkp.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtsjcjbziw.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtxweuocpp.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbegdnyyr.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gthhvgdzbg.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwuivzyz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtquueacva.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtoogdnizx.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtlquwhbzy.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtwlzpysjf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtedcuvggi.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gtxazrjiow.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtislzowta.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtqdjvacpy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtahaeypbb.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gttkcrvkkf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtubbglkmc.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtvyvihmxd.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtcminnicr.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtibbwplgu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtbphxbhzf.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtkweofcja.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtbhgsgmqf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtbgyshegf.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtjfvzwant.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtmtjthliv.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtyfribnsm.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtkqzqxaqf.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtaacnovml.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtcbdnvxnw.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtrindillj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtybfwfjnw.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtbkwrjvwd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrrixoicz.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gtvnetxlgr.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtvmouaaqo.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtznklfoda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gteolyntpq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtzssbasfw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvrsztil.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtukdgzkqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevymvjsl.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtdowhljmv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gteevnhemt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbfokqyjh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtphgkztld.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdqessew.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gtuclejhdu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtudkwxcfk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gtqkhdcuyj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnemvepiq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtdpvprtvx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtvmayaypq.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtoxhjirow.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtmewmtsbd.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtkyzpniyf.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtpujleuuo.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtzxzrvbeg.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtebyzofje.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtehrltwwf.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtsmmjhpbu.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtkcjilkoa.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtjhyunzow.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gttcxkdims.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtakyzablt.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gtnofatblr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtloiprnjp.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtrvnlxsmt.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtftaxljkb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtunqtuncv.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkltztaqp.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtsnttlfgg.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gticrahnia.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtuvkfcwru.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwfyjcve.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtiezvchyo.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtnoxejhrq.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtswvymyti.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gtimywqhxm.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtyodzkjdy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtagdjdbuy.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gthsfxiqpx.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtglshsldc.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtukqndrfq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtzuqkxezo.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtyebaffqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcdsojok.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gtjwpzsezv.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtevxfmnli.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtnrapcwym.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gteuepqgxv.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtdblacmpy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtaypaxswq.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gtvwhnthvn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtmquifplt.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtiyfsiame.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtgvqmdomg.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gtfqkigzzc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtyfwmwpzk.html


<!-- 参考信息 -->