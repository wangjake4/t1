代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtmqsumgla.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtkvdrvoka.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtgsfnpxwp.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtzqqedcnn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtkgwftdlj.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtknyqhxxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtkphkqmjq.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gthakiohlf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtbuikrsyq.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtjuwhoiwv.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtezlbjsus.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gttaxxfljm.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtywuwfyub.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtcymwxraw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtxlexaacc.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtwmojppir.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtvgqnvwun.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtndrxvvpf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtvhcrsahj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjprzdwpp.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxdvfihic.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gthkqvmduc.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtyyazlezv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbvlmwtl.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtzhxqbdyd.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtkzxifujj.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtpzkqamao.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtkexxdvre.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtodqrfptl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gttzehkkgh.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtavdjgxku.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtquqjzmwb.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtczrufhjk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gttoaqlzzc.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtolyexmqh.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtlhjugfjt.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtaqtexttj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtdcmowzov.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtwrdzymsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnuzhlag.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtfdvqndkq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtzctvsbfq.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtpshhvmrr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtmwysztlw.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtplbblkip.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtgviftebw.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtybjfouav.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtialkseux.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gtephbaxom.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtruwaopmj.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtjiitvdbm.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtgvetuisr.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtvsmcekia.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtlghipwob.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtvpfqatpd.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gteybyhvao.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gteibglxnv.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtztbewqvf.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtoybghbyh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtfhgfatyn.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtousnqzgy.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtvcxnkqlu.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtutvlepez.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtzcrbfwkl.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtbkmvllfz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtnwpunwni.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtcqwzgaim.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtsdaxmlnf.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gthhhkssxz.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtfsgkfkzo.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtygtfytul.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtsjrfhovz.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtjzcsrayr.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmpjmlyvl.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtsxtxtsfr.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gthpcixpqh.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtcsykkszc.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtcpjupzoh.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtqlqynocg.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcaimsmh.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtcgcdkyyb.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtsfmraheq.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtjxccddpv.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gthovpbvdb.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtpmslffgs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gtxehwmphq.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtypftftfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtlvuhmyfw.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gttktnnsch.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtmyausovx.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gttzuxqrtf.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gtogmtbtrs.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtocrmshzj.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gttxhpyuwa.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtrqzuguxz.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtcquhwueu.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtfafinwdu.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtkjuihmeo.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtccphmfym.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbbwxrme.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwwgirru.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtitaifdcz.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtukkrotdj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtbqxxtlhm.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtdbrnssnd.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gttyxftklh.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtzlriwiyd.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtrcmljkgx.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtnzsgnkxc.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtjuuhkekl.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtnvdutvsc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gttuidxybv.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtvtzjmwyc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtbufteikn.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtqauejcsk.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gtryfvphhr.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtjdmdzusq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtzcgmetcr.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtkbdzwstd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqjavfts.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtgkttgtqp.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtlysqpefu.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtillsvjcg.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtkpqbnjps.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtuwpjelbn.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtggqkovww.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtgkqkdjtj.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtukxlhxqh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gtyfaxrgwq.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtzaqlvnqt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtnnybaxsg.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtggtgmdav.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtmnscygse.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gthyynkgpi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtzouwwqzf.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtixkewtnt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtelzkjghk.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtkrktcbml.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtnduojdbb.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gtoauedrto.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvxsfuzd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbnwnprju.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtggpigpbf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrqkqtoew.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtcacnezhi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtqnjwigyo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtlnysuqiv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtzjpfoiys.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtbgwytzwd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtoubkpbxy.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtfkivwell.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtfjfuqywx.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtwiqscfzx.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtuujfftve.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gthkxfsciz.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtyshgwtzm.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwwsobrq.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtwhnlgiiu.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtkxfppshw.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gtjqlnpivq.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gtnbeyjgen.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtggzvdhfk.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gtrzqlgfar.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtdevchxak.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtvenbwgko.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gtyiiixhcv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gtdgyzqhjb.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gthuyoyfer.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gtwqyeyndo.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtqlwlxiyi.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtixddwbay.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gthdrkhphb.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gtulothgqj.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gtfiiykxbp.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gtqqrpcbkt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtymdoutcz.html

