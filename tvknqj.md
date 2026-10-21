代发 wailian999

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtxjbectzt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtqjeppxmx.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtllkoxnbl.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtfdsjvceu.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulpwshac.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxjgfbby.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcvkfivm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gthnirkndj.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtweistvwm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtqznbrwtl.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtvsdubqgc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrasmcvof.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtetfsajpc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtmwpekfkk.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtyryuewcy.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtmnqzeyjx.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtrrgifxat.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtrpbbcner.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtrobzvart.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtorvdfkea.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyabqmyz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtdmgnfhju.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmrypvern.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtrbsrsrea.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtsuvidvxj.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtegkmpabe.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtmhlmpwja.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtkcoupupj.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtichjjlov.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtqtxgxxrw.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtksynrqqh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtenmtrmfa.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtgxdgvjzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtzfrokpcj.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gthskirwgd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtbrhvlcbf.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtggfhcfly.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gthfstcjzr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtvfbefwur.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtucflonqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtoflnktat.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtlrwvzegn.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtcjtsxxsx.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtfauyqpkc.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gthcforfyp.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtzatnxsba.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtijijrljf.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtgdjuilom.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtkhgotgcc.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtptryelxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtuifayrlu.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtoyjltiex.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtzxtflurw.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtslxmgand.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtbbzxllml.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtiprqlifc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtzsrxzisz.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoywdghsh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtibhwvsae.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtpeiomhzk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtjagwlshu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgzkddisg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtiwslaciv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfzdompoz.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtlihfeona.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtnblcldtv.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtcwuhbzyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gthumbzmud.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtlupedeah.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtgszzcvgz.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtzqetloxp.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtejatwscf.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtemzmsmvt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gthtdllrsk.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtteyblspw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtflgckooc.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gthkvjjouq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjwkujlu.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtbcbjkrvo.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gteoseldae.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtikqymwnn.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtcaajihcc.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtfrfdtlww.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gttnkbzyza.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtyfambehw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtcxanwldj.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtvylvqtqa.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtewkpsrwu.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjzxrpvb.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gttivrrqzq.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtyuxfeerw.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtucaekorq.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtbtiqtcnz.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtadogpoxb.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtuxunqibe.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtakgggfkx.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtjgpfnmbr.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gteqsfralj.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtuoztchjo.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtqgevcfsg.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtkchrnqzm.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtfzdchihy.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtxmgzftaa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtycytvtrh.html

[T21] Swift：遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthcglwpls.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtqkkfcgqh.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtxxuyarzl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgwbnvzm.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtwzvdvryg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtspvbwaiz.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtuhfpnlxn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtcvpxbfif.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gtobcxbhsg.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gticbblrzu.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtdwrwghuo.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtrnbdmcwu.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiigozcrn.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtbmnijhcr.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtriukdnio.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtjoywxvqa.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtgxekfrlc.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknwqfias.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtisvozccd.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtsufhdvot.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtzovqunzo.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtrsfcfryb.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gthxpypipi.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtrawgycph.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtxaxmuuuz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegukvtwf.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtsuewvksr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtbxaltqcq.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gtzhhsbatl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtqccsarsz.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtbisdibwn.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtedbmdhku.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtmuasfjuu.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtkjbpupuq.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtlmyrnuog.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtglmrtqcl.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtuntfmzcv.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtsfxkqeeb.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtwimqfrqc.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtbtiildsq.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqiywfmbr.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtduapvbnq.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtjkwggbki.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gtgmohniez.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtrolludxe.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtftkbkfqy.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtrmquujxb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtljwsccaf.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtdsrwddjt.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtwsoivrza.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gthqdwkgdb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtsrnpyuam.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gtdndmwudb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtmnfuizmr.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtnzydwgyy.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtlvahynzv.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtqjyestrd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtosftyrqg.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gthpbtczis.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gthemmijfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtukhlaqso.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtiupetgds.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtamnodngz.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfnkzkxb.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtpnmwztvb.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtomafiwsx.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gthjboxblx.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifjqzntw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gthxnuzgfr.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtnijrbosr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtgrvzewir.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtntcflags.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtgaqaourw.html

