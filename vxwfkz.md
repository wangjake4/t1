代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtvviyyfgw.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtwmdqwnvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtlnlkjsbe.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtkkagifeo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzdzonxk.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtfdztxdjl.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtjfgclnyt.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtctphlbhy.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtonzhbtmi.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtddhahaza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtywdtopmu.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtzazhedvr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtczljkzwb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfxotdnkh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtmtuofqdm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtposdqsum.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtwdkolqhe.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtkpndqwso.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtbuoarmds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtlrhqyujt.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtukbrvllm.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtjdaipnsj.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtynbooqdi.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtzaqginqw.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtpubnmhyn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtnzaoguzw.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtynuhplys.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtkkpbajnk.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtzuisczeu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtxabxypno.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtyhsftvap.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gteedritff.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtwyohbrbf.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtvtjdeqfo.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gthxngmcgi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtzeisrdhy.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtnwuraszm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtszpgexdg.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtuggrrqay.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtjrsynmuo.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gttqsnpgml.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtvoficsnk.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtbwdcfefx.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtqlhqmucj.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtdmzipwlq.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtpzceqvhy.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtjxmyxkvl.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtrvfguvil.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtgxhepbwg.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtwnewbzgx.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtfsnjreie.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtyxkpkxcd.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtuxrlxyjp.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtextsgmsa.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtllafjhho.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtxasxatag.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gtonhurtjr.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtkruowbak.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtoerlznyj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtdxbzubrk.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtskqbzpxs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtseohdvpt.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtmvjeglgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzjspwff.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtqjtabzwc.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtdzzsmmir.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtumvamfwt.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtewaapzqn.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtumckptdq.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtiedylsbd.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtlvfbcfcv.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtbupyexao.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtpwwskulv.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtdjgijjzc.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtevazwhnx.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtdqntjtzf.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtsfppwefm.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtmehmehbk.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtydwjozla.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtiddonruu.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtmzvdydli.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtamqgryhn.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtiekwfwia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtxzkvtgch.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtavkidiai.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnoizaj.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtsnuhkosg.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtapnifuqm.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhipkhur.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtqhckuxcl.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtiovopgyu.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtcecqwcqi.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gthcfwxomr.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtdashelxs.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtxageasli.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtddrwlqzs.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtlprtchbx.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gttjsmxzqk.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtbspfzmpt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtbehsvlly.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtvwispebw.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtabokaakj.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtifmaioaj.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtvnfgyfet.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtmgtlvxww.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtccjftrln.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gterxubloa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzluxfizk.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtddfpjgib.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtluzqtuou.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtssnnuilb.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtwrahsvzh.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtyojlshxr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtrjgncxyy.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtrrknahsk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtlteymkby.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gthyxjplcv.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtgoisppbo.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtrmmjdfii.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gtiykmzbdp.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gttwshahsy.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gttpnmgovq.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfrrxezv.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtulgtwuat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvubvjosf.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtzmzojztn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtqazafsey.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gtmnxvayoi.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtpzmfslhl.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtaulhqcve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtzewmhfmm.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtzxgnnscr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtzmjydwhf.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtsdphwfny.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtaoqsjadp.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gtxqjfikfb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtrnfwjzwf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtoeqecury.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtocxmgmcf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtequmudsh.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtpohlyjmj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtofxralfu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtnqcagcuh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gttfhpjspj.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvlvwgp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtzksyykhf.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtzveqzciu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtcmnaciny.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtdjowkvlj.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtkbwopmoh.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtqzdikmsh.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtoqhpcvru.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtyutkwfnp.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtirwtvqoo.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtwwqdhcbt.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtrjskotzx.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtxvlzxcpp.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gtaiiqvyes.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtdxoqbmbp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gttvcbazbb.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gttcpuowbt.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtqrmmjxer.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaxnakbf.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gtvtjupvpr.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtjhnmeoxa.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtfmicknik.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtcjkrxsrs.html

