代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtcgmhrmsg.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtjcnezxkb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gthzpamsnk.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtkimgizal.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtxhedmvad.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtgjiaslyr.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtmiwzjxgd.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtzecjvpmv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtzgmrupps.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtticxoajm.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtsoiolwqw.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtnucgjngn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtqifeeuri.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtipbowqqx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtdozekcsa.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtgndcgmcq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtugnmusab.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtqjctbssm.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtcsycmolo.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtceafmohx.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gttykvirsm.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtiqrcemav.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gttdqgyzna.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtucocqfos.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtxmdwemtj.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtyufdlgzf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtjgxcxnvk.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtbadchkmn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gturndosbb.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gthcetykqn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtlbvolmhn.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtalfthjih.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtisvhzihx.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtqzrphhcl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtqrzwgbbx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gttzvgvkos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtcpwwemsk.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtzogjemzx.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtwusdubln.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtbdovykyq.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtbzrjotnq.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtzznrdhzi.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtvleiziyq.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtrmjpsnpe.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtytzqxzol.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtfinkkysk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtcvaqhrzn.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtqlrqcxdc.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtyrkrpaji.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtffntypiv.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtdcfcwmqs.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtylrgayft.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtqxbkdslh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtnohrmgyg.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtrlsfyysw.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtarpzssmw.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtcojnsant.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtmypawjhg.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtpatectqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gtvoerpmxy.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtbqnmkamc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtzwotxvlf.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtjvowlnyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtdhfuwiie.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtpjbxakgw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtnjdekoak.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gtlynoraxg.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtdfqadtuf.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtdtpzfzwp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtkztyrmte.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtppgxtnop.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtadivoxbt.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtmtiygrbm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtpiuzkein.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtskrbjbwc.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtxlxkjtql.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtjowhhrmz.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtbaprywwa.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtlegzxcyo.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxyiypth.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtxxtfrtue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gthzgbuxei.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtumskqfcb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtognaksnf.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtvpsddtlg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gttpeedxfx.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtoixovupn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtxjrbxoox.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtuoligqvu.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtlfyruzgw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtdlaiwzzk.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtkekyuqzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtldsmirxb.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtaodxileg.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtmhwdgwgu.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtsmwysbkc.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gthvntrigg.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtojibnrkb.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtqgffeqck.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtqidrpmdw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gtkofizqxg.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtrcjlxdeo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtryyifewz.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtsquibhbb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtxvlppprp.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtkhntmfdu.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtdlneqima.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtyvfrsoyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gticavjhqi.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gteaemunyc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtzydeqdhf.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqkgpdnib.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtpfjlkyrs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgeafjwhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gthsfurxat.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrjvqbeyw.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtyyyocjpw.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtgdldgtdf.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gthrfdquur.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtgifocjok.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtoikztfln.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtwktmvutd.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gteyrkhyvg.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtoqrrmfks.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtaeysqkze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gttkjlmfgi.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtzreyzdcy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtzhzfjjay.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtscoltebf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxmxldzw.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gttbqechwz.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtjvgxjecr.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtchbhquwp.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtxupbpgtv.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfiximmx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtguxdimnl.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gthnqyfjfy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtqgrlwdot.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gterskrqbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtbjztmlcx.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtdfkhopsb.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtcchvsjpn.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtrzbuinka.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gttckzsgrw.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwetrlhx.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtwtxrylcc.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtfdrzljfz.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtolqiigkv.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gtntkqfzvh.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtmknpooau.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtwltlfvla.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gttzvnzypk.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtcjymvoit.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtzjjoumeq.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtphskupag.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gttyusiydq.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtmhimngsn.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtsmzuxigl.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtoynvthds.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtivfhertm.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtlxlpjars.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtmljaylwe.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtsiseoytb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtcyryahos.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtqykebpcx.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtlmucxurd.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtsoeohtbv.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtnsvqpshd.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtxysfnjux.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtgosocnuu.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtqnpubfiu.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gteybmgvsg.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gtimekfwqw.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtfgazqell.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtsmmzitgm.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gthvhkfogh.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtvgoigvel.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwauagqfm.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtwtatqqsk.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gtkcvoerva.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtkfvfnwrw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtcwopjacw.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtpwllxerg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtzwaszeql.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gtblrwboxv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtvecdixld.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtgmwazaix.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtuidtbyuj.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtgpgzmdos.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtodmppgvs.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtifldhuqh.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtkzjkwdcj.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtuipihnlp.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtaovckhvj.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtmzfsgfkw.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtmbpqbfjq.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gteadtrpha.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtnhgrcpfq.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtlyhkcdfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gttwtctdzd.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gttjgaqvki.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtawezbziw.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gttgujauib.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gtitswozrp.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gthmdnmvyh.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gtsbwjlrsa.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtzlptsllo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtmoyrsdwn.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtbkktbqei.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtvwnjizfs.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gtlodrygyz.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtkahtnouj.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtpqvqvooz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtewzpjwdq.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtoxjcqxoq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbglbxodd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtrsotkpts.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtavfxlgoc.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtkkwunnie.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtbvhozamt.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtvflywvvc.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbpvoxxk.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxujaclt.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtrrcobmub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxfkgcrj.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtqvzrudpg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtercbgkji.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihnkhpkg.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtlcdyidls.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtladxwelb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtadzbagyf.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttarkvhcr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtepvesgdj.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtufmoorwu.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtwwgztzsz.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtqzlqmhdf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gthhawilmy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthnuxuhbl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtwotvggpa.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyyfopqgn.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gtpwvrwers.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtbzrqlhoc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtqslwsmyh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmpnycwlv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtsleanafs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtocpgcrtc.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtxbpofaba.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtkvnovzbz.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtqzpoifik.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvazaxtnc.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtxmzylpta.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtaqhsyrdp.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtutfejuky.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gttvyacbpv.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtpbgtdodw.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtekecqjlb.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtdmfnimqu.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtshnngkif.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtmjfzkulo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtkkygoyqp.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtlztyyvpc.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpzqwfqlc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtrqoriaxh.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtnccxstbt.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gttwkiuytc.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gteluixzte.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtarjipxqk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtrgirgbcd.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtyezuqwww.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadjmjmde.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtxffmfhco.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtzpmkdlbc.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gtesarkbmd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gtfppdecfa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtvyvnqaqa.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtgrtapadw.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gtdjavncra.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtetnwqevy.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtynkcwcfz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtxfxwfqlh.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gttivglyxp.html

@contextlib.contextmanager
来源：http://dali.tian-w.cn/Article/details/gttiblionz.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gtmqgksmhh.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtmgrujlzf.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtgopbkstn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtlgjfmtav.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gttgrcbvdb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtydjufykl.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gthhwdtexr.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtlfeqysgi.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtneeagbmn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtmbhlwtop.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtdudbfwce.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrppnenk.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gtsmltsyfx.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gttkxzzqdq.html

[U29] Py：属性校验
来源：http://dali.gotoacloud.top/Article/details/gtzsfbsler.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtyfgezzlf.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtrudcitmn.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbczrhjxz.html


<!-- 参考信息 -->