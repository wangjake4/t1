代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2crwxsnhb.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2pdqfpjbe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2iaeqtvxt.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gt2uomeozcd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2ojqrazpi.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gt2fyblpecs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usdztnmm.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2xlqiwhmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2tunlzext.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2mfzhxhho.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2fgpahuvo.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2agijijws.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2dbvpsine.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2akdpljwr.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2fjczabms.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgtkjvrf.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gt2gylwcdvo.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2zzroegvp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2zuebdkcv.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2ogwduuvi.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2rarmtbuy.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gt2wuonnvck.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gt2dmkdrocw.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2shsoldct.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gt2ppwysgdl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjizjjgf.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gt2vaysadmf.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2muyezwyy.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2nphsnfpb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gt2ghlngwrr.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gt2dbcokvsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2wvaotkvo.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2chtlovjl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2xtkvebmn.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gt2nasqvhop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2mablmfxu.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gt2rwsekeuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecmtjxmp.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2ubvjvbwm.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2kwtixesc.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2otomnbpc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlzekmrz.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2scnvowdr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gt2etllmnzm.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2niphnjuf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyspldiw.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2matdtenc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gt2bnozvcna.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2tfwnqgkp.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2jkbarhkk.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhpurotq.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gt2fjcahbks.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2tusgrqtl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gt2vwwdynnz.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2ofszvvdm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2fwnesxlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2zdxqjwyh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2nypdfsgs.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2igfofctp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gt2beppclyk.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2xobhsiaw.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gt2ysiskwdl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2orrubeba.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2cifuqhrz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2ojfvqvag.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shuryzhh.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2cyajlyze.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2zdtxjjgy.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2gceokjcc.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mefckomp.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gt2saikdqlr.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2ooxoqemb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gt2tgcrbjan.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2rleqgorf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2btuxyfhz.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2lbmtcuoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2byaewjpa.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2iqepisqe.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gt2cyxjjjeu.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2xfbyczil.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2vyxbzdei.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gt2iiydadue.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2kjtgvjgb.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2czubstur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2mlihwipt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qgdzgzzm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfogrxxc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkxalrmz.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2vsnifkip.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vusemhju.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2rclyones.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gt2rsjeqtgk.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmxzcboq.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2xygvepop.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2fmjsdcjm.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2fvstmoda.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2qljltejv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2duprlyov.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2zolbabjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2amqabhjf.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2xxdodesq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2zccagbnu.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2wgruzxeh.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2zdpqtomb.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2afeeddlq.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2bsrotmhu.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2etlaqupr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2oolvozly.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2jfyybckh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2wjgthwvf.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2uszqcvcj.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2jidhfswm.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2yhtiuzqa.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gt2dkrvtmqi.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwtargqk.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2vehvfgec.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqlhmgrl.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2iyopmlow.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2vxohcylx.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2gvdrjrbp.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2evpmbnts.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2ooymtuvf.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2siufqjhe.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gt2omrewpzq.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2zmltthah.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gt2xwxvqvwz.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2tzkihxrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gt2pridssyx.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2utkjlqmy.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gt2hoeixtbv.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gt2jgxqtvod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2dppesvwg.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2knfsmndp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2xyjjtfdj.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2lazfddwh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2ulzmwjlp.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gt2kparqgbp.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gt2lekkqgzi.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gt2uqkqkjxj.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2bmjxwazz.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2ogcmhaxb.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvzdtpda.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gt2lrmlcofb.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2bhhzekhz.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gt2klxstbzj.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gt2ftzoopnd.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2goxexmri.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gt2ycserfnu.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2pynxqibt.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2ztgbzzsy.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gt2pctmvnfq.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwjxqihj.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gt2wulamexe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfyngljg.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gt2vbfeawmh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2nqaboosu.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2kfxlnxwn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2eunmujpz.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2lycpxvtj.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gt2luuwzptn.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2lumtvvts.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2nhudswdz.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gt2tgfjhcuh.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gt2dsjipghq.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2pstbkeku.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gt2rzxsqjfb.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gt2nsnpjygw.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2hboxefbh.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2yrdqpzvu.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gt2gqqbseji.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2ajbgqbml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2liitmsib.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2ditncadl.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gt2wesmjgvx.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2mkrygsnf.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dtvkdqdk.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gt2eecbbftd.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2pcfqxstm.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujjfvsul.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gt2azegxpqt.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gt2fubntkas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2losjrjoe.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gt2pooupsvu.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2ejkkehkz.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gt2xowgwszi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2gmgbwvlb.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2nyggxgix.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gt2poqatrsh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzelrtek.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2ppfilygy.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtlnxxka.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2dshcdrij.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gt2ucywfiki.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2gmcacyfe.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfagbzcy.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cytqusax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpxqegzb.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2znfahmqy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2pitxfqtm.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gt2rhvcylwt.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2rkqizqrz.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2qnaclnxb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaojaplx.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2lmpxxpqu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2yoguxnyo.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2herenccd.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2dblittla.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2dbqgeamc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gt2pybaydxj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2sibxlgof.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gt2qfgrtqrg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2vaytrdrf.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2uctteqtl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gt2wnxcvmmc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gt2mbxewqdz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibbnndbq.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2iequevpu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sstffyko.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2gadhygwm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gt2logitaxw.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmthwqpk.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2iojxpluy.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gt2fvpcugro.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrbccutp.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gt2zpxfivst.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2rmtcdzui.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2gzktskxo.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gt2zfhsxdek.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gt2qhybdenx.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gt2hkdavwvp.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gt2tpowudtc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gt2tuwzzxiy.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2layeieeb.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gt2zcmysblt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2yzjbctha.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2mviywbmz.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gt2syipsaxy.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2nlikvepq.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muhahtln.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2dkvfyqgz.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gt2omunupqn.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gt2abgfdrlq.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gt2iyeiwkwc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2eudsdrer.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gt2qnfbdyyx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujzndygb.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gt2jriuxxyw.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxdtdohe.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2scapwczu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gt2xvzbtucx.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gt2nqbdbcph.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gt2jppbivyo.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gt2trlffqzn.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gt2yipnbtyq.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gt2cfsnddko.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gt2mztwaaev.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2fnxnkwzd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gt2hujuklqy.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gt2nsjzblmy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdexxrse.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gt2pqwhyovx.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gt2pmwfdlci.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gt2tecxbksl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gt2iemrcwkm.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gt2zqiqxywh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gt2esxpjywp.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gt2gdjsivpb.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gt2rhrqzywe.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2mncrsevg.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2yvsbfmnr.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2vkobjnww.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gt2rznqdqoe.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2royfpfkt.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gt2iqgkjxzs.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2ubzpbisf.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gt2jpmwmgax.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhabxnjd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2hmemrcua.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gt2rvmcsete.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndenrqof.html

[U35] Py：发送邮件
来源：http://dali.hfpthk.cn/Article/details/gt2fqinetbj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gt2bsrxuwbu.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gt2uefgabzp.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gt2odrpgupy.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gt2erfbijhs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfvmakhr.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gt2sggrzqko.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gt2qkdsgztd.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gt2cznlupmp.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2csyrhmoy.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gt2qghnnuab.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2vbxkfbze.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fengsongda.top/Article/details/gt2xdbapnvj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gt2gbtatpox.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gt2noknanfo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gt2ydiixgxt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2seghaugh.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2oifajfqn.html

[U44] PHP：开启严格类型
来源：http://dali.guowangkeji.top/Article/details/gt2pckoxyfm.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gt2nqimbhje.html


<!-- 参考信息 -->