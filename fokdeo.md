代发 wailian999

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gt2mczaxqxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gt2gmabezqu.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nztkvlzi.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldcjfxfi.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gt2etktrqee.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2gdfiupoj.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2qvdpqjgl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gt2uzwicknh.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2efdccygo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2mkwivvaw.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2vbbuxsfu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlnwzkyy.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2rjwhphmh.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gt2svsmdqhf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gt2oycqlxta.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2opvurcrf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2clhyknpd.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2ejdkqogm.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2plqlcbvx.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2jezjkbol.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2ebojbjqs.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gt2ifwnixig.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2kvbipxwi.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2itlxnszk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2lcfgcuev.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2fqqnxyds.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2sbiwcufr.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gt2osvitisw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gt2xdqcfwqb.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gt2btllxzas.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2rcpkloxl.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2lhaayhia.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2ljhviwcu.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2bkfyboas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gt2amuoqjoq.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2xofrpypt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjtatnlj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yuboqiwq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gt2hrgqiygb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2rdaytgku.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iilbbzsw.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2xypmmiis.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2cebypotw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2uhfoggvl.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogyvzgzv.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2nugfewnh.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2vtucvyqo.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gt2bmgdnlqd.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2rzbodxuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gt2tisvctlv.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2axzkgmzh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2wkpqemgd.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gt2iepxzkiy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2qbaxspro.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2eamzptkv.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2lagxygbh.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2gmthppcv.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gt2ypuxcdyi.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2fybupphp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gt2fckpuvib.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2fjargjsi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2lbtwgdnp.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgegocvs.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2zohnmcrc.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2srncyowg.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gt2sswmpwmw.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2ptaxwlpa.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2rqmiotrl.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2gbviaibj.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gt2arqjswtm.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2cqukhaeh.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2fvjsanbn.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gt2podohsxc.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzbxmjhy.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2ljzklaoy.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2xzlrmluc.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2trdlejwk.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2ltbuoowt.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxhjyuuw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gt2thddidhw.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gt2mzmhtogd.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gt2mvrvecqu.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzxsphmy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gt2ufbxkhnz.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gt2nekvyqpd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2zozngdwg.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2zjqrsmnm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2inoyadcp.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgcqxzze.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2gesmyrrv.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydtujqdk.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2ikigqiwt.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2tkbkirff.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gt2pfzfmrsu.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gt2bxxkhrbj.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2nbipnwhx.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2bcsqznbd.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2husncscz.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2jprzqxbi.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gt2qduegvya.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2bztmyvfo.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybpodehq.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gt2tyzmgbty.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ymsbmqnf.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gt2ahuumfyy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gt2ojxdrjwx.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsfarbjq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2nhejgzeb.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gt2rutmhxwa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2awuskybs.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvhkimkh.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gt2lgposrbb.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2jntzcois.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2uzeekmin.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gt2viuzpgeb.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gt2ssdhufux.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2uwzndrte.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gt2kjdbfxwp.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2ixgfxwcw.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gt2bqkkbpbz.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2mpokjvha.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2ltkcfgfy.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2unathbzf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gt2gvndhtze.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2tnuhlros.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gt2yfwxxfgs.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrtopmct.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gt2hknadfhs.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmkidlou.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gt2ymzokhnp.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gt2admsrqij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcqqelel.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2hdaimsxf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gt2dwagneoe.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhibglut.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gt2vzehsygd.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2ccogyzmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2fikaguwh.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2flojfflj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gt2xwigdhgb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfwhezei.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdzxecjg.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2iymxanpz.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2jvqrgzwe.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gt2ubdqlsof.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2hjiuexwl.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2qylghsoe.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjbejrwa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gt2vnwiizmz.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2egjsezle.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2ybnnllsj.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwqbnigm.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2xugdwebs.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2wqpkwanh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2dtgauhqp.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2uudmiqho.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gt2awosxhak.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2ripzvtlt.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xatgurso.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2azvavupv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gt2mvjhytxf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nxzlbuij.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2rmzwpkyl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pyseoeif.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gt2zkngomsu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxyleokn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gt2axlzagqr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2uybbsdih.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gt2khwsurru.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2jjbquknt.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gt2rdtptfto.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2sdnodngc.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gt2emzckfsi.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2chcqbwki.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gt2kohlkyyf.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gt2irmcimur.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gt2kkdelbea.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gt2qecccije.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gt2zbxpkcfr.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gt2wpjbajcw.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gt2eoptykts.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gt2myqwlbxk.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gt2zqmszmzn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2kqyyyrpt.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gt2blqvgcxu.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2akzzlmmj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhixingplan.top/Article/details/gt2axtmpuvw.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uudnwbtr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyudsfy.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gt2ymnpevtl.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2odyvjgsm.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2lwkihsjf.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gt2uxfzcpst.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2vhekntls.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gt2krorfwpo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2myewqmnu.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gt2qpqtfuum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gt2kroyowex.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gt2urgvcuxa.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2rlmwfmxn.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gt2kozwrjwg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gt2xyjxdbgc.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gt2mjvbplkv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gt2bthbchci.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2rosxpmeb.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2fhzoiahs.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gt2swzkuswo.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gt2xdjxznft.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gt2tsonwwhl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2axaiuvqh.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2gzzlhomq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2kfvwwdti.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gt2cwmfsgto.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gt2bhuftrbo.html

