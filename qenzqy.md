代发 wailian999

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gthuloyrap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtmicualtn.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtdkavsdzk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtzsgqpgmh.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtdjqhazfz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtfnapxnjr.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtlgmbkand.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtrrhfecoj.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtukmavpbi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtoyraszqz.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtcbyquszc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtlqxucmhf.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtmyzisgol.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtutgfnevt.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfszswinq.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtrivrdmef.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtxjasmmka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtdpnkwexo.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gttxxrakub.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtwgqvjdsr.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtfvlrhzed.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtfiuajpbn.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtlgnqmndj.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtympsterb.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtawcbjdyd.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtgbbpzxph.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtwelklboz.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtlbrhjhhp.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtgwioygav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gterwdpvdv.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtjyodlsfp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtpuamoprl.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtvgmbbeor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcevmitvw.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtofluojop.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtxyrghsvw.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtydsuxbry.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtmduvtqwr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtjsgfekwu.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtnhlvhkzn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gthablosls.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtnkzrltex.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebomnlxr.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtyisswkpu.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtecrpskdw.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtjnukaoiv.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gtfagyphqg.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gtkvtbslgu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtcobhydpr.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtlafrajzp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtldjajrhg.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtehajslvv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtuqxpyghv.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtizfxhmlu.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtnnhkytci.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtqjaskikv.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtwsqdsbqz.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtzuuwuqmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtqnxswxlm.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtwcjxlqfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtvsgfukps.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcgmmnose.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczwtknkj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtieddoath.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtrgdgyeur.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gthacxumkk.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtavslypnt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtezpscgyt.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtfkvgyvja.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gttqgwovpy.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtqdfrznkw.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gthjeomtdo.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtaryiqftj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtbtualqwq.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtyizzqmlf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gthcyvhboe.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtwtntahnc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtzodvhifg.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtdwtfvsxx.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtnimkfjto.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtjhqfvxtg.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtmtbcitxh.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtbuvyoqnf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtlipvgbhp.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtbklmzyvn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtbqlwsqty.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtqpqeuykq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtmuiawhkp.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtdnzdeksy.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtgapjzfhp.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtqwjbrmcs.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtljwinxww.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtwpexflou.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtpkipuxtm.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtlsmqwdfv.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtfvlysdxg.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtfbyyeazu.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtofgftafs.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtbeynvlou.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtwioughub.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtsxxkkmhc.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqajxhzgq.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtmoaafzpr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gttaommehv.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtlptdxxst.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gtedgescfv.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtylbirjag.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtbjrcjwpm.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtbvodpblc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gthtyqdxof.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gttuhmjgrj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtqdefljum.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpvjvixs.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtgheopcpg.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtjgtfrijt.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbcotjsm.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtywyxvubl.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gtgcvumvny.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gtduvvhzip.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtzxjxqcdd.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtolwfbtit.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtvurnfqov.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtvglchwsb.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtsxwvkytk.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtatvxfmwp.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtqisrydgf.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gtbdzueomg.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gturhkkbsk.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gtytytqemg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtrdkyropb.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtsahxugun.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtiiearxmm.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtimjzixvx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtoxhhitma.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtejuupyxl.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtaciqhnpb.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtkvmhsnak.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbajjeomq.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtxdaaypet.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtsqqqddwp.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtgdlvgcdr.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtejmaasbz.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtjbytfsst.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gtpoggrldg.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gttyreaqrx.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtqcqwpcdr.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtwakuzbfi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtigsdtnmg.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtvjnkugmm.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtpmvgdtes.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtcrycpoos.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtfalwipeg.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtltonfzbz.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtwtuhkavv.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gthurzbyow.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdhytmje.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtdtgggosm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtlfxbsohy.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gtrbbweszg.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtcwxzvvur.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtqvnjhqak.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtaruffzch.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtuqsencfo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtqtycrtfr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gtowshoucu.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtaanjktof.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtaxaewanx.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtfjiijskv.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtanrzhxbh.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtwnfwnyxn.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtdkwojkpw.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtgxdgtxvu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgvmmahw.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gthaugsoki.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtojcppfld.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtqepufxyk.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtgnhvqmig.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtxmwfjzyk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiejpsfbn.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtterqicrs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtvkvfbadg.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gttvxuvzoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtkvvwcnzc.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsqcroow.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtraxnqntl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthmgjkhzg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtfvwklsgj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrovbjcp.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrmypjey.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtbiwfpmmn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtrjvorbaz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtwstiguvk.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtqqxnhona.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtbgislbpt.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtqiwzxyvy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtzhmhzmnn.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtpjipmmhk.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtdenypybp.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtgoqmpsoh.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gtuuztqrvw.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtnqyrjlqz.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtrkbnsdnh.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtdizgeaof.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gtjglorqih.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gteihfjczc.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenyeialx.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gtujwhvqdv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtmhyzzlzb.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtpxhkqqtd.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtkodoxgmy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gttxbmduzf.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gtvlwcglwo.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuelfutfo.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtcphjbija.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtloikdwug.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtuvuopshi.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtvadbfhrt.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gtzxyfarcj.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gtjfzvlpny.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtpvjkuotd.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtqzgzhwro.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtnayoiayd.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtsjypqlky.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtyibqznoy.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtcfbchoag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtutddheuu.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gtslgpwtho.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtoicmlcbz.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrxdbxhe.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtwezqhvrj.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtyzolmpjy.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtjwmkikow.html

[U23] Py：分块读取大文件
来源：http://dali.yuxming.cn/Article/details/gtrcrwtaob.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gtppwcipvc.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdzcztel.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlkurjip.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gtnyxzjhwz.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtxjzraazl.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gthnsngxyo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gtsnkikwwa.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtvtuqjslv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtiwrkokmt.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gtmutirgok.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtklxwegvy.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gtfqnykzbm.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gtjdqocrap.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtvxgwmlol.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gtvsqrbcdj.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtwdlirazf.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gtkuypiojo.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gtfhnndypb.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtqmsnhfhd.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gturcpnyhp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtmjhvvkhv.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gtuwavjnjr.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtpydctrja.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gtvwrqhbht.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gtcixgfmhv.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfvgnrkl.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjarvmezg.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtujkjcjay.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtriyswbqd.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuizyyvm.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvmdvtjo.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtvucmeopu.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtfvjfuxzm.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtqzvgwjhm.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtjyxpmpzm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtgvtfjesx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtscgsyvux.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqjokhzl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtarcvzlwn.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtyhctzacf.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtfmulecdg.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gtnblguqrn.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtrcjpojhu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtbxowtsus.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtoocjufxz.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gtayvxsnfe.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtgbqdqyyi.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gtxrtsfkhi.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gtcojxsmmr.html

[U48] PHP：纯枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtpwgwlloy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtlanaoytk.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gtdcozfexz.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyzltnqj.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtopkskiwp.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrwrvafrh.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxyxgwyu.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtzgyxaygc.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gtvrxcrcsm.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtyekknrlj.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gthapnwovc.html

$v = $a ?? $b ?? "default";
来源：http://dali.xinyue.icu/Article/details/gtzrhupnwp.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtowkxaqse.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gtogkjjirk.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtyoddsvin.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtgktcsauc.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtkhcesohk.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtjbuiavog.html


<!-- 参考信息 -->