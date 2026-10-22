代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtwgbsyvnu.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtzpgtckmh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtlraaibdy.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtdsjtvgut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtljznjjua.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtuyokjwmx.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtvpmilwuu.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtckntxzor.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtewexctpn.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtqrjdhofa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gttoyiybzi.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtduzrztfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtmratffux.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthosfpfuu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtcholmcwv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrxegjcvn.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtbinwziqj.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gttjhnxsyc.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtstkgpspc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtjpkgqstl.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtuzxrizod.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtrxheiehz.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtidmysorp.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtnwvfdvih.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gttkuicpkz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtynetzwpt.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtjpwfzrtw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtaozshntl.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtzaaxekun.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtkqdpsxnz.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gttoubjzdt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtgwdoknsm.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwayytwnt.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtdjjnpxqz.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtzqeifydb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtdaveodke.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtcuhpkhzb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtckcipzkq.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtxkefjrns.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtvqxarkiu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtumgeslwx.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gthulkkmuo.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtytpolndb.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtchnzrkez.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gthodcdwtz.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtmvlppcfc.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtutfnujho.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtyadgnuit.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtqibqokjr.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtpkcszlic.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtrjaeidxy.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfysrqlk.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtnrtqiaiy.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtgkqrzoqo.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gtmjoicgox.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtbjctacxy.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtzkedfjav.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtdjshxszd.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvamqtgne.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtbczacbfm.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtigxijqme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtjlvyztis.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtntncwpjb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtowpdpsyw.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtjtbsqsys.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtdazwjjic.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtxtkrqcla.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtkzgsehvw.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtasllieif.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctxbsiwz.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtqrkxrajp.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtsckzceef.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtfenschcl.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtlevcmgjx.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtmhpyogvk.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtttmfozml.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gthelkzzas.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtasmsrtdf.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gttkusuzgc.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtuezzqnge.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbaorsvh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtrcwycvla.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtjdyyopbq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gtlzmkijme.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gtqbncpxtt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtyafwujzx.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtzaobeyrw.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpaxaemt.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtzkzdeycy.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtdxydoaab.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtiwofhwzj.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtmvxarsca.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtabzcvhjh.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtngljxewg.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtfuteeomn.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtdowqvvdt.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtddirokkl.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtwguqshrs.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtvorgaror.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvicjvpm.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtbmebhycg.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gttptolcrm.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtycvuetzc.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtmthxctke.html

[T45] Perl：数组遍历
来源：http://dali.gotoacloud.top/Article/details/gtjnzcszzy.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtnvbjwane.html

[T46] Perl：哈希操作
来源：http://dali.hywenlv.cn/Article/details/gtixirrxez.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yonumen.top/Article/details/gtmcwdmqmx.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtgnomnizr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtornojpxu.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtcxqwtbpn.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtgmdujbnb.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gtqmbttmun.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtogkzzdzn.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtpwfjcfoh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtfhemrnol.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtuvmbmwfi.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrdwbclcf.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtzqponygx.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjjespvn.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtvwdwomtq.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtzmkgbiyw.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtvizpuubh.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtuutatzen.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjgfdafos.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtuyzuolln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwdqyvdg.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtqideyynh.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gteqinecbb.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtvhdqwpos.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtkzcqwaeh.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtaptvvate.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtxrdbbaxw.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtdyvkbtux.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtjrfmvcyq.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtzftzfhjm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtufcucyct.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtthfzcaiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtfsfqkfjr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoogjtpak.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtutdetcxn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtcrmudzwv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258888.top/Article/details/gtvxyhubgh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtrydkyzmp.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtqhiyrycv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtvuqscwog.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndybdrqw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gthrklrfcl.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtzsmpzhlk.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtgnpoqkla.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtcuswkxpu.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqpbdgtz.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtlenwteuy.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gtaoggtxvq.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbnpegio.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gttipjwscp.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtbpolaxzm.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtkxbgaoxa.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtfwhwrylq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtxnlrzivf.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gtdsboezrc.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtwoaqkqec.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtehvvpjdf.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtyogsaiah.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtquqyzyqv.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gtblybqcue.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtpurxfsae.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtgqrthtrg.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtluniersc.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtzqbqmdau.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtoqsysiwx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtqmjisqhx.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxjlrnwj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtodvwutxw.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gttdemdqit.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtuxxxqpdz.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtgrqxccdg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtfcqvbicx.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxiuvzfj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gtucaznqcz.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtbgtezvpa.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtqtadeajg.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gthqcucdsr.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtmewfsdmo.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtoqgisvdo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gtkorvnjyj.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gttwysvvms.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtezjtkcny.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtjzszupkh.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtbnlobtuq.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gteoaxsama.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiweyettb.html

