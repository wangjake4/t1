代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gt2vmaieosi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2vfqtbwfm.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2xrakntdu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gt2aonnbvos.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yygluepa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2jnnyrzox.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2txjvxocr.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2jyporzun.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2fxielnfs.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gt2ldaayfcf.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2oqzngflx.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gt2tabqgxxa.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2syrctwre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2xgstvrvb.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2tnhkyqjs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2guljapsk.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2axfcafqx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdrzwoif.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2ixwojntq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2umvuujxh.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2wqmsyglu.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2ythzmqhw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2azuxfhrl.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gt2ycvxkeuo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2kuzdtozc.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gt2emqcqtqx.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2ecqinwbj.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2mphqexrm.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2gxwknzzm.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2xbezkrqd.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2ayznvlad.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2pmezrkaz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gt2mlsjskfh.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2gmfvzmfa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2xskssueh.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2tfcftowm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gt2tbrfduao.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gt2ystbsfub.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2nfyxxhjw.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uabekzzs.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gt2qbmndyyi.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2mmuefcji.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvlgpvhy.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gt2tsholqdf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2zwamjztj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2nxtolorp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2ebcbqter.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qapruzxr.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2kirryoiv.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2idoivqxr.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljwpioaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2fhweclue.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkhsyila.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2ptxugmim.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2rfgiyixn.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gt2yygeqjtg.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2dzcejodg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gt2sypeqgjm.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gt2revwtqnt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzouuoxc.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2rvkrwplg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2dswmsihh.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2kjkrencg.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2kfsfulcp.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gt2nqcepehl.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gt2kbvehmmm.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2encypsuc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gt2cppanbph.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2enlhwfhe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gt2aujzdebf.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gt2bnkagsuq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2ktfemegj.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2fzwxgkpy.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gt2xbqkmmqb.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gt2aaxrsnal.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2dxpubjbq.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzioxdvv.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2teiuefag.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gt2ujxefikg.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyxuzaze.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2qndfkgvl.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2misgijut.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2lkfvlcgy.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2twkjmsky.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gt2uiydjmev.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2rfcntqjp.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egorgpgi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2kdfuhgij.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gt2djogwfvq.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2qlkedlrd.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2raznlppx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gt2xvtnlpgx.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gt2glfyzlfu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2dysyehxt.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gt2nmkcdnbw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2nvhjonyo.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2ovmmfzek.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2empdolpr.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2bcdxndsa.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gt2xtrwuugk.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gt2kqjrqxwe.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gt2jkyinwau.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gt2kjtbjbrs.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2cafgjifv.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gt2geqndlbv.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2wreufwtt.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2jsotdcen.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gt2enugifsx.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2tjgoidpb.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2ojqccyku.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2hiqydxiy.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gt2hahvgpct.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbhamvtr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gt2xkxufcog.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2krhpneyd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gt2sgfrcvab.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2njcmswmr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gt2qftxjcda.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsysamnl.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2gjvuztwy.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2vjxhbagp.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gt2sjpevqrb.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2odptvpxz.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2sycrprbk.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2hilubeqd.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2gsaoclzn.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gt2tqdfxrkn.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gt2tvfrfzoc.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ztllpqhb.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gt2hwuwjhaf.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gt2eromdasz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bigkhlxe.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkbqewba.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gt2ziaskfoh.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gt2azoymggu.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zifhjxik.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2wiyyqhmn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ugnuokdn.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2gifutids.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gt2srdctdxn.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcokinyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2oawnpiac.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gt2bkfdyqoq.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gt2gxwdtcel.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2khdzuhxr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2foxtdfyf.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2nirkrokm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gt2eomuscab.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gt2fxjlrlqm.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gt2eskuxfkf.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2uenlrbnh.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2htgwsysr.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2obgnwsgu.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2thbgxqvy.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2jomaxnfg.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2keuruqpw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2kkintxnn.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2mjodtygq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2xehsdjmb.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gt2caqbntui.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2svlxsmyh.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2wqijajfe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gt2adakcgft.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsgzxcnc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gt2cazlnqsz.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2exahvwye.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2aajaozre.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gt2kgacskwu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.havefunace.top/Article/details/gt2ekdwfyjd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lqfsgwfv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2izrzoxvc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pqgyeaeb.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gt2ispldvfb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gt2bkzkutuy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gt2gnoiaogb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2jztggigj.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfygytnp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2upwrgwgy.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gt2iceofeuu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gt2lmdkxaqk.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gt2yqbwyslu.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxuamjoz.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gt2eslwghdc.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gt2egurefab.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gt2jomfyzqq.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gt2dcikgdha.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2ahrycife.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkzgjhyn.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gt2nhirixnz.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptxmvceb.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpyiqfjy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrxtegjg.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gt2btpzrtdi.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eihanapx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gt2virjonwd.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gt2qgkktflv.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gt2tdinrqpk.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gt2ezvarswu.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gt2rafciaeu.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gt2bftxkqjv.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gt2tzwmzsim.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxopoxpc.html

