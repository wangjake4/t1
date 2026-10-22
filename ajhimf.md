代发 wailian999

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2utdiihhg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2igabeuhh.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gt2nlkrmazq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2tvyllihi.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2qnujgkss.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtcocvsw.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gt2irmbshzd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2gszfypud.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gt2lmsebggh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gt2dfipftsz.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2hseijngy.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2zjjygfrj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2mftcgroc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2enuxbpro.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2gyhrphjj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2jgkkgbzt.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gt2cuxotvlw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gt2srfpisrq.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gt2waeisbgx.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzgdjmnd.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2axwlqrvw.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gt2fprlfznk.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2rlpvxdsp.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gt2qktgmmqe.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gt2xiyqfupr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2yeajuwpi.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2cypwqdht.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gt2zmfzacvh.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2thyzfyhy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2ckuqtupr.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2osfbyujt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2etghdcwx.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gt2kdrkuzau.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gt2ybavicid.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gt2ryjbtcnw.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrhrdvdy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2tdymwsqx.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ppkscpmt.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2edwbakhk.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2uxvsrpsu.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2vgjsfnhl.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gt2zaixfmum.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gt2bzfonhxo.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gt2oamlwlkd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gt2czeckynq.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2owurolws.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avdsplht.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gt2uvsltuma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2nxwkzfba.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gt2nisqlcbt.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2dqguuoco.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gt2racrowuj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2dfycmxim.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2bqgtcfgn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkdewfbf.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2trvwqqiu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2fshugvef.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2wejugoaf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxamkckr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2aksicbju.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2tsqpmgrw.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2ybkdlvvr.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2lntfxxjn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gt2uucwpxan.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2cstayici.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2vzyppvpi.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gt2hrvyyafd.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2qhufmyvs.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gt2powwqlhw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2umopgwlr.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2sbmdlndq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2ewxbxwkn.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2sctfzrbz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2dhedkfia.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nevzajlw.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2znjrdbmj.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2nobxvjha.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2gzquhfth.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gt2hwxyotcn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqhwgnbk.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2qdthbttw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cthjwube.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2alkzawex.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2akrslobd.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2rsnguugw.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gt2arhqosuy.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gt2yvycrdtr.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2dsphtuic.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2exexlezy.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gt2qsmijreu.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2dvhdzugv.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2svkmthyv.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2emubkjxx.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2fxnqjysk.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2iwjeptyu.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2gtoyoikc.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgtczaom.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2fmxivyzz.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gt2fgnfessn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yntsmadf.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2qzbztmde.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gt2biatpcmg.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2xppzxxlt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gt2csxgesbi.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gt2irghiqko.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2xweicibz.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gt2drqiciec.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2knityprl.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gt2zixnayqd.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2idibxihp.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gt2fylhjsgz.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gt2ngfkihjo.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2kgrloenm.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2cxxyjvmv.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2ecowschb.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2thgpowsr.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyadzxvs.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gt2vewbbrbu.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2ghzxhkxw.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gt2dbfpbgqi.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gt2lpvjnmmg.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2vsruiqmk.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2antpjogc.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gt2zjgjhuyb.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2csythgws.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gt2xwwdsaxs.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gt2dflhxdca.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdmbveu.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gt2xuaaikfe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gt2mopfadek.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2mjurwmxk.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2xxblsjlc.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlcgjurd.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gt2qozzvymi.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gt2wkqvtpha.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2huehioot.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2ehqnvnsj.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdiyaqjd.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2fkdndoba.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gt2wnaoxpxa.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2owguntzb.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2hunlreaj.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2umqduaeu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2iomvikhv.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2jeuihvlg.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gt2rdcitpwt.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gt2pprklufm.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gt2faukejcy.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gt2ueajnfhe.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gt2iovrsoxm.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2nunzpylm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2kpujlwdj.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2elxoowvg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tdktgqzm.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gt2nixxirir.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2nxjwlpwg.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gt2ayswqrma.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2kzonujyi.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozplpwgp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gt2avbrpczs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2mtveucht.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2pscitxsh.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2syitaafn.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gt2emamvxdx.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gt2enzelait.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2hgcsusig.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gt2gxqjmynm.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2guebgsmt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2nwlpdwrh.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2sgnqygrn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhsttwnz.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2cvbjbexm.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gt2ebwxqrpz.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2raycbbwb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mggytxsq.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2fijzhxtx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gt2oddczglc.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gt2xbzfamzk.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2epdzlzeg.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gt2ndilivao.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmgpcysn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nzgesfch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2aleewgpn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2yflrrjsg.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gt2avcywwxl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gt2vutyrfdm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2skjpswyi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gt2myuqmazg.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2cdaulgnj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gt2dxhtwjky.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2npndlmru.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2rvkymltn.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2nkhmqzqf.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2pmcmpkof.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2zaxuyxxr.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gt2pzrgabyv.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2mbgmvvdy.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gt2shqydgar.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2jwlsmalg.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2hmzltadt.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gt2mmlrleuw.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2cfuomegv.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gt2qmngfjho.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gt2xfxdeedo.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gt2lpwnhpjj.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2lsrzxoqx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2djbgyrob.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2bvqojwbg.html

