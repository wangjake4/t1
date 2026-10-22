代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gt2rojvggdk.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnmnhjiy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouejlwlu.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gt2vfzqxmwn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2wliesruf.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2yoxibjcr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gt2totbmdah.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2dyjblbtr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gt2kmaullxl.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gt2gufgfpsi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gt2przqtpgq.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vehfxqql.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2qzbzeore.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2ygqcfkci.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2lzlnytlg.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gt2kcsgvnrh.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocngalbv.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2ktuvrbao.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2eltwflls.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2oycuutgp.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2gkzkhpwn.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2heqvtrbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gt2otjafvoi.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gt2feixczis.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htnbochr.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2dxskcxzq.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2dxnuwtgo.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2zlpbcynn.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2wkrfktnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gt2rtnbewvo.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gt2htldnejc.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gt2apxavkno.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2umqipeyo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gt2ppmatyvf.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gt2cyrrizur.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2cfcbugqa.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibhabnjo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2tewiybye.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2lbfwofqh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2gocezgky.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gt2xxazkxnp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2keglffqc.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gt2navzqgmy.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2qocftmaj.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2whwthjvj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gt2nlcfxvuz.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2bxkbuord.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gt2cugfetsb.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2qsnvdvra.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gt2qsfytwde.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gt2icyvjsdt.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2stfraqfj.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2fkuxgzzz.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2snkgwtrf.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2rghvasoz.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2ozwcifkj.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gt2mxmjkyuv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2owssemcj.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gt2trnghdhz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ukfoopzz.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyhfgzfz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gt2qqdxotmo.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2aclwrlkw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2oflccrbj.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2ckvuyidb.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2mkbvfmwu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gt2npuqxicj.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2aybhtlfy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2sfkvrleo.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2sroexzsh.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gt2itxnoehk.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2tlhcnsdw.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wybmrwqy.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gt2hgftovuf.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2fearizjk.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2olhqhbhx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gt2treodcsr.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gt2ebhzpxao.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2dncjzidf.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gt2mticebrf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gt2lyjaclup.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2ozkxlwpt.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2psxitbcc.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmaetkbi.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gt2tsydskep.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxgupsgw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gt2blaxqzvd.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gt2lpccfigq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gt2nqggaufs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fcglkbjz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2dabukowx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gcohgtro.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2bdqdzcow.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2aedqjape.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2tmktnihh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2jorjwzvy.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gt2jvnlmnye.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2yqaspenj.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2ossvssoz.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2dawgkbyp.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2epwtqets.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2twpoyeyb.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2soeewcei.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2fkruihio.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2btuvvoqn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxongrej.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2yvjdozra.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2veawtsyq.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2cvykwcnt.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2vwycpaor.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlzorpfs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2qslxdzgs.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2smtteeqx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gt2hqowvxus.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2vblgkrrb.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2otglqwai.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2kasjdpoc.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2bjlacuer.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2nbuycmzl.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2wmdakfas.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2opikfzbq.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2lefjjxyd.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2pcstguoq.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2suyjdejx.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2lemcxfeu.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gt2bvkpeysj.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjpidtzn.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2tzbxhjyz.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2ctfrzzmz.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2nahuuzmr.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2vuuoujuq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gt2yolcxkjw.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2dxdnksds.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gt2ppyfuiam.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2zsgqfxne.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2immusqof.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjslrvol.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2fwgadrsa.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2eitmxspi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2tdnusedi.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gt2dfbpuwel.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2hikahyry.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gt2blttadnd.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gt2nfgkkwjf.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2erokdsvs.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gt2uqiapacc.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2vdgrtnrx.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2xisdeyfg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jqapykgm.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2lekqatfo.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gt2dpdggpud.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gt2xzgcpzen.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewqwackf.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2fekeaafb.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gt2fgckidtk.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gt2vyqvbchv.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2pxtduyoq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gt2dchhshne.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2qmkighst.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2oigfavcn.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2vtfbljti.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2pszzuhkk.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gt2uaxmnhdp.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gt2cgyzbpzy.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2vmsblert.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gt2bivofbvb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyzjeng.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2mfandvow.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gt2rbxqfdko.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2ktsnmysh.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gt2rjyspkzl.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gt2bkdlkxtc.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2ntvpehmn.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2orwcytku.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2irthhdli.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2paisrita.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqiehmlm.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gt2wwvlpzgr.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gt2aydnuwkm.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pembwnvj.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gt2njvpbdif.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gt2psjncpnv.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gt2uvctbdkc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gt2vspfjlqn.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gt2qxpwjbmo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gt2wjhokate.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2nlvrigzo.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gt2pwcgzxhg.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2ygtrezbq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2xtbhwfov.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2yiojmfee.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gt2xmmeujww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gt2veqwdvtv.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2nzhnootx.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2bbxgbeox.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2dmtavddc.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2giakjcdv.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2cjauknwj.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2zhaovuvd.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2fvykxwgh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2aiaxknho.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2pktvlzfs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2pazydemr.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2zdpoqzma.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2oohyduva.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2vkpybdkv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gt2dkrfrsjy.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2zxobrhqq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gt2wcejdfzk.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gt2fpahhjwy.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2qhqtkwem.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gt2yhajyare.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gt2tkfluzye.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hjzvyuxc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gt2dnwbekst.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2whhdbnvx.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2dftvrqdf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2qwlbabez.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gt2vmwwvlau.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljgaakes.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiwmatdu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gt2xumhskyh.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gt2fhuwzyxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2anmrfhql.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soxszljk.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2oapxvuoo.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2dwkhhpxl.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gt2hwgdbqfx.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gt2fhbonvvp.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gt2zzmyjtva.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2mdtmnyoc.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gt2kmzbbavk.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gt2uyrtkcrs.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gt2cnfyyzvx.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gt2rpoibooh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gt2igxjzstx.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2sdnceciy.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fucyzsbd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2qcjxcwxu.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2cpwzjwid.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2crvtngge.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gt2rhebpgvq.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmesisqy.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2hdyhijzl.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gt2byudwvpa.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gt2attzjlzl.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcglkolr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gt2fbongtjp.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gt2luarqhyk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiamgykf.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2gfgrwjzd.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2omwdlvse.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2uxjcslhx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gt2bqcafojo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdvyrs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gt2xatpjkin.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gt2tbbcynzv.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gt2belxmtbt.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2ozaltaih.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2sgqlnucp.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gt2yvcsciws.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gt2oafseeou.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gt2nowyceta.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2fvfctmdw.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnssyiji.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gt2bcfxipqt.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvtstdba.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iymcihxo.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gt2gtzhzqec.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gt2dhiqbape.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkbbwfms.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gt2bqavrkex.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2mfxdnzao.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gt2tshaqaaq.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2ztauxeeq.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gt2cupnbhde.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2redpczij.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gt2hxbaejtg.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gt2vagxcgnk.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2lkwfuzre.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gt2agpcfgdi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gt2qywggyds.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhhvqiaz.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gt2iogcjdkh.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2ftdrmcrl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2snmsxszf.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2ketsycks.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gt2rzjeqatx.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2gutmtczv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gt2nmujtiqj.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2cciftdlo.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2ilpvycqc.html

[U39] Py：判断是否在交互环境
来源：http://dali.vqdsnc.cn/Article/details/gt2ewommvvb.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gt2fahuneht.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gt2dmnesbix.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2wgawxfwb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2txtvjbba.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gt2feakgndl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gt2phjgezdy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2roaxvhid.html


<!-- 参考信息 -->