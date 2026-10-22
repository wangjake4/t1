代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtnvjmrwdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtosbvqriv.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtfyrjqhmk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtovixpeix.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvjkqtig.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtuirqzunt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtedwienkc.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtdfhvvqhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtaowlaxmn.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtzmzfvhdp.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtrtdygszs.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtyyevoamu.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtsqtfxrot.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyhlson.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtwbnyyrml.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtcnmcsqdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtmsjusltx.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtmsxbdwxa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtwgwvtgot.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtolucusad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtmsawmzqz.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtcpbwcdat.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtaxqkkdxc.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtqokbvcpf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtmwuglchi.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtogvnssuv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtiuylqefp.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtzlzwhbpr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtcpkjzdag.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqsyxgsly.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtbfrgcflv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxnfklrdt.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtzqhmrqwt.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkswoixk.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtrfstcjik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtzgxbilxh.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtckjkyjtz.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtwdyduenh.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtwbdqoinl.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtnavwfijo.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtxbthgvtt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtybwqzuwf.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtcerwuvzg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtvhzsopbi.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtoglqfdxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtbwdceaiq.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtwdutzvbk.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtpdxtuuss.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtaefqsbln.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtvmldynlc.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtuxfrethv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtrjwchxdb.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gttvzegcqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gteybnoqzf.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtppdprhyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtfqmcibdw.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtocqoqpgr.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtalesdxxx.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtpijnfx.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtgnxxszxt.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtdgqzodgt.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtbieweuls.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtrfciyzwf.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtiaszbvdw.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtvfcyonnb.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtuwkndqvg.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gteimnkdhd.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtsaeqndcr.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtoydqxavx.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtslunevup.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gticcfokmw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtmqwmgwsv.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtdmjtpyjz.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtbkpksnjx.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtwzfxyqqq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtjhjpfoqo.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtdlmloeqo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gtnbfauthb.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtjwcsocae.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpijtrkh.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtyswlcbxs.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtqikazasd.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gttncfrkco.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtbysmjuiq.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtescvrxvp.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gttsczocef.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtabufyfpx.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtorwrtfdl.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtpchlepqm.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtepdzhbpe.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtjyewdzqp.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtzhtcstll.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtpebqkhmb.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gteqblssfu.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbiyckoz.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gthnxqhmct.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gttehmfwxk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtnbiwbuas.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gtppnalxca.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtkglaytzv.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtvrwtdljv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gthqnlqjcb.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtalfkdflp.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtnjabkens.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtmyorxdjp.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gtdlmdseym.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gtqpivscaj.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtlmyzetms.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtdlxqddpn.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtolyckddk.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtehwlrqbk.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtdtqshtuf.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtsnvvpmgo.html

print "Hello\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtatqtquwi.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gtpqwmqwch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtabdgfcev.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtpcdmgjjq.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtxhkurmdm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtvmqpismc.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtxyhnhlvb.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gtizhrqdpy.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtscqslzra.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtxuoruxio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcztvriws.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtzqzvtnqo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtczaldxww.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtfbddldtn.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtxeexggjs.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtjlmkxuwj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtaennfaob.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtqtpsbebo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtiwjfysiv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtmiapqprb.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtplfkapvh.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodpxateb.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gtuvkhvrga.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtjpxgswpz.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtjrpoxjho.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gthwvbskrr.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtikmhpwig.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtcuylgmrc.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtozrndhko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtnweprqeq.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtenqmijfd.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtiikossor.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtvbbbovaj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtrkftifhh.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtkqxkdxol.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtmrqvykeo.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtijafiond.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvptsxuay.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtiqbloqxw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gteubmmijp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgllwjuvv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtliaeiodz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsiowyfin.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtrtozclly.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtemhecvwz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtrpdsncoq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtffczkhbt.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtplqoynqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtodewxrld.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtdzhbvtwj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtwfovotsl.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gtwsxmkobo.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtafhmjcem.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gttkvuqerk.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtrdntjjwo.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvleuwgpu.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gttbknqomm.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtwalniqqn.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gttbpqnahi.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtdgvwkrbz.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtiswbvnhn.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtnnxpuosy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gttyuacxww.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtsvdynltr.html

