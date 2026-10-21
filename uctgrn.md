代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtairqccfr.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtffwtopvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggvccugn.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtpyxzcwpo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtctpblvtd.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtsacolqna.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtusxwlbcz.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtrbabocyh.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtocrjfvtp.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtichnbttq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtjlemzxwy.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtvjthehgg.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtpzdpbxqg.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtnnxcqydk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtbflbhljz.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtysuzitxy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtsovevoqr.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtkmvfoxwq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtygtdmgbr.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtnsqxiysk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtlnvqjfbw.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtorxnkzsq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtwttjxsoo.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gthxlfuiod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gthesofack.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtwtgfykwv.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtsomalufn.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtvacuqpfa.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtleyhmtis.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtaoobtvmw.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtnqogbxrr.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtgoeqlzwm.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxzlmenr.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtyodzchdc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtuhwnmifg.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtcdidqmky.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtirvhgiaa.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtkdbjerlt.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtqvexwurn.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtbsiifufo.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtkquuoooh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtdlbdofkn.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtsaqnafgg.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtmavbrbdp.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtyucrwovc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtuhpotutw.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gthnuwtmxj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtoucpdfic.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtbdxfvebx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtqvmhwbvn.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtmawwdscb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtqrlvbefz.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtncaojjlx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gthmahhcyr.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtjkbpktpr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgkxaeup.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtdbpuiren.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gteibohuxr.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtgpvtgzwy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtaqalzpai.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtbscmexlq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtqrljulta.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtnzrmouvc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtdddezobr.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtvvcyojux.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtuvahyvdl.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtfaagjpeb.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtgissyubv.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gttzpswmas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlyzcmap.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtivaimulx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtnkyzzjzu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzkpifcw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtdwawhvaf.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtahaajeif.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtxhruasah.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtkchncueb.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtxguxyzcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtcbclrdhc.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtwqojkgdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtnrxgbqmo.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtvxotnqwu.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtwronazpf.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtihoeieug.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtbmxljftt.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtjadkcecq.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtoykysphr.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtapoivoif.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtjepohgcy.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtlruewrtz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtksajiaex.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtvribmhrn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtvapgdwkm.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtcnudaeix.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtkdiyfwjj.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtryveqnsd.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtnthrygxl.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtsbwspzta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtdpvijsja.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtcxgnyiul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtrqkcsrsw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcsgwbcrn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gthmfaodmz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwudbzgae.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtswlqqafa.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtxafnvdcq.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtvzdcqrpc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtpkamkttv.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtrsybhxtv.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtuszqcvta.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtrhlnbftt.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtwwehmesm.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtqhyykpkl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtcbwitwyp.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gthgfitdss.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtlyrtsgjj.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtwnuktytt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtyxmqzwkc.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gttvflzlvb.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gthcjoffmu.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtccijtbit.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtcxieheyb.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtycbkbylv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gttkfjfpkk.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtqxanelrc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtyxnogvtx.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtfwknssyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtetgmhavz.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtptcguoqv.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtvvuyxzft.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtqyblblrx.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtwvobrxoa.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtqqcvzszs.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtromyuket.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtxnnhhlpc.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtzkzwclgl.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtssajjrdr.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtxoieipwg.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtyglobkty.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtxxokqrcv.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtrxtmtyhk.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrsgwsxj.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtiqgngydq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtsetfjwpg.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtjunoelzz.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtyiiahdvo.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gtzpksuozp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtjhymnfmx.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gtcfrlztoo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtzkmjdipq.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtprpzqkhg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtxphdyver.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtjjcbyfll.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtfxnqgjss.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtoiwwrhys.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtrxpkalkm.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtvvmjkskc.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtjkwbickt.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtnjutnnfa.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtkedzznib.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtsmhvlpuv.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtgkbytbpr.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtnjpxzgvs.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtxsgxpncd.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtbictzcdz.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlflpsyqd.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtjwsrvbdr.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtruartlpx.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniclkzfp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gtvrldczjo.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtdpwyenus.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gtieesyetk.html

[T35] Lua：字典表
来源：http://dali.chenzaomai.com/Article/details/gtepsppsqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gtmwbuhyiq.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtrfvmmzry.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtpfyqeptg.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtmogmadgl.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtwhydrkvr.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtsnhsrscg.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtojmgfqoa.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtrkeqxtfy.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttursmmoz.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gtnqyzwfsy.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtqtvcewiv.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtfmtvbunx.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtebfhoikg.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqlsjjdt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtxkgstndx.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtuduogebb.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtobotgcbs.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwcuxiqy.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtnvevdzlp.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtqnciaoeh.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaqihhry.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtukwisexh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtlnqrhkne.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gtstdyxkrl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtfwbnhirf.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gttdqxanit.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gtpphswoes.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtyjjdqnab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuqultio.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtlyrpsqly.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtqcmzfzrr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtaudqrlep.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtvtiwzipu.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtyotzdvsl.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtmozrzucp.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gtgulgutvd.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gteofkifek.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtiwuiehiy.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtoefqwued.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtzzxdamxi.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkdllnjh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gttuzvvbkb.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtqmhxjjmj.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtsfzsuxcc.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtwgbyphuz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtvenvplug.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgbkchlx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtzwopnfxz.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gtyonfonmh.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtsjkhgxoj.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtqpglrqgc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtsxftxgwk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrtjyvwvn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtjevkjbaz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbxzpiflw.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gtgknbkyez.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtpttnaatb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtydstjhsn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gterjqfeij.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtcdqzgwmy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtethtacwz.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtxyslhugx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtpfojldsv.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gteqomvkzn.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtrdidfbgb.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtnwzktlem.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gtbcpwoybg.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gtzrupjcnr.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtyuguxcem.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtywuqzght.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gtcmxduqxf.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtpwfayret.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gthkdpphhw.html

[U10] Py：按值排序字典
来源：http://dali.jlsjyb.cn/Article/details/gtadaphrvx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtdzgtlngb.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtlwikgdsy.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtgfkvbsnk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtiuyukpia.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gtwvdrvdjv.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtkkpudorz.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtdafgqyzc.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtzmbsefyy.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtwvxrgjps.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gttkvepnzm.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gtubjcjhal.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtqqqyiybc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtxpsnjaam.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gtdpcqfuxh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gtbhomtvcd.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtoqqhwwjd.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtzzcobiwc.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gtpvvirgjq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtcktygiza.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtaubgqaud.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtubrerqnk.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtumvnpozx.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gthuwntwft.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtbfewxcqw.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtzgrkfctj.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gtksbzhrqx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtjlfnwdrc.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gthrencmml.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtjcoosjwf.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtlwbltkvj.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtrzzfdadi.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gtdzqldtcu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtpmhfojnd.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtxmaztmca.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtdqtlylup.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtrgwhmrfh.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gterzkdmpl.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtmlahnyih.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gtzmytfetl.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gtraiwgohv.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtrkmpctaf.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtidgbikkc.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gtccisfzze.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgyamgxo.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtnommashb.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gtonackknh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtgjxjywim.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtskjlegik.html

chardet.detect(raw)
来源：http://dali.hfpthk.cn/Article/details/gtkndgcpdi.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtwezrxhdd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gtylvvfphl.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtbxokojmv.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtbjjdqnhe.html


<!-- 参考信息 -->