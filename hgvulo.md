代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2bjcdxnnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2jkzygcwb.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2wccvmyev.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2vgocpzvx.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2chaovmav.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2zkkbpkqt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gt2sihqisdr.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2xxqsagwc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2sfyzflfy.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2qtcwvazp.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2xorfxzih.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gt2dzaddtwt.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2mfpmletb.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2sjdwoooo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlhrkbrg.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvvzubbz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gt2oijevysc.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2lsjoblyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2qnpgocgz.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2fgknbsoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fbpwkhvt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yetaqzdr.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2atjrflsg.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gt2axirxsqx.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2lfboykdq.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2dyxbmpas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gt2kasxwfpa.html

[S60] C++：遍历并删除元素
来源：http://dali.316326.xyz/Article/details/gt2pfpeboyr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2aurntgkj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jqxhiagr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2rjlgmenx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ldywbjbc.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2gtrbwrir.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2dhdqcyhq.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzfhwvjf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2toawlihy.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2uabuzrhb.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyxfllkh.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2vpeqdzyg.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2jouudwvt.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2fudiiptw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2qfditcha.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gt2qryfdpfb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2mgivrqny.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2opchjkzv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gt2xfaewltz.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2yfspwiva.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2oryjrbwr.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gt2jnovnxsd.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2spbgfeyw.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rejtsbte.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gt2tonqjbcw.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2xqbfphdr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2xvtyflil.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gt2ruejuhno.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2petwgaej.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2slsiqlyn.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gt2ptcsguoj.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gt2finseous.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2hktdwtzu.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gt2kvgnnrjg.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gt2oztxbcrl.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsujdcav.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2xcbxegas.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gt2ykjvxcup.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2nqclbion.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2xpiwxsyr.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gt2ontcfcvp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxofubd.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gt2fbkbhpao.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2qgdhgjnm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gt2msdcujtf.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gt2vikzcevo.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gt2nezmrixz.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2yglmtfzx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gt2erjrbxji.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2iieuibtz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gt2acwkwmib.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gt2oqrblrvf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2vpihnwam.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gt2fpwzkmrw.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfpjrwad.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gt2nlerhsyr.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2qzohmgvv.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2lfrssnnd.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2vxztvjrd.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2bcnfqgbu.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2yjbnargf.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2okgirnfj.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzrazsfj.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gt2wneioqnc.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlwolapf.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2nffmhbnf.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2zvjttihu.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2azhuaubt.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gt2tycyrkbx.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2wdlghscs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2ecyxhbeo.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2qhhddxqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2xztvyoun.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gt2yqcqxzth.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2nwkzaltq.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gt2yicevyrp.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2jinozahr.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2lmysduoh.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gt2evhdctex.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2fngqrhed.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gt2biahgogc.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzvpxpug.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2hjwxfvoa.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gt2ksjgnofr.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gt2rxywwcpr.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2otgxzfgo.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gt2smarrdpg.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2unbfqhsm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gt2ypzdifaq.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2dleysalx.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gt2pgwyzodz.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2mkzglwgs.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2aqhcoggb.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2meqiwfty.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gt2ttnaicap.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gt2ritimjlr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2apynziph.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2zmkvfqbn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2ogjfjisu.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2qbhvywgl.html

$s =~ s/old/new/g;
来源：http://dali.iojbl.cn/Article/details/gt2coxuxwpn.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2sscxcljz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2rpxvkuey.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2fwgblyza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gt2crsprcfi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ocgpprvc.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2jyzihhry.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2cjxmijoy.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gt2grqdyqll.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2fcngsauo.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2vjjxblnt.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2nabmrmfs.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2hccqtwri.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2kkrgbvqj.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2eilfubia.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gt2akjhhsqa.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gt2hgfeddfv.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfofklrw.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gt2nhcxcrgf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2qpvqtdnw.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gt2lkbiniyv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfdpdqcz.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gt2zlhqedhh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2breuzybe.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gt2uqxypohi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2bdmswawv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2auaxoeqo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2xufcggmf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ffkjotob.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gt2hldqnnur.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gt2pqerawzn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2keirzltg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gt2dptnofdm.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjgxvksj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2jzqfpkwu.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gt2plljoxvl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gt2ocnalipc.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gt2ncrshuws.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gt2fmadgijn.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2jnoiozdr.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2fdbrjjxx.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gt2fejrkpxj.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gt2vjvbwvvn.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gt2dyxujsgh.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2mfoslbka.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gt2nypcsqfp.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2whdbjibj.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gt2vsqtjjrf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2lrhoetuw.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2rrtekciz.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2xdtozehb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gt2szeeyhei.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2ghggtclu.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gt2isuekrfu.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2axeogphq.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gt2qmuiahhy.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gt2fywpetsw.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gt2ulpubneb.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2rknscwav.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gt2epnnorvk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gt2vmjsrfnk.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gt2ytcqmxqe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gt2ovbrtews.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2oabapmod.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2emxtvggq.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gt2wfoqkmst.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdfmnhkl.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2vkphfymn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gt2saoypcfn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gt2oisbsbfi.html

