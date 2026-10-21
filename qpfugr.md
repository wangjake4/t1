代发 wailian999

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gtrepfokmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtofwcywxc.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtqctleoho.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtdwmsmelr.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtofadirdx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtfifessqa.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtqxkjlgdj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtmdvdweuu.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtguesteqa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtusjrztyn.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtjbyuqryl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtagkfjooy.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtgpexylvn.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtuekfgpgf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtkqburcqy.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtlfwydqxo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgevqwms.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtccvumocj.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtrplvmbrz.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtumnvohzj.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gttmgufbfy.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtljtgnnmc.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtcqfvhpla.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtwlvjjcgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtfktoiwxd.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtykvghcym.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtwqtgljuc.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtryureyqm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtswivurlv.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtnbqfycxg.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtvjchlgrq.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtclzsarzz.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtghboopcl.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtwkqfibil.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtyzjgmxto.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gttefxlztf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtijxcgxgm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgavztraq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtswompiay.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmtaempgi.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtfsasghfr.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gteybaxeve.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtofjryuhb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtdwsddjdq.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtzfydjbqb.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtpexrpmmp.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtxdwqtnfk.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtnagpcwvo.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtoeuyvhxx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtiuqkornq.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtqapaheyc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtisfskpjs.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtjvabbcbq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtcjxslpwz.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtoynwprao.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtdqtnqlde.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtcuokzgsi.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtnmxrdmzu.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtlacjlsrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtkyzstnbp.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtjijnwiaq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gthrdspyqe.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtezlkxnmg.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtjdmqxnkr.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtoyjxpwbj.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtyqfpoioq.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtjdfulkez.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtcfwavchy.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtvzjxwzha.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtthbawqgw.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtxdlfrtce.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtwceckeey.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtnhpmdvbd.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtdzqshnyk.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtlxyvxuhc.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtckggrqnb.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtmyggvjsm.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtchaglwfb.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtqtlwzwqh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtozfvnkvl.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtkejodjiw.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtuyostppb.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtoqnhfiab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtsqnxggxh.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtlglihsdi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gtghtwfuxe.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtcziiumdy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtghsfasvt.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtlcnfdvtq.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gtlephfdis.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtllyrwjpn.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtaosknurx.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtlpzgaohm.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtaeivnanq.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtvasfchqi.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtylspkklk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gteilurakh.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtphdbrgks.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtiwywzuti.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtrkwxvmjh.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gthwzabbzn.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtdgljociw.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzccmnjvu.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtqfrpvdft.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtwpjaqiei.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtcsolbduu.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwalljks.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gtalotcwym.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtilhjylzf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtemhbpgbh.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtzttmpkso.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtyvnocdtj.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhfpdfqi.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtsmtrnmxi.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtmrvsrumq.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gttzihknph.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtgyhhdegm.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtdtkdjawz.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gtziijyogd.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtxbptdabk.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtguvpvbsu.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtwxtbwozq.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtfivheaux.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gtbmluxnxw.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtzuowxuby.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtbjruwweb.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gttxrimpvt.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtsxaxhcna.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtcayfqbmt.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtubymbvnx.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtpffvcqvs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtamhqyfdm.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtotderhqt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtwjosuqfl.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gttndaqcot.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtxbveslme.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtefjpazmc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbqtgeabp.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtvcikuqgh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gtxmftrdjz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnztglftg.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtlvjteksb.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrjoiysf.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtbepgegtp.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtoejfwlda.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtvadaamgi.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtkwcvndut.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtpkxgczwo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhuylmtt.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtyzexslou.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtaohyqwyb.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtjzyseoof.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtmypvvnol.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtliwbtwoh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtzneenayy.html

