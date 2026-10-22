代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2wwzpanwu.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dafemill.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2smwkdpjw.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gt2wnzialkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2fcgzjmqi.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpzkjnea.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2oseqjyfg.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gt2vtiauaxl.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gxpwgkit.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2wdquvrsk.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2xczezxss.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyxifgsg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2egijxcjl.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gt2nmhhwcve.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2zfogbafk.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2lpljcpyv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gt2qpkxsizi.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gt2fpnhthwy.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2izdczvxw.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2popbqpso.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2ugdthtek.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aklxiril.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tabdgokt.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2vfdxoilf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztfeysyn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2mpqoovqs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2rdufrebp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gjamvznp.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2wcxuanny.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2ovatntyd.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2gtandxno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2qlmizcpy.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gt2vjacxmkq.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2juidhhil.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2azeyraoa.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2xtrppnfr.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gt2ilelqozq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gt2vdlnguni.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gt2eiirzqtb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2hslzzjli.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2kgeqslhl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2alxrbslx.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2dmbjtvug.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2bldrmvfu.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zabjmnqu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnvpthvv.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2ckpjblxn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2xscopocw.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2wnjcotgm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2pcnayfaq.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gt2evvgymfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2vrpjrkxi.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gt2dbdcsqcc.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gt2ivornudb.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2fjwcyvkt.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2ozvsbpne.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gt2jhyzkujk.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2vgkneusv.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2jdckyzmi.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2gxzeqtwq.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gt2xvhtusxl.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2lldwaaif.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2balfpqhq.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gt2oxtfwezi.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2kuhhiaal.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaxjmrid.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gt2goexrwgc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gt2xvhfwioa.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gt2nluygnez.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gt2xpmulgzq.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gt2tnoooxqa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chiegqwe.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2yxrndgxs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2ntpyqtiz.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhjxyove.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2xymgngxs.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gt2tgpmfnnb.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbzhmcqa.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxthiofa.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2ukjcotbr.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2xuhjxrjo.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2jrgwrhmy.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2yzshbbzu.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gt2kaznxfes.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gt2zljaevtp.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gt2lsqmnkks.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2bvuvhidf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gt2ldnurooj.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2zgxcgslm.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2nmbckgun.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbkcqxtt.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2uuuzugug.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2ofppnntu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gt2odexrosv.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2hvcwlltu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2dmpsdqcg.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2bohctlaq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gt2gezmkijp.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2forratqa.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gt2qetkepbg.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gt2opntudmu.html

"a" .. "b"
来源：http://dali.gzhubu.top/Article/details/gt2kxkenaup.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gt2pzunpnok.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2vkcjfygv.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2cgcwwxlb.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2pcyxxvgn.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gt2fjtihnba.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gt2swroofdd.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2nhasctxq.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gt2onmqwzpg.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gt2tbqgpfae.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gt2xxkapfmx.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2hbuwgwwh.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2ftnpzvsr.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2rmneglnw.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqysansk.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gt2ydbwgtpv.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqvzalis.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gt2aqihgozs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fumbvgkz.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gt2ucdnibbs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gt2qhvywekl.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2nhkvabdg.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gt2tnfkvwqo.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gt2rfdhetsu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2ijjsghub.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2sfyuegkw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2manuqjfh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2dkjkzbbz.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2euiiegpv.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2indwniuq.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gt2mihyvtib.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gt2hsfhrjhe.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkfpwlwd.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2zazyikzx.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2hfbrofbx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2vlwcrkcz.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2bvfwgpmu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2lvhrfubg.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gt2lkqoqueb.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gt2pyvyonsi.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2hsqpbkzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gt2sckuiwku.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2wdgbtjni.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gt2ttjrxlsx.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2yototsiv.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2jjxunoiy.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gt2teolwfhh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2drklwgle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvtodlj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gt2ehjuqjfd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ikrzsnem.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2uthyndqi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2ykkbdkoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gt2dudbzinz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2brqfttnn.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gt2bywapafb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gt2tigftlep.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2pwtpftwh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2clrarfjt.html

