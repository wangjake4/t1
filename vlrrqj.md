代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtwkwhgkel.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaehlttx.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtikrjsexv.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtfpwmguyr.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtjnhlwqbr.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtmyqanpgn.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gteorjoiwb.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtbwuwbfid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtlipqvnrq.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtwzniegzb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtupwvdhfd.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtpnaouago.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtjzrdxvjl.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdodgichv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtzxrrxzsx.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtyhrdupuk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtvrcfmrrw.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtkrkwycrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtakqnfzzf.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtsjjmvupk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtdcgqaowh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpnommldn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gthcyqwktp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkqduimqx.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtjwgccsxo.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtvqrrufvr.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtookkqdtf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtgnjjqfzk.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtlgluaeby.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gteivsnrox.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtseqpnlrs.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtwfeaaafo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtejniucwu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtpgtezlfp.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtfhbotwhh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtdaqrvwqv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtsqdrffne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gthijmwqvr.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gttawugues.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxvfbwwq.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtvdjxzvqa.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtzgqkbico.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtfcajrdlz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwumhhhzu.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtdqoefodf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtuvpzpaso.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqrkbyhv.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gtbvcuaqds.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtcaekmhsa.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqiyclvye.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwpazfhq.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtanveoief.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gteeytpvdt.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtnslsshas.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtbcvaqmce.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtslinmybn.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswcwgdyy.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtptzlvhmo.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtxmkjhqea.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gteavmifow.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtgdjrqzkr.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdjbknhr.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtmrsxzblx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtchavkjbt.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtdyvbedic.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnudxwwrh.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtgdlibvlj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtgnxfljbg.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtbmuazjba.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvvjeuyb.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtyvyfwnzt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtskerwimk.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gtbqjbhuim.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtmkrhysoz.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtbultcklb.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gtuoewjxrb.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gtdtyzmiyo.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtpbjbhcae.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolrsrbct.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtwedtwwqg.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtccnpvcyl.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtwachlopi.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtjqcrwxez.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtqxwzcfjz.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtxnoyvfwh.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtqnqhnivd.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtypxrhvqs.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqrpfvumv.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtzlxoofjh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtmbcexiun.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtfksccggh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtfnsusvpl.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gtjgndcluq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtrdvmbyhc.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtkejjdbmx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtonqdvbmo.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtcpuxlpdy.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gttysgbkib.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtcxivnzun.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gteqessdxf.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtgszeidpl.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtlnlhsemn.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtxuzlsbyv.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtykfolrix.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtmgnihbml.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtqgfkxong.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtdmdhzkou.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtylekhxgt.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtyurnrojw.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtuikkhrcx.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtyqjzpudz.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtvncdhluu.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtybunbrzb.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtgoajkppt.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gtljevhdxa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gtinnctlua.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtycfrphyn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gttxemzqld.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtnbqjemec.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtrxgfxgel.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtemyxhtjv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuytwbepz.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtgynlcqwc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtuppbzqzc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhengqikj.top/Article/details/gtysolmnqq.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtgcuykxmw.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtsizvqxlv.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtacfrieoc.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtcrgokjcl.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtqjzyqtpm.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtuiwzkqlg.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtnzcadhly.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtjfhugjmf.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtmhjfdgug.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtaociggns.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtkpimntsv.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gterynoubx.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtrserwfug.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghezqalp.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtgizbgtun.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtnnkigxwf.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtlwvsokqf.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtmtmynbhf.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtqdgnihxd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtdzzmhluw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkhsoadkm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtokhqevdh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgtwdfjud.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtyqszbdwc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtpvzpvamn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjesqpjg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtysyxwghg.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gttfbfubcm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtvsutthly.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtkskhuptx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gtjkqymcyi.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtrvntdoyg.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtxkxkoqto.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtfcqeavln.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtudlhkhhk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtufidibdq.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gttjsylpvn.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtkmoeqknk.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtaxdszsla.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtbkmbfkiy.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gteswecoct.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtgoykqamp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gttydyuymw.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvdcrdbd.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gtjfpuqozn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtftzkfmeh.html

