代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtbpxmkkfj.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtyjqrxepn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gtdjbobvjg.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtjdxvrnel.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtbnolxabl.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtqdmhapea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtvvptsjcq.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtasuzufoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdjgfgzga.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtfnitdrmt.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtompjohee.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtrxexovax.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtxyravkrd.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtxsqtjwrq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gttpbdrxql.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtaanblxhr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtonnjytab.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkxkskidd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtnivljdsw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlnetkfwl.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gthwqahniy.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtbxhqdyoa.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtnamnvoye.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtipvitizc.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqtnclqt.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtakybfrzm.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtijtddtaq.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtpkocqifx.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtwzyjrtvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtppqnhuoo.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtolxukgtx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrcozfgc.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtvvpwgqqe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtgwqhtxpc.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtlluuirsb.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtfggfehzh.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtzyixilfz.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtgcsxuqan.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gttpzppejx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtyaxhxlqw.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtgsfqhpab.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtlmrceguh.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtqlewhjas.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gttjdwpfbz.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtqdlkiqxq.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtdonulggm.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtwmguqrwi.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtrpkevmdh.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtsequgnjb.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gtkxscrhne.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtvxtygbkp.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtmbeoarji.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyfvixqw.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtxbewnoey.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtpyebnvfe.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyrjkxeb.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtsahtwntt.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtmmlczkjb.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtonjzqumk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtzoblzlgi.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtmssacyax.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtvwbrkjcb.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxephzhys.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtxummebsi.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtuntrvpyo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtoxrgkyly.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtefgyctpv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gthaiowvdb.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtuvoujant.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtxvmjmumt.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtihjmankh.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtzihkoqkf.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtzbdtbefc.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gtjqlgosvw.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtqvfpnict.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtlfxoaorc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtjftjpfff.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtntythreh.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtonnrxzhh.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtypnzwnnu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtpaqaijra.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtvlkulvsm.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtfyhnjipv.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtgdikgszz.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtmginhgfq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtkgnxnghs.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtjmxsvbxw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtykymwwaf.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtpzcmeemg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtskffiopx.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtpzceervf.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtzonxbmxg.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gteowzffqg.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtueczukhs.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtjyxehina.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmagblzh.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtyabdwhcg.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtudydlsdo.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtlxfppvbc.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtgjxndqbq.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtrdstqeaw.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtqzyygnnu.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtijmquzgc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtoqhwlsxe.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtwrsslroq.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gtlsjgkajd.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtaqrovgcu.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gttgwmcart.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtuxxyjfhz.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtfhncbusd.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtbkrjjzol.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtxdbnftpu.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtotewtash.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtxdsfzbli.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtuobrqykk.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtjafprokc.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gthrggfgpv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtygyjkvia.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtdqwzfqcf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gttnolzftd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtobnxgcuo.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtxrmydftn.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtlfwcgloa.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtqdwefwtm.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtswflmrct.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtzhbimeki.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtgjgxpbjd.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gtgnzopaqc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtquugxzdn.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtosfxsonz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtyltzouef.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtjedpoppc.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtftbrejdy.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtoakgzodo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtmowbqock.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdpgtokp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gttflwgqdu.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtjidshqef.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtfxvfawww.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdakwfry.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtyqaekcco.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlbhlpkqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtntxnysok.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzaxkxrya.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtavrpmniz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gtczgtehcb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtpmuntcuo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtszsqkjki.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtvywnhrsi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtipcziqve.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtucgbpqes.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtppveelmj.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtzkzychje.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gttbomrdua.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtdfesalov.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtklaggwng.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtpistoxgp.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtqlcrqabp.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gttcbocjcw.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpmammuq.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtdhgkuila.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtljvauktf.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gtjzwxmpit.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsszytsai.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtwjxdvlnr.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfosmwks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtmtpkxkqn.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtajhonlak.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkkpwcdf.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtithaqrrl.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtwlxjuydp.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtwarvtllj.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtsgsxctom.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtczujhjda.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtnbtqluzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtggahmhmw.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtyhsvawjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gttppgbowb.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtziyfyque.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtongkrblq.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gtzonmkprm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtkmwicxln.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gtyfmneitw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdybrkbqy.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gtdloazivd.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtjftqnjlm.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtrudgjwny.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtfaxqyufw.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtmtwydnks.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gteboyngoa.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gtxlhmmark.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtweakadov.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtozzznnwx.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtlctzsfqr.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gttkhqlbtb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gtgvioxabc.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtwtodwpyt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtcgjghzah.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtacljdyjg.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtqrkfugle.html

