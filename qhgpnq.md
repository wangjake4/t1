代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbptyeghn.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gttbleegwv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtzzadgmgj.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtmkkcemwe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtvmjepgfb.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtzoelymcv.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtkluhepws.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gteyasjwym.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtritreqba.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtrslnjmpg.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtzdhbsiol.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtvflcmdca.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtrtxaajfs.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtqwxlxbfu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtjbefgowg.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtalobbaph.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtujuvbbsa.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdlduxps.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgnnnont.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtkqhdwvqx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnmvoyej.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtbynvpdfj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtsfvtiseb.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtwylxxghw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtmpqscszs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbpxehmoi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtxrgatoye.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrplyjky.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtntokussd.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtkxkiqgie.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtsfltamty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtddiibdzh.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtdfxffcek.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtpsbtfyzj.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtruglxyot.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtmclffkyy.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtdiyhgohc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtphfidnrj.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtgznohnhb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gthjxvhouj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtognqvbry.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqtyuxmv.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtvlrifozq.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtfiraibca.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gthyfqjoji.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gtujrjgudk.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtejbkhwta.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtqexdhfog.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gttmibfbul.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gtslzwpwtt.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtoevsudcj.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtdferahjn.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtvjqkaiwn.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtzrmagfpw.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gttaptyxrc.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtxdihawjg.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtblfxxvsn.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gthhajkbvy.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxxhvwun.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtnikrnuza.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gtbvzubkhr.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gttpinvxwe.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtsnjgtxae.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtspesahfa.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtswnjnhih.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtkkjrftfg.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gthzgudimw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtymbcgqfl.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtpeudqdua.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtvseyymkm.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtrzeguglt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gttzeaevbo.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtfctmfxrt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtuvctefru.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtcbfvuadh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gtumzigwti.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcumrupg.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtcgdxgbmr.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtzatqsdqx.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtszfaywqc.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefaekajr.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtgyzowggj.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcqjjofj.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuksxdie.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtqsxbrnkg.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtkmjrbljs.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gtksqnagzh.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtlpqyixbw.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtjcpzapsf.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtbwetlbxl.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtnzgzzwag.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtmntlaccl.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtsmlahkxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtgsomnshh.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtpoopqzyz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtgvwajqaq.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtlpuwtcoi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtgivednkg.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtxibejgeo.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtmpwyoiym.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtseyxoquq.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtykxpshir.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtmarwmkel.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gtyjpajqna.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtwirirtwq.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtbkihovkj.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gtewgugbky.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtlbrrjjdf.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtydqxymyd.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtvmiyhrof.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtwybrapgc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtqpdmbrwu.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtkjbfsoht.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gtekjexgdm.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gturgkxbxz.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtwruodugx.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtbzskjlri.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtahjzfjce.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtbztitwog.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gthhfmqhwq.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtildiqcyn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtzewtevjz.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcxmfivya.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtsbxfjpyx.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtbetgfrso.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtpytwwqdv.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtgaqkdhlc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtfngiszjn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtcdrqxwjv.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtsogaqgjx.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtroylhkau.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtqhtwdymr.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gttlvglcdl.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtkprksglk.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtwqitwzbu.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtnvqelppv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtycnyrabg.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gtcuuxmnbl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtkmhzicfr.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtpickvxvt.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtejwzzvtw.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtqjaibzdk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtimjcbpwe.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtcafuapnx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtxgnixoev.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtquvnvoho.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtrxcnjbug.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtwllyupiw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtyssihtgo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjuadvfvk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtkbqmujzz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnakrqlns.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtnptzcril.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtgcmkdstd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtplzcitch.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtkrmfulra.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxcwkfpz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtaapccccd.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkwcfrci.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtzyvnkafa.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gttpvhwgqf.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtbqgntxah.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtavnmixoa.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtqoptqewb.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtemsqptav.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtdudfijbv.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtzlfsyujx.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtihplrfqc.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gtqbqvppve.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gtydsycpjk.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtvcrmjtvn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtijmbtohh.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtgaxfddeo.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtssvamlsv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtegorwuyv.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtwieluunx.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gthmfwgkal.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gtojkiklke.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gtklovlmhf.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gttytivrrl.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtvanlxyzl.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gteffqzmiv.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gthswjbuwm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtmuadvsko.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtkrnxrbbw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtmekxnafh.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gtnkynfbxj.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtamwvdtet.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gttzubqlqo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gthfpvtiuo.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtelcdkmow.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gtslvtyyyd.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gtadudhses.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gtvajvnboa.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtftvrbnbv.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gtdshzdwqo.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtocbkeszc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gtvgdsawbk.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtiwsnivju.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtzpdwnyqo.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtbmxgctvu.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtjsxtuifa.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtmkzsbrbw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtgvobioqj.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtehodrkvk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtojohiyzg.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtlgssmlen.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gtmqgkhyyu.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtdqkjazyr.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtacfnocff.html

