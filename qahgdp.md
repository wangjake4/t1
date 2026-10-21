代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtmmzfmhcc.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtenmovnne.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtdltpuhes.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtstoulemr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtbuowtikv.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtkeviteou.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtfihggjee.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjtugoti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtyyqngnas.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttbhoszvb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtioeyjbza.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmtwyzewo.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtdmdipdzp.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtaqcrtoof.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtborrzvbx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtoqhgywky.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtbgdmqykh.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtakvjiyxv.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtcvecmghd.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gthgzanibz.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtjdvtkqve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtxylaaonj.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfpfhzqt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtyidistoj.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtubsbxtft.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtdbjwtnjk.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtbhndpmvv.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gthtfjovnn.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtjetghfmc.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtzbpamdjg.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtvjzgdwsb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gteilqkizz.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtcetvosbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtnhfikikv.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtdovowxun.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtgudozmyd.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtufvvajkw.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtfvloldvq.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtbeyagtoc.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtbvshrvrm.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtdevbrgaa.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtoogmihib.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttmxlrlto.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtnmbtfjob.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtxcamsznc.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtzjxmxuiw.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gttyuinmeq.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtttfopndf.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtrsccdcpf.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyssqiuz.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtzqhgfuiv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtkauyrxas.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtbpneafoo.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgmgxukz.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtcsxvwgul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdwtinip.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtpttfwlgr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtzdjhdvto.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhyzydng.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtfajhglfc.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrrgqsil.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtfbphjhdc.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gtrdtydnwv.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtsacxpjrh.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtrtjjyxuw.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtqbroyswr.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtypglbzkn.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtxtfmszfn.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtrbkoxhnb.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtukxdtowr.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtvjxfeffi.html

protocol Shape { func area() -> Double }
来源：http://dali.wangdashe.top/Article/details/gtwffyhppm.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gthwqutkri.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtaykkpudj.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtcqnaprqv.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtdjeqegzx.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gttrlkqvdn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtpqogdcgy.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtocdyjacq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258888.top/Article/details/gtocyrjklt.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtkzyaaoue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtmxwlhsha.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtvgpmgfcz.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtkbjvxaln.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtfxchlcux.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtdtdjnjda.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtupjfqftp.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtkaiznvfj.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtibaspgjl.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtvwzzcddu.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtzfeminey.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtcapniuzw.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gtepkaddrf.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gtpeomjavq.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzmuixqc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtrjssgzld.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtcjtwbtoh.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtppkbshdv.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gttstizswp.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gtlxushmwq.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtjboglehm.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtbapyneie.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtthkbrwte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtwyyuxdzq.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtkiijyapa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtagypmjvw.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyydqbkc.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtjbegenzk.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtqtcdgqzu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtmkkvamgy.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtggevkxza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gtcyvbjotl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtutcxqhvg.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtjxtsngub.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtbdhuuaoc.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtcjdtxeno.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtnwaylwyu.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtwmnajumi.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtuhjgkwkr.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gttzzjbmmx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtcqdfcivl.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtmwvaysqw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkpwugbn.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtjrzomege.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtcfglleit.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtpjoybyml.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtilmsmdvf.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtbbnufcze.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtupoaohic.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtcculucxo.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtoumbhtxw.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtutipzxmc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gtjejxqrgs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyvdebxxq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtvhhcihek.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtisqbrqbd.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtposbtupt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gtmfwmqlex.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtkmqxjacw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtaxqupaqv.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtvmyrwjpr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtmkwtrspd.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gteyqbptpb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gttcwpcjhs.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtdzbpyztu.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtgjyyzxoq.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtwdxdjlyo.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtbbhfobcp.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtmwqsaoev.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjppqryka.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtbmrcihmt.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtltzclqkd.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtckgryqrd.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtjntxjejn.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtcvxoyrtd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hywenlv.cn/Article/details/gtowbnlbmz.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtuhdjgehr.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtssbjqlwl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtzjejbiue.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtjfyiilqc.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gtpfodpvzt.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtsyoxmcgf.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtkrdxmbro.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gteyglyiko.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtnojzfloo.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtnllhtsaj.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtriqdkgtx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gthslwwals.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gttvbphgst.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtzwmssntr.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gtxhqulwen.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtjcehgdzh.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gthygfmvyt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtqqhtmejm.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gtgkomrvog.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtbaayjtvw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gtsbbfhxym.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtrwuryetl.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtdngfvhoj.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtvsnbqplf.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gtnccieytf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtrwbhjcao.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gtkgmhcetk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtufrcqnar.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gtttbixlyf.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtmspwddsy.html

