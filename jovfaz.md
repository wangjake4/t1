代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtnjysnigl.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtsdmcfkje.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gteedxdzuy.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzqhuson.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtbvgtnscl.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtkrbtedku.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtxbspyolm.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtxmvknhdr.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtjxplkasq.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaomdykc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtzsbzlqoy.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtpnfuuyww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtkbchxbrs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdbbqxxrk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtnnfxcxkj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkqkwyrts.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtudytmkfp.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtxitfiywz.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtmwcubbub.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtbutbjuij.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtmuwetoiu.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtbjreqmdj.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtnwanecdo.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtwtfibqxh.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtsstgtcwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gthbqxrdym.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmtqczgj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gthvjwocmg.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gticniqusx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtummkqyco.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtreyzpryr.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtoofehvlo.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtljyclxyz.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtvtycwxxa.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwgiqegv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtfustpzcl.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtgowmurtd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtqigawaqx.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtmtyxxgnq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtdsfmkbny.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtequzyidg.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtatliqbyw.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtsiifnfiv.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtbqxebtvm.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtdmgyckkl.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtelddtnuf.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtnwslascx.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gterezmhfe.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtyfqxwktv.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtyrjtkhfz.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gttmqdpcgf.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtfyldhsgg.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqgyczni.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtksqnosvl.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtfyewwxtg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtcrujksjk.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtomhxcxey.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtejoltcor.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtacmhrpsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtlessdicm.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtsfsaeogk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtxsypcpxt.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtmygpgcyy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtdbhvlgzf.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtsfchdwuz.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtijsueojj.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtuyuyskyf.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtisuhpqmh.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtfziaenmx.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtrigjcpba.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtyddfwvfm.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtlfrkxxzh.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtcoycmkqy.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtawoettss.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtqrfxjsad.html

protocol Shape { func area() -> Double }
来源：http://dali.ehwqpu.com/Article/details/gtyyxcesgx.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtxbcstzxm.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtgqehsdzz.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtnxgzoxcu.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtjeyfmxwp.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtipzqcpdl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtqhngbtha.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gtxdqtjwpc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtqmwjgfwz.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtesfuyfit.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtkynyuvjy.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtcorunhnc.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gtidhrscnr.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtfyhubpeo.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtjbapjxyd.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtinyrawgx.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtxmxyqloo.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtjrtyhtya.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciinrbwl.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtepmfbsgu.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtrysshada.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtsexpxnwr.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtpxqjzcrf.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhqlnekx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtktxdewms.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtkhtylwai.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtscfbdwtm.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawgfkqxi.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnaarjlyw.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gtuplleumd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gthxkrvcks.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtjbdynlpd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtxjahzgtz.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtecvedvsd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtiwfffyjf.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtrykwxrry.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtpkqtizwq.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtwtfdbyel.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gttuanzaah.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtyvwywmpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtswtagivp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtsdnyddqp.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtrxoiyvkt.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtpwqvllgc.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtywyurmgg.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtiqkohbcs.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtmhthkuwc.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtshcmwvts.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtumusywaf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtbdrtnpbt.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtzosrtvxz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtgfdukkgx.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtzjdxkfrr.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtfuyvdxzr.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtsleahiko.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtsxldkqem.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtsniscsqy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gthixbspxy.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtdtwdpshb.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gtqftmtpxa.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkezglwf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtlvwwmkir.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzvowtgyr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtdlzptccm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuzklwjrd.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtzpaxpbsz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtvanjngwo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtjztqedqf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtvngvwljf.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtccnhnlzc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gtusmfcjjc.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtrgrrlmdw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gtymhovpus.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstncvktq.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtkodglpvz.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtkpaxxwas.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtfwcsaqwu.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gtaknirdbn.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtzassqjly.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtszjdxhnv.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtpccthmwt.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzurzvwiy.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtjbsneatj.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gtdojsnzby.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtxxxubxga.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gtlxeyheua.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtiaczwymc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gttazuzrrs.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtvrhxpkve.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtczkadfze.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtgofqradb.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtbhqxdjet.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtbaxhopqh.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtypvgatqt.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtfhiykjwm.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtrnefcdkl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtqkdipyit.html

