代发 wailian999

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtcldjyujq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtiveazbfc.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlljgrfuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgefaatlt.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtomojjzya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtpkbgrsrj.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtflpipvjt.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtmgzjdcve.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtrwhpmyjx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtleinszyl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtotusdcux.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtdchxdcum.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtgnshmlmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtvplfglvu.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtfwerrgpp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtmshqkpdy.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtxscarkue.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtjivpjayq.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtvjjpqcqu.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtragwfahv.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtsxhndgwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtobfstjfa.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gteeirdvwj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtjzwdypdg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtullevcvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtgdfsxyiw.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtoceollxy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gttiwhgnay.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtzyugrwhr.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtkjpmggat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtklozywvq.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtvnqsdcrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskudurkf.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtuwfybdzb.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkfuwwss.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtgxgrjmqq.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjpffbeue.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtfcrrdamu.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtsvnoprdf.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtbkephudt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtlwvrxiog.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtxqioyzuq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreyqgtpy.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtdiqqbybg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtsjmtcngz.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtgnphwvlp.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtbxrhndhi.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtmjjfjhux.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gteoytrxse.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gttvfjzuzy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtekkqwsuc.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtojwiztol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtiaubawjo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrmajhywz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gthiphonnn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfzhjoxfi.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgrlquim.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtkpomoyad.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtelqemawe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtinhoaojf.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtreqclmwc.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtgtxeirmk.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtwqtfrxxc.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcdcqqzq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtdcmsjblx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtxozkrqvh.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtvvhlxtrl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtpldzwekf.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtymyjiwrt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtndqpeshy.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtnbzkvjgx.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtgyqjrgoq.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtovxvtvaz.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtptrhiauh.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtjzpdmoug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtxozquoxt.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtoizknuzt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtqvbfubgc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtaqsyqons.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtieeuwcrg.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtexradgvl.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtknbhzpbg.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtbfxwtufk.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtpnupghpu.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtlzzulklq.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtkkqfxmit.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtpuwsjzgo.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtokmcxdsn.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtlywdlymu.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtytpymebp.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtecqzhsll.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtauywmlic.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtcfhmypnp.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtygkrjyso.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gttufttlmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtzuqzejmq.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtycxlgpss.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgiacawo.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtaxsmrgtq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwtszxll.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtlolgiikh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtuhlqxjuu.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtkqhfeywy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtmnniygxu.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtnxptugyq.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtykurvqzy.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtgxxcmhst.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtoksryaav.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtjkvnyryi.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtjmiksxgr.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gttuwthuap.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtotssangc.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtwysqwpud.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtaypyrqqk.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtoxslusuo.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gttxeincqn.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlxekejjm.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtnihnjefc.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtcdzxhiqx.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtbtcgdmsd.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtmpjepdjh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtykakmehu.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gtuxxkthav.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtwbawdtza.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtosrepmhm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtxfoovgtw.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuqfmyyk.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtfdyacxtr.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gtqwalotzr.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtnnohlgxd.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtrbejqutt.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtmqfwidjp.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtvdrfsfwq.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gttuwffimj.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtngigwybr.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtpnrtcvzm.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtvohcmohe.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtuywwakxn.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtdmxtsqxu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtrwqubxga.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtvxcxvbyl.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtgalcgity.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtjuzywxad.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gtldjhqbgv.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtcfnrtvpd.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtehjdueua.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtopooemjh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtekqaxmgo.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gtudaqfukr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtpwhsilhv.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtxnfbbakl.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtzijjqdhq.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtztikhtvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtwfcnsupz.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtshyqcwkc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeeqwags.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtzrxlzwwf.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gtlnnlipkj.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtdetjxxhm.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtxaknlqha.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gttticetfd.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtswrtxyir.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gthnsdayqy.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtkqnwvtco.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtkiyyxabl.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtpydoquqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtgdskheol.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtdvsnoqkf.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gtsiwmccgt.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtescgfmpx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gthmdnszxo.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtymwqqkvv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtfdhbdidf.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtxztpidrf.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtyqggaufb.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtucwrvknm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtpnwqpugb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcaegqlza.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtzxtfnsjj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlohojgxi.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtvsgvubuy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gthjxvdaji.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtorxwksbf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gttszzxoni.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqjhczdd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtsikuqwcb.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtycflboub.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtldgznmzz.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtysbtamkk.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtirvcridx.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtufaudjdz.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gttnxcrxbp.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtoepduyfn.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtwpoklvua.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gteerqlegw.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtueuqlobt.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gtdzexsisu.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtgycbbaio.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gttaltiltd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtkcppkxut.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtbthzqhnw.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gtxdwmbvym.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gtafvtwcay.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtbowtqwab.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtovhubkkv.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtpjstinhb.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gttqwklgaw.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtsjaeuvjq.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gthtchnmok.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gtyxtduxgb.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtezksmuba.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gtuqdrbqsg.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gttrggtczx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtymarcdre.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gthjhcnrgq.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtdbvtajlj.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gtsazwvhen.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopkdbsel.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtxwfjseul.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtpbdvilem.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtbnxehixf.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtgwuahdal.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtkkiblhfw.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gtjkwmdybu.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtqfoyvcth.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtzyfbqoab.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtxhfvtmas.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtgappmnjn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gtswvstlff.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtdqpjedfr.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gteutppwta.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gtjmexiqcq.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtfqlemntl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gtsffycnav.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtgszrsksh.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gtfhlmxwbn.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtuqfetmgd.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gtlxihmliu.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtkxryihel.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gtnesbigod.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gtqhsxwtpi.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtqegdsugc.html

[U32] Py：代码格式化
来源：http://dali.cheryme.top/Article/details/gttrblimzs.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gtquistcci.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gtbjzkvzdb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtumsctipt.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtykalrexc.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtlogidlnb.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gtcvtlkebj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtnhbzrxel.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gttxduyqaz.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtrtpwacqy.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtcoxbpexk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtakytjzit.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gtdssdesmo.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtobtwjykl.html

[U39] Py：判断是否在交互环境
来源：http://dali.daria6918.cn/Article/details/gtdzymmkff.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtcmmakuez.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkhneshp.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gthzzzobht.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtmvigaakr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvqhgubj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtessstfnu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtkpkmcklt.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtayddbtcc.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtrbjmzqgg.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gtycaofobe.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtdrszmolt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtnpbycxtk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtznkynhcj.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtniturrqn.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gtgpccidri.html

[U47] PHP：联合类型
来源：http://dali.chenlongwang.top/Article/details/gtenyshrst.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtzogwlfhd.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gtyzwtcojb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnxiangtu.top/Article/details/gthvccsbnh.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtgxatgcpk.html

public readonly string $name
来源：http://dali.cheryme.top/Article/details/gtidofbojt.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtbyplhxvn.html

public function __construct(private int $id) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttyunmzpl.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gtzwlmimrq.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtptyksknc.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtbjksocuw.html

$double = fn($x) => $x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtaphdioda.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gthlwgekjb.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrkklqmf.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbddtdf.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtvakwfvvb.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtmghtspdr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtpdgtotck.html

[U56] PHP：命名参数
来源：http://dali.sufxvd.cn/Article/details/gtnfainomw.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtphclgcqj.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtlvcssnfb.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtfjegsmhl.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gttlfqzonj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtojsdyoun.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gtdnwodxnf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtsfpvxpvn.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtrneexzxq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtnolrilrn.html


<!-- 参考信息 -->