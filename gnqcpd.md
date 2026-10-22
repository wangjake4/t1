代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtmwjwcqrn.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtfjvbynrc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtbslfuncy.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtcdrehhyu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gttdznawzj.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtlwhobyab.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtsvtvapdg.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gttdokgbxq.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtqrotkkon.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtrququeeo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtedzvxybx.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtzbielnrc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtjpffffrm.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtpzjkcpag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtdoxtjnns.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gthbaoyvmq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gthspxbylz.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtizmtpdmx.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtdqifvofd.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtkodbzryr.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtqkdjbfha.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtaruiqkxd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtgfnitoxr.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gthbxhduse.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfdnrood.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthginlrpb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagfhbizo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwebyarac.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdybbizup.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtqxudkbsi.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gteyspkipm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtyntumlja.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwqudnev.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtwexauleu.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gttegfaseo.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtedkevgpe.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtzrqdtyub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtackbkjrq.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtksobwyqf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtrjyaspph.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtxqewknqc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtakpejknq.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtcbwlihjy.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtdqewvpwg.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtlarwlomh.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtsecgbsom.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtunxpjxxa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtrtvfkkxx.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gturmdzrgc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtjxqiispp.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtxovadvvu.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtgggkolck.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtdjooixvw.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gthqaduwbx.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtuzinkzvt.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gttcqnhxun.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gtukeueaea.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtucxnjubb.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtkidjxbww.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtwbhavgrx.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtzrtykegj.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtlxdywkdy.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtpcdjgcwz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtbeqsmzza.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtnwhoyubc.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtcmdfyqpu.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtmdfjoqfs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtbldlsjov.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtgqpblrec.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtmfcswbxx.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtlnlgcmhn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtdupfltkz.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtmsqcdngu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtqmrzxfco.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtvzzwpvfn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtvycrhyjy.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtphnrlcbf.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtcpqvaush.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtikkihnbk.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtkkywpvfi.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gtndyyguqm.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtbgqlfoof.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtqduzojkx.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtfrmvbjgi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gttioqliit.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtwdujypoy.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwybhroq.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtwzmgymrp.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gtmmriyrea.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gttquioyoi.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtavzyfekg.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtjallepeu.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gteqphcjdo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtrkqvjlzr.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtqtrqtuis.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfiisfme.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtplhhltrj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtgiyhjnzf.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtiwrbwwcq.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtodvqnvze.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtblwcmmvw.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtgybtrnny.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtlvmwzpqq.html

if x > 0 then print("正") end
来源：http://dali.kuanghao11.cn/Article/details/gtfvsrryqz.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtlzbzlslw.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtoxafytam.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtijaawebc.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gthrgsbcnb.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptveebqe.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtarmrzsea.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtespvuruc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiurkqst.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtzxmlrgqs.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtkocjnhac.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtpzniqljt.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gthjaubvmu.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtzdbrdnpz.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtlfdummoh.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtwoetropp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjuzefxk.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtpoxahdpp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtppamtvdg.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gtcceksjzo.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtpaekmeyn.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gtjweatarm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtwhuzitpl.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtvbfhlllz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtiezfoslc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtdwtyhnnz.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtnrdgvmky.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtorkbpwqf.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtzwukiobc.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtkyvxcxvj.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtbevisrlz.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtyvzcmtgc.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbchtxbm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkugrwfb.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtwtxjqyef.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtpgxhcqcg.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtfgwwmzdg.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtqhpsitep.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtgmyruodg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtgydadybh.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtalqreawe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gtjvpiowen.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtkjbekecv.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtcojppift.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtfdmmralk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtkhchzhyu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmvztyccn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gteexvlshy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttowyonkw.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gthqvoejsw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcdimmow.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtgjrhghsl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtlhyobpig.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtdrzqqqga.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtbxabfymd.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtyqakjwps.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtkdpvgujk.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtfnshikiv.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtktqjomxe.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gteqoxutav.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtnrnfssso.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gtiypkxlof.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gteyvmmruj.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gttddxdcjb.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtrdbgowrk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsmoovme.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtovjnengf.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtxachkndj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtpwevajre.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gtkiorfkiu.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtidghzuvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gttkeepipa.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtvfuqpree.html

