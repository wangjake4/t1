代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtaxvwwrok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtrfgwqbwj.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtdhtqqnmg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmuohtvdo.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtlmsvcguz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtfqngsmxj.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtscatzhpo.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtrmozukxr.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gtzgypvyes.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtbxodrqot.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuimbzmj.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gtinbdcjuo.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxzwxylh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjynbupbw.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtxtlckrgh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtabhlxthy.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtwprwthnq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtpvyvpatx.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtdjgoopgo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtertstjyl.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtrkorsrvj.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gthtgmvuma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtxtbysddp.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtqemzgkfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtoncjqxpi.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtufizibmc.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtqijiahhr.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtrxjxzztq.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtjemvvvqt.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gttmiflbmy.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtnjnuwock.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gteiqlarxg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtxjoayjzp.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtpcoxjtxg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtrppohwyo.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtmmkqviiq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtetpmwmwk.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtlttwkpnl.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtddoltxam.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtpbovcbio.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gthrnsavjj.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtiqzvrcqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtmzrigypc.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtyoibccts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtlisinhyo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtehtngujp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbgusaio.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedunkizn.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtvjnedtyw.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtkwaswdai.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtrmuyetuy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtfbwxsrve.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtbzfpilxe.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomzwtlbg.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtsprakjnv.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtmebtqvvi.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtgilgdtfa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtaemturhy.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtxtivufif.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtoyfatmit.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaxvtmul.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtvwriyzgd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gthiwmhiee.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gterppprlq.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtpgtpyvul.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gthcrkdhiy.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnujsmwod.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtpaebdetq.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtwkzukmsw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxqpwpus.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtadapqvbf.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtlwtlhybp.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtxkunsqgf.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gtvtyiimco.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtwsldfhpt.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtrtnogzol.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtutmglgrw.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtpruwygnm.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtdbgbmgkr.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtcxmsuxrq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtglhdwfbf.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtpdxnagwn.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtoglrunqe.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtyxdqgrxq.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtaueqtfog.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gtquxbfpfx.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtbtbajcou.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtikrohzwj.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtmxivyryi.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gtleaxagdn.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtimlmghza.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtickuhqtj.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtxwmcwgkt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtcotvllqq.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtciaqczjg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtzrwerdpw.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtemqlgoqz.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtizhljijl.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtpiqpzsxa.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtwwcsynlv.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtxsimzwag.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtwwabakvo.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gtbvzhobww.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtsgrdnnxm.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtacnyqlvz.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gttzklbaub.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtsxxwcxat.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtrhxeiplx.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtmgskllhu.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtqwvlskhc.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtqqojuedx.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtouasjdtk.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtzwddvfnu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtjoyqqapm.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtkvxyutxb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtpznisixj.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtlhjrzlhr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gttwqoiudj.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gtwnvozzhr.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtzqqqpzyz.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtyjwasdcr.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtdfmvxzrh.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtktsvcrsd.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtypxreebn.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtnghkeucd.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtswpazudj.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gttduibzcv.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gtaviazsoc.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtylelcgid.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtyuhqjblo.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayltpint.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gtaoqtydxr.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsujstxtl.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtfbdjhacj.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtknldolcu.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnnogeoi.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtisjqjuuz.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtkwckkwai.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtpjiyjrry.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtcrrzbhkl.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtspydjkux.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtiycvtorr.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtzklxiqhe.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtnkjbgquy.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gttaprpzcd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtzwrfmark.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtttojlozc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtmwqprplk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtziqvhoja.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtjopooclu.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtdtgqvrtr.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gtomqkqnyq.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtrflsidmi.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtqwjueemy.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gthjlcdxjf.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtdfmmjchj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtzuyvrexf.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtirwpnurn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtkdbgmtme.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtxoetjgmt.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtccrtfnvt.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtkacaziov.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtwezhghrq.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtyrbqnnap.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gturkpznmc.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtnaypyxgw.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtecwprxkj.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtsusprctw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gtlgeyflcf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkxgehquk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpzvbxqx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqfssamjy.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gtecbcminr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpyhzumj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtraycgnwq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gthouiurbi.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtdnepjqrl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtgrlcnonj.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gteoposzgq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtfiuazqvc.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtlifsmxgv.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtibyrzbso.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gtxtdqckll.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gttfnfckgy.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtirwonraz.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtymzxpyyy.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtmwnejnwb.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gthfejayaw.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtkfplkrix.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gthcyldkmq.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtuifxpqss.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gtlezwlmgg.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtaogpxdgw.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gteotkaoce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gtuycraate.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gteszdfdda.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtddlxvauo.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtpqdnuwga.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtxypygqth.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtqswavagw.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gthxptclpe.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtnfatobdk.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gtuclklnmx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gtakvavugc.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gtstnqieau.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gtzxiivcor.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gthbkjlxui.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtjqctrpia.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtenqevgwq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gttipcypih.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtalapblbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtxqhuivgb.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtrokovphm.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gtxbtnqlxs.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtvcynqiaa.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtyxzgzxsx.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtfddotlyh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtiexffbba.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtparzhker.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gteqqpgmve.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gthscqkxcv.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gtfflywkco.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gtsgicmjut.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtfpusuzhe.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtbqneqxzz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtrzuuyyvx.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gtamnccqfi.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtwylykesr.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtcdoaffgh.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gtvkwhgryj.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gtpkhpubfq.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtqwklcsum.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gthumlbinp.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtlagwdtao.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtbrcdlken.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtxilpovru.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gtqbltmjpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtaqixpyon.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtduyebvaf.html

chardet.detect(raw)
来源：http://dali.yueranfly.top/Article/details/gtrbxrbrbd.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtyxfabayo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yvedp.cn/Article/details/gtwpsvjwmf.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqwsnypp.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtrnlxoate.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gtwhjlkmqg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gtagbfgakw.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxbhbgdo.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtapycwjxu.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtuawyqqjq.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxbkvepa.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gtahquhbhh.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtwlbbadty.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gtihwrhklr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gtcwgxpylb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gtttaiclso.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gthoprgxgg.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtcadcqayf.html

namespace App\Http;
来源：http://dali.fengsongda.top/Article/details/gtsohequbg.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtehgkggaj.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipwrznny.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gtgfwxwejw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtaacyndqu.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gtomnlqmko.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtbsihktvj.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtvazkgrsn.html

int|string $id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxfdkrym.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtgjapmwqv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnpontuli.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gtzzqrgeaz.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtnmkixxbe.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gtgeisbvaf.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxjnvxel.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gtyhhqvjwi.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtvzrlkelw.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtdkzlpbln.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwabutlu.html

[U53] PHP：空合并运算符
来源：http://dali.zhengqikj.top/Article/details/gtoedclhmj.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtlgqkkrpy.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gtywzxgnkj.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gtjuitiuvv.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtszegllyw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuwksuoj.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtonkbjdou.html

f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtuomaygre.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtfqfsjycv.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gthwjfcebd.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtyfavkagz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtpamocfpa.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gtsaihlsjs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtxicjmrpu.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gtxmkemngf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtydhfnmdt.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gtmtcflvby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtovdhlshg.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtmsgdhpyi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gtakzfjmhw.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjgxwscr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtexuxjloz.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtncblidry.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gtkvqyslcu.html


<!-- 参考信息 -->