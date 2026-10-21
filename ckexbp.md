代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvqrsupg.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtsjyidpbp.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpmbhhfh.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtchohjgst.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtfbwckuvq.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtbjzipvrq.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtrfvhjpsf.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gttuoualnd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtsldwwzao.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtvnnwwgim.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtxkokapns.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtmatzyloo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtndamdsjj.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtalxcyaqn.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtxbxmahfc.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtwahrtqno.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtrlxkuoyj.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtzosmbrgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtmeutjakv.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtplwrchew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtwvcmntok.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtafzlnaxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtcyrsgmtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtaakofzfs.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtggdhaxfn.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtisapgzqc.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtqyaguwnm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gtroihlweb.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtvnleuqpd.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtybtmpdsq.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtagqkbdup.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gttwqknpwe.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlisskkl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtzjkszkzp.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtfykjvyjw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqsqzofo.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtmreyurgb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtzajjjyyo.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtlpbfrrlw.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtcelchphg.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtbbifibhy.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtufqfjino.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtlmcrsmxa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gterghailt.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtioplouki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtprnidpmr.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtijhszicc.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfyvantfi.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtarcopmcx.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtvuqzuxdq.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtjgosjrnu.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtnztlmxwk.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtqsekdbbp.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtuznbswqi.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtodhvrxhu.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtdqletciv.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtjazbeefr.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtecnrpnid.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtgbaxqmxn.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtkzyqzfbj.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtltsnsacm.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtrejwzicd.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtcffromch.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtxojcagqv.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtrqwoghqf.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gthiuhkzwf.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtqmyzowrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtwzpvwrvu.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gtsttdilra.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtulucridj.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtdapwtrrm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtydoifqrj.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtjqmfmyby.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gttomvgpub.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtfrfoaeet.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtarsevvrs.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtcszppelk.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtdygvuvnz.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtwaxiirzc.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtehmfuojl.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtdxywfatn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtfgljxzri.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtlbosknll.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtleixelfp.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtdlzkvgya.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gttxlbefac.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtcnhzupro.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtnesgbvvn.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtrqjobrzo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtuhbenwvg.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtfomkwyqz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtnpqlwmod.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtpksdosad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtydrsllpy.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtkbtakvey.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsmxqkfa.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtiffaeqla.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtegbukjir.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtxztmryvo.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtwroawqfe.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtyhurrvkn.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtayomlsei.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtntxwlhlx.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtajzyguuj.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtfxtkamba.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtcrjhwvvc.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtengwicfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtwgwbymmw.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtpbmmzagd.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtkyjopdeg.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gttqfznkwh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtlvvqazbe.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtwcuauxej.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzpszwpw.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gtoivhdclm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtbpfwuvfj.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtpcrnjnfq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtalddhzok.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtxliteqob.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtokshcznu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtjsngiwfk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtshqsodcg.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtkxjbjcbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtmmyadkvd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtatcecerb.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtjvvmxgch.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtfhmdvhzj.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtltirvsuq.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtztpcvuxp.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gteskyvixw.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtaxalxfbc.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtdqofxtoa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtxxgvdlli.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtqnlvojqa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtffvymcyk.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtnshaxemy.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtlviudrrt.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvyvgudgn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtunlndrhc.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtqdpkkthg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gtwuvzoxlx.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtsfbscqdr.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtiloibaor.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gttnxgeagt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtorfawohf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcjvkidu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtmztuxehl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgiizbjj.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtoiicrhpg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtgmuhsfnn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtledeqdiu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gtisrgtoth.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtzsxardtf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtlxpmsldk.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtwzzhltsg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtgpmqxpgn.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gthbqksfrv.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gthftzutyn.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtmbfdmcac.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtphkvbkwq.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gttdfpyaom.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtvudyerar.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtltyuklwa.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtlmpdxuzp.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtmnoymjcq.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtqmriwyij.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtesipwkml.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtashmowrd.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtkbfuuwkp.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtliszymwk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtposkpxhf.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtpzoyhxxz.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gtkyvnwrgx.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gtdttahdnt.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtcjnsyfvh.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtgfqigats.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtsjrjsddp.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtduquyjxv.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gttdmybrlv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtbznssxet.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtowdbjxmh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gtthryqzql.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtfguzhtdl.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtrpzpxxrl.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtozfcjtlr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtlfqniagx.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtsctphide.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gtgsbmiltl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gtypnietpv.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtescdynjv.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gtjlkoryaj.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtzbgqckcg.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtxinezrdv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtmlsnhzdz.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtpkxyiklt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtugjyzrbo.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtvcbrmrrr.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gtduhsavdd.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtsmvuyanm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtfptwaicw.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gtbkypmmuq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtqeljwxxv.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtekgnknuz.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtfjlafuoz.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtwsmohtsk.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtcksqgusz.html