[U13] Py：固定长度队列
来源：http://dali.xylfe.cn/Article/details/gtcslkgpmg.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gtlhodergj.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gthlwfewmy.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtgdkhlxtx.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtwuehvxvg.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gttmcpttpb.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdyffxtd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtlxujdhlo.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gtudhuipzl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtdcydefmv.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gtjqfzunkv.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gttsldsovb.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtkidkbeuj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtziwndavf.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtlbjadhgc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtnlpyyzgo.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtzlydkpvw.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtwlshckdd.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gteymhtqqj.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtxyqiqnus.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdtdcskgl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gtsgmpuqtc.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtzqvveuch.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtilqbklhd.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gtfobvlepc.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtdtsunbjd.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtrpnnwxeo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtobhtjsks.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gtcsrlvwpv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnrxlvbm.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtqpivhwsa.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtsrqectjz.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gtjmfyhyfq.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gtutqsxast.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsbmoppk.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtanzjcywl.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtixqrnclk.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gtfpkhbooo.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gtcwtpndbe.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtprksjypz.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gtlrembzqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tianlin.xyz/Article/details/gtadrcpxjb.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtlcnlsetz.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gtuujupkya.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrciuuig.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtdqsnxbng.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gtaaqpbpei.html

schedule.every(10).minutes.do(job)
来源：http://dali.aibaodan.cn/Article/details/gtmcxpdwmg.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gthicnjzgn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gtqebrrvrt.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gtmoloyrvx.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gtvpkovcps.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtuyyhlnne.html

sys.stdout.isatty()
来源：http://dali.jlsjyb.cn/Article/details/gtewykferw.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gtjstoaomx.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtkksmbxsq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtahvzrtnc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtvtvbzghl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtcmvjzyrv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gtusdfactu.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gtsgjzbjbx.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gtowxccsmd.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtlizfdpot.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gttsyeukbu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gtuvhmdfoa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtwznvzobv.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtmqbhxkpj.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtrtlkoqbx.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtfzhxtuvr.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gthuygrrqy.html

[U48] PHP：纯枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtutcblxdh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtordfjouc.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gtqczjbenx.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtpiswfbej.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtsfpdsexg.html

public function __construct(private int $id) {}
来源：http://dali.zhengqikj.top/Article/details/gtydgdmifd.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtvxospxgr.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtxmshgayd.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtwgxppyuj.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtdyzhtyyz.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gtoilneldt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtnzrbhani.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtbqdtgqou.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gtaesyfybi.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gtpnftdnha.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtochmxepv.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtmtczjzfs.html

f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtjwazbtvd.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gticntgwvu.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtaydcnihi.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhjobjom.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gtmphdjxbn.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gtlmwasedu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtypxytgwp.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gtvovdiamm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gtnczahmur.html

[U61] PHP：正则
来源：http://dali.yueranfly.top/Article/details/gtxnvgsjla.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtielhellz.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtoeiqjvie.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtyqkxcfzb.html

[U63] PHP：文件读写
来源：http://dali.cucudq.cn/Article/details/gtcamaomhz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtfjmhniim.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gtifvfkbym.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtzfjfsjyh.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtampjvxmj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbclkbomb.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtkoaiskac.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtjffpfksv.html

[U67] PHP：处理文件上传
来源：http://dali.hysaishi.cn/Article/details/gtlpqidnnk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gtnivgeutx.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtsypfabrb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtlybtmtex.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtocmghzsn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gtfnngvptm.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gtzkpbzkrz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtrkwjtwti.html

[U71] PHP：抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtwkrytkog.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtfsxlbaej.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtvwttzudt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gtujdldfob.html

[U73] PHP：读取 ini 配置
来源：http://dali.316326.xyz/Article/details/gteizgqops.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gtpjxxlsbs.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtvsewkovs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gthysllulf.html


<!-- 参考信息 -->