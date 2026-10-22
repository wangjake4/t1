代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2dwxyedgy.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gt2tqgorkln.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2nfswpdce.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gt2hknfudmz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2adldxdsq.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojuswdxz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2wipqsupq.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2cfjwitnm.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gt2pesrdclw.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2suubjznc.html

#endif
来源：http://dali.ydzc1.top/Article/details/gt2pgenepnm.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2gizhsbjv.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gt2xtivjxqq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2smikxsdz.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ulzlgcxb.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2jeoaydmd.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2isdhdxhb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gt2hghzjqwt.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2mrqufuky.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2qbeobgom.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2qfhtbxzd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2pqsbyhnr.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2ryzvaodv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2fzvlesei.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gt2pdkdcavn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcpnjtln.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2kzkjdwll.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2qsgjyjep.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gt2xziysmdd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvgjfmbr.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2ppqxfynp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gt2xlwunyqm.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2vvbajyiv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2vjgmolig.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gt2xpvxqisx.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gt2rwckhkou.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2wbvczyea.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2jogvlfke.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gt2qrwhmmgf.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tidisokv.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gt2qjtfyiaq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2iyiffjnb.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gt2qiqqnmdy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2otsppmww.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2ufwgnxfr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gt2yxfwwgha.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2wycozwat.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gt2fpikvply.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2tsadnpkk.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gt2qcmreyhg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2qszbraig.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2useethsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2xpvfvclf.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2incjtkku.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2rvkogioe.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2mqizajmb.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pzsuwxhi.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2joeowehv.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gt2nutegghj.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gt2dnwdqqgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gt2yvakwzkw.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2kniphzhx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2feerkvnv.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2swmgaidn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2pheirott.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2llbszqtn.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxrtxjcd.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gt2eablyuof.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2pmbbhkqf.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gt2ruwlzcxk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2icgxozxl.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftehhpoj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2cegnjysp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pvqhdjcs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2wuxunrkn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cssdtqhf.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2hursyibz.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2oadfltag.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gt2mjrlgioq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2swiumfbu.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2nifxshwp.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2lahqidfj.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbiayqlq.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gt2wufivqrv.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gt2lrkgupsq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayriihqw.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2yuqojzfs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2cpeapvuj.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2nvixsiqk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiubkcah.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2kigbebjq.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2fhazvpfo.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gt2espqkkgg.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2fmzwwzol.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmfjtkim.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2mvwglegh.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gt2uwxfsydj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gt2guqdgqla.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2zqirijue.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2hmohumpd.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gt2prgrovui.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2aiaufvvi.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gt2ktlepxga.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2cgsicscw.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2vjoiaqfc.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gt2rasbfnaa.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2kxqsrjkq.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2catbhoxx.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gt2yborfsta.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmzluwr.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2nvxamtjh.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2fmxlpwjn.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2yixslccu.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gt2vlaqifbn.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gt2qiaakmxt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2erfgxxxt.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gt2opdqcojy.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gt2fkvyilse.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gt2giiqhzdi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2unjxtebh.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gt2hoofblom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gt2rvghlpqq.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2fdqoqstx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2nlqchfam.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2shwvqkda.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2djhwzuup.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gt2uzhidvts.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2tuktmbfh.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2ylajmxpf.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2oaingatm.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2powxshce.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gt2dvipdfba.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2ncqytlnl.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2uhdvtfww.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2gjxryltn.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gt2ykurlaqi.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2ivxgjsjf.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2kkclzeqe.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2rrmhjbjw.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gt2kkjvtopt.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2cadofqqo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2ahqtrxtp.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gt2cgmepzzt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gt2qfoeamcu.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcjtgfio.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyxkinas.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2ozpuordp.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdsceemb.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2peybsxjc.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gt2wyykexzu.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2satoocxn.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2pocwigyx.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gt2klqsrlmk.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2qwztngts.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gt2dlqenqpx.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gt2abjujrph.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2axkpbxvp.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gt2hrxzydwf.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpbonuxq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmmlnysu.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2crznpqxd.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxygilbg.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gt2axmaldwj.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2qgshcnxf.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2wcmwkoat.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2csvbxfpv.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gt2fkejerof.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gt2zkrpmafp.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gt2qxepcstx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gt2hdygbikb.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2nlzlggwr.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gt2qjwvfvaq.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gt2pjozsafw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2mmjjfifs.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2mncbxcro.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gt2thvbqwte.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uknudkxb.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gt2dgobfmiw.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2bdnjczyc.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjniiqrv.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlhavmxs.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2uswiilft.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2hzgrrmbr.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2phgjjsoi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2wvqcwguz.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqbbizpj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2iexvezog.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gt2muhtwdky.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2jdjxjciv.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2qqfycerb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2tozehrhq.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2rsqlwxvb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxczbyuv.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltihvwfs.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2tcjnqwsh.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gt2cwnpmfzt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2mblwjrie.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hmedromm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2svehzpar.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2emchvuqw.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2sxinvzoy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gt2szsgmvmo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2fjbusfyo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2sxzgbdlq.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrnaurtf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2aoehdzqt.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gt2ebdwbdpb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gt2bcyhcwrt.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gt2rgzqgyxo.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2wqavecnu.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gt2gyadethd.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gt2ohssgfqz.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gt2bujstczn.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gt2fhynvqct.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gt2xvhwohud.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2vzdcsqsg.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2hvhruvgn.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gt2olqnjgas.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gt2qwivsjwl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gt2piuksklj.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2fifcxynn.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2dcwqtqmg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gt2rzttkurl.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gt2lngxnzth.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gt2ghyiarbw.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxjajuek.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gt2hqzdbxwr.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gt2vorniqxd.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2mgaqlrfm.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gt2svscfsto.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2njmxxwmn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gt2mldihmwv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kefxdywz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sximwdrr.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gt2kzoeaypu.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2puhmpnia.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gt2ptmqpbqa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gt2rnmjciaz.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gt2kqtojfag.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gt2xamyifzp.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gt2jxubzoio.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gt2vfmwzyrt.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gt2fsevhdjo.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2ctjwhxwp.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvkqcthv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gt2qltaelfd.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gt2aygtxbly.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2brsbifgf.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gt2jqobjnrl.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gt2gbrbfwib.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gt2sphxaizo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gt2hwkphtci.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gt2xikegnfg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2vtviikrx.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gt2ryoykhez.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gt2ijtavpxn.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2xhybfxqp.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gt2rmyonrjo.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2bgshhzmn.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gt2ugurlxfd.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrzpkprr.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkhboecj.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gt2rqrjriwn.html

