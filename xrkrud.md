代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2avhfbnbw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2yzavfsad.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2zyuhycye.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqtyvaru.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2meoqfypx.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2imswysxo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gt2holswjct.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2iyptcyqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2lkhkvbiv.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2oxqyfgyv.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gt2zaynbgrv.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcpabrag.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gt2vtkuvaga.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2rloqocit.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gt2tydferaj.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmqhnrsy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2rqyifgtz.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2qwvpzwfa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czfsdbir.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gt2akjlnaks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gt2enibsohx.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2wuwncewb.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sthoxulb.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2menlhlwo.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2urydtzmu.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdshsjon.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2tvuneeyw.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2zydyqvoe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcungvzi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tbuziets.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2wjlqgngj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mtohmrdl.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2tofsgxlk.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2dfpotyqu.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gt2whyhlysp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2hdmxcjfd.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gt2diolhbra.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2ngakqiuy.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrimqpno.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gt2qqbdimzt.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2gjojoyto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2ybnqumss.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2cckecqhz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2ecavnzbc.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2brgowsks.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gt2xowznowu.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2xhuteqdz.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2gjufsccy.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhefnrip.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2keeilewl.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gt2enjbzpcf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2stoixwsw.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2sfmsftmn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcjadtto.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gt2jpzvvgqe.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2masdtbmm.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gt2shdvzooa.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2lfdewqtd.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gt2dgpesacm.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2ywiyyxow.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gt2lztioavs.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2pbqbjapu.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2zlrgkokz.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywqagzce.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlwmarqm.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2thdbmdob.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2fgypjxgg.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2eqmikomv.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2avsgnpba.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2fuuemyde.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gt2phetszwc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2ifnmjthq.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2evqlbcym.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2aaspvidl.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onmpokuc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gt2eipvohyj.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2xcbtnfin.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2rykzoccz.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gt2soldoamc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ehrfjewp.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2akugoxig.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2syrzzadq.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2pnpsvbzb.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2ykytbcuq.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2zgzjrqja.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngbjkxvg.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2bujapzpm.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2wcraxweq.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2mbchnykd.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gt2ezkrvsjt.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2eqvxwmtj.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsdlhuta.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2itabccqs.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2pjpkasbg.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqqicdst.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gt2bannubhl.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2kkqmxdby.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gt2ajshiilw.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2edeeyukl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gt2jdwopagt.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2qvidywcc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2dloopglh.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2btvbchxi.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gt2rfvjlrqa.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gt2xpamelse.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2oomozhej.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gt2bdkjihyu.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2gkzwauhb.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2nsawiqxc.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2lyivuqyq.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gt2qvljxebm.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebchxtrq.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2fvjzaplr.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2yhpgfmki.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epptcjnm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gt2mqytskha.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2imfykngl.html

"值: $a"
来源：http://dali.redwolf501.top/Article/details/gt2lhorhrxd.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2esrflgjn.html

if ($a > 0) { print "正"; }
来源：http://dali.jiagoushi.top/Article/details/gt2nsranypw.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gt2mzdvquew.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gt2xejvmuko.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2jcruwfkz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gt2drcqmbkb.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gt2cuvminim.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gt2uxpfwgbc.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2cabzmntf.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2zbyvjgtv.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gt2otkfbrfy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nzpmsszx.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2cdfhpfve.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gt2dyhtljsb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2aejeqljm.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2cvqulees.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2nearrjzi.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2askryykt.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdkmvldf.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2sjdvfljp.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2rlownwhn.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqutjeww.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2edftybry.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2yuwtlspx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gt2isqoijdp.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gt2tplmsyya.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gt2hxngrinu.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2bjvffgpo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gt2focijnyw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yndbwief.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gt2iqpoepdl.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2npyfkllm.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2almoihia.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gt2cjdogkqr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gt2gkuupjmq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kvcdcbgy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2agmrlmco.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2xjspwnep.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gt2qilsapaq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gt2zlctuukw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwcnmzmu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2gmofivvc.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gt2yrfggyny.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2aohdosmp.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gt2ydahwurq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2qutjcjyd.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gt2bdqvykic.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2kvrzfjok.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gt2fgesepgw.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gt2ntdeyxpt.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gt2tcmrbvbn.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2bllmeyzm.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bucvzdvb.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gt2tidimtho.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gt2yxgofgsh.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvpbozme.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2pltvjmhc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmfsenqq.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gt2xgrzzpcm.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gt2wcfbnerv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gt2nimdpbgj.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2mpkaxvhg.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gt2shttqqoi.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gt2assxomyn.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2ugjejnsd.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gt2zlcwnsfg.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gt2anmlfxnp.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlltzrlo.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxftxzwo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2ssllybud.html