[U13] Py：固定长度队列
来源：http://dali.guannengcc.top/Article/details/gt2irddoznh.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnnazjyz.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gt2igplcyvt.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gt2foftgife.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2duhtuzco.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gt2igrchuvp.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gt2xhoiuavu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmfkyhrc.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gt2gjiymamd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gt2giovryzn.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gt2jshhsmwn.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2knsehdux.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gt2aroqhrdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gt2xskntemr.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gt2zmurzyls.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gt2verjxyag.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gt2ithdopmq.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2cwmnnoxl.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gt2nnocglmm.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gt2kdeljemo.html

[U23] Py：分块读取大文件
来源：http://dali.havefunace.top/Article/details/gt2vbggjkex.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzykgsos.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gt2ydmqpdlk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2trwdlaue.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gt2urrhiuea.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gt2irsjlqfx.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gt2nzceujpi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gt2uuxidmvr.html

[U27] Py：异步 HTTP
来源：http://dali.aibaodan.cn/Article/details/gt2zrmobsyl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mufuxzmg.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gt2xwwkbqsn.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwffwooa.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2pggufnpd.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gt2cdlmhvyw.html

[U30] Py：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmwzwini.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2xfbdwzvg.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2zdhmqhci.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2taoxjuno.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gt2qtreojxk.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gt2uarrhwlh.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2quregdel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gt2hucaeodg.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gt2wqntrixn.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrlmwtxg.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gt2icnqutcx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oljrqimb.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnyjsizu.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gt2pvvpaqln.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gt2thfwshht.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2qljbkppi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwnovat.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gt2hegyawdb.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gt2fucdpseh.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gt2jaduarnu.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gt2ptssdzgq.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2zgziyhmm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gt2hekuvddh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gt2mdgfzwmi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gt2lghxwqsq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gt2cbgvxpja.html

[U43] PHP：声明命名空间
来源：http://dali.yvedp.cn/Article/details/gt2eocjmjcl.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gt2nztrvrey.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gt2iptwcenk.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2fgjdeaha.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gt2efrqciok.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2fjmfruar.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gt2ivxwfcfo.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gt2mdhqnion.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gt2pvsnghbb.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gt2mspyyvre.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gt2tkykdqro.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2xoucdwid.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ctmakjao.html

public readonly string $name
来源：http://dali.tanke756.top/Article/details/gt2wwlddlpt.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gt2bqccfwcy.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gt2qftepaci.html

[U51] PHP：数组解构
来源：http://dali.jyoumei.cn/Article/details/gt2bztlqoit.html

[$a, $b] = $arr;
来源：http://dali.hammf.cn/Article/details/gt2vqzsxeoh.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gt2wtmfieej.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gt2aibzjvvk.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnewggjf.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gt2cnwuoelm.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gt2fmkdfvtj.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gt2jdrmzere.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2urgnnzsj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gt2mhylxxdk.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2msspocnn.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2bgbjntau.html

[U57] PHP：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2upxocxbf.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gt2wmklfjqh.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gt2ctucisyy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gt2tdrofcii.html


<!-- 参考信息 -->