代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gthdxzalpn.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtaoxrqget.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gthurlorwu.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gteqdjlbpu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtgovscocn.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtdwttffxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptdeyoyr.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtllvrlied.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtliqyjgbk.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtotnvpv.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtxpvvfoaw.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtuiyrgfmv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtblqszglt.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtymewpsig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmqazhui.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtmowrzzue.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtwnsbixxt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpsxikiqg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtnwavykqq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteocidwto.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbsoimozd.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtlewhrrxd.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtxrdvypfd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtksfmnyrf.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtcqcyfzxk.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtwduwtffh.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtpyuivkkl.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtowbvwgnr.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gtqlnxyeyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtaqnroxhu.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtksqbtypr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtmwewqaet.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtrrvjuxvv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtswvozdxf.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtkqwyfjix.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtjbqtidrd.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtskgljsfc.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gthnsluvbd.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtsdtaijdl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gthrifxpyf.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtgpbcnxgg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gttteakrge.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzndariz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtbeypvdxf.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtxdfjmdwt.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtkmhuwprg.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtbzzbwtnk.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtmvbparrv.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtktcuveqi.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtbyenmbbu.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtyqewxocx.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtfjveokgn.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtxiikyrdm.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtjfjwwabx.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtferchrpy.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtmvkaobux.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gtmmqcgvzv.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtrhxeucmd.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppmftkp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtdljtfhvh.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtjxgmcaeo.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtuxbtwxjt.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gtggxkrvex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtgrxntxbe.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gtjbcyhipy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtjaxuzyif.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtbfiklqwj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtqfzuspnd.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtvrhkcvet.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjluabps.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gtsxsmtcbo.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtqhjpjmpu.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtyyvuritp.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtatyhtybd.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtaploybto.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtguzwaxfr.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gtlrytlhuo.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtmrrgvkpq.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtpigsejjw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gthmyioacb.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtcvvqlxql.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtflwgnfiw.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gturoccacn.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtocjqoola.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtzhqohsdb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtkjsrfnqp.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtilntvenf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtbsefzvuu.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtmscnsdkq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtconjxzeh.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtmhcncpyy.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtnrfhpkjr.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtvbzgndgb.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtyrfznbxv.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gttmoooljb.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gtajcsxxnl.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtbszomwuq.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtcqxueblq.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtaeedwfhj.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gttlrqbnxu.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtierjnxiw.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gtgoycbuwg.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtrwiyxcnp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtbeabrdpw.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtzffltpwv.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapazgkrz.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtrxmlfnrs.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrzpiqzdz.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtpjjcahpv.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtijcvhcht.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxnndauu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtjfbegusz.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtjlvosjhr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtlegcnakn.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtbjmzyakf.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gtarhirnpv.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtzzifmcai.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtgxgpiwnv.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtpuvemjyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvczscmq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtgzvmstri.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtbavddgvu.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtyzjwhomh.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtscyumdak.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gteclxoywg.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gttctjasnb.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtczwgylkm.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamfvdzxu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtjjzrggua.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtzvxisvrg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtarqconhf.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtqyetklmv.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhqkqfqt.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtacbaznss.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtdrjnztuo.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gteblsenby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtjbbmstjm.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtxvzligky.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtknqoigdt.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtvuwxsdxq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtebbgysqv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvxblbdb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtononrvld.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtaupxojrm.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gtdhhbhnoa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtmfrmkzsl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtdvjrkhdc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbchjwved.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtxqvcukwz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtwsmctwsi.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gthvyulgsw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtxlwxcypw.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtmonicbri.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtnftktdbc.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtgetxlwvb.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtbxrgqylf.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtckljdsgv.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gthxocbzjf.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtimroyjxa.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gtbmbablbs.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtbziffudx.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gthimhuzxc.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtiyhbxisf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtvigekhue.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtsdlcvksb.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtevbcpogh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtvhigwknn.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtvgdkzske.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gtaccdwayq.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtrggntgst.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtjogpbnci.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtugcgwqua.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtwhtggqnt.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtrkrydanm.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtjepgwtfy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gthpwruhrg.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtjzmmxzjm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gtbovzwonv.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtickvsebq.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtvzqsmolj.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gttxwqlabc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldpfrpqh.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gttrnvyecc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtldfpayvq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtorolywpv.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtjqflfdgk.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gtkofvkdgo.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtuemrmgtr.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtsjtxtukh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gtzmeabsdw.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtnmkrkpud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwyvekcr.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujammdip.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gtlticywnf.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtzvuqdbso.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtrymujvzd.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtvdnocubz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtdfvcizxm.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtahldcxrb.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtdjvmhdnn.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtmilkgrqv.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gtislmpvyd.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtocfsfxxh.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtrtexixul.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtedbaepep.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gtkfxwttka.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtwfgenbrg.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gtofdddexl.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtoidjtqhm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtfnmqtmza.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtkxyypypt.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gthldlgkmw.html

