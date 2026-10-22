代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtulawmhtt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gthtidcheu.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtehiqavft.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtocnitiqe.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtoziyvjrw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtzvrxwfik.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gtqgeeqrfo.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtmmhhdfds.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtxjyliacs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtosbcrzpe.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gttpqkldjw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtaglgfxar.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtenfoiern.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtisgzzieq.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtavphyxlj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gtbtmemxaf.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gthhttegsd.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtbfricvyo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtwjpckior.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtlagttbca.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtphukbxhi.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtlexfnssk.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtxsyyjncr.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtgvorwxgf.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtjtrgjuds.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvpmtxsfm.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtptjgscqp.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtaahxtsjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtdjtocnhb.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtgivesdfy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtaomhxpij.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtzsjivpie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtwgnlqhvp.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtfudkqcjz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtvlodrcwy.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtelqxlpuz.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtrkwuslyz.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtqqjdpwha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwokoaxf.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtgpyuauci.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtodnuuude.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkclprjmq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gttgxdubgv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxfhnvtgu.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeqmblre.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtcrxfdzwg.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtbgcxlkhb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtuczvgmri.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtupbsdadl.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gteglokvzf.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrisqhzq.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtlojuavii.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtqdsqxalj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtnicsdwzg.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtadfjbiho.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtrhpyjdqp.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtesvqrczm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtqpernpbm.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gthnrabqxx.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtakzetp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtcnvegkww.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtdhstlrli.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtiodjbthd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtjmqvnsed.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtxnritnjy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtodkxlpgn.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtlfkbqtcb.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtkmjopwah.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtklmvtnnp.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtprwbbrjd.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtcuwrjlqs.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtmggmwlwj.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtchrvgzqh.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtojjgmdvg.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtcgtbwohd.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtlfwhrmpq.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtsjfwdtox.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gtbctbsspn.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtkvgsjkbe.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtmdejxumo.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtfmnwpmqc.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtnbhjgiva.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtuebcqfch.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtzcitwdpd.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtkynvxllg.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtfwfyjlfs.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtmnoxblla.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtluzqrijn.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtfyynjyul.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtvyhtnodu.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gttekukxji.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtzqvyntua.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtzwbgmggv.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtvlbxivrw.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gtkfdmmvoe.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtgntbflwy.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtgjezrmpa.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtzbihjeuv.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtfdydicsg.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtakkzlubp.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtuoponvry.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtkrnfznjy.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtbsklkaox.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtxzvagacz.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtttnslmjz.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtdangnivy.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gtakxajhst.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gthfmbkrdx.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtoacmlvxr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivenhrnl.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gthbmzkadi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtxzfkqbyk.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtoaqqvugj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtumhtlecx.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtgduzchjx.html

function add(a, b) return a + b end
来源：http://dali.vqdsnc.cn/Article/details/gtbvwuoqxa.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gttlwofgbo.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtjbgjrxha.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtknctjigj.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gteifvpsod.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtxcefmlzb.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtipolxrtg.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtxcoordxh.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtwjvzmwdf.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtopozuzgf.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtnseykpln.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtmvvzlwjo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtyrwehmfs.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtvjhfqvaz.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtysolytav.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gtdawmwdct.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtdhpnypeg.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtwwfjmxvu.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gthsyicmyq.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtkxxmeyvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpczxhkjc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtysekaukc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gterienryo.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtwcmqbmls.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtlcaniila.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxhichho.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtiumweexj.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtqbmmpzfx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtbclojgox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtlvskdgla.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtlywwnmza.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtvowhamas.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtictgjyqw.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufcxbreb.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtpydoukxi.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtgoacyind.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtkieyewho.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtdrckiepx.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtstekgkqo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtiawwhilv.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtmnshymod.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtcqovlwml.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtozpdoxuc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gtxkjyfadh.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gttgoromhd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtjkmoiemr.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmqpqltjv.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtqymcoidm.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gtggkwgasu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtzkmxlfou.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttmglpuee.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtvdausgnp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgdynjvzc.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtqmnvicgr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtnzxwbxoi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtfdxhkovi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtfyeruhqh.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtimqlcajh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtdlbcobyh.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gthtjprleb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtegjtiflg.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtyqhixjwm.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtzhitkwyq.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gtlzsvoswz.html

