代发 wailian999

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gt2vqxppsmj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2xfpoiloj.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2kfpqhoks.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2syflxusa.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2hrxfygor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2faxlrxjr.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbgrijqe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlvuusie.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2hzxkwfbq.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2oiqmhwai.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gt2wasjilde.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gt2kgkncfad.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2sofjkpvv.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gt2kqerejja.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gt2qlvbczkt.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2ognjmery.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2zralsxgz.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2huvkaaqx.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2ptyiwylh.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2mdlxvwux.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2hnlcjtpz.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gt2sbwipqyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2lwfrbbnf.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2veewyzem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2lusmotgh.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2sobsngrf.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gt2yfmahpol.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gt2rgggozzh.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2rrfiirfa.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2dbxfksno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2rylrckmv.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2mykjwndj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckovxmvl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hzhbgbxz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2wkfqbslu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vqhqkonb.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfvtinrx.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2glgrykty.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2edpdkubi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2gyhnmmzh.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2ekiyoyrq.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvtaharm.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqcnvjnk.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2gqlvhhhd.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2pdninutg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2dbudjblk.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2uijrwcqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2cmicbint.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2fyihxvgb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2xtnvmmmp.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdaohkqa.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2zghwgbni.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gt2nghphlfw.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gt2eaeqfowi.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2wysvwige.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2phjuurqv.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2iurkckay.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2ogkvswkj.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvusptdv.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2bjiwotct.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gt2glwzosfl.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gt2encxzkhu.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gt2uqzgpzie.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2rikcwvub.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gt2qslialwi.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2eotnznlh.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2yqsyipbp.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2zjevzjsd.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gt2qkewnisu.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2dzfbomec.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2oxoipiag.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2usftgsrs.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gt2hudttvzx.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gt2ypxglpfu.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2zzdeukxe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2ytkuwfsh.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmaqgzrm.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2obobzimi.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2aekdzupg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynnrtafx.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gt2ftuwvmdh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gt2owgwzsls.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2illndlis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oalsdube.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gt2fccietpn.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gt2jkodcogd.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gt2wfuyjycc.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gt2hyldlihv.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibguwmrm.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gt2lstfaevl.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2pmkseqai.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2lhqhntir.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2acxxhcgb.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2gsilgeyy.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gt2fmaacylr.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gt2bymrftok.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2tussixhx.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2zberqnih.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gt2numknkkg.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gt2iutyxrfj.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2xmtplgij.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gt2zabshtje.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gt2imehzowg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gt2uguwlvom.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2jeupbdxs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbgjeqmj.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2xvmmhuev.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gt2owgchvkg.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2begtypbm.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbgjuhgs.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gt2aqvxuhnu.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gt2mlsweeso.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2xtsrsbzh.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2wvzostle.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2auhttund.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gt2jwvkkxeh.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2zcfofmtj.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbfgaoav.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjterltz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2dtrhhzrv.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2aprjooyn.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2aatdryku.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gt2zpcvrzmn.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnrqteoa.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gt2lrmkhiwu.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpmzazna.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gt2fazetfqm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2liyqqqgf.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gt2rbqpkhyx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2jzwsbjbv.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gt2yuxzpcza.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukycwsrp.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2ttetfumw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2bulzxohu.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iihxngvd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxkwbkfp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujageitg.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gt2jludjaue.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2cssiaklr.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2vbowbney.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2uuqsjyrp.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2qpvxhkeh.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2uxqphpmc.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2whuhomlm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2afisqidt.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2vnvkovxd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gt2hdapjemo.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gt2llfnrutt.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2jfykfdyr.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ktmyhdgo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2szfcivhw.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gt2sdzwnsvt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkurnyyk.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gt2ysgpjnzd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixqdbafl.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gt2bnbrodzu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gt2pbbyekkn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ydsoivij.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2lovxggab.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zhtluujg.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2pqoltvvg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gt2jvnobhxr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2yeifhhzx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gt2fhzoggrw.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2oudydylo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pllnkphb.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gt2friotzib.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gt2uzgglkhc.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2zfgetepi.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2hotpbgks.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gt2afceurip.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gt2rawcajbc.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gt2biwoetro.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gt2mysgzlns.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gt2nrmhwcqi.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gt2ckwtzhii.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gt2toehzaqk.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gt2lrlpbnzo.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gt2qilpbqoy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gt2hlgtbsua.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2hjmuwdvs.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2tqnvlmuy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gt2wxrmranu.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gt2accgwdma.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2hbjbbfnq.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqzptcvo.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gt2gmnnwgga.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2goeqpxwh.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gt2gnhoctfa.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2egevephu.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdomutkj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2yyaybhjw.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gt2sorjvoij.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ehwqpu.com/Article/details/gt2gzrpptpb.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gt2bbqjsoul.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gt2jhtvjjbw.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gt2atdijghe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gt2ptjwtfxw.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2ctufsupn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gt2arbfgyak.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gt2dxkuioqq.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvnpjmog.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gt2npmxyqqc.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2dflzqekq.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2bxmkkvmk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2hzyawreo.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gt2rudaoxco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2qgbckxqy.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gt2kdmwtxxa.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gt2ilasbonc.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gt2jeqbhmta.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gt2acnnuboj.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbnpdytc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gt2ymumztmi.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gt2ysvvfwws.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gt2njrktyeh.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gt2loykwcsp.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gt2ttohieyo.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gt2uonisjvz.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2drsyqbip.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gt2hovonfeu.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gt2ahxgucsa.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gt2keemqxwq.html

