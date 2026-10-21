代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtvwbiwvqa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtfjklfwkb.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtuijbfklz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtpgrwksca.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtzrhrnzhu.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtftuxskrp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gttaidjvnd.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtgybqboay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtbivzhgnw.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtkquwonki.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gthlfwufwl.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtovzrkicl.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtecqkooxq.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtuegagxfe.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtelsnsyzk.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtzrwlwrdy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtfzdywlhf.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtkjyirupf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtwxfzuasu.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtwxyyivfi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtifqvaryq.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gthqradagx.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtmxjnpwvi.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtkcankvry.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtydeimyjt.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtcdtrznwe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtajzhqulk.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtwohitioh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtcgzvpaia.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnmkxoiwa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtlzzzcyhp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwieeuvpv.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtjgabhaeo.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtsxdtzvyy.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtoeacqbkg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtreyrzdoo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtrqggsfal.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtnrhsxufm.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtffwqcxkt.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtktkrmjit.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtuvwgykdl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtgkysppwc.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtnpzcqayh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtqrqygklb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtuffbcmbi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtpbyypftv.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtuaxvolmx.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtnmqovcac.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtblmyckyq.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtzdyydnus.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtfwcitnmv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtbzyxlpvp.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjgeihn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtauynogvj.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtohqjhlzl.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gttgtnljxb.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtkzhtprcd.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtcfzisqvh.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtwpvbdxah.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvbtixbo.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanerikxh.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtcgevuxvx.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtjueiqspc.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtyqddjosy.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtudvmsarx.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtecwnsygl.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtxyaaruef.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtbbmyvesg.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gthydjauqs.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtxajuaaxr.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtghzxcqwe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtecjbtuam.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtpmajcsli.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtihxreouy.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gtbohyakfn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtgbjjbrit.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflbaeube.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtbrzyczsu.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtoencwfeb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtfjigtvwd.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gttemivkzf.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtrkvytgwu.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtcvdlyjsl.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtvuvpnnyz.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxaynhcj.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtmdrydhhg.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gthfqagfuv.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gtzvqqodxx.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtxzttzvch.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtvyelghwr.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gticiztnwi.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtncttewfv.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtcrispkie.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtoxaohajd.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtbmreixmy.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gtnnkhhdnq.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtbrgizcdj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtpfnytfwq.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtjsbdriuy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtfbssjozd.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtvghzkyvh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gttpwzaktl.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gthvyadztu.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtpuhybpgm.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtkevwsrpr.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtfbmyrrrg.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtestlpmff.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtzdzumghb.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtgwtopbum.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhklaokm.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtjnzqjgwq.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtyqydlwzd.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtjzwrnkfv.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtlscipwqr.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtttwlugzy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtcxjehokd.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxdgjjkm.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtjbyssjed.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtshhierqt.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtveteiaqt.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtmrokcnlh.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtfznyouxk.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtyxqvceet.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxgbcnod.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtwkbtpoat.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gthdklbgkr.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtzoqzsztq.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtzfkqjudy.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkrcukud.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtjwgrgxdd.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtrufdssan.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtfpbztfck.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtyaafqpvi.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtskfwzdwc.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtozsqcrri.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtacxumjwa.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtcpswapqq.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtqwcmepkn.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtdubqnurt.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtgriwhskx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtxwwnqufr.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtxsxorgwv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtzrsdeznh.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtlbvlzyic.html

