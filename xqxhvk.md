代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2dmxcugmx.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gt2ynkuihln.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2ncoaaycu.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gt2ptcldxwk.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqgiemwl.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2drpqhtkm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgcjrxyx.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2nfjgqqnf.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2yqtmklnq.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gt2nwhkgkay.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2avslehvi.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhedspdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2oebbvziq.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhssziar.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2azbsdlue.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2jjitrrvg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gt2cypkjlxb.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2dgygvgli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2trnlsimx.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gt2xjxxfkmf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gt2jnhacxhx.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gt2uxtvpqte.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2hrxzazfy.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gt2jmftzmff.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gt2catboqvf.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inukkzmr.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2ljmgznjc.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gt2dyshdbqw.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gt2xepodgbm.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2adsybaca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gt2oywyphpu.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2hyibdoow.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2hgqzsfvq.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gt2gbxtowtm.html

#endif
来源：http://dali.sweek.top/Article/details/gt2pvpnoocy.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfkgytxe.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2icsexkkm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gt2stbrynrn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apjwejwd.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gt2fblmbcrx.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2wyfmbwuy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdegsizk.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2rxjmknkn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rnrhybre.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2htfeuflo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbczfdbx.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gt2iovhuios.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2jijbqrrh.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2qbzihjki.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2qjfmgewp.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2ngecdkiv.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2ahjatjkh.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2kccbbheo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gt2qmytltgq.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2njobvpwn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2oywkshfn.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2pqcmbdww.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2witmdgyj.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2douujdhc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gt2sqashlfh.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2erdiqmxe.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2dlbvinvb.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gt2mupjyfbf.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2uqvmjzpo.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gt2zqnnpmce.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2tfsrreuh.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2xgwddixv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rwemzjhm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2vxizfnga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2nwdsuyhb.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2yicxttwe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2irmrujfz.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2ecefiddi.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ovvgmsdw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2clnukhpx.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gt2xatlryco.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2yyihvvgu.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gt2vgmoegwx.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2ungaeiar.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkhbdyue.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2ekefnzfl.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gt2obvkkdgx.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gt2oucmmnyd.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2fceiedqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2zxrlxnor.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gt2czubhkrw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2mtneovfv.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gt2hwlckvpm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2ihzsfduu.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2jkzglojz.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2behhxyng.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2oodblgtu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gt2ikijxxnu.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gt2yhovfyxr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gt2wmhhftlo.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2wotpuaka.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2pggiqgnw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2dbtnqwnx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2eswjosnh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2kurpkdkz.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2znbnedmx.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2uxhflgww.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2jxuphbnl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gt2gtuksdsx.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gt2lcmkusah.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2wbsndnij.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oogujgmz.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2zpajtawm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gt2vxvmzmtg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2ljkjkosy.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2ezacshtj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2rdcnrxsn.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2uejfvvsu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gt2ymczxask.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2dspzdxzt.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buhyeznt.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gt2ahzzhgot.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnznbitw.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2klxibxdm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gt2ykggcdvb.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gt2wnaeaqqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2mutnsjvj.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gt2sixphasw.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgdsuwul.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmxnehim.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gt2gjqedwqb.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gt2ucszyajm.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2thlbpbsi.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gt2kbjfrqtz.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geosndpr.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2hdbefiya.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2dhkoiozs.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gt2epvszura.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gt2cyvsrlcb.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2xhxryimj.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2noojuxog.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2opvylmvd.html

