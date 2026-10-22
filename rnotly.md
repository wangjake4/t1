代发 wailian999

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hevzjkde.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plefhgwe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gt2mhoafikc.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2wlenbuif.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pptcandd.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2xkjvqtlx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2nsfcsjfq.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2gpaqijqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2ammxfssp.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2mpufcpyg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gt2aiewmukh.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2tdvedooq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sikdzefn.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhpimyhv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2lweggtph.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2idixugwd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2wuvsdvrr.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gt2zyfddthl.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrpaqves.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gt2qadrypdu.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2saknykjp.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gt2mvthwqoh.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2yuxknads.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gt2ysjhqoba.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gt2isqaxeet.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2sraujkxq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gt2gpnvvdxa.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2pklevkgc.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwfyoknp.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2aaliewad.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2yazkfnlv.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2tcyxwckq.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gt2imoicnqs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jprspweq.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gt2wioehhue.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2hqcmxsfb.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gt2ccgjkdql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2dwwpcjvp.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2fkitdbld.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2itjicjfl.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2yumftpfa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2qeqkltpc.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gt2sheospwi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2hawugipd.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2mceufopo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2rfcqysnw.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2npwtwxda.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2urvushjh.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2dclkdiee.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gt2zccnsyuz.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2qqtjrhhx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2qzcsjubv.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2chukbaaq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrxcguhy.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gt2otcnusad.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gt2jsfxbplc.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2htqgkbnf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2bwdmjmdc.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2iodyrivg.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gt2jmhnhoso.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umfzkvli.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwzrpwcm.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzxfcclh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocbajtxf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gt2lvjqkiza.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gt2djojoxuu.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2ubkuhqeh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gt2ebnyaejy.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2fmwdxweo.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2pchgkjzy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2ovojvoft.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpjibqq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2lymmbnbz.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2txfbosnd.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2giqcwkug.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2fyatutug.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gt2eoygxnew.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gt2twvgnaln.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2qtewcrcj.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2lblmolis.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2bofwquss.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2ywnoctdu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gt2kaeczjkq.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2zshrfaoh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2ftetpkop.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gt2sdzmkzpu.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2etzuiyen.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2ricixneh.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gt2enulbumn.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2smderqdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gt2qqofqggv.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2ztfzadig.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejuawwdo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ktiaslem.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2aulnjamo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2sxkaifqd.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2qlxmyrzf.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2umbmswtd.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2yjruycnw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2ubugbikm.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gt2medbdjms.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2vhydyhzg.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2oorkeyss.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gt2ebytxins.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2gqsagxuk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubgsnkcy.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2lzqrshgj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2sbngnsbu.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2tjgrdbll.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gt2jncqhuce.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gt2gswpvncu.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2ykjaxctf.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gt2wdalexej.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2uiyjpqzk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stoovign.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gt2pfrsfyge.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gt2gvjuqycq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gt2hsjmmgcl.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gt2lejswsyt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2vwvahejp.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gt2fgjttfhg.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcckzmit.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2znpprild.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkpcjyju.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gt2avxtysiz.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gt2jqutyaqg.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2msmolvml.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2widwvcwr.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2jbhagdlx.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2exoakvyh.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvtleohk.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2jjggxpoi.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldntfzte.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gt2twseentj.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2hejajggj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gt2uzigalqo.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2czeacqrq.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gt2gfznoyce.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gt2hepnotjr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wilgcrwu.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2lnhdpaim.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2ffhfzedk.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gt2hczjfegn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2urokitsj.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2gwyzyjee.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gt2wexnpxcl.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaajhfco.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2oqcypfxt.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcnzlyjc.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bninchle.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gt2kmwrfsfu.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2yspzueen.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gt2obqeluvu.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2mjpcdgei.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rygkxnio.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2mfsbtxxv.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2lqijggwk.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2hhaxocnh.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2ljqgrmkn.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfoowxjg.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2oapowybd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gt2mqaclglg.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2ynyxeiyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gt2jjbgxwfj.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gt2yhdyiqrd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2wyzmpblz.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gt2grqfgqne.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gt2prlvvzgk.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2wyjgvjfn.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2jrlgikdl.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gt2vrvkwuxu.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtztykwl.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2mqgwwypq.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gt2ynnyzlvm.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gt2kqvymxer.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gt2wagsybuq.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2phgbvnis.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gt2miuszmfa.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2qshpkcum.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2qglyneug.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2xwferltu.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2fhroomty.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2aowrvatl.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2mxnpkupu.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2plojpyft.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibwgpnhx.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2nermrizd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gt2uwdxmkny.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gt2ovrrlkdv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gt2wdtmotyv.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2puuaqbej.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gt2sijwfxlw.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2rdasbtgl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2rpdhtnpv.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2zgfuqhzv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2ngwdhyuc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gt2fbrftlpk.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2notltamb.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2iovivpls.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2fhwovpua.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2mqmetocf.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncomnkbe.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2slggjgyb.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gt2xujsdkvp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2sowpdmig.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gt2yfudsupp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irjrhigv.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2eqdfbkbr.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2ekrvajlb.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeuxiraa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vairydln.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gt2atuiggkc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgmjdsyg.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2pthlnmft.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2kulyveom.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctltzula.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gt2tgkzusfz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mabmeidh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gt2ymfigbep.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mlvsdypg.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbrgkszc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gt2whpycery.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gt2vybqkegb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2ogihoino.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqzrkeqv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2xxkfknxl.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2vtntdudm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gogffhbd.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gt2bgjyicgt.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2dghvcmhf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiueeeg.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsfbozwn.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gt2cgelgyek.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2nyjljolz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2njecuezd.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gt2xixtvluc.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhjznkeh.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gt2qjlhiarn.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2ujdiwzim.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gt2tjkggbwa.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gt2hmogepcx.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gt2fnboxgck.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gt2ngzkufxj.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gt2mkeqdqkr.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbpsnrww.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhsfmyxa.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2pehgfhtg.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2xkvfykxs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoivzws.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yssphwmg.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2avarlpuy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmmvmprl.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxvnrmls.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gt2jmayrpvx.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdgjpmzl.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2vljmjilo.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gt2pyyydsll.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gt2zjixcckt.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gt2eowuernc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2qsdfzqii.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gt2oilcqicp.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gt2jnobgkts.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gt2cvzspgye.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gt2zvcqucld.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gt2kvpkmtzk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gt2smiwujrn.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gt2ulofbxxg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfsyzbtu.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gt2mujhazaz.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2zsexcljd.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gt2zwwnemzx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gt2swnrmyus.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gt2qbtmnvac.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gt2hagpmetv.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gt2yazbhxqa.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gt2uraozmfq.html

[U29] Py：属性校验
来源：http://dali.gzhubu.top/Article/details/gt2irvieftm.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gt2slvscnqm.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gt2lzhhrqym.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnllmaor.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcopnsct.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2fnczvwqj.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gt2edsqgdzz.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gt2eaigwrol.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2vlzwhsqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2yqhycdpz.html

[U34] Py：判断编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddhnliyd.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gt2wpumqeot.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gt2jzqrqtep.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jiagoushi.top/Article/details/gt2nuauyayi.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2arepcoeo.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gt2brqidvcm.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gt2zggyayxm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsnaarpz.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gt2jiphiuqo.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gt2gvgyjfch.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gt2wybskwqu.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gt2hratirfl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaaxsmr.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2seroicqk.html


<!-- 参考信息 -->