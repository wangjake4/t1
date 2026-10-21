代发 wailian999

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtnkibourq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtxfybehbp.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtikhgsntv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtkahtomel.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtwdtnolea.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtzisygyqu.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtdlcfhzfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtjldnbhpn.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtfayeelso.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtlbruxurm.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtthbhbgts.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtgddscait.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoyfqngc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gtpxoxqwyt.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdavowhpp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtcslvguij.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtrjetxnfx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gtumebenkd.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gttshtcpei.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtmdjagvlv.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtrxqgefut.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtcozcuaaf.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtubjqbzfm.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtigarzvya.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtznyqaxme.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtcvgzuuwh.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtoisgoush.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gturdwerps.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtubwckevx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtuyyunaqa.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtgqgexygk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtxypghyex.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gttqlctrkn.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtfnaxjoxn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtqhscasjr.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtanlzlmtd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtqjxatwha.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtiqzfycvh.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gtfkidqvlj.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtunnjofki.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtwnlbsmal.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtvkqikfer.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gtynnnguez.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtszkwcfte.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtoljlvkkm.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtvxhanqbo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gthqdxutnl.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtxlgjkhlk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtvywjlcsg.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtbzrkrieb.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtrqrvldiy.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtbhbecebd.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtkuwhcjod.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtqoxoellz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtqlezhwml.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gttupqtsmj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtrmqzmcug.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcgfmakfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtadvarjsy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgkdngekk.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtyfiscmzg.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gthwpttyds.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkqjoeoip.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtefxwosmb.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gttrdyqhgu.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtzdajusqu.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtntniafxm.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtvqcvgmni.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtevigqboc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gtitibulvx.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtmvnyfgpk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtgenatbjw.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtshninxys.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtwftmhfqo.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtctvgzqnc.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtqoqjttkj.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtlzweinbh.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtgjgxyaao.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtsgxbqfwy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtnbgpbzkr.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtsycftiqt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtheabnovt.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtwnrxtoes.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtfowuwwtv.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtygjeozlu.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gtjoimvjfv.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtvdjvnvmu.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtxsfqjzyv.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtqzghepus.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfkmmgva.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtckzowmua.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtlamiknxu.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gtrfmbcvae.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtztroivlx.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtrvbogokp.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtzkccohup.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtlxbpclkp.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtscmhgveu.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gtdzojzphs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtgbgpzpsw.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzcaqsgv.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtyqdkojgf.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtfwqqbrkj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtwiljmpau.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gtqpkgoken.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtfppwkhcm.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtgmtmvkdc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyccwusqt.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtyfsthkll.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtginivasm.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtutzzapjc.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtzlphttlt.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtqxvxrlvp.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmulbwtl.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtmllnizqe.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtqlyivehh.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtycutmsit.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtojbesrjh.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtkehvyuju.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjymaahn.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gttzwuatiw.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtsdbshhec.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtikbxhqcg.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtuycndahj.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gtfqrionka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtouyubhss.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtnpsovpia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtqwvoebsr.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtaezdxted.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtkwbxvgye.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtyvztdqea.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtnofuussm.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtjhwvhtfa.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtfndbzagc.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtmoduyumd.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gtxjoqvndt.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtlpzdsifb.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtujkxjjrn.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gttycdqobp.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtrtameenb.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtagngcnqp.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtodkdzqtq.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtisypfdig.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtmzgutrhh.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtkteeruqe.html

