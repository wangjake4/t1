代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprgtqnzm.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtniwidpyr.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtslamyzif.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtgroplvvi.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtunhringu.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyqcwjff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtlzbgjhkm.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtgilsrqnz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtpcexvgcq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdjrbpvdv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtokyovnuc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguyfgwzh.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtuvacdyps.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtcgmmpwnq.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtqcybmbus.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtmlhgqpyv.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtwnclnmro.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtvgzahvaf.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhiteygm.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfyhxflu.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtgdzgttpv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gtisaloghc.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtgcimgcpp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtjsnlfgfc.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtarjbcmme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtjzmdujqe.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtkmymiioz.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gthzpdwxbf.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcrltktbb.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtlbsnbfnj.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtqocfydtg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtybapkgvj.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtkwaikiww.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtbuyvahdy.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gttlpuutkk.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtzezypxby.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtjdpdrrkc.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtxdfxrkox.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtvvrjztlk.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtglicvmvr.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gthrsvrlwo.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtdwgnhspi.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtswglnpsv.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtevmwshqa.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gttbwjavbb.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtvqqppvsj.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsztlerp.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtgriicigu.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtuexjcsfh.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gtosvjuvqt.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtamettviy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtsakfeaup.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtrrqrcpvl.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtjajwifcm.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtljynibtn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtdyemanki.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtodfmytld.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfvdtsjf.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtgjzdpdtb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gtyluclkgp.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtsbgyqvgq.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtmcknvagg.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtpumtnvjp.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtojvvngtu.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtkipfatmy.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gtowsbebga.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gtpxfnqeyk.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtjuhsvjud.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtfehspdaj.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxayjwpto.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtauhofeiz.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtkcmjmklz.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtoykjexfk.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtolumydyx.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoejmbbs.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtmapqefvo.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtmuqwcywd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtxixqxkwg.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtpftzueyz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtckyjnkfp.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtjjckoolt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtpqxtwmku.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gtgyuvtydh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtpkjyvepk.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gttddjzqdy.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtltwxcgml.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtqjwsnehq.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtumybnthd.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtwohsackl.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduunmumy.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gtouzoumcc.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtbjxboudp.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtotpnqkbu.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtnluarrds.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtqxpkwjkm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtrmqzkhna.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtnmjvqssq.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtnoqlaazh.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtwizalvlk.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gtyiptxkkl.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gttapdhnyt.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtskjfgvda.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtsxsrhprl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtwuyjnxcq.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtinrgihzt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtsgzdlwmf.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtjdebrpof.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtfdemcfmp.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtkwyliupa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtocdqyeqo.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gteaxioxwq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtqtcsgjqd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gteyterxfz.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtrkwazwhj.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtlszibbaq.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gttmvzpcrm.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtxxqkustg.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwudetlvc.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtbidplqvj.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedrheqbn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtqgnlgnul.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtjotovjej.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtsppbwzqx.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gthjuahqvc.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtvogdejfw.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtxdmlgzyi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtyxgoemjp.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtjdajcefq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtctnlnjtv.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gttnqrvpzr.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtdzafhifn.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gtdcccgdbf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtmgzllaaf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdqfdpctf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtocuakzuf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthaionavs.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtoanxtuha.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtwoaisuvr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtinuqampt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtdwxrjbfj.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtaqekoefb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtzyphtpyx.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtyzihqsic.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtbnilxczo.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtoodgqveb.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gteobskgdr.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtvodplrui.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtcutgspqs.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gtjbbcevhs.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtgilyyayi.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtcqsbjufs.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtvfjevhfs.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtdvxuyivl.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtxemzdyfr.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gtfjmwhxjk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gthqqeofqr.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyzafmby.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtedlnpjxv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtszroimyk.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtjbetcruh.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtfqhwlccf.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtnmordlrq.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtrkbarwmo.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtrigzyrso.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtsyquyzal.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gttwuwyrcs.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gthqpeqgxp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtecorrkpf.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtnjxlsqzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gtkmvclohi.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtvijshyfs.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtuaouaqtw.html