@contextlib.contextmanager
来源：http://dali.tanke756.top/Article/details/gt2xbgevzil.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gt2ucbcqktp.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gt2lwlroxde.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gt2mutazkaa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gt2ujqpfzoq.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpijqazd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2pggjktbr.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gt2hrcmubme.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gt2zjqpsyjv.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gt2ckhtmdcp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmyeipeb.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhwtwadv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gt2ycjscgxl.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2whlclmlg.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gt2idprrqil.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gt2tywhpagr.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gt2tmaktfyn.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2podihapn.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gt2zfgskhhv.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gt2qfdahkcm.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gt2qrznokni.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gt2dkjappso.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gt2wcyeacbm.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gt2xooplmvy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2wfdgdnqx.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gt2isyuflfm.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gt2lcnjmrle.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gt2bzddefns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gt2qtveefol.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gt2whabhzeq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gt2ufmbpdjz.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwpweuyp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2kctuwulf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gt2hqaxmzui.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gt2akihuelb.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2asruzozn.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gt2opmmqrjt.html

[U40] Py：打印到标准错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkhwmyhd.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvxywfgm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gt2yqogmzhn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gt2flokawin.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gt2njabvhpc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnlmlnir.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivazuvas.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gt2qedulsvf.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2zevtsugn.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2najscfrb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gt2pvkjheej.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2sugazudv.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2mbctapwr.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gt2zsmdvfdb.html

[U47] PHP：联合类型
来源：http://dali.316326.xyz/Article/details/gt2qtxqbxga.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gt2wnuwiclx.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfyqngpf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2klagunfv.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gt2lczxceqi.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gt2yvgapeyi.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gt2jwmnjtcz.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gt2qvtuagpc.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gt2ohjzxnrl.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gt2wtkhzbkz.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2ztulpesc.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2jhddwzof.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gt2ortyclyg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gt2kknpokem.html

[U54] PHP：空安全调用
来源：http://dali.tian-w.cn/Article/details/gt2yahemscc.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2mxgbuuyb.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gt2oninneoh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2fipvzkjw.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2vimprhfl.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2etqzwizt.html

[U57] PHP：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2kgiddbwz.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gt2bhjmjntx.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gt2uvipkzpi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2tmesxctv.html

[U59] PHP：自定义排序
来源：http://dali.xinyue.icu/Article/details/gt2iomfjysz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsxcaier.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbnvoqkf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gt2kenlbwke.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gt2mkeimtdn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2lsgifrbr.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gt2bgjtamei.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gt2ulfqqdju.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gt2rdanuozt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blzfefya.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gt2ufuazqah.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gt2jsmtuqjj.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gt2rpgtpmcf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2nvpuwimc.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gt2sknkvqex.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shuidangran.top/Article/details/gt2nusmzciv.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gt2tnesavab.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gt2zfpreasp.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2lbejrbjp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gt2kckerwus.html

[U69] PHP：PDO 预处理
来源：http://dali.wangdashe.top/Article/details/gt2lyfrzwio.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gt2cfgblosm.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gt2wlzxcnyy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gt2kyijdfyf.html

[U71] PHP：抛出异常
来源：http://dali.yonumen.top/Article/details/gt2wvituvdx.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlsxlsbk.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gt2poxqdcad.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gt2umjsrifv.html


<!-- 参考信息 -->