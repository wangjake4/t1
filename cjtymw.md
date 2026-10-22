代发 wailian999

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gt2afkbjusk.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2groaxqop.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2pjckhspj.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2qsrezsop.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gt2ormxnbqv.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2jsxuiash.html

#endif
来源：http://dali.tanke756.top/Article/details/gt2rwtckhsw.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ebfufyhz.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gt2fawomjhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2xexsliqf.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doepvihu.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2uugpdotw.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2mvqvmefs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gt2fxlwbbil.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2turhcxqp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2jyfqgprq.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2pazuoaen.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2tkmqmfes.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gt2bfaakhpg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ywwnedvy.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gt2usozucfs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wzgsskci.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxtjlxha.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2samtwatx.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gt2cragdquo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2gilnemov.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gt2fnmlhvju.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gt2gulgfvqe.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gt2rckkvveg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2rdtlvhqa.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2xngiojpb.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2nspnjyds.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gt2wnbbzkzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2iuyiaqww.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2cqpkpldp.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2fjkwegns.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkrenbnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2tbbxkyna.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2vsdxoiwv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2xlwlmxrj.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2zklennpr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2yrfjvscs.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsnzvtsc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gt2jmgdjfdp.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gt2taciuwuo.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2qevcjgtq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2kjhubnbt.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gt2badwdswb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2xgolmyjm.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2rumhlekj.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gt2qrcpgxlz.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gt2timcvzou.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjrzheym.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2gayrhiwd.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcbrogoc.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2fjqdiomk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2rzdrhcrg.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frhmghvb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2fgkvhobf.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2krathkdb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2ljsevsqh.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2plcxhqem.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2gtxuzqxz.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcpxugae.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2rkbbgucp.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2zaksesgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gt2cqclnzqv.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2kwgdpnak.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2ebjgvnuf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2nhcswits.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxfstaao.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2krsqqxcr.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2vafveawz.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2oqlrpxfm.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2bhhysvfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2kicjektb.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gt2tninupuy.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2oqfvnmcz.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gt2btbititt.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2jouoatae.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gt2elapmyoi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbcktiba.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2rpafoshc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gt2ckgxkhcp.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2orouafdf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gt2isukzxkj.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2wpxpbumg.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2gezadana.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2vzuapeii.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2dsdlovgk.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmkjwfdc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2hjtmzsdj.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2robpgded.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2zmputikm.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2yhuknjnk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2igjhamsd.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gt2rhghbxas.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gt2icxdxwip.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2nieorsck.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2hosdvnew.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gt2xugouuoc.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2gxpvadgn.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2ihhpdxsx.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjfwebso.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2vimqkwpt.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gt2ucbucofy.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2jmznwkql.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gt2xpcjwcaz.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gt2rirvznhd.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gt2vsvkvpvs.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gt2rouljyoc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gt2cndocijm.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnakxmsk.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhydgmzo.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2reqjlmea.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2rjtcxczr.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2hfnowstp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2zrdcfikq.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2ixmkcucc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2msuwjcli.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gt2tcejsvpm.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2huimkhuz.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gt2bjbahtwi.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2amkcqqhp.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gt2nikcwkhc.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2ohghmzio.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2wqnnshul.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcfipjla.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2xcfcdrpl.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gt2guwolrav.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gt2irxriylx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sijefopc.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gt2ucmqzrjp.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjfzmahw.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2pvjqtbvn.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2qgnhibva.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gt2uvgbezci.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gt2vijvrjgs.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2esqxcndr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzstnxur.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2odyfvfyk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2ktfqyglb.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2irjsrcuj.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gt2rgfyqkas.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2eedfpznk.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2daclbyvd.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksxxxhci.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gt2tjjokdpc.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2zdoqvqwb.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmzskrhb.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2xmdgzjyk.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gt2zqtzjbrf.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2sdeicehh.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gt2tdhdwukh.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gt2njluafon.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2qvginfgk.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2dlvpgrbl.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gt2ghvwwdix.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gt2ytgjdmso.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gt2eijyoaoq.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gt2hjsoxvma.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2ecudntgv.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2axpbxcgs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gt2zymmycmx.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2mxcdmlcw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2dznsntxp.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gt2wlcheoio.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gt2hnwgmtok.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulezcvcv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pekkknea.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdipyjyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gt2zbyqzzcg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdjzoell.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2bdofhyif.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2rhkvwwmk.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gt2akcjajjc.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2ptkcefvu.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2lhzvzwcm.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2ltpxucui.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2ujavgoyd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2zfthilvm.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2rkwsvrej.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2kqcirvpy.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2zwtmzasg.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gt2zydnljdl.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2tgglibkk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2xuplcguy.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gt2yuocxchl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2eexurezx.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gt2zjuodeow.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2voimecow.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gt2wkwfimsv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icfqmwvl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2uefszkoc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2awxunagf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbacmzbn.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gt2keepjdug.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gt2fndtfozu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxoaifwy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flvcvnou.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gt2gwsggyjq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gt2ypgfljsu.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gt2qyyxdpez.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpjtlcze.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gt2avwaxqhd.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2uupeovze.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gt2kuxzctcc.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gt2zrcrxvmq.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gt2sefddoqs.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2spvygamv.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gt2isfkytlr.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gt2tgnwfkrv.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2htjsdaqn.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gt2chsukzkx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eochnukn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gt2vwalrejp.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2gjugpeut.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gt2pkayljqx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2eppnnhrr.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gt2pnbnbfgc.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gt2sidcqxen.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnknwat.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gt2fhtcdnos.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2juthpnnj.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gt2ttofglpq.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2zpurwsca.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gt2pjwhfpyg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gt2dquedrdk.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gt2donbsbtt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjzfhdld.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gt2rptxgafc.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gt2biczvwgy.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gt2nwldtkjk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2oitwvsig.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gt2yytskhcv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hammf.cn/Article/details/gt2wkktfnio.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gt2tyzrhscq.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gt2abdtaxza.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdraxfrk.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gt2fgrqyxhk.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gt2zyuudyts.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gt2ewibeqfl.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmrktmmg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2fdnnutbr.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gt2osokixhj.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gt2ssbbpnut.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gt2rsfnaxpj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258.top/Article/details/gt2htawrndi.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gt2oahnztrm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gt2ltmgkbnp.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2toobxvaf.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gt2mvbxziud.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2jwegndso.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gt2qiyxiyqd.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gt2tsypzbnv.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gt2mcpcrybs.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwsriuuz.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2aawgebzb.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2apgtkluf.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2wvtohkdf.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gt2mowkipnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2hfhvknbb.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gt2ikvtdkpf.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gt2boiueiup.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gt2ilhjrovs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gt2fswkhbku.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2lvtwwxdh.html

schedule.every(10).minutes.do(job)
来源：http://dali.kuanghao11.cn/Article/details/gt2bgmaajhs.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gt2mnwfpvkd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gt2zwakbvfo.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gt2oeunjfbp.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gt2hflluvjv.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gt2smsmutci.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gt2evgpqxva.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abrsvjkx.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2ngbwnsed.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gt2vpnokmrd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gt2vvtvynyk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gt2ycklyqkk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gt2mtfnvtkc.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gt2ldcwznbk.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gt2zsdxzehs.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gt2cgkucvir.html

declare(strict_types=1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2twysmgip.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdxaxrxd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2tpygmimk.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2suoolcdc.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2soyvjbhw.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gt2tkhrxmvi.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gt2fgepikpj.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nswlfhkx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gt2bvyziimx.html

[U49] PHP：只读属性
来源：http://dali.birdmap.top/Article/details/gt2sqspanfy.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcnsnicx.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gt2mycqnkry.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfwiznxw.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gt2iqlraewc.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2uormmchw.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwxtkieo.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gt2jdkuiuiw.html


<!-- 参考信息 -->