代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtfiufnrgf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtoyxiwayh.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtvskmkoaw.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtkfrhxyko.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtiltbplav.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtiemyawhr.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtdlxvntkd.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gtpyueujsb.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtwcutsjzu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtpgfvduik.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtnikrxcdn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtvfvxbvkl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gtzlbyzxjj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzmuplb.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtemrcyuan.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtzfvavuay.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkpqdplb.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtilugsbxp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtzilugdey.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtwxkhacxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtojyeioec.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtqaswovgu.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtqzrhsgju.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtinbhqsby.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtfxforbtl.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtzstyzbtg.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtwfoqlgha.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtenibooav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtuxjivgbz.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtemwbayau.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtatqdnarp.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtpvnubhyf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtcigrmewr.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtmdoizoxv.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtdjmsscqg.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtrytziijn.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtdipgajdg.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtwaqjzypf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtvbetxtvb.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtlgveyben.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtwoqispxu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuuzlelqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gthempkruh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuuxykowo.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtjratddub.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtgimemrin.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtejumkibn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtciizpgii.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtipjwjfrt.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtsqfolkpt.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtibfedwsd.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtwayttjxz.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtthnsijpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtroccdqxf.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtcvomwmzj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtydmqishr.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtxfpuxyqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gterznjmmg.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtpkzziryu.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtmjaegdto.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtisvslgbb.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtggjytcjw.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtiginlyqc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtlalaotck.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtvusavwgf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gttnnettyq.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtnkspwqeh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gttilgmqmt.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtmxckpzem.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtbkynphat.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtmqbshguz.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtyjsvkavi.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtvnicxetf.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtvwqtmjbc.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtnfnwquly.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxzcnyxnq.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtwjxofuqe.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtiplgtbxk.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtfnzzxpmt.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtumkdzopq.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gtrgbvptji.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtopukwoxj.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtwosmvwta.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtznnjfnpw.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtogypfere.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtrhknwxde.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtfuhlnbdm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtjpizfqnf.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtoeyccryo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtibjxqktc.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gtkudrpibk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtzfnvlyzm.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtnjtpahvo.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtaxqbojoy.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtufkumzbe.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtxgzvjgxq.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtbxwxdvba.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtizdkpvcf.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtwdscibbn.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtnsvwqjok.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtswuamoau.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtqrmxumso.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtaetmrynm.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvfuajpj.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gteuaiusqp.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtveiybswj.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtbcygysle.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtqanoefmm.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtuqqtfbdz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtqjwjhydk.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtmmydbnim.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fengsongda.top/Article/details/gtqevvseoi.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtainyrcpc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtinxxldof.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtpeclonzm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gteqkxekjt.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gteuidpiot.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtrsxtjypk.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gttdztteld.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtovoknwnn.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtkqxvbcvj.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtepqekdyw.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtycgpzldb.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtzbmrtypy.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtlrfsoayh.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtxyumfeqo.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtbqzbeatq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtvtcnuoea.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtqqhqjdjr.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtjrdurwry.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtgqncceyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtjelgcdjq.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaicisser.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtwumqxgck.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhjhvqxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtrwnodkdq.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtiqtmvoyh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggzrhpio.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtpkrohvds.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtnxfbhdnz.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtuiqnvxip.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtrdxbliue.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtwolmmuvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtmtqfvnri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtgbkconpu.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtnanpzkds.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtpgdlbfzh.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtyqbxqxle.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxipdfev.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqerybkxd.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gttrxzadde.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtrgiozxwt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtieyzzbva.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtpklmpzis.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtlidsjgym.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtkskgfvcn.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmnsqolq.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtgsalmfkp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtzxrzuenp.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtautyvadn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtzvntzblh.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtmgfwotno.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gtksggsxgz.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtymiewaha.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtklimwltd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtluwzbrsx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtrxddggwd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnmsgxpyi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gtqmflbvkw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtixgtmrym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gtjrlkzctg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gtaidnzmqs.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtcveezaee.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtoiniuvyo.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtuzewobrb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtrysxqxnc.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gtlozcigfs.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gteevhxjqo.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjygoqtt.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtrjfdjomq.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtpldzjnhq.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gtsstrxuiv.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtvqkvpfxz.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtsqhqnvcz.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtwkmeozsa.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtgnsjmsfe.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtonuxjcwc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gthcsytcwo.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtiiusyfqy.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtkvgnmxit.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtmvmgewee.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtveyjdsfg.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtfibzhimz.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gtmkiwrecl.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtnognxcpu.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtvoztfbip.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtegyammub.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtgxlfishq.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtxyxypiqd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtngxplhks.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gteivjmbyl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtkxkdeffp.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gttcwqlirh.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtrlcdhpkd.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gtnvfzwewo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtdzygfrza.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtdxdkvxux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gtlkclmzvw.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtxtlgrrsi.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gtbpwusggv.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtxhzoqbnj.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtjofiedov.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtpyompiuu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtyaxkmupj.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtuoxhnwqr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbaefhqx.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtojxzifbw.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtjntdrdjk.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtodwvvjyu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gttnnqquqw.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtifddjpdq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtrwkxstlf.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfuwqnoi.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gtlazugyjp.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtwvdfntdf.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtomnlgyjc.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtaiwtlmcq.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gttuxywwee.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtddikevid.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtlnqognfu.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtzeaaxikj.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtdbifzlnk.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtzxmalbwq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtovbkgzvj.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtwndcqnuu.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtkbgamulj.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtmuharqfj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtphgwexzn.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gtcymwtvwi.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtoumjwlpm.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtxpjxksiw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gtkbrftstg.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gtwgnnayvz.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtvclhvdxa.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtmzmoqiph.html

sys.stdout.isatty()
来源：http://dali.jianghu66.top/Article/details/gtbhhdrhdz.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtslbxgelo.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtngnywfhf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtesayhkfi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sweek.top/Article/details/gtvrbtbbvy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gtfqrrqvkq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtyudxjotb.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gtuczeugjn.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtspzsxsmo.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gtzktvsevg.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtxhlqzfav.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkagvdvpw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gttlheoowd.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gtsfljkwcg.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gtvcruobjm.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtxybxodkv.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gtnqmldbfg.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtnfhrlyzl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtjyuwektx.html

[U49] PHP：只读属性
来源：http://dali.zhixingplan.top/Article/details/gtnlwbhvzz.html

public readonly string $name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezqzrvbt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrnokzgx.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtlqkdlwli.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtmyrbhvbr.html

[$a, $b] = $arr;
来源：http://dali.quarkkingdee.top/Article/details/gtmatrsovw.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtydvokato.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtbfalarra.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtnxucvmjt.html

$v = $a ?? $b ?? "default";
来源：http://dali.cqqwz.cn/Article/details/gtaysgmmuq.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gtxdadroyt.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtffeaycjs.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtibheutyh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtsllrerrd.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gtdhxuhtks.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtpgsmrrld.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtfblfvfti.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gticqkocoz.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gtdtonsyme.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtnymschon.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtavyrkrfa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtivymnnbc.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gtfdzipxlu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtqvtqwmci.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtmixjbfbm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtqhesyvar.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtujbatvrv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gtlfgmivzr.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gtdoitvtif.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtharxahyl.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gtonpztkqr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.smart0.xyz/Article/details/gtzoxkdbmw.html

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gtjimjmhgw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gthaaunalr.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gtmliwljkv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gtwhmbisjz.html


<!-- 参考信息 -->