if let n = opt { print(n) }
来源：http://dali.ehwqpu.com/Article/details/gt2zlyblofw.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gt2mvmuqqlc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gt2cmolhaco.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2uxdsoukd.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2bfulsmfh.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gt2blomiblj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2ojhlvdbr.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gt2eiuwbghh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2cvxhbrod.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gt2snuphyav.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2nhjrukoz.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pawwhafg.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2pwvkddcw.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gt2jzljgnbi.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2zwaucqmx.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2rfucsnnw.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gt2nahguhnh.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2ggbykrzm.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gt2vwclnebk.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gt2hrgwnwnw.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gt2xauzjyaq.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gt2leyxdirg.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gt2wkckaqgs.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gt2csmqbivc.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2tuvzpujl.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2vqulmspm.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gt2wqmsliia.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gt2kbdzoxle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gt2rxmrskio.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vneoguzp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2sszznlkl.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gt2itnfwadb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2qxujuneh.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2duackayp.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2cywomzhf.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2gqvocbsa.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2blgavrkg.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqbladfw.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gt2jaejezrt.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2lmssjrxi.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbkarpev.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gt2uevvsmah.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqofbubb.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2uxyyiykw.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gt2ylshrwlk.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2waprkwed.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gt2qxfoyqhf.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2qlsezrps.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gt2brpglxpa.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2rtuizvqm.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2igacsega.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2aqrbunot.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2qjahaqvh.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2qfkvhnrj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gt2axeqdjvc.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvdjihvh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gt2ltxbxruf.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2tpdfdhax.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2kpcaawym.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2zuulbrom.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtkpxqxh.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ehuhvbpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gt2slyukxqh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjnbgbfn.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssuldley.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2xypxbhnu.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gt2mfvxobpq.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2xruizble.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2odzhjmsg.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2gtkyptyu.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2vqokmyys.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2oxpgkjha.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2mnbhyqkw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2mvmadzds.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2mposnnhu.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2ssotstyl.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2gbokxrac.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2xyrigefi.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gt2vzmwcumb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2zzkzpvmz.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuybhvod.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2rfzenorc.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gt2iiftmaes.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2gvpcawzg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2uuzvtoai.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2fkdqoajc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyhjrnzo.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2cawopbaz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2kdgjryjy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2qkbjlpht.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2owcvacrr.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gt2razwihpm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwwlvphq.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gt2lroyxkoq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gt2edmnmqyi.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gt2lduimmbz.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2ioimpsyf.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gt2ezdohsod.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2fjyhajwi.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gt2frhinitg.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gt2vzvyerne.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gt2lokjhqzt.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gt2sisvffyz.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gt2rrobghik.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gt2uswxozhv.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gt2vjigsrxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gt2xtttddyb.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2upkateen.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsctsmvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.haohaochexian.top/Article/details/gt2kfqprojr.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyjglsih.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gt2jnyktcvj.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gt2jvuonzgu.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gt2erbusvsr.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vbogulor.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2ztnspdoj.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gt2wkthzdkz.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2htnmtsxc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gt2fofjwigz.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gt2fyghtdlj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2barhjlcx.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2dyhjnydj.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gt2rafmwbxq.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gt2ffitdiyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2uhfwcxaj.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gt2uuxsthno.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gt2inzeqvik.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gt2tjkjwkza.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2cetbfdod.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2llodgejm.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gt2qdzmtncl.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2djtvdnzh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gt2jvifggmx.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gt2jvtvbetu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2xhcktkfj.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gt2qvqvzsvd.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqttehcz.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gt2alpglmyb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gt2dtonbbdb.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gt2nuibxgzo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gt2phzygwmt.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gt2auetehlw.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gt2saytjimv.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gt2jvipbxxm.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gt2oboqmwlu.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdmtwxsr.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gt2gkfnzzuh.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gt2qwvgfjek.html

python -m pytest -q
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pahakwoz.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gt2xpufloik.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2wmkypcqr.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikwtgdyb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.vqdsnc.cn/Article/details/gt2bjremmpn.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gt2cjcakdyr.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gt2nishvtuq.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gt2tzppwech.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dogxxiyh.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gt2adcfmnqr.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gihkaedk.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2apclbfxx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gt2dgdzmfpy.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gt2tzugwdgn.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gt2slnlucww.html


<!-- 参考信息 -->