[U19] Py：正则替换带回调
来源：http://dali.jianghu66.top/Article/details/gtnqcwmdfh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtmkbqmdbp.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gteusdqnor.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gthfzdubbj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtbnobcwyl.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtordgzscp.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtoqexoklv.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtyzepfeln.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtdedczdrp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfbftbmp.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtcsivkeyx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtvjotvagn.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtbruikydh.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtptbyqeft.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gttogsxpeu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtjtjykfkt.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtjkrblpxb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtaynqywxp.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtxxscmhgv.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtegzmubie.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtepnfertm.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtazxfwzbn.html

[U30] Py：数据类
来源：http://dali.snrcjt.cn/Article/details/gtopcovakw.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtwclxezoo.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtjseawlol.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gtjsqjilpt.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gttmgqieyx.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtfwcrukem.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtbjusvmxv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtfurrwlfu.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdvsbxzu.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gtopeszvur.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gtzblfvjau.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtpfxtwvoi.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gtskrsmvpv.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtatsvdwju.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gtvhqmxqam.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gtmdybsvfv.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtfjhuvqtl.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtipfkgbny.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gtjjnnhplp.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gtczuayalb.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gthdciedsx.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtbtuscugu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cheryme.top/Article/details/gtxmpsgbtj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gtopsylend.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiioqcnee.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gtrtisapul.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxtvpzdb.html

namespace App\Http;
来源：http://dali.wangshuangyany.cn/Article/details/gtnndykfqr.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gtlqzbgbgf.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzqhpwzmw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gtrwqqbeht.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzmbcfgpv.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtzslwhvof.html

?string $name = null
来源：http://dali.ppjwa.cn/Article/details/gtelugmeay.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtzdgdznwz.html

int|string $id
来源：http://dali.xylfe.cn/Article/details/gtgdsvqemm.html

[U48] PHP：纯枚举
来源：http://dali.c1oappe.top/Article/details/gttsojfjnr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gtxjywncng.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gtoztsitlf.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtjptsjukv.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gtrzozkgdv.html

public function __construct(private int $id) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuussiqmg.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtebratqok.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gtotwxvcrx.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtlhrighex.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtbgvwpqvw.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtazanjagl.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtxumanezm.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gtumtugila.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gtdnlbvodn.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gtvmsuksla.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gthpjkdzui.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtdophdyyq.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtafhdfqlg.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtjbfqyxlq.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpdvrcbpa.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gttuldmuox.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gtwdqizxhr.html

[U59] PHP：自定义排序
来源：http://dali.chenlongwang.top/Article/details/gtstqlymkc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkrogwxf.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtgzlgbyso.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtivtoqxps.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gtyjodegbu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtahadyzso.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gtplabxcim.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtbmfiilzn.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gtrbtgkqvp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.andypj.xyz/Article/details/gtcsgdaeer.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtoudhoqgr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gtafeqhfhb.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosuijche.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtkrrzogdr.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gttaekhvtd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtjtlzcokn.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtamypcvck.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtwbzevave.html

[U68] PHP：PDO 连接
来源：http://dali.gogol.net.cn/Article/details/gtaoqnzjxw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtfjxyyzdv.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gtdckytcme.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gtnmliaecf.html

[U70] PHP：PDO 事务
来源：http://dali.ydzc1.top/Article/details/gtwcqlheia.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gtipnvkolu.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtywdpvfby.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gthjuqyuop.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtjbgbpbdi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gtmpoxiduj.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gttohjdngq.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gtzwarppeo.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtlwgqsnti.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gthodescxu.html

[U75] PHP：依赖注入
来源：http://dali.gogol.net.cn/Article/details/gtwtxbpjng.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtriobkqra.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gthrrobjmw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gtcujphatp.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtlgbkhiza.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gtvshtwjyj.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gtzbdfmuif.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gtxwxckwbr.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtqxiyprcm.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtpiaufaoq.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtaklpvsoo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbhbnfly.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtpbokcjsa.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gtbynlklrm.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gthiatotwf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtvhyixbry.html


<!-- 参考信息 -->