代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2qvzpcepy.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2heubzyor.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2yiitzovs.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2vbfbacxl.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2imjnivxh.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2xesjljsa.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gt2hgdedpho.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2gknnuqxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2evputnzr.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2nlmtgvju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2shqtwxae.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gt2nltwccdw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2aqiinvhv.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gt2visthvye.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gt2lzxwucgq.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2nevtozhk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uezecdra.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gt2awmiusvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2azfywobn.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2mtpbvrno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2aontdjns.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2xcfpmrgo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gt2dpgnqquc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wkbhqxbx.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwlqkeyc.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2qaosxjzp.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gt2sjvwctdk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gt2ipuabyye.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2pvfwlaiv.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2bzycgtnf.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2kvxpvwaf.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2txqoatvw.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2blxpakqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myakxdwm.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2xlhvsexq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2ypjrxdvj.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gt2viarhrzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2cvbkovff.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2uhwpznvq.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2vldvexdq.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gt2gzebnidl.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2uepvkpfm.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gt2rdksoyil.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2vlmddtkw.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gt2xqgurvlu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2rsgywukh.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2ebwlgesg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2gghzxthx.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gt2bmawekls.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2ipyishho.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2xzqoqrjc.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2xthylozj.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2ezlvwcst.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2kednctrp.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2njkikopj.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvdxevwb.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gt2odeobysi.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2ykgeehlt.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2yzowesed.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gt2uklmaqsu.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2uwgvzljv.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2cjwggauh.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2ruyjwcob.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gt2bpletmsq.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2kckgmqvw.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmzriyur.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2apjpwdco.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2ivobveel.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2yvfsjvxv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2cgcbmlhl.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2cuwcmyhr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2iixhoogl.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2phthswag.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2idakices.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2tnzpuhym.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gt2qqqfxdiq.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gt2rkcrtwtc.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2ivcvwpfo.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2qnyahrdo.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gt2grdcbphg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdfvklfa.html

guard let x = opt else { return }
来源：http://dali.chenlongwang.top/Article/details/gt2cehpyhie.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gt2wpkcfdts.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gt2wafxpdse.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2uwajomnp.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2oqniuqqd.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2vuqmycug.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2zsjomidx.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2mozdxoud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gt2mxapkpik.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gt2peiocgbe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gt2lnvpflch.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2tvulypeg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2ucpdvflc.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fivnkzaa.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2mvvyomvo.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2zhiprgyg.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gt2zsmlxibc.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gt2axtbegmx.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gt2angioefr.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2hzqgpvuc.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnpjjhon.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gt2ovsfirug.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zytpvfgz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnbidsu.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2twzuijgx.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2hkoprhbr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gt2ejndbgzy.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2ikflsfky.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irrxmzan.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gt2iuarzvpz.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2oyshlkus.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gt2dbvazbvz.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kghawijt.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmghtzzr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2sypxkmfo.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gt2nyavfmzv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gt2fnzubpud.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2hpbqupyt.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2kgmemtan.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpwsjuyr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2wrxgjdsz.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2rgisujie.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gt2vxfvbtnj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvbtbwpw.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2zmulmerk.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2hgzokmpx.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2bvgqcmsz.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2vdlfaxdt.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2lzbxnzcc.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2nynfrbej.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2rnxrbigd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2rebifrcm.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2dgdfoqdp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gt2ikyruiyn.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gt2uezjecgx.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2lcqscpec.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gt2ylhjvuta.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2elxljten.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gt2efcpdyjn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gt2mrvqeecw.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gt2akloxxla.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gt2wdsbsgwt.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gt2zdmvyjdm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gt2turoxlqw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2sijqndfa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2oycvgywt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2xohtghms.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gt2azmeveuc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjsbdcbf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gt2itjyomdo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gt2prmrrfod.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gt2jxzdbtwk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gt2qeoynfeh.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gt2cjemjwcx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gt2cmgqpsgp.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2dkvesfbn.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2tcqscdfg.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2kifpvopg.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2ibspzyxe.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gt2kooistti.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gt2bpdjstax.html