[U17] Py：初始化日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfyiidis.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtmmddfjok.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gthpbyodsb.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtugwkhjxy.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtdkqxhrln.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtgweucjme.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtzdbqxvdw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtfbohltoa.html

[U21] Py：自定义上下文管理器
来源：http://dali.jiagoushi.top/Article/details/gtqajmtfpk.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtvyofyhlh.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gtkjtmovbi.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtymltkgcp.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtbhhisgth.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtayixlbbl.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtewbysjyl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtexkeqdlq.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtlbbozkjj.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtmiwdzing.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtvxxztprq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtwwfmvzox.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtaljkczju.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtoehzodnf.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtatfgiqym.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtwsqraasp.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtteevvkkb.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gthmtmixhk.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtyjwifwij.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtrcoybkxo.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gtrwooxzhi.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtejffsedp.html

[U32] Py：代码格式化
来源：http://dali.cdnleiting.top/Article/details/gtbcosbehv.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtnwhhdyre.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gthucgdqmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gtmtepinzm.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtxujtjqup.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gtjxgbgrlt.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtrojaxfwt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yvedp.cn/Article/details/gtirrluogw.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gthropsseu.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtrgqgfqbc.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gtuabhiekz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtcyihezgu.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gtryyairok.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gtzqzqcldn.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gtcobhnklm.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtflagjkmv.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtyirzutke.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtzgkyfiyt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gtovfdvwrd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gtrzpwjefh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gttjhyvknf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gtwlytsccb.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtnfnfiaza.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gtrogscjmh.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gtqmfkowfw.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gtpffauogr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gttbnputyq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtrfdaqrzl.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gttoivnqnk.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gtbtkvtzge.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gtayexfxwb.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gtrtebttsg.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtvvzidhgm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtaogsovrv.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gtzakbvgal.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gthzicsmaa.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtbwnyvfoh.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttfphqhpa.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gthdsvjdva.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gtyxnbmhvk.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtdtnhrcww.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtwduimgth.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigfzy.top/Article/details/gtxuhrqgbc.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gtvhoyeeob.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtnrprpyac.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtoyqconhh.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtuywacwwl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtnozxkwex.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gtehzpzzzx.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtawbmcoyr.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksqmxmue.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtijazdbcj.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccohxtxi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gtgvgzramb.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtfeczbefn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtxgopvpxx.html

[U60] PHP：JSON 编解码
来源：http://dali.sweek.top/Article/details/gtpntkmctx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtmkodnyns.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gtppwmrqrd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtnvnlinqi.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gttwmpfbvs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshmchpon.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gticmnzoed.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yanxiufei.cn/Article/details/gteelpjyjr.html

[U64] PHP：目录遍历
来源：http://dali.cashguo.top/Article/details/gtpjltbpyz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpmgjwic.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtunqkilmh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtqnutbpsh.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gtlhvhcjim.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gtgfmxmgwu.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gtlulpjbop.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtycrkfonb.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtaumpshuz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gtzdlafakt.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gthvsocwim.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gtwnhlnhhj.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtomoblfkq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgufenzy.top/Article/details/gtiupjmxti.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gtuotxotue.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gtwnfdzlgq.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gtqmxbedxj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gtasyuuqdn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gtevdyqxwn.html

parse_ini_file("config.ini", true)
来源：http://dali.iojbl.cn/Article/details/gtoipdgdet.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtjcftjzai.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gteshuaquk.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtetcnerca.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtlcjhvajx.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gttlmcridt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtdlntprir.html

[U77] PHP：模板渲染
来源：http://dali.zhixingplan.top/Article/details/gtxicjajqu.html

composer require twig/twig
来源：http://dali.jqgfzy.top/Article/details/gtkasepjex.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtjdolfqqh.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtctbxwgay.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gtgvxtusfn.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gtbxpdhgfj.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gtzinfwbex.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ydzc1.top/Article/details/gtmlxmuolt.html


<!-- 参考信息 -->