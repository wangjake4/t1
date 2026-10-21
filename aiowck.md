代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtrsfslaio.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtrbqvisor.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtsuqoavxh.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnpykqlv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtdynolyix.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtdaaxgmdy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtepqklare.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtzdhxbesq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gttdwxkwom.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqpnrxwkm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtrtevowar.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsykqdwvj.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtczzofhvr.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtmzwzvdij.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpqkybte.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtkrcjtske.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtxcmuasxe.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtbxnaglcw.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmzujljv.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtcerjfyhx.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtrgixcwkn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtkiebypky.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtprnvwfwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtpxakgjbn.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtjxtlvnjw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtoqamkiqr.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtijviedor.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtwgpmifqh.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtboxbhpbl.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtvvlnszfq.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtwturmpab.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtakuxylip.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtqbxadyai.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gtdhmmsjdf.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtjendfgpx.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtniplhvmu.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtnztilauo.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtvzqpdnqk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtormswzrc.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtovnutcky.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gthkwrbfpr.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gttorblbsb.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtiumyacdy.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtiktupfza.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtqxeailob.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtrypxrmpo.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtuzepgwpi.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtivfetvsi.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtqdqewxih.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gthcptitwp.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtuvfpkmpj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtukaiaafp.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtjhpnnyjk.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gtzjgbioss.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtieyrolxs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtrntbsnti.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtdgnvlqzo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtxcvwlpsq.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtalsbxlqk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtxsjlqvgb.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtzqkldfyj.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtjmtgjwxf.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtewlybhkq.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtunktsext.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtovvcmzzb.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtkuyuvcwz.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtywboffhv.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtclhhwvmb.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtcfiedand.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtkpllmzhi.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtnzhchcon.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtwojxilmi.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtnylzrnxw.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtnfiexlne.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtpbkbtzcw.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtpxgolxkv.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gtrmigtdqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtvofyogta.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtyvghravk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtiunwdvex.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtwfowyzyx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtkgirofbe.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtqolqndnr.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtnryhkfik.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gticugnume.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtvrzovtir.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtdvfbqzni.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gtmtdzlbhv.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gthpqxwlvo.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gtzrslgxgz.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtyqdxkydj.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtybplhgwc.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtrviwbozc.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtajrbrzxy.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtuecnstrc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtjjssswrh.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtumezvzvt.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gtvaicluvi.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtxkpqwdwg.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtqhucfhot.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtzimfcpql.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtxtjkjhtv.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtbucoensu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtopwpsffo.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqlctsmf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtxuddrevs.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfazortjg.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtacgspkfu.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtesgebetp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtfrdyruqd.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtvartahxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gtivzkhhjj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtnnsegcsr.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtllbdvoka.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gthokwjrzb.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtwmjroypd.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtodejpukl.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtalozjtpz.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtbxdlipdb.html

[T54] Scala：集合映射
来源：http://dali.jianghu66.top/Article/details/gtrjegfylo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxpxqjai.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtayfdwiij.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtdgfwqtxc.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gtnjysvwfi.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtufostxmi.html

[T57] Scala：模式匹配
来源：http://dali.tanke756.top/Article/details/gtgjyqueyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtlolnhprv.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtnxkhssnr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtevxzwker.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiqdawoj.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtlgrrxhqx.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtcxiibzde.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtqaajplai.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwsavanuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtyebeezsu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwjzupjpf.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtstunjxpz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtwpypaqlu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gtrjbsqmwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtgmyncsnt.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gttaarxxqh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtmkxplces.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gttbegbbox.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtxwcviped.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gteawtsslm.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtgxvrnpdu.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gthweqdzbr.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtctjybkhv.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtphdlauqi.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtwzygvwwx.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtqjmddhes.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtjscethsx.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtnblsxbtp.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gtwxyqxrkb.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtgvqojwba.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwvdhsdf.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtdioulccd.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvakcewch.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtllfvoqxx.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnjparxl.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtiikbmurd.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcauefcav.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtlvuqonce.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtocuccmvl.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gtwklnnagj.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtbrelmemg.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtompldsfe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gtvodpzqsr.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtyydgazhb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gtgxaehhuw.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtvpyxnqmq.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtcaecyohm.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gttprokgoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtumcnjuks.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtkghjxgrp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtpdkfhcxa.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gtivtjqqfn.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtnaovobvu.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtcgvnmxex.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gtkwuctrlf.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtcrefgyun.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtmfifrbob.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gthjtpwftp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtxtlfzbbo.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gthdowkunm.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gtiqftbvha.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtpgfarwng.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtiifpmxik.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmrvajpn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtkdcxdklp.html

