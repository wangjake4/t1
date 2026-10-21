代发 wailian999

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtyfcgyrii.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtspbxexjf.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtitjsimal.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gthvkevgfu.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtrarwemwv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtzehccyjz.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtshxxkquq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmbgzqiog.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtevbpsmyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gteopjoejg.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtqwgqpbsl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtoovmnuzm.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtftbzeula.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpnjgivv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtorqvirvi.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtsnasyqfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajsolcwc.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtafryrlkh.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtkgwzfzcp.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtbvxbjozm.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtqmskzbhz.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtdtitqxng.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtwhcmhwyh.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtzsuesroy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtvmmzpxyo.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtcgsyestf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjesevibj.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtxqtdzesb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtegmzsyoh.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtyixefwwg.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtcckorujm.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtpflbdieq.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtgrfbdgdd.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gttiecztle.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtjnmzsley.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtcysehusz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gthipvpclz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtetzcusqe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtbhudllvk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjiquenjn.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthpqdojvo.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtyfjgwyxt.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtfwikyrga.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gteiqtbffo.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtgvlxayzd.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gthkuspgtx.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtcqamhstx.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtsqkgrrds.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtxhnxsqpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtkvtgtkvh.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtmtljusfj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtyjzebali.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtrhvgxvph.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gttssfhaqf.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtcvfwkwlf.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtnqrmlfqt.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gthgevvort.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gtzjoqamxp.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtgziykqem.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtmqmiyndg.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtddscsjtw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gteucebmnd.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjrycsdv.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gthfyhfogr.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtfbmpbuqa.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtiahjexlz.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtvdvmsuct.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtbvdhlxcz.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtmashmhiy.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtdolacjnf.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtchqfyhky.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtwaceligd.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtebjnoksh.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtvjfqyibe.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtjnroeljs.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtmeciheqa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtribecgkj.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtlotzposa.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gtvzmxyuvi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gttyzekklx.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtkrkepwjd.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtceglgwor.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtlzmcxjzv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtwjiorpzl.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtibdghprz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtdtxztutt.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtayakfbhw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtouuvsuyz.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtpzsplsyd.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtxwdailca.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtmyrndzty.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtoooqygrk.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtphwiduhe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtizhpfiji.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtgzvjzlir.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtuibwlnzu.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gttsptyvdo.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gthmyvylnq.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtpijhuvyl.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtkpkvipzs.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtmtjehjgb.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtvlukbuvq.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtowagrpwv.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtissbaqgv.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gthzrdpmpj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtvvzezekq.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtbhxilkdg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtoyekuvnc.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtwztcpwqp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtqllzqoll.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtktireqsh.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtczihbsit.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtwnwpbced.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtewlnqtbj.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gtlaguards.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtosscejdg.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtusptbjkq.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtnmuweadd.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtyganzfzm.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtqripfpbu.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtppbyuhoy.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtidimhmne.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtkzrbdxnd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtyfvskpcq.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtqjerydpi.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gttrsvknwo.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gtqwjzomrk.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gtjhlgtaxz.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfmwlkhi.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtsxvpfcbb.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtdmiitoqo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtsjtccykf.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtwtznpdum.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtdsagbnlr.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtkigszcyn.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtomutthhm.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtsbixntgz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtutdbstmh.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwataonbr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtchktlvxm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtwccobvii.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtwszobepo.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtnvupgowa.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtrhtzpuwi.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtcdbpssmh.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtuotwcbgz.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtxfumadsl.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtcxusprqt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtnrigmljb.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gthmfzbdas.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtfuulhbhh.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtkhbduqab.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtjwkyehau.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gthwxpstau.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gttevecakp.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gtjoaaeiyq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtxlswuaph.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtguelvqrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtjanszhlw.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtpeqjgtew.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtftrdpull.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzfvrhvgi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtszeykwxq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnmzkvqkm.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtsaaxnqig.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtjryydlat.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtchdorwsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtgastldyu.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtdgqsckqe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtyhmvzwle.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtkhomqfec.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqefemgq.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtwgyxexvs.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtdydtatcc.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtnfwmdves.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gtazpfaeaq.html

[U07] Py：反转字典键值
来源：http://dali.svipenyu.cn/Article/details/gtvhbhgoij.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtzolqreuo.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtspwpcfhv.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtnayqyrxq.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnnklqzm.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrkyhwpm.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtqtphpqch.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gthvexnjlz.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gtfebgarfu.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtuuuhssfq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtvbronmib.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gtprqdolia.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtywcnvltw.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gtowgstgen.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtoiztrzmo.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtcxkrnirq.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gteanuiwhp.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtjtxroozr.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtlsknnqxu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtrwszdpny.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gtyujgupcb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtibwozpre.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtrpenknfs.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtsmjjtcol.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gthlirsixy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtnzebjekz.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gttsjxkrdo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gtymjxzrzv.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gthwpahnaf.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtfffafcvq.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gtivlgkvbw.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gtwhspvttj.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtwtdsccht.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtdysvykjl.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gteyyrtvdw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtgjnpjmqs.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtrvmsynjm.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gtchwmuudf.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gttukclmmi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtdyvuzyyt.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtvhbhrbhl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtuhwofqhh.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtahdzhcur.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtwsbkffkt.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gteglbtrpc.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtczulcidp.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtajxinqnc.html

@dataclass(slots=True)
来源：http://dali.yangfankeji.com/Article/details/gtbvuosynh.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gtppcelhlo.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtwjpencyf.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gtkujkcypm.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtnerevlhs.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtbzizonwn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtuybjsdpr.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtumpogedx.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtibfomcem.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoxifonm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gtaraxnedi.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gttawpthqb.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gtwmnwezbf.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gtmhbaqcsz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtkcxrgiqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtzygsdvfs.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gtzyxosyoq.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtbsjljjhm.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gtxyewjhao.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtkkqubyot.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtifuujtye.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gtxnhkurtc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gtxibzsorw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtzcjbuknu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gttbpaycgp.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtuhsuvcjb.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gthwevvuvc.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxsccbga.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtexxnlo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtrzfjyswz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdzkfnsa.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gthmvxlybg.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gtocidhxxq.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtbsehgila.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtnczppnaq.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gtbtbijqkq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gtzvixczru.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gttpsdvoka.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gtwrwoudce.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtkuptsaws.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gtsilexdxf.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtgzoprcla.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gtvnyzupnr.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtvtggjpqj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtitpxbgew.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtnciyjgug.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtqundiuyc.html

[U54] PHP：空安全调用
来源：http://dali.meibo888.top/Article/details/gtfrvmbqdh.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gtjesuuunk.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtcprjokfy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtymfohuta.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gtxgmaxjjo.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtjjobnsyt.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtmfvfekbs.html

"值: {$a}"
来源：http://dali.pengpengdd.cyou/Article/details/gtngxwaikf.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtfgszrenx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cqqwz.cn/Article/details/gtlauzpqun.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtheissudn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtgbdekbcw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gttuhpibeh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gtlqqfrbrt.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gtimczhonh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtbltbzcit.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtepbuzziy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gtuqbvafgj.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gtgbtkxtlk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkdencul.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtvjnuixvx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hammf.cn/Article/details/gtfsvsscfa.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtpfxletve.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtmeupyeyf.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gtkxmgicvt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258888.top/Article/details/gtngusryzv.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtptcrwetc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtulcybymb.html

[U68] PHP：PDO 连接
来源：http://dali.wangshuangyany.cn/Article/details/gtisjgonna.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtdezdawft.html


<!-- 参考信息 -->