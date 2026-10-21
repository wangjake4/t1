代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gteoyibdsk.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtyzknzavg.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtnqjutxgy.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtrejohbxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtunlxzurf.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtsbtpoppk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtqtfrjyhf.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtknqhmfne.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtfdkltfnu.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gthaaycqwf.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtpxmmyunz.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtdkkhpzaj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtefllsvur.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtvaapyatt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtecbszaeh.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtejdvbbae.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtwybmtrss.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpraeevot.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtxcykhfpb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnzyubnkr.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtxqxhtmpq.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gthgxbohdm.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtixkaoixm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtcxsbarzc.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtkgcgnsms.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtffodycto.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtwjppvasb.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtyadjiitp.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtobjniajr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtckradebt.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtysoqtuid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtialowgxx.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtuuejuzrl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtmalgcytd.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtlnpajhxz.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtwhfaygyh.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtvlodxpqg.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gthpmcglux.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtlwqfdpkg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtuigfuuqx.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gttaelmlcs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtkzpymftb.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtplotcmez.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtrkkpuqbh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtfllanrfh.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtiokrrwpo.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gtirkazadf.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtdfzskfoo.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtgfwzqijn.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtgysaxsfc.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtrpqfhupx.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtrjxsjimn.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtdkxzynqn.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtzadhuyjl.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtyckuamjx.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtvqppebhe.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtlpimaxsy.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gtmorqhcqn.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtlbmgefqp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtxndemeqt.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtjwjuiall.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtlmctokdf.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtlplwekcp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtcmxyvgmo.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtisoizuzm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtxmxxalbw.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gtiqnadoor.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gttheuxapc.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gtnovbmyxm.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtwejwoorp.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gthakhiinf.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtkdlofjdk.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtswtofdgc.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtswjzmiiv.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtynbfjuer.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtrxsmwkyi.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gteriobjlu.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtywkysgec.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtcuomfgav.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtnxveqfjb.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gtsyleztjn.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtypmbafsm.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gttzikbprx.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtebkunwvz.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtrrkuvlvj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtiqgnwfsh.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtapbrejrr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtwiyfamey.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtvebgkmdb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtzhmhivqd.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtejfudaqf.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtgnbcelce.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtbbnjwzov.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtkqwowshs.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtnzyijlcv.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtdlxzqcyh.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtodcivgqf.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrsaitjn.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtwncieanf.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gtwfxbunop.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtakswrrab.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtsttpvzfj.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtlrrbckey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtsdhagezn.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtrqtaivhg.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtbedwswgl.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtzepxihoh.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gteoopzwwp.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gtspdjbudh.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtehusmjva.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gtwvllmpgs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtwssabfhs.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtpkeegtkm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyeqpyajx.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gttasuohxy.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtkevykkdl.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtvchuqrxi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtvenvjmgn.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtrxiainfj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtwludwusm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gthjuecxgx.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytqkkcgs.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiadioqsm.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspllqiar.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtfpvhuvac.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtdseobohh.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfcgoplm.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtncgbguld.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkrvrshxf.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtabiuusrr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtqhmtcylm.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtgstlsrla.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gthuhqdxrh.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtuvhlrdzm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtrjdabyhm.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtzpnhvgbb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gtqjyuvytl.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscieqiir.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtuadszocu.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtvcmtfwqz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtbdgesxcs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsfcizeuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtlmeoyvxv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfkgfbkne.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtsijuwgox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtmxeinqar.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gthfrireyt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gtcpjdhckl.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gtznmguloy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtynqpuqkg.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtbsvltive.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtdlhxvykt.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtkvzyyyli.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtwbgkocfq.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtkdcxpapj.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtirogzfuu.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiiwehcc.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gtbxdaqtat.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtmacpimac.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtkcutzfao.html

