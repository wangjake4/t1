代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtyzmsnxlv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtqkinxpxf.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gthdfzlepw.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtekjsknxd.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gttkgwwjpd.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gterbdwfrl.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtdsveomqb.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtjwyzwhyo.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtilrnkdcw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtionsxkkb.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtkxtvowqh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtlufwsfdt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvlkgkdg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkeesnrm.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvodptex.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtqupjpcuh.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtmghamsgt.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtduaiplyj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtsoabcyfh.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtakhmdmhz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtsxutudvf.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtkdyfmrzu.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtlwknnjyc.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtftzlosvk.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtcoayhhgr.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtztswcloi.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtwrqaqalo.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtssnvunma.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtevwpfmlj.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnxojbeu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtkvqqahha.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtrhmnooem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gtjijpxtrg.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtrcmnuxkg.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtqljkfdpd.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtryagzqvp.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtnshueflq.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtyirpaaot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtdtlmhldr.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtzwgihelb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtrbabeptd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdwrufrkr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtrpqrhakj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnmgphjls.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gthxgxxxfh.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtsvgxbwwn.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtjgjadegs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gtwkbdpqrr.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtjqusgkly.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtiszjcihw.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtxurrbjwc.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtmnnpbiaj.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtdglpayze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtnflguoth.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gteiyuvorz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtoglodqat.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtugxucnew.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtmonwyjrd.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtqzsbyowq.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtdwcogzaf.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtmyoqiaib.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtssmfclet.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtxofrdgqd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtzxyruogk.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtgkfoujjm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gthecqsezv.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtbscaedzt.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvmmtcgrb.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtsaisgtsi.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtkarlyvcx.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtdccpahgi.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtblkzoxhq.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtmxqjsunv.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtqpknugzq.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtfgyjzsir.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtcfcumeqy.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtawcfeywo.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtrkgbyvgz.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtrxkfeooc.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtindewoig.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxwomiip.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtxbyuxvwz.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtqrmskmne.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gtsurqgcyc.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtqlmahwxl.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjfoybav.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtqlhyybtn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gttpxkepga.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtlbwlzjzz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtbsppmxvj.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtlwxmpetn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtjbzrzfyl.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gtqlwfyerd.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtarqgnhsh.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtektehmpi.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gthflrmkrz.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtnyzmcioz.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtzoxibkfw.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtziapzghs.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gttrzmquzj.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtuoxcbkox.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtztojfelx.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtitfmmbej.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtsclxyllz.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtwxbwowym.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtjmtahdfn.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofwpjkfg.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtdqjegxea.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtnckypgrz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtijysfxpv.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtasnobrfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gtbbrgiuzk.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gttnhokbdh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtdmfrnqxw.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtbpiobsgy.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtnpiigqun.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtxnljyolo.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtalvwtecr.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtqdhviwnc.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtdvfvpbxz.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtvgeegtaj.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcqxcumx.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjjxmywl.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtjpevikrg.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gttbweytyu.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtafhxagka.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtnobxunzo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtzrgpzznt.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtxflorxoy.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtaeorpleg.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtoiwjgdwy.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbwrvjqio.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gtztynuqrb.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtcqphpdpx.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtpqeuuvkm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtmgmuddcu.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtkjsbhlqm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtogtklaxj.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtjzhutkpa.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gtdlpnyipn.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtfladluam.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtrkibjvtp.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtbfylhbqq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtlpncvicl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtkdoyaqea.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtwfyahvcb.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtfmjrkpyn.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtxotdvwyy.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxzkqba.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gteoysieqz.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gthavksqpb.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtdagjsftt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtnfzqlqul.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtblgexeae.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtpcjulugx.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtshczwwef.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtmauylhvi.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtziaiyvbn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtrvwclcxf.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtvxxjunmx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtovixcjwd.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtgqdtfdcb.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtuxejqcxc.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtbiwcmtqr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gtusboqoet.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaflquxko.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotpsmmzg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtggcrofkz.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtebctmtdn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gteslkunzz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gtsnqjvdpl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtcvpwvwhj.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjsdobbt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtbrivnznw.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtoxrjizor.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtuvlpltep.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtkbpiilds.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtyxftur.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtxitepwuq.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtguuhgnzy.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtafkdjvtn.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtpysnpdcv.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtevwvrqvd.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtacivwiyf.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtjkdkvmfn.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtyvvwsuhm.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtelvrkeqz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtscbkvluv.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gthchbwhlx.html

