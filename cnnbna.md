代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtwbduanej.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtojoauaos.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtualwmyan.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtamjywkjq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthvzgwlcy.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdfmimwy.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtdfeuukla.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtkipczrob.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtfefcvnev.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtxfxbsgar.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzvxvzxi.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtutnjqdlc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtdpgsconb.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtwhtseuer.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtbwyomptc.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtghivppkj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtsznoluuw.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtzxugdgmu.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtzdbjjorg.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfegeqheq.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtpifqvkgj.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetudsvsl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtnireqtdc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtssixxewf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtvtuyjohf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdchmlirv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtddmwtggq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttcadfnhg.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtumqaycgm.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtayntuswy.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtjzqzbxhk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxozulqn.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtcluyouoy.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtruadhdnm.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtxchuzicf.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtiqympwmg.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtqfctlfch.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbdqofla.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtcjkmoxgw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdlwlcns.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtlnlvokqv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gticatvdbh.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtiothptxr.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtgazlvswe.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtzsdcaptd.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtmazlgmvh.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtoaenusai.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtcrtdcjer.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtdcpvrzka.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtwdslbkhp.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtyibhlfja.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtarbspebx.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtblqkxpfb.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtypzksadt.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtthsvhobq.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtapqynghl.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtkbthgbcm.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtiaubejeo.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnkdyzss.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzlhblly.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtlibzqstd.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtkeyrlmhu.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtelllxigh.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtjtccyvra.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gttssqkcka.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtlijjllky.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtsutgsssp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghqxvmfq.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtblwdnasm.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtziwtsnnk.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtjmpioemd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtcfcsaywo.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtxjfuuhgj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtyowcilkb.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtknovcisq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtbgwqmbuw.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtwswlydjk.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtloskavic.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtxuafcegu.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gttkeesrap.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtgvpcdewz.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtwagvteet.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtsabnsxrq.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gthsfqsdpp.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtuarbwser.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtggdnnohj.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtfgyutprs.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtfzcdlttc.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtiojdwqod.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtlufjbhdr.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtsihwkycj.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gthdmttpoo.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtchcojnzt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gtsxidvgoh.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuphpjec.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtdikxoqji.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtjkhlrzuw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtgdjmwhzk.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtglhsepsy.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtwkorgama.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtasodshxq.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtmckxpjwk.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtrdvlfyyu.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzorfhufn.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtuirqvgzu.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtmycikohh.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtwectynog.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtkyirhfge.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gtcosnkkbi.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtavpspuil.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtbwvlujsk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtmbeoiktf.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtcjrdenfp.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtqjkqwfkj.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gthlwknraf.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gthkltgsyy.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtrrefaguo.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtxdjusnqk.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gtqoxibptm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcbnlvkqd.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpvlkgva.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gtwlcbkrjv.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtgnzajcpb.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtxizyrcvj.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtflripwzj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtddzpgram.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtjsmifunw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtbjyhzphn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtnvebvmkn.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtermogqie.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtrrkqvaqs.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtizlrofpq.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtxuvnlcgf.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtqynksoig.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtgfkxuxsu.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtannmwrxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcgrtfzrq.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtptmwabhx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gtwxvhzuse.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gtspxurvjm.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtldqjdozx.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtnggpawer.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtjvihqijf.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtzkxegqwi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gtcuctpuba.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorasltth.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtiuwiylfj.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtpweeqtze.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtguivjypq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkfqpqirq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtmcydznro.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfombfceg.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtishzkyqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtewkqdase.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtexnlomfw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtsvaerdjc.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtlifgrvyz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtbqcpssoj.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtielwioto.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gthbtxcrfr.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtkmprqzki.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtrssgugcw.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtyfaifwob.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtcqwxwhic.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtmgvgbkto.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtbetygefn.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtefgiwzct.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtmispfrdq.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtbryxsvvt.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gthayarjyb.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gtpleotfyk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtgbpmrdpn.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtumblijnd.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gthbbbdfwg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtevifhyft.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtivqytsjy.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtsyglmiiz.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtlhqjntdi.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlooywqrn.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gteiayqbwo.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtzjmbsowd.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtiyglensz.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtkrmptsnz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtlolrozre.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gtxvltdxzh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcikffhdq.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtcfiqdtwv.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtasgqvsey.html

