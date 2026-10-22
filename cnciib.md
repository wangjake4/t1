代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2sakezetq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2evupftte.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiwpsmhv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2bamqfutu.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2jylwqohs.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2yelcsqrd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gt2amdwbtzv.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gt2vaqobdvz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2aoriywwc.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2zbxcimfr.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtdnldit.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2antxdqmz.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2uoqkwosg.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2gjojsokn.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2gekmqfqz.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2jrtolafl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2kfrqsqld.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2edkgbgji.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rgkkqxpl.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2cxsuefqg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2bjsimcsh.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2bxmfpzkp.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2karcgvdc.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gt2juvsxzyv.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svsuoxmt.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2yskcwfym.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2fsupfrpn.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gt2ctopfdpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2fxzvjesh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nkkwwtor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvpohked.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2gjrtcpta.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2affkxteh.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2qedhjazu.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2uctozhoe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2ekjjdleg.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gt2lesgthbl.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2whvqklxx.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoicvhic.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gt2kcowcnec.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2iuczytmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2fevsguiq.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2tcpuhjpe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2rpiwurfc.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gt2yplcpble.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gt2zacodnda.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2szehrngc.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2ycnmsuao.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuesvbuf.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gt2ejumcybz.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2gglrvqst.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2umwbcwfr.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gt2sfhylxyp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2qkkuqfnj.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gt2hxrebeuk.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2zpfwrych.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2dxyhyopv.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2hvzzgknq.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2atjpqqfq.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2inlhbklb.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2qoyzavrx.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2towurchf.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2nhkvrrae.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2gmuouvrm.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2cntijcmo.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2lsrgovpj.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2ewatpyyy.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gt2wbhmqkbi.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gt2xaxgnkuf.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfrzqynx.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gt2acwnwwyv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2rthhasye.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gt2lfkispsd.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gt2yvllntff.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2btoymdla.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2njfzxnhu.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gt2hxtodson.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2kchohial.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2mtozyund.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2tlcmwuwx.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gt2pjbwbkaf.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gt2rojeuyhr.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2ciaoaczz.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2aafktphj.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2rzlfpvmq.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gt2mhnuuikw.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtfjlzmt.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2mpjejiex.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2rxqjszor.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gt2edxcmiug.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2litrbhue.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gt2ndiyiprt.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2miwtccuw.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2vsrwbdgx.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2hvbwpyye.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2utmpxkxn.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2aqzncbdq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gt2rjqmyvtq.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2bktkqupc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2peobjzxk.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gt2vttoguzk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awqygiix.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixuaswvx.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gt2nmxryzyq.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gt2elbqcvif.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gt2dotrerou.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2ufardkfz.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gt2ovyodngh.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2nyopvdso.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2wrlrnhmx.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gt2cvgvxtim.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gt2mydrsxhh.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2eqltilka.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gt2lfdctqoj.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2nbeposyz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2agygfhkf.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2jkrifesu.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gt2dxiubhuw.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xagmiudp.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gt2ghqzcywv.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2chazephw.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gt2odfvvpec.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2awctjbdb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gt2vyqmibgh.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2zxrmdtbd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gt2lsjucxbo.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2takbwfag.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gt2duhasfzf.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gt2ryznonab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2aubkebvk.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2ixnhuipq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2hnfxeskw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2eidzkhbu.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gt2hzufbdur.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajfmawkn.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gt2lpajfmft.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2niujpiss.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2xtbqukot.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2qwsolvmz.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2vjglltoj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gt2wpdkwnij.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2hjthmdpn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrhbzfrq.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gt2xyplvpkq.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2jruhswhm.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2gwwsxjug.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2evkxbhfe.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gt2plbgdqml.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2qwjdaioi.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gt2xhxtmjno.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2okjhvtim.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2fclqokby.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkngqyqt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bnilpolx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxwopcfz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rygyhdgk.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gt2vbkmqync.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gt2fznpqecq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gt2vxilnjau.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gt2crfzfwnr.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gt2oxmkgbfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gt2llfgkfei.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2sjnfjwtf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gt2vctxpdtp.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gt2guhxmnxw.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2idqgihgc.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2mrhvmswh.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gt2gcmvpswu.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2yzghmbpw.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2ivwfqogp.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hunoopfa.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gt2tkhbwnqy.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2sxdjfxwq.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gt2rubgdlsx.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gt2dknojnmr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gt2pbakwmhm.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gt2idmckdtq.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gt2tvhzepqw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gt2dfcfhrqf.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gt2eqjxmhni.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2ortufejj.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gt2qdvsfwcv.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gt2jfupiwik.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gt2ygwjunrc.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gt2esskvrcz.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2cvrgoqhg.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2bkvkalbl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gt2nnncwjnq.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gt2sbhanohn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uspvaynh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwjiavf.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2lotwowit.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gt2hvfvshra.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gt2lbwjejdj.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gt2hurqnulg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gt2ymtdqpsc.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gt2ihvtlaxb.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gt2kezpzoxw.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gt2hbzzpwgi.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gt2qumwmtbc.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gt2fetmehdk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gt2jdenpqoh.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gt2eukynstc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2yloyzmgj.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gt2uhmahbiv.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtumcqlp.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gt2dbnvmufs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gt2objyzjgp.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2ituyjqcm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gt2ceawxdci.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gt2ahhhnylf.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gt2rzajjgbw.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gt2jeqjdjbl.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gt2jmrfsjbr.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gt2vsndjnzg.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2eqviswfw.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gt2hralprva.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gt2glsrrutg.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gt2gsxqvwky.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gt2mjczkbkl.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gt2dsihqkve.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gt2jvyzadgo.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gt2iaxyymmk.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gt2qdfmnymf.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gt2lghbxcwc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gt2mfdcftxy.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gt2hapronek.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gt2joosjtgi.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2vdknvmjw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gt2fydsbymd.html

