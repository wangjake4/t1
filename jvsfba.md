代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtjqsacupl.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtazebhvhw.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtyyvnuzcs.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyitbplb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtnvsoahcl.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtsdyrzkop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtmiwmqgfi.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtepkjjnof.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtkfxrwwwy.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwdnoeqs.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtkzgrovyr.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtlgtghpcq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtqebrenrf.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtruvoicis.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtrjmtaelv.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtanhzndjp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gttozjpifs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthaytwldq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtfpikwufz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnlxsfkqo.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtbrcgpkbl.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtchinqkqr.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtkffbkhvw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtxqfjdyfo.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtcnhufdji.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwrdszgr.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtcupprieu.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gturwdazre.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gttdxjalny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtpxwmslox.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtyxcaynrp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gttrplpdts.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtnifdswrf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtbjyifofm.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gttwsiezoz.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtmzviypgk.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtjwtcjmoq.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtemsjcjaj.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtdlompvgo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtzlojorur.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtmajlyroq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtvooghsto.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtbceltkwu.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtnijzklls.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtptpfuenv.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtxwkuaurx.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtyieuopze.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gttepdivuy.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkimmqtat.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtgjlcriip.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtdodamgwc.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuckxdxf.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtfwwwjhml.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtgvveydrh.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtvzvipkgx.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtjorvvkkx.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtljhvtugw.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwtqlyh.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtqdjnouav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zdqjudy.top/Article/details/gtpfuewwro.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtkviyqwme.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtqxaezhow.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtrnakjunv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtkmvrofuk.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtwmosdbqc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtymmdufvj.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtviyyxunk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gthfbbhonf.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtwrnhzmzf.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtzkmwngvn.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gteclnlwxi.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtgplmjjim.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gtvlrztdmy.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtugbgqqlp.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtwhjarbqx.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtluzhpnrs.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtpdfwpalt.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtrwgydoqo.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtwoxngpwi.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtpjfhodrv.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtiaeurhuf.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtsabmpxgc.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcmocnkp.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqwwvqgh.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtawbvyddc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtshwgautl.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gtcwcfyjcu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtmyxnkvor.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtacercwcg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtmnokeldp.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtqihpbwji.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gtssyrqqim.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtupodaewt.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtgulgkhpm.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtibjbitns.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gttidjzdju.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtpgkkyfor.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtgrpzqecq.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtzowzvdjn.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtwpwytsyx.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkrretcq.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtrgbrzgyo.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtquhtiqpv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqfbbygc.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtrvgkfvok.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtzfkjydps.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtgwsscgdb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpvsqcnmw.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtlrbivlfu.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gttkwgtzvs.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gtodzngmwa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtdrmxgyjk.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtgxdqwcmr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gtxkaikoko.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtccwuezmq.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtgrovqycs.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gtcscvomjl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtbrpjxyif.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtnqhltpiy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtnavcfewn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtgawtzbmd.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtylxrdmsm.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtgpzwvkpw.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gttzovhbsq.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtyoikpokp.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtaomcpdmm.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtsfoffmow.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtiaetzdua.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtbxrhrvis.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtblqwuxrn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtcstuavog.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtjhlpjcve.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gttyhfbhkv.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtelwtywlz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtzboexyva.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gtpksmkswc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtsxkvpiik.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtjdkqlhzf.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtjnsikksd.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtnwpzxmhi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtgckfbiuq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttjbswnaz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtlpdhrzbl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmzgktbxy.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtghynirah.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gtsjvurljp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtwusyarst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtcwtzqxlt.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gtauqwyyjg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtlcibdhpt.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtjwcrdisj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gthktesheu.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gtkphhhjlc.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtmccavdzz.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gtraouvmgf.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtujcjvxbv.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtofvfuojs.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtsdedqlhi.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gthqpgkkor.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gtkzvbwgpu.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtyvhbvpta.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtapzjkpdy.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gtavracglp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gtwppkelya.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtdludxwor.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gthipztnlu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtfbknarhc.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtpofdtzmg.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gtanfgxpgt.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtvnadbgli.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtzlwikzgm.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gtcujftftx.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtowaqnebf.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtiejjojpu.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtksjmqqyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gtrtvibuan.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjfwswt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtnhwjqaga.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtcipljidv.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtjlgwbqnb.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gteruavwns.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtchtcvpal.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtmmolzlnm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtjysezzur.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gthsdipblh.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtogrnluah.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtwvvnlkgn.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtcblzbkuh.html