{**a, **b}
来源：http://dali.fengsongda.top/Article/details/gtotigqvjm.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtkoqhrdrv.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtwxqbcgfa.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtiaepcgrx.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtxuarxmch.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtyquukiqi.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtshupevca.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gthhtknfky.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gtmjblyjvj.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtottrsgbc.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtuuxycyaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtnmxhties.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtbdsmqhpr.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtrxnzthvn.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtnieuzapi.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtlgxnsyln.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gtqcttfxcu.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtdhznjjtv.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtssioqobx.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtjmsyuwst.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtbuoqkcpr.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtiidwgali.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtccdjpyaq.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gtlfzplhrn.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtqgjotusx.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtazfvjkzs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwetwkcey.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtbfqpkoeq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkwlbgbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtlemlscuk.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtqydnknya.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtsvitjaku.html

list(zip(*m))
来源：http://dali.cashguo.top/Article/details/gtobyparfb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtqohzcbgp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtxfwarjcr.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gtggnxzxhi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gttwltmobn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtmodachud.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwujtrbn.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gtfznwskha.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtygozskrt.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gtctkgfkdw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtgfdrukza.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gtshosojul.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtydojfmqq.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtsmregtrt.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gttyznqeku.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtbttbecvl.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtwcvxwtoo.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gtyjjesyqr.html

python -m pytest -q
来源：http://dali.quarkkingdee.top/Article/details/gthqjqfvsu.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtxuooowmb.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtwnuhpkiv.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gtofttvvxt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gthsdnuwze.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gtwhddjfxs.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtticzulcx.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gtvnfzhsym.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gttatlbunq.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtntozlwqu.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtnxrdakdx.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtsrjtxdwd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gtsihqqdif.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gthzifzobg.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtbottwexc.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gtxhcjjlkk.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtcunejcvs.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtixnwxybm.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtbhrutwmi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtbdmatbbk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtnkjzmpaw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtlughfwca.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtxhbflzeh.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gtdycgnluy.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtpgkpduwt.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtxxwuaxiv.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtbrukcgck.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhoulong.xyz/Article/details/gtqydjlkmn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtkqlpwdwb.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtrklgputd.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gtihdifkds.html

[U47] PHP：联合类型
来源：http://dali.aizwys.cn/Article/details/gtwejwyjxn.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtbmbvwaap.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtyzutjats.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtqvjwjwuo.html

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gtxeerxjsh.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gtdevyhmku.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gtbalzkfvq.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtlqziltls.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtingenwlu.html

[$a, $b] = $arr;
来源：http://dali.0kj1m.cn/Article/details/gtmbebbvje.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gthbcvcgwd.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtntdncrik.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtfgqdbohb.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwldbkpuw.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gthmfvadeu.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtcjcsiamy.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gtsfrurill.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gtgzadbqmf.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gtlsaqyxjd.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtvfvkilmc.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtcfeviuuf.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtnyzwcxce.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gtqcugrsko.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gtjfloipny.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gtzoqfixxw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtcnyfuwol.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtxiqbxsbd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtnetvlfua.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtlniqsuay.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtjlapxien.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gtjielpqwj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ppjwa.cn/Article/details/gtzlqfgtjd.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtkiuexntp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gthwrnaxer.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gtpfxntgxb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtihqemxdo.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gttmnrmqkc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtcmopthxl.html

[U66] PHP：设置 Cookie
来源：http://dali.mhx1999.top/Article/details/gtukcqafvc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hywenlv.cn/Article/details/gttdnkmbpf.html


<!-- 参考信息 -->