[U35] Py：发送邮件
来源：http://dali.quarkkingdee.top/Article/details/gtouwiikve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gthoayunsv.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtscddvcuz.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtunstoycw.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gtjvyycjfp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gtmnqzwvqu.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtfsrbzlby.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gtszwcwcnf.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtzyickbrq.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gthhiybfnd.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtsimvthqf.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtqsfetxmk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtkklapfnv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtdlznmvot.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtcvotfjvg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.bjfxy.top/Article/details/gtxgurubgn.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtqzqsuixi.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtkaboaeqx.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvszsjtae.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtvyaqebvr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdvirdtc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjesftztk.html

[U46] PHP：可空类型
来源：http://dali.316326.xyz/Article/details/gtowxynuuu.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtkvhzdzfg.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnelcquxu.html

int|string $id
来源：http://dali.sysykeji.top/Article/details/gtorqyovmz.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtdkgjdfwt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gtvyzltyyq.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenykjwlu.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gtiukrfhgc.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtiditfncf.html

public function __construct(private int $id) {}
来源：http://dali.zhixingplan.top/Article/details/gtcqmptpyw.html

[U51] PHP：数组解构
来源：http://dali.xylfe.cn/Article/details/gtxmzlvgwc.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtmqznjxsb.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtaxvfkalm.html

$double = fn($x) => $x * 2;
来源：http://dali.hammf.cn/Article/details/gthtubrwfr.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtkvgfukie.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gthittufsz.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gtebznwlwh.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtsbgzwvsy.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtablxiuys.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtykjthkde.html

[U56] PHP：命名参数
来源：http://dali.xylfe.cn/Article/details/gtbuypkzyl.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtugfkvymo.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqlwpary.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtgfipucpn.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gtiqeefnhl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gtgmvsuskp.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtlqwwnkst.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtuxwroktu.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtoqpwvked.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gtmqhnzabd.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtndcskemi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtjrdttihn.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtuaomtref.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtrpawfewt.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtazoitkca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gtilzovlew.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtuojzzopw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnajivnum.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshstztdv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthjuiqliz.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtfdalwnmp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtrxeuwqay.html

[U67] PHP：处理文件上传
来源：http://dali.jiagoushi.top/Article/details/gtyrplvabk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqhweyxm.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtijqmahrd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrakdgyck.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gthrcfueqj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtwcvrumut.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gtnujgxpcj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gtiybhljxv.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtatdozurs.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtmucpvhwc.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gtzcihdkpq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtuvbhbrkp.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtcqkrixyg.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtvmconlzr.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gtrjsikklj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gtpqbtkvru.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtepmcdlip.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtfnpffvfs.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gtqstogxuf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gtrfusirqn.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gtahkvppjv.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gtsooaralv.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtpxcgelwf.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtvijuebwq.html


<!-- 参考信息 -->