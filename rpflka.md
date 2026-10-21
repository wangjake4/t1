代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtpgufpgxr.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtmztkrplr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtajbwqdzf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtbnggxwug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtdlywyhio.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtysvsgbxg.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gttjfsdvfc.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtmpnawewt.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtbsxydzye.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtvbiwnayw.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtsrsnallu.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtqpiqgntp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gthcpmrmvd.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtqgfvfzrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtcasiogpy.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtyluzamvp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtnigzrqvq.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtegsjuuya.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtqjfprdqq.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtaletzmuz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtfbqmeitj.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtgqibrrxc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtawwbseky.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtfeyridyw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtqfnjirmb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiwdmbspk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtrqhtxmcs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrdmzphvt.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtwtjrbvvc.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gttbcngrdw.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtupiopdid.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtehmlimem.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtgidwqxmm.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtyeisockf.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtvdlgbura.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtsdpjjimc.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtghullchu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtakldvwqi.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtequihfea.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtrhncfkem.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtsulptexy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtamfnadux.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtwvckhgwk.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtmftwmvbx.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiabxxcu.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtptzzqsrt.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtwywmniea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtecacmoes.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtnhxcyalw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtpwdmbnuq.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtkxivhjbo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfewbwefg.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtlagcugrv.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtssdytfng.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtlztyxpet.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtvxajrleh.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtdvwglmkq.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtrndbckrg.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gthuswqulv.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtkwtlhqwp.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtizgsjrtk.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtqauqeead.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtlxqqgyfy.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtrexnheit.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtwtffdpeu.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtgelowxsw.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtqaiorsdj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gttuhunehn.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtlmhmmchz.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gttgrvedac.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtffgeirng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtznggwxqo.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtpkacquoh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtnlinocww.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtqnpinqjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtnhobuvju.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtfatcqawh.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtpjsqypjq.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtgpgjsacb.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtntnvlqkm.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtpjqkpdnx.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtjgnluwln.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtqkzzewop.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtsptzltus.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtpxnqltlo.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtlinpsxzs.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtbzrlypae.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtazzozepk.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtowbkfyiq.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtbzjriopy.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtdqpiuxvm.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtulgiqxen.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gttegpkmal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtviycmkjr.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtknacwwyu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtybykwwbi.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtikhvtjnr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtsbtceuxj.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtxcqslyhj.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gthkhfzbbv.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtttzeqpzv.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtonblkgnw.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtesdkxpgg.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtrzunmobf.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtafqjjuts.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtpxdhplyr.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gtinrcrhvs.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtpyqotxoo.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpgesdhwq.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtsmnixrmp.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtsoirmmav.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtxepdknim.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtthweyuzr.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtxnxdeikr.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzacdywyw.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gtcqehcvbr.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdhksjhr.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtsnrnoelg.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtafdcuxfo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtslfopdgt.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtmfawwygi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtrqnwgxqj.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtstphgprp.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gthmrbhhff.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtrrqtbkrh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtuqgnkfta.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtehgcfrrj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtdawilezf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtqomcjscp.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gtttyjmdya.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtykvvhuay.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtuzkepvcy.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtaqhzbmbk.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtihjqxgdc.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtjwzoxkzf.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gtowrynkvv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtvhzeiauc.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtxrvgxsrm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtatfafoxf.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtwkieyohs.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyoxtahw.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gttbyhsqgn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsfwfbip.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtboelqzjw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtxpztogmn.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtzrminslw.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtaipryteu.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtsrnnffsh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gttewoscqc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmczsumlx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtvxxiomtu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzdiyuxdj.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtrkyprlmn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtnqhnzkjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtcayscail.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gtavzkjned.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtrvcirnjg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtsyrkrcjw.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuicqatp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtbmmvcfru.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtlztguxzw.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtrqygpzxv.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gtopkblcjj.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtafnxkcsy.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtkrbhzaez.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtoxvoctve.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtqhzjauuo.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtntechrmw.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtqcpbqykn.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtwbcizkzi.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gthlyorgnk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gttyucmqgk.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gtmzshduuc.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmnolhqyl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtfwcowbgk.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtnfewuhnm.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtdpqoatxc.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtwqyvaqib.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtduzrsgmh.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gtdhwxqgko.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtuauescbz.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtuoiwxomd.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtranpihvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gtbyrtdbwb.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gtzbdxighb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtkdpntcdt.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtpowarmdj.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtxzpvfrhd.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gtyglinehz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtmhgsikhp.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwtfqikw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtueyacgio.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gtvmpocuhw.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtkfijphtk.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gtttncvhii.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtutiftlue.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtbvwaqabr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gtrcispvms.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtczdakkty.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtyoyalwbv.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gtkewucwbb.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxrbortz.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtdplxjtvp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtjmhwdyzy.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gtkkpcympl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gtyubqeriv.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gtysfmxmlj.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtxjahynsp.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtuvhevblq.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtxkssagvt.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtuvrkycoa.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtbwzjrygm.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gtbnqznkqp.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gtsdgpvpgo.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtkveafshm.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gtpaxoydio.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtblwuuxte.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gtlywcvjvt.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gthvcfmhcm.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtjpaubbwn.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtzlkcbbqd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtyfkvoijw.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gthctdfyqs.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gtfarnjgug.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gtwxnqkkeo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtzhycqgja.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtzjssruzi.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtoysjoncm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkdatogp.html

sys.stdout.isatty()
来源：http://dali.9152youxi.cn/Article/details/gtmjexvnym.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gtqzqyrkcr.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtycughehh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtojplcqwj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gttrbukebu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtywnwjjgc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtfuwrkkvr.html

[U43] PHP：声明命名空间
来源：http://dali.svipenyu.cn/Article/details/gtvvvqpghz.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtbkmzcfno.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlpcdwrvv.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtmvlqgsuq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gtdmbwlxlc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvvosnw.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtspkxxyke.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gtsylrlvix.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtzfktakoy.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gtldljtjug.html

[U48] PHP：纯枚举
来源：http://dali.hammf.cn/Article/details/gtvjwzugwa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtijselvwl.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gtfnupazex.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gtiiumrgdv.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gtqzxgqmul.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtdedhomeh.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtwwjqncje.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gtxjtangnp.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gtxgyaophj.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gtkfzlnfws.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gtrorjdyyh.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtzgqfxbfb.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtknmzhwen.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gtosenvhrh.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtkgbfowuh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtsfqbfnuj.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gtwuddqklv.html

f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtutnqemiy.html

[U57] PHP：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gthiazxdfp.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtaezqbjsx.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gtnbiigpzo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtamksoylg.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gtkvwxcmal.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtdujbgdbs.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtrrhwexgu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.redwolf501.top/Article/details/gtxiqfagea.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gtupaoypgj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpstnecrs.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtjxgelrhf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtzdboalvd.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gtolawtgei.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gtanzaqxwl.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtarwffjsr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtawysonbd.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtwzptvnth.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtqvolivxo.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtqnodlgqp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtpcmkcele.html

[U67] PHP：处理文件上传
来源：http://dali.fzhhl.top/Article/details/gthikoqafw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gtdtholbba.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gthkrvbmxr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gtnwynnfqj.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gthepsgrgd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gtdqtjrmcg.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtpisufegv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtnygzoirw.html

[U71] PHP：抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtneomdtpv.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gtwfztmhsr.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gticmqtuuu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258888.top/Article/details/gtugrexcwn.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtkpiveifd.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gtohvpmafd.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtyhophnnj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gtvttvsvez.html


<!-- 参考信息 -->