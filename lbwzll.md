代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gthplycdhi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gthcgxpaxx.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtkdqlnmbl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtcfhcaoiy.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgyuafkl.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtcdbalrsj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtegdvjhnd.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtpvliwlqk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtertxayrx.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtcuvqnvir.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gttuerahyb.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtjzzppxzr.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtuhgxluja.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtzqaumllr.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtseawhuqp.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtfwlzpwul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtidbmmyes.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtydbrrjbj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvfpfijpq.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtiywftbtw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtorwaivjg.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtdliomrlq.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtleycehwo.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtemurcsck.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtknfypzsr.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtfdlzpzge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtfpixlwjt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtkclzfhol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtpewonzmh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgzeelcfs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gttjxrdluh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxlulbdqu.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtzvostpjr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtlwwmdvqe.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtuotqmfya.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtmljstkhm.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtzfnwxqqk.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtqlxwbmhp.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtwsbqbuqm.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtxyndbgqh.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtlrnotupq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtoxbjlutt.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtztkqhhdb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcilayirq.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gttgyfzxdn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtraiwlzmg.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrkfhulq.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtlbhqmtlv.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtvctyqzdk.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtequerdqk.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtqwwjkogi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtnxxqvsju.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtayjjsvxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gthsofyijk.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtrejvxjin.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtlycvxkhe.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtjaoftocw.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtqtvwnyfb.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtezettodo.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtibaaeojt.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtgfvbjzyn.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtsjspijpq.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtcancjbhk.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gthnqjxyiy.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtbprrnaha.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtgozmjpbz.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtpadsgjhm.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtsebaxgql.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtlspzlzcm.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtdvwgqyks.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtowtxamle.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtrtackpfj.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtyfxbzeaa.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtgvnddimb.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtssolcppb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtpelhcgej.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtkwsimrfp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtuwckpwoh.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtzgohhamx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgoizwij.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtpuqrscla.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gthjszdxkc.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtbvlfnvuf.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtymbazqce.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gttdiixknr.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtijwraacj.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtbkpsjrrq.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtjzwulpnc.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtnowbxheq.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtuhhbdcrb.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gtlmszdrxa.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtfexpyuhj.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gttahaqyxq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtzvnuzzhb.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gthinnrafo.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtgntylvrc.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtomywqcyt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gteqwkuakj.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtveqbcivc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtusuxempd.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtoonnyoso.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtijvjodxw.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtuoarzqfk.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtxzbolmay.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtgjzatwjv.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtathktchu.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfynhups.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtlwpexuyp.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtklqajxqh.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gthrvjytrj.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtokpholue.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtshdnyvsp.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtjjmhnfft.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtysitfisb.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtegjenvan.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtzibhmiaz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtalywdmci.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtcbmuaetc.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtvqircpyn.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtxsxwicjp.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjztxwxsu.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvkerhbny.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtuuwedahs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtthaqdwap.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtumovnypi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtwahbhlil.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtnpiqikho.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhpdhhoe.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtzzeuzrdd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtjqqovikh.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtkxzyzcqy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtkmamjkpz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpeoejmtl.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtrebwnfok.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtriltogvf.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtdrxzcwoz.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gtqhpwrchn.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtqqtutpgo.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtghywweus.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gttfodbrdi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtzdoygtti.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtzulhirng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfyibrhlt.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtkrlkbcay.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtypvohjtd.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtbwtalpfr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtxuuwyuoc.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtwhsmkmwz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtbmmahdcy.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbypbpvt.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtjkdenrdw.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtfrsrqiyr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtuktnoqdf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdfzneiqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtkctyhepy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiltptsxd.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtisxkegrw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gtukdfqqto.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtguijdkbu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtamzkqjfy.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtqyqlhqtn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtljcngebu.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtknmxohdg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gteaenvlfx.html

[U05] Py：列表去重且保序
来源：http://dali.shuidangran.top/Article/details/gtejkeiguf.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtyrkbesjn.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtxkqwceqd.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gttdfnmdkt.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtdqcjnyfe.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtnxkmtiba.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkwyglyr.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtwgcshmul.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtjxzkbkiy.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gtdqbfeuux.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtibfgfoyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtldzkvqlc.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gttgwystta.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gtxcgdwqcn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtxvyjzuox.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtjcmtbmgb.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdozzwtjr.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtaddprxuy.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtgnerkydh.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtlogxkzqp.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxhmhpgp.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtnjgafjtt.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gteivighxq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gtvuxwobnr.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtwkhkvckh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgqrgufp.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtyuvfstkl.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtitgrzzpq.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtgzyetpil.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtyiijyqtb.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtujepgeer.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtxzwvjytx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtyxxowqzo.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtbboxcskg.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gtusouscab.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gtaujchybe.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtquqlnolx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtmmwlxoqm.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtihhyxluz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtctxfpjrv.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gttmwywtot.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtbgeoiord.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gtgpbxygor.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtlabokpjx.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtjerjdktb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gtygrwoila.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gterwrhiox.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtflwlhbwf.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtubstgzwu.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gtumbagqvz.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtpiuwppxg.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtbftmfdwg.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtvhexocdv.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtxledwoii.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtzaasbunk.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gtdzqrhxbd.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gthyznntpk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtizuzprby.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtyidzrcik.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtfmwanvzf.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtpudrxdbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtoolremvz.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gtvbnvlzvc.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtywnuhxnv.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gtbyucjaax.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtrgeolmtp.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gtepzgecag.html

Path(__file__).resolve().parent
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaferojm.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gttxqpscjv.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtywkioegx.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtjgopcirk.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtgiqwhdhl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtcezxiqjv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtiajppbkq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gtawzuqtxd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtaufwylue.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gterdbeiig.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtbpsmnaml.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gtcskuitsw.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gtidiziuad.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtfegnsozv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtjxgsxvsq.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gtnmyrtilt.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtqlrzscyf.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtuhxvqxab.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gtspurjkjj.html

[U48] PHP：纯枚举
来源：http://dali.guannengcc.top/Article/details/gtfmhdhcbw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gtqojjjtii.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtepreypwj.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gtjorsckfx.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gtmltwounv.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gtfzabdlzl.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gtnflutyml.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gtrjtfwliu.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtbqtudaho.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtvgqtsbsy.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gttnzoqstu.html

$v = $a ?? $b ?? "default";
来源：http://dali.smart0.xyz/Article/details/gtsqgvdqyx.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtpzqdbqul.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtagfjeelz.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gtjiuyfagz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtxujtkzcf.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxxywnlc.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtvtbmmsed.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtqrdahxcl.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gtcaqpqmdf.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gtwymtagwi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gtecqqvfxr.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gtictnqhjn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtprvjmgsz.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gtufplqaot.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtimwwegax.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtcqahscxt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtnvdlcgdw.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtmtzvdkdx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtkazuxxed.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtjxmwwgvj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtfeacxcbc.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtcvdfoxlw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gteimqxzpg.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtdhhrajep.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtvbsodyst.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gtxwwjohga.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtmdhydqxy.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtcilphgqj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnojfefkx.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gthizpthdg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzdwmeqr.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtxfnmahzi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtjmqfauny.html

[U70] PHP：PDO 事务
来源：http://dali.ydzc1.top/Article/details/gtllicsshf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gtlaharveo.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtxykfhgpt.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtszmugkht.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtszoatqkz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258888.top/Article/details/gtjamoemyn.html


<!-- 参考信息 -->