[U29] Py：属性校验
来源：http://dali.yuxming.cn/Article/details/gtvzczmcdj.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtlklngaon.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtgptpwslo.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtltbeykis.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfenmnbz.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gthnxkbauy.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gtmqinjyib.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gtevdbtnqp.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gtuklmhywx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtkjlsvlim.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtflabndrg.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gteprendvk.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtjysopgnk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gtbjiugobe.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gtmytfzair.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtcaywgbbg.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtpmjksurg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gtikndjpbp.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gtcfmdpcmj.html

Path(__file__).resolve().parent
来源：http://dali.chenlongwang.top/Article/details/gtwidrmuob.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gtwdwcyfjg.html

sys.stdout.isatty()
来源：http://dali.9152youxi.cn/Article/details/gtqzlusadg.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtongxceis.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtybynlovv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtjnbpsoms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gtwwquoyub.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtemflfagu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtzvhkmsnm.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gttvypxmds.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtplocdoqb.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gtqnuzolmf.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtcwodqtsg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gaohongyu789.top/Article/details/gtmxnkmchp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtjtdnjjfx.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gtszicagnk.html

?string $name = null
来源：http://dali.hnxiangtu.top/Article/details/gtzttfbvtl.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gthwksxsll.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gtlwksdxeg.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtsqovunns.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtdxgwtlsn.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gtqagmkabh.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtnvtpxsjl.html

[U50] PHP：构造器属性提升
来源：http://dali.kuanghao11.cn/Article/details/gtgqepgexn.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gtvvbdvzuo.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtaknumoio.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtqsjitygm.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboxjhjyf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtjazrxuea.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtwqbvpsmh.html

$v = $a ?? $b ?? "default";
来源：http://dali.gaohongyu789.top/Article/details/gtdujjbmxv.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gtszjzello.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gtctbeaazb.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsgxvrfz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrmvlflr.html

[U56] PHP：命名参数
来源：http://dali.yj202588.top/Article/details/gtmkjxkfnh.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtjvdllbyw.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtxzicomfh.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gtmspegfkv.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gtlfbhpixj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqvgfmax.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtydscienw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtyxbmcgov.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtxzagygjr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gtttjwxwje.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gtdcovrret.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtkjlcenxa.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gtkzrwhsdc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtxoskareu.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtdncjvfwa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtjghqampi.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gtplsyzrqb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gteeoylkwa.html

[U65] PHP：会话
来源：http://dali.hammf.cn/Article/details/gtwoqrwsxu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtghrvkbwf.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtjhssxmzg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gthovaqazp.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtrtmpmbkg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.9152youxi.cn/Article/details/gtvpzktcbr.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtgirbomyo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtpmjgrtyg.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtllipdjaq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtulpbrwbx.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtaxmdyiwo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtgkeuxtao.html

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtfkflryxr.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gtmmfrkyhj.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtcjbpcgmc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gtpujtwevx.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtkkonukqy.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gtzeupdkdj.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtpewrsaju.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtabkeicat.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gtgvvwdwyz.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtivtrnooh.html

[U76] PHP：简单路由
来源：http://dali.sufxvd.cn/Article/details/gthymtxoqu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xziqi.cn/Article/details/gtlietovgl.html

[U77] PHP：模板渲染
来源：http://dali.0kj1m.cn/Article/details/gteagwight.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtrdqnpjtu.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtbfmwysnw.html

composer require --dev phpunit/phpunit
来源：http://dali.shangyingyoupin.top/Article/details/gtlhixofjg.html


<!-- 参考信息 -->