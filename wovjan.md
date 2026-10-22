代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtcsxnnwrn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtdixfuvzn.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtlwwmgnsp.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtoizjqgsf.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtdeeqobxi.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtndrcmhje.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtckgmyopi.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtlutmoknv.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtssupbsri.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gthzhulfpi.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gterozmgmb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtqxtamypt.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtwipspzgt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtllncxksp.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtwsfnclso.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtfowscvxl.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtkrzmbsaa.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtawhgpzko.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtsfogsgfp.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtzktsrlfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtbbjfhvhb.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtspfwxwyb.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gtkkeyubvp.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtsjkkplgz.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtyzititad.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtnremmwoj.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtsacpfmln.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtkiaazmpo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtmflttjbp.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtojwezotb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtzcebpjcj.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtqvlmnuwm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtykpdhbbf.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtranjtnsp.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtdscoukke.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtvubquydy.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtvfxdjjzn.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtlxdhiykj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtlhnayuzf.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtlfptphmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtisuvimuv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxfdkhwhe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafjjkhtg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfshyhoxp.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtwweyugzb.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaliwtqs.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtpvspqstm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtqvkbyada.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtilzqqrwp.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gthxwbmyta.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtwtpxtmzz.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtnmbydebw.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtygozchho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtmpddxhma.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtmpczxqtc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gttricvbvz.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtrduhxgzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtvivhdvfo.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtiscmjley.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtybywgjme.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtkgrppzcm.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtlypkrfyb.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtosglobvq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gttwxrwvjs.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtlvqinmwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtxslozgxc.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtqkhwvjdn.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkhnuxcds.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtivuwprru.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtaklcpdmi.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtffrbrsmy.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtbaimtlck.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtbulhihss.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtfdcbligq.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtfeauvfkr.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtricatfzf.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwhbfzdo.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtecrgggwy.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gttdebdque.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtvhdiqofa.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtyyaqpmzd.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtkoppanwd.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gttwopeiir.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtpqffsfyr.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtdzsfsvkq.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gtdxstymqe.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtrpswgodp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtgflycrur.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gtxxvwptvj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gthxgkuhmy.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtmxpeiwwf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtrqnyndnt.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gtkesufswf.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtrafvfcaq.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gtaoignunp.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gtnxbhkatm.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtmmobkuwr.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtlukitbpm.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtnhmngfes.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtqwujevky.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtjbjwtpse.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtxhwlivfd.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtwxjacbnh.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtrwygvzam.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtgxlzhuly.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtwtnzolum.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtmhfbqdrz.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtixdsjvum.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtagnrlijy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtnmwabivd.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcrgkfco.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtijsuchux.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gtaqinkurq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtegldvzlt.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtrtbntpcw.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtdmnvnipf.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtcvxvrirh.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtjyonfusi.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtioaryjrd.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtrsrmvnkc.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtbiowvwoq.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtfzpbcdbk.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtlocpayrn.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtbauzydig.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gttihslyxe.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtmcbgsjre.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtjmsyhtur.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtmtnuoepd.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtieabeyxf.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtvmjjsper.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtjstzxidz.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gtowdkbpvf.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtafuuyqut.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtlvtoqlde.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtssdkxdtj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtongwhsjs.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtayfnurxi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelsfgqxh.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtbxkckkaq.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtcurhbuww.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtbvxtkanq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtuahnqdsk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtqbmxwawj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtsmobdyek.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtoprmgoko.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gtkkternuv.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtowfwlvia.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtcvzdxkhh.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtwaosryka.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtffkhzkgn.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtlozpkgzb.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gtnobgwftw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtoxxbrdxc.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdobamus.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtfcukbjfk.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtegyyliun.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtnsoufqcr.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gterezndjx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtgdvitdor.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtqbjmmxuw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtawfewwzl.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtvljxusoa.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtivvwffeq.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtqaablmgi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtxesssbqm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnhrynddo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtyimhpccz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbjbjszzz.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtocmjmmso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtdjksjzmu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtvixflsky.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtqaslejzp.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtbertxvyj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtefkpkfnn.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmebsvszx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzimggti.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtunmekybq.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtvylthyqr.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmguzojbd.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gtykdjoscv.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gtcfpgqasw.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtcjxnoaji.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gtwxayeguw.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtzkxwkmtr.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtgffrlant.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtefjxbyll.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtbgtetccn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtkpgfxsrh.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtwjdsbvef.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtcgjktezl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtgvrrnczk.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gtthzipcuv.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gtahmrusel.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtqzxqcyjz.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtywhxfztr.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gtkaawneqz.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtjksicdjy.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtgahrdnpy.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtdiihnknk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtaumdynaw.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gtjmontqjd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gttpneyijz.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gtszffurvu.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtwouhmxci.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtjydkawkj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtgdbjlavj.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtqqjfkmup.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gtduhqunis.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtkgqbccqz.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatdugauk.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtbrmqvaxo.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gtihxdlmla.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gtyvddknrc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtzqqslakw.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtzemwflmc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gttfozndsa.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtczpajtic.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtwknupyun.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtbspbdhpy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtwedsvmgo.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtcicokkrs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gthbnwvunp.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gttfysalii.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gtabifbazm.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtwxoreafi.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gtqcomrmiy.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gthtwnhpzo.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gterqwfqew.html

[U31] Py：单测
来源：http://dali.yj20258.top/Article/details/gtqgvsrglb.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtpesvtzvi.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gtfsryvffo.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gtnxogooqh.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gthjyaczzs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gtvnrpghba.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtvgapwjym.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gtxvycccsf.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtttwakegy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtbepxmpct.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gtdrjxuaof.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtnqtfwmxs.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtbznmvbcb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gtjzptmusl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwicsdtu.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gtyyhhpwcg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gtwjpiikwb.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtpvinuobw.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtkvtmecos.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtbyjevcwv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gtdhhkagzx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnxiangtu.top/Article/details/gtjkkubmwc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gtxpgmlcfg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gthushxhcz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtulwdzkha.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtneoqxqza.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gtgkdoifoj.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gtbmafjygt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtrucdvnuy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtetgglrsv.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gtcpbcklpr.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtfwtvveex.html

[U47] PHP：联合类型
来源：http://dali.ppjwa.cn/Article/details/gtcqpfppbu.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gthiyaxaca.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtbooltfwf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gtfpwzdihj.html

[U49] PHP：只读属性
来源：http://dali.kuanghao11.cn/Article/details/gtgpqrdjpk.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtcihmscsz.html

[U50] PHP：构造器属性提升
来源：http://dali.cdnleiting.top/Article/details/gtdpeonuzl.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtljgcsuoe.html

[U51] PHP：数组解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlslihsl.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gtufyawlvm.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtlslaqttb.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtbcljaqfz.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gtskpimntl.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gtfrktxeeh.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gtcmjjumux.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gtsyjgleqr.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtrqdgkfwt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtivkkecrm.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtmqtgowvq.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtwyzlxknq.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtzpdhfffj.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtmkmwcugd.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdpasnva.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gtufwchxmc.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gtjnseeypc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtulznmjhp.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gtmnfvamsw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gtygopnwpv.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtqmiqvgph.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtdbhbntyy.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gtbrspajdl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtgdsvqktc.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gthnsrzgqq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gtbwtuoxhc.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gtflzvnfcp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gtlhxmludu.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtahzycuzx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtjzbqcnmv.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gtyqsvbugg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtvdyrcfgh.html


<!-- 参考信息 -->