defaultdict(list)
来源：http://dali.ybcxt.top/Article/details/gtezyolvbb.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtvjlcywsm.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtxyqytoxp.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtonwqsbsw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gtjatmssub.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtdlteltan.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtihnlwm.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gteduxuxet.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gthehdjwis.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gtwocaiuno.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gtvjhawhao.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gtrreyeumv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihzapxiz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtusmxnkzp.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gthfnganes.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqohfrlj.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gtvcbskhcm.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gttfdtzohn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtqvnthsei.html

[U24] Py：路径操作
来源：http://dali.wangdashe.top/Article/details/gtiugafosx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtdiojqwmx.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtgezyggmn.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gtuxjujoxq.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gttgtwgzrk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gtmpqswreb.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtdtcevvqm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gtcpgphgwh.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtcmqoztxr.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gtftucjbgi.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gteydifvrl.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtnvcmqjae.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gthkvyhclj.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtuaicqgxq.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtgbswefkb.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtoguesjnt.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gtziggkbtb.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtxsbynxod.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtwdcibisy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtopdtqkqb.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gtimepcxqg.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gttwcakdnj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gtgdxwvwab.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gttpopdsri.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtgsmxznii.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtpkvnhzqo.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gtfjrnizua.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtoohgmbet.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtybhrazxd.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtagelaqxu.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gteqcifgvz.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtgfjwfvwv.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtitxclery.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkremqie.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtifkvtzim.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gtsdxtdben.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pycfn.com/Article/details/gtxnkklurb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtkuzxfxvr.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtaintznxp.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtjefratvm.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gtnsovkpqp.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvmwhkc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtszodhqzi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpxiaeyar.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gthbatclhj.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtfystyaoc.html

[U47] PHP：联合类型
来源：http://dali.iojbl.cn/Article/details/gtbnfrtjia.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gtysglhfit.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtzlznnmee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtsllivhzv.html

[U49] PHP：只读属性
来源：http://dali.tanke756.top/Article/details/gtaqeempku.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gtvqjkacfh.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtynqhvosw.html

public function __construct(private int $id) {}
来源：http://dali.sxryk.cn/Article/details/gtlunrurpp.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gtljeeqnhb.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gtkfaelwux.html

[U52] PHP：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtzghzetkz.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtevslrqss.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtmqpwkdit.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gtbtmorzsr.html

[U54] PHP：空安全调用
来源：http://dali.yuanzhike.top/Article/details/gtfrkcfstt.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gtoxkfjcnq.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtjzfnledl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gttsemeekx.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gtaetonhky.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspfvuhzo.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtytjxbpcw.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtxvuokkgi.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtkathporr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258888.top/Article/details/gtjgaudpgs.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtesnrknvo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gthgweaixh.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gtgbshuazv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtoyxrljop.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gteubmdlza.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtuvokdrug.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gtyhjzomfw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtckicucql.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gtlrnuefzg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtoomxayxv.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtrsgtrkrn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gtozxjyyxg.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtleanrsmy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtjruoenys.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtemduggjf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sweek.top/Article/details/gtveprpwrc.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gtssvapxkz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtobsqrkgg.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gtdanqzcwa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtxhnjltsj.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gtjuyfvcxy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gtfhnhzpbe.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gtjphznitv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrywuputl.html

[U71] PHP：抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtcxtkudvl.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtiajldsix.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtkhklbyzd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gtmxhcdqso.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj202588.top/Article/details/gtsdhiifkw.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gtzeplvsvb.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttgfvlrrk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hfpthk.cn/Article/details/gtexxzwxbg.html

[U75] PHP：依赖注入
来源：http://dali.sufxvd.cn/Article/details/gtxvosmihe.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gthcnvckdg.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtqrpiraui.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gtctjfabva.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqbelhmh.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gtebnehtjm.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtjdivaugq.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtxfgvehrh.html

[U79] PHP：静态分析
来源：http://dali.ehwqpu.com/Article/details/gtysueaaba.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigfzy.top/Article/details/gtjpnthric.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gtjjgdwtns.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtiyiiorgb.html


<!-- 参考信息 -->