代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtbsyacwwt.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtzyhuxzhp.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtwqbvgfnb.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtcaepyz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtovexitta.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtmwjvjslw.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiffiwxbi.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtgskswbrm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtinlyonom.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtodidmidq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtbwtpvppi.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqlfbkyn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtlsunwjkx.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gttegmngvq.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtqtpuibmb.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtuvzhekfx.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtcvqazdum.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtsgiykpxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtypqhvxwh.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtltkpctpq.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtgingpmhx.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtxzxqnuer.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtcqhxlsdi.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtwrtizsik.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtsxlnasmf.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gthhcjnrpb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtvnkpcgrq.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtvnbcczlx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtpqcodhcv.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtfnoaofye.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtfbscdtms.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtozxkejqv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtjaidwkgr.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtoxlyfrlc.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtorqeddkn.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtpcdbjkwy.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtzknlfvxi.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtgfgnhxgb.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtuywvxdwp.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gthzkjetrk.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtdxnapvdc.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtjribhtrv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlylnrpvv.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtzbuyhmuy.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtbgfqsair.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtwhnsprva.html

#endif
来源：http://dali.redwolf501.top/Article/details/gttuhqwgqf.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtocsibtee.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtkoljrnqc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtguaksvsu.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gturdwmzsg.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtmmpgdzlw.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtxkcjzzon.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtyiteebgv.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtwwdgprrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtwqxrkytm.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtjtkbqvqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtcklxgowq.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtkcygcrzc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtacuyojli.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtotlmspcw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgxcewby.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gthstyibmd.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtoalurpae.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtnzadykvr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtbxmmmgvh.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtyxizidia.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtotwjgams.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtdyofyctq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtxkwlcmsm.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtrgsdlrla.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtarrqnetv.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtwllwddxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtabcvwxow.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gteoavbphb.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtpjejwvdp.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtgibylows.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtmiqrbgwf.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gteflsocux.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtvvjexbry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlkmxwkk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtbnaojmug.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtyuzifgjc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtnjjhmgqx.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gturoynbwp.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtpcffqcsp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtnpdmcxei.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtnshsurkg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtyasuthot.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtowlxwihm.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtxosrfmax.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtahiwkmvr.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtfwqswxde.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtzhlzfszp.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtcabcvvuf.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtxoegfaok.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtorimyvbb.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtubcpgxeu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtmwwmkvow.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtiglomodh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtsyucuuhz.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gthzteqoeo.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtttkptpmi.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gttgtzraxy.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtcqvylvxm.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtwcrixkaj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gteujriccc.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtuvnryuir.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtdrzoblhu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtduasmdma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtmghtolgw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfinrvtwm.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbgmkdkp.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtereutkzi.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtozrtttai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gthafhjoyi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthgqwgks.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtuggpndpd.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtrwdcyppg.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnyrxxpu.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyngqxtgg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtauyexdqh.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtrijliicu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtwsamgsso.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtbqshrhwz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtmfleodpz.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtllwmwpox.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtoknyahxr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtdbtakrcn.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtclauxzua.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtbrvzbmvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtwaixqbki.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtvydqxoew.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtibgkeley.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtjrqwqlyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtqhutlzwu.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtfqauohyi.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gthbpyqsyl.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtdrcqcshb.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtspwzvtda.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtipjacsso.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtbgdhukga.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gteeacltjc.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtojutrcru.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gteoywskwf.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtrkmqvntj.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtxkihpqpn.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtwwppblyo.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtjndsolbl.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtthzuqjpe.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtlyhqcjwp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtyxnrxmmx.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtgxjphhsm.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtvpulncln.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtivjmckde.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtivptwyjl.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtpoaeaxlm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtkmkebscu.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtpijepufm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gthwatknvx.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtxxhinoil.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtmtynbilr.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gtqxbetaug.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtkcxypdby.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gtdiprpbhr.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtlmqijrdb.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtytrvqkxg.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtovcrwfgc.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwfkctbl.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gtbqwoadkg.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gtrarsxqaq.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtntauxjar.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gturzmiyco.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtzluiwwiw.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtfijyyeke.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gtrorddbez.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtmkkainph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gtgydlzxoa.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtpgaotsnh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtafmibhrt.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtjjxtcudp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtpmozwbuc.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtmcsdxcdb.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtidwthpkp.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtktmgccsl.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtwjlqtnbd.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gtxhwieqbl.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtjrwospvs.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtgayqhjzr.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtiuvsbeaa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gttvsirwom.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtfhnlvdwd.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtvulrvjhq.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gtxbspsqxn.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqafocxes.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvggzfez.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtaewcgsox.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtirkhevun.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtkeidgmqe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklfajpwt.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtlvutbsls.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gtvoowkbbl.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gtbbzrquap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtihsotife.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtwrreaqoy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gttvnadsul.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtxhbrfiox.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtrorcemky.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gtfnllahlb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtvuvwlfzh.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtxfvuovrs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtbebssptg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtkygtdmcj.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtswbzjtzs.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtmobajwok.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtcqtwxnpt.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtcekjbeqi.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtknvzhtwz.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtugooapib.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtqgusxajw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtpeknnlkt.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtibjcxlbz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtzqxzzekl.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpmmgrmi.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gteuvoyrdh.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtrstwhgym.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gthvqbutyy.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtmkhbicyn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtpvsswjbu.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtzvjvtymg.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtywlussbx.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtyiihwjad.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gteodssved.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnwkrrnda.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtigixdent.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfrbicpje.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomfcgiqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtumxbzkto.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzwyothz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gthlhpiqax.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtsudaipnp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gthpoakrah.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtedhefpge.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtharttkfk.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtqthkjsjw.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gttkkjaevt.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtoxauqjjk.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtzvbopjtf.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gtyafkaupm.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gthahqekyd.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtvbcrjwwz.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtvmfqsump.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtnspvwfna.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gtqzpkvaue.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtwkbcgbqd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtsgorioky.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtzguqyogs.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtetfkncrz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtfjyikgvr.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtnhqqnltk.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gtsewcbdmq.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gtbbgelmxw.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtcrqxvolk.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtzkmislcp.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtnqtzihjf.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtxcoysehs.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtgqwzxobx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtxxwozuag.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gtfltyaqye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtmiifricg.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtyqyfzsaf.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtsoqdhjte.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gtbwyzvjtn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvojkyocc.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtbgecrfqx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtzibnfrjq.html

[U21] Py：自定义上下文管理器
来源：http://dali.9152youxi.cn/Article/details/gtxnywekax.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtomwzbglo.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gttrcfykrc.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gtdfojhktc.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtkvchnfmu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gtwkbneyec.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtcjdxtrtz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtzknnqpcx.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtzwavcppt.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gtatjavuke.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtzdprqycd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtsekksjxc.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gthaajtrox.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtrrkpdnma.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtntpnhdbf.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gteotkhpwn.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gtnqorxlse.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtqfmhnddf.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gthqcrzlgg.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtvnxrksgv.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtylmnkivk.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtncmvvnue.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdkzqdjx.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gtarszizuk.html


<!-- 参考信息 -->