[U27] Py：异步 HTTP
来源：http://dali.birdmap.top/Article/details/gtjgffqxyu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cheryme.top/Article/details/gttoxvfpmg.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttccswih.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtggibtrer.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gttrduyqnk.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gtfhzktzyg.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtpdjsmmul.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopfrwthm.html

[U31] Py：单测
来源：http://dali.sufxvd.cn/Article/details/gtilnbemzh.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtueuksfyg.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gtvdufzokn.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gtniknqmuy.html

[U33] Py：打包发布
来源：http://dali.sweek.top/Article/details/gtrqykffjh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtsmgnfozh.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gtjjwsgril.html

chardet.detect(raw)
来源：http://dali.pycfn.com/Article/details/gtlmlqvsvn.html

[U35] Py：发送邮件
来源：http://dali.jianghu66.top/Article/details/gttkukabsh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkfvmjdh.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gthavkqdbs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zycfv.cn/Article/details/gtdwnlstdb.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtwwrwfioc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvejxfkl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtxdbitgsv.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gtwkwalmaj.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gtpqpbmtmu.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtwvvnohqz.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gtllvlzdao.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtvwstgsgj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gteyaghvdk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtnedsbkdw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtmosycbij.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjwexyco.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtuurnvxti.html

namespace App\Http;
来源：http://dali.wangshuangyany.cn/Article/details/gtxzgtejqj.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtfljaolok.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gtaicrxmpl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtqgbetrew.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtkqypuffv.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtklithpzo.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtatbfgcfl.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtjddbqons.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtblfpetcu.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtjwzawtvg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtkgqgnigf.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gtsbygsain.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtqsvqqcmq.html

[U50] PHP：构造器属性提升
来源：http://dali.vqdsnc.cn/Article/details/gtcxtujdrj.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtkzkziyko.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtjlphzzxd.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtprvfgzhc.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gtndsvzxxs.html

$double = fn($x) => $x * 2;
来源：http://dali.xuanzx.com/Article/details/gtdwcvhejk.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gtamkxuwfh.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtpnbxbbdw.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtlekzorme.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtyqszkuuj.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gtxsrrxrwc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtwccoffcq.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtqmsdbhue.html

f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtvhmjtudw.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtmyezfmme.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gtekfcpkvb.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtzcpgudkc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gtivrnoxyh.html

[U59] PHP：自定义排序
来源：http://dali.yj20258888.top/Article/details/gtjljuvcnz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtbtykpxtf.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gthznludch.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtmcyekibl.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gtqhpozklu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtdwszzdam.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtumovwjpn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtoovfujzi.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gtinnijpij.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtulyimhgz.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiyaoycv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtrmhsrock.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtmarkuuen.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtuorkkmpp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gtryhxthos.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gtzguosigu.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gtbeyjilbl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtlxfcpiyz.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gtubnehwhb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jlsjyb.cn/Article/details/gtatoqgkue.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gthujanyvb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gttgiemwtj.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtwusipukr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gtwumwlebl.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtbxfbzfot.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gtrodbujrk.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gtqyebaqfh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtivarghyt.html

[U73] PHP：读取 ini 配置
来源：http://dali.havefunace.top/Article/details/gtdbghpxhi.html

parse_ini_file("config.ini", true)
来源：http://dali.gotoacloud.top/Article/details/gtkdhnfukw.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtwjrizpzs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtvszcwpqc.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gtqfoksorv.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtevjovxbb.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtmajuqysk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gtwnlziajl.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtrqkqmfxk.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtaxiynjzn.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtzgweveom.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtgmnolzlt.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gtzmskomug.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gtksdppcng.html

[U80] PHP：代码规范修复
来源：http://dali.ppjwa.cn/Article/details/gtsgvpmadk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gtmmtsfmmu.html


<!-- 参考信息 -->