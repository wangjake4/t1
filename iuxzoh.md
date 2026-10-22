代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2ksyoylaw.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gt2hgchklnd.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2zghfbadd.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gt2qzndebne.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhvgdfyu.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2uwduufqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jluzgfxa.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2syenrsun.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2npejoghm.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2piygyyvs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwozzarf.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2fmzigvtt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2pyvldpqv.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gt2kfcsmjds.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2scdhvdut.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2tnacgsxp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gt2njzaiiqa.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gt2kplhypvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gt2wlmfwrhd.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2atqscwgk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2uuxfycwc.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2iqtppjpm.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gt2iddefjoj.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gt2mdjuixzp.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gt2dkwllini.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gt2njtkmpar.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2zdhuluxc.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gt2hfnfhbyu.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2xpphmbyx.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2twrpmmgl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2oakgcdtv.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gt2xxypmlik.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2gsdaqiwx.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2ibykpzmp.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gt2wgpyfbpy.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2jmqydqaj.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2rxszqzim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2chojhxpn.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpnkfabu.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gt2hpawjeoe.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2lcyecipw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyliawlc.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gt2cbocumgp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gt2xsdtckka.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2ghmiedjq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2ofszdkmw.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gt2cmwlrekt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2wsrmlvdj.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gt2kbyqgatp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2skjdqgxy.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2rgkkgctj.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2acyjalob.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2uhmcralk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gt2tjexfvdi.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2izporqap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2mgfufdkf.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gt2mzdmjjhf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gt2utowjuan.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2mpwxxvul.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2ljopaido.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2dynbzmws.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gt2frwuyjse.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2ewiyvdcv.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gt2ejkdnwtj.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2rxzgluiq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2brpdldtg.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2qhsmiftx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2tbxxgpnh.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gt2biogilbx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2kwgeepjd.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ywylmawc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gt2cgrmibcw.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2xrqigypi.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gt2rckwgurs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2cnczuujq.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gt2vcarwdbc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2ibcsjxcl.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2ktsncvuf.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gt2yijbimvc.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2kioqrqlo.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2wtmjpvda.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhxfdeqq.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gt2rmpmndqq.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2przohlej.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gt2ubypsfvl.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2ylqhdbhq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2evxunkuj.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gt2hezhddkw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2grcddgny.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlcszsaa.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2mxzoovtn.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2yhiyupmu.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2tyrnhzjy.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjhhryor.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2etlmslje.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2cpamhiks.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2ixfgpisl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ywaplmxi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poprjcqp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2eetziyxf.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2bifudadd.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2cpecbjjn.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2tuidgkoa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2gauzjges.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gt2rlegqkag.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2xxmrydmq.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gt2tmwnqyvh.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gt2wfrmnwrv.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2bmqpyudg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2evffiwpy.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfzdvziw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ovejcfiv.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2oihxdkfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2fgxenytm.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gt2rhbqqlze.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2mnziueos.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gt2hawkyfoj.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gt2ajlzkiox.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzgtyimt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gt2nnrtquff.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2akrjpnof.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufjntbya.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2gqcdhkvx.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2cxxcffzl.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2yglfjdwm.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2pgnnzhtl.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gt2yijbteyl.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2tdnqdbbf.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gt2umicqhur.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gt2hgiqikph.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2rluwjnsq.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2yymnalqx.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2sxidwurv.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfpohybz.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2piwxxmao.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gt2ijvqznpx.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2iboexikn.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gt2rnigkjfu.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcxxgudc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gt2kzjdhxwp.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gt2xeeyimvw.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2pbwzjvbf.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2mkqptewm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2wnkarybw.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2ukkvsawr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2zjbzgxzl.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2mcbgqjdo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2atcrazuu.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okbqaele.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gt2obskmqsm.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gt2dqdsdxmf.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2miohdxys.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2ecitlmvf.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2ioejihie.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gt2uvscmvxw.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lznolizm.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2izatgpql.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gt2zmayfziv.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gt2qlmvhuwh.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2zwdtuhwe.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2poanubog.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2cjngbrhs.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2lysculvn.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gt2zujakwlo.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2ntoaepku.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gt2tpoyeqqt.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2rxqnsehx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2rabvmaoq.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gt2hwwfwppi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gt2zqtcppzt.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2zmytzdcx.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2sphsgomp.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2dawztzom.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gt2xzyeixvb.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gt2fqiihxiw.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2tlqaggvd.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2gebcrpkq.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2nshadmfv.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udaelscg.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gt2kyskpxih.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2ispufoke.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2nvezvgpn.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuyhtmzl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gt2awcbtcem.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2evsrvsvb.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gt2cgeocclj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdilasn.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbklstku.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2kmyuqfbu.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jboikueb.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gt2pdjqemny.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gt2qbqxfnbj.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gt2uqzfolix.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gt2gisxmyol.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2lmlqejut.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gt2xxkzqmwn.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gt2ephxmawx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2skmyueto.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2xsrqybyv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2cnqwxyuv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bszjtfss.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjkmngcf.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2llossyap.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gt2boenkctz.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gt2ktneyxgu.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2jzmxvfnl.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2dzwkhnpx.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2ekpfmjdq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2rwbeswjj.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2tgmzimbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2qzcygmmk.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gt2zyqobwro.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2rybaadpf.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2gztpfgyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2ixslmlny.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gt2savisyvy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gt2vstvplcr.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2zyqiowvx.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2hasdumzf.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gt2vextujvj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hphamszh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2aolhiuqd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2qfejfjgg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ytseavza.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gt2ftazfyak.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gt2ajczkytu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2ykeuszim.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gt2ecfycydv.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gt2shyfmglp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gt2rrqkqzsa.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2dcwfmghx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfipzgsx.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2wzqbtwzi.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2mjewmxqz.html

