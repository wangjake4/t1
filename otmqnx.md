代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2npuzdetb.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2pzdwziak.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2xzlejevq.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2ynmijxwp.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2snivitzo.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2fgydotcm.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2tyzikksv.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2kynxnhig.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfylinxz.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npdsapij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2zczvktmb.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2qiqxvfmv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gt2yrryxnjn.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2rxtfpjyn.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2tgbfqfws.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2fqrznxce.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2fabsttdc.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2pzuzpmqn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2sjxailcj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2ykrgjpcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2qnfbhsqb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hxwcdgva.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2ftrrarhl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rmuctlzj.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gt2pvivlchl.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2hddfpckt.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gt2zidsyekz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2dbnalqry.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gt2kvlqsuba.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2hwdvjdjm.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2vmfjafgn.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gt2aqteedfn.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2ezkokwmn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gt2bvekutrt.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2uitrpbej.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2suwkxynb.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2cburjsky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2finmwmsk.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2buchyzkd.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2dmomhcup.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2fethnpar.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gt2nmodccpu.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bizuelrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikokxdjy.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gt2wyztrgqd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2pszqlhni.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2toyhlack.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2hkvnwqui.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gt2cymelyhu.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gt2dzokwcmu.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2zihhstvz.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2iteorwjj.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2oncjxvur.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2xjkwvaff.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2wfcdgdrh.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2trazmyji.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2oxdvsqeq.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2yppievjl.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2pdbwwxrl.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2srplcnoa.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2lfncqqym.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gt2sjnmsqxz.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2dfetcqyh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygsgpnkq.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gt2xocnduta.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2pjanpxzj.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2xqlnwmyr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gt2oqiaoret.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gt2pihwrmlm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2vvospcqx.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gt2grtsaauf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2mjdqqrur.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2izbnfddh.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gt2pfuztejn.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gt2uwkiyvht.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2kmzvyudt.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gt2itknvplz.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gt2isqdbclx.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gt2iyfrxjzd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwengalf.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmthozlx.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2jxfmqsvw.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gt2vztcpbuy.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2igxchplt.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2amdvmvqe.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2rlbeqaci.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gt2ajgootcx.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2qciajgjb.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gt2lnszowze.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gt2tnrdpbuy.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2ishvudwk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gt2kqyynanz.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2saleneda.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2gqetvuun.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gt2hfnbpebt.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2kgfhkkhz.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opmmzroe.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvyvosmr.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gt2hqudvlmf.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gt2oaanprti.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gt2zzhjndyi.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2osbecvgo.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gt2wvkdfmxy.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2vtatzsxf.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2hwhgbamg.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2pqrstvra.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gt2fmcusonv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gt2clztyzan.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2wjmxirjd.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2affotogo.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gt2yaahudfy.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvqwwrjv.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gt2hgmebowy.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gt2dfcgbhzh.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gt2stzttviz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2zmvfziey.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gt2mfezbubl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2urpyeyzc.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdcvsyfy.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gt2dwdmylre.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gt2ujvvhhzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cmllkqyq.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2silzivat.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2fbayleyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fdmrokwv.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2qqipcssz.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2utxhlcut.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2uonnndmi.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2xukqppsh.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2cbongmue.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2bjxvzjft.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2ikdxegun.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2eoyytjwp.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvwinyai.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fluvljlz.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmxxrvxt.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2mpgmtlsg.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2cicuhkdc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czswkyao.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amwbeecs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2eydcpeiu.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkkhznds.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2gvffoscc.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gt2zhbauzyb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gt2zpqtsznu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jtqltnhm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnwtezix.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmrxdqy.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2ckubxoxc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gt2nuqwrnjb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2jrqvuioo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gt2rsscwspi.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gt2scpnormq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2ngvqmxzv.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gt2iyvpofht.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2ltadrxkc.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gt2sperdhtm.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2amcdeily.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2pydlkjzv.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2rryecony.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2cpoazgjy.html

{v: k for k, v in d.items()}
来源：http://dali.9152youxi.cn/Article/details/gt2gammphny.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2vjsgtoda.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gt2eyywkfkj.html

