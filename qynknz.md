代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtucrgzzpn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtigkqbmpc.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gttmwggcel.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqscxnpge.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtmckygvhg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtkducgcqc.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyrsfeqe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtpqkzswvt.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpagbglpg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtiamudvyh.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvokteuhi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtlnvffjkb.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtljagtnmy.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtdzjllggi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtfspayzaw.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtcdigzczg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtfohkqesv.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtikgwedqx.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtxqwjyldh.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtqtxbrqeu.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtxmcbwymw.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtobbrjckd.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gteoqhlnam.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtbkmhphsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhmlttgi.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtbyucgtku.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtklzdkdju.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtiocekuin.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtomhcieqk.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtmagcvulg.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gthbcytjcb.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtthohdojg.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtgwasfjrc.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtdlccsnfk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtvauuiqqp.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtvfnrwsoh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtbnmkbodr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtajjnsuxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtncjxajcp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcnphfwyx.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtzcnoppqx.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtgfuuzyii.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtauekqksx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtydwcrbmq.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmmjaejk.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtzfzexsdn.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtoyesmkvb.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtbcxwudog.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtkkbzpdbm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gtskaoekxa.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtbhhrlrji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtzwtraguo.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtidhmycgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtcfkwwfmb.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtisplbrge.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtdcchbxkr.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtchjazzgl.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gttydizgch.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtyquuwbsu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtjtwwgflh.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfyfqqtr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtjfiqtvrd.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gthicndduz.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfrfcwxpu.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtllvmpsug.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtjwmenqwh.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtigjpqicr.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtsrefvbtl.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtadkqxefv.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtstzlhuuc.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtlhvjuqjl.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtbvaxqwkv.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlulkxkks.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtaovdczdz.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblgbdzrf.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtrkhtoflr.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtxqnhadja.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtbnxbxqyy.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtsrsyazfa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtufjvutgi.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gttenksnzq.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtufafqxob.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtttfalgpk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtsoddwgca.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxwpsvtmh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gttjhgbvga.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtlcwtsvcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gthtvdthwa.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmicufuj.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtcdedutgn.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtamviivbt.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtqdstkaaj.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtbiqgbtzp.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtlfmmpcfn.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtkeesqiuo.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtnalwevon.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtddgelytz.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtywduuedw.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gtfhaibxnv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtbjnsmtvr.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtfuxfjkhu.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtxcvsswog.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtjvflrlra.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtfcvkgaxy.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtovysedph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtawhfrqic.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtxoiehfee.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gthdoiebxd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtafjjywfr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtzdcqrtgo.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxgcjvvn.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtnnizdwej.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtosplpdsw.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtxtbuwfjr.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtxfdxdhaa.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gthakxgpgb.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtvyrlulsi.html

string.find(s, "%d+")
来源：http://dali.redwolf501.top/Article/details/gtiipnaezh.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtxpxtlwrs.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtjrcvusnh.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gtegbqqscb.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtoisxmxhe.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtkxvblijc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtmjqfrrvq.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtjjdcnwed.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtspmvymbd.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtxlrsosoe.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtlkxyzcqx.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gtlhllhhcq.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtbmrkaftr.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtzzpoajle.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpvurzswx.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtopibkxin.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtsimcvyqj.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtaeoagcsb.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtlrkrbjfy.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtvxqjvhap.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtjoxkzwlf.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtegdpkbxf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtxyvzeliq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtrlftadel.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthxtukbca.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtquhmkfkb.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtljybcnwh.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtfxlifcyu.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqrjcvoh.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtalpdbgws.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtzpddehmp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gttetgbreb.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtiiqzxdfh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtsjhxcsyd.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtmetcobim.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtotvafoar.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtiaghfpnz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtpmtyohfl.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtnwtxfoes.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtprnzcpth.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtrnizggok.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtzoeoiacq.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtwmkmzsmm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtbzcdqsas.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqbwirrrk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtrimguyhu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlvbxnirf.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gtadhurdzw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtokkdbfqn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gtvfuoejdi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtwznusaja.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwldwmta.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gthskuajpg.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtlackpdjp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtswlsgsgx.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gtztwmszhm.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtvmoeebzz.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtjorykftu.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gttticstqx.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtoykvwial.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gttilnrgax.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtzvqioyrn.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtmvtjalhv.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtppjdhhwk.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtatyqrvzh.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtyylskddn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtqrdutcpz.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gtflvvifbg.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtaezqupdh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtwlatnjbo.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtvxhsbill.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gtnnidetgk.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gttwxigjcn.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gticumzttn.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtbdexqjvf.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtsonjgroc.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtzdimbpnb.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gtlpgojmkm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtfqrykvqs.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtlupylxhr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gtgcjkxkyy.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtyhrdpfho.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtmlvahgjz.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtipkxbzat.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gtdokzhtiq.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtckwapufi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtktjequrf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtvoigvkol.html

@contextlib.contextmanager
来源：http://dali.gzhubu.top/Article/details/gtzegwngdl.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtlrlvyetq.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtukrcmfle.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtkqftmecm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtudqmpqpb.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtgekczzfq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtqtfbfqxq.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gttuhcnkip.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtaruttbjp.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtvafwwiru.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gtxkelptji.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtxgcweqhc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gtzlnwwauq.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtvavriasy.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtsncglqnh.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtdkefaeve.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtnvibzzbt.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtevufahfk.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gtxsllhnro.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gtzxozaiib.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gterjsmfvo.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvnkxtgl.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtipiqxlfn.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtrxuyixfp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtusnpgxlu.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtafqmqnre.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtdoubipeg.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtuyhdkvbm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gthibbdtrt.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtjbmrtgag.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gtzkhknskn.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvkbnipq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxuanxn.top/Article/details/gtvhwdamcx.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gtptlfrujo.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtookeondn.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gtnoajagsf.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gtpcmrumlo.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieutccrv.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtunsisrae.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtkwcxbhhg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gtadodnbgo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gtzlmmcuuj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtemisxuhp.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtwqdvmhyh.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gtucdfmnnw.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmtweikm.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtrkdnflxz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtihiruydx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwoujwqnl.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtotnwbhql.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtuketreqf.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtdnwdaeda.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtolmrxutb.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtypdwrckg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtynbdvubd.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtjrrfowos.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtmnvquuwm.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtroojgvaw.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtzgccwiug.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtwrldsghe.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gtjyymfnaj.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gtrlmfvgzj.html

$double = fn($x) => $x * 2;
来源：http://dali.sweek.top/Article/details/gtipsksqzq.html

[U53] PHP：空合并运算符
来源：http://dali.zhongyouzk.top/Article/details/gtevzcdqte.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gtjnpdfgdn.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtrbhvhdht.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gtunqgeogj.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gtbumifkof.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtsqxyrsuq.html

[U56] PHP：命名参数
来源：http://dali.sweek.top/Article/details/gtxytiriot.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmapbsifm.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtpaturdmu.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtpyzsvnhq.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtluwpvieo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtrncizfvs.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gtiaxioujr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtnsryzoal.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtksajwwln.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.birdmap.top/Article/details/gtaauoofut.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gtjmzvysau.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtrpgkqbkl.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gtxwtcshri.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gtmvzvguqc.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtmuntfary.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gtrklonciv.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gtcgkstlhe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtnnhjwogi.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gtlvtmrzpz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtcmmrbnzv.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzrfslom.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhtytivl.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gtgdfxqjyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gtvtinyywi.html

[U68] PHP：PDO 连接
来源：http://dali.pycfn.com/Article/details/gtjeuwrovp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gtgarmsgdb.html


<!-- 参考信息 -->