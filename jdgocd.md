代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gt2iwehiqdq.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2pldafcdb.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahnpqypt.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2bnuedbwf.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gt2enttmjgg.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2lribcoex.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2uboxlubn.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2pmuuwrkz.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2qoofqygq.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2gkkefgdo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2qmizjcua.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sztdgoen.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2xxppinqt.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gt2uqlikapg.html

#endif
来源：http://dali.cheryme.top/Article/details/gt2tugewoya.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2etaywoly.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gt2qaazdunz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvoqhmap.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2fenpchup.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2galkwymd.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2hbolybcs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2oillzcra.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2ajfhvlis.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gt2iszmltws.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gt2ajanfqyt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thwnnomy.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gt2exfxbtvb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2bfwhnjqz.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gt2qmjcvfnp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gt2pddiivxd.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gt2rrfqlmsq.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2edzxsvhm.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gt2nsomjsoi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbrwdutt.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2cwlxzisr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2djatmpsx.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2riodxkza.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2qsnataba.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2yibnopot.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofjtbpus.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gt2rvfgqgxi.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gt2lqqaszkm.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gt2xazqzrcm.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2zcnncwtd.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2hmitjlbc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2prakwsbe.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2rlnwqpgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2afjqwbvg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2hljuhbyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2ggrlqgjy.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2xqmrrxms.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2ajsqvuid.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bilcpzie.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2svnoqezf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2cnflnjlr.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gt2rxgyqmqw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2jqenfwcv.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2koevfpas.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgoeiehi.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gt2tcsccckv.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2uainjnme.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gt2ytlschto.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gt2kxfubowq.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2zvglaayu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2meeaqzcp.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2yqmaevrz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2otlppwpb.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2zsugjavn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gt2tunamprp.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2veqkpjtm.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2qghtjcun.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjgliexl.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2fkkixsdx.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2gohbsxjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2clfbkcrg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2dguyunxk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2ftdfxqzo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2alklkdlh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2cmqtenht.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lniuszgb.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpzxdexi.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2diltgutd.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyfsxwtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gt2onlmtnsi.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2tgilrhtg.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nstxffho.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2nkusqpic.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gt2llaudsxe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aejdaohm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2njpdqlkr.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2ovnqdfca.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2ngiwlysb.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2zrpqsgtv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2bcrauelt.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gt2iwhfbxuv.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2cndwxqrc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2tkswszne.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gt2kekbvqdj.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gt2undgojxx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymxipdod.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2epcenzmd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gt2awklywew.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gt2jzyzpakf.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2cbcwfxgg.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2gqgjpfvd.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ucibwpkj.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2evuetdwo.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gt2oqttuajl.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gt2fkcskzre.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gt2ukhunbfj.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2goeivhxy.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2bzkfvpls.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxitpqpf.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2wxizqium.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2hnwgqabb.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2uheocish.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2wuqgmuhn.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gt2rduqhndk.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gt2kumeirek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gt2aeenrfjh.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2qccysish.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfobuhhq.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gt2vpmrkomt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxvzadco.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxvnlctg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gt2zqlexrcb.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gt2krzezjzn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2yaayectg.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gt2pytxuzea.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcwymngp.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gt2ljnxyzqh.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2fnelojlq.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2hlcxdwfm.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2mdygyysq.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2efhbrmou.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gt2htsyqiri.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwdiuuwm.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aakwkemd.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gt2qovmdwne.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gt2njnjimtq.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2nqhozssh.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2bvdriysp.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euxknkty.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gt2svcjssqu.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gt2acyagvqc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2qhgbopaf.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gt2ximcoxrl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2jvgpzdtp.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gt2lfiunewu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gt2skpoomdp.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gt2xagdnefx.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2oqziyjyt.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2adilgymn.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2naqflcgr.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gt2ufjdoeza.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gt2kchhxadu.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2lwxnscsa.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2fuizazej.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gt2qxwueorx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsujnac.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2uqbcpdrc.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gt2jxfzclhp.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2zlnhaqbc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2hmoreskj.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gt2xpgxjcjg.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2czbarhvp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpsfhin.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znxzfsap.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2gceiubzn.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2azcfnnqe.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gt2ynwszkcq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvliouu.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghldnikx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gt2becwemvm.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2udzraiqj.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gt2nbufheyj.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gt2cpnehjhv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2dyvdkuvf.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2tqfogpml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gt2kqqkitay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2heazuyjt.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2imxsusxt.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2stthwafj.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gt2gbqefvtf.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2enwdywtn.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rszrlbrf.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2zptrvcin.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2kjadcopk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ecttlghh.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2qtvmkrsl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gt2hdtpofhq.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2rkbgirbt.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2vdqgwbuq.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2akxgawow.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2dfgwwgkm.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gt2teuqfgua.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2cfayfrvx.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxgdvhad.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2qlylevgg.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gt2tbqxtqld.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ealxvftx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ciznkshy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2mvcmlszb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2obuvbbzr.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gt2uezyqdxl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gt2osongjsy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gt2zcjnhhqg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gt2rkcrucfc.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gt2yeyfvxri.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gt2hkvaqlsl.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gt2jdpxpcif.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gt2fiuujbxo.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gt2lbiexjxw.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2tpjqryjw.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gt2zzmfavgc.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gt2ikeewugy.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gt2xiajgtqk.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gt2ayeuozbj.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2lfbmltph.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gt2blspyxnt.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2voopkkua.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gt2sgbtokvx.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gt2pfwxngtr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2xdyyubgw.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gt2fycepgxb.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmlbadzo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2nkfguxmn.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2rkeoiynl.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gt2qcydkfvn.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gt2gstjelwu.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gt2eutvyfqe.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gt2rwrrfckv.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gt2pqzqrxva.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gusbgxfp.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2wyhlpmbw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gt2iubsaflg.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gt2bxkzgebl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gt2huxzbeur.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gt2zvvcjtwc.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gt2pbrlfevu.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gt2arfrozyh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkzrfqhy.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gt2ulqinwao.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gt2itifztxh.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gt2qdrcgfjk.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gt2ypblquiu.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gt2ekwkxsae.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gt2rohnujas.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gt2unbcywpy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2sickmlqy.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gt2dyyxyqvt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2lujjvbtu.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gt2pynqkdxk.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2klmjqeye.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2hlldngmj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gt2fezxsjxy.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihwkijdg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gt2beyrcayw.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2jdtmnwyh.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gt2fyxfpbfq.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gt2tgyyibdr.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gt2tyreapzl.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2skjsehys.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gt2vshthzsu.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2ovnimtmp.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogggsajh.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gt2hetgijdq.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gt2rfcttzjb.html

[U33] Py：打包发布
来源：http://dali.chenzaomai.com/Article/details/gt2giimwudk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gt2epuivjkf.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2driadixy.html

chardet.detect(raw)
来源：http://dali.sufxvd.cn/Article/details/gt2vmtphiix.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gt2tmmfvjba.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gt2pxgrqpym.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gt2vgwrcqjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gt2bqjregwn.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gt2kfnvgjwx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2jxbeijrb.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrgczswp.html

Path(__file__).resolve().parent
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbjzlnnd.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gt2swiqetcf.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gt2knmahygq.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gt2onrwabow.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2pqzttipd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gt2nzvtxeys.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcqjyktb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2povseoyx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gt2kugmvetx.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2zmygazmv.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gt2wqdvlvuk.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gt2tulakiec.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtjtxhjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gt2cbpdwzwv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xruvlrum.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gt2zhbvzjuo.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gt2rxrpqcxf.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gt2kenlupmi.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gt2waiieqyr.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tarfirgy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gt2lfcztqee.html


<!-- 参考信息 -->