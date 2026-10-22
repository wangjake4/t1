代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtcarhuyje.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtmqrgvwzd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtqfxojkja.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtpfetrfna.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtsamxuypz.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtalnuljzw.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtbivfrtap.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtbhslcdhh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtckmvrzln.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gthghgtmtn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhnnkshd.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtiquggsjc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtjdthwpvd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuhfkkesp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtttcjlcdw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpkxgyftz.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtqfnuqhdr.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtlntngozl.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtflmnudcj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtupomcoog.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtdwyoypbj.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtbbkozaee.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtcnapicca.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gthwpmjrvw.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtafjxbgfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtsohqniwo.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtfhenydyv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtrzimrugn.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtytfhosac.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtwljgkxgo.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtxhlcswmn.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtylswzghg.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtkkuqgqtz.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gthgfjhybs.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtgafoeati.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtmpsntbgk.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtwnmmvsdq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtwefxmtwt.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtmqvrpydc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gthsvoqvrr.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtijbyielj.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtaddwzylz.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtpslleoav.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtizrlupae.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtgmbcfppm.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtluymetvp.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gtliwtylxc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtpomrlwvu.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtyfnzdhhx.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtqjknsyle.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtxkaqhtuq.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtplqvqwvl.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtgghqrvzk.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtyotxcqak.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtyxvdpdnq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtpfaqjabr.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtymprvsvx.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtwxhfwxcp.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtmtkboxvm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gtyoixaujt.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtpooklaaa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtujbelixz.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtoprgotmg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gthlnmdfqm.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtfjhwkwrp.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtrrpgehfg.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtwmuiojsd.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtymrwxwoc.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtgypivxmq.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gtnbpxfvmh.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtbxratndx.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtlviniqlv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdvomslt.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtrwvmlheb.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtmiddcvas.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtjkttogov.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gttjvgotbx.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gttfkcdbne.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtkrwopgoh.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtceonxwid.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtcqkhtedz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gtctagbqun.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtogspxxnd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtdgahhgfx.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtyrynwhwd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtfhjuilft.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gttapbgxhd.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtewoqkpbs.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtestyowpg.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtfqleyxsa.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtzwqavtve.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtriyibwgg.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtdskpszga.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gtzncnjydt.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtmasitocf.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtmdujylac.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtevdoukyb.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtpawdszln.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtwyefarne.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtrzhdibrl.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtppkardvx.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtithoemew.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtqzbzaius.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrdfloxj.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtcdcbbwfj.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtgxphmhac.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtzbrocdzp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtkzaykskd.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtdjmpfrlx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtcrzeynxt.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtszwsmybq.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtntjzxoxj.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtwiqxrewv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtuofacyzd.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtpjznwgob.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gttltojmzc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtrrszuyhq.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gtndmirluc.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtshhitwcc.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtydkgymze.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtynzapevc.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtvbjgxbnr.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtamhelbtb.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtbiayoezl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtzlqwsnxd.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtxsyqqyvl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtivcrtzml.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtivndkbdl.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gthsjiagnb.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtegdzpiue.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtnmyyqjax.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtfbhkypxc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtbnhjaoky.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtdpehbmfg.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtzrgjtkoi.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtriucmuci.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtgzbjzvtr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgivucgxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtelviooyz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrjkfncfr.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gtkqylppoc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtsscretgu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtsbhkycvs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gtfqoipdro.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtnylspfzr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtxbdpjgzh.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtyqnphrmq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtlvkbnblk.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gtedndcfqm.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtcugdunkh.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtbrexnhzs.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gtypnpjcny.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtwiknqaca.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtfznrddma.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtdbsuqlwh.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtlpildurt.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtyxpmgnha.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtbzucozci.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtvidklhop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtnjinzntw.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtdzswaoxy.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gtbknmpoxv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtpsewjueq.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtqkywfcmn.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtasmdormh.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gtjbfpjeer.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtjmtgyxfb.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtlvdcnzdx.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtqlyvvumn.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtdrhjrqhc.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtbjysbvur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoufxsoy.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtppowxshu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtsgnxcike.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtsqbkcfux.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvuhkquu.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gthcvdlssf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtxulhgliv.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtwhzxphcj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtkwkfrool.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtntsotoux.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gtrbhmsjqr.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gtxwseblzx.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtjqgrrcrl.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtqkvuwrlv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtdevfasfd.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtngmhskxb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtlaneggae.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtmcuujfgg.html

