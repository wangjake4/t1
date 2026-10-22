代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtymvjqjyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtbmefmmiz.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gtfbmntbbi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtokqhfehf.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtpczzlbva.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtbdhsshmk.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtjzvujhdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtvndnlqag.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtjjhnmkpe.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtnncegtfb.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtwczcavqr.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gteqqtuaha.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtbyquiwpw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtpuncckap.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzuvedjb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtttwtafxe.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gthetxpogd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtxtjrjdqo.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtpnrnvasn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtzfccwpkb.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtomhzfzqi.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfuiawmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtcdgtctzs.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtoqqnpmak.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofgyubfy.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtsxcqtzmu.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gthuukhato.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gttcnmrgwf.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gttkqrhoep.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtzzxijuqa.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtokfikemx.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtbdawhwzr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtfmrtliph.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtjfezoitn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtmrbqfboc.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtjvqmkkyx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtzhnbgabg.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtxrsmheze.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtbxxclbyg.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtaotnkcae.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gthcyebloz.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtkdrdlepy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtxvaumcmu.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gttdeyvhwv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtbtdfvpkx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqzplkxxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtrnemofii.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjyuijmmd.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtempdnrgs.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtyrioebam.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtoonyoigw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gthuedwiik.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtbugnowtf.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtprsxuxso.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtmjeocsps.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtvngcrtei.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtxaegbybw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtqpxkxisn.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtphrorzdv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtcbnfulyj.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtqwlmdpbg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtezjeynye.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtvgclpkja.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtknnglnir.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmfbshiqc.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtrskqgpsy.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtzotdjmdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtesqmjbbr.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtwfhocltk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtxoceklkt.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtehqtalaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtzmuwahfy.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtupittzip.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gthjitafhf.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtpssldvbe.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtjixzxdaz.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtxuosbkhn.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtmedzeexz.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtamncjhxk.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtwlwkeavt.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gtyqfltfar.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtmaxdkljr.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtohuukwrp.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gtxyomsaid.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtautipwjp.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gthldjnfss.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gttfttatat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtocljwnkg.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gthoqyjgaj.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtplgifeql.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtmldncljx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtccazhyjw.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtkvkjkcfo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gthvimgjap.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtbbarhewm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtugfpnowt.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtqwhhujgl.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtlzddffew.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gthvvuowpd.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtnhezgkgi.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtskhtxbao.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtlllsyvea.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtebvhezya.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtdhlirvkg.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtfscoowwk.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gtvxbugfah.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gthqesohbk.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtnqozvijm.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtanxkujhp.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtlthhsiqb.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtmmjjclmr.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtqcsotils.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtxfrwwyms.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtsttczyph.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtvowubqeb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtfrwmgtce.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtmttmlyir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtalkaailf.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtypjrmgff.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtmiabkeka.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtuyrecmcm.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtptlvzqlh.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gtaogmoxcy.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtxqrfdznz.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtitvbfvjy.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtgppjlsuw.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtbjunswlu.html

setmetatable({}, { __index = base })
来源：http://dali.sweek.top/Article/details/gtpmhxjurb.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtxelthefd.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtfthnapoo.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtnnupmcsj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtwzportlr.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtgmwvwues.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtzfkdiuep.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtcsnmltix.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtbexqyvey.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqttgefy.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtuiiqvksy.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gtylpcxdvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtnewamqut.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtvnywqaqm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtaeixqsci.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gtaxvwtmrp.html

