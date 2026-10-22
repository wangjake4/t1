代发 wailian999

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtfkkpcjdz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtyeyycazy.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtoqqdrabb.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtgfzfnaou.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtjbuaodgt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtanjfkpib.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtnoafekcu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtqgeisbyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtfmbncaqh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtfporjhhe.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzogozqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtncrgxosa.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtqxtakzdw.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtfauqflqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtuaigixzb.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtogdmhjdi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtyqfawsxj.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtgeaggmgr.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtoedoxjbi.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtxzscnzdx.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtlhxvszep.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtzgozrpky.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtdgoedyuk.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gttbdcehjo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtcfsfbwms.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtaavqagbv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtezvgburf.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtvnmgbrke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtyhrdpuew.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtqmwpbate.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtuhtwdbyt.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtqbzvcqdx.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gthexezhgp.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtsuyedubc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtgtcdstih.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtmvsuwtpi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtopqxrrhw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxbztetic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtjbdwecya.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtenxvrsce.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtwsobndaj.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtvoeantov.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gteqqatmnq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtcscsljss.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtakylptjt.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gthsegxvze.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtvainbfgm.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtrvrotoov.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajjrpijx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtzpnujilt.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtwihicnim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtaxnnhulw.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtgqqezjgx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtlmpccjcu.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtwxejyqfd.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtteckakyk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtrohgspaq.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtizgodqrk.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtbiqwthdn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gteebucsex.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtpnusyqjc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtdkukaury.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtrfdrrsbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtkqazepxd.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtohgeycyj.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtfohbnstt.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtrvwthzkr.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gthulkutwe.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtovyiybay.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtcnhflaud.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtmzkyegoy.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtxeydeyyb.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtwynwwaqy.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtdjhvdhco.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtpjbstrjf.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavwwqfba.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtpqumotjz.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gthjjvzzqm.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtuvtggeac.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtgnpurjvg.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtxjsccehx.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtjbjhittk.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtmryjztvh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtugkxzghh.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gttzhbvdss.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtoyjfpnor.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtrmtabqcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtnfikwljr.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtxypccbft.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtlcvyisuh.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gthrwoeezl.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtlhfntwyy.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtnsgqplhm.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtndjsbwfj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtwowllffo.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtcjyqydlz.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtwkezntrl.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtcbhsneut.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtbpyoptyy.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gtknhznakh.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrenqijww.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtmetatoyx.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gtavqmrsyi.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtnvvlftoq.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymjjgbjq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtgshxggjx.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzppnaiqn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtskjiapcm.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtruunpotc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gttpfnpoeb.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtxhonalca.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtzynnwwrv.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtcbtpoyoj.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtvqrwatgp.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtfjxayvuw.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtwxqfvlew.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtozbjbybi.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnxgnfbm.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtxkthpfse.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtjefrdusq.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtnltlszig.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtljvtkocb.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtgnhbizwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtznmonoqm.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gteevnfsyo.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtrpncvyrw.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtllvtiywc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvgszxicg.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gtvqcazmhq.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtppvlctql.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtbeydizfo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gtnlwjqduq.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gtxgetfcrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtadyycxfs.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gtuitnctfc.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gthiuhtstb.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtqvxtmxwz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtqppyjuch.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtooedfakp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtyoildumz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtafvadeal.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gtmjjcmtzf.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtuglrkgcu.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtkhmmpfbv.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtvelwragt.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtqbwoyevz.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtnxawthgi.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevoehpub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gtrsyeayrb.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtobmivqmq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtbasvidle.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gticuhzbiz.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtfltzcckf.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtuqvzvten.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gttpkqtavn.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtbzibeklj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtfilspbah.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtuhrofmgr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtlhbqmzkg.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtgvvehcpt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqgffzsi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsvuqsefq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtwofgfrkc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtoprqqeer.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtyfygmqfq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtzluiuyti.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gttegrgflj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtrqgdncec.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtlehawemo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtsqtppyej.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtnuqofgbx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gttcizluvz.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gtxakyvkof.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtwwkojqga.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtvcjqdkpr.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtfyrobkcc.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gtuksgythj.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtbzmgpidy.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxgxlfna.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gthpngvqyg.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtykszorgb.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtczmoessq.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtlzzqjgxz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtjwtttkqn.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtcvvxmpvs.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gtgnbtrczl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtazmubugf.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtvhoykwmu.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtsuusltlw.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gtdvwkltmn.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gtutehavqc.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtbgrexwwz.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtlxcfccko.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtaxhcserj.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtaefzgoop.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtamnmajgw.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtcepuwxrj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtyhlwywaz.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gtdlybssaa.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtexzyqske.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gticvxscix.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cqqwz.cn/Article/details/gtbapiajxp.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtvdrbpetw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtbwfkoaqy.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtsuxafhcd.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtbfiujtel.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gtfanardiw.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqpjcsju.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtkrmtmiwh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtqxogpmpm.html

[U24] Py：路径操作
来源：http://dali.ppjwa.cn/Article/details/gtgqqqvorp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtlftufgfd.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtuafzesnd.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtwefknjyo.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gtdzicmoxw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gtyqwbprvt.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtvqthsqzd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gtloohmyun.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtzklzdciv.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtosogryno.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsunbcemr.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gtkopfwqeg.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtdryhexkj.html

@dataclass(slots=True)
来源：http://dali.jiagoushi.top/Article/details/gttjfbfcxq.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtkxjvfzio.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqhyasse.html

[U32] Py：代码格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtrsygnggk.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtkxdezxcf.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtjywkplpx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gthozsoshz.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtosyyhngz.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtcyhulcuw.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtepbzlcvu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtmfnrctyv.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtvyptpcpp.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gthuxulkua.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtyqjxgidc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sxryk.cn/Article/details/gtlttpzqpf.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtxjwvtwqv.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gtkxsulsqw.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gttdhhdlic.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtrdrudcvi.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtxijylttw.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gthmhiobqp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gtxbosrweh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gtvskawacv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtksgnemfo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gtslmcppcb.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gtekopukap.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtamiexvsn.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtfcpfswoy.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtbqgleiec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtnsufogjv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtopojlykx.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtbqksomgv.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtokzurucr.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtjdeindnx.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtytsabign.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtuaylyymi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtpkwwyloc.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtqkqklysq.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gtzqrnfxll.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gtsnpkqdbw.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gthjdscsyq.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gtjpousibx.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtjvlwjjsr.html

[U52] PHP：箭头函数
来源：http://dali.yuxming.cn/Article/details/gtnqkwawwu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtduofisuk.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtcxaikpld.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gtpwjoyglm.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtofpkggpy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtdzxvghbi.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdobnbspz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtlnoensbw.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtpbufbllh.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtyhuoyiww.html

[U57] PHP：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtpvzxwrfx.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gtekosxznn.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gtclhqzufl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gthewdbryt.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gtrlsuwyzw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtyhibwvol.html

[U60] PHP：JSON 编解码
来源：http://dali.vqdsnc.cn/Article/details/gttseyibaq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtdjnonukh.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtzelxaupk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtlsfnfxiz.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gtgxvoxrsa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gtyzqqbrve.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gttsqduzwu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbwatxoi.html

[U64] PHP：目录遍历
来源：http://dali.sweek.top/Article/details/gtfsnogntu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.316326.xyz/Article/details/gtphmuuwbg.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gtvcjsqpli.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtqgyrcafl.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtkhnvxelo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtbpjmdzsx.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gthizdmuez.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhrutekx.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gtuvwezync.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gtcnunnpzi.html


<!-- 参考信息 -->