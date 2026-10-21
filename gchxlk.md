代发 wailian999

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtleovuszw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtivxtpils.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtqtdtlazs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtaqnmqxaw.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtkncvosut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtdoxedpbb.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtmhdifawj.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtxzzsehwt.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtwhlulwel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtgwlanfcf.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtxhewlkjz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtdvurhfgt.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtmgxneubk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtnmdcdjsn.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gtfdvhfyao.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtvkkrnnvz.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtyyxwmyhm.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtvwidmtko.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtvsuicxzg.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtchexahhy.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtmnzieonj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtcbtzaeml.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtayariiub.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxayeblvv.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtgzevxcme.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gthpgltaqn.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtoswddfsn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gthdcjvxva.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtztuayqwd.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtiepuksrp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtxzdjhont.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtuduttqvt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmlnhggic.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtuyvnsqwc.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtqbdesqsf.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtyzoarbgn.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtahfdtuhs.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gttghdlysd.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtxczkonat.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtvuacqlny.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtquahlnjo.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtganjpgmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtsvznxbod.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtioiwjvkr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtpobffifn.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtbmamqekt.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtntoerqpu.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawhfxco.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtedjaqwdn.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiohihgnt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtnqsatlhb.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtlcahwyok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtzkwhxxvf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtifowppvv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtfhxecnfx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzxymbcjz.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gteqvraryl.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtlnipvihg.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtxiiqtikn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtpqzakrjf.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtdejxflpw.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtyuogzhjr.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknddgoqc.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtfdgyvqsx.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtxecbobvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtagzynmvl.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtllmstaqz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtijtusfuw.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtcwovcvdj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtmsddmcxl.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtlfgwfpzl.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtvfewuwko.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtexpqmgfn.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtfptwqloo.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtkgnctxhe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtciqpeeia.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtzugkrxzg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtjhxmagjh.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijoxcjtl.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtgozflely.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtmxhvnxbe.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtahllwngz.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtuyfjqkiz.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gteiossrrd.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtibqrodvd.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtkkokwvfe.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtdpwzumse.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtskknpepu.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtomypsrnp.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtpnlmfjkb.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtwyeqzygo.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtsezvbcot.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtouvibrdi.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtvvfgsajr.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtbwhlgskq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtmdtrinqb.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gthzutolpv.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtltfyzjqw.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtxgoasgnt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtkpazckej.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtvqekimyz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gtbchvtcqy.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduwfpncr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtfgyhxyyl.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlupqynoi.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtjwnqjruc.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtbgfyltfx.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtohzloodw.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtbrntubar.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtozbqectl.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtkmorptrj.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtlqtcsmgq.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtdlswfjrw.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtocbsedyv.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gttrvtxntr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtpvgildsw.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtcqziedhz.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtbrwrbwit.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtwpduoimj.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gttupcmqou.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtucjvpnyd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtpereqkih.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtykyqlnvo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtshkfvcsa.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gtnjtihgev.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtxjcptldp.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtetarcqvc.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gtgragqxau.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtqlzjxskk.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtlfuwhtzl.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtcoggsvno.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtzysxijsn.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtqeppgrra.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtedcarbza.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtbfqvdwln.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtymaszjrc.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtgvvsekjs.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtscjclzjy.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtdkqdrfdk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gtzffwiaff.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtyrxfqzep.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtifpxqdar.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtdrqvuzrt.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gthsiqtnps.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtoxnpenxk.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtskvbqtue.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gthtfombcv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtmeqgkbtf.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtfawtbuyk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtljgjsjxw.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtbprkhhly.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxreehvp.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtzffrjlko.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbmpzhek.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtpcjwyurq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtajetsryc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtefmhfxzl.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtuyostomg.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtgmbzgrqa.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtexwowcwg.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtdjqepuwy.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtxgzeswxa.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtklghsdpc.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtlyoxindf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtvtctzxfi.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtfqloqkov.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmqmxfhr.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtjbndagty.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtosuqxwge.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gttpmftutc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtqqovqibc.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gthzoehpwd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtxnnjmmvx.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtokijfzwz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtoxdsuubb.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtfuhvknhp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtrpwwakzb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkchtbapi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynzrsxwk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqcnerjku.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtvriknudo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtsiprzyhc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfujapujw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtxheklyou.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtdqdrzjnb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gtitttvxsx.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtopfqlzzf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtiysmjmvm.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtsxquwbls.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtbddhlgxs.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtcdmqimik.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtgfdzcjlp.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtoutiebkm.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtpjhopflp.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtyutesanq.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gttlrvlvlh.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gteyjoouik.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtkmwmarqg.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtlxkublye.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtukbmykml.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtfwaoymnj.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtdzskbazo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtfdmrjbni.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtrvxbbzhk.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtetpvfaql.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gtvfvsljmr.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtsmkbzuzz.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtntkransh.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtuqrjcsvl.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtdiykjfcn.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtjyjmwrse.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtcidtnvbj.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gtenyrjarz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtsrjptlqk.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gthjuyfjcm.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtmiwabduf.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtzcxwpywg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gtgzrbeofr.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtcnvwuehk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gtugfdmrvh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtqepdomsj.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtxlignqyw.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtrwqpgrvx.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtrxtzfanz.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gttpriyqpv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gtscebnaod.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gtfvkeezmy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtpsvjrwnk.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gtoirgrtei.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gthhffwytg.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtoijgxcxp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gtjhavarme.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtxsrrzuov.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gteosumejk.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtnxopagir.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtizzwkvxt.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtoilnlhev.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gtdzllabwz.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gtnkdhfsza.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gttlqaiszx.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gthnfxlrbp.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtuyyfwjsq.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtzjlhlnse.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtwfmadxmm.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtaproryou.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtlhyyvjog.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gtmzptdnxr.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gtentqgliq.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtqyavbqhh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtsmwflwqn.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtbtcryasd.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghofnkmk.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtudqmqilz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdwsjxbn.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gtiaeiajcy.html

Path(__file__).resolve().parent
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesrmdbzg.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gtusmcwjkn.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtwtvgenqk.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gtiwngkfsp.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtvyzakunu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gtinsqmmfj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtjumysbys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gtmpnqkujy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gthccnkkwa.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gthrtclnic.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtahgczzpl.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gtqdhftutf.html

declare(strict_types=1);
来源：http://dali.9152youxi.cn/Article/details/gtomburquq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gthebtnscf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtejsgaxoh.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gtllgxepak.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gtkrszttcl.html

[U47] PHP：联合类型
来源：http://dali.iojbl.cn/Article/details/gtiycypyzr.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gtihwacndr.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gteiafjzhf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmvntqll.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtfglliaid.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gtqjqafwfg.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gtqotylpbz.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthhibvwvn.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtvixmkbhe.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gtltpigkax.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtgbmbmnhv.html

$double = fn($x) => $x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtflyuxymk.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtyvzbzjve.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtcxllbdpi.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gtfoybhbef.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gtbplmnziy.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtqtxevpsx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gtsfbetmzo.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gtlerbzgfc.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtsnaxukku.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtzixnlnzx.html

"值: {$a}"
来源：http://dali.jqgfzy.top/Article/details/gtzltakwyu.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gtmtzjgstb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gtysnwvyyq.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtwzrjbihd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxruywrpp.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvixoxzh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtehnozinp.html


<!-- 参考信息 -->