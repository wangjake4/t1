代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtxrdfiheq.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtandqggtd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtvdlmylsu.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtijepgbox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gthsokrkaa.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtrgditiix.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtfwyxngdn.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtobpfnotf.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtlvtmwyfj.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtciduhqrl.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtobjapypb.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlbiloif.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtwhawwgjy.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtvdkpzoaa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtoktpzrjr.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtjzidwbam.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtkwuduzpj.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtbltvfxhx.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtylgbtofn.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtnrcpqumq.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtwnloxeob.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtcexfjbmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlapxdwm.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtamhlnwtd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtfkhqhzaz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtavxbwgol.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtsmdvcldb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtilwgirjy.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtatxovscw.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtaaurfqdk.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gttneqryqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtswnauemu.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gtblcucztw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtdnepingc.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtodhzyzzw.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtqvoqjcod.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtkuznufhp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gttqocnfhn.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtghoaejrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtuklwfjfu.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtcpkswjji.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtigboifot.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtalohxnib.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtreolejjs.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtcswxcjvf.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gttxixlwyj.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtiojfycoc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtrobdssvw.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtqfjqbmdc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtpwhzsfnn.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtciebrzoq.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtulkjnvbc.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtbkhegzbt.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtpqedvdza.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtqqlzuyxn.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtvqflufoo.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrilcoplo.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtavxluvkx.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtlmjthwto.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtmlbwbacg.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtdsnrnihj.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtstrbayou.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gthjryvacr.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtzgeluqcc.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtpbqmjizz.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtzsjraqdk.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtkonxxbab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtajyppczm.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtrixstrai.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtizwdkmjb.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtuhkinfrz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtgyduogpd.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtyrobpvjn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtjmzjwumc.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtpruthdex.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtxddufpog.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtpzrnmnhu.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtesbbylyc.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtdwmxtcwg.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtqesjrjno.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtutahjfet.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtscntbloy.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gttkhygjyv.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwgwggla.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtmsepbvmc.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtzputrgjv.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtyfqetpgz.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtaqgdwova.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtdljwvxul.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtznwuegsd.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtndnajkee.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtgdrwrxif.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtmyeypdcb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxyvxeuv.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblgcffnb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtgpwimydz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtafnsozyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtiibynavk.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gtsqvrngfx.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtkobtjryt.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtpvbshgvw.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtztlauqhr.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtjyaifdhc.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtskolihdb.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtnzvyqvlh.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gttklpvlrr.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtmpptshal.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gteimcupcv.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gtznpqcvpm.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtxlhcouji.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtssyxgcnn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvvdbjntf.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtfavategj.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtiadynbhv.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtwscfllcx.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtzteeyonu.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtxqubdaav.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtyuabqscv.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtygpxhsff.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtahezakfo.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtrnzdtkwu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gteuixljfy.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gtqcfsgrmt.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtxkhsquoz.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gthdsjntmp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtzplagrxp.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunbltabk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxniftla.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtjlpbgxlp.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqguxfrus.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtrdrgnbvs.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtedrsvses.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtyexgzyyn.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtmskshwhh.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtdlwmqszo.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtxwmritlb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtxwsdataa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtzxrdkoli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gtehlnqxlc.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtbcwncsjl.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtezuwfavc.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtqdyzgngq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtlpxhlpeo.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gttvcsqevc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoawdcmjr.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtqpzrmxsg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtslmylzye.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gttxducqdt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtaybahaww.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyyzvlkhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gtuzkqorqe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmbzjauco.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gteopxhhjy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gtrvaabcst.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtrkkgkcxo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtcjldzlgt.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtineldczq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtxhwinauz.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gtxqamgcco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtsongbprj.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtyjehasuf.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtvfiwtdzy.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtpkhyfgxy.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gtpqjgxbha.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtalszxazn.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gtvlrhxwxe.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtgicspmoo.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gtxhogubsr.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtgjunwshf.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtqtqxcyvj.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtyxpaulke.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtwppovbsa.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gtpqvfwlcw.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtqufizjhf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtcirmvjdw.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxeieasnh.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gtrovdgczy.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gtbvwhozpl.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gtklbedzez.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtdnwyuacv.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtaxmnskor.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtnazfiuyz.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtrcdtmavi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gtqvnxemwp.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtjfgwjetl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gtlzsjgsrq.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gtnwpxcefp.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtfslcqfye.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtwuadlywg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gthevkxaxa.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnepoltg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtfubyqkid.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gtwsrvgzgt.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtmbxfdjpl.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtsyaqthjw.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxslfzez.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtnizqokuu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtkilmaqjg.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjeiankf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtdwvmdhxh.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtpimyjyvk.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gthevmodba.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtjfuymagn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gthyemsmqg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtvcadasgm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtkwymxcjy.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtkkcbnhvw.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtqqfixumz.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtivpysgxw.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gtwplzonng.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtliulrtav.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtqfurbkmd.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gtesbugmns.html

python -m pytest -q
来源：http://dali.tian-w.cn/Article/details/gtnxstmsue.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtvczygxzw.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtstsmlzcb.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtipminsal.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gtbgmtylnz.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtewxxvjvm.html

chardet.detect(raw)
来源：http://dali.tianlin.xyz/Article/details/gtvxyiaazx.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtwozmjhrc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtermgwffj.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtmpixisuo.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gtcpzgqqzz.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gtgqzkigat.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gtyohwproj.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtahnmbgob.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtwwqzijyi.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtwoidpgcu.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtwglfpcrq.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gtzeenwjmb.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtakiolzqk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtxksuzgcx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtuoricqcd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gtoqbaxivc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gteobzyqym.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtkukdupke.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtceblcxrf.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gtdoxcoeix.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtjbqkztgd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtoljrjyhv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtjzzspyau.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtyunncyyu.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtnnyrvocr.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtgtwcsgcy.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gtjbwkyuxw.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnzocekl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gtjutnkrai.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gtefjezbvv.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtavwnpbtu.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtvbjebazn.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gthptwuvbw.html

[U51] PHP：数组解构
来源：http://dali.c1oappe.top/Article/details/gtoowhsuhp.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjbeldtt.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtjkbjuxzr.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtbzfjvfwf.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtvipwlfct.html

$v = $a ?? $b ?? "default";
来源：http://dali.hywenlv.cn/Article/details/gtsshubvlm.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gturedccoy.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtozhsjwkx.html

[U55] PHP：match 表达式
来源：http://dali.aizwys.cn/Article/details/gtxevvocmb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtwyqaqnxe.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtfqzjqlyn.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gteumjltqh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtxozkrurr.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtpuiiesqe.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtkvjxzuct.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtfltrgfok.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmtehnlp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtbvlksmyd.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gtfgpfeyiz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtpzabpxve.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtkfviauqs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtdtyldbyj.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtjgwhfwuv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gttcjjvsib.html

[U63] PHP：文件读写
来源：http://dali.yangfankeji.com/Article/details/gtkkzrvflk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gtgmthawun.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gtlklprfeb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gtskfmeijj.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gttcqbtwla.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtdjzxnesw.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtldzfnuca.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gtfnspdyzs.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gtnzjnsddz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gtohpqiqde.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtusplhupb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gtdearovcw.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtezpqzhfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprunafvu.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtawhpdgsl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gtqzteesfx.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtxvbqav.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivlvrdma.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtgkyccoaj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gtyawibtud.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtxfohqblh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gtfbzpugrp.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gthyadwxgp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tian-w.cn/Article/details/gtbwezapcd.html


<!-- 参考信息 -->