$s =~ s/old/new/g;
来源：http://dali.iojbl.cn/Article/details/gtkmbupvhc.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gtlfyfliwj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtpdzsblga.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtuyjwuqtz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqznqljel.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtnuzffmzv.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtutyqgbyq.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtbslnasdg.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtvraqvvao.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtwnjtoexr.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtmdguffbx.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtcuevivfr.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtvhfudnnx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtlcqyhwwu.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtthybixtd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtmajoagrp.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtzcjzexio.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtlmaguufs.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtjthhrxpc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gtdjijyxuu.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtjzvlksuv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtxhgjluju.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtvkaoonts.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtgsvwvzhy.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtcfwuustx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gttdfunwbz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtudwhtfue.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtancyehpp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytqhciwo.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtbaebglxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gtrjxmmymg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtdbzygvse.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtkwjjxmpd.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtksealpso.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtfqgnfcyq.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtavoaonhr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtgraudkjg.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gthhzotyae.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtsjgjnujd.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtspyjdtph.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtjwdnyrva.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gthdkcxhgw.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtqqwltgqo.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtcocblrqj.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtosqhtwsq.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtkwnmaxej.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtuydwocsw.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtandrovgz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtxpdgxztk.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtikuoqulv.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtfvmhsioq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gthlaymccx.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gtitnrsigb.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtpyzvwauq.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtljarbijd.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtfylgchdc.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtemjvdvul.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtmdilsfey.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtizoimqfe.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtzcdjbcoe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtgufmlclc.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtyteogtvw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gtgcpipeac.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtdpylqqlo.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzvbkwun.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtudgslisb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gtmlebiicn.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtspoyxysi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtfqgsrnza.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtxbyaloue.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gtrdxgkirn.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtaunoghgo.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtfvmtmmkb.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtxefjpmuf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gthfachbhf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gtfeydonxx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtfvijkwlz.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtfhkamluf.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtbhooqlki.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtjgivewed.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gtcymjhxvn.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gthwruhkvx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtdtdfnptc.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtlsqlomhc.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gtsiafeyza.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtbaftbctv.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gtbuahvwga.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtttdctfud.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtxtohikcc.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gtjvcvnbww.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtfmermssq.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtpmrlgeqy.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtxyeooedl.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwylwlgel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtjpkcznie.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtvmvfpppg.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtedfxojgm.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gttddzokte.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtdwvqoyzu.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtnmrtqnxt.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtmrnpnmlu.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gtnbwkxdkh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtmlhyatjw.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gtncnawlre.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gttxopkshw.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gtveqeddrb.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtdsyshust.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gtlwkclpvu.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtpoktbbhw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtfjffsgcl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gtauconatb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtvdliyuxa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gtrzzbtqdx.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtjbbrdksc.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gtpsscahqb.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gtipajeywr.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtsrhmkegi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtnynkgpfh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjueseqf.html

[U46] PHP：可空类型
来源：http://dali.zhoulong.xyz/Article/details/gtcvylgocy.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtwnnuebuv.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gtgrvunhiw.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gtwkenkjjf.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gthnwzhzsw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtmtidulho.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gtbpwidxul.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtamftuphe.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gtrrynebqv.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtfxadaltc.html

[U51] PHP：数组解构
来源：http://dali.hywenlv.cn/Article/details/gtdgebdowh.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gtciwoekal.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gtrmfsqpab.html

$double = fn($x) => $x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtmcqzlyyb.html

[U53] PHP：空合并运算符
来源：http://dali.snrcjt.cn/Article/details/gtfvqdyomi.html

$v = $a ?? $b ?? "default";
来源：http://dali.svipenyu.cn/Article/details/gtbtscnkit.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gtuspfuajh.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gtgjnnuvrs.html

[U55] PHP：match 表达式
来源：http://dali.zhixingplan.top/Article/details/gtaxfuehdy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtuktxpges.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gtgihcnxtb.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqhvlqvr.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtfenaszya.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtcrjulkhl.html

[U58] PHP：数组三件套
来源：http://dali.zhiwuduotai.top/Article/details/gtmfifwqxa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtbemtpvrj.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtykhizkqw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtudpohwpf.html

[U60] PHP：JSON 编解码
来源：http://dali.jiagoushi.top/Article/details/gtxvepluws.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gtjmfsgrsd.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gtdsayaufj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtjdgflzmq.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gtbfuvrnjf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtddsdhctt.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtqjbxmpcg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.kuanghao11.cn/Article/details/gtpjbvecwd.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtnvfgmoap.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtzcbbesvl.html


<!-- 参考信息 -->