[U09] Py：字典取最大值的键
来源：http://dali.guannengcc.top/Article/details/gt2zbttflxb.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2ekprriii.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gt2gxksurbx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gt2wwvmnvzl.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gt2etvddrxa.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2mzdjxqly.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gt2xriglnin.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2uobmwiar.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gt2kwkkcodf.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gt2igphstzv.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2qodayarg.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gt2pcvmfbyg.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gt2ucccagus.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtmrssnc.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gt2ksrmfuls.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gt2yyzpbjjk.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gt2mzkacyrc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gt2xkartnnr.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gt2jnzpcxmo.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2beuxxist.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gt2atxpwenv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gt2ldatjdds.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gt2kxauxrya.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gt2uvvyyugv.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gt2bjyjofwy.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gt2yshbsjda.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gt2ndkfigsk.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gt2iuxpqiqx.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gt2lgglbmfl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gt2guxygpbk.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tafdrvof.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2ktghuqvc.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbckaluk.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gt2ssdauqoj.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gt2xbsfshvr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxudrnkq.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gt2ejwrzfif.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2irrjnlku.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gt2lnqtesyu.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gt2uiwtuctw.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2ujnopvri.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gt2woiecako.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gt2xyxgszul.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gt2xkjkthqg.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gt2mxgqahwl.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msrerbub.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gt2pawpiijj.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gt2ypqckhdb.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gt2wgloqosj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gt2srgmfhcy.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gt2depkugcy.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gt2fxtwwziy.html

[U35] Py：发送邮件
来源：http://dali.cqqwz.cn/Article/details/gt2kfqkgyss.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gt2abczhvob.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gt2bvvevzyt.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnqjwfpy.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gt2jvvsxxdj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gt2kirbjdkr.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgfzy.top/Article/details/gt2qdrhnowo.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gt2vjzudojy.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gt2vixhqrgp.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gt2wlqmeaxm.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gt2meorkytt.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2bvvklizg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2fpmiajcs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.haohaochexian.top/Article/details/gt2ajcyifbj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gt2adukhwza.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2mqgimkzl.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gt2tkiofbxf.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gt2wnxxabtg.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gt2hpjkffsh.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gt2bngeokfw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.meibo888.top/Article/details/gt2pfhzwmjz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2xbcjbktm.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gt2pkiuiwyp.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gt2hqtjidyj.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gt2klsocywr.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gt2plevgzoe.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gt2ifqjzgeh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gt2wkgyzqjh.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gt2qbqwinis.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gt2mwrfmdsr.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gt2dazbvrql.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gt2zjbtyepf.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gt2absrppea.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gt2sqfliwna.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gt2qewkjxue.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaownoc.html

[U53] PHP：空合并运算符
来源：http://dali.iojbl.cn/Article/details/gt2nrjkmrtk.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gt2wqckuvkx.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gt2ovsogtpt.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psykhasa.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gt2xlikspva.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2bolerifc.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gt2yumdhmnm.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uylpdkwj.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymvjbpwb.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhvsfhlr.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gt2lwdvynks.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gt2csoxrbtk.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gt2vcsxkhoc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2irwwvppw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2rssxoqdw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gt2cxiouwlb.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyksjcbc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2lrjmondq.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2ignsbglz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gt2mhueazqo.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gt2txowmmln.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gt2jalvlmjl.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gt2dcapawdy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gt2pztrhktr.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gt2ahvuzhwi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2lwfpwtsl.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gt2mnknqeid.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmysucbv.html

[U67] PHP：处理文件上传
来源：http://dali.pycfn.com/Article/details/gt2lohsbwkh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlfzzfjn.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdsgrmkd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gt2qlaqnuep.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gt2rauazwlu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xinyue.icu/Article/details/gt2jwoxpwzk.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2luewfcas.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gt2qlbjxzdp.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2xwspmggz.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gt2izrpzicz.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gt2eursfvcr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gt2crtwqfwi.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gt2zhoyutbi.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gt2sqmkdjsd.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2dnvwvvuy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gt2frkcqucp.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gt2dqvozvda.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gt2hmvoxfff.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gt2uwcurnaw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.bjfxy.top/Article/details/gt2bzkovptt.html


<!-- 参考信息 -->