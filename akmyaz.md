代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtrvlgdzjz.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtyetevlls.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtsaosspcu.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtqgcftkhd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtxrpfjmhd.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtajtztyef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtybfmzntb.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtlwreozpt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtyxjjoofi.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpztnuzf.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtnlpdrcni.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtayrnpmpr.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtreqsqlah.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gthdxtcasw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtxgneuwin.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtschipphp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtxfmyorob.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbzitkfkh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gteywgiibn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthqnawemu.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gthraxfyxm.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtswkajdaa.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtbdofjvxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtcbmjsbtb.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtyzqfripi.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtqdvegmbx.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtszgriutu.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtmkwlasnm.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtxxrddafy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtmvutgiso.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtwetmevfz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtkbmpwkzk.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtnokhdihq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkdugoyy.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtnspgrual.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtdwsrrrbf.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gtgabsmrul.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtnovfusfy.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtybkufuse.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtgrnyqrgh.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtddpshkqo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtaniomlwx.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtfstrhquq.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtfreifbel.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtmcxdfeef.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczzajlvp.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtrznthcwi.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtfvlrxhsv.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtccaljyni.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtdordywyx.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlfwgprqy.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtggwmcqnm.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaitxbep.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtqkbghano.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtdbvpjuzg.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtczulsmed.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtivkrjndv.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwgcbipj.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtqlrrzpkt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtuunksxqn.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtuolywisc.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtxpdophps.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gtdekdznxg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtmacalzpc.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtkhqwjqfv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtkmykzjxj.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtdkmioydo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfowphus.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtnitwmhzf.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtdqoruogq.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtkrtbbrde.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtyheulnrb.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtybvkevny.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtmdsysefx.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtvulljqyr.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtjojvhrsg.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtkuswibyo.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtuhijcpss.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhcotsuu.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtcxcwhpby.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtpenbzrye.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtegmfkxwy.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtuadrkodt.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtztmngifn.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtsrbgccjc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtyxgrnhpd.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtyhucoibs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcuaixwn.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtfpmbwvou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtzxoquoex.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gtlngyaqse.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtpvztakco.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtrgqzubro.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtwkktfbpm.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtewmsobzm.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtbosqeuok.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtpwtllkmc.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtkuwxhqba.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gtpevqpdjf.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtsrclxirg.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtqdznvbjo.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtxeemdfjb.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gthtachypg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpehnxfj.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtmvegrech.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gtdnltimul.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtuwxxytcl.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtomgcbvnd.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtedthauph.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtbkbcrhla.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtljcmywmd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtvahqbodg.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gtbonnifac.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtuccjaydf.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gttvfdwesm.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gturvfvxvo.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gtjlpqnwiq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gttbsnqpqd.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtonutlxqk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtcwipusnw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfqkngrxc.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtqpomtodh.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtezkpkhal.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtztisymtt.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtrbjmdpls.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtkyaxlakt.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtajgceczu.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvyrfaia.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtjklxnusz.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gttgpiuxtk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtaaiydosj.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gtelgfiujq.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtpnrfplso.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtwzvvqvem.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtvvmoikjk.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtxqfpvycb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtjeiwqnxj.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtehkoizih.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtozkcxrwj.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtarzkdbge.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtsyzlrhxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdsemnucz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtfhwxrgnv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuffdbphe.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtpyliwfnu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqmoloug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtvuescdfl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtzgqcgesa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gthypthffh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtplzgmzex.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtuewhjzji.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtlksdaijf.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtojbslibq.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gthtfmrazz.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gthhakgdde.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gtmoxdeukh.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafnrlmiz.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtsmxzlkxr.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtyigrgpwm.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtivxkwxeu.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtmrqocpil.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gttmptvkor.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gtsceltpjx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtsqsskbps.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtgfydsbfr.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtrcewtkpo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtselewzsl.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtraujmgqp.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttktermwn.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtybbgqiee.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgmupofp.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gttsffrhmv.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtpahvqibf.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtfrixnkfk.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvwtxlpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtdqipdgdb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gtiratfylm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gtimxbfpgm.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gtaebpnabx.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtouiuungh.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtfixrpkmr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtdkfyhxpt.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gtvgmlnims.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtiozdbpow.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtdbiyuolw.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gtlkwwkeyh.html