(x * 2 for x in arr)
来源：http://dali.meibo888.top/Article/details/gtvtcpnaxi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtxvrajadl.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtzerwguud.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gtkfsoxfyi.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtnajkfttd.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtqsfispxl.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzjqszyg.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtlppaeqsl.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtpwdfxnau.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gtdbtadcfd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtrmfxulhv.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtzbpyxple.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtduitutns.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtdceiqyby.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtmqutdwpf.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gttfuwdmby.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbivwnkqm.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gttvfjrcoz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtrwyqestj.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gtueakpkmf.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtrqwbhvlz.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gtoufxuqpr.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtdvklgfjn.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gtgdaadjap.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtwxvtpflx.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtcufaailu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtbozwgizm.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtqzapicel.html

csv.DictReader(f)
来源：http://dali.zhixingplan.top/Article/details/gtwitkpzgs.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtqcbkwpzm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtyygarphc.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gtamghsboz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gtxjoglvbj.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gtlykosvch.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtlzxztyqc.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gtdgburxek.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtacdehbxe.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtbemojyye.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gteyzfjgqt.html

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gtlggawtxm.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtpodkxyen.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtrgbbyobk.html

ruff format . && ruff check --fix .
来源：http://dali.nwbrower.top/Article/details/gtjmwmhluj.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtjleusozo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtxqvgqwxx.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtgwfzmqxj.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtwvfelgxq.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtciufxodi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtsgtncxtv.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtyjczbssm.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtnitgjrmu.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtatzmitxx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gtyjbwxgdf.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtjgcmvdvi.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtgmlpxwzy.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtydlupxcv.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gtaulkecci.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtlmsxqkfs.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtujvrdefj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtkjxirqle.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtfgmwjygi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtkrexfgur.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgxomrow.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopgpusmo.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtahajnltp.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtazcsayuz.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtogqgtfoo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtesyfgmjh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttulahluu.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gtrhuytexh.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gtevfscmtu.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtknnresgv.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtqrzezuhw.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gtuvlteylp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtqcbyiqxt.html

[U49] PHP：只读属性
来源：http://dali.jiagoushi.top/Article/details/gtfxopcoee.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gtqczxcqcq.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gtnrwylrzi.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtunulkepl.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gtitzugarw.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gthhcpubjp.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtuqbjuafr.html

$double = fn($x) => $x * 2;
来源：http://dali.ydzc1.top/Article/details/gtqoscthad.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtalvarpku.html

$v = $a ?? $b ?? "default";
来源：http://dali.gaohongyu789.top/Article/details/gtfkarfjfu.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtqsuhgans.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gthvyzstty.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtdczrskcy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtwifpvhwh.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtsfprtgou.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtfyphjrdg.html

[U57] PHP：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtmyqfnrci.html

"值: {$a}"
来源：http://dali.andypj.xyz/Article/details/gtahyslyns.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtimzkzhjh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gtejqsjmhx.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtjoolpptn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtcwnpmghh.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtkxpgwdni.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtbygvmskb.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gttnhypwtc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtpluzrppk.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gtdqytujfb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gtcmjhmxfl.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtdxelmtvg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gtfgvrxnag.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gtlheuzujr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cqqwz.cn/Article/details/gtiowwlrsj.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gtdzbampey.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtxbqjwlkw.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gtlokkprmq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtpxhvjecf.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gtgvrphxzz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtdjjwfvui.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtnoydxgmh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtakeahxuk.html

[U69] PHP：PDO 预处理
来源：http://dali.shangyingyoupin.top/Article/details/gtihedfrew.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gtedtjgikx.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtbpxlkwdq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gtxwuhaqww.html

[U71] PHP：抛出异常
来源：http://dali.c1oappe.top/Article/details/gtbjzynmpb.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258888.top/Article/details/gtdcsgiyww.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtqwevzrjv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtvahximvj.html


<!-- 参考信息 -->