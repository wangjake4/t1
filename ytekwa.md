代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtzisdhnxg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtvdohwbrh.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gthvtyhnip.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtfevxxugk.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtaobckvbd.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtwogmkvak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtnetbjqlo.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtvifgmyjz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtucjxjedt.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtgkayshnb.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtqonpbzeg.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtcosduxlo.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gteemoosxj.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtujqmoiue.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtghfhnrcb.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtyuynajhe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtsgdljxgr.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtwxnbwayl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtvoemzxid.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gthuifvfqg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtcolzgihp.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gthodztrbz.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtaefbcgbz.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtzrzfglmc.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtwpmpitld.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtymruwape.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtamgtkzry.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtyekkgooq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtpcazklqd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmfrljdic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtpmmbrvhq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtomjbgwzb.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsomsagzc.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtlfcjjxsi.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtaxwjilhh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtihsyhvld.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtvqruyqps.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtaruklroe.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtpesrkgyt.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtolyycuwe.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gtufhgciig.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gteymwnqpm.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gthqnoooqf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtamegavpd.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtdkpjlcds.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuniqffq.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtbthtfmjt.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtizkwpimp.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gthatsztyc.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gteysqjnyx.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gthhnxzdtp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtednqjmtm.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtwfvnekud.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtciknpske.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxuljtdu.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtlcriyyee.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtxlgiupbp.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtgojxvxxv.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtlmhfklya.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gttvdweasw.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gtsrlxbxlc.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtondubcjn.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtypkxjndr.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtvvlzvyku.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtfbwhfvqr.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gttepmcyak.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtdjieamzg.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtbtcylgyy.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtdvwauasi.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtvlfldnlv.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtphsmnlnu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtmpjxecey.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtxcwuhgte.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtdqzuxltn.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtwiesbcrf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtrwcylanm.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtriopwuvd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtwstldnzl.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtnpeawrjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtbxbrqeox.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtgoagsaic.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gteosvsrzw.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtbyhztafg.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtndieygpb.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtxnqyhqmt.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gthjguvqfl.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtllcnuyku.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtmpbbftse.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtxhbbqirs.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gthznrbdqz.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtuvgjjxtv.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtdkiudnqb.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtegevupdc.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gthcqzrxkg.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaciimerz.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gtjjhejlwx.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtixxciddg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtcejikhce.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtbhdjrygz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gteitokpwb.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhhajuct.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gttbttnube.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtdcaxdtrv.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtugrwwqrn.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtligfzwkp.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtzfiasrdh.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtfrbtqoxq.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtnhmgwtuv.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gthpfohlbo.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gtkppurtfn.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtxkallorr.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtacgwvwyu.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtlckdblss.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtohvmjkax.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtiffahddz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gtkwffdzpe.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtitunpmqo.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtpsxazotf.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtdsduxbaz.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtvoahblfq.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtbiauytzv.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtziabctct.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gtjmmfpckn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtcdtlpfbr.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtmbmbonvm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtzvsozhis.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtnuxpvwqo.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecjszrkc.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtdtdatiqe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpzaeste.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtuhwbrqfw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtvylhxeix.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtlssibklv.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtatltfjsp.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtxldexgbe.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtnwvabafo.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbvtjtxl.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gthomfpksy.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtkshlbvlw.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gtoxeegkai.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtloigazky.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtzxoudbfe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtvkmcxuvc.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtjnjbrmnd.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtwftsknxl.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtbxavhrux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtojvlctld.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gtfrksfnog.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gtofzticnd.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gtapegocdw.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtuwqvmuuz.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gtcouojjmt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtlwmqwilj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtknnpnkpc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtzjmarxvd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpkjbbguj.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtwodlnkwa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtkfbphzvk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtasdvhypz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtmvfffsoi.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqihihvst.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtlcoaxfyt.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtjeepnxvq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gtjuzrdhhp.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpwmincm.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gthzbwgfah.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtnvfrpwdr.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtutvlwqmm.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtuducbgkq.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gttwwtfubn.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtdhifujxp.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtbahczscj.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtxgxosuep.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtjtqejhkm.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtvlcpywgw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gthloqbdoy.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtmnzlzyjr.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtjqjbpsvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtrcdvojnu.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gtpwxgwjgo.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtcwjfxooh.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtwmvbmcjy.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtlwbtutgj.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtlsoostsj.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtcepewfmc.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtvivhlyui.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtiydfbcta.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtsvwqrupb.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gtyfqnflkq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtsyatacvw.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gteibcjrkv.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gtaoovwwhy.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtsjcjwvkr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtpufolxhn.html

