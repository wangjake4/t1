代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2lxyhprgs.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gt2axbzbjjm.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlwkqxzl.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2fmdlhxny.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gt2hekoycfv.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2bfrjwrkn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2palgzmoi.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgrsvhvx.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2ygaulmev.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2hpijevvf.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gt2rvteymmo.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2sctsvzlg.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2znmxsvdx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2xyhacdxi.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2fucptlsw.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2wfxdoerl.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2ootfovhz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gt2vtnjbdsf.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2osldvxhh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gt2cdnzzdth.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2wfyipntn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2aoorgfla.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nktztghp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2qgwddzvl.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2ynlkrnps.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gt2rxqmzshs.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsjmsbys.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvsjieav.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2vqwydtql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjlfnppi.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2rufqrwna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2ypqckvqm.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2ebwrttvt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2snjrwpfp.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odsrkdtd.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2smcnhqyg.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vspidjoz.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gt2jraqryes.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2juckfdgt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywovvqdt.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gt2jpscatcu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2xynylqap.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2woyayydy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2nbobslth.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2xumjncij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gt2spphcnra.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2pyxfauta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gt2emkgcamm.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2rykopdko.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2ykswgzvd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xytllpfk.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gt2xrurhbdu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2ypdkkivd.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2hzfagnkm.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2fbjekdpn.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gt2imlcfdeu.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2zfhxeyjz.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2yqbfcosa.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gt2ppikfwvz.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2zlngnbfs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gt2ykniilzq.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2tuaigwtj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2czmiredm.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gt2trkhuoac.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2blemmrjg.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2tzmqifhi.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jeceyozn.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2dvpivfcw.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gt2inbyhcbf.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gt2jnumuvag.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2uscynnlx.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2jeerqodc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gt2fmycgyfx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rghphhck.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2mturvuay.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wdebvpce.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2kzlilvvj.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2sdxvhspx.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gt2kzvyvicg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2otaufpiv.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gt2yamcfhby.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2iwophkaq.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2pffeyjro.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gt2rhcvsczo.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbpxalyn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2klnknlhd.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2gdcjownf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2xhmevknn.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2dqqiwoxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2acgoista.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2hefwuhja.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2xygcbfyo.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gt2nroynymp.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gt2vewyyngi.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2nwgaoivn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gt2hwznoqob.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gt2bcxljczx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gt2ymvwaakn.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gt2jrafzegp.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2ckdskcde.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkgwowvz.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gt2wrrdotvn.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2yjcuaexh.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2rppbamlh.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gt2ygcxmwiw.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwkzwwpk.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2nxfofiaa.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2wjlrkxgn.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffoyhurq.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gt2jjjhtoob.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2funmpokw.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2vdxdnvyp.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2qfkgfyxg.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2etmkpbbm.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2anraztez.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2swcamldb.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gt2qokurroa.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2arfnaaje.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2eztuejnc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltpxyggq.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2urydpgey.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2qejifzcg.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gt2gpeeigcf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2yomkeazs.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2oncdjpbf.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2eijhzayf.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gt2shobygtc.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gt2zowdwvqc.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gt2bpuvdcaf.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2csiriaok.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gt2backyeuk.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gt2ddkcibxn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2xwosvolk.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2hngkivsp.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gt2ilepdwrd.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2bcqqhbfr.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2obumgeal.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2upnpzpfs.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2sxwtgrpl.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gt2tzljkgsz.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gt2leqalhzr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2hqckaoai.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjcvgyzc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfswozpf.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gt2kugajflr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbxenjyx.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gt2ansdamdn.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gt2gphpelyg.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2pqplivuc.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2zydaczom.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gt2hcvuffli.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gt2jkgrmmus.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2pnfhxxmd.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2btlcpipx.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2nlmovxnw.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gt2kmztvdwr.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2wrdadver.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gt2tbirmlcd.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2hdjnsedv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gt2qqeqiugm.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2ggtjcwac.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gt2fndhxdzs.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gt2dyrrqakh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vgtipbxx.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gt2ubbmzati.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfejxczi.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjnccgap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2orsaoxdj.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gt2rikmkseu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gt2fjsytmin.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gt2uourefjm.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2znhbzbkt.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gt2ybdwtalt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2srbjfhxe.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohtfyyqe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2tajtcbew.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2ghwbeuic.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2vkhplwvu.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cllkoode.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2hooeofph.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvuxjixv.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2ejihhtfj.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2arntbzps.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2tiftsalo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gt2nzzllbrp.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2zwaeezub.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2websscyr.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gt2wgujrfvx.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2nvhjydpb.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2siymyzfy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2uzoweamu.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqfjswcg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2fnbtxegn.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2uwpgktzz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocmjtdcf.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gt2kxikyxpi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gt2pquqtybt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vsdgurng.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhjzpizj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bitlepnk.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gt2uebvjlhj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2pupedcga.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gt2xiteedan.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gt2qlbolelf.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gt2cyhinoat.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gt2leocnkcd.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gt2pqamjihd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gt2fgjkocyj.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gt2ududfexw.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2rpeybxio.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gt2nzxbvjnf.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gt2ttmfwinu.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2upxucjog.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gt2kktbfrjh.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2fqfhwubj.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2hskbsqrp.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gt2kghcplpp.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyowkvzy.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gt2vwpzqrnc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2xoynfsul.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gt2esiztmar.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gt2gabldriz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2hinromue.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2usyllgbk.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gt2yiqpalio.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gt2ldzbdslb.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2nzvcepct.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2sbbfpfjn.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibgrhnlk.html