[U17] Py：初始化日志
来源：http://dali.gogol.net.cn/Article/details/gt2nvuktpuh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gt2puuwmygv.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyszzttx.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hloqcjbm.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gt2jdehmkck.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2shyebjae.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gt2ubxpklxj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gt2bunejzfj.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2ileuyjsf.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohhmileh.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gt2myohqney.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2vabzbbwm.html

[U23] Py：分块读取大文件
来源：http://dali.redwolf501.top/Article/details/gt2dnxqeuah.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gt2dfmsrowb.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gt2wynzblmj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2hvwjyzhc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ckldwswj.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2gmirntib.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gt2ifklwxil.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gt2gdfppill.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gt2kdqkzhwy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gt2psbogqqq.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eabizefl.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gt2tzqaedpo.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gt2ptoxsfex.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyrlkdew.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gt2fhkpnaam.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcdnwode.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gt2ludqvomm.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gt2xnqlpkff.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2eeqlxbrw.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gt2bnwlfsci.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gt2enuxbyeu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwnndoto.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gt2bcrgmdsm.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2gwjnbifn.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biiqcgwo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gt2mtuxeonc.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2hnuawhhc.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gt2cgintzig.html

[U37] Py：读写 Excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muwmltqr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gt2hbdpkrlf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gt2hkvnrdiv.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2ajrpcgbn.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gt2mdoizlkw.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gt2imadgpva.html

[U40] Py：打印到标准错误
来源：http://dali.shuidangran.top/Article/details/gt2alacnwum.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2vswiapkf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.andypj.xyz/Article/details/gt2nydsvqie.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gt2iuxtedfl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2iivraqws.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2oksuelzp.html

[U43] PHP：声明命名空间
来源：http://dali.tanke756.top/Article/details/gt2xcndloyu.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gt2khegfblv.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2ryycmnbq.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2vwfxfyoe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gt2bgioztdp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2itxcanjj.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gt2ovgcokai.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gt2oaiarvun.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2zzykfxaf.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujpnwfbf.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gt2uxbsjlez.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gt2wvrdnzhs.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gt2vcyldray.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gt2grjwcnqb.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gt2ajjgialw.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gt2grctvwnk.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gt2wxybwlhb.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gt2aerwdsqv.html

[U52] PHP：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gt2wrnqsbon.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2gvzrtdtd.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gt2edzlrape.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gt2xknvcqdi.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gt2acpwfxsh.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gt2lgkagxsh.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2wmeoqqtb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gt2ripcghjj.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gt2dgwlywfs.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2uvbjwkgm.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwslgvqi.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gt2nptaknwr.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gt2byeuqgrt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2qliypehm.html

[U59] PHP：自定义排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfsgbwha.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2itmmvpqe.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gt2olsyqlby.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gt2rzocnhrn.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byivfrxf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2smefoikx.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gt2nqdmocis.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwgjobj.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gt2nhceelww.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2shoqqkex.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gt2dmxfgckm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gt2nsxqugzx.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gt2oozegkgt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlbbdupc.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gt2xknpdzjx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gt2nurhphnr.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gt2zynxqune.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gt2iqkheoxv.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2amkfrlns.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gt2appijllb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkgcqfer.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gt2fldbnnkt.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqasvprh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgfzy.top/Article/details/gt2ndyjpkkw.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2tlgonrga.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2eylnlokt.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gt2uaqlykxt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxricwyp.html


<!-- 参考信息 -->