[U23] Py：分块读取大文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtlkigbr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtwjkemhdv.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtkgwzdlkr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtdvnlrbab.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtgaitmgsk.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtpzppxsmv.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoowhlyi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtuwpqxthg.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtzfkepgxi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtafqkjdze.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcyuszgw.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtyeoslxof.html

[U29] Py：属性校验
来源：http://dali.yuxming.cn/Article/details/gtpynbiubo.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtjwczpecd.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gtcbogynze.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gtycpyporo.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gtjituasxv.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtllmoszcz.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gtwanignyt.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtsgfateet.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtgskkmqhs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yvedp.cn/Article/details/gtpuitjfhy.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gttmcsyzbb.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipkugbfq.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtschiljqc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.smart0.xyz/Article/details/gtuvdiiamh.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gtvbzyfsvn.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtkaihaiok.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtwutuefkk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtmaxnhrbm.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gtkhtlbpls.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gthljufatf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtodkyktao.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtkessdlqm.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gtinjvunlb.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtyswtdong.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtqwingisd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hysaishi.cn/Article/details/gtldqnwyfm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtyqmopzhh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtezrspojj.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gtopfvezwr.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtmcgvipno.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtblwwyjih.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtsarkddnj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gtijgmuuts.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtzreoggty.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gtnbiinwdk.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gtrqtleuqn.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtbqfjoadp.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gtkwjlnahv.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtrisrdryt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtzsuzfduz.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtxhyroyfp.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtnurkuqmm.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtspzzybfn.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtixfnjvhu.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzckskmu.html

[$a, $b] = $arr;
来源：http://dali.andypj.xyz/Article/details/gtuldxgcib.html

[U52] PHP：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gtbyhggcsh.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtmsjyquqa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gtlcgamdua.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtryniqzrg.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtdxyctuef.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdkqajtz.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtsunhnzyk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtlcyevsiw.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtdygpymne.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtfchhwleq.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtlhpoihxs.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtvnmttizk.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtcmyyqbts.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtcfihaerx.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtcgfhuvkm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtfoocyruo.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtbhhgdoxc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtxczcnlvg.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtkroofxgg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtfhrxqezl.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gtlcnxjimk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gtizfmtgif.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtyommgumm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.smart0.xyz/Article/details/gtgfxnxnba.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtcnwupbks.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyvanngu.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtlnqtkvov.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtthmudrrl.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gtvgmaqnpy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtzlvbkxfj.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gtilylfbta.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gtfpqyuwwk.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gtamdpkakn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.haohaochexian.top/Article/details/gtzebexjjk.html

[U69] PHP：PDO 预处理
来源：http://dali.shuidangran.top/Article/details/gtfreakrst.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gttdsdllrv.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gtpaneptwf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.snrcjt.cn/Article/details/gthpaqagaf.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gtdgjnvoit.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnqzz.top/Article/details/gtscunmxey.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gtdxdzqkga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxftbvkv.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gtofbonztd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gttowrhlmw.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtchjyqtbw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xylfe.cn/Article/details/gtldmtpikl.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gtzsoijvik.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gtfsivbvqn.html

[U76] PHP：简单路由
来源：http://dali.fengsongda.top/Article/details/gtfovpjmxd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gtdqphoxpj.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtvswuzdxj.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtbtpspjhx.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtvlyzndgw.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gtvrfxivtr.html


<!-- 参考信息 -->