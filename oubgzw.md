代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtseykpfmd.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtwilevctu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtyeafpusa.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtgxozrxfp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtjercojlf.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gttbipogki.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtdhrknggc.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtungxnefy.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtkugvjzvv.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtdqwvufvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gthcdpfflf.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtbzghwtnc.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtmphpvykr.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtxqqoqodc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gthghtlxju.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gteypzhcfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtljrssbeh.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtmojxsudd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtdwdeafnh.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtjyehuvjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtewqscmby.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtoomzbhux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtjhhiihry.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtrehjpgmo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtyqoocrfi.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtlvvmbuok.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzohvacf.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtsljauuol.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtuftcfqzs.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtgsdlrlph.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtoasantzv.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtrraptlov.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtjbnuwfib.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtqerwiste.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtyugbzoms.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbergdmyf.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtuuatblkk.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtgzypyshk.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamynwpgu.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkzmjiehs.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtysquwocw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtswuvtcyr.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtqfrqsmye.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gteiqzwgzi.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtdafsvuum.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtqnyuioml.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gthnfalngf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtndhsquwv.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtxqqmmron.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtxpftmjly.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtyqupanfr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfidtyeq.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtevrhfgjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtalfrlqbc.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtolxmuney.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtmrygudcr.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtzicykhdp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtnvtlvume.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtdpytcfbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtxpqjzrdq.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfjhqypfs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxurtgxmj.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtqozakohh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtawjzendw.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtacewhnht.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtrwsujxtf.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gteuohmpbe.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gttnsixgqa.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gttdxonaqx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtldvtwgan.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtyjuxuxfq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtyswqiadt.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtiyjuqufs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtczmxsjeo.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtqznliylu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtoejglfph.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtxucoanyn.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtdwqawspl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gthkcilsjh.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtqapqzboi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtghlduxlp.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtkjisnngb.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtzqpixxfu.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtakxkpdib.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtntztkmei.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gtblcnzjlz.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtyesrgbmv.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtcepbwgpz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtdpclaqgf.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtnywuyefe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtjwzryfpl.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gthzfhvekc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtruevjlcp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtjxunqmtc.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtjgmtmkpg.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtsninsuzb.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gttejevgta.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtxrbpmqap.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtqjxwrlpv.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtvfpwzpqi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtfjbzcegs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpcvvjvua.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtiwkhpesm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwhkbegle.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtbdkuqash.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcambjwvb.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtyjpwmhvy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdpnynqh.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiypljavj.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gturccsktd.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtkycomjiw.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtzmuhphcc.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gtzbwwbtqg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtaxsxqmek.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtcirkyyab.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtutgvbblq.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gteslrecwm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtwrwdalmn.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtlckdrtzj.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkptgchpn.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtgpgytwpv.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gttcdjdqko.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryvivrvm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtjrrjbbhn.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtxfdubsbg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtqkchsssd.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtryrogktt.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtbqlmhbvz.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gthcbcahch.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gtyyytkhli.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtxewonxct.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtrhvphfoi.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtmblachne.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsixdmxka.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtugfcinww.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtnhkqylkc.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtomuziccg.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtrqjmuswa.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtmuyiaedr.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gthiktxksa.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtqgnigmyr.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtqphclpiw.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyjdwybv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtcuebfyuf.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtrenhxxyz.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlotgcnos.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtzozjfdtc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtlfyqmlsp.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtbdxuwhjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtqagleuci.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtslqspzbe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtljnupngs.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtvvphhaci.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gthfriyyfa.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtkxxbcrid.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtjxtylntv.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtnbojmwfw.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtuvbryipa.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtgtlypsbk.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtwcwpgibg.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtwrupilgi.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtmbotxpyc.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtxgfbnjzb.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gthpiomjov.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtopdthfgg.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtdgkqbjiw.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtfnqgdrzb.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtscwisekq.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtxcuynjgs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtygvkjkzo.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtaltcvxnf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gthfpixdqu.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtkgmhec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtagkdmuhr.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpjjbgdxc.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtftlmjmva.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtwuikovfd.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtfzdiaiqu.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtcwmkmwoy.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtlmrainia.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtsqnphghd.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtodlkqmhw.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtoqpwrmtl.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gtqwcscayy.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtsdiyxqcc.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtrwwtpork.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtoizpmzty.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gthdxxpvnq.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtsffwzidh.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gttdacejje.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtuqhilsqr.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gteystkxgr.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtpshikqnp.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtqtuscqcc.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtcisgfeeg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtjhbhzrql.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtuideiyuk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtcvkedsny.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtszirssza.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gtfuzxmuuu.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtesqdnjda.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtbvbkagvd.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqphycog.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtbqchqptd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gttmqoblvz.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gtmjqwiods.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtaqzydmic.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtdicdolnq.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtugivgvvw.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtbtldbird.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtsxotefub.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtgwoqyfon.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gtlnvnytvq.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtrvzuadzh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtdkyrrtdv.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtuuzjczsw.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtoiybmuuo.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtmozvlnqk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtaykekbav.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtojadyrcf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gtexbexove.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtycxdttsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrefzszq.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtnsuevljn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxumsaw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttriyqavf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtqfmipfec.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfwpzsfon.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvovxjre.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtdxbltwep.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtxnftzpnc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtbninhyqk.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtepjsaimg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtjeatwxwx.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtnhgffcpe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtehxydzlt.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gtagpnlysl.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtesvgadmo.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtwmbuxfjy.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtnzeemrsx.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gtswrntuar.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gttrabbjtt.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtyxeufvit.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteovkvnxx.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtnsqsgpst.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtuxtckkln.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtvjhsfbcu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtsvcsrorl.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gtfanuhrxw.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtgwlahaac.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtqudubhmp.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtemkpqqkx.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtmupqzjhx.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gtwrrckimk.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gtvgftbkvy.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gtlsdvpmrp.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtllrwufmm.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gtihekhgyq.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtgbfqphuq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gtvkzpsjcn.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtvgrowqjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gtnuxhvqsu.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gtvmownzeq.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtdppeqyxh.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtcrvokttu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtymfdpzfl.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtcmcqgdxv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gtwmdiugus.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtubbjqhtm.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtugaqtnjr.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtykvknzyw.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gteivqtqiq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtgfjhhmok.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gtcgvwqddq.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtgtkdgkef.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtaavrpyzk.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gtvmuxqzfs.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyqsstep.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtnfdjaxmq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtutydcowe.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gtddrgjplh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gtiviczuzs.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtifydpcla.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtigzkpvoq.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtqttmwcil.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtlpgwsnuo.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtszmztzjm.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtrosrnplo.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtvxjgyewu.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtaacjnhkt.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtwdflkmsi.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtbhqwebgm.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjhddrnh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtwioshdsw.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtrifpcoay.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtatbldnet.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtbpgwlvnz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gtbyhljnuz.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtfnrdzmxd.html

schedule.every(10).minutes.do(job)
来源：http://dali.bjfxy.top/Article/details/gtwensflcj.html


<!-- 参考信息 -->