(x * 2 for x in arr)
来源：http://dali.meibo888.top/Article/details/gtfkvvsdqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gteshavtoh.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtqdoqnysu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtqzywgbsa.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gttufnodgn.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gtpfdaqprh.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtfzdetlju.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtepsjpzzs.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gttywzrrcd.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gthewhwcqz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtunqsiewf.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtvnqdllgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtomfhppmv.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gtpjuiskbk.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtdbzidyos.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtllhtaidx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtdulvmudw.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtnnlagjdv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gthuuarqua.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtsvxqhsgv.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gtclwxnakk.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtoiikgwgy.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtdevtoets.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbdxcfxj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtlzyopdsc.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtbwdnszaj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtotqkhidw.html

[U25] Py：CSV 按字典读
来源：http://dali.hfpthk.cn/Article/details/gtucnqonmt.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gttogdtcqm.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtogzbbleq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtlacznacf.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtfyspirmb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtzkpenlmn.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gtkyhuwrfa.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtbzkdexbj.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtnhyhtonw.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gttvukqtvw.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtgoemzfde.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gtmkwxvgqe.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtvolkvzdg.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtxuckeqhq.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gtpreozwxz.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtbngucqib.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtcqdempsr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtxlochuye.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gttjboywxu.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdchqohb.html

[U35] Py：发送邮件
来源：http://dali.hfpthk.cn/Article/details/gtwtdlqteb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtghycqqlb.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gtfdvxciay.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtxucgkhsc.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtnefyrefd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gtsdikwkwq.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmumsznvg.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gthqwebzqf.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtfxsckatz.html

sys.stdout.isatty()
来源：http://dali.ybcxt.top/Article/details/gtjpoonalu.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtucgnwfgg.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtqxujuzqx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gttplwthif.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtbmuoxibv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtfztnrclk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenlongwang.top/Article/details/gtiqfrfmqg.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gtplqukgmj.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gtduuixgdy.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtjfisnafc.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtzsnsaayw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gtvnkcpawu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtivicitny.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtefewgcmg.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtnbatdnhu.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gtqdcqxmzb.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gtrgyyeeoc.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtuovwbziz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvvvrjyms.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gtxsncuesz.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrezjtjpr.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gtuvjrxxlf.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gtndmblemv.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gtilvjbbqo.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gtvyezgytk.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbgpbhwr.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwtcppkc.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtfxodtmhx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtnnntayuh.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gtpzyztpdz.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtvyooqpwb.html

[U55] PHP：match 表达式
来源：http://dali.hammf.cn/Article/details/gtxmxbgtwp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtqedvngpu.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gthpjjrjmj.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtlduvxpyl.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtmxkunhpp.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtzpnwwwgs.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtqcxgjvtn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtbrckvqtj.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gtpitcrarg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtveedggkr.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtkiujwsju.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gtwftssabg.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygzilloe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvwhzrml.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtidsjaeoy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gtvvegwmbv.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gtyyypxntw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gttrixextb.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gttmipjhhf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcrsnxcl.html

[U65] PHP：会话
来源：http://dali.sufxvd.cn/Article/details/gtxcbbwhdg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.havefunace.top/Article/details/gtyjmdsryb.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gtuvglyzfe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guannengcc.top/Article/details/gtyewpzrgn.html


<!-- 参考信息 -->