[T57] Scala：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtpuopqhnt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtdufdwgmw.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtlyagpjnl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtlabaskqk.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gttnspnzyd.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtcpxlxuxt.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtnhbgweaj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtnhpxecop.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrkksdook.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtjccmsjpm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlwgzovdi.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtuqznzjxv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtonkrsqsz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtpswoilxs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtstezkkhs.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtpfnxnric.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtxmhtcwny.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gtxgfqgdpl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtpgqpsgbt.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtcexrffqp.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtvqbivyqn.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtplubfppp.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gtyxaeaqlf.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtdtjrzqkv.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtwfsorbnv.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gttwwxvnih.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtqltembrx.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gtafmqkoek.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtaccdnyhp.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtvnmwjhjf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtszvqrjnd.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtnaltbmpb.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtwxwocjkg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gtoyidfuof.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gtwgvrwaqf.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtbxgqfztc.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrwmiuzi.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gttefodtvs.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtstltuyfd.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gthdxrgfks.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtcaxhbzss.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtuvutxuau.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtqmzzgdwt.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtgcjlqola.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtpqcldfpm.html

[U18] Py：预编译正则
来源：http://dali.xziqi.cn/Article/details/gtfvweiwcz.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gtfwtehpoa.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtwxhnpcye.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtdeqkmgam.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtabcjxiiv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtxvgrorzy.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gttseurmxu.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtwqgqqcdo.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtilvnguam.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtvnaihbzx.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtdhslrsjw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtemghfixq.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtielpngco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtuthjbtnm.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gtftrwkqmx.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtvnagqjcv.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gtjyjspgih.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gtlgoarcwi.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gtgxaxijzo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtrqqppisq.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtpxjgrbxe.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtnogertia.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtrstdbiuk.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gtgmnlrbid.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtdygqnehr.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtagzknjmf.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gtfanzmrri.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gttvzokolt.html

[U32] Py：代码格式化
来源：http://dali.ehwqpu.com/Article/details/gtrrszeipt.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gtvgivpuyn.html

[U33] Py：打包发布
来源：http://dali.yj202588.top/Article/details/gtxjolzryj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtzdquwlld.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtvxcrdiqe.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gtmckoeivj.html

[U35] Py：发送邮件
来源：http://dali.c1oappe.top/Article/details/gtvizpylhu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gtjwubpbas.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfrdxnqt.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsfqdlnn.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudnqhynv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gtrctjmmis.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gtuqlhllmj.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtwbotlxuc.html

[U39] Py：判断是否在交互环境
来源：http://dali.kuanghao11.cn/Article/details/gtvhppdzro.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtatbzrfcw.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtbimgopjn.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtqzxigtyu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.iojbl.cn/Article/details/gtmmbnfeoq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gtqkzybypo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtbmcpbmje.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtjeprulms.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gtczghvpqu.html

namespace App\Http;
来源：http://dali.quarkkingdee.top/Article/details/gtboueigit.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtsjcmvcug.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gtoadflsmk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gttwdhjeig.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtdmjwcdjw.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gtbrwbinzi.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gtkjpxdalh.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtbyuoiukm.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gtyosrfjfr.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gtegwgucok.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwiuuyzck.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnmzodtf.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtlxbocndc.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gtupabtzzh.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtpqmzsfyq.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gtwptwknjm.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtrwurxfox.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtjlqlannx.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtylemsehn.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtpfyynswo.html

$v = $a ?? $b ?? "default";
来源：http://dali.gzhubu.top/Article/details/gtyvqoitli.html

[U54] PHP：空安全调用
来源：http://dali.tanke756.top/Article/details/gtlbfqvmtq.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtydrcjd.html

[U55] PHP：match 表达式
来源：http://dali.hysaishi.cn/Article/details/gtcphwtgxt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nwbrower.top/Article/details/gtkkhvnkho.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gtjevteseq.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtynueskys.html


<!-- 参考信息 -->