[U30] Py：数据类
来源：http://dali.redwolf501.top/Article/details/gtzwmfjzdu.html

@dataclass(slots=True)
来源：http://dali.sxryk.cn/Article/details/gtteicsnbr.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gtutidceoj.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gtfocfwstb.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtlfhpmasz.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gtltxnlxry.html

[U33] Py：打包发布
来源：http://dali.yongpay.top/Article/details/gthtfitxuq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtuhmhedxv.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gthednjrum.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gtijybjyxh.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtvaidmxzo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tanke756.top/Article/details/gtloxxgpbs.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtljgnbssl.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gtcfxfwjik.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gtuwepqhon.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtkjdzunok.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtndqosfxj.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gthzaubqac.html

[U39] Py：判断是否在交互环境
来源：http://dali.fzhhl.top/Article/details/gtfugkwwfw.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gtvlnloodf.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gtkvcqicsh.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtlztmrhzu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtyjcfdibb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gtwhhchnqx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gtuhhfvkfb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gtiteifcuv.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtbunsjnwp.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtgkohbybh.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gtnjfvsyyy.html

declare(strict_types=1);
来源：http://dali.cucudq.cn/Article/details/gtoeuilxtx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gtexlrgwmr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtxtzwwwbi.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gtlpdwnymr.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gttecqisrz.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gtarnrsnva.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gtcqklataj.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gtjfuksuil.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezwijxar.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtdhctrhga.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gttooerrzr.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtzbmhsyxx.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtfvsjljiw.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gthvzdvmvn.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtsdzyypbz.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gthtoqrwxj.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtndeuexng.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtxwumsbyb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yangfankeji.com/Article/details/gtxohancxb.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gtbgyviets.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtrlbwxags.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuedzuexo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gtaphtklux.html

[U56] PHP：命名参数
来源：http://dali.jinqigufen.top/Article/details/gtcaelavve.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtemmgxoih.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtinhnwhsx.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gtwaqqedtz.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtkgouucdj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtpzszmsfh.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gtfuhaecxh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtrodiqnbf.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gtdtlbsiqh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.c1oappe.top/Article/details/gtilxfovxm.html

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gtusgjvuyl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtnumsqppx.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtgsavvhca.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gtscugefnu.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtxsnknkim.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gtnetgnyrp.html

[U64] PHP：目录遍历
来源：http://dali.0kj1m.cn/Article/details/gtvezluhwa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtxrrjhsdy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtutzncjfz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrsetsuc.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gtuqdprxhw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gtcgqiznuj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtbkallhio.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtvjmyhxvt.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtbqclmqrn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gtfwqzkath.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gtgsknuogd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dianchejie.cn/Article/details/gtwiffiuij.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtebyoietz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtxuaxoogi.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtwwjeihzy.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gtuuyfnqio.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtbbwtmayx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gteoxqttjr.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gthepnknoh.html

parse_ini_file("config.ini", true)
来源：http://dali.shzxlz.cn/Article/details/gtkuhrsoip.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttecqyxus.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gtkwpqrzhf.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gtspylwpny.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlerslrjx.html

[U76] PHP：简单路由
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzixjgzal.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokskxsbu.html


<!-- 参考信息 -->