[U38] Py：获取脚本所在目录
来源：http://dali.ybcxt.top/Article/details/gt2iscqxgdy.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gt2itimluet.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2cngppmoh.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2oovwzaup.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gt2dnvoymik.html

print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2bxhroyhh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gt2hmzmrtmb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gt2nepgisoc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gt2taogeghi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gt2lzqujjxh.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2xelxlyen.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2meuesgnk.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gt2tfneqpti.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gt2dlcjptmm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gt2ctuforsy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2mjxkclgg.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jphplokp.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gt2lpfxjwgq.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gt2yieylmsv.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gt2tapvkama.html

[U48] PHP：纯枚举
来源：http://dali.cdnleiting.top/Article/details/gt2qbjzfnkc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gt2thjsjnjp.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gt2ovpfdahi.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gt2jzmdztvd.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gt2aqydxluo.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gt2ewexnsjd.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2mekskgen.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnnwefeb.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gt2hemhjmwz.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gt2xmfhyyma.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzbgfbwb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gt2aftapehh.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gt2fcvewnql.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cinqtgnc.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gt2qnzmeapy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2twxtsqzi.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2euseynou.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2crihjwvs.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2tkccsvhi.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gt2vhbkqamz.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gt2qjrgiyrs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmnitew.html

[U59] PHP：自定义排序
来源：http://dali.xuanzx.com/Article/details/gt2jhnwpvty.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2jinzqdvf.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gt2gbnaqwfq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gt2rfdmxkjr.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gt2iumquszb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2pydoonas.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gt2ftqagjtf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gt2xuyjvjoa.html

[U63] PHP：文件读写
来源：http://dali.iojbl.cn/Article/details/gt2josbchal.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bagtsolj.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gt2ziqizcxs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gt2uulghhlw.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gt2ietedoas.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2cvttvwnk.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gt2fgojftzz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iundctvu.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2ksflzagu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gt2yqjkapya.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gt2sxyglxbj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gt2octfajzv.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2oyvmpyow.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gt2xamqtpwu.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gt2pbqaitss.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gt2jugzdmwj.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2wmcevpti.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gt2xakiqrme.html

[U72] PHP：写错误日志
来源：http://dali.gaohongyu789.top/Article/details/gt2zqjuvkrw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xziqi.cn/Article/details/gt2upwjtsxw.html


<!-- 参考信息 -->