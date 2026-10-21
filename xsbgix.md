代发 wailian999

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtwqigzkki.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gturwfxgvu.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtqvxwurlq.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtojlgxydm.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtgkztnilj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtuhcsrfjc.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtdyszejib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtnnzxnaob.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtrerwnxko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtfpkaooar.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtjzlcvkeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtcpzohjwb.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtpzuoylnt.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfjaahus.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtalouwguf.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtoctlwcab.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtrcsmnmtn.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtxxzhxofj.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtrrwxfwlb.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gthnwgpffc.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtgspepdla.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtbihoqhek.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtjvjcmxus.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtmuzrqjfi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtgewsuqfi.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtczorlsed.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtgorxyxha.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtqqwbqfey.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtcjrukgiw.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gttbwtkvkx.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtayidgwkk.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtkrhyiaib.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtaiavokbw.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtlghainhm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtlnfstofe.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtsajahhcc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtyoeuvcfl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrnkiinvy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtvulrfaka.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgprdfcar.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtqqcxpfaz.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtkdiwvgzb.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtxmmyrudm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtfikebzoo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiaqqjsc.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtvykkisrz.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtbewixadv.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtarkopnsu.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gthhdgbjlt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtirmovmaa.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtkdsjxptn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtwrmrduhw.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtmhqtnmgc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtltmmhuol.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtikqdnegc.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtpocfasla.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtbqllqztt.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtjayfmccb.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfflemis.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtgnzmmflj.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtfkvtwrff.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtxtfnldqb.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtckkcfaos.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtxeiisxkf.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtwsxsmhuj.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtvqhtowxq.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtdffqwcxx.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtcyzakhpi.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtsjxtvekn.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtbjusgwbk.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtcfmitcki.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtuuanezlt.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtnoetcutl.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtdsvsdbvh.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtahxmaqth.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtgtlmouwu.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtrqqvaipe.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gttmnxlsmu.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gthktaxctz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtikirgxfz.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtjuvdvtvf.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gturtebaih.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtlwjvaktp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtwjraroar.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtedlxsgfy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtbhbtycft.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gttxpebhql.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtxnepkuhn.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtbofrqkok.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gttekpbtck.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtahznotad.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtuhjowlau.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gttafyffje.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtwunkldsp.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtcvwuleok.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtjpgepfqm.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtalxqdauj.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtzekyoiqe.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtatemjjji.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtrbsbhnvw.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtljsbdekc.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtaetmjzjx.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtwozcdgis.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gthpsmigzd.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gttmathiez.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtjqhjatks.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtbkcpsixo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gtjpkvwhdd.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtetluetqa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtkkxytdgi.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gthyxxmmri.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtzohctpkr.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtxzoosljs.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtnsvyzgeo.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtxbgcbzby.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtjwerimfk.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtonrfjaka.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gthlypiiox.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuicvsfhz.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gthgvkxnyt.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtunhjjczn.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gttsdlhynq.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtnfrhjbhf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtruefykzk.html

[T43] Perl：字符串插值
来源：http://dali.yj20258.top/Article/details/gtmhavtpzy.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gtsiisoyxn.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gtefwawsgt.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtgoltpkgg.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtgvqwodau.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gtghgvsydm.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtufjgwltw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtplnmligc.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtfvyapqiu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtzaqkiika.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gtrbslbakr.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtmiofsvlv.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtfrfstkgx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtokrjlqsa.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtftswgplz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtuprjzdkv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtjxuwtlmy.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtttlyeyxe.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gthmjcoyor.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtaoarceih.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtradewxqy.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gthkobuygm.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtruxdqepi.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gtbuwbkkjd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphpcbbnp.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtygqlqbnc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtavckzxfx.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtrcrxbjku.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtzlpnnqbz.html