[U05] Py：列表去重且保序
来源：http://dali.jqgufenzy.top/Article/details/gt2sydsquhn.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2ijuwiqdb.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozurcjmw.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gt2jptwqanf.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gt2dzhuaoqh.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gt2ehisbrmp.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gt2pgqvezvi.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gt2asfcochl.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czjdbttz.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2oktkonjx.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gt2gymanwap.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gt2bzzfnbti.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gt2odrfwzdx.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gt2gbpobxiq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gt2plaqrlwo.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2rmavqhom.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gt2zzirijck.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gt2jyrjarjm.html

[U14] Py：分组收集到列表
来源：http://dali.wangdashe.top/Article/details/gt2ffxhwbvv.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pupqomlo.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2ifdiqkug.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rifaegjk.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2otudrozb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.meibo888.top/Article/details/gt2zsgdtjci.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gt2jxkbujwg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gt2dzoxepjr.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gt2amluppgg.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2yfivmbdk.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gt2ticastoe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gt2zvngtzdd.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2jyiqvhnb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2akcnxfsi.html

[U21] Py：自定义上下文管理器
来源：http://dali.daria6918.cn/Article/details/gt2fauofkct.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gt2yutkordz.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gt2antqxpik.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gt2gqgbqltb.html

[U23] Py：分块读取大文件
来源：http://dali.redwolf501.top/Article/details/gt2xzxrnxxq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2dgaevrwn.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gt2ppratpoz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2ufdmfbrl.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gt2zovawbmq.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gt2jtdtcljs.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gt2iwoplfku.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gt2yojtuqll.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gt2scofvgfk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gt2mnnjlyfk.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gt2kigyzobe.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gt2loobkmfg.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebuyemfv.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eipzolro.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2pvlflflt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacixcnp.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdhniven.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gt2elsgzbhj.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gt2gaicogax.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2haezgckr.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gt2wlhokvys.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gt2qasrdhfv.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gt2kdofozjv.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzrccgwo.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gt2wrjnifeq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gt2vbtxcdap.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gt2irbixbmo.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gt2swtrodtv.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2xepwkdka.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gt2mtytmtfy.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gt2cwgitgka.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gt2pzkljmay.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2licqgooj.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2nwmovadr.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2mqmpvavb.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2rxtlwjzk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gt2qedazrey.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258.top/Article/details/gt2uvusygxm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gt2bqfdpmxl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gt2zzoohuzr.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2pongtkuf.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gt2lrjehtyw.html

[U44] PHP：开启严格类型
来源：http://dali.zhixingplan.top/Article/details/gt2orhawpdt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwovcwmy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gt2lhecsqir.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgijiyfx.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gt2zzfmcrel.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gt2xxvwcmdw.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2byyigwbf.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gt2xmirslid.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gt2nvttgbnm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymnnvhkg.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gt2gjklltau.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2kqqfdbhz.html

[U50] PHP：构造器属性提升
来源：http://dali.birdmap.top/Article/details/gt2ijallyyp.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gt2xgexcvsq.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gt2lwpyenon.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gt2cqtqyfag.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2fjaqtepj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuinbrso.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gt2psdkecyx.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gt2worpwtms.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gt2freyhnwg.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gt2bgriympl.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gt2xwhefjzk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gt2onrdpkce.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gt2eltitdwj.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2hbyhgjyl.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2kfvqaejm.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2quojeutt.html

[U58] PHP：数组三件套
来源：http://dali.dianchejie.cn/Article/details/gt2holuqzxs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gt2qlcrszxm.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efporyhr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2pxkpgwgf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gt2djwcwetn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gt2offlmdhs.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gt2bmizpvgj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqjdpeld.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gt2pkvtjusw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbuqcylh.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gt2psugufmu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gt2irlhydar.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gt2honkdqfh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gt2sznvmxub.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gt2zxczfmnt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2fxkhaebc.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gt2sjsdjoez.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gt2qwxsoxdy.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gt2zxuhascj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gt2mjcaoltg.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gt2dvtmdokj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gt2jiuvxpqr.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gt2lmxwltjc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ethtihyo.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2jiaoogkc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gt2pamrydqu.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2oxewdsnm.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gt2oypdothb.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gt2vlofpmqu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gt2sohnkcdc.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gt2zqhhbfrs.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gt2gshmrkzm.html

[U74] PHP：读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2ahszufvu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gt2fqcdytdt.html


<!-- 参考信息 -->