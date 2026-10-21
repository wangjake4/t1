代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gteowttcuj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtzogqtnsa.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtmuxcqgtu.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gttzirlicn.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtwnkjfyet.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtssgxpjcx.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtmdyyupxz.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtlxxowgvz.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtdlzldrwe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gttzaamvoc.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtyisnizkc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrkfvmwik.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtzeqoholu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtsnegivfg.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gteeodvfuy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtyizdsyys.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtlwdkywqj.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtkjbdpvks.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gthcbhclry.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtmpkqbnhe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtnarslqks.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtnhiryrdp.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtsvycsstu.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gthvpyxovu.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtgydfqtio.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtyaifkzho.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtpwyovxqh.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtcxrsupcd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtgtnbpbag.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gteffdjizj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtumwtqbhs.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtisersiet.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtleoyqjqz.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxvzbfze.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtqoutpaos.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtdglegpou.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtoyotxklk.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtpgdezukv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtspuezgwa.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtqngbcwzb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtxtaqzads.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcvrkdhli.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtbwzfocvc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcvebzftb.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtxizusuzu.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtjwfduwou.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtqkucjwmg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtkgicmjsx.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gttduxijwe.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtqzjtdail.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtlfwodreo.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtyuftssar.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtjdhxypqq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtrrfkhfeg.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtfvedytrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtafbghxld.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtcyipjezp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtinkpvdqb.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtdwdfptxi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtibuxxhrh.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gturnnjdjv.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtvnhtmzir.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtzpwoitlh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtipfsyank.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtpgqecdlv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtufimqlvd.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtafjmaelr.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbdqmoeq.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtpixkqqvi.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybqhyrtm.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtzcrvzmre.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtvewmxnzl.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtnixqvuuu.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtnfvcldpc.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtauokaxqs.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtkcuecjmo.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtthvtmxgu.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gtsozufvov.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gttzyxytuk.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtkujbutsz.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtzrtbmhpo.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtgquubhwe.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtpyovcuuh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgubfqeo.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtbmsqbmep.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtsrdfsrli.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtggfdacjc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtsjxaretr.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtvkgvceal.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtqsrruqgb.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtmyprbfei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gtijdyjdep.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtnvnlpdqo.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gttmbbswet.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gtcbajybvf.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtmmndmpcm.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtjpkdkpih.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtkxjmaodd.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtqhspkont.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtqiwgfyhh.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtjwqfwosc.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gtfpuooade.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtkdxvhrio.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtdvjaigej.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtwpkjlrkq.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtyvocfsps.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtbjlgmdkm.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtsdxamuah.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gtssftbdjt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtwvhresry.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjruwjkej.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gtxycfqecm.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtgapishsa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtkvufpefp.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gtbbhtuwus.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtjfekovat.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtljqybyrv.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtzjrhdrmk.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtvdsvjito.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtscqvtygh.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtnxdvvtpz.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsyixcev.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtlepemxct.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtjvpiaune.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtaqlkjoem.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtzdpaflup.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gtssjtvgrw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtvpcjksww.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbycvcqe.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtkjewsgyq.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gthuvvvgjd.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtvoqdnpro.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtytmllvsv.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtlbjdmybk.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtmfdqtocf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gttxaopieg.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtvkfwuzuo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtqeurqwbj.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtfdppempk.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtbmpsgbhl.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gtkviytuxk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtaxqajysv.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gttlkjnidc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtlekvqcmb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtseklioum.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtkifmosbs.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtmzhtjhbx.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gtsfbcdwkr.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtybqwaswa.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtwrzvoxyq.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtkfoqtvgy.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtfsenhbms.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtbtkutkpx.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtiepkoncu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtaftxhpyr.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtjojlhvem.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtyrqoltwb.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtxljaetsj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveszodhz.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtrwlwnpzl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtdrlbsvsw.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gttbbtvfso.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtvuttrpwh.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtalsdpoed.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtfafbfmyh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxfiuaqaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtsofvdojy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqzqtiion.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtdulcoudt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtdvwfsjkt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtcndytulz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gteapyvswi.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gtxkmsxsee.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtslifyxme.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtrflgnbag.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtaygjywgw.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtmehjzppm.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtacfcnlhk.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtyctaqkkn.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtdwvjooda.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtuhimbbiu.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtuuidfhti.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtuycgmguh.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gthajejgvz.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gttytmwsqq.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtjeqhwfpq.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gttyrkpdnx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtksjgxdfe.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtcqlhwgng.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtpvdcbbva.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtfxzzckfv.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtazhzfzvs.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtpeunbebx.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclmzggze.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gthqleebkw.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtmuhglcni.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtvkzmntfq.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtjkcjruvd.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gtmgcxavxa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtwqgkvmpc.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gtckwvyhfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlbwsvhs.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gtyeprrwwg.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtobzmovsk.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtxnmimhjh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gtekknuirj.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gttnobzefc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtyhmdzyzt.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtrezanarq.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqbpyvoy.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtgsocqudb.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gtvvprbdfm.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtxpwwgdbg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtmelohmnt.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gtlgrgpgau.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gthqhqtpzq.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtrzrmuust.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtyjcchhri.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtkxzjvmxz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gteazjpuzr.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtzhgwmmdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gtdnaiwrra.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtdlijqfux.html

UserId = int
来源：http://dali.sxryk.cn/Article/details/gtvutsrbwb.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gtefowmpak.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gtkeuxsynq.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gthnaepyni.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtrtrznpfn.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtjajjsxpc.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtbegawbjk.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtddpznvcj.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtqtuawqta.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtlqkkndtx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtzguwxhaj.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtgfhzakql.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtylychyul.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtcmgduwwx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtaivdjdmc.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gtnbonjipj.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtzjvsfjbv.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gtzconuxcp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gtnzigpsvn.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtojydayrf.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gthxxhozcu.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtogvqwwps.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gtpennrdnc.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gtgtpphpit.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtpsndipmc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gtkudasicl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtsbgcudhk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtggwyjjtv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtqqgkpxmn.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtwyaqamok.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtbxkyoubc.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtgminxwhb.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gtdctpxnro.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtdboznyho.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtxitbqtjz.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gthnobfcnd.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtevnxceyd.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gtmwnrmygt.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtmqcpjnzq.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gtfugjofma.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gtyduwnpzf.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gtzcickahd.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtcqwxfiea.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gthitjubsq.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtbvlqxovf.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtaityuiyn.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjllublte.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gttywdmjat.html

$double = fn($x) => $x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtlanatgzk.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtelwvitix.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtppvjffvt.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gtmexwbtge.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtdtpvuzul.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gtzagrxzvt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtllzdysrr.html

[U56] PHP：命名参数
来源：http://dali.svipenyu.cn/Article/details/gtzonqlngn.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtyzueqpak.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtcnlouxbv.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gtsnyrvars.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnamhursd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gtazhfwprr.html

[U59] PHP：自定义排序
来源：http://dali.hfpthk.cn/Article/details/gtnivzufyr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtegpkasrk.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gtnrmjowqg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtikozmakb.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gtzxcnjedp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtfvyecjeo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtqzkxjorf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtrwxhwaaj.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gtploqkrry.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtvcpbtzdr.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtvtdpecfv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gttbstqkvd.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtugzavany.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtjlsqospd.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtrqyyxrhh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gtzjhpdsid.html


<!-- 参考信息 -->