[U28] Py：类型别名
来源：http://dali.fengsongda.top/Article/details/gtmiacrcxz.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtsilljfmj.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtpzjmmxyb.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gtviqfhnzm.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluqkdkah.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtqhtgqngd.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrpwzrhx.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtsfhmyypn.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtcxhdxlif.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtzroyoksi.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtaiktcgyz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gtbsfubise.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gtaryxgswt.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtcfpwhxeo.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtohkzkdpv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gthjpyhipl.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtkuvcxjir.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtiykecovl.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgofymsuf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtnoqtuwur.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gtoarhbmkj.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtlexstmkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gthqegjlxk.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtkpntrete.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gtnzpejzkh.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtuegyuolf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtvfrnlxhe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtcvyjsnxz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypzsfziv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gtbpiyczuw.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gteloaqalv.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtsoefpdux.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gthfyfwvpb.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtpotoljmb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gthkcmjhno.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtidjtvosj.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtefofqpay.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtlekwcqev.html

[U47] PHP：联合类型
来源：http://dali.jianghu66.top/Article/details/gtrorqauwc.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gteqzxzxqc.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtxzmfaljc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzwkqyfwx.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtvdxacgur.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gtoeoxudjz.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtusqrgder.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtpvprfayo.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtwkqgtylz.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtrngpvsfq.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtmemhbtwy.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtqjgaxixw.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrusxdphm.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtjuvkdqkz.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtlvziluee.html

$obj?->method()
来源：http://dali.chenzaomai.com/Article/details/gtkslcbnzv.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtumztwsky.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gtzjoenjpo.html

[U56] PHP：命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtyknwzwzf.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtnrkwvfxj.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gtshpaedcx.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtkigbxsya.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtjvoivxlu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gtoqnizyxx.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gtinmekisq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtpvbckude.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtbwklfnfh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gtojtdcmcs.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gtrqdkgnrr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtyabkbqog.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtuxcneufa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtpztpetco.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtsolgsyeq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ydzc1.top/Article/details/gtrfzlkugx.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gtioayxlcj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtvdvcangd.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtgwrddezu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtwclndozh.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gtcssdloko.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gttkgskbbu.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtklktdidy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtxrspuvwg.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gthmhjevlq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtkxumzqqf.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtminwbfgh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gtlujdaode.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtotfsvmmo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtepqyfrrz.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtgopvkwpp.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtojxfveju.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtaqmnnxbz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtnhaodugh.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuanzx.com/Article/details/gtocnnozfy.html

parse_ini_file("config.ini", true)
来源：http://dali.zdqjudy.top/Article/details/gtnsdbrtwx.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtjuzledfa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gtjlcdtosz.html

[U75] PHP：依赖注入
来源：http://dali.tian-w.cn/Article/details/gtthapftez.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gtsswmuvjm.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gtldttxnyl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtgnyywuju.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gtadppvzmt.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtapvcgsln.html

[U78] PHP：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gttoochjcl.html

composer require --dev phpunit/phpunit
来源：http://dali.haohaochexian.top/Article/details/gtusiauybu.html

[U79] PHP：静态分析
来源：http://dali.yuanzhike.top/Article/details/gtaqrienzq.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtzjisqcpw.html

[U80] PHP：代码规范修复
来源：http://dali.zhengqikj.top/Article/details/gtuofvtlfb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gttaqboyvp.html

[U81] JS：初始化项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfixjohst.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gttikbqysm.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gtglvqucib.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtvyhjihuh.html


<!-- 参考信息 -->