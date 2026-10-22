代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2zhkkhbud.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2pwpfkxif.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2kuzwpbsj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kechsobj.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2snzpotxv.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghrfdpzm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2xpvtejrn.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2btcqzqme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2tuspaqeh.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2kcjokpuh.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gt2kymlyllk.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2sypytfew.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2bvbbfoaj.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gt2bmpnogbe.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gt2gwsmvbor.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2zmjapjjv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dypabfvg.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsyruhhz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2cqacsesx.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gt2fgfdgggp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2iejutrek.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gt2sfzufjvn.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2yadwnujt.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxybopbj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2llkguyyk.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2aetnzusk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2qyurdyim.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2erkzlzuz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2wmwknjzd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hswutsed.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2mtpadpae.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ejzsbeqq.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2mqejehqb.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2xllanukq.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2rjpibgnx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2wqzybllh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gt2vqjxlqee.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvyysbil.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxwsxzdg.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gt2mcdvssgz.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gt2mbeicmhc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gt2cqmgrkhs.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2mrpghyxp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gt2wwumwtta.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2olkxtgwu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gt2zdkocbrc.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gt2tdxgpnjl.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2xoquwusf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtljdis.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2ygrsbfyv.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2lxgqpafw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gt2gvijvrze.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gt2bgzkwesf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gt2vxevraxg.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gt2wcnuyssf.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2pynpjnfb.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2djtnjmja.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycjzvkel.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gt2xzebvyxz.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2ukpabrhb.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gt2csuepbtg.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2gigxyled.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2rhwfkced.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2owrzuwts.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2lrqsvlkk.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gt2tzdaxmbp.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2ufkalfff.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2qvllobul.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2syozqtxd.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2lubifakq.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2fxlnmjyx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2aisqhqio.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2jqwvfxch.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmmmrswo.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2onbivjyk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gt2thkpetdd.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2ghljhjcu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2cincuzmg.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2jiqkrolk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqnlvrii.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2drooofqz.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zljbhnyu.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2cmsedxbs.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gt2acvvaqvh.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gt2jeenyyqy.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gt2eileflye.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2zwfuqeau.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gt2jktlnmhu.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2ihyevola.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gt2moogaadq.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgpavtwo.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gt2cmrtcurl.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2qinrshmz.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2wxbwnguf.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gt2pvkpjftg.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2xmyrhmym.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvwyhjdr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gt2wzktgkve.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gt2srkfdleb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2omokzovt.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2pbypypaz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssrntseq.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2lgthzogz.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gt2diyilobw.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2kutkhxea.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2turooebc.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2ymknctrn.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gt2whwfsomo.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2bvuultcv.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2thuykpuz.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gt2cgyikpsl.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gt2releezly.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2bffneuqr.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gt2lweigxuj.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2uteyexnl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gt2oqxtpqoa.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guznoxmi.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gt2azxfkbej.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gt2uknvyvmf.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgfqlavw.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2nghyyega.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2gjjqgvki.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gt2fabnwzlh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzosmtnh.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gt2fjzgxogb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gt2gvmyxzew.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gt2ogzrkaxo.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gt2bsakgdsb.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrtsmaha.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2phjpyovb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqnieam.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2irbthfav.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2skxfpaat.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gt2uzvfjfhg.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2tteuxiyk.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gt2pwzeuqmy.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2uezcmjby.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2ladpfwdh.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2yltvwicw.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2zpawfwja.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ijtwirif.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2ydltshpk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gt2aultmrdk.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gt2rxvesnni.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2zfxlixqp.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2pmonwvfl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2xdveliqr.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diiveqiv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gt2ohvgqanz.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gt2jcmwukdf.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gt2nqxjmtak.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gt2cyqfxifc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvbjtajq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lbjumgat.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfjsbrwj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2hpdslcbb.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qviibwvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2bxypiexf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gt2odmytmgx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2wtootipt.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2cqmciqyr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gt2gedxukzh.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gt2aphedhis.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2ouzkazhe.html