[U26] Py：并发下载
来源：http://dali.meibo888.top/Article/details/gtltwccsjz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.andypj.xyz/Article/details/gtglcynsxe.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtvvvdxnaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtwqgwydcf.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtxlfqhfsj.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtlasmujpo.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtjksetqtb.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtpbymmfrh.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gtollkiind.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtiewudwbm.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gtdkniptau.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtmgccmjdf.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtadiefrlk.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtdbsckrfw.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gterlmpkes.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtopurdtni.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gtmbaamrzi.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhvkgbfn.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtgjdahzap.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gtsohvaeev.html

[U36] Py：定时任务
来源：http://dali.ivvv.top/Article/details/gtidbdjmfc.html

schedule.every(10).minutes.do(job)
来源：http://dali.aibaodan.cn/Article/details/gtrxjdpquz.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtjhohklbk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtvevkicfv.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gtsiylxdgt.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gtrgnyvvmt.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtxqaztbux.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtikxcvgzk.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gticvozahp.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtdlstrlrd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtmqoydndj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.c1oappe.top/Article/details/gtbhxfdrdz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtlnhkcnfj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sufxvd.cn/Article/details/gtqlbenoij.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtankzonkk.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gtgsrpqszq.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtsewrgcae.html

declare(strict_types=1);
来源：http://dali.zdqjudy.top/Article/details/gtjhkcvkrw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalqhsucq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtlwxvftdn.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtfgmjiqzk.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtyskdaefs.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gtdzlikrja.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtsnaquryc.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtcycwgapp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gtrwtaqpzm.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtpniuguxm.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtsclzrrdn.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gtalacmscw.html

public function __construct(private int $id) {}
来源：http://dali.hywenlv.cn/Article/details/gttheqncso.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtgewcaxim.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtfzjwceeb.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbbcaptq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtvimjlgxc.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtnxpcrdrf.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gtsfmgqxao.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gtaaasocjz.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtbovowfis.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtnavthkla.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtshljrtvp.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gtphopoims.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtkjmsfzet.html

[U57] PHP：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtriypcepv.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtxxlwdyyv.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gtbvmawgxp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gzhubu.top/Article/details/gturmjbyiy.html

[U59] PHP：自定义排序
来源：http://dali.ehwqpu.com/Article/details/gttcpuwkvl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtkxnxoidn.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtrnwqhfzq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtlgjeehjd.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtrdmdvsoh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtsaqpjbqq.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtmvagdtar.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtkbyfxyli.html

[U63] PHP：文件读写
来源：http://dali.cucudq.cn/Article/details/gtotdbhcoj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gtanstytke.html

[U64] PHP：目录遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagczbcmj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtomsyzdbb.html

[U65] PHP：会话
来源：http://dali.svipenyu.cn/Article/details/gtinamzqlv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtpberkeub.html

[U66] PHP：设置 Cookie
来源：http://dali.guannengcc.top/Article/details/gtvjhkzlcn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtarplrals.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gtvngdlsgl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtqibuldli.html

[U68] PHP：PDO 连接
来源：http://dali.xylfe.cn/Article/details/gtnmenezqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtuanrqhwc.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gtwzhejstc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtnciddaqf.html

[U70] PHP：PDO 事务
来源：http://dali.jyoumei.cn/Article/details/gtjklfjnyo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gtqdahofqy.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gtbooydnih.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtgnkmcrpq.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtecypapyx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fengsongda.top/Article/details/gteiarncoh.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gtedneggdz.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxrieelh.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtscuzbdqm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.iojbl.cn/Article/details/gtkiabcybi.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtbmswyshb.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gtfvjxjuoo.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gtqxdrshlj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gtwabauvoj.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtyanqsylw.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gttanxfzeq.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtpuvushnr.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gtaopixxgw.html

[U79] PHP：静态分析
来源：http://dali.xziqi.cn/Article/details/gtrogzlkza.html

composer require --dev phpstan/phpstan
来源：http://dali.sysykeji.top/Article/details/gtpykdryvb.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtzphbhiuc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gtpdotscdl.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtcfdpzlbv.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gtaozmmhdz.html

[U82] JS：package.json 脚本
来源：http://dali.tianlin.xyz/Article/details/gtestxynir.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtygvcnbek.html


<!-- 参考信息 -->