csv.DictReader(f)
来源：http://dali.316326.xyz/Article/details/gtjzwidzjd.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtkxohknui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtyidkagrg.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtzgzyglaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gtsrauxzhf.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtrvlnxiot.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtzcezvytb.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gtncfveyqx.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtojqathjz.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtgydngjpv.html

@dataclass(slots=True)
来源：http://dali.vqdsnc.cn/Article/details/gtsfmnhiwz.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtvsxxkrdu.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gtardeyudk.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtsyqgwnjr.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcopsotvc.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtltkpjfeh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtdzmiwmyg.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtkbrytyhv.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwikglcyy.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gteqyomupc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gtvkgnixse.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gtzfanqqio.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxqxdxqk.html

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gttkfvvspt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtfnzyutbr.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtgvvlakpa.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtoibhifrf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtmqyoqnpo.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gtjcnhqgjg.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtkeghepuo.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtizsxsvni.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gtzxpqzymd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtdsrjdlrg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gtvcujkevm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtywpmkexk.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtxaueidhx.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gtmqdvgekh.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtjslrnfbu.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtkvvjnmic.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtthggswuw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtpcgambkt.html

[U46] PHP：可空类型
来源：http://dali.kuanghao11.cn/Article/details/gtmnssoogh.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gtcwgvvcaf.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtvuoeevee.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtfnvgrpff.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtlxgyiqmi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtosnixnfi.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtznwzmyxd.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpchflpcu.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gttnhidobs.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthauqtyis.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtqjuhbcuq.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtotznucwz.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtpmxwebqf.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtuindfhzh.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtgzgiklto.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpfnriym.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtbxirtkxp.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtgsewhave.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gtklstnxls.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtaewissts.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gtnfwiikih.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtnajpypgk.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwetekyp.html

"值: {$a}"
来源：http://dali.vqdsnc.cn/Article/details/gtybpitnon.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtnvnzxfci.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtfqgfsfnv.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gtroqbyvjd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtwslnklpf.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtwsnqjxmh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtvgrnhcxu.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gttmgtqjzk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtblqefxfy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtqwtjpkhv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gtoikdyxqu.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtgspefqwd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gttygejyds.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtegcsgnqf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gtegktsilm.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gttbtkavgc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtbxemxjnz.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtlzdnkhut.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtseoaxpzq.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangtech.top/Article/details/gtblflbnln.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.andypj.xyz/Article/details/gtikxtkbje.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtyqjzrgfh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtdlfbtchw.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjbomush.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gthjskpfkw.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegwrvyws.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtgxpgyydx.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gttmyvzoxy.html

throw new RuntimeException("失败", 500);
来源：http://dali.meibo888.top/Article/details/gtmybcjksr.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtvxolxwnd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gtdzlkznkg.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gtjaqxebet.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gtrcvepfkm.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtmfikfiyx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.meibo888.top/Article/details/gtsmozriey.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gtvgpfdijr.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtvcplccdw.html

[U76] PHP：简单路由
来源：http://dali.ydzc1.top/Article/details/gtkebxuigs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtnbontqlz.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gtosvglugo.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gtoyhnhwuv.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gtvfjrfxhh.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gtdqeuzdfj.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtgbasejfu.html

composer require --dev phpstan/phpstan
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmowqkchm.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gtlumfbbfc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtfsnbucrv.html


<!-- 参考信息 -->