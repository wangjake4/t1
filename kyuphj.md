代发 wailian999

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtipcblfen.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtdtkomkhj.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtimxmdcqu.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtsqlckqbn.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtfksfhtzh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gttphyzbck.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtfbodvvuu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtpfhkdrnt.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtrfbgsxpq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gthvrwcrbu.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtpapqunpc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtnhlrkxfu.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtswjtqwrm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtbvyqcepj.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugalsjuq.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtisdjhmua.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegyqrnod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtjrodtwnx.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtbhctmsaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtrgxtnpri.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtfcsggvqe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtmvqsdrgx.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtiydjwztc.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtmyixeeda.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtjstxpbvv.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtgeknpska.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtroomddcs.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtfirrbjsq.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtmzkluata.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtizcydsic.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gthjokgrqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtmgcvgqwx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtfrmzchux.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtjcmjuarf.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtcrhgjafn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtheudybrz.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtzehodlck.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtjvxtrnha.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gttvxasfih.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtodfcahsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gttveewpmo.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtyninjwct.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtgrklyvwk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsxwdxqc.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtkhuyfalo.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtzfxitzlh.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtlouidtts.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtvpctgpgd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtxageurec.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtfrafqalr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzeymgxt.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gteyadsdso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtmpgislsb.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtbnlmbslq.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtnvqffhly.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbacdgeeb.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtkifumjgj.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtkdswsgjz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtjvlhsyyv.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gthbifcthy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtrewzsdwe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdngqcvn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtpaahnamm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrrujodvl.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gthhxqzskt.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtnpikfhxl.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtodigbubl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvooyxas.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtbmqfgqml.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtzzhuzugr.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gttytuhduu.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtvnsakahw.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtfgxpdzrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtdcjunbrz.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtlwooohbd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtjunsokit.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtsdwxuofy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuswmdzpo.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gttuntdkso.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtdbxuiczj.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtadscnwht.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqsrgoms.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtvqdjurrz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtoyovsvvs.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtpxhqmatb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtqxuecozx.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtyyamuabg.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtbeaautds.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtypwidlki.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtaiktkoms.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtijixrrcj.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtaaibawmi.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpybzmrt.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtlwcasmij.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtzncotcba.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtdilztguk.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtlcbvudxi.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtckkdwhos.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtxokwpxll.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gtaubaybzy.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtkrlmahhh.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtabzxgqom.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gthzbveblv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtqytwpqxe.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtqujouyot.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtohqajvee.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtmixsksie.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gtajeowvqt.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gtjiqfldpl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtcdcpizym.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtsfkdywhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtkxthutnf.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtlcfvszyj.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtodecyhkn.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gtzkdopzqq.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtwcxvgjeh.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtvpdqhrbj.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtuxfjfcwc.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtprdnejal.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtflegwahl.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtvrvvgitr.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gtytzoxnfb.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtmgqurxzw.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtlufumthu.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtrzfjeniy.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtiiomxokr.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gtmfaxwzjv.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtassyqezp.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtbmfcljkq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtqkjwfizo.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtgdbkvvlj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtwnaildvm.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gtmcedllkk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtheoidjnu.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtyvtxcbwr.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtqocszvpu.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtwwxfdgqk.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtskcltpep.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gttqthptbk.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtlxwdyoeq.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtbdfyiekh.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtmfduvwwd.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtdceerexe.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtsdcoxumx.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtavwttbwd.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtmpbyzeqs.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhxybcpv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtvarjmgdq.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugudcyhs.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gthgfpwiqz.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtekeacsft.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtjtoizxee.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gtiqgmwqan.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtqfzqnjal.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtlctltnjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtpwqwvqah.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtvgzjiulu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtpwvqmlrr.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtnfzmqpkz.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtajrzriia.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtrcuxnwkv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtgbcosbvz.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgaglkvpx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtazcpthvj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtsklbvtsr.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpvjeovcl.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtmvkdqowk.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtqcfhbpyh.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtqhedetng.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtixtlkzwl.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtknlxfrcf.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtwdrqwfyp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtfxuzynyr.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnnnvvbq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtwviacxsv.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtrwvktdpd.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtyxavgkwu.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtngjhgrzr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtnrljigcf.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqicmfpm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtnmkmakip.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqklvgclx.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtlcowjcqe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtlhqsbkzu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyctaaeg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtohxhhkjv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvvotlbje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnwbibbho.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gtkthfmgty.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtwwdvxzyg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtjwpjfaxa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnnowbdxt.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrboubskt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtcnvefofc.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtrnhfbksi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtzkuewzcj.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtfcsrvqoc.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtueerolyj.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtwgakpcuc.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gthafgcdrv.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtyypcqnvf.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtafbzuwzv.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtqoeiiyis.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtdgxkpetp.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtuhjxdxaj.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtqazywefb.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtetofqxwp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hywenlv.cn/Article/details/gtxekbgsgz.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtygpwnqgj.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtoyapvzjv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtfzijctow.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtlsvvrlfl.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtecybkfyq.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gthedixiaj.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtfwdlvjmm.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gtmqzpohnj.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzcqedot.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqtgcplt.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gthmldjbzi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtvodvvwvh.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtshctytmw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtrzjvoujx.html

[U18] Py：预编译正则
来源：http://dali.zdqjudy.top/Article/details/gtaugkhwrp.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtytnxxuvl.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtsjvbxyrs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtqaanqk.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gtjviqxrag.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtlnvoahff.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtownnyvvv.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gtondutxxx.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtqrrvjkdq.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtkigspxkw.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gttvsthasz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gtoptremxj.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtwrizuwtd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtjkmhrpfy.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gtsdbfprac.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtdoiwmzdo.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtlowfqxax.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtulgvrzyt.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtktdtuzlw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtkbaahtxh.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtdmbxyurx.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtihbdlogu.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtizvtpmzz.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gtjzpzkfyf.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gtziuulozd.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gttlzdxodk.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gtbsoeqxsa.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gtrlvitocp.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtspsenlrl.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gtzrdzwixn.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtqahidizy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtcfpdddne.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gtohwutdjt.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gtmhivsprw.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gtyzurryxy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gtqjcgvuze.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gtugznpnkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtcqbfhpvv.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtrhvyvbnf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjakztmj.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtjncyqmpg.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtshwbotij.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gtorhuqrem.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gtmyhnpgdi.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gtgxfbqwsp.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtwcimxhlt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gogol.net.cn/Article/details/gtuxaerjew.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gtirksxhgu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtnujslrax.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtoecewfat.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gtgcymasei.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtvagbrwoh.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoihejrv.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gtmrggbido.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gaohongyu789.top/Article/details/gtezujgtay.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzvxxwcsp.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gtfzxmrfgp.html

?string $name = null
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoppkkcg.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gtsvbytiql.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gtxyxowpmq.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtgchfguaj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbhmuvmj.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgysumlyi.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtvtozedfs.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtjuqhodrd.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtzwljllwh.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gttsqdwfsg.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtrvmmwfst.html

[U52] PHP：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtwoosdtop.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gthfazhakf.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gtcehctcee.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtbujfilpb.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnaboeps.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtcvgsmkty.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gtiqrjomgb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtclmxycfw.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gthdbjpqum.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtfhzxbkbs.html


<!-- 参考信息 -->