[U09] Py：字典取最大值的键
来源：http://dali.sxryk.cn/Article/details/gtcfvsdcjp.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtlejvhbdg.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtcpyslsid.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gttwngcpjc.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtwftlwhfk.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtfymvelbn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gtqsosxgov.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtkglvnopp.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtekoeieox.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gteogyvkqc.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtmobgogub.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtuvhljjjd.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gttirglwva.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtgqgxpcgj.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gtrimthido.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtsyhcppoo.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gttheevjsv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgpaltjd.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvoardql.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhidczif.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtkxasdurw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gthfxczfuk.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gtjuolwgxb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtyyteojys.html

[U21] Py：自定义上下文管理器
来源：http://dali.jiagoushi.top/Article/details/gtagmjdvew.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnjqtskc.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnghmkxjt.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gthianlqpr.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gtrniorgte.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtvbpskgpx.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gtvvbohnwn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtlgxfiukv.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpkprohf.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtezgeymtw.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtxfiiqbrg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtqtdngmtv.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gtsvyjqwwh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtncivoemn.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gtynbklvsi.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtajtqzrhu.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtgaowatfi.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gthkgugfkn.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtyafmgmvy.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtsvrapogq.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gtdgoyxghs.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtehqewkkb.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtakzptfqg.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtxnymdxhj.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtqshysjcd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gtuskkkrep.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gtvjreiadu.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzszhawp.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtxqrwqdcb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtfzqqmfzn.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gtjtegtqvs.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtkoiylczc.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gtowaridsb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtijbfgapf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gtdfpwvvku.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gthboctwbb.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gtwnglquid.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtwodewoze.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtkdbpgnoe.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtuyecuusv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtpbkqozjo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gtakujaznn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtxhjmwbpi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gttjvkhahk.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtkiixtkug.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtfbxpirqb.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gtfzwqqbhm.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gtmumvszjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtgfmnnrza.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtxcrceppe.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtqdsysqen.html

?string $name = null
来源：http://dali.meibo888.top/Article/details/gtrlzubfao.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtzpvsdtgx.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtoiprqioq.html

[U48] PHP：纯枚举
来源：http://dali.snrcjt.cn/Article/details/gtfjrahpys.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtdvzryvpd.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeuwhope.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gtnznaxmns.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtveacsuco.html

public function __construct(private int $id) {}
来源：http://dali.yj20258888.top/Article/details/gtmzimgmgt.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtsvukedfj.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtcdwcyhgh.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtktnzsqzz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtbwtasnyk.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtamjuicta.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gteyllspvy.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gtznzzaybj.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtcgggzgqb.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtemfgviun.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtszkdebqw.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzewpcvqz.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gteuyrjqli.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgvfjauu.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gthqinuvzc.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gtwsxqfxzq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gttinaisgy.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtkxuondlt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtrhzqggab.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtjpcvajbi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtuswzxqjh.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gtayvibulv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtwmacnrqp.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gtxwwizqsk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofodnkmx.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtgayogeqk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtryiehede.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtwmjtgknj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gthreejlqe.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtwyotlqao.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtekwgozmc.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gtppmdoyeo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtqqogyiep.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtoezcjxir.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gtbofaneli.html

[U68] PHP：PDO 连接
来源：http://dali.wangdashe.top/Article/details/gtjksvtpmd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gtjmaqbkwy.html

[U69] PHP：PDO 预处理
来源：http://dali.shangyingyoupin.top/Article/details/gtfhxbutgi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigfzy.top/Article/details/gtzudmuvpr.html

[U70] PHP：PDO 事务
来源：http://dali.pengpengdd.cyou/Article/details/gtobutanza.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfytoydi.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtxrkeutqd.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtwhjuhtjz.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gtnbwypuny.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gttuyrpgle.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtncxnxlhp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtwbbflxvj.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniegkfld.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzbusowm.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscefcrvf.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gttigeivjz.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtpuuyhhrt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gthfgtnnwt.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtagqriqqw.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gtygazofrh.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtmfzxlcag.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqllzcul.html


<!-- 参考信息 -->