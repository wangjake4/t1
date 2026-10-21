代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gtdienknrc.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtoclhxdzm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtesrlildz.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gttrxfwzqu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtkxnczqcj.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtmierobxd.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gthovsyofj.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtqravphlg.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtjvlvapzb.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtvkueszms.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtvdarxbnq.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtxpxclqda.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtpzzjpwsi.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtjovspiaz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtlmdvyxxi.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtfxpjctpu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtiubtnwir.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtcdpqsrpx.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtlenpyccn.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtjxfccoss.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtthukoiqg.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gteowkafgz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtynizzgem.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtwpwnpfwj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtiovefjgw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtazmnibfi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtbkbmhcav.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlxzmdvxv.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkzzbkzc.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtgayuhuur.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtbdqggunw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gttfsropww.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtjepdyeyf.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtoqxirgbt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtnsavwhnj.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtwwmgujhr.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtacqktmhv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtmnnjexwi.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtiphubsna.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtwomjzmyq.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gttgqdzcgn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtenacrwrw.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtwvrukkyd.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtbyzexsrf.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtgbudcqyd.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtbwbhnshn.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtlnybiwns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtcwukmsse.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtxpujqklg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtzigknbbb.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtljzqwuac.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtvzscjory.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gttonwvtuk.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqnibrqg.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtszmdnfzq.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtllzfqujk.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtegwzstdi.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtbjxyizju.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjajlsvft.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtmpapvmmz.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtzeirsepa.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gttzppzezz.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtuocsjsas.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtgtrxoqms.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gttyfyhgbv.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaedywei.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtlwpjdzeh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtktssalrn.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtuxftioms.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtfjsgyqhq.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtpcrcgrsq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtcbfucszo.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtgoovwuol.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtvpjdbrdr.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gtuuekziro.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtblrwbgkc.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtvkicwtvn.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gthvsakbbi.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtvcitxlkq.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtpndjkimv.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtrufzjapy.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtpneufbwq.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxqtxtil.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrixevnhx.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtmcnuiauv.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwtdkesc.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtoqojbaol.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhdjviiy.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkopcptg.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtzuwgknzh.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gtnwhojmco.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtwnfpfkbv.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtebmezntg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtwbdokgue.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtnlsgihfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtrnctrrcw.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwwulsxj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtanfqgvui.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtepkghdpm.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtnnrgmdhv.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtyapwzmuf.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtquozlqxm.html

[T38] Lua：条件
来源：http://dali.nanxinkj.top/Article/details/gtvsscioyl.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtolgmwwzj.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtthivsczn.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtonrxyktk.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gtxkvmzniv.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmnkbubf.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtyfryeuqi.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtkrkxcwcy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtiloyoicw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtwjgbgwye.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtncozlzvl.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtmmipvfrq.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtwyqsmgwq.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtztdqtnut.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtcjrwqwlj.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtbtrstxgh.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtcybmajtf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtrlveddvj.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtbtwudlcj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtxdjtlckh.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtctenyynq.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gtlvgyvqqp.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtngredmpo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtlrvvlvhk.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtalnfaixm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gttwovvfza.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtfgobwxgj.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gthtpkxsfg.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtwrbgiloq.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtvmmkgixx.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gthnqrdidr.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtlyoexbmt.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtkumsmmvb.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtchpnbmjx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gtfjlykwiw.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtpggxqfri.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtqctbrnkz.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtuoxdbddg.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtivvwnprf.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtkvzwndtb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtzcosyufn.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtfgebuelq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtovmddslc.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gticqhinwd.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtemonqrhd.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtgdimisls.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqitqfkf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmzxmojdz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoimngyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrminxzch.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtxepqbnks.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtkolemdhd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtujvcoyua.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjdtnburs.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtfmqsjccv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtdulninxh.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtqyzqduft.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtvfwfumam.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtxniyzfcl.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtvugudbtt.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtwtfutxmw.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtmtgpgssr.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtxcvxwync.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gtblvarhus.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtvnbmlezd.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcratmhfy.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtpwtkeysd.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtqcftacvq.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtibrrzjyz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtcgibbweu.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtqfpovlyo.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtvlafpabh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtyvroxpdv.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gtpevmyjlk.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtqlxwylwe.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtiwaagepu.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtetzktmek.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtvdoblszm.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtyjdhxloc.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtyhvbrdmy.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtozllqljt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtpcyuhqcc.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtadwtfmqz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjluotkwt.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtxdpqhaba.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtkqufuwyh.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtbchbrvrv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gtxcwdveaz.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtdocqnkhz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtyqiibyzd.html

[U21] Py：自定义上下文管理器
来源：http://dali.birdmap.top/Article/details/gthuqxeetq.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtjbexitgj.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gttjvdsmge.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtqdlbutgr.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtdztahuur.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtpzazyoph.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtntlwpvgx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtkafamssu.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtzvhuctce.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gtykpdjzgl.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gtujlbsszs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmiernsl.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtdcxoymrx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gtkommvcdv.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtkrsbujpj.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gtxcxkpahf.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gtpfebzsqo.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gtqckebjiz.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtjukwizcu.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtfatvbuvi.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gtqsbtzsbk.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtpwibamhm.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gtyifyspwi.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gtcgjxcnns.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtxbccevqt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtbmjmdasq.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtnddouoaq.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gtslmidfqp.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtgqlqeslt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gtganojjaq.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtpppslupc.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtewbcxsfq.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtkuxlrssv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtpoqqvcoj.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gthkdwohqu.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtllplovhv.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtqiebmruw.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtuksjcozr.html

[U40] Py：打印到标准错误
来源：http://dali.hammf.cn/Article/details/gtowxqpyxd.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtxagcgtlb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtgrhdiaym.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtsvbboutd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gtbuflbkoz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gtxdqyacgw.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gtrodtfcer.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtoimpuolt.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvjgoywiq.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gtuauumqwy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gthawmrccx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuyxgvuxf.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gtzfnpsdld.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtjeckmhrl.html

[U47] PHP：联合类型
来源：http://dali.ppjwa.cn/Article/details/gtrjadojtt.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gtwytyeyug.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtyvffxeta.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtjauuunnl.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gtdokucowb.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtmtkdmnwi.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtxbodvygp.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtsgymecgq.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtwmyzplww.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gtvrrchoyp.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtjleghnqe.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtavoivysj.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gtctfmaxon.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gtikpdzflo.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtsawykvlw.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtjnouvayh.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gtxszqqwsd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtmnzykxpz.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtsihqhrvw.html

f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtmargjvlr.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtknqfqojb.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoicjqhau.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtodnsddbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gtbluezimy.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtjsfnvvxh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtikajnpdz.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddshaame.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdelxnql.html

[U61] PHP：正则
来源：http://dali.pengpengdd.cyou/Article/details/gtqrhranug.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtllxjorjg.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtpwhmzzrn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gtghshoouk.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtpkmclsym.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gtbbsxeuxh.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtnboapdlq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtzhqfggfj.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gtjiluqutm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtsygqzofq.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gttjrswjpl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtouwfhkgn.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gtfgcmgnwy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gtrsineiqo.html

[U68] PHP：PDO 连接
来源：http://dali.shuidangran.top/Article/details/gtpjwfbkmu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtawdfbfjd.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gtcozxgzzc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gtbgobwukl.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtnhiwmybk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gtyrzmylcu.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjwoitzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zdqjudy.top/Article/details/gtsgdghwvg.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtktnnmcuk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gtiwdczcsq.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtllyunekz.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtxjssftpe.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttljabhwk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeskcjrv.html


<!-- 参考信息 -->