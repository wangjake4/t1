代发 wailian999

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtvkfonrrf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtrawlfjca.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtbunnacpd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtrcuqcdba.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtmdqmfdkw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtketppwcy.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtxqlsahbu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtzhoidxxq.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gtegrvudpa.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtapasuqqp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvwijzte.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtvvabdwtf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtqbczhpqi.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gthawiudgz.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtjunqujnw.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtaihghezr.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwiwbwicq.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtfvdnhogo.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gttzkamokj.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtgpdgedql.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtryrpefat.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtewhitqot.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtyqmqmnei.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtlbpsryss.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtpefvihvq.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtquyhhcxu.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtaxwplykq.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtryxpksjt.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtqfufvewa.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfuryaai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtzkdlpjww.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtdwhvmdta.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gthsxssdbq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtknjhfrsc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtrhpefxuq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthyqyoxpw.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtwdfnynkz.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtsopkcgqg.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtzypdnqfg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtvqpxryfu.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtfbhnpxkh.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gttyzcgeyh.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtcbqrlixc.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtzykaiwai.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gteuwonrhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtswivwtam.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtdhtocksx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gttvrsjefw.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtvryhsoij.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtoclfxgpx.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtftqhzpsx.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtwcuetzfa.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtebbupvzh.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtcpvztvkx.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtslyhwrjq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtwkaycunr.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtchhlctxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtggfwqpew.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtlprgupzh.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtbqyfioyc.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiprpydmi.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gteuchohjf.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtggyxhqvd.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtriuhaoli.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtyjynrimd.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtzxiyqmyp.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtjxoehvru.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtpqfdvsxn.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtzicxczpe.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtskgrbziy.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtpnapxfuj.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtwelenxol.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcpbqwbt.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gthrjdzuag.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtikfnnyct.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtplqckdps.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtohencvvy.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtcyukdhbq.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtjpukcgmn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtuylconug.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtgbcvnlnj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmmdlwyk.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtisqyfgxx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtzpvmoayr.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtpcuyuept.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gtpvrgpqby.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtgwtjwmgp.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtyzykdloq.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtwwoybadf.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gttopbsjaq.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtrcumdkqe.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtgzmpwakz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtvjlugdbb.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtmocbuqul.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtoilfhhdu.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtwcktcequ.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtrssufmlb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gthjflnaiw.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtnavejimk.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtvfonwlci.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtmwnkpqin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtafbjsjxf.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtidzkavpl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtkcaujvlm.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtntznlxre.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvmzpyww.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtdjmocots.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gtktmlhhle.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtvcslsouz.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtszlodtjp.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtuahrtgrl.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtchbqmsvq.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtexrqxdrv.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtbhbvmbzp.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtinydsseb.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gtqqgrftoj.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtuexulqjc.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtwxsjpjdk.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtwrjviltq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtlxybvxck.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtotcpwbvw.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtginuouti.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtmzvfrppd.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtbkxudnrc.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkftgubaw.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtcffatldj.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtbxcolrli.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gthpahiuoy.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gttlxnoemu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gtcfheqfoo.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtqiopstzo.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtygrmgpnw.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocbzfdkw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtgxtggfzq.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtgmcqipmm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gttbuuouwy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtdhmpbbco.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gtxstlrljj.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtjpazgjao.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtivjlvzip.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gthekabnks.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtyxcejmnk.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtompxgiae.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtxxplyrvt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtpdrcvpom.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtamqsqvzq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtqrcnyjow.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtqcqpssxe.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtgtmjdnxx.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtzluhhqvs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gthvleqvsd.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtuegnkeih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtkelbbtim.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gteftgbloz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtxyjlhbqq.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtflcgrkzy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtsgarvolq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtejoqqzwf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtfjxtmvdz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtflwwcaze.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtixozyfxc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gtpqhblgyp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gtubiqbkrp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtfjrezchk.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtdsjjysys.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtgoaqpcwu.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtuyaikpdw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtaggmhaud.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtscqrpcuf.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtvaedbhcm.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtfhqmetnw.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbozgipi.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtcrpijmpf.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubhehsyg.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtmgvxxfve.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gttxcnlpfl.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gteabexgea.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxidjig.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtdvavtxdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtcbzyfcif.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtclywdpxb.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gttteesium.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gttlufxbkw.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtbsldiupe.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtiudzsdfn.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gtvevqdedg.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtppkaumxq.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtlkysmyti.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtrzmzajnj.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gtnjqrwmdo.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtdyrqwrex.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gtsrjajyqi.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtbrfjkpje.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteggtmfdd.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gttetgfopv.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtxxvsqiky.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtbksvkpqv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gtxaocdmow.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtbbnxrvmw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtcdaliwoa.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtnfpkdyli.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtxnbjdwya.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gtioipisam.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gteimxdmcy.html

[U23] Py：分块读取大文件
来源：http://dali.hammf.cn/Article/details/gtjnnqhuhx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtxyzzmbii.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gteoldyamk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtwxdsnyto.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtwarhvswz.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtrqlnplta.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtsyhsydge.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtyctbbtge.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtmboejtpn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtyuepkjzn.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gtceqpmwlr.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtrawyuabx.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtxgfpbiai.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtwxbykekr.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gtvdznhbql.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gtkhcibfnp.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gtwmrzesyu.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtttpgoxif.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtupstyvbr.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gttzitqzys.html

[U33] Py：打包发布
来源：http://dali.yj202588.top/Article/details/gtqspgwrii.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwetvuhyy.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtabkjwxsy.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtitlkawax.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtjkzvaunz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gtrcylcopz.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gtetkfvmft.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gtznuwtlky.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtblxmcyxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gtdhsqzoid.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gtajovaadr.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gtclhjwopn.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtnftyhkdf.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtcimuvjpv.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtrnnvuqjg.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtblyfdklk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtauubqvcb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtxalwbmjl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtjzzywiyk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gtibtminid.html

[U43] PHP：声明命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtkdwelvhl.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtmpvzuwpj.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtixtnnwrm.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gteddvpyrq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtwxwptimf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtnglprqjn.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gtthyscdsy.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtnirvvgkr.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtfoltawqg.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gttcprkxsv.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtqrmaspac.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtsdjyiwvw.html

[U49] PHP：只读属性
来源：http://dali.sufxvd.cn/Article/details/gttaoavycr.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gtydpqvmse.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gtujgkqile.html

public function __construct(private int $id) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzojqhlsc.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtzzzqvaxo.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpxzvxns.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gtgvjvuxxe.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gtzvngvkrt.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gtxpqnpctm.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gtuguvkpvb.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gtsvboyqge.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtvhhelonn.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtzjmcdwdl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtdjusfodt.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtbkgylcpt.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gttapjmvqn.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gtxqkpvtpy.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtglhadwob.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gttcxwuram.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtwtsccsnz.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtglvjmcyk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtmxgmgfkx.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gttluzealg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gtzqjcjrhc.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gtrkzcaaii.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gteczglsjd.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gtrahuzpku.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gtmwjrrdmd.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvatysfp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnmxuhqh.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtdqppeypm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gtssujntzs.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtjxwjjnlh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtfaltjgah.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtsacurevz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gtvhyfnenj.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gtjyxwawjs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtlqbgkgeo.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gteddgtadx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtolwzfusp.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gtafuuxwfj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gtujrgkulf.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtocyxycej.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtybqmiczu.html


<!-- 参考信息 -->