ruff format . && ruff check --fix .
来源：http://dali.mhx1999.top/Article/details/gt2ooowfaun.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gt2nofmmueo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvnsidyn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwirsvwx.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtubfqhq.html

[U35] Py：发送邮件
来源：http://dali.jiagoushi.top/Article/details/gt2ukghnlpm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxuanxn.top/Article/details/gt2cbsiwdcv.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2ziylmcrp.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2ddhhtint.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2vvvvpcsz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gt2xdyxlbps.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gt2dxvxqqio.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gt2oyphwolw.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2whydoapt.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gt2vbjxooly.html

[U40] Py：打印到标准错误
来源：http://dali.bjfxy.top/Article/details/gt2peiftinh.html

print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gt2phyircmv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gt2usskrhik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vssxwzop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gt2zssquaoc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gt2ozdobgmw.html

[U43] PHP：声明命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2rfbzshxp.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gt2jubnnhyq.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzwtbivl.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gt2bxpziwah.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gt2ppycycfa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2xbvsinxg.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gt2acreiaja.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfrfqndk.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2drvvizyj.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gt2qqmthocq.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gt2glpfcxvg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzztufsx.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gt2sulpptda.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gt2hndjqfrr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmxgykh.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gt2vnpngfdr.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gt2ltcoyjfw.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbahplcw.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwqgpled.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2iswqefsx.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gt2gkaavtpj.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gt2xdqeakjr.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gt2wkbvhnce.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2obzhsahp.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gt2adakhuak.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2glsdsjyj.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2suhmvjjc.html

f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2frazibbq.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezdkrzui.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gt2ndzlpzgv.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gt2twqseljj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2aflnioxm.html

[U59] PHP：自定义排序
来源：http://dali.hammf.cn/Article/details/gt2szsbrbkm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2udnnjgwd.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gt2dtqctvua.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gt2uigzqdux.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gt2srdnnbcv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2psyyhwhq.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gt2gefyaqcf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ppjwa.cn/Article/details/gt2mjjdvsev.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2xgolrxnn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cucudq.cn/Article/details/gt2onbdztgt.html

[U64] PHP：目录遍历
来源：http://dali.xinyue.icu/Article/details/gt2twichyyl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhoulong.xyz/Article/details/gt2eejottfp.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwqywds.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gt2nwnmtwgh.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekpwjcsi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2sqvuvpzb.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gt2arjoirjn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ybcxt.top/Article/details/gt2uvkiuoaq.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2zwwilwmb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lopdcjum.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gt2lpnuqoqt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gt2aetxgbez.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkyetxul.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangdashe.top/Article/details/gt2evmnrpbx.html


<!-- 参考信息 -->