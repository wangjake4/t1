代发 wailian999

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtjioypqry.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtinnniycg.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtuullpqrs.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtajzjwofb.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtgylulngg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtbkjewebd.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtkdlvqcgo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtrvzyxbnl.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtyltwlvws.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtmpotqicu.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gthgimfozv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakwqfkwt.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtfsfahaql.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtbyuxhmnd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtnzvmrtus.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtedocchuk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzlflzhu.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gthhxoclej.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtegqwdooa.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtyxfnghdu.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtimwirvkr.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gttlnecpuz.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtzmybreym.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzzgwfoi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtpphkfgqg.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtocjxkvll.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtmzmwqrev.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtoystqzhi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gtmxfcdrya.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gteitklszw.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtqntikkwa.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfaycwvc.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtjyppxhdr.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtfoqvwvhl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtgxnqddzj.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtcsyjaxwk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbacougq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkcqpjucc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtmtwhjzzj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gteqtrynrd.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtnutfwsca.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtoswskdhh.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtkrzaxrtf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmymxssu.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhewracn.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gthrzhvsfr.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtjifquuqj.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtyjlnrojz.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtgsgqvidy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtkktzgwdg.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtlvyajjmu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvibpoxkt.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtohcrxgzu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtpvlhhpzp.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtdncvvali.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtajwymxsh.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtaosugera.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtrvlbffiv.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcpopkks.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtapgorsne.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtpkotbpsf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsebiwnw.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtscdpvrmz.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtkuwmesmh.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtiaxgsklr.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtjlfmwzjg.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtkhgtzzvr.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtvvnyksbb.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtumhxhixq.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtzwhndzrx.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtzvlkzmfp.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtusczsimj.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtomqxrvyz.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtdrumjlxw.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtpbxixqar.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtzdonuckz.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtjsknscht.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtjndnfbth.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtzggzukcb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtfldnrgpw.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtavuzndla.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgsdljko.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtycfdwauk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtoschcbrz.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtkpboomuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtssxrqjfk.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtszhhdqjj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtkkkzvaii.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtsztvdwmj.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gtzcqfxybi.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtxkxywlem.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtxdczhjxj.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gtappzrpqw.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtegggotrd.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtwgzpafmt.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtvlwieqwl.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtlbdbkkgx.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtoyjrmqul.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtcrczzviq.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtzsmyadcv.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtrrcysbjw.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtqpksgwnt.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtvijxibje.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtohuwoocp.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtgmhxuxgd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtjhbfugsx.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gteguaafxk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtybqnltji.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtjjssolkr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gtgoszueil.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtcoddzxed.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtgwepyhfm.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtkxjhtipu.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtbmydhazq.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gttuvzgumq.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtmahkswhn.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtdzhlcjcr.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtbcbibluq.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtpdqwbtgc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtgcdnjsvc.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtfapvrekw.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtjmpjgbsn.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtqortjdnm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtqhbcdtab.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtyplpwdoq.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtjtihgggx.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtaxhgwrlx.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtgstmxnbl.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpsjllow.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gttuhzegei.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtznehqouj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gttatmwcbb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtvncspdsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gthlfezkcc.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmebzcle.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtnnweafux.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gtzugggbay.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtjnyhefuu.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtyispvbwu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtsztvabtf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtxwcncylq.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqqczijf.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtxtftpomo.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gtqxjlevlf.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjadgirqq.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtccxvhmwh.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtzaxruuih.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtmjedclmj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtsdxdkeqt.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtopxuehnh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtjynvpsvf.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtksvscxff.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtwbakubfw.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvbjbvxfy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtylnsrcsy.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnccxvxyy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtwnrkhnmp.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtleummnhi.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtjnwrweia.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gthtqszkmj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtrymxfdmr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoovpankm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtyvgjpmkr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtivwiwmey.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtpepfcvba.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtcjkynhlh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtocuaptta.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtmbifunkp.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzymgfvs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gtbyxhayrf.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtdmyhctpj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtmluhtsns.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtawelcnys.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtclkluspk.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtmaodfswh.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtykvwxrck.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtgszkfwqw.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtuucrscrz.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsahqexsr.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqvgbpap.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gtkzugzbvr.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtxvdjgcrm.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gthzsswure.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtgimwdamc.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtllsbytvt.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gtyvctxvln.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtusiavlhm.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtqeaatmjw.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgdmfqsc.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gteuqmmjos.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtrscoetip.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtmakrnxxu.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtcrzrvwzg.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtrtgapauu.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtfobbkvuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtwpqjprfy.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gtwyhzkejp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtwdhafjbe.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtckmobxra.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtuslezatb.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gthqdsgyfy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtolqigujg.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtvgdaqvvt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtribbycda.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtvjbiwidh.html

@contextlib.contextmanager
来源：http://dali.xuanzx.com/Article/details/gtcpwdbpvz.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtulhybsjc.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtcybdcsxe.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtijvmproc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtxbrqtxus.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtqfvyoptg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpihnbvx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gtvfosnxyr.html

csv.DictReader(f)
来源：http://dali.xinyue.icu/Article/details/gtlgkdtgnm.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtgmjiqmzt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtdvnmbsjn.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtlzviyham.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjvbsox.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtouqlcmdb.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtqzuzeiig.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtbecowneu.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtlspmapdh.html

[U30] Py：数据类
来源：http://dali.yonumen.top/Article/details/gtyqhvfdbh.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gtdggfvyrc.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gteectwltd.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gtuxdantaa.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gtkmtsarau.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gttybjjtqn.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gtmzxhtyik.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yangfankeji.com/Article/details/gtcluqyhcd.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gtaoqpqist.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtstyvaajw.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gteqjrmhtf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gtwvybaflj.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gtynpkwjod.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtazanzndg.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gtvfmrzaot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gtoaytljms.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtqisnaoaf.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtiijugrlz.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gtkxjadpvn.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gtunuawbzj.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtvoadsrym.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpipnxkbr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtioofsxtr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtaxybozae.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtfnfnwkgq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtcupqnnwv.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gtraomadcd.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtezusjhoy.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gtcmrmxuox.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtveytptwv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gtuwqsgeud.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtctsfpwdc.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gtqnumegal.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtxffcjyza.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtsrayuxce.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gtavgtuhsl.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gthuidelhq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzvimetpi.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gtrsstbswl.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gtytwtjzcv.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtdycukxpy.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmkvtkrop.html

[U51] PHP：数组解构
来源：http://dali.jinqigufen.top/Article/details/gtzhwergbx.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtlsgakdwq.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtuvyzknrn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gtbmxhadnf.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtjmezfkkb.html

$v = $a ?? $b ?? "default";
来源：http://dali.shzxlz.cn/Article/details/gtpomrvuvr.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gtettepxzq.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gthaqkbydj.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtrrgclnzx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqomkgoj.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtuhcztjdg.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtrdidukqx.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtquhbzavb.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtmsvcqdob.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gtzydkromy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gttpqchaye.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gtqxenvkox.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtawqleoek.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtaaparibe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guowangkeji.top/Article/details/gtbtnmwkss.html

[U61] PHP：正则
来源：http://dali.zhixingplan.top/Article/details/gtpubibudm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtaulewyzt.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gtdxhjbqra.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtekpxtumu.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtvqyjcddh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtomkzzvkh.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaylectys.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtszmlwhgv.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gtbdeiuzgj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtywovwaws.html

[U66] PHP：设置 Cookie
来源：http://dali.0kj1m.cn/Article/details/gtesdldket.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gtyvwumsvp.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtfkfxffui.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtjnolobjx.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gtduniwxlm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtzgqqutif.html


<!-- 参考信息 -->