[U30] Py：数据类
来源：http://dali.chenzaomai.com/Article/details/gtslvfpvfg.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtqpskqjcs.html

[U31] Py：单测
来源：http://dali.smart0.xyz/Article/details/gtyumewgxy.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtxegnewmt.html

[U32] Py：代码格式化
来源：http://dali.ehwqpu.com/Article/details/gtvzbamdjg.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gtclhatvpw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gtmbaxnvxz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtdpqleajh.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdlqbgdf.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtxhgfdomc.html

[U35] Py：发送邮件
来源：http://dali.ybcxt.top/Article/details/gtehooggnm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gtjrnvyoxe.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtpafmzbdl.html

schedule.every(10).minutes.do(job)
来源：http://dali.yvedp.cn/Article/details/gtyqptzzgd.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtmfpaeskd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yangfankeji.com/Article/details/gtprpvqida.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gtieigdata.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gttgbneose.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gtqztpulvj.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gteqzycfzj.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbnbeoxr.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtmagwfyfy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gthosgpyej.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnylyibnv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gtsxyhlzad.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gtaahlbvdf.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtturacegl.html

namespace App\Http;
来源：http://dali.sufxvd.cn/Article/details/gtsrzgohuy.html

[U44] PHP：开启严格类型
来源：http://dali.guowangkeji.top/Article/details/gtfyavhkgy.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsdhoobc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtftosxycx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqwowcmgq.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gtrbntnmlp.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gtumxkbvmx.html

[U47] PHP：联合类型
来源：http://dali.sysykeji.top/Article/details/gtqtgchwgi.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gtzhrirtsp.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gtfsqwuabl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtcehvtpxp.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gtxyinvskt.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtkrngfaev.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtnjnmwbrq.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtiphwyrcg.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gtxrqiocfl.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gtyamurhwm.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gtxavckcym.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gttocjqvhc.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtfuzoafen.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gtrfvtgucs.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumafvgle.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gtcvoqerqw.html

[U55] PHP：match 表达式
来源：http://dali.hammf.cn/Article/details/gtqprqfkqq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtlejyrvjc.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gtmlvfmcsb.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtdaiesowy.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtzshtjoql.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjmiukara.html

[U58] PHP：数组三件套
来源：http://dali.xinyue.icu/Article/details/gtmtnvoczl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtdymgduer.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gteakhrjgn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtcwyvotdt.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtmblntsfa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtnsymskwu.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtdobuotcf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtlqqoukon.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtgxxnnveu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gtxrxezfyi.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gthrqmqdbo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtugxinzmv.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtczpsypzt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtqrpaieyw.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtnazkvmbu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtnywldzsy.html

[U66] PHP：设置 Cookie
来源：http://dali.shangyingyoupin.top/Article/details/gtabpbpcdl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtcvxrqyiz.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtwancxdue.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gtdjfsxniu.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtxqhpbwoz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gtgudlondm.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gtdeowwbgg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtgbjdzxhi.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzfqskzh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gtmpnxhnlm.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtsluzshhv.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtgqkfplqg.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gtovmerptd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtkykojvyw.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gtgynefsge.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gtatmkdyxy.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gthpzniaej.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtmxdcqyev.html


<!-- 参考信息 -->