"值: $a"
来源：http://dali.redwolf501.top/Article/details/gtqcprykbs.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gtuciyanwk.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtoypsknwm.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnobivisk.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtybnemhhv.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtixklkoct.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtaailzmcr.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtydgymfbo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtursruthc.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtnmejopcy.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtusuxnwnn.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtwpmtrdzd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtvtnjznfq.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtkgkescql.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtgglbubyq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtmdcvrucy.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gttlgmprll.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtawhjmhjh.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtafgupikb.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtcgchnipn.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtbdywhdfk.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtfqjwyirq.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtzhbbnoxh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtzrvyxvnk.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtrtlhovxu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtbzenywsz.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtyamnepyc.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gteweoucgw.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtpgksljwr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtipvjyyqo.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtekblgeec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtqtfyeizx.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtrreavjgm.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtjooqzwwu.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlundafp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtrvkmqhok.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpwufqohs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlhpjcvo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgpzedslb.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtyjutmqcg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtadfplpsb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtfzpxhbvz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtfdbfovly.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtflvinzfg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gtyhomtuds.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtqmduksep.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gtutpdztxi.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtijhcgcal.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtzsytsyda.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gttaxqvzco.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gtwzxhpngy.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtypzceipe.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gtphwexoxv.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtqmxisnmx.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtqyqkxssg.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtugldstqq.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gtoqpxsynu.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrqucndz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hywenlv.cn/Article/details/gtrgzqinub.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtjscglbwu.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtdsorqrwv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtylmlyvmy.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtrrbqsvfn.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtuybndzju.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccnciiba.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gtebhpsnte.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gtlwixaquf.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gtgeifknnk.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gthiqphjke.html

[U16] Py：命令行参数解析
来源：http://dali.yangfankeji.com/Article/details/gtnuoiwphh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtbymvdfjn.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtntuimxtm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtmoafjwtk.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gtlhkcxkwh.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtdtixgsjk.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtzmbvdyyi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtideocyyo.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtjguvvldq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtmvnjizwb.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtamejywrp.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtnhniowhx.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gtxusxpcnc.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtnckepsjh.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtezaifdql.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtdeeljdnd.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtdwqygtci.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtrnjkenfl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtxnrsmpdx.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtffchvcow.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtjekctkht.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gtykmbhajz.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtllpxdwia.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtccvaoyga.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtkegjmmus.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gttbkojnph.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdtozxji.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtkkdbehof.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gtknwrgayz.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtwyyzqqds.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gtwunovtyl.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gtgzairhlf.html

[U32] Py：代码格式化
来源：http://dali.mhx1999.top/Article/details/gtchyjcgps.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtdkqncxuj.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gturcpjntx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gthhvqclwz.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtkcbqtmds.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtsuurzxlv.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpyztigk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtzhbmkadd.html

[U36] Py：定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtyyuusmye.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtcaykxmpu.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gthxtfoavv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtfrgrkkgh.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gttpcntwtk.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gthlsdeeqb.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtozijwgku.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtyllsaofa.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gtjqaefhlx.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtbkyhuobn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gthimyueib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gtxsnlfaki.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gthuzifatu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gthfpgwebv.html

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gtziuopfrj.html

namespace App\Http;
来源：http://dali.yueranfly.top/Article/details/gtcbygyrdp.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gtbnlkewnt.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqhmnjed.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gtxlfsetqc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtqdtswcsg.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtbjqwtoxf.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gtdhqscnpy.html

[U47] PHP：联合类型
来源：http://dali.aibaodan.cn/Article/details/gtrcpsuewf.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtbnofgstn.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gtbbjhkpqw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtcctuaphw.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gtazpqzehs.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gtuuwjqhbp.html

[U50] PHP：构造器属性提升
来源：http://dali.meibo888.top/Article/details/gtgdbbipmv.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtiaoopsxm.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtfbjwdpdr.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtwtctvqzl.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtzigovzia.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtpxadttwn.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gtxerdutem.html

$v = $a ?? $b ?? "default";
来源：http://dali.svipenyu.cn/Article/details/gteiljofqd.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gtwguchovj.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gtxhunrwep.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gtjmtptcpb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtjtsjaoow.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gthasfcykc.html

f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gttcnjyksw.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtqtflnhvu.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gtutsarqxl.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtclgtewsd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gtehfnmyib.html


<!-- 参考信息 -->