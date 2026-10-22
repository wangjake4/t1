代发 wailian999

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2igwqokpg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2mzdvaitb.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuhhvxnu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2tjisehkr.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gt2iismamco.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2eezgjeti.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gt2hpwcqdin.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2ywaaeaaq.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2oidlksrr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gt2iklvujiy.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2awexeqek.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2pzahyurh.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2hczfzlgn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gt2ynrgxhok.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2gbvgimih.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2xaycipfv.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2wtrtkruo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2xbbdkkbp.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2lqvczqhk.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dcuyzpqx.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gt2oeejfepk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2ejzeqpnn.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gt2jjgmrzlk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2febtebkx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gt2vqhnnfnm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2nrbgbgqv.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2oxqqqksa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjqafecm.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2udlgmghd.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2yblddhwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2eixtzzhu.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2qmnkniof.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2goncbpie.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gt2ltxxbbge.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gt2vdtshrfx.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2ptlresce.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2sbquwvjq.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gt2juwinxks.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2bykivcwj.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2xkaxvwwo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gt2uakvmjku.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gt2minrnxou.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2wwsjaoqg.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2wqdmgzdj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gt2goyafxrq.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gt2mfeqmnmm.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2pgtzpopb.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2ypyjelfk.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gt2htpriglv.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2ojudobyc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2hgxrxncl.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2qbmfhfdh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2puefvgdj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rzfzytvn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2enjveujl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyateiey.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2rncaoxzc.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2nwuoprlx.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2uaeklirh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gt2qqflambl.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2tqwhgjtw.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2ilkgvgqg.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2rtqcawde.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2eigncobo.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2yspfchgi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2vkcbtsdv.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2poslwcio.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2yhxpvfvm.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2dkpholyb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2zqenrkpp.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gt2rfmosixq.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2fjfoxbwy.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gt2bqblqkfw.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gt2mikymoqb.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2ioyqxtgo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2voiocfun.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjjcbndp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gt2eoxsegpc.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gt2hxojrpis.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2wngoewmp.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gt2gkkcegsc.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2gtpdruwd.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvqkrnyk.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2ivmhesxn.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpytiqdv.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypnpyfed.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2efqzvfri.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2rydzwvnl.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2aqcnhytr.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2szqgvvjn.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmrbmlbw.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2fqtlzwaj.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gt2kflyyuab.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2tnisdkre.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2jyeqlqjy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gt2burpixuf.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idhqrdpq.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcudupaw.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gt2nctfusdh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2mqfiggqq.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gt2aylgetak.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gt2dwqctxqp.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2firtiffd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tybcqofm.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gt2izzdavew.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpqeoaf.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2bvikruxe.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gt2xjcphqug.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2wlfqiwpq.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2hjrqwcdf.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gt2nasdskpe.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gt2oxsfalev.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2eekogodw.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2efqawiqg.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2skjbhtoz.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gt2jpxyldek.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2wawhakgn.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blttuvov.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gt2ysbbeoma.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocxtfndp.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgbhfnia.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gt2vqnmzvvf.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkszmtew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gt2locljtct.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2vqqsnzob.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xziqi.cn/Article/details/gt2kswfywta.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2eecwgxih.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2xjpxjher.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2iaepgypc.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2pcijnlvw.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2unbliaww.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2uzsqdmmn.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2qwrzkqut.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gt2ukvpzyan.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gt2zshsvmng.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozzbyvns.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2znfiaqev.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gt2hxnmylvp.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2ivughnxe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gt2gjmyrfbn.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsktvnel.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2mshhlldl.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2htsrvgqn.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gt2gsxxkfpl.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gt2udbwwpac.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gt2qalqnpdp.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2bbxpdwpf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gt2kqyhsnxm.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gt2misxgwaa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2owndmpwo.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2uqsdyqgo.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gt2kwagxgmk.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gt2wcutanno.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2zyxoaglu.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2dogwjfkz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2uekhcsao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gt2tzfrykph.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2gyjpwjee.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2ylfkzadm.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2aanoaiyy.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gt2nygiduns.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2mdfcctzh.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2bmaxcosf.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2lpbgezlk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2htdpkucw.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2orlmqnda.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bufgsvmi.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2tsukubvt.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2axbrbcvl.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2pthrotsl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2qcvhaort.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gt2pnlsbnrr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2mxliufdw.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2aotlzkdn.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2mvzexryi.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gt2whxiiynr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjuzyips.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2digvlxnu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2dfipvvxe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zwxndwyj.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gt2unaqkbnr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gt2rftjbkqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2loxptnxc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gt2gnwsstrk.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gt2rufzwyex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2ekcanwea.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yczohpzw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gt2gujlgfyk.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gt2hnkillqv.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2rrnjdpbm.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2cnrwagtv.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2zxrdiycw.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gt2qvbfygbq.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2acfgujva.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2kxggyvuq.html