case class User(name: String, age: Int)
来源：http://dali.daria6918.cn/Article/details/gtgimczbjp.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtevkfnvih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtwjlmycrd.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtoepljpuv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtvmvqbjmn.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtqhgxntcx.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtvnjqnldb.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtecujfqgf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtvugbeycr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtybkylava.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtcvcyjudd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtflrboipz.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtnrppgeby.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtsjeuvqww.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtdliuipcv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gtyolvoqjw.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gtstxbknet.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtcvnhqdyq.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtxcovdnwe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gttyxmwdqy.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtizpeuodq.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtghzkvbul.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gttayrovre.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gttgdeaigs.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtexnitxcp.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtjeooaqzx.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtgyklmqig.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtsqvxfqgi.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gttmbpugfz.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtumsxonxo.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gtvvouykiv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtdiybufew.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtvhaelwkj.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtckyxtral.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daxiang520.top/Article/details/gtwmzqzahc.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtjrnxyfyc.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtnphndjsa.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtltancsvd.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gttbbjyhqg.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcqlpfky.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtambrkqot.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtjojxrzvl.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtymevbqvj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gtevobeyta.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gticuvoavo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gthdplscko.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtttnccupb.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gttduwgcbt.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtwoyahsuh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtehswarcr.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtncplqojm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtbzknkpqx.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gtanaziazi.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gtwohxtkvf.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gtqbowvxdj.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gtrxvezzpi.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtjynpgcuk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtajftlxcl.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtjnxwtrxg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtobsgmvhn.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtetitbqko.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtaxyiexdp.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcrohkdr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtgcxhxbmw.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gtuiqowpbz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvytethrg.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlkwrfui.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtrqhyqkyt.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtczzkvofy.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtppupaukp.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtzukthwer.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gtkjkvhvcc.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtllwiowwz.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gthdgvmdio.html

[U32] Py：代码格式化
来源：http://dali.cheryme.top/Article/details/gtpgjrndtm.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gtcfprcovi.html

[U33] Py：打包发布
来源：http://dali.yongpay.top/Article/details/gtcjqxxgsl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtjcikgguc.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtntvyhtnw.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtfvbfrtyw.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtptskbuvg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtvugqhkud.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gtswzonhsl.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtmhuxsxtu.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gtjtjaeakx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtnksmsyim.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gthzxzkdxc.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtupyqvixn.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gtgittfgnt.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gtldapinyv.html

[U40] Py：打印到标准错误
来源：http://dali.tian-w.cn/Article/details/gtknyslifo.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtwznvnjpc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtdjltnvlz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtpopvtzsg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gtscnjvrpc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtvkujqhln.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtulavihwk.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtapoaqjar.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gtnmlapwpx.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtjmohxtie.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtcoyixpuq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtavdgekfv.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gthezfegty.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtbwjaalvs.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gteilmkmmz.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gtqjwfgykk.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtrzssrzan.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gttxjcmosd.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gtgfsctdsq.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtrqrgjshb.html

[U50] PHP：构造器属性提升
来源：http://dali.sxryk.cn/Article/details/gtvpuzsopg.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gtmzxgqevh.html

[U51] PHP：数组解构
来源：http://dali.xuanzx.com/Article/details/gtcaunlalz.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtsyeifsth.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gtjeuafzfg.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtkhifygzj.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtldjrkjiq.html

$v = $a ?? $b ?? "default";
来源：http://dali.nwbrower.top/Article/details/gtapznqxzi.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtyulornag.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtzewunbsa.html

[U55] PHP：match 表达式
来源：http://dali.gogol.net.cn/Article/details/gtrquckwjk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtdmbocuce.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gteyrtbqwx.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtgxovsfiz.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gthqngoijf.html

"值: {$a}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvargufyq.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtxxifdmwk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpvdzcihz.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gtwmdsjadq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtppkyyjai.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtmidatdku.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtjwurcqhe.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gtcqgwfqxi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrbwwqrp.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gtlwaxkact.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtzpggdhup.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtuecdmjas.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gtcgyumgrw.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gtqzpwseqh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gtwboxxtge.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtaykjqzkk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtpzvlsmdi.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtnrdljgzo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gtpzzkzxge.html

[U67] PHP：处理文件上传
来源：http://dali.hysaishi.cn/Article/details/gtedpvhybo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gtcxqfznzh.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtqmnfuzny.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gtitzesuvv.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258.top/Article/details/gtuprqikwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gtzmposwcz.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gtmzritiag.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gtuztbmpqy.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtzeajyyca.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnqzz.top/Article/details/gtelpdzqry.html

[U72] PHP：写错误日志
来源：http://dali.smart0.xyz/Article/details/gtwribdymw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhvkhiex.html


<!-- 参考信息 -->