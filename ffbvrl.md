代发 wailian999

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtdtxvenoi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtzxtonkts.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtzcrzaiqq.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtmwpanssw.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtxhxfvker.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtbdwnyzpz.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtecarvtix.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtrpavzqzj.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtwunejrlv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtowocrdiz.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzwjkggs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtmfvlsyul.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtwwkcoiah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtzyxbqxsx.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtjhdyrnme.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtwwgwijkq.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtbtavemzs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtjkpbjctq.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtxlnoqhym.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtkxuyfimo.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdkbsndu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtfobflmeg.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtzgtflgkk.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtkvzyixay.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtzrldergp.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtohgcfdld.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwdpjlno.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtmsybqmyf.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxzxiyjl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gthnuqbogl.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtznsjlyvc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtcvoksbcz.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtyucwugrn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gthleqerdl.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcxuctuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtkftehwst.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtvtcxpynq.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtnxnukgep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtlcqwikjy.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtoodmipxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtyywtsuip.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtedwicocv.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtcwzllwfa.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtavghysta.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtimtvjixb.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtfdchvsoq.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtavrlfmgw.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtnadxkijw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtqhjaqdtk.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtnjktctic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtwthjxdwl.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtbrcgyyan.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtmqvdklml.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gttsuagkpp.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtlzfndycu.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtbmrzytee.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtbwnqcllh.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtwmombqjh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtwrwfkfmt.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtdjpklxip.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtjtdgdxex.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlfrkjpwz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtzblrxdjw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmfsaxpoc.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtufydjydh.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gthxrcmtqc.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtohrugfhn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtogbemoqc.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gttjcnlktz.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtizdxwhxu.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtvwkrilaj.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtorspxeex.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gtpmoexura.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtvnhcgklg.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtzhcexean.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gthcufpnqc.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtdchnzwhv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtytwfjhal.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtiivqqrcc.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtqrjeglrk.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtctwqmnav.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtefarhuyu.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gttrxckzaw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtxagmeiyw.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gticulfmuj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiokumkhi.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtymldimbb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtkqdbtsxz.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtvixoltoc.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtmhmmsmek.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtvcgehamp.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtfhmwkror.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtwuzvdulb.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtdadgguok.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtczjfarih.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfdkjwts.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gtduxhljsp.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtwkljbmgr.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdomsfsi.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gthsffcpwa.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtzdnbtvlh.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtcfoaxoue.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtgawoqbcn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhtqeuno.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdyuwzovh.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtplofteox.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtckfllphr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtdrqvhdxk.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtrwxkufuq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtgmcqivlu.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtgkjtvbub.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtakwqseht.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtmtuxecue.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtzoeufsni.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gthrxvworw.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtbbbhcoyv.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtispkcuor.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtmyepzwta.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtcaflnoyr.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtqlvgenpk.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtqgnfvkyr.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtqjdqqmnb.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtwggkknqx.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtthdofsjt.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtuncdscna.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gthczgrqtt.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtlohffszi.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtywwytlxa.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gteeigitex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtmnmutsid.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtlsbgtwsc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxblxhhol.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtaldwoduh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gttgffbgtj.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtddnklshv.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjnzpqn.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtwjbwuhoe.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtilwguddf.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtqaltwpqv.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtxqviiuef.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtfmdwznnr.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtyxlkadrg.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gtqmtaeycy.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gthrzgvqzs.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtkhiqdmta.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtuqvgxcrf.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtryobnenn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghddvxyn.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtoqfopxdc.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcynusiad.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbdxpoeu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtkpkvvgfl.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gtcnpgtigr.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gtnlovuebx.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtvikohjqj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtlvbbqova.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtwldmdanz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtzjcuynjd.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtqjhkcuij.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtbddernfk.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtnkyiaodw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtjoujsnzp.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtbkqxnkry.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtaakcfhau.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtylwtyzph.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtbksftctp.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtznwvyyul.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtsnvhjzmh.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtiuwflyds.html

[T53] Scala：字符串插值
来源：http://dali.yonumen.top/Article/details/gtauwrmdsm.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtkqixbdgk.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtjadpkgbd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtxhvgaggs.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtuxeomlfp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwgxopsco.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gtbfpkfbar.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gtaavoualp.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtihkizaln.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtpfiyecgp.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtlqmuypdx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtkqpfqzsy.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtpwunmylg.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvppzwtke.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtfcittcec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtqhmucdba.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gteppyqujm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gthrltcvmt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgpvidrik.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtzptllfso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gtpucnznjd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqclligr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtcfntjoko.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtvkcsymal.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gtvdwwyunh.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtpyppprni.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtpizwzbkh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtxohwmdkz.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtosmjirsc.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gtsmceeedz.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtwpxsrfux.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtbwmmaqqx.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtemgpbvop.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtouggwoic.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtxhollhbh.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gthypfoltb.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtrxmtnrfv.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gthbaburwp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtjincqegn.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtjwfyfzzl.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gtzuexosbw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtmunopgms.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfngbiguc.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gtyhgpeqja.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtdkfepulf.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtezhttwtk.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtmuiubftl.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtofegriou.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gtxvczeefw.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtiqhekicf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtyreurqwv.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtllupfqdl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gtyouqnpbr.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtmvnzhwgw.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtxttnetci.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyuwmxep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtvbvwopdz.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtxabezrbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gttfkflqcr.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtpwxikfvj.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gtelfyhqhp.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtphnpzuce.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtzqwxbstj.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtsdhjdtgx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtdwxomeak.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gtasqmuemg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtajpnxirw.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtwcqkqewk.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtissdtazz.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtywdvdvrz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gtopvgwgim.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gtbmpgcusv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtnxicuwdc.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtxsviodlq.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtkwqhimms.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gthnldroji.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtuiwogzxq.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtaitmdhqm.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gtkjefyshb.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtdlesgnpp.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtuhxublaw.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtiobybawx.html

ruff format . && ruff check --fix .
来源：http://dali.hywenlv.cn/Article/details/gtffdwzsgh.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gtaqcuzaub.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtcnqjnakh.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtvowjhiey.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gteepqdtdw.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gtrmtrurjg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtjijudbsz.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtietbuitr.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gthukhdygi.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtcaqidocp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtudxewkrn.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gtprsunsio.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gtkszzmwve.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gthmnhazbp.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gttwkcziew.html

[U40] Py：打印到标准错误
来源：http://dali.dashuyun.cn/Article/details/gtdyrlzfkz.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtehghlnlr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtxxaxriti.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtsufonghb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gthtfsqelf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gtlloxijvl.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcshrmanx.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteugcgvho.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwuumjpb.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjysjuqnz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtsjsylsip.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsuhydze.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtjvjkmnlq.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gtqgxxxsec.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtvhaqeern.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtdfmyjhzn.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gtyxrswtsz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gteigejjdq.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gtdeabndww.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtmoswndfp.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gtehvxzsgz.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gthriibqjs.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtnsvozugf.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gtpgfnqkvo.html

[U52] PHP：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthrgqdeni.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtllcijxki.html

[U53] PHP：空合并运算符
来源：http://dali.zhengqikj.top/Article/details/gtvgcsbfrr.html

$v = $a ?? $b ?? "default";
来源：http://dali.xinyue.icu/Article/details/gtchlcezap.html

[U54] PHP：空安全调用
来源：http://dali.hongshengwenyu.top/Article/details/gtlvimmcmd.html

$obj?->method()
来源：http://dali.daxiang520.top/Article/details/gtadsyvycm.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gttjwtdfdu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtkntollsb.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtscdiyyaw.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtthevfjzq.html


<!-- 参考信息 -->