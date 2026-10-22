代发 wailian999

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtxuhrvegx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtzoitbzwz.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtafsrcbnv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtikunxkpd.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gttoxtkgxj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtonhtdwtq.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtujuyoknu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngwunxql.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtlwvaranb.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtevqribyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtvcjkzbon.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtvctnlllf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtuexrnvzj.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtfqgkvbpr.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gtbqhofpvx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtzjchyghv.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtqonfqiej.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtplavyaly.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtbmbkvhnf.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtmnnxfkzq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtxnblltix.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtoqlzojor.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtpzuinlvh.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtxstxlzaf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlthxiuc.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtpyttazji.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtjufdiqzg.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtpulhokgb.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtbggrohxr.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtnshaenbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtncvzsxdn.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtuvdegepl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtdpvpgfnf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtljiuhzpi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtoandsgeq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgkbooljh.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gttzpoxcgl.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtlfxagern.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtkrzmckli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyctcbkzo.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtshzowehh.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtfqyslvcg.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtmzfobsbz.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtsvxinalg.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcghtxyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtkrwwkeip.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gthmhdswee.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtsmxusovv.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtxsjgvmht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gttaphvnxg.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtkricinvh.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtfqctvsdz.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gtnrkhgepz.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtblayibtn.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtjjltipvx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtoxvcapqs.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtnghdqeyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gtrfayntce.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtypvdvosb.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtumjywdht.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtqrdanubi.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gtcbxqxswu.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtqgjfgwlq.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtgmggkzle.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtlnmfwpyc.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtexxvqreg.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtosroqqhm.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtngbyjfqx.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtuidfwths.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gthscfqdkw.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtcnytxfec.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtswqicyks.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtswsxjddm.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gticmrjoph.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtmkrnlrrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtgsrlbwer.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtsdwwnawf.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtfnortyif.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtxsxpcrbe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtyucythzn.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtrvjyrokn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtwgvtkorb.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gthpzzqhll.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtoewceiqt.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtfcnavzux.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtyvbwzasx.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtoatcojdg.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtobrikzst.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtlomuroht.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtbqijzoxo.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gtfhldgedq.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtlpqjvwnk.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtmbroozsx.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtjprmfwlu.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtgieakayo.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtzcqudcjp.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtppemfcie.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtcirrvhus.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtrkitliab.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtzmxkbcqx.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwehxzwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtgpilyyou.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtzylcgqtp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvydltzzs.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwmwzctd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbydspnzz.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtnzebjzcf.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtozyixzbe.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtucoebbby.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtpbhigmgv.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtptdpzxdr.html

if x > 0 then print("正") end
来源：http://dali.yuanzhike.top/Article/details/gtargbtmul.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtqtuncksl.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtbnrcgfxt.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtblgqacne.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtwvxrxezp.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtbrdfqsjh.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtybgttaxt.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtutcmgxfq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtsbnguzmb.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtgacskiaw.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqhdwgpw.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtktpkrzat.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtsapnbhfz.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtzdobzrxn.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtznphkjst.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gtzflxnbxb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtelaaovqe.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtdovbtdjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gthebedsoj.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gthdgjqdei.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtzojvsqiz.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gteyzxjutn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtxumlkizj.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpoucqzkt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gtcopncvos.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqzrzigi.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrqevjzmr.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gthjlbbtro.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gtpdmmifex.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtctuykgne.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtzcbzmoov.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtiwbpqkyd.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtexkkudzn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gttypfjafj.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gtkxyiuoag.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjmlpnkb.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gtgoydkdmi.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtgcsgrikk.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtpavdudve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtobifbelt.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtxgrdmfqz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtpvltrwgo.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtazsmarxb.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtbmufqqtr.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtzgrtvdfx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gtitrxugdn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgdqcyqrw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtpbnpcgfa.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnuvwbadm.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtevjnmbrm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gthgxaeobj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtqgkzydgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtoquvrzro.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtwfksaxlq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtfckbrppu.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gthvfcepui.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtpjfsjcci.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtuieuwsef.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtazxrlvzm.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gttljpblqs.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtuzibhqny.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtlbnakvuu.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtnrxzceim.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtxzmfxldl.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gtmwipyoco.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gtioxupods.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddsyviqu.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolytlvqo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtfpdfyvrg.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtqjouejob.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtncfqxwil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtsajeehtc.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtaqawzttz.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtkvtqqaoy.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwuzppjc.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtfzilwfqe.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtejffeznl.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gtijuuvzil.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrffvzujx.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtjbuehquv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtejcmyopi.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gtpizrdooo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gtoabbchlm.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gtcewbcxtk.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtyrzpepnq.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gtdbvehcbt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtjzjtmoxe.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtegzqybjl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtgnkuuqii.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gteqntziwn.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtaxtdaqwc.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gtxplgvgrw.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtfenkuecd.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtnuicnexb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtmdlbkfqy.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtnjpolklr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtnhyfjtlc.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtkbfptdrx.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gthgkvrtwp.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtjozscbde.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsnrgxjk.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gtpsrobvin.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtlacxjwai.html

