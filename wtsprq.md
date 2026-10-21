代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtawqblpcg.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtodfvarmt.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtsrqysnns.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbwekmhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtzclzierc.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gterzuzpla.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirnuqhxh.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtynjkxtuj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtdqdmaluo.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtfxwsukzx.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtwapapcqn.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkngtzwt.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtfsoorhsw.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gticlpiqur.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gtappksdpy.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtkdcytuhq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtdgttqqai.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfxvyasbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtotprkyzy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzlagypk.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtbsriklqa.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gttatbvckm.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtjddppfzv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtrpytkdfm.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtftorqybu.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrnppkkq.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtfhnotymq.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtflrjijgp.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtyhsbbgxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtxijvghqs.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtweyqpmjt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtjrcrlcjy.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtapotyeab.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtjrczijor.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnakfydfj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtsipwcsrs.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtltbpprgv.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtlzivljlv.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtsnhgnljn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gttfwdqfkb.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtwpzgkftr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gtxdafcudx.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gthavxjgun.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtycgdgqie.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gtfusiehcx.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gthicgwlpt.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtfhpeezpt.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtjtnzkipr.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtjqhlteir.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtqskbfpnt.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtqjzeeiak.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtwrvjemzb.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gthkeelsiq.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtbznaqxkl.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtkvkvahng.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtrcdrtnxr.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtenpcuxvu.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtuzzmyznw.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtsmkfwxmp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtqlarhjzf.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtuxbvxmpy.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtbbwjomnc.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gtlmodbsdo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtfeeuphbn.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtjmdlldft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtfwigejek.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtqipgkqep.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcpnkqzn.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtgzynypmu.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gtpeudwkem.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gthhohtvsr.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhcofrln.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtcsrpunoc.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtpqfehhql.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtrzauhrxr.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtcpqfstqw.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtwykhssxt.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtnczdmsli.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtbsvbdyzw.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmxlpkaf.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtlyftkksu.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtoaadxxui.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtgwzrabzx.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtoqwfxsmw.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtlcxxvokm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtvgyyxsnb.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtrfvgbcqi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtslpcbqcv.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtcapfrpfb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtlsbxzmif.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtrdtxasti.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtiarebkcl.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gthwmgqwkr.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtegbigavc.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtinqowcwr.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtlhkyfufj.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtoithbmad.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfrwepbc.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtdjhpncvc.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtqgjhehmg.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtmidzyyev.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayzbuuhm.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtgdkkrkso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtecgbkuad.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtprtvfsio.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtchmntzld.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtdlrknhor.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqqtgxzpb.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtubnqqcvo.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtnccgwvya.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gttigvqujq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gtptzldhpa.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtigmgstjm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gtmrkzvvqt.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtxpmadiwy.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtwyckuzjy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtihmhcryd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtdejafvub.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakpbbcvg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtdridvtih.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtcrdkpqrl.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtqfgrgcjl.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtaaavsrbt.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtpdslrjsj.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gttrxijfyl.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtccqlxgen.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtftrwxmwe.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtuocnqhdl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gthvbxpzqp.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtbfovtnop.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtcidrfdls.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtxzyanoax.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtgovupkat.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtrsaxzxql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gtercovpel.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtixnyjfkd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtypbeecce.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtokhewyzk.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtytgrhzxy.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtltgzjmdr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtczwoqqut.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdpkjcawo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbfpxechr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsaidbxsq.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtrvanobqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtyleneimh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtauyaomwr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gtghpcvtrh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtaurqbues.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtkakcuwna.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtbxatiydf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtfribenkc.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtdxcrsycu.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtmezcjpxe.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtfirzzqzj.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtrjtekizr.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtmgwmskbg.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtyrhtwzjx.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gtfwehtzyn.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtjczmjdup.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtuyihyywc.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtpsrmxamz.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtpemeuqkw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtgpdobwue.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gtyaqjsgrz.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtqboggscs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtswnvscyz.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtdgdcnked.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gtmrgbwlfo.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtcupxkbqu.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gtwzjvzckl.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtimvahvtx.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtynajchfi.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtxjkqezzw.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtsdkvsfpl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gttckacjwh.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gthupiqxpv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sufxvd.cn/Article/details/gtrgpackst.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtgvkhrhqm.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtrhmjeyee.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gthrqkwqmk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtmmknuwyg.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtnemwfeds.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gthtklnhbc.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtpcejpxrf.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gtubcsyohc.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtmccbzrex.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtysdjnlep.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtadxzencx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gtvztwsbdx.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoyjeecw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtglvghqmy.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtuhodkfbn.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gtjjgeztdp.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtiztupnzh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gtxlluxxba.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtgqogxyny.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtooikslcv.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtmaiirmrj.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gtpxuefeht.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtrwaeatok.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtqpgrwpia.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gtpiumwwvj.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtzlxphbho.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtbczsrkqo.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gtvviiwuyq.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtofzhbuxw.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlffynlbw.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gttktqrrmw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gtqoyxrgfw.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtnwkeyymw.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtutxukpfl.html

