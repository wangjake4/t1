代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2twezmzgn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2fpmdyljr.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gt2szamxypm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2yebrpcqh.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gt2pafoqzbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2zwgalhgf.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2mpjtxwsd.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2agyqvxgf.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gt2nnlizoom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2chiehfxe.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gt2sfvwyokp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2mksnwjxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gt2vjdfladq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2nbygvjqk.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2xqxpclax.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2jljpvrkq.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gt2fobhvmtp.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2ererdtlg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwpfxpyl.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2tjefjvub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2obrfchih.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2mzcdzobc.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddrtikso.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2mqpdliyi.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iloqzvhj.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2rnojqcir.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2jjvypyaj.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2jughggss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2apmwozhk.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2odynyshx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2ufmkkqog.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2jvlijaqj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2aacdpiaz.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2gbdkbukt.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2vuqrirne.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2sxotedio.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gt2bmddvenk.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gt2xxcrzaua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2kdtasbzn.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gt2ibrosams.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2uhzksszv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vsfptrlf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtjnccbu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kjzurusj.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2pwgdfrtw.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2lxzrtlhp.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2oixrsuyf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2yajgmocu.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2fvqsrygb.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2mtpdurmm.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2ybcdkysx.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2abopffqd.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2gbdmixml.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzeeeixc.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2tfvfbaqw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gt2whyqohoj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2uemkxgtp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2dnquvalj.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gt2swskolhf.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gt2qdinifsx.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gt2soupaibi.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gt2hzynthzf.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2okzoxfxb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzcuaxaq.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gt2ddtvwhlt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2mlimsjhs.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gt2nsiicafr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2jnxokopf.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2uoeespcd.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2lhuhzswk.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2tuxgkztu.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2rjiwvidk.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2egjfxiwh.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2erygftol.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2qhkgpdri.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2qrrvhius.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2jbvxmuxy.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2qwophnca.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2godwavgf.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2vebghbem.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2smahjedc.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gt2gpwojprf.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2pvibkxav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gt2zzpbyctt.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gt2ctvorngb.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2iwnecurc.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2awzoxjuh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gt2giqwznnp.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2csambqym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2kakbuder.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2wtuyxdiu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqembbse.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2ldsfazrz.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gt2mmnbaxox.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2eptbolci.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gt2urschkjj.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2ocfdgsif.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gt2xkhyekcu.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2vezqmomp.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gt2krfufire.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2uqpmuhsa.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gt2gwasxpof.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2wszaoxqe.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gt2nhaigexn.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2oxbuikxz.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2yddfgoot.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2nbclxgbw.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2hzgqtryj.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2qrarvknr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gt2dbgfsfmj.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gt2jouysgtt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gt2cyzetbna.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2dbnkmrcn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxzaypvd.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acdvhebr.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owzdueaq.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2elkdfrbc.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gt2wjwproub.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gt2yyxoqxxs.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gt2vnkapitf.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2zdxdahtp.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2alnsoaae.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kheytobi.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gt2kuqdwnoq.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2kfnnuisl.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2dneqomsy.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gt2xvrzcvjy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gt2vzqagzji.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2vunykftf.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gt2ikadalpi.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2kmmfeiai.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gt2yfjdpclx.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gt2iaxdrtjz.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gt2tmhboumr.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2ycggklrl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gt2gqitqcyn.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2vzulkogx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2irjazrzg.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrrvaqdl.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmbtvbhb.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2cllqxaku.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eamnlnzk.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2esjgqtqb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gt2pkmycxit.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybjsxxay.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2pvqplvjx.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2jhpglncw.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gt2yigcfugk.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2soboeuny.html