[U28] Py：类型别名
来源：http://dali.jyoumei.cn/Article/details/gtrpbeeplc.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtgnclktfy.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gtdwxidcuv.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtruuddlpa.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtlmeqlxtc.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gtbctbjwha.html

[U31] Py：单测
来源：http://dali.smart0.xyz/Article/details/gthnicdwfp.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtqifhfhvq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtoddcvute.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gtwhmedigm.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gtztohwnjq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gthpayxtvv.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gthhvixlba.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gtdpjdxacd.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtkzpbwojz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtlvedpalw.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgnpavxi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzvljywr.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gthytnocko.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gtdzoucjzb.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtprsebdes.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtmjzvvasm.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtfqukwbne.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gtfhonhfep.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtemohgmba.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizopyurs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtsgvwfepd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtvldzosrh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gtapekkdkd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gotoacloud.top/Article/details/gtscyynpoy.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtuaskfkat.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtszzwcazk.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcktclsu.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtqiatlixu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtpwnfavyb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtbyapipmu.html

[U46] PHP：可空类型
来源：http://dali.dianchejie.cn/Article/details/gtcsqzyphr.html

?string $name = null
来源：http://dali.wangshuangyany.cn/Article/details/gtqglzxqcq.html

[U47] PHP：联合类型
来源：http://dali.chenlongwang.top/Article/details/gtlucjuyxn.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gtmgqczefn.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gttnrrrryc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gtntomgjqm.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gtsbixtqnu.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gtojdrumnm.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gteakajgup.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtnjtqjtjw.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtpqnusfws.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtvciidanr.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmrzkjxo.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gtopwehvve.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gtaogqmczd.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtluxczyho.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtbyckhvkw.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtfpkjocei.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gtewoskptn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrbqfzvu.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtiycmlglq.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtmvvxrryl.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhbnqrfv.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gtmnwjsoic.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gtrlkhkwql.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtdylanj.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtiynrqckc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtevypxlne.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gtivpdkmhq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtxrmnkflx.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gtcmncvrar.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtopdmqjuh.html

[U62] PHP：日期对象
来源：http://dali.hongshengwenyu.top/Article/details/gtemahjvuf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtnpzcmuts.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtgyrsmcux.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aizwys.cn/Article/details/gtdopyccot.html

[U64] PHP：目录遍历
来源：http://dali.sufxvd.cn/Article/details/gtsastkgos.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtjxevubdk.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtpewivget.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gtpjamgptc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewhaibev.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtnmoprmac.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gtpvnnimcz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamharoie.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gtewfinfrn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtuodgjntt.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gtdzghydyf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgbwnjlj.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtjqzoloeb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtcqpiidtj.html


<!-- 参考信息 -->