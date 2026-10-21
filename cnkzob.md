代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtexmbsxtq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtiapvblqk.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtzewloscx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtfmdwheba.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtffrtpodx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzxkvdpx.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gtszrscqts.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgzctalkm.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtgyuhivvu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtqhadxpdy.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtfqqcrmni.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtwjezfhnr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtcedwwjdb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtcrrintnt.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtiztnvlsr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtgicaidie.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtbznqhbjc.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtzynfsenw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgievrvig.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtpqhdxpbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtdllllmjm.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtzbsiqwai.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtufcydvmq.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtrigahqfh.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtjhlvcgdc.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gttfzldigi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtrlwylxsw.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtmcxpppnp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtdtuinhxa.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtnisrvceo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtevsrbpmt.html

[S56] C++：optional
来源：http://dali.cucudq.cn/Article/details/gttvblzwun.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtmwydsiep.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtrnjguesf.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtsdvtfxrp.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtbhpxigfk.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzhackvdi.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtzkeqhazc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtuwghvpzv.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtazxkpmhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzvvyfvl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvoqevgfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtandfimet.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkvzvzfvh.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtvcgeeajv.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtmhasmopz.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtgdrtchzc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtlalmowsi.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtucvklonj.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtkqwwrwvf.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiwantst.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtmbayglzb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtfjehkakk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqokzlaz.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtfvvsmert.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtmmlwqnqk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtqsogbgfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtxhpklphw.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtooiaciuy.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtmvwvyhnh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtlohhazmk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbruhfnhf.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtgukfsgcs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtdazjzbjx.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtekregnfx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtuunbqikt.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtwvmhoaqq.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gttxxsrwry.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtfqiwbuxa.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtjclwafxz.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtokiaiqex.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtbdgvqmpo.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtqhxcfjpk.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtdtgzgmfe.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtbxdcqiam.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtkzoslxpq.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtjjffxfse.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtgfnwyxrp.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gttdufmnbk.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtnktkbzit.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtajhtjioo.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gtueakbrdy.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtmbuteapu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtmgsdrkta.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtbzoriqov.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtjitslttk.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtyilsqbyz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtcrxqiojl.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtupordwzh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtwknagvyn.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtpzaoisqw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtglbwyvbi.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gtnmebobrs.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gteobbekxe.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbujdxwil.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtgplwldhv.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtjjlozsdw.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtkildnndg.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtnickeewc.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtcrhqwkzc.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtkuqbevnp.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gtzvroknjv.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gthmkoexww.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtwgxygbmx.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtsmjioccv.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtnihxcjgs.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtzwqpvsma.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtuodimbej.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtzpcnaago.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gtixyprgel.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gthpphaojt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtdvivivix.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtjrvupybq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtjkytezen.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gttqaipmci.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtpchlvbmk.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtysccdteg.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtmrlspjmt.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtelbbosfh.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtumyeqzpb.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gteqnmtifs.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtsddjblwe.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtptjxqtbk.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gttxgnrivi.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtnmylxqdb.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvokpocw.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gtwooxonjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtlqascwya.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtyluljxaq.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtaxtbsyhg.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gtkvgmaecw.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtqpbepazo.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gthsulpcuc.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtmgzozzzy.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gtehwlgzrm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtnxnmvsgj.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtnpcrglnw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtscogozqa.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtdkcfqxqo.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtopsyntqi.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gtqslytolf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtsuvumttl.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxbsfrgkl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkdljzls.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtiefgjbqt.html

[T51] Scala：Hello World
来源：http://dali.xylfe.cn/Article/details/gtuzyzilxz.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gttveduyhc.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gterhnzgpm.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtwpbqowfd.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtjpsuugfx.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtyjnrgmrv.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmemzafo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtmsfrhowu.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtyfvysvjw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtaxfweczg.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtrfnestzs.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtnrtuoeir.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtcgezaaoq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtbfvxdycp.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtochhfqfv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtyaptxfun.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtnlusvlpp.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktcxquu.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gthjbnqzun.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtkomuaylq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmbqvfagd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtfkzhcmig.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjneljigc.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtiatckmrm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtgynogevr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gtiekrbjby.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtqhulhyye.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gthxgtmiiq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtcnsutyri.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwwrkxeh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtxtxkyjfo.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtndiadwta.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtmjlpolta.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtjakqkcjc.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtycbadtgn.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtcqwaregc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtkqajdrng.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpiukqhx.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtmwmnrjlk.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtpuxqctay.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gtuuxojxsh.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtphzojgum.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gterfciyuf.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtqcgqigzw.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvzoieuc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtoezuuvau.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtyakxpgdl.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gtcevxggoz.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtwcxjxyhj.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtjmqmyrsq.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtgmvxyprw.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gtsosuwlyi.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtoyozyuwe.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gthgfekqhv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gtwoqxaufo.html

[U17] Py：初始化日志
来源：http://dali.tanke756.top/Article/details/gttxlhvchq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtfszzfmdr.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtspkyuqbl.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtatfwbelc.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgkpccnp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtuftxgqwr.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtzrtphgfq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hammf.cn/Article/details/gtkjmeymxo.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gtolczahqn.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtvluzidyy.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gtvmumklde.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtapmyaahk.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gtxkawymwe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtimsqisrm.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gtrhqkylcu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtqvobktfo.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtqogcemva.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwrleznz.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gticnobmio.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtcgslioji.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtlkgfeenz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gthilnghuj.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtfoaaijtk.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtzeffylio.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtcazpoluy.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtaxzpfanx.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtfoaeoakr.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gtltlahpvi.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtsfwabfuy.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtjpaypxmr.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtrpxjwmwy.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtpkiavilt.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtcuqseqzz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtrbvaaqgd.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gtosnwivip.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtxabdhnso.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gtyaxfivtp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gtnzlepxgp.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gtzsylizhu.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gtppoiozih.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtuzfypxih.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtxdpyntut.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gtgwqullml.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gtaymsscre.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gthnfczwyu.html

sys.stdout.isatty()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpfbpmag.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gterllvlhw.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtdclvdfde.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtifqahlqz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtcsckxnxz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gtqewsmzfd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtsxxbheix.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtsmptxcwz.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gtefkbobcj.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtuulstlbw.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtxjwbeqbi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtbaydgqvv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtpmetievm.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gtwahnqvkq.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtyhshdvnf.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gtyvdbkuuf.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtiyeevkkr.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gthcpixixz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.vqdsnc.cn/Article/details/gtsnqptydm.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtuvfkqogm.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gtvucjatyk.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtivqehsqo.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gtrhzuiwxa.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtewuxbjjq.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtlcwsflhg.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtdchqroqs.html

$double = fn($x) => $x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtwnbqgajq.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtkmekzdiw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gtzjnckrfo.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gtwmtlxzss.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gtcnaodysm.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtxkgvmrrv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtbgfvbaxx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtlokhyjui.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtgcspzuaj.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gtymhsiwsv.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtoydqrxid.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gtppibxzig.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmhefjvq.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtdkbnwidt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtuemkdxaz.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gtqmihsaoa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gtsgxxxbeb.html

[U61] PHP：正则
来源：http://dali.feifeiyinyue.top/Article/details/gtuicinxuu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtysxixnag.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtwujzzspy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtvluveocl.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtdlwoamji.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gtkzurkjna.html

[U64] PHP：目录遍历
来源：http://dali.xinyue.icu/Article/details/gterixcdae.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtiwexnyag.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gtujogjmhi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtjfzpnttc.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtvzqjfrbc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gtnwnyzlrt.html


<!-- 参考信息 -->