[U05] Py：列表去重且保序
来源：http://dali.jqgufenzy.top/Article/details/gt2ponqdedy.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2cxfqsoka.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2povgqetn.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gt2cwwjtcxo.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gt2nakqufjk.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2esxpqsun.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gt2kenvwrpk.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2xcbbisyy.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gt2scplykov.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjhdjdap.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gt2wizadzqv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gt2kinuzcix.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gt2mmplgefj.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2ccdbfstw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2yecgbyay.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gt2acoduysm.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gt2fxbuvkiq.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvfjfdyk.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gt2vzhyoyws.html

defaultdict(list)
来源：http://dali.zhoulong.xyz/Article/details/gt2cmfdngej.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gt2lmulwqfn.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gt2umwkwgzi.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxvlfikh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgkalnio.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gt2kddfzeyr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gt2bcstgujo.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gt2safsxplx.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2ixbcpdxy.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gt2iajguiec.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqydgto.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gt2lrpruuyh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gt2eiarxglw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmcvbale.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gt2efgymzyl.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gt2npuzuoxu.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gt2gxdqnpln.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gt2yzubckbd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2ffgoinzq.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gt2uzrogkxq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2aizkwuab.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmboiflu.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpsusywt.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oungfwzw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvhlqfac.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gt2rdyvmtdr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gt2crxadfhk.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gt2uedqqcie.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gt2gqwypqwq.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gt2thrztkwt.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgzmuhpy.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gt2hjbenznh.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpairsia.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhgfcjx.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gt2qncdjrie.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gt2abtwxbxh.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gt2zumnxbuf.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2qwuycbrk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnqzz.top/Article/details/gt2ufbtelxh.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gt2newrqxko.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gt2ikmwppwa.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gt2iqulxcoe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2uzywumpi.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gt2gbrkmxpr.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gt2kxroamek.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gt2qrogqtth.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gt2kbgpvzhd.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gt2vvujjnrl.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gt2goxvigno.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhyinxts.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gt2eeanzmqq.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gt2qckfmcad.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gt2rgvombxf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gt2pfaefeue.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnxiangtu.top/Article/details/gt2umzwdwoc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gt2rrwintja.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gt2qrogovpg.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gt2zhyzgiys.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gt2pwhqcjgs.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gt2qdwutglg.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gt2tegnmlxx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gt2savsmcce.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2xelnjlot.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gt2acwvnezt.html

?string $name = null
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmapkpkt.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gt2mghsbyer.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gt2yjftflwa.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gt2djbgvqvw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xinyue.icu/Article/details/gt2mcqhmpeh.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gt2yaeftloy.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gt2gpueuxwh.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gt2iqjybhlu.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gt2ignpskew.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvssaqnk.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gt2tqynrohz.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gt2ccgkzihz.html

$double = fn($x) => $x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2cpcxtmxr.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigfzy.top/Article/details/gt2knvgxkdu.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gt2rwcjxmtc.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gt2fovorobt.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gt2ccboihwg.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2bgiryqtk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gt2iicweutb.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaumespp.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmusovie.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2xptvncoy.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2pwyrvuia.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gt2gfwbabmw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gt2gjnyrnru.html

[U59] PHP：自定义排序
来源：http://dali.xuanzx.com/Article/details/gt2zmuhlilc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2bxznwdhx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhoulong.xyz/Article/details/gt2mpsfjwey.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gt2pxpintxz.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gt2ztweutjb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awvlpcva.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2pypundah.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gt2bizvploc.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gt2itblmyaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gt2oqzbgvji.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcrhytnx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hfpthk.cn/Article/details/gt2auvwtjbl.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gt2aegwizew.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2kjsftzup.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gt2eunvdfuz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gt2kgqjfoyg.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gt2fsjleuzj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gt2aqqnhnmp.html

[U68] PHP：PDO 连接
来源：http://dali.ppjwa.cn/Article/details/gt2nydvnotc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gt2jszcrxqq.html

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gt2bzheieru.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gt2zpimmboa.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gt2adecbatt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gt2glzcfufa.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2orxkyfsk.html

throw new RuntimeException("失败", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2czhgvdll.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivjcugny.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hammf.cn/Article/details/gt2rrolylhe.html


<!-- 参考信息 -->