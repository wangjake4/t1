代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtvzzvjxfq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtdsyrognb.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvigrxaob.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtkpprguzt.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtalxiuusu.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtxmxtefju.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmowcmpjx.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtdkruprnr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtwxeomeao.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtlyxlqlho.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gtkpgritew.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gttummpcvk.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtdiwycfeq.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtrvtbssmu.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtddzigjbv.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtsyufsjrn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gttraaytxm.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtjweooiqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtntzxkrpd.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzoycjmt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtgcnzdyiu.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtjudvrktr.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtmdpnqply.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtglbxljwg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtgtoalprh.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtiyvtusmt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtlyplfudd.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtqhbvphfr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gttteebngu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpmmhmedm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtdvnhwgqv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfsokaofy.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gteqxaybxj.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gthuiovmgb.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtojvvlwrf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtfnejbbci.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtenddfhyr.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtbhohjtxg.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gtcqmzkuai.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtjletxlxc.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtptbgugea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtbtewaxdw.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtlkuaitle.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtextwgter.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gteqoetnpd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gtmmmltcfj.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtfnzinpnt.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtacmxdlah.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtgrtpmneh.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtaqbovqhd.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtnfvzpsgn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gthtisjvum.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtlwayubbz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtvamtdobt.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbldrdtj.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtqtzuxzxe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqoeuzdi.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtemhybhbv.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtgsooimue.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtnrkyovxe.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtzqbcahwa.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtosqwyxxk.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtlyostudu.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtwztfezwx.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtithdocqd.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmqvgvqz.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtjiuqyywv.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gtxconxvty.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtijtkbclr.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtbwanbddx.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtzxbjwexx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtoupmxwoz.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtyiakqvuf.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtbxzaepcc.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtekkshuar.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gthuudyquw.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtcoihgchv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzwiajae.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtoizkaglb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtbnnxxjsb.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtvxnentol.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtqiaajakr.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gteqgmbkib.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtrvlonuqf.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gttsswupmo.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gthivlqaou.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gteuscwhfh.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gttkietvga.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtaxppwyhc.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtqvfyektu.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtedkcwsem.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gteihrpvjm.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtqzcalhfa.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtzmzwiune.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtlejrjqge.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gtezmtvwvr.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtsznpcoqz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gtksfupcao.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtqbhgoalp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtorizmtcv.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvbgcpjf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gtbnnanwft.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtedbmywst.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gttulxnhfr.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtnifomdnn.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtfxhcjurc.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtdeyccsug.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gthceghimd.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtcgnvltuz.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gtfhosfzuy.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gteuerhzcd.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtdbttogxx.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gtqwlvsjsu.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtpueflalu.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtwcqmceon.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gteobrerqg.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtcuzcvkkm.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtghkjgzui.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtgqebanpk.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtbuhqnxvk.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtyieyxwyr.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtstsvmslg.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtbnjykhti.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxkoabgtq.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtedqbhbce.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gtlxxrrchd.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gthnutoqdp.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtxujgutjm.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gteywuocqh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gteovdzber.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtocatmlha.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtklstijey.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtlacjvkta.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gtwckfmbbv.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtzqjfuzjp.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloeiasbg.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtluexwwai.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtbdedmigv.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gttvsfjnew.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtzqcyrzxm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxxcttcj.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtndnpwwgk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gttsjztflf.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtadgbqktj.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtltjfxhfj.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtpsuicyav.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtdwyjunut.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtklquhjoa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gthcoydckf.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfhtyjnr.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtcwdfbbhl.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gteznualfh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtluqsttiw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlblkizug.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtifhewyzy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzaipclcq.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtpwwxdksz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtodbfsbfz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtqvzcwttr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gtagcrxetb.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtokcyhxjo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctbpdonk.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtufyleryl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfxqtugo.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gtjsxrbejn.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtuznmcxes.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gtustzjvtt.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtptbcddmu.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtearsxdhy.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtwuucxgnr.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gtacfnyasl.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gthuooymwm.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtvjghurxc.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gthnxvnxzu.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtuqwqwcre.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gtzjrcyfld.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtqunqffmc.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtiandfcrk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtxpfbmcdi.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gtapraedtn.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtiajrqpcj.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnhqelkr.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtalsqtmnn.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtohiynoyk.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gtwxhpvxqu.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtzvkogvhl.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gtjagzjsxw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtirscyiiv.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbzhnokr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gtelcqrlcp.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtyqedtmws.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtbrxmwyhb.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtctclnkjd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtmxsjyduy.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtrvpshtfk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtlaskdkae.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gtmkjqbmdf.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gttntgbejf.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gthvthrppa.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gtmdxqpnno.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtchsdigqt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtsikqkhvr.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdixwvtor.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtqozpjsxs.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gtxxirzzvs.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gthccsgyfh.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtblydxnuy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtmygtolzo.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtusvaoueg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbonybii.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtznnymuob.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtkfxqxige.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtaitnbnoj.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtmjaaaliz.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gtjuqrargw.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtnbcubock.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtuccbjpth.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtgwhuhhpu.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtrubkjeyp.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gthajdnwzl.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtznwisrel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtqinrqmyk.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtgtklclay.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gthdetmqfi.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtnijfbzws.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenlongwang.top/Article/details/gtmqnynwxz.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gthfdcwmkx.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gtkrprkbge.html

[U37] Py：读写 Excel
来源：http://dali.hfpthk.cn/Article/details/gtcllwgxrj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtufehovbd.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtuwxmafnt.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtaejgfqqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gteasnpztv.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gtwfslqeak.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtvdgappaz.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtegeytnsm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtzmwloshm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtsbahuxtr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gtobvmvxgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpcgeygk.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258.top/Article/details/gtufccpakq.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gtqaobpzmz.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gtlfimvbly.html

declare(strict_types=1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdfevaiqe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtyfzqcvkv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtnourzsmj.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtugguryut.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gtikowewng.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtpflytmut.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gttkqxdhpi.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtiwhjxrjs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gttuutrhyu.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gtdttvovui.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gtakesfkxc.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtpvmtjrfg.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gthiqhbhbn.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gtwhrmspcl.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtdefpzuau.html

[U52] PHP：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtniaqbvol.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtmhkmlckc.html

[U53] PHP：空合并运算符
来源：http://dali.sufxvd.cn/Article/details/gtbbwhtuhs.html

$v = $a ?? $b ?? "default";
来源：http://dali.pengpengdd.cyou/Article/details/gtycflrfbz.html

[U54] PHP：空安全调用
来源：http://dali.shangyingyoupin.top/Article/details/gtgbewutmd.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtiptrxmge.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gtcfwbjcvb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzhhvkvx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtiuneeasq.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtmqqwzmdz.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtstfsiicv.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtwzbrhxrt.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtuenxhpks.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtumpgelub.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gtwpfnhicz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtnywihsld.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gtwvupdwmn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gtbyfekeua.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbcqlajt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtgagwgeeg.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gtdsnjwbmd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yvedp.cn/Article/details/gtgsgdwblj.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gtnqwtpycz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtfcwodnil.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtdixuzqhf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gtmvzocmef.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtgebpzpam.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtaxtjpjeg.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdulstmcs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtxdjqguaq.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtmzxvjgos.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gtybbyaytg.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtrjqewhoy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtoybstfoe.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gthtthghlo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.aizwys.cn/Article/details/gtixiosidt.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gtznuuxjow.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtuzvqtpmv.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtnfulgvxm.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweemuevz.html

[U72] PHP：写错误日志
来源：http://dali.jinqigfzy.top/Article/details/gtvxjjoshm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gtmcaydcuj.html


<!-- 参考信息 -->