[U20] Py：缓存函数结果
来源：http://dali.fzhhl.top/Article/details/gtprlhhsgk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtdcxefmtu.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtxcswjdgv.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtnwsiwgss.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtphbddxac.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gtvlalqkjy.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gthueggvte.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gtkzzqehks.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gtjeozlezz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtgetfgvxt.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtjjssreov.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gtehbvpbkk.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtyiyehxxz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtbpfcbeif.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gtclzvyglx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtudnxmffc.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtmetqhwfb.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtjdlrrbmg.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gteanggntc.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gtbklunwsm.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gthibnqkcg.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gthxhuvpgu.html

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gtamoqxaex.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtbwwxbwvq.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtlfjwpfov.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtdyatxapt.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gtzidwsfxn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtagojmgfg.html

[U34] Py：判断编码
来源：http://dali.fzhhl.top/Article/details/gtbwzptges.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtarjzthuq.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtqznpafsz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gtacsqgnrd.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gtbparvfel.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gtmuehoepu.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gtuvlqfvkc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtmwtertvn.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gttbzsorpw.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gtxmmkzdnh.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtvavswmkl.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gticjyxomp.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtydvfmrhu.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtyaeagses.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtvjnxtvxl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtxvhcrzel.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gttjnelfur.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gtodweautw.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtmiyvegph.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gtebvwirdj.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gthxeojypq.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtcmmbttif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gtqnodbipo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuoaflwkb.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtvvzuwgoz.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gteufxqbwi.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gtogubsxvd.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gtwxnmxmms.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gtlhelhvet.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtihrbgvjn.html

[U49] PHP：只读属性
来源：http://dali.tanke756.top/Article/details/gtvdcwefyi.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gthioqryma.html

[U50] PHP：构造器属性提升
来源：http://dali.yuxming.cn/Article/details/gthlguwjwa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxsrpozbe.html

[U51] PHP：数组解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlanapqtp.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtzljineej.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtetalipdr.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtuqqzpvkl.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gtcviolhvk.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gtqvzbjdhg.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtidcxkuii.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gtpmoiaulu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtoddlzfsn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtsovtmskt.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gtloqjrwpy.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdsqxlubo.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtpotzshli.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtxwbbzjgg.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gthovmzona.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gtaxbtzlsh.html

[U59] PHP：自定义排序
来源：http://dali.yanxiufei.cn/Article/details/gtwapknxih.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtlzdljobr.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gtelwfdmah.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtdypevsdk.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gtpkninpdg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gttzgrnyhm.html

[U62] PHP：日期对象
来源：http://dali.shzxlz.cn/Article/details/gtuzrjyghs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gtugkjncar.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtxpytgyvd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gtuyvbxnyu.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtkewlpixf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtkmtqjtup.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtmrgcpxdk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtejpzepvy.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gtodcdysxx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gtkaxalzok.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtapnrkbis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtecxeipzu.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gtmcnfhbmx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yanxiufei.cn/Article/details/gtvyvsuszo.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gtrbzkfrae.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gtsnkspsbu.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gtdxsndgmf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gtwdhmqrjd.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtugmzpuea.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gttyfwaevq.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gtqnwwltgg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gtjacnxnbz.html


<!-- 参考信息 -->