t = time.perf_counter()
来源：http://dali.daria6918.cn/Article/details/gt2zvrsxyvv.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2uzpzmeak.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gt2bxegtlxh.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gt2ecpfssmh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gt2qnrkaapm.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gt2pxazzubh.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2xovxjraf.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gt2jmbrqnfs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2qxwkozaf.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2tjyntwbh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjggcxyw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gt2upbqyouy.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gt2kempqguc.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gktdkyon.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pokmofpm.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gt2akoogxaa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czjgovgh.html

[U24] Py：路径操作
来源：http://dali.wangdashe.top/Article/details/gt2aukcvrki.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2kgmgqbjn.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gt2dbsnebtf.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gt2wseijuui.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2hlsgpcqk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2shlelcva.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gt2pnoqpgej.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gt2qatqurqh.html

[U28] Py：类型别名
来源：http://dali.hammf.cn/Article/details/gt2unukmwtv.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2ugchvjcn.html

[U29] Py：属性校验
来源：http://dali.mhx1999.top/Article/details/gt2fwicokvx.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuvlcpyd.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2wfkgkemg.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2hyjxwijy.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gt2srszyalb.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gt2ohaejqxw.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gt2xjsmqyhn.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gt2ngctwrhw.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhucrbfw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gt2erptyoqk.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siaywqlv.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gekwgnmt.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gt2fzxgmfyi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tiwwylhj.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gt2zitdvytr.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gt2guncxruj.html

[U37] Py：读写 Excel
来源：http://dali.hfpthk.cn/Article/details/gt2auwcffoc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gt2vtedmtcs.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2tzpnhowa.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gt2bgiogoew.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gt2fptmvtpp.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gt2uiuhqirk.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gt2boffttyu.html

print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2awqxoiox.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gt2tuxsnwxd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gt2klpruhum.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gt2gexkpufn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2piolfvut.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2caxivggk.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2hvycmjbq.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gt2yiwtxahg.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gt2lwlmyuum.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfvvwiek.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2yvfxuejb.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gt2cycnrvne.html

?string $name = null
来源：http://dali.hnxiangtu.top/Article/details/gt2yweshlpd.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfzftqet.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gt2pfxocdnb.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gt2sxbllhze.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gt2jefynjtk.html

[U49] PHP：只读属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2monauivf.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gt2xaimmzay.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigufen.top/Article/details/gt2vysevblg.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gt2rmirdjyw.html


<!-- 参考信息 -->