[U26] Py：并发下载
来源：http://dali.meibo888.top/Article/details/gt2pjiqjkxq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gt2pdzadjhy.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gt2vlxmgdpw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gt2tghqnopr.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gt2lhjbnrav.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gt2bjngxsjg.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gt2hkfbsqkq.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gt2nlzpggyf.html

[U30] Py：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2hwjjpemz.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2cpqgpbue.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gt2awbtzduz.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2iaregnil.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkqukwko.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gt2ulyuerqz.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2xinzuehz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gt2ejkismse.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gt2afkeacaq.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2qjqyezyk.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpxszgvv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gt2wuogpxlm.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2airnoldl.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gt2yojtyzsi.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gt2crmyxpdo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gt2ajmyjzec.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gt2eyxvimmr.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2wnbzdxsd.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gt2irtjiigv.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gt2iqjlxuwr.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gt2jpoktqam.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2rtvtqjrf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyzfaysd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gt2fzqzypct.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gt2orpxtofg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2ylzibzsy.html

[U43] PHP：声明命名空间
来源：http://dali.redwolf501.top/Article/details/gt2laemvqqx.html

namespace App\Http;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcjfivmo.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2colinyea.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gt2ummfdnyi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkwlyhof.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oademeim.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gt2tfkwsoou.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gt2pluhjadm.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gt2rkwygaft.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2eozqywbk.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gt2jrienytb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzsxwhvg.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gt2mtojszhz.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gt2ewnkprha.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gt2xrauszmo.html

public function __construct(private int $id) {}
来源：http://dali.cashguo.top/Article/details/gt2daaioauk.html

[U51] PHP：数组解构
来源：http://dali.jinqigufen.top/Article/details/gt2ekewfidq.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gt2ocjkhwgh.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2pwctiayi.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2vvqgywyn.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwlqggrc.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gt2pkerdkik.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyqavjog.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuiziffy.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2avqblvzx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2ldiqberd.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2kjykoxjm.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2iodwwham.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2hasepivz.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2ypqqqnuh.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gt2xecurxpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangdashe.top/Article/details/gt2csljnvfx.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gt2znjhfhlh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwnzygxe.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gt2xtxoalff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klyuqomg.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gt2fczbsotk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2atubwfri.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gt2hzztaqme.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewopgzee.html

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyyeoiol.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gt2uuxxjbhz.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gt2ukeecemm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjltiyuc.html

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gt2botgzulq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2okixwkbp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gt2mktqpgvq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gt2pixuotox.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gt2rtkuuylo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zdqjudy.top/Article/details/gt2bagiehjp.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gt2gpmiebkq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gt2qwhzxvkl.html


<!-- 参考信息 -->