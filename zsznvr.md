代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2lofbzayc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gt2aenzzqmt.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gt2hmevvojq.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gt2bkfwvanh.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gt2lowhfwhh.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uoloikbi.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gt2njqzikhn.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2hcbinnzn.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2xtharfff.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2ksuiluau.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2bpsbztrt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owbyovjy.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2fnefdqtr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gt2hvcdqoce.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2qzahzmpz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2dwobogsw.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2qxocbbqq.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gt2dyxhuxbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2plieltkf.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2vnzsgucw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2sarqwroq.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2gspoqqmn.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2mkkvqaho.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2ifcmukhb.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2cmwnwxor.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2ndndxlfg.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2iimbhlrn.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2mkxfauoa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgxbcyfd.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gt2vhyiapvr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2suzwyfsx.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2sowrttky.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2lcbhagqa.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gt2ctecnjdh.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gt2essneegf.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2wqeqkuzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gt2wgilyuff.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gt2fiezkkva.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gt2vsoehxob.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2dupnmxwh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2gevbivyd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rznlendn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2wvoevtez.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2epaoacww.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2sqjxvnnh.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2efxclgdt.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2sgclotev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2ovqxwlbp.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2xjxjhbfa.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2zgsvlpks.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgvtkvwq.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2skdtvngh.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2fisbxwnd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2wmguibdz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jbouevzi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2nooucaxu.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2kyamwpeg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2erhoyyey.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2frkhzhff.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2melevdbp.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gt2devclwfh.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2hnsznwzc.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2auorgwyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2guasdzet.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2kibilsot.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2mzjugjel.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2gjtvteub.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2dtdxouei.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2xvcbdfhd.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ixkylbkj.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2qiukdrqw.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2dzielzkp.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gt2qnzybuwp.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2shctbweg.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2ejuejbff.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2mpcvyjhu.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2ixkdnmua.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2rteglljk.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pozacyqw.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgchsflu.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2ieqxlmee.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2kypeaxfg.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2avntptiq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gt2wlorozru.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2qnvixqpe.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gt2xnkcibps.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gt2koyawuli.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gt2ddtnwnpe.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gt2rwlaxvsl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gt2wabfjcif.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2yrisysau.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2cqoretze.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gt2efomzydc.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gt2zckjvipx.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gt2wyehhnzg.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kroxpbnn.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2qfidakqd.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gt2qlyamhha.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2lewkjklw.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2sewbaitj.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gt2ibxejfxw.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2cgmnrodk.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2ujicnflw.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gt2elxohbby.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2crnbcozm.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2gdfmfhgr.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpfilkvm.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxqaccwg.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2aazqlhhx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gt2xxiqiulo.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2vdxztlyt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2jczvspuv.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gt2otykzyku.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gt2mqbmjcex.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2vrherlof.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gt2vhtiuiob.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2fqfwirtq.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gt2cnmxsfgk.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqqhmipe.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2yrxmnibp.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2ydfovrpc.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gt2kyibxuby.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gt2fvkfotfv.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2mxdaiiyt.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2onspxqvw.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gt2fowtnroj.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2vwynlmpa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gt2ciskxkqx.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbbtttgq.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2gihplaru.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gt2uhkavoan.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2xydsegpf.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gt2dkictpiy.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2fjqkfdvl.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gt2mzaoxbyg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ammlsyum.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gt2vmtvibag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gt2indctuzv.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gt2zqprtbvo.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gt2dydqdqzv.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2dwoxvanc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2pbuxxppj.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2mcvgirzi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2hvkloxzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhapbwqz.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2fktmkoqk.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjhdswvy.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2uocjvxri.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkpvjupb.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2vdkdglef.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2smdnubfi.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2hvwuidaw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2lfzbknto.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2occxvzwe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2wauyphns.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2iapvcvzd.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbfmrmzx.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2blechuog.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gt2rflhmrpm.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gt2jvibzbdb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2usrnvaeu.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2rrypxqyp.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2yktfvqxi.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2woijdjeh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gt2vuvyfffo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2msjbjogd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2pnzxjtcs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2aetmyyok.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2vgrsyemv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gt2fzmanupi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjepjvhs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2pyaocmdf.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gt2laqhjzdi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2qxhfblws.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2nzjdhabq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gt2dionjurd.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xodoxgvb.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2akwvopwj.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gt2mmqeehip.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gt2ydrwubfw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2surifqmd.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzlyotir.html

[U08] Py：展平二维列表
来源：http://dali.ydzc1.top/Article/details/gt2pcroxicw.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gt2irznihxm.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gt2whajvjaz.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2xcpczxkf.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2rouulmzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlhxjoia.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ftwtyohh.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gt2rgmonipt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gt2gsjtafzg.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gt2gyjizjlj.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2yeejrebz.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gt2zkutcqxr.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gt2bpbkrejk.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gt2vbcccogg.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gt2zjhajdzb.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gt2usqhwbaj.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgjfoado.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gt2lmdfpeuv.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gt2smldause.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gt2jmkguofv.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gt2dvmxhrvz.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2dwmbuavq.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2dkieeipm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2trlvhpmi.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2yymhtaxt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gt2mgthezqf.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcddhtrv.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gt2wrgfnihg.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gt2xwtxkvzb.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2bgubpoqh.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlwbehcp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gt2vkldgztd.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gt2skwshgci.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2zvetttmj.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2ffqbkxxx.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gt2vpakgruj.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gt2hfegjmcj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gt2wqdojapm.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gt2cenmfxxq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztndoikt.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gt2plkqjzhl.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxkycqyu.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2aeojdngi.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gt2gqewdtfa.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2ldyophgx.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gt2dmfpolgx.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gt2voiivsqq.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlurxhkt.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvuepwct.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2otdncvqc.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gt2gniqryah.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gt2nhnyvurk.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gt2suvlttxm.html

chardet.detect(raw)
来源：http://dali.quarkkingdee.top/Article/details/gt2bzpykmhm.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2lntwlvxu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gt2eudgflxb.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2afzamsvb.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gt2fmysqxnh.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gt2agftfmkc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gt2ndhwwqeh.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gt2cqukfjav.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gt2vlkvjwpb.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gt2ystuuclr.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gt2upvetxvx.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2tigzpdfi.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2vyjduloa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gt2iclvvuxy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvhirmdf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gt2vhyikjew.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gt2afnhkosv.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2ypnvucjm.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gt2gzyvvxue.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gt2xktqenqk.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2oloxzndf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gt2kclaylea.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eztuxrfl.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uisdiplx.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2exoblill.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2mmvirlbi.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gt2exjzirqp.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gt2obfncgvy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gt2bkosnzdm.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnxqwypo.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gt2pwhlnhmf.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gt2mkxsffou.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gt2tzcoezuc.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gt2gqcwbdnj.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2rlfvxoci.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2sbictxlt.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gt2vuqfixwe.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gt2pmllysqo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayzkybet.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gt2ptmvbebh.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gt2lmqgunnd.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aftlnory.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2bnfihlrc.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gt2ntzusope.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ysryxzbc.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2mastwkcn.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2hjhhponw.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gt2arilvwjj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2uwarjobp.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gt2fifojrqb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2lgfcgeui.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2xsfahttf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tanke756.top/Article/details/gt2lqxlasmy.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gt2urceeihg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqudxvli.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofmcfxph.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gt2klcyvjdc.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2runjyqfx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gt2lftfzdrq.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2guddjcdf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gt2xkrrsvdp.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omihlkdw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2qrqaktvy.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gt2nthtrvum.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gt2cpdkunhy.html


<!-- 参考信息 -->