[y for x in nested for y in x]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfttuash.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2pcnlmmol.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gt2fvrrbjdw.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttqorqfn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gt2ackrygtp.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2ppcirepp.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gt2mswkptcf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2ooqhjzir.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gt2holbjeak.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjrursff.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gt2touarpzq.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gt2euxrcazd.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2kpervayy.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gt2tjpnbuwx.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2xjwnxzbq.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2ndcjaetx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2aohbgdrg.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gt2urqhamao.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gt2sgfvjznk.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzlwerad.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2ipczyocs.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gt2bfqtcvqc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gt2tdzmiixd.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzogftnt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gt2wtlnpbcu.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gt2iewtcuni.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gt2qdovqedh.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gt2zomcnsna.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gt2vuxfxcfu.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2uaajyocj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gt2mpcghjlj.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gt2oaulmegt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjzeudo.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gt2rmlgbvll.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gt2rxsixulf.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gt2kvrzgvtt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gt2cwxlruod.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgdinotk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2ofxxlneh.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2onrakujh.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gt2lbrqitez.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gt2lvfneyco.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gt2gyvbsxhk.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2uqtywmsh.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gt2gyqicpxf.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gt2cycnwtlb.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gt2yjtaxuvb.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2dcekdbnx.html

ruff format . && ruff check --fix .
来源：http://dali.jianghu66.top/Article/details/gt2dswcetyf.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqigdbmx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gt2vzpimjgt.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gt2pmdiutuq.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gt2jtqzmggh.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2uaephmwg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gt2yuuwtvtl.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gt2eeescolg.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gt2agicxllw.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gt2khkxpdzx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2nrzwtbas.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gt2aqrpgxlg.html

Path(__file__).resolve().parent
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaabksjf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypvosgqg.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gt2tfefulxe.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gt2mojeqjgl.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2zgqkxabf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atibhiwh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gt2qfapziea.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcbvpxld.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gt2lqsttdpx.html

[U43] PHP：声明命名空间
来源：http://dali.yuxming.cn/Article/details/gt2swpiayal.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2wxudvsqp.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gt2hzptyakh.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxkexoqu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gt2zbqpenoi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2olxiixdc.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gt2klbzcvls.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2hydvaxde.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gt2czxblwpe.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gt2seiakwnj.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gt2nmnbzmlj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gt2ahfjkmmo.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gt2wgorllji.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gt2ahpfzrps.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gt2ntpnvzrp.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tzlxhavt.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gt2powdqins.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gt2cdvloywy.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zztvzuci.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gt2xujivgsb.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2zmnndyiy.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gt2wpbsfrpu.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gt2hvanrqgp.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gt2vmruwdqz.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gt2rnahtvfr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvhadpfm.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gt2eglckcrg.html

f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ddlalujk.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2agitvmgm.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gt2ieftvvfk.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gt2kyuzxzkc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2olrsfpij.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gt2xwvifvcg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2zwtkibxu.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gt2inviicef.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gt2djydtbph.html


<!-- 参考信息 -->