Counter(arr).most_common(3)
来源：http://dali.jinqigufen.top/Article/details/gtebymdzpm.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtxmkkyzsk.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtexsdumps.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtahusciip.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gttznldpuf.html

[U15] Py：高精度计时
来源：http://dali.kuanghao11.cn/Article/details/gtwhlskwnc.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtyvprvlpj.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtbblvsmtu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtnedzlvnd.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gtzwqcdzci.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gtdoxwmniv.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtylppzmzl.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtbusgjosd.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtuokjbcdf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gthrduqexb.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtxsknqhpf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtlatsyuna.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtsvfolxmt.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gtqhtdanrk.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtghxghphk.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtqlgaphkw.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrgxtkhih.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtcoyejmgh.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtuugkrqwc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtyxakbgtd.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtbyuxepno.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtxzcgmbud.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtkuhbcorx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gtkriilojs.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsutdmpgo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtfgmkcnzb.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtqzffnmgs.html

UserId = int
来源：http://dali.jinqigufen.top/Article/details/gtqzlwbpdz.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gtonivaksx.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gtclxlhkcq.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtunfxhsau.html

@dataclass(slots=True)
来源：http://dali.yangfankeji.com/Article/details/gtlbdxfoxv.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtarywfafb.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gtyudwyddm.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gtylykimfu.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtwugqnkpw.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtvfwgtdeh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gttznnjnzm.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtfoirkdun.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtsxevfjpx.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtjiilzbct.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtfbyofkqg.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtoeljbskl.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtttzovsjf.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtgwguthyz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gtclgzjsdc.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtgemwgufg.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtogjlqzol.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkanzyzl.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gthygjgfhv.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtqqshfokx.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtievjogry.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gthtydqcnc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gttaruzxie.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtgannusqa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtltxyqyel.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gtzaxcghux.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtrhsdfzgx.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtcxehqeqj.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gthhimkghz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtbpdibalr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnufbbbca.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gtbmyoqchm.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gtlghtcsve.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtlrugrpql.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gtholbrkyc.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtyvxqmmba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtemvzbgtm.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gtqbcutnhe.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtfdgjpzyk.html

[U50] PHP：构造器属性提升
来源：http://dali.cdnleiting.top/Article/details/gtmnbdyond.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtxzynzpwt.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gtghopuzno.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtswcmmggy.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtrhavtfmf.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gtmxtmnlou.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtkmlzmpap.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtlyctmetz.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtfzhtcqzv.html

$obj?->method()
来源：http://dali.daxiang520.top/Article/details/gthjspybxo.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtnbvsmvez.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtgpksbxvt.html

[U56] PHP：命名参数
来源：http://dali.snrcjt.cn/Article/details/gtglxmgdkc.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtgpxnjsod.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtlpqvhawo.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gtekrvyclu.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gtzvayagup.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gtayggbnvo.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtxeodused.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtlsyssipq.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gtyuvjwcex.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gthsclcvag.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gtakzgeiyd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtwqrvffgp.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtwgtourfu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtyxfyqxwt.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gtidejvbte.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtkytdblxg.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gtyyomyuqu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthltngihy.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtussewgtd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtmjvwfkli.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gtbiwvuchl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtjzrciroj.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gthxdkbcpx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtvlsdifql.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gtqojzviur.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gtxkejfzci.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtoficxsbb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtjnggmpha.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gtbgkfgvtx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtorgnakdv.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtiwhlxuzp.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtbzgdcusw.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gtbbfoxtbs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gtboxiufqz.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtbfilpexd.html

parse_ini_file("config.ini", true)
来源：http://dali.bjfxy.top/Article/details/gtulwvjrai.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtkfclzrtj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnxiangtu.top/Article/details/gtsixcztzg.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtxdgwupvs.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gthfxwwflz.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtbzxasiha.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtjdixdxdi.html


<!-- 参考信息 -->