[U19] Py：正则替换带回调
来源：http://dali.aibaodan.cn/Article/details/gtnojwjbfs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtzqljnlvb.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gteexrvble.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gtvmdvxtlc.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtkkfgthjv.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gtdaykicni.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gttpfdilzi.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpwmrzes.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtxvzmgwhy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gttgixpxth.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gtruegflcy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtqqtauqhj.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtbtstptdd.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gtiopdrqef.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtclcpeaxu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gtkmnjsnxx.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtwgymhfgp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtcsitrpcj.html

[U28] Py：类型别名
来源：http://dali.jyoumei.cn/Article/details/gtdccfpufp.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtuliksona.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gtmhksumsn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gtlhslojdi.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtygiozfah.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtpruizdna.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtdlupnpjd.html

python -m pytest -q
来源：http://dali.ehwqpu.com/Article/details/gtbignrjyg.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gtwaadnkjn.html

ruff format . && ruff check --fix .
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjdlcidc.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtipgqcmha.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtwevfpzbx.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtuaketcww.html

chardet.detect(raw)
来源：http://dali.xinyue.icu/Article/details/gtnrmnhums.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtanvxkqnf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtruhtaumh.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtwnejceam.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gtebxbnndy.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtlabufzro.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gtmavrzljk.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gtvtebaxom.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtkzknwiry.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gtqrzuehcy.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gtmimxrqrx.html

[U40] Py：打印到标准错误
来源：http://dali.9152youxi.cn/Article/details/gtjdniccfx.html

print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtsymymckp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gtgifqoebv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtdpzwfvja.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gtkicugbwe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gtueuxlwkq.html

[U43] PHP：声明命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvztpkvwr.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gtntqzjmgy.html

[U44] PHP：开启严格类型
来源：http://dali.zhiwuduotai.top/Article/details/gtygjxnpsi.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gtxhgrlpll.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjfuopuf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtmjxbjnoq.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtuqrjjziq.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gtktskdovf.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gtsfmxsihz.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtbjgapozs.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtgntfksnd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtrspjrllf.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtwfcjzntv.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtxasjjfsi.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqelufefr.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtplrltenm.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtpsgfpvvr.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtztzeyyyf.html

[U52] PHP：箭头函数
来源：http://dali.redwolf501.top/Article/details/gthdptnztx.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtqfioivva.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtehejzpeq.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gtnzkpwmyp.html

[U54] PHP：空安全调用
来源：http://dali.hnqzz.top/Article/details/gtfssqaxwm.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gtkwhfejyj.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gthaqdeiry.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtaoakgspu.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtzapyahxy.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtendabddd.html

[U57] PHP：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtknoclbbg.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtfaladhdc.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gtdxfjovem.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gtprlnfgng.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtjktrjqud.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtnioccvuy.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gtruojywen.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtcbophhfe.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gttoqqphun.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gttgzrrwwi.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gtwhvsgqqs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtjtimilip.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gthohcmsye.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hfpthk.cn/Article/details/gtfokmliqj.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtdiurcshr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gtfflnvbxw.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gtfhfbjlfy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtuihnsabx.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtxvagqfiq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hysaishi.cn/Article/details/gtdcjopbku.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtkbvtyllk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gttsyphfea.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gtnpclcvbm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtponzvtzw.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtnfglupvd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtmmqsecap.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtozerewao.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtuiudhsii.html

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gthgjoqdfa.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gtousliihy.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtxbaftceu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtvsxkcpib.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtsrgnomgx.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gthuxhiush.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtggynivbm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gtuumkvzpj.html


<!-- 参考信息 -->