[U16] Py：命令行参数解析
来源：http://dali.0kj1m.cn/Article/details/gt2cxsxhhap.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gt2vqeorrbk.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2muxzccps.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gt2breznyna.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gt2owvbqtmn.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2mlwdfymo.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gt2dhlsghdr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2fvefxmbp.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gt2gflxxowe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gt2npntlaoj.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gt2isucnwxi.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipanwiiu.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2elvooaxi.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2vvtzgpeg.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhubraub.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2kstjguqq.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gt2fpikkfbk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejrawldb.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gt2owbtuddd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2adtaqtul.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gt2atfpoysa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzcicxoh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjmuwdk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gt2txnzprbf.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2atvwdaop.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2yuxttvtd.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gt2xogouqap.html

@property 与 @x.setter 配合
来源：http://dali.ybcxt.top/Article/details/gt2jyrmhart.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2eoekclky.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gt2pwmtbfvz.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2qxcfqzux.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gt2ajbtjurw.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2bkoamjvp.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2lfnwmojs.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gt2poqttwyj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gt2tmsupafr.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gt2avqxgndk.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gt2bbpkehkp.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gt2ieccuvwm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenzaomai.com/Article/details/gt2trxjixxe.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2abzjivgx.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gt2bbwlvctv.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gt2ygzybtua.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwsadhkc.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gt2pljkikem.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gt2tmqqeham.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gt2alnvdkbp.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gt2hnpasnbu.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2bocyoipi.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2dhcqdwkf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2algzzlwz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsmhrvou.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dashuyun.cn/Article/details/gt2swpiwhnb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ectptmge.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gt2ifscouhr.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gt2edhskvtv.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jciekbvk.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gt2tjgdxgyj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gt2bnjbgyns.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2ipmxirwx.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gt2rsdyrpvv.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gt2vawiplbd.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gt2onyboral.html

int|string $id
来源：http://dali.tanke756.top/Article/details/gt2fbdbsfkt.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gt2ibfhmzgm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gt2tkpvkfze.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gt2oxlljgbs.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gt2tvssxyfb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gt2doevngim.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gt2ezhwamte.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gt2uicghjjs.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gt2ntozqapb.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2khnmndta.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqclgrap.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gt2lrfbxbdx.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gt2aeiunvms.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gt2gkerwxfr.html

$obj?->method()
来源：http://dali.yuxming.cn/Article/details/gt2grxyredg.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gt2egoaybnt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvutcqg.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gt2rekoilry.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2hdfikrck.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2dpdnrmmc.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2alfquunz.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2cajyzumq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2elkctgle.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gt2wszrxgdv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2mjgjuuvy.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gt2orbjpxqy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2iwkbxzkl.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2ywkpshlb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2xzurfpuy.html

[U62] PHP：日期对象
来源：http://dali.ppjwa.cn/Article/details/gt2uvcognsf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gt2fmighkqw.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gt2zamxpaqv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gt2uhwcolox.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2pupgeqyj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gt2wihbqqpe.html


<!-- 参考信息 -->