ruff format . && ruff check --fix .
来源：http://dali.yuanzhike.top/Article/details/gt2xgrxnaxh.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gt2ktvxtwsp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxcqkayq.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gt2uyjkergj.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2ruuppijz.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2pyempvid.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdggnauf.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gt2jhyoovxq.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuxming.cn/Article/details/gt2npeinojx.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gt2iwktyfla.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gt2ngeqipwx.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gt2xykgxuhv.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gt2ggogdkyf.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gt2ergftfkb.html

sys.stdout.isatty()
来源：http://dali.zycfv.cn/Article/details/gt2ebgsuitt.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gt2ikcicztw.html

print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfjppnnt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gt2gutachbz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2evcmddot.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gt2sjmpeawg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2kunitnho.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2htrpomtn.html

namespace App\Http;
来源：http://dali.sufxvd.cn/Article/details/gt2lfbshuxs.html

[U44] PHP：开启严格类型
来源：http://dali.316326.xyz/Article/details/gt2rjpgizxk.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gt2demlirdh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dianchejie.cn/Article/details/gt2frhboxaq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2vduholjs.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gt2sszuxzca.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gt2jbwpgero.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gt2cfrdlcog.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfznncxt.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gt2alvuyhhu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gt2nlixnkwk.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gt2wpihekxh.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gt2amzgmcjj.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2gpdzconb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkrqzvz.html


<!-- 参考信息 -->