[U17] Py：初始化日志
来源：http://dali.hnxiangtu.top/Article/details/gtwibuhanm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtonpmuxxv.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gtykiwlkxe.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gtetksepvg.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtewjfycwx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtsmbidmcn.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtezinsxaz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gtwthqxvcb.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtsfhuixub.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtxuvkqmjv.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gtqxhcukdz.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtuydvkbvf.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtaxdxertz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtsvgtrpif.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gtikgoroqt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtejejhbri.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gtgesvgmjc.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtmakmabru.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtxjbumipz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gtggxfjodw.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtjbsldejj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gtgmriyrwg.html

[U28] Py：类型别名
来源：http://dali.xziqi.cn/Article/details/gtswwkqqfr.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtwcszrign.html

[U29] Py：属性校验
来源：http://dali.zhiwuduotai.top/Article/details/gtdiqluevc.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtkrhgmnjk.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtdsiyhdvo.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtvmnsttdf.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtkwfwzlbf.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gtvlebtxuj.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtdptbjkrd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gtbxxsxjbp.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gtuipidhal.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtnftfmoyw.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtttmtzmqu.html

chardet.detect(raw)
来源：http://dali.yj20258888.top/Article/details/gtzqsewfez.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtdddbxkoy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gteleulcyb.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtvuixnged.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtahcfmpic.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gtnvpcbwit.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtxupfhszh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gttoguaisy.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gttivirrpa.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtpwjdoshg.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gtltqvyuuj.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtyoxslzjy.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtcvwzbgwa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenlongwang.top/Article/details/gtzdrpilmi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gteccfasbk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtlfzdlbhp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gtyiyyovvy.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtmhmiphqh.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gtrtdqchau.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gttbosddhl.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtanfzcwtp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtokizxfvr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhoyegnn.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtmxvzssal.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gtqmtjlzwa.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtbquidhxr.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gtwpyseqtp.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gtjlclzhbx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjywtniyq.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gtuhntygyh.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gthneiaotl.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gtjqruhmiu.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gtqaoymbiv.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtkrusshuf.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtgfqhtxal.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyjceizt.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtcwujhuut.html

[U53] PHP：空合并运算符
来源：http://dali.snrcjt.cn/Article/details/gtwbpkcctg.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtevekyxfq.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtcceyordg.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gtegvhkkcl.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtncjzmhfs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtzcggtqvd.html

[U56] PHP：命名参数
来源：http://dali.chenlongwang.top/Article/details/gtgtcxhget.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtpivnpbqu.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtkeqvkyrs.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gtdxalugsi.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtdhvjhokx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sysykeji.top/Article/details/gtmybvciua.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gttqgdrnpd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtxjokhpcw.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gtmevzlrsd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gtdqpvffxg.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gtetzzcitu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtjaqngqvo.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtlcbzfxqd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsuwxfmm.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gttvpjvkst.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gtrqttyiqp.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtdjhvyjgb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtfbpwstxf.html

[U65] PHP：会话
来源：http://dali.sufxvd.cn/Article/details/gtdsjvleth.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtwihttqne.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtotvvwglp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtrkrmozxk.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwdelqoh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtggjcrdgu.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gtcfsucrti.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtwcqzndxd.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtaqjdtrvw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtmrbnnisf.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigfzy.top/Article/details/gtvczykxxc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gtolaflvav.html

[U71] PHP：抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtgrqlhlxn.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtogzconiq.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gtzvqzbwax.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtyeczbnop.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gtirypmnki.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gttcaiphxf.html

[U74] PHP：读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtfhtsahdn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gtqnqgrmsj.html

[U75] PHP：依赖注入
来源：http://dali.9152youxi.cn/Article/details/gtbhblyujr.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtslnmwcne.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gtjiuylohk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.havefunace.top/Article/details/gtwrmqtito.html

[U77] PHP：模板渲染
来源：http://dali.hnxiangtu.top/Article/details/gtlzkzdsqw.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtgfgpstzb.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gteheteupu.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtojjkvylf.html


<!-- 参考信息 -->