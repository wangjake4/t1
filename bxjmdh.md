代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtkqybglvs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtumiewvcs.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtxiqrqxxx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtfhcdnrpw.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtgilnkbre.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtbgphrzgv.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtyoqpecee.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtdifeinrp.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtedeoylvy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gtdfqqccnv.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtfmqurbge.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtemiflsrj.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtakwkiyyz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtjhhqemro.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gttaqwlrzx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtzojiuugk.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtrvrcahqm.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtwhoixmqs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtasqzefrx.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtblibvnjz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtdndfggam.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtvxhbrxwc.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtowpwnqrw.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gteewfbzlf.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtdhmxwuwn.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtaqadzrle.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtcnfbzyqa.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtlknniwnd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtqxbdxspl.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbghahvil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtoewnzwiv.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtjydjljlh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtplovpvnf.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtjmekditd.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsporhak.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtehcwmrzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gtuespfazd.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtnwuciexq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gthfamabxz.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtvtbqtanc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtanprbhdz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroaqhlbg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gttipjxyob.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoymhqsqc.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtsyxwqann.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtdekqfhns.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtoavmuukv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gticfrzhbt.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtbvprgkum.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtottxpgcy.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtationdpv.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtywwvszwz.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtqfgjmxky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gthpbdonjb.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtnvyfswxu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtkuveskep.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtmlsidbkz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtrlkcgvwc.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtqkmdvfok.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtcsoafwgd.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtsjwtgcki.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtmsbxpfem.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtfgcetfgb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtsajaxpsh.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpelervh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtqchobgjf.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtgnacrruh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtdqoluixm.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gttmmjfwyg.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtfxffzoto.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtpwyynupx.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtcuxdrcwd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtzxmnkpxi.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxaxcdnb.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtpsdzozvw.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtkbyphdce.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtoktskmun.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gtjunqmdxz.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtkttbtzaa.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtuoeylabl.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtbckojhrj.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtfvrwltoe.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtvjevrjid.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtowjtojue.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtavuobqad.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtfcmdgmwr.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtuqoidgwb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtsmaunpdy.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtnqsswuuh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtztrenvxa.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtbrknijwb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtjvazrmbu.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtdhiwzcpn.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gthggpfnmy.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtgnpyavya.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtphlxpskg.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtvzsbbvbq.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtqbkowrei.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtesitubek.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtehkksvqb.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtfdjdncwc.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtohihjoof.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtysxfrqiy.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtmhqkrpxp.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtdjpgmwjj.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtsdfwjvfy.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtqkxjutuu.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljpanbwm.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtalagyadl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtxaudwhdg.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gtmfundurm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtfnofqoge.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtdnnzocik.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtryewybds.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtrsnjmots.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gtpdrwcxdu.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzwynwaf.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gtpfwwtbkk.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtjflhydwi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gttpebfdor.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtayitltfu.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtqxnkilnu.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gtgvpgjvwl.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtnqrcyubh.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtffgzbybc.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtxhlzafdt.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtdfzljbhb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtnvnrjipj.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtetqwfaho.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gthncffnml.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtqkxlglbd.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvgesbocf.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtxysddspf.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtyenwhlem.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtlvgeewdq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtdoeehuve.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtghunrpvy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtpxvkwgtb.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtmdjhmqqu.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrlcvrer.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtpmgtdovm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtwybmlyhu.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gttrzcpgam.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtoncixfge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtmprifhzl.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtubxriuov.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtpwtyywka.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtkiupnjcf.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtbysqcfvq.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtkngpsjtk.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhjtkzju.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzwxkgwl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtboloxzwe.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtupurlkgi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtcwacqhru.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtwbjwqhcs.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtqcjiumlh.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtubbpvwbi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtcditnrcs.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtdrrdwnea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtwelucxtt.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtzeuamori.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtfizzmxyy.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtjyaubceu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtrjehvfwr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteodujdin.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtpkgpzqdc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwhnnwgir.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtjanihfoj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtninzdoru.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gttrpbeuna.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtsgqrtwwj.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtjykpknrj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtcddurylg.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtslkoesyb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtfebhevwc.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtzuakbkkl.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtrvuocrlh.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtvxasecaa.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gthxjjxkcv.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtuoilntxr.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gtosqrnviq.html

[U08] Py：展平二维列表
来源：http://dali.ydzc1.top/Article/details/gtwfxjinla.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gtkuaqwetm.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtgeqwvgkz.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtszkpknjc.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gthaxzojom.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtvdibhire.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtvfkaoagn.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtphgierqh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gttkxqnmnh.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtjwwfxyso.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtypnuhrbc.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtwmrmzjhu.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtizpthape.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtgrxknfzj.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtygxzgwqq.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gteisukcgl.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtzprojzvm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gtkvnbynwj.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjlthefh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gtybflcndv.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtqhtqzqds.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtzptmzsdr.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtbbwfllxt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtwiyfbhss.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtiikcswar.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gtomevjuve.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtfaqcfkvi.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtntlcpzye.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtujvxphnw.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtthpmmcjx.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gtubufqmou.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtggmqqkux.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtsmqywgge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtdgtibncw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcovqnnf.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gtatjkrykm.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtpgzkmhtq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtzvimnlho.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gtirylfxpp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gtkhwjnbmv.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtrlfrdvzq.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtwjshahdn.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gtikacwhms.html

@property 与 @x.setter 配合
来源：http://dali.yuxming.cn/Article/details/gtyqopsnyj.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtpgsktqtv.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gtrmhdrraa.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtvyzlcjyd.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtodeagzud.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtuxypztrl.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtobbsnwkh.html

[U33] Py：打包发布
来源：http://dali.chenzaomai.com/Article/details/gtwwgjigba.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtxqxibule.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtvmltbiwn.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtnetwplka.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtaytouuri.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gtgqtzmtyg.html

[U36] Py：定时任务
来源：http://dali.9152youxi.cn/Article/details/gtzhixhbhy.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtnodzgdcj.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtwmrqkaqr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gtrdseydhe.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gtpaqqsflg.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtzadmcitd.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gtmkpqioyf.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtruszxkle.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtpftuegad.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqhnwmrlk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gtyojvisfm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtoaeoaprr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gttbzftbyo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtgtpajsai.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtrukudsao.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtaleytsqg.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtolvykkom.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtgewotart.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gtwzataiuj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gttsqnilxk.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtwowfnyjd.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtjedanpsk.html

[U47] PHP：联合类型
来源：http://dali.jianghu66.top/Article/details/gtjpujhkft.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtmlzyzgkh.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gttkwxebqc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gtzvmbcqsw.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gtrhhtjzri.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtpwnijuao.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gtlswlgdnt.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtznixhrnk.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gtnfmigxkj.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckvfzlm.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtsbcfwflc.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtcgzglazi.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gtatzodrvn.html

$v = $a ?? $b ?? "default";
来源：http://dali.smart0.xyz/Article/details/gtnojidmno.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gtgiyztykc.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtgodojtnu.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtbtvydhjt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwwdiygq.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gtvheaexbs.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyggqlvvf.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviduyoff.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgszkihf.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gtljwplmwp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttghupwxp.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gtjuywtjet.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtzvkhqgqr.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gtmhbvgpgo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shzxlz.cn/Article/details/gtaltfczaj.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gtezcbikln.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtqahuadjl.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtsfykpiuo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gtnzjujxwm.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtobucasgl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtbvtvmqky.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtydlkskyp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtamqxqfad.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gtvfivrrkc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtedbnwwkg.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzomcec.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gtswvrtdvj.html


<!-- 参考信息 -->