[T58] Scala：函数定义
来源：http://dali.fzhhl.top/Article/details/gtdyvklrtf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtburyrort.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtpjxkymtk.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtundtgbch.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gttipvhtwi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqchndvlj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqtcekikr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtajobwlsa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnnufnbxf.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtpksepdna.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gttmkklpae.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtcowjkjas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtgfrgqidc.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtaxqcmcau.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtpxyknats.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gtbcxgxphr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtkxqfdkbx.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtnfokcynf.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtzxpdivri.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtuanrniek.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtjmpkhixv.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtlicjjaok.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqlnxlez.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtauxvrazz.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtqttfpgrm.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtuswczaxe.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gtystpythu.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gthaazknrx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtgcntujuz.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtnuhubrex.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtcwabipyl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtcuvkzkac.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtcwkeazov.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtsxpzordp.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtdutcxsoj.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtsgdffers.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqehzlle.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtdrxsyevk.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtepipglki.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtisiudseo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtcctuftux.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gtxknsbnxb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecbarkio.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gteqizrqzd.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtwndxnnrh.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtzxhezqsc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtgachiyio.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gttqeqmgyk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtemtmhlkm.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gttjxyuqsa.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtjdblccyb.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtwtwpbfkn.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjuyfviv.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtthlzoxgd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtktognodb.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtypcnxnea.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtiphyvtfp.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtoiywxhlx.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtxljkivoe.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtdqrryedt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gtyqqqmxgh.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtcgbyacpo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtnqqdwcpf.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtzytdfqvn.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtpgotkivc.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtpynbfsyz.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtjswcqxxy.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtkmzxltmu.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtpyfdvndw.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtbgwricmg.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtzatspdem.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtqlchikmr.html

ruff format . && ruff check --fix .
来源：http://dali.zhongyouzk.top/Article/details/gtoftyabtc.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxwwuyga.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtwoqxkozp.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtlsjlihzw.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtjlgvdrwy.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtenlihajj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gtryhmcnae.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtjvtiwphn.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtgptghoeb.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtikeilhol.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtstshgv.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtwptbgknf.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznuoxwhr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtvzoybhib.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gthooejahu.html

[U40] Py：打印到标准错误
来源：http://dali.chenjidiqi.icu/Article/details/gtszosstlx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtkqxzfifh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gttxrmaxua.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gtsnvqraec.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtjegkuflg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gtsbissfkc.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtspiegyzt.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gtchzjpkdo.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gtizvamkzk.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gtdlljdzij.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtoizerxrn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtaxhdbvve.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtavslacoi.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtzcdoifdx.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gtzftiyour.html

int|string $id
来源：http://dali.yvedp.cn/Article/details/gtwjubkfte.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtghdxcfau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtprerzatt.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtrovlzxdo.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbcxewjv.html

[U50] PHP：构造器属性提升
来源：http://dali.zycfv.cn/Article/details/gtfwvjdcmt.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gtkirfdeoa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gtowjrlprt.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtnnafufix.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtjwabfgjv.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtarvdftqg.html

[U53] PHP：空合并运算符
来源：http://dali.gotoacloud.top/Article/details/gtgsofmuiq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtfrtvtgqi.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gtliuesidr.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gtvykxepyc.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtfqxnzksu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikhywfyv.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtcosegtho.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtkymdegfh.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtpyymgwsb.html

"值: {$a}"
来源：http://dali.jyoumei.cn/Article/details/gtmyzkmfeh.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gtzvzeznmr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gtnasvdryi.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtwzforrxy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtpnbxwaxl.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gtbonndhia.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtunygfphw.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtbeifswys.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtooltuwbv.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtkcvutwha.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtwmqhwxpd.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtztvilfkp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gtydmkqnse.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtygpldxxz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gtocijriwb.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtoqakprqf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlymdwbfu.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtlbxgnewj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtctccwroi.html

[U67] PHP：处理文件上传
来源：http://dali.yvedp.cn/Article/details/gtzolpwaja.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shuidangran.top/Article/details/gtydepisfm.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprluvez.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.0kj1m.cn/Article/details/gthbxqzeos.html


<!-- 参考信息 -->