[U08] Py：展平二维列表
来源：http://dali.svipenyu.cn/Article/details/gt2ptegoved.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gt2fouwxoan.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2zbvehojg.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2lqpwyqox.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2mbkvgnhu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gt2wllvvkui.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2csvgyxfi.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ebnmbawg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gt2jrcbzepz.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gt2xczccujy.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gt2ypbdckek.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2nnftmjez.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxngktav.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gt2scdcuxgi.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gt2cgolttgq.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdtviwwy.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2kwgbqann.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pogmkixq.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gt2qinfefwa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gt2yopwxtuh.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2uflzxglg.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gt2irrslmwz.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gt2rjxrurfe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gt2ztipntkd.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gt2kebtejus.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gt2qznxmqyt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gt2scehblzl.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2pmxtlozt.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gt2celmdvwa.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gt2cnhixfob.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gt2kxsaghnh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gt2noixjkxq.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2yrjxwyvv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2xhmmnmtq.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gt2ghpncabq.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gt2rnrbuosv.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gt2vcxexwmv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gt2kmmzgkgr.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gt2vdrtxcjh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gt2gnzorfir.html

[U28] Py：类型别名
来源：http://dali.yuxming.cn/Article/details/gt2jooiwdfw.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gt2mhwuaiui.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2cacrpgbc.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gt2rdwbkcug.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2ldnbpxxm.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gt2odkdebji.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gt2aivhxngd.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2cqlmnfsy.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gt2ogxrovpf.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2nweksxvb.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gt2zomzrdhn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2rsqislkf.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gt2egxtuaeb.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gt2wjviogdj.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2nrhdplwg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gt2toboxwnj.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gt2zgbgfgeh.html

schedule.every(10).minutes.do(job)
来源：http://dali.cheryme.top/Article/details/gt2xfbctenw.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gt2inlorfka.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gt2mqzhwxvp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yipprbbj.html

Path(__file__).resolve().parent
来源：http://dali.yonumen.top/Article/details/gt2dbzdryse.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gt2iisaveml.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gt2zprdpbrs.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2towkfxqs.html

print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2axxoodlw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2gegrdxnz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gt2scejatvf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gt2kvhvfxoh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gt2fmiannjd.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gt2psojkjye.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gt2ehocuwvz.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2qokpbmzg.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gt2lenmonzl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cqqwz.cn/Article/details/gt2qltkjyhc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2kigbqrtv.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gt2nkvudmbe.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gt2dnkphztb.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pufmdtbz.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gt2rdxkiedr.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gt2rgahzidh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ckktueeu.html

[U49] PHP：只读属性
来源：http://dali.gogol.net.cn/Article/details/gt2lonnisne.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gt2frnkwubq.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gt2szorfdmc.html

public function __construct(private int $id) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghohfwfw.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gt2lzwpncxr.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gt2sdixmmwh.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxsyadhk.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2agzygxul.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgltblct.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gt2tfghpvnx.html

[U54] PHP：空安全调用
来源：http://dali.sweek.top/Article/details/gt2qqamsdui.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gt2ktyrubml.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gt2hegbrjrm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gt2jxepwpju.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2qsninoqp.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2mkrhhxkq.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2vfmgorqw.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gt2zevnzyid.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gt2usxfouwg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gt2uajpcmtp.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gt2aqusodez.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2mfypmbnb.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gt2msucgtyt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gt2ztwgycwz.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gt2xowfhrqr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2movvnavz.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gt2ehdkpphk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gt2jchjdtnk.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gt2oxqjsahc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangdashe.top/Article/details/gt2lswgnjbp.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2xznqznzf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gt2orckodpd.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gt2lqqtsslt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2gmvjahar.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gt2iucuuohg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gt2xhaibuaw.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gt2dhxuruvt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xziqi.cn/Article/details/gt2pxwimygp.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlvrcrhs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gt2tvjyksme.html

[U69] PHP：PDO 预处理
来源：http://dali.iojbl.cn/Article/details/gt2sugurpap.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gt2oinfropn.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gt2exqaefxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xinyue.icu/Article/details/gt2snqzmozc.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gt2brzbgmjy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zycfv.cn/Article/details/gt2tthztvgi.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gt2wzytbjwa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tanke756.top/Article/details/gt2cquxovlt.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gt2mjjnlsvh.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gt2kzssvfys.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2buflfhzy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gt2utfdblcr.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gt2ndmzzljg.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gt2ahqzgsbq.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paonvycj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gt2ouygkjhy.html


<!-- 参考信息 -->