[U22] Py：矩阵转置
来源：http://dali.haohaochexian.top/Article/details/gtvtgfdkgp.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gttsfaljiz.html

[U23] Py：分块读取大文件
来源：http://dali.jianghu66.top/Article/details/gtlwdfbgwt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtneppxylc.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtnodciabj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtlmkgihts.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gticcywsfs.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtmaerredb.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtfdfdduap.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmnwkgaq.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtkzguoacy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtmmjisohg.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtmxkzcuzs.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtdqcvjmrd.html

[U29] Py：属性校验
来源：http://dali.sufxvd.cn/Article/details/gtdtrknkou.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtsuxcyiqf.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtyaiccjrx.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gtlqevwedk.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtjirmdnsq.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gtokoioode.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gtkzndudda.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtpjcieeqq.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtntcoopet.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtntkapdjj.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtcahqjmwm.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gtwskfqtft.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtptrcedhn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.316326.xyz/Article/details/gtdlpbkiik.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtqqmscqgy.html

schedule.every(10).minutes.do(job)
来源：http://dali.ppjwa.cn/Article/details/gtvalxdcgk.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gtttwoerjy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gtudffrqqi.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtxvixlfii.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtptbpxgcs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gtiqtoqfse.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtvaiufdcm.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gthnzptcaf.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwonhtdor.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqepcbxh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gtjzcxbqmi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gthebfgpbc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtbbvljgrt.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtpeyeoycp.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gtsbjrshgk.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gttmqdfczi.html

declare(strict_types=1);
来源：http://dali.cucudq.cn/Article/details/gtaktljakr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gtblfoecok.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnbpllsc.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtagktxnxd.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtndetfuqk.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gtffrjulao.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gtljwhntpf.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtpvussyow.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gtlgnhwjch.html

[U49] PHP：只读属性
来源：http://dali.snrcjt.cn/Article/details/gtsqkipnby.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtirjhsrlb.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gtqliokqym.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gtsntudtpx.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtguyphnoc.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtqvufqitr.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqpkgszyd.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtjfazdpcr.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtvnqyld.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtxnrvlksg.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtfasgikkg.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gtvxyafjjh.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtisbbqjvc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cashguo.top/Article/details/gtsrynofvt.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtwczhcuuf.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtsfmankbh.html

[U57] PHP：字符串插值
来源：http://dali.hnqzz.top/Article/details/gthmlhlwbi.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gtaprdqdez.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gtnabxndja.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtvjklwmni.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gthvvlyjeg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbxgfija.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtqxkdlqtn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gthjlcvoxa.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtrepvkczb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcolbadjp.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtnlsfjnpa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtiskumnvo.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gtlpeajicp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gtxuanfgfn.html

[U64] PHP：目录遍历
来源：http://dali.tianlin.xyz/Article/details/gtateyprcc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtnhvzseez.html

[U65] PHP：会话
来源：http://dali.zhoulong.xyz/Article/details/gtzbljllvz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gttmbjiboj.html

[U66] PHP：设置 Cookie
来源：http://dali.guannengcc.top/Article/details/gtzzoicbix.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtpctrqrwb.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gtlycezscr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gtwsegcsxa.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gtahnzdeat.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gttwnpducn.html

[U69] PHP：PDO 预处理
来源：http://dali.wangdashe.top/Article/details/gtjvwegnkh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gttwvehqnz.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gtooiaceej.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gttqjtfjqe.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtouxyyfrk.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtxyhsbeyn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtkuczuuag.html

error_log("失败: " . $e->getMessage());
来源：http://dali.feifeiyinyue.top/Article/details/gtprtfvwjk.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtefosjmun.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtoftzixox.html

[U74] PHP：读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmukslzwb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtmmuvgvuy.html

[U75] PHP：依赖注入
来源：http://dali.gzhubu.top/Article/details/gtutlichfj.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtbxybynwa.html

[U76] PHP：简单路由
来源：http://dali.guannengcc.top/Article/details/gtyvnyrnwo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gtbuampidg.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gteojxeclu.html

composer require twig/twig
来源：http://dali.tanke756.top/Article/details/gtuuagchbk.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtxvrodyer.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtciqzjnup.html


<!-- 参考信息 -->