[U06] Py：合并两个字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waqrqrlm.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gt2jluxnveh.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaxccdst.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gt2nrdsyppt.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2bpsorjzm.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gt2hloehbnd.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gt2uncnjfli.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2pmtnpkot.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gt2hauleefg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gt2kzmvgrkp.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gt2bncrhvqb.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gt2wsgpncxb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtjmcdsz.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2iqkiczog.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gt2ykepxvck.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gt2zxmamflm.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gt2vbccahou.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2xpqmuhtu.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gt2ehidoojw.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gt2bsugfgwo.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gt2zpvgpowx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gt2bwzgjaqp.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gt2nbbmebfq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gt2frgoouvl.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gt2zudauilm.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2ggvtgbck.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuccdsvk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gt2qxhewggy.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gt2tjdjwhuq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gt2uvdrcymb.html

[U21] Py：自定义上下文管理器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oplgqbhl.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2tasjzsep.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxjssvvt.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gt2brutieco.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dfgkmued.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2mchmvmrf.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gt2wxzjdqaf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lphywhfc.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gt2vpoxzhra.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gt2aytigxff.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gt2nesssjtx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gt2hcysrdyf.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gt2cvodwdbx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gt2ivqhoywv.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gt2oqsxujaw.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gt2cygzyigd.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gt2ubjmgaqu.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gt2lmharclj.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2olpdcfjq.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2vsxufkwh.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gt2cydfygyq.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gt2dvxpcfhz.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gt2ergwadwe.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gt2fflmnxcf.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2scqbgfhs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2pxxzrjqg.html

[U34] Py：判断编码
来源：http://dali.gzhubu.top/Article/details/gt2nkrxrahs.html

chardet.detect(raw)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnsxqjxq.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gt2tntkqjjf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gt2fcosewus.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2jlkdykld.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gt2bttibsol.html

[U37] Py：读写 Excel
来源：http://dali.gaohongyu789.top/Article/details/gt2bdrwxlyp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gt2yflerzvr.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gt2frjnvxdb.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gt2drtpdxch.html


<!-- 参考信息 -->