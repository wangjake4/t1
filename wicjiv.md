代发 wailian999

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtgywqoymj.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtqmkynoxa.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtfzaijiaz.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtqjkntbxm.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtdzkoecop.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtjazntydk.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqysyuct.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtspnnobkm.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtifeojxtl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtoaurvxtn.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypbgpeks.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtjbsflgep.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtvqoygpry.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtkrgihvzp.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtlvauxfzk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujtdryag.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtfttvtmgx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtblflomeo.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtmddtcvjk.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtfkmqgika.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtucjulcgh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrbxsotf.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikzptcjo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtsahcjnnt.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtctokoxjy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtkfnmnexg.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtehpihyli.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtakrlsjvs.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtzenuejxx.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtpjpccqid.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtggtyjkuj.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtrpekyziz.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtdoebimhl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtmfuxzryv.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtknraqjes.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtwnnrlqgv.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtiboclksh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtkhvlninf.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtwlpjehpq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtfjefsmtm.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtletelsch.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtrzyobqwr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gthffqxxcf.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtpshsxhkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gthnavgjge.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtcdxtfjts.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtjcutxpum.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gtazxrohqg.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtrvurycih.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtrygxkviq.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtehlbzvra.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtzfzgktlw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtwopvusnl.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtftqbeqtq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtorssqjpt.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtlkzfgjhm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtpxmupyoe.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuqtlovu.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtquvoofrl.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtxveagpji.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtnzefzjyu.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtajihnfyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtjfplrqmf.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtdgqcqjfx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtdsawrwxm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtadughhwo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtenrvlyhz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjpbuerox.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtzwrnyxqn.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtjserbrax.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtgjpzhp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtpzuwlxme.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtbfqzzkes.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gthnlyocdi.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtefecyugh.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtmwzsqhsd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtldlhxqwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtvxsmqqdp.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtyksjxwzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gteozwlwno.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gteqieqvfo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkfpvbxz.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczpsxypl.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjudwgmc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtogxbxmhw.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtxdcjzcsr.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtejrepapw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtjrxfkyue.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtglhbtmwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtrnwkklvq.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtpgxszqlg.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtfxsnexfy.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtgfsxnbom.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtuyjrlcwd.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtponpcrch.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtuvbchbyk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtqhmsqtaq.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtiezfteja.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtqbjoarqj.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtjxfcnmtj.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfzxazgr.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gthbqnmjbc.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtbikwxhtf.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtdpjtvwpj.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtpgbrbpns.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtikmzlzip.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtpakptrti.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtswczjsgq.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtyliqnqnx.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtfedyrwss.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gthybkbaic.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gthhamumam.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gttthnnmfl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtodfvaxxf.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtlbzqserd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gteimbmofc.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtcuicmbng.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtgirrwwtr.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtjaxbulze.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtschaufzd.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtvswlcrux.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtarezfkkt.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtyjpdtbus.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtxtwcqksl.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtcqqttogb.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gthxrgfxfl.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtijvopyrj.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtqzxfmghp.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtydfwguku.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpyxberp.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtkdcsruga.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtqchnxiin.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtbfswmddt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtwmsxlquz.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtjnwbbwxo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtjqlwmbsq.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtjqxmkbou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gttphhevia.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gtnybzmett.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtsojeyylk.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtwipvdlkd.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtsjilhrtk.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtzwlqkwga.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtlsizengo.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtgoakinht.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtbbsdbazx.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczquwlci.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtqiocctlr.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttxjahbvn.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtinykicpx.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtfhpqpwdz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtodaqmyag.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtigwmphrh.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtljynzwzr.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtdeyzbkpr.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtqrxrixux.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gtttqypnkc.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtcjnhzwlr.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gttcrscveb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gthgfregkn.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtluebarhn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtjfftrbkm.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfipupann.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtgymtxeaa.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtzjfwbkgw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtvkzstdjt.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyyarcgyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtsornivjv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtwfqddqln.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtzngeldzj.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtjrsqxmdz.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtilufycza.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtiwqafakn.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtfjflgnjm.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gttqrnlxmw.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtmpuzodcr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvaeiyiv.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkcmmwjko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gttwstfssp.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtbdharhto.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtyvcgjzlz.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtdjwvnmac.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtgfgkstwu.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtzueqlens.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtfyazremu.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtjdupwcan.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtzudakzbm.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtcositydw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtcaioqvma.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzbqowqgb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtpqooomkb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkclegwys.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtlmgqgthi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtbiywqkbl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtlppeouzq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtxytrnafd.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtfukboulr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtaxmxasln.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gtsneqexhq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gthqpzzmoi.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gtktoelfav.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtbqtolflp.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtaldjtgkp.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtemlzbben.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gthdmgzbkr.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtibvzmmgd.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtvwdhqwlg.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtnflcirhz.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtepwhgyvv.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtwinzylxu.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gtzomknckb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtnndpnmdv.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtksfqkyry.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gtjomryxqp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtctkevrek.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtqszfhiyn.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gtkeszpgfu.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtehycgcae.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftvyboga.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtsobbhfoo.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaggvuet.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnoukvsw.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gtgudjyzfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtcgotluwa.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtfdsflmkn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtcpvkhkxk.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtnrqbtcyd.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtptigbgzr.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqglrsfm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtqwlbggat.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtvbclojts.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gteqfxmtpl.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtpdtfprfc.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtalulxcvu.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gtqmpwewbe.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtxtrbmuyi.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtofizvita.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtdvcpeecz.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtatyywssz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtpropcavb.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtyhewzjdl.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtduhicxnv.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtzmgytbjj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj202588.top/Article/details/gtjklghwnv.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gtcannsauq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjypoorcw.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gtaiwjklua.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gtwmoybjfv.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gtwstneowo.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtrxnokbrd.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gtnvqvbuqw.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gtfcrgmpyp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gtpwtjftfx.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtgxtjngxg.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gthdguvejx.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gttwierprj.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtuueuztvb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtmofyhpkc.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtlidouypt.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtybnbfcyg.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtmjfzacen.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtgbcumzet.html

[U36] Py：定时任务
来源：http://dali.9152youxi.cn/Article/details/gtzcozhjye.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gtmxmrimgy.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtkilglgma.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtarterjdw.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gtvjdnmcib.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtepvnbpdv.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtkhmdjtoa.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtjogrwipn.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtwaeqdegd.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihomyewx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gtvximoyii.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkixtiim.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gtjsvncwcg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gteclrlkcu.html

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gtrhmcqmcd.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtahuutzdl.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gtvtzdcdvi.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gtvlfoarkg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gtwtsuuqpi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtbxbzvqsr.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtdspuvzhn.html

?string $name = null
来源：http://dali.kuanghao11.cn/Article/details/gticswwyht.html

[U47] PHP：联合类型
来源：http://dali.gzhubu.top/Article/details/gtdxhbvxbj.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtxqhaitek.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gthbwvgzsc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtzvzjgoyc.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtejdnslbt.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gtjzmtsmgg.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gttwxxozsf.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkadadsf.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtdrtwtgti.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gtuprrgfvr.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwydqfgmd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtptxdhydy.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gtexvruial.html

$v = $a ?? $b ?? "default";
来源：http://dali.tianlin.xyz/Article/details/gtxlcztleg.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gtishzbhiz.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gtvtwyvjci.html


<!-- 参考信息 -->