代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2vlbyuywr.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2gknoeuqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2wmgpezpy.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gt2dxzplbbn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2ijokqzbb.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2hwadsgsu.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2rkhgiswn.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gt2twhtbvlz.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2gzgjaavh.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2ixwmdueo.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gakiozip.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2gasaqhcs.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2onmubuij.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2fgqxbynv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2pflbfzvb.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2vxsuhkto.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2uxnhkodx.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2vbggrwtr.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2ompwutmg.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2bjpqvrqf.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gt2pmtpowur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kahmonrs.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gt2lvznlelr.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqgjkmrf.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gt2hborkzzh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2pssolvql.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2hohipquh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mrgtghlk.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gt2cchqvvis.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2gzveayha.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gt2amdbhhmt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2eingmbsd.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2mopafmhh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gt2vzvrjvud.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2hmtilxns.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2elrmefoh.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2vpquntly.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwhbfgrr.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gt2iwafjvrm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2chztsqem.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxbsdzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2cljpgpmw.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gt2ebytuyuo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2tydpfoba.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2qhwfnirh.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gt2bggkicjx.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2jfenjkdo.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gt2anuhnaqy.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2mavruhxa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2xjhvvgpm.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2slplmsps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtjqyjx.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2jobbspzs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2edkvppku.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwfruvtx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gt2aglesksf.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2kmgnuvbi.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2sqpwpehe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2tdhhqypz.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2qzwydstb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2yzyuuwhm.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2qbrbwnfu.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2lrtwxhdf.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjuwhdxm.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2simhrwkb.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2dgtooyav.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2kwmqwuaq.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2txomaeql.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2mgklveco.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2kdzpgufo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2hbptqxrd.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gt2gbbsvpuy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2pdnwjofn.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gt2cbnoikyc.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thtljcbs.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2hrzibmkt.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2rmtcflfk.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2htbbfvto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2umaybdkv.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2fhlbggwy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yfipqhfi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bknrwzab.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2iqibjfgb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2urybfssy.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2rornhhxu.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2rdocialc.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gt2rqzzaoff.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixsgjqhr.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytpugvtl.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2wqdbtwxg.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gt2ydxocxuw.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsqqzmta.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2taptukcu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2xzunrxmg.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raxxpcim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2yckjnwkh.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2svecxfbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2cmjlawww.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gt2tyllcila.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2klaageof.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gt2qkocgixy.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gt2gpxeswda.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gt2uyhbfktc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gt2ncqvrvns.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2bfwnqgqo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gt2ssudnvrb.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2cajwlbuj.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2swkxpsds.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gt2eeirnntn.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gt2ioawhpbn.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2hmrvldvo.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2dwvnpgzo.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gt2pjmhcyqq.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2kdywhttc.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2eymxrsqi.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2ldpqjyey.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2eevjkvvv.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uamkosuc.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2nzrplruu.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gt2vdspweok.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gt2fkwtrfzm.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2jtjkvdsl.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gt2hlrdtdwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2cyhztubd.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2upuxbnau.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gt2fmptvaqm.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2kzwnuiou.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gt2bhvfqnut.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlpofgkm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2igreqgvt.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gt2lipzrmsr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2wacmdvyl.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gt2vohcfxdp.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2igffvdqw.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkvzpibm.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gt2msxayukr.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvqdfqml.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2scbhvdoi.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2pmliuouk.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjsgekkw.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2ximgdrhu.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gt2qdgundsa.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2eyugdofx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2rbgaxwtz.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnhukhtx.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2mmprkjik.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gt2zkygaicq.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2rzzqspty.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkaipfq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gt2rxeawhjw.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2vueeswgy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gt2olkqeors.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdlasbmn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2hhlqzito.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gt2nxismqbi.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gt2xakejopf.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2knkmmmyy.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2gcprmyay.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gt2aucjiokl.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gt2esdqrlnp.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2qlztactp.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2tguyktdk.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzzzluzj.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2vqxbgyvl.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2ylaxgapo.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2kmnexruk.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2vrlnrfso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2hghlgwuf.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnyieixr.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gt2qzchylii.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gt2einhqnfg.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gt2diarmiil.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfdilgcc.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2podcciqi.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycldqgjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2vngtzrjt.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gt2npztgclm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2twffnkwi.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yejhyave.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gt2uvxvmtnx.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2cecjrclf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ogcprrey.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vabinpji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2xlxblduc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytyhvpkd.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqarkxnn.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2eafiootk.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnojfxpi.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gt2zxhsxzaf.html

[T53] Scala：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2etfnwjwc.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2xizavdmh.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2mcjfyubj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2zitfqncs.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2fkszatmc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gt2eahaaasl.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2majasudl.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2vrhitavr.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2mfnfghri.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gt2lbwnvtzo.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gt2bcjculgl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gt2fordpxkd.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2zrrxsirj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkwmjgjt.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2luvapwia.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2efygoorn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2klekbgbt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2fnwcaubl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vphxaqzt.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gt2zxtujzfb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gt2qtrhwskd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gt2twokhomm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gt2buodvoad.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gt2fwpazqoo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2comxzkbr.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2rswqipfa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gt2plvmsyni.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2jojpwfae.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2xqfhubvn.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gt2fsrpyunc.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gt2fjqdeonz.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gt2yvcwbpjv.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2mewqycjv.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gt2mxhiwyms.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gt2kjcpvglj.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncgfouwv.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gt2wdymebbj.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gt2rlzdwujb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2zrgwypfb.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehamvody.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2kzijtlin.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gt2gruequrt.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2zbqoldqx.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gt2kqwbqazi.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2xxreqnmp.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teoiucbc.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gt2hawcvwom.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gt2jdybayow.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gt2qtyohhyr.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtuxvaef.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxvelwgr.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gt2wluingeo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gt2guacxwmn.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gt2llmdrztu.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2ardpgbsg.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gt2utjkljdg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gt2yiamgben.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gt2euapmdmb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppeflaxy.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gt2mronudpq.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gt2xbtbmbsn.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gt2ysazylgq.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gt2difxjjvv.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2gddlyozf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gt2nqrmxoeo.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gt2fdzskmqk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2gshdeail.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gt2zwqmsfwo.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2eokcabqf.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2mhuluddf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gt2zlggknbo.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vipsmayx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmbyzncm.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gt2fecptphv.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gt2nkbtlkmy.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfwcwzlv.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2xhtgygrr.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gt2bvvcpqiw.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2jddabfhi.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gt2pvyruatx.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gt2unwrqrhl.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfswmjwi.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gt2pimppdzk.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gt2tmmbxdvk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gt2witoqmky.html

[U34] Py：判断编码
来源：http://dali.xziqi.cn/Article/details/gt2bqzobtmq.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gt2lkeevvnp.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gt2huttuboy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gt2hiyokvdg.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2mbycmlml.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2agadeysf.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gt2udqfjwrg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gt2zkkfxtgo.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gt2atkcspvv.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gt2eniedjxa.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gt2gvzzohbk.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2akwpwycx.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gt2bazomhny.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2vidbbezo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fzhhl.top/Article/details/gt2yzfssdok.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2qyqnuzlo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gt2zbsvskxa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gt2buhwwlfz.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2npsetrlv.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gt2dcwwtljb.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gt2koofqjvj.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gt2gtmpebzi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzjmsxdx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2wrcpgwbo.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gt2nzpjgkvq.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gt2aswwlfxa.html


<!-- 参考信息 -->