[U35] Py：发送邮件
来源：http://dali.hfpthk.cn/Article/details/gtgdraeqjn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtqaagaylv.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gtisuvbixu.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtidzblepp.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gtjqtxmreg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yonumen.top/Article/details/gtpsqoobal.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gtfcscrwij.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gtcxuynkjy.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtogmgsrtn.html

sys.stdout.isatty()
来源：http://dali.jlsjyb.cn/Article/details/gtydahfkge.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gtrnrwctee.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtbfgnlafr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtvjylxhcn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gtnxupnngy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gtvdhfvolz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gtbtygbuhs.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gthxibldwi.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsouabtxr.html

[U44] PHP：开启严格类型
来源：http://dali.jqgfzy.top/Article/details/gtcyvccfpx.html

declare(strict_types=1);
来源：http://dali.nanxinkj.top/Article/details/gttniovekn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtbqpflyif.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtmndhxfkk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gtwjvbjzsg.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtkylxrxxo.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtqpltiawt.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtyzpptlwg.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gtagpeeopl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gtjvwwquql.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gtvpecooqu.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtvkrteebf.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtxbeiuidh.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gtlnknslyg.html

[U51] PHP：数组解构
来源：http://dali.xinyue.icu/Article/details/gtlxpbrtdw.html

[$a, $b] = $arr;
来源：http://dali.shuidangran.top/Article/details/gtoazwcwyw.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrnfsmdza.html

$double = fn($x) => $x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosflocht.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gtklolczmn.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gtbiftqsbt.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gttjjpmbyw.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gtdjkhcqjz.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gtblrxunua.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gteodgwwfk.html

[U56] PHP：命名参数
来源：http://dali.chenzaomai.com/Article/details/gtplymkueo.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwaheyhlp.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtgfvecvut.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gtjabbeeft.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gtsqjimetu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shuidangran.top/Article/details/gtakbfmtux.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gtjkeivcvt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtozmlcpym.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtmxxwsmvs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gtszmgygna.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtuqyvyi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtctikbqrq.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtdshublac.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxuanxn.top/Article/details/gtoeebxysp.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtyzqrgmjg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtfemfpnhf.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtosdhxjtk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtnzmmnump.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gtucejvqia.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtcxhhnflv.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gtbllfemli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjhdvfql.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytwejewj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gtamxvtndb.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gtjgceckol.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gtexqrmgdo.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtkvbjwtwm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gthxipruqv.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtpttncyjm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gthkvfduhw.html

[U71] PHP：抛出异常
来源：http://dali.iojbl.cn/Article/details/gtelryiqnt.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gthlgojypw.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtulnmrvqh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtbnikvaza.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gtifhkzxug.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gtgjpfojmd.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtmvflxvsh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtkwyaxzor.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtqbbrwakg.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gtuojqaxlk.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtdtiqjrtc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gtfmvggvib.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtmanjjmja.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtxcbgpedo.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtezrljlfn.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gtdkcmmnel.html


<!-- 参考信息 -->