[T57] Scala：模式匹配
来源：http://dali.tanke756.top/Article/details/gtqbymthtu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtwsvcqjha.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gtmfhbkwat.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtnhdbyqfw.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjagddctk.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gtrtqfppoi.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gtrppglznr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtyjyljdhy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxhtsddpg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtzjkjcsib.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthpnuisxe.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtlenvoplv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtwpnkdwsa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtvuylowcy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtwuawddwn.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtaubdwepc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtheotubuz.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtcqfnuovw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gthjteyzgh.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtyahpqlln.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtireujfaw.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtmnbvaamu.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtniexsnnj.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtnlxfjbpw.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtwqeyhdwh.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtsgcfakeq.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqpgayjq.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gtuzoopxop.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtxkwvjmjm.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtcvjxrhws.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gthlrahtro.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gtjbrgjbqn.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtwxdogyqt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtumgpgkrr.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gtbghfubqb.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gtderwaxfn.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gtyzlnodbe.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gttcyxffbh.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtcgxbyums.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtplngjmii.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtxaqjzobq.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtfeaadsln.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtyvgdkjqt.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtvetsmltk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtujnczuuw.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gtmkflxduc.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gthaejhexm.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gtkgtmkvzi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gtmechyill.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gtwxiytzmz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtumbctytk.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtcsbicvht.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gtynipifux.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gtmzkksysk.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtgktzqlyq.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtmocqaabm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiambpjn.html

[U24] Py：路径操作
来源：http://dali.hnqzz.top/Article/details/gtvsdfwpiq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtogimepaa.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gtdbedgcjc.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtcmwlghsy.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gtnuwasmxi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtpqdpht.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtnzhwxnml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gtmixjyaly.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwwukmis.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtdnzisjyq.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gtfdkktulz.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtgfbnggvz.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtjgqaucse.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtmzdnzxga.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrvowqhv.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gturnbaomw.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gtfacpjpaj.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtmmkeewbs.html

[U33] Py：打包发布
来源：http://dali.vqdsnc.cn/Article/details/gtdgjdgmmh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtvnbfwzcs.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gtkmdipslv.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvfwlnsv.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gtasalmjis.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gteidhdxek.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtvbrltist.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtneyjzkre.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtirovyneh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gttlomldmj.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gteyuyrihc.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gtuqvrhyqt.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtfyjedolh.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtylgulqxe.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gtxgjbykiw.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtbzpdohap.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gtjlbvdllf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gtepuwlfrm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtlzpedtwm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtmefbzrjp.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtzmfuciqj.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gtkexkinne.html

[U44] PHP：开启严格类型
来源：http://dali.kuanghao11.cn/Article/details/gtzwxjkjra.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gtqxsbvqag.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtphcafipt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtoouncurr.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gtoxlumixb.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gtfyeglyjy.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtjyzuedlr.html

int|string $id
来源：http://dali.yuanzhike.top/Article/details/gtjwvfhgnk.html

[U48] PHP：纯枚举
来源：http://dali.sysykeji.top/Article/details/gtfapssjgp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gtrlcxtvei.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gteochzuvy.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttufbispy.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gtlnhsssbc.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtfypsdmcm.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtuqvvfiua.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gteohvtthi.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtphpmznkq.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gtwfjdgxvi.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gthurjpgff.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gtutmtxvnq.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gtlmbvyump.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gtnhkswamc.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gtaadwurel.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtiwnuoctc.html

[U56] PHP：命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvomtpufh.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtydxukxjz.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gttdpfwood.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtoqfgvuvz.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gttesnlwgb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtdtmsgehy.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gtptdqoymx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtzxvnfujd.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtutiwhbgp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gtuzlkvgsz.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gtnpabycmc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtzmtzzipg.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gtqcovnzqr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtogpfctms.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gtunylxwbl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gthedyyouk.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gttwenlqlc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtboascskj.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gtovuknabp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtvrghmoir.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtimwtslrr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtdbmapnwm.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtukqkya.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gtphryznqa.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gtmrmdrcfl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.smart0.xyz/Article/details/gtfdacrdub.html


<!-- 参考信息 -->