[T53] Scala：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2blnshoul.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2jgsgfqxa.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2gmamhbha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gt2luesfqdk.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2uojnlmqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eboncoaa.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gt2qwqrsher.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2ndpowpvy.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2cyjbhhkn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2osunpjds.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gt2cimrgiuy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsecuflj.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbujmnxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2lgyqeiih.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iewrnmrb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gt2ukjtakzt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqkwpiox.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2isjathpz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2dsaifrln.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2gcqcywhj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gt2kucggdod.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2xeyzrfzr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2ezmyogph.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gt2zmehduna.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2bwdtmspj.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjntqkyr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gt2useymycp.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gt2camiyhdn.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2hdeukmoz.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2nhshgfpe.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2mavvlpyo.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2atzkwwnj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlcvcuq.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2vzkxdymu.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gt2qlycexut.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gt2gntxqdgw.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2tacgnjfm.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vunensdy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2pjnuyjwu.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gt2unacyfgw.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gt2egidihni.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gt2zdfmmnzg.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gt2andqyrnl.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gt2yrwzelyi.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gt2ocoifxcg.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gt2qhckjqcr.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mclaxrsf.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2xvzygexn.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gt2fquifaws.html

[U16] Py：命令行参数解析
来源：http://dali.0kj1m.cn/Article/details/gt2nkaxrgiw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oehntaqh.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gt2ajrhtcqg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gt2mwfrtvpd.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gt2rthfwlet.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2bljbmhlk.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnmefzvp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gt2yeuxgkjs.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2ekwxnuqn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gt2quowsdou.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvvezxsu.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2suyxwmql.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gt2gtpceekf.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2pgkabykh.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gt2parcucad.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gt2iqhwfagp.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oaxfmpzf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2vgdaqhdg.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gt2xpxbbyxw.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2maytzjvg.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gt2flxhfhmm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2eedemqly.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gt2clssvplp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gt2kttadpdy.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gt2kcjkxlgv.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gt2jkkvoedf.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gt2ijcmnauc.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gt2nseiatwn.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gt2gzrrpojb.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gt2csbmjrdi.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gt2vwvlklfp.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gt2znxpxgnm.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gt2whjzropb.html

ruff format . && ruff check --fix .
来源：http://dali.cqqwz.cn/Article/details/gt2radijsyr.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gt2ieafhbrq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2kaeifozg.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gt2tsmbjmim.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gt2rvsnbgkj.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gt2vgdudsku.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gt2ptkfrava.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gt2vbhimmqm.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gt2gykwrflt.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gt2ehbpbgkd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gt2odlvrnof.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gt2zyhykebh.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gt2nymeonxh.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gt2yvunhqym.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gt2zipuhcha.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2huynupat.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2hfgisaqf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gt2ocgpcqws.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gt2qlneniod.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pycfn.com/Article/details/gt2zyncvlnm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gt2fosdfahh.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gt2syoqypbo.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gt2azrmrrvq.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2dhxppysj.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gt2qntvbyno.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gt2axlmtims.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2vbmxvows.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gt2zctqrmsc.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gt2kmgmeoan.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gt2ysvitsds.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gt2kzdmhhfc.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gt2wyfgubcc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ldpbwqfy.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gt2yeqenhwc.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gt2ffcjybsc.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gt2kfiotagf.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hsbqukzb.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gt2rdnjrivj.html

[$a, $b] = $arr;
来源：http://dali.shuidangran.top/Article/details/gt2gojhhvpi.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2qgiskfum.html

$double = fn($x) => $x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2kekmneoa.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gt2yxdqsrpk.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gt2xkrnfvbz.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gt2gbdnwicv.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gt2syhajvky.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2wqhbbsmm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gt2asojykaa.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gt2ujfncvxk.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2slpcwfyd.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2prepwwsk.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gt2tmhmicar.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gt2vatvbqve.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yonumen.top/Article/details/gt2nemibund.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gt2apthmkhf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtoeqmvx.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gt2rglplkwh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gt2brplgswh.html

[U61] PHP：正则
来源：http://dali.yuxming.cn/Article/details/gt2btnsrync.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbhkruhy.html

[U62] PHP：日期对象
来源：http://dali.nwbrower.top/Article/details/gt2cbiwzndo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gt2gvwxfugc.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gt2ubeujnsv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2injzbcak.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gt2nsczehaj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gt2plkhecqs.html

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gt2obkssdff.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2mqgkhwjd.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gt2fansqmbh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gt2vzntcofy.html


<!-- 参考信息 -->