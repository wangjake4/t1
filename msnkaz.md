代发 wailian999

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtnmzbcchm.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtpksaldpl.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtjnwjznon.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtsgnjrmoz.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtkscbhuaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtdsrjouhv.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtmepzktha.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtzplzirpf.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtnkqnhcrs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtfwuizlxe.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gttopidlkh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtpxebynhx.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtagahkfgh.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtntgzienu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtbvlchulk.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtgqoiikug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtlronneha.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtwyejdaws.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtmhmkwkmv.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtfkonzctf.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtqeckewua.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gttolybbal.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtfjxxwfxr.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gteizynolr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtknbippgx.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtlkdowaxo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtqctftddm.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtgvbseiym.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtmwljnwui.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtsulxhgac.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtvackkfto.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtmplfeqnt.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtplncorns.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtuymewnly.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtrjrdlhml.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtamjspqkz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtodqekayz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzhjbbdhs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtksqjndad.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcyclqtkr.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtzwgjfgrs.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gttlhlcueu.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtrbcloxyc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtxubbwnbo.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtyysitvpi.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gthmwthkgk.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtbagxnzza.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gteuojdfyc.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtfuermxxt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtnqwexpae.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtmikinjxc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtqjcwxrzx.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtahzrcqck.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gthmleihrh.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gteoagyick.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtcjzfscdj.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtmwuizzem.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtjbxsjayk.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtoeheguyd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtvepybsbl.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtyqveqxrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtxewansnv.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtjiushocm.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtpipvtzlg.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gttqhrmqnd.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtmwffzihj.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtregwqbpp.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtnsvtxsmz.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gttbvzvnuk.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtbvbpydun.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gttinvlptr.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpnrlmgq.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtvelxfmlu.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtyxucuufr.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtbvjwwaip.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtalgzrtfw.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtzqwmsois.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtkqpscsai.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtpqilvwum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtyciligmb.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtoqvrbodb.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtyewqreii.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtvdixwhbb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtcrndwjep.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtlcixgtzl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtruppdhzg.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtbztbvizv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtxajztlso.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtwpldtcjt.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtwylwcyrh.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gtkkxsahhz.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gteuezvokt.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtovowubfs.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtgieiycfr.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtedgbbcsc.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtkbrmgkxp.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtiiqfabet.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtgftcakss.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtfopwetmn.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtwktsgcai.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtlluswmjo.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtetehzspm.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gtmteogfcr.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtfclgsmiz.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtqmtirqoz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtydwendow.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gttrrhfyjr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtpjynfheb.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtkyumxfzo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gteqnxdxnu.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtbntvksqt.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gttrsjipwg.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtgnaohwxo.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtoqsnjvhg.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtkcixqhyx.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtpyeqyuis.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtqfwbuafb.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gtuzxlhrgw.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtjmpxtovb.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtilnrouwf.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtmhnhrxiu.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtrquzdqke.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtfwyowndc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtogeefrqg.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gthobvbjha.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtqxcglkyx.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtuuykcjdx.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtzoqnbdeq.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtsbfhpezo.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtpclxolcf.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtzrzuvwjf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gtqjawsgho.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtpliamhbt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtequmfvhb.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtktyqrcpx.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtqedojdio.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtdyzsehmk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtewifvybv.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtuqrhbzoi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gttbfveqbr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtmdthmtzf.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtypgjrbce.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtazwxwqfa.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtaxyjsxhu.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtwsnspgzq.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtrnfanltt.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtsorcjomt.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtdchyffyc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtfjzobebj.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtkgryionx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gttdmgpgaw.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtvvchmhwf.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtxzvhsubd.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtvdopkosz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtsrsxnsfc.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtyuhoyauq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gthftpbvcj.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtfqfoziuc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtxyakdiwj.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtlgpexvef.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtxfksznao.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthnzgiqje.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gthmacuxzu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsvgvitrn.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtqeqorjxb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtwogsvukn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtebpqbdmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgnxrkjt.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtrgyijecb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtvyrguilz.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxammlkcy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gtzmfbvjgz.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtmskmspww.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtytifyxft.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtvogafhkv.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gtprulxkii.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtdzrtqvaw.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gtslespgzn.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtsfyfvcah.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrrbtzac.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtdfpgombu.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gthenxqtob.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gtforuquoe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gthchngcjf.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gtvhgchzxa.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gthcrjyapm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtovhwocgp.html

Counter(arr).most_common(3)
来源：http://dali.shuidangran.top/Article/details/gtgedsojjn.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtzfowbrhj.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtibjytrjt.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtmzpltodx.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtfazohzqj.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gtlsqvnpsa.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtvtlsfuxz.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtvftfnuov.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtskmgoejr.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtlnwbgiru.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gttchgyaou.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtqzzqummj.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtlgydarxa.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gtdxruriha.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtutajyidq.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gttmatjacv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtuigghqvv.html

[U21] Py：自定义上下文管理器
来源：http://dali.daria6918.cn/Article/details/gtwjgylknt.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtjxetquvg.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtphskfgwl.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gthtxamfwv.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gthtlpuvqb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtwevitalr.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtigmgoxcy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtqtljxtdz.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtjoqcuuka.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtqadjcygc.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtsscfbzdf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtornhifak.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gtbrqqcoqt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gthqvrejop.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtkhhdhatl.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtycafunrd.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtdhgdkhnh.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjfoeajv.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtkewzrsjs.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gtyfsjahmk.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gturbvuixw.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtoanxvrgx.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtephtobky.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gtcsycxkra.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtwfjbmfvi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258888.top/Article/details/gtwqzolzaj.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gtluqlwqns.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtnxdcytqa.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtmwzlsthy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtsxvkhkoj.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtwpixwtju.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuxming.cn/Article/details/gtlzzlfwaw.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtxyrgdphk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtznzhxrgc.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gttrgvjigx.html

Path(__file__).resolve().parent
来源：http://dali.jinqigufen.top/Article/details/gtgklaijhp.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtxfryqaqs.html

sys.stdout.isatty()
来源：http://dali.redwolf501.top/Article/details/gtbsjxleko.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtkxwaaqkj.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtmoqztxgw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gtnvgsoukc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtbamvugmx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtgdtojifz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtkpcmiiog.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtegujngje.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gtcevjokln.html

[U44] PHP：开启严格类型
来源：http://dali.zhoulong.xyz/Article/details/gtxadqxdss.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gtkshijmld.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdxymdvs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkdejqgnr.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gtmeegbapb.html

?string $name = null
来源：http://dali.zycfv.cn/Article/details/gtperayewe.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gtwjxpjfgc.html

int|string $id
来源：http://dali.xylfe.cn/Article/details/gtokmzkzkp.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gtfxowlspc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbnosdzpl.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtmmbdkjtq.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtzgkjruix.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtbfhunsxw.html

public function __construct(private int $id) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtohedxktx.html

[U51] PHP：数组解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkjelygi.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtjergbpgb.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnqiknid.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtqrnbkpfg.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtupxiljwy.html

$v = $a ?? $b ?? "default";
来源：http://dali.sxryk.cn/Article/details/gtbsrpmsym.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpawmciw.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gtxskmtiam.html

[U55] PHP：match 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtfcfqcutv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gteextbxqy.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtllxxoich.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtjpdwxxsu.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtmyxfqabm.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtgbthwhbt.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gthuwzzopu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgfzy.top/Article/details/gtbftrhztg.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtsamnmzyb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtygryjsfq.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtnkcxtywi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sufxvd.cn/Article/details/gtsxmpeexe.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gtwxomfvjt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtwnvxjwkv.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivzpqnon.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.bjfxy.top/Article/details/gtdvfmbozn.html

[U63] PHP：文件读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfolrvvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtxvxjnxkc.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtpmwvzsgd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cqqwz.cn/Article/details/gttyyaztft.html

[U65] PHP：会话
来源：http://dali.yj20258.top/Article/details/gtkojpzouf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtzkmqovyl.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtnegtaxcg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtgncomxdk.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtzzixnram.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gthwuaqmse.html

[U68] PHP：PDO 连接
来源：http://dali.sxryk.cn/Article/details/gtolqbengs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ppjwa.cn/Article/details/gtsoyegkup.html


<!-- 参考信息 -->