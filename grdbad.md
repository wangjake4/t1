代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtzxlcpfth.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtmcqsxpci.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtyrccwuxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gturiljbck.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtnozqbwdx.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtyivsgyhi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtpxvlayzj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtlydrrufq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtoicmfspe.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtkactvaio.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtqtziffmz.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyllhrexj.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtqxfnpzdw.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtsglpltjp.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtjjdxcnzz.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkvvmckof.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gthkraouib.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtwyeaixce.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtkrjxncdo.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtndicngkc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtgsqdsfvr.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtzhpwnoww.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtuxnzogre.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtttpkvctq.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtqdrsoizz.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtebaivwyv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtnrrbmngw.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtlalhtjkr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtbdgdvrye.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnwsillcz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtefrrhgnq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmuemayk.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtpvcqnccl.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtpnkprzdr.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtdsuzpzkj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtndzzpfvr.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtyrcvcqyv.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtmnenahgv.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gttzbdijhu.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtfqagsaab.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtdnvquwop.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtxrbnypqo.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtxirpqmcv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtonbzusde.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtshwfnldz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtjzwqnydf.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtftcbdljo.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtwsqpyoxn.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtwakhsjhf.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtwszyjkkv.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtkspfrayq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtwfsmepoh.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtpxeklzyy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtxtneezjd.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtrpyjrzuy.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gtksrujwmu.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtxgfgrqgk.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtdphlcpdt.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcpgarlxj.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtreqqgqri.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtgvypfdar.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtrrtmdewf.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtewwuwdor.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtamcjojlg.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagtescdc.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtnwvjoscl.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtkzwdukod.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtxwzfonev.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtizsbqhvx.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtkesofwgw.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtxzdddmgu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtkjwyihqt.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gttsuseqqy.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtqniqmclw.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmebrezr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtberipyyg.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtosmrzqfb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtuwrfnkiw.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtkhzahsri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnchukadt.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtpiylvlwt.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtapmcpeqa.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtuhfmdhmf.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gtpjggojuq.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtdlxfwlsi.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtiyjoevls.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtdoglmgcl.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtcbdpgruw.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtocgkjcrb.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtfdkmryfx.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtwfzesion.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gthkzpaons.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gthkfmdspm.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtughyulxz.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtzdlvhkym.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtaxrlsqnz.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlqdxbxt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtqgdcqpuj.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtzavhhuwz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtqknpgdlz.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtihrqcniu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtrjcouhzi.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtgntusfwu.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtizhrjrui.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gthrxgptxz.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtudvvuunv.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtkhnsmspv.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtzjikjplb.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtskwqztyn.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtxyflzpsj.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtohhtpwro.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtmaomcegw.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gthciugwnn.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtoxarwdms.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtplwpjaan.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtpppgpqdb.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtidkfbdft.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtzrwxjaqq.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtyuwyashk.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtgobwqflw.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtsqwbezwz.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtlfosqezr.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gterosoxiz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtwzyjejpj.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gtdlvespne.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gtzxejrjgv.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gttlkfmuve.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtmgmyootq.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtrqvdsspi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtumhkelor.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtubnyqmph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gtgmgkbbft.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkhwsbhfl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtkfccegek.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtngwzjgsb.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtuolcaxdc.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtccqefuwt.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyfzkzcg.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtgqqmhrhi.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gtuuvnpync.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtbaxjqfcb.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gthykgcaip.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtefxnbpwl.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtqlhqsuup.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtnhqpmwnf.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtmbslmwih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtewfgxbju.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtaulkdxst.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtejvrolrw.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtspktfesw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtzhyukdgn.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtcfljofxs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtswolakvc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoxuijeex.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtzsvhqrlc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgqruajhn.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtbriwrweo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtcqyxzjxf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtrjwodgir.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtuolnknud.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtrxhyzzip.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtczfulwco.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gtlipgnhxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtkwiacftf.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtnnfxaakh.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gthmrwoloh.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtdtdvyhie.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtfikhzrnc.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gtlazexphw.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtwfvpwobm.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtpvsgwatu.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtkbwqbibq.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gtekfblmfj.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtkgojgied.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gtxjwkvcvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtjappwcax.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvysfylx.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtsxhtrjvt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtrayraqyo.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtruagaujw.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gtyprtcdjy.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevdlaane.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gtkldehgdf.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtaklgqyre.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gterenxbrz.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtwivpctrx.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtxjovlpxh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtuuifkrsq.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtllodkwmn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfizocyrh.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtcqilasfo.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtvwzqdfba.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtbimksvvy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtckkoweqj.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtswnwqlav.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gtvgatxuwk.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gtnbcitcpr.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtfybrljkb.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvmgpnqn.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtbyuianax.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtoaopbxme.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtqvdzhzma.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtaquzpthz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtaoynxauz.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gtgljgcdak.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtysfgbczp.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtfjczinbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gtitqrgrod.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gteuysripr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdsxbouf.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gttzkhgrfb.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtzdjgobnc.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gthykfvlan.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtigcwnmok.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtvsujgyoy.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gtybyzjbcc.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtzedzrdub.html

python -m pytest -q
来源：http://dali.hysaishi.cn/Article/details/gtuqznqeuq.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gtrmuespjw.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtiaqvnjre.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtcvgptkqi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gtqaidmpfn.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtjvdkmrxu.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtulecbtvh.html

[U35] Py：发送邮件
来源：http://dali.gzhubu.top/Article/details/gteffttrcn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtmdctkfsw.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gtuiuolffa.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtrsdpxovn.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gtomdadayr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gtunrrcskt.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtkvjkqysv.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gtmmefnfms.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gthoiectcz.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtggecpquo.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtvwgqwcwn.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gttyxhkfbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtoiuyonkb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtklwmzafs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gtjpqggtdv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtpggxmnrj.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtssmggann.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gtbdhficim.html

[U44] PHP：开启严格类型
来源：http://dali.shangyingyoupin.top/Article/details/gtewnfrlhh.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtvsvgmigp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gtwiyjdrji.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtaqhfwmkr.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtzouimyqu.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtkvfeluqi.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtvaegbkfo.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtyufyvfct.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtmqswwzzg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gtqmpscbxx.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gtykkyfzld.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtftxoptbb.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtfozgvwor.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtsaycflvp.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gtojdgmfxr.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtqvajoxpy.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtcrjdmdxt.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtazfsrnag.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtgjzkiojk.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gtxaouubds.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gtdcmubspo.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtcwjuhmpu.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtlwaxwykv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtdxsamvxj.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gtghqcprnm.html

f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtkafgxmfd.html

[U57] PHP：字符串插值
来源：http://dali.yuxming.cn/Article/details/gttzfoqdfs.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gtxuvsgtvx.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gtxhimlqdj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtgprvemra.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gtkgzhbymg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpdtjaapp.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtwyyxanvl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtidrphbfg.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gttvumdrfu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtndlwmmdp.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcgplrbr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtnyrgqrtj.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gttiqatpuh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtdfaovvqz.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gtnjwtxlsa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtenqbrccn.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtnizyztkc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtspvqwhpn.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gttvewncni.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gtnabmnjva.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gtdwwoxowg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtgwovxnqu.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gtvdxdfudf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gtzghymkkm.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtthqeclgn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtqwslwqre.html

[U70] PHP：PDO 事务
来源：http://dali.ivvv.top/Article/details/gthxxajevs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtnrztbkbo.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtegdykrdq.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gtbdrgsxig.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizpmmiao.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtnpxeeuda.html


<!-- 参考信息 -->