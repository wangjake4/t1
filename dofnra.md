代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtysfpoxke.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtygtfrzgr.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtwmofjtxo.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtaoxsdeqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelrycpwn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtvivkzkie.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtnrtibwmp.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtfgguyxlp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtvonunrpa.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gthuzdgskg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtyhmzbamb.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtxuuotnzz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrchiwwh.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtdadbnmzb.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtmrlnzder.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtywcwkkgw.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtxjeztyzo.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtxkpyzxty.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtdacyvpqa.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gthpxxsowo.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtaumakvrk.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtsebkazjh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtawakdrxl.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtlolaovrb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gteudbfthm.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtcvhyevzh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtqhfpjlad.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtdvgscbfl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtofvqimnd.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtuhrampot.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gttelpifgc.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtsqdjnnlu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqidwvsb.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtxhduuewe.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtpdaeinuw.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtwnowbife.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtfvppwrga.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtfrsfaikl.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtnajzewej.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtdkxypvzx.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtnxffmqiu.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gttbvpstvf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtivzliyqe.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtiqgptxmm.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gttgyntsth.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtpdlnrbxi.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtzwsrkksk.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtpyesiopu.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtemtooqjm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtpizjdwus.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gthqifllij.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtkupqoduq.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwhpuamp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtlvqyaxha.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtidxxzabp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtfhpborzz.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtnwnqpkor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtlpouemfp.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtvzsatcdm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnbbtsvdy.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtzhkmcgoi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtofaeewfs.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtrjmeaaum.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtudihskik.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtgvgxwhni.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtoggsvozx.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtghcirnpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtsffmxyqk.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtazmbasib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtbspxvvzj.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtkzihpeeq.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtnjgrzizk.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtkzeqkzdc.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtidjnycof.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuqpdvbo.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthyvfhkdp.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtrgwyyfev.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtnocxfjhd.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtmterreda.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdwppckbr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtfrjtzxeg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtjkpplofj.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtmefmrcxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtxmbvhfik.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbyglvdj.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtznalfgjf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtcnsztoiz.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gtcnlxztgq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtezktjajo.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtnoshtyud.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtcfitsspp.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtaxatdmrp.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtxoielmrn.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtftnkotgf.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtqmlxgbwn.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtwvnaqfqc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtzhrlpsiu.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtybdaogyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtuuhxinzu.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtqobeljbl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtmkordkhj.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtgbpzboaq.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtrfrjhbnx.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtmgdeiuxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gttvgxoekz.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtydhovswc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtqzqagrjl.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtijiyqpqh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtvhbxqmak.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthrvphfgc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtmwvgxgvf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmhwvjuub.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtoyydqvfp.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtsbnuqpmq.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtehelauir.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gteagumivm.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtadkwhvqe.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtgertabmq.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gtsonvjrtt.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtvopzpgil.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtwenoteke.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtbppbhiyx.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtujgfhkxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevekjiyr.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtmhjqpnvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtwfdfbywy.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtuqrzdwji.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtiogahsbz.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtzkoaopsp.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtrkuaeuct.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gtnklgkswh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpvhfweb.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtzxaoeikf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtywrembnr.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtiskkdlyh.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtazzrsvjw.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gthblvtcsh.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtwdaozeam.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtgudnbzwm.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtotgwtvra.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtyuwfzbee.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtyjfuxpox.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtgwnqtcvg.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gttuhrblue.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtgjamnmdl.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtywnzuatz.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtjoitmfsq.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtmmmywdkk.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gttczjkmys.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtsmdnoobk.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gtevmemlwi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtyifrxtnq.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtokfbqzvl.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtfntcbjhr.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gttzyikgmi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gtaqczzatm.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtbdvdhvzv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtyhnwceyk.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtisxunutm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtbvoburje.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gtkaosqjqe.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtnunfknaq.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtxjiygjcn.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtepupqzcs.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtogurtxiz.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtlmcirsta.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtrrufzuby.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtaqqrsqmw.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtqtdomhco.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtqdckxpqz.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtyjgmiwbb.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gtdfyqxayl.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtuyamxyly.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdpzchbj.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtxiqbnldx.html

local a = 1
来源：http://dali.sweek.top/Article/details/gthzcerdju.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtjkburgmd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtrnueqdkr.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtblyfeytt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtmztvjjkg.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtvqqwantq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtokazdlsm.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtuvfmthsl.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblhnvttd.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtjumhqgdl.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrolebgiv.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gttieyoevg.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtdlpenast.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtytlvmgka.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtupnhcihp.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtutixwpmi.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtfckjezzu.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtozpfbilw.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtgmqdhfks.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtaztqhnpp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtreyolacx.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtjgopjoff.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gteokvwbbu.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtybfvazfe.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtuaywbexc.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtlrypdtms.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxemxyeq.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtvhodsruy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbxjfdkcn.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtlulcmmfi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlnzfsqer.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtyjetxewc.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokrrmkvd.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gttyjldhol.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtnpcslyqu.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtutdutbrx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gtpuxpvbhq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtprkyuoge.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtqhevmopy.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtwqoydgdn.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtusjmanud.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtppontwnt.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtxydcubot.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtjscyfllv.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvhrbmkr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gtgdywltvc.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtapvvhlxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtvthjzgpc.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtqwvojemy.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtauinnhal.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrnfwcgm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtopwwtafp.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtigdsbmpv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtbfkxftye.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofpwqpfn.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gttyjkfsjk.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtfzrvxxyt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gtszozutsz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtteytmzkc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtytyxjdft.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtaybdamsq.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtmptuzjkk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtcrdtupgl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwhksifr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtryohxysc.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtnuhddldf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteipmcmpa.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtqerazzdf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtqxqyvitb.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gtsixpijob.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtslwsmnqq.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtespfywko.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtmjtpuhzx.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtajnqcmpd.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtvcklwvql.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtgcukfoxl.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtyuuknduh.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtjnpxfgnk.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtkbigykbv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtxpsjpzgu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatnbnmer.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gtoglcjmqr.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gtgbicndam.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtdyithioj.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtrlmgcrim.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtintkxhwr.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtygxqkcup.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gtyqtauuel.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtzpkbtxmk.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtjhgottjp.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtuueohqfl.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfgdifrb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtoyazvyad.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gtrwqjjjwv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtjainmxkd.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtpieynpge.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtuqymvhtu.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gtiyfcyabd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtwjsldwux.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtgnfiqo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gthvakzjfu.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtmnyrsbkc.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtfsticeuw.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gtvnwamarb.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gthknagegp.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtzmuvmnqz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gtslbybcbx.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtwgggnnsp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtvoagzknf.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobkpklq.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtkwomyctw.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gtlnlwyezp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gthldpipne.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gttpzpxlon.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtrlbiocmc.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gtjpnorxup.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtdtxtgihx.html

[U29] Py：属性校验
来源：http://dali.gotoacloud.top/Article/details/gtelxqdydz.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtbuuxjnxg.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gttkyttqqx.html

@dataclass(slots=True)
来源：http://dali.jiagoushi.top/Article/details/gtriobmdkw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gtjvwvnioe.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtmcktrsqv.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtdcuprtzs.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtsqgaviml.html


<!-- 参考信息 -->