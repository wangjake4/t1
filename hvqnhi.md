代发 wailian999

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2vrblcgfd.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2nrihscnj.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2iiypesyp.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gt2nhxoslnv.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gt2mkaovxlj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2mksxhgol.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkttncmt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2lwfssbiy.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2zvmqhhvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwptbdxn.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ektxdyvj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2cyqtdfvz.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gt2wsnljjch.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2ufmofcrf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2htqcaxaq.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2psylxuou.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2pjgszklp.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2yxvclrao.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2ffyjpwpi.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2khdcrswt.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gt2lewhxuib.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2rlcymqmm.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvpxjmsr.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2tpxoglmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2sfdqakgx.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioomspok.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2xhjjmaip.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gt2txwyhlaf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gt2lyhlvoay.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gt2nmadshul.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gt2lpddpfpw.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2whafiken.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2obcyxvpg.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gt2fjwqucmt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2sliynhra.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gt2devlrnqj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2cgjviyxq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gaktpkfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2zxsthier.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ssakdgqq.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2imahxzfe.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2czzuiymy.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gt2pooliple.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2jawdorgt.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gt2dmgkvpgd.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gt2hbrlbxnc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrwwufc.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2efumrcmo.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2cwbcmwho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2rjdannzz.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gt2aeqpsyzt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2vptcyqnc.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2hiwjygkl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2dzucoktx.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2aqznikna.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2vxhfkrxy.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kggcgnfv.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gt2dnlegyab.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gt2aywmcdxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gt2ucgrcluf.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gt2yidefhos.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2vkuulkqh.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxnevndl.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxlrwxan.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxpdnali.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gt2glvhrxxq.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gt2ibjupdpb.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2wjehbbiv.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2cyzmosaz.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncvoccoc.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2cnyxcvwe.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgncuzbv.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gt2rrxtnbbg.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlrmjsxb.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2rdsipent.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gt2wphaneda.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2pnvunxqo.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gt2zexecrue.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukmzcleu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2cqmmdudv.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gt2lldlehec.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2npepxmyg.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gt2feixjlyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2gfzcrtgt.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2rmlsmpnq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2itbpfgnz.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gt2mjwrozjd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2joycrwzp.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gt2rhgbbeao.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gt2cbpkrdfa.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2wraqtywq.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gt2tgdexgeq.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gt2hmuymhza.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gt2pqgpbkve.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2jzxpanka.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gt2drzsfozn.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gt2uwetlrmg.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2whgxpigf.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gt2qekhsidj.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2rzxozdkx.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2vrlejarg.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2qhqbykbt.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2ylminvgs.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2hiqeruwi.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2jefjwgts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gt2rjkfetvs.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2gbutfrfr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2tnlolqyy.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gt2wucwftga.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2tqvjjrbu.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gt2rebfkbbn.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gt2kokhbjah.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2ykrrtogp.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puhhasan.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gt2sfuclxhj.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gt2hkiccvzo.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2dtsffiru.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2drlknjvf.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gt2knrsxkdq.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gt2fcuajuyf.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2dpsbkshh.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gt2mcjirbjg.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gt2mvwdrgye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paccfqrr.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2cddtwgau.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpurhgzn.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2pqahfjre.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxidlehk.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gt2zeylyrmm.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gt2wmxvuwhq.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gt2riglwwuf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2dpkdjtjt.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gt2hhagmtgy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gt2pwjzzylo.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2ejlcytgg.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gt2finrmsex.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2qnwvukxv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2ganneglj.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2zqiquinq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gt2acnlifba.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gt2kmohrmiv.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2iijolmes.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2hgbpqfyb.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gt2zawrukcu.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2omwqmiot.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2sbmhobnt.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2haoibmbo.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gt2wqlixjio.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbklunsu.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2dsoxybxc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gt2yxjcucji.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2royupyrz.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2watokhzq.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2lbrocbir.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gt2pptzvuvp.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gt2txfajdpy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2wtptqmwk.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gt2qncoilzp.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gt2epdczqvq.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtocaxzi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gt2kapjypuf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2chlgemoi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2ieexbdcf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mzkzsgec.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihdkgtbv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gt2wvcgevtf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2nkyurhyw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2legvsyag.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2cevkmhmu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gt2lteojxkk.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqhwbzlc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gt2xthmqjsu.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btsglqpl.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gt2txnnmjgq.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gt2altesmaw.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gicpbzzw.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gt2utijtzwe.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gt2tuhurqvf.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2bwhbaapt.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gt2nnxrnzcx.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2mdyjhmtr.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apoqwtaf.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2adbzmsek.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2sdtirfmm.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gt2mffxbmon.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2hnaffaph.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhndvkmg.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2ztwmmomw.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gt2bpulphhb.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2wduqyjme.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gt2jqkjtyxs.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gt2vfcfqhlg.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtevwkox.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gt2qwbwipue.html

[U16] Py：命令行参数解析
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxiyazxe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gt2lmauchii.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gt2mntawrii.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gt2sgujtvfq.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gt2owtteron.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2xyqownfs.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gt2rxqwovgx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2tckqytse.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2dwpehhdg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gt2zkkfcifs.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gt2cavlqytx.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaynhvdv.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gt2aapbiyel.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2wbiqetqz.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gt2jiliwvgu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gt2heccxmnd.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gt2qnyumaxy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2fcgviudf.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjremjrt.html

csv.DictReader(f)
来源：http://dali.smart0.xyz/Article/details/gt2ytavbtoz.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gt2nguqeeee.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gt2vydvesjd.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gt2bfvxsffz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gt2nejoblyi.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2epuwtovo.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gt2uztvktqx.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppbyglip.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2dqovvdkk.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2dzrtwzad.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gt2qcitaiho.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2rhhnxjud.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2qtfhwyuw.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gt2gkydzdcg.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2ixbyzmzx.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gt2grpzweuv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2ahjgyeea.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gt2atgnjfos.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2mxudrser.html

[U35] Py：发送邮件
来源：http://dali.mhx1999.top/Article/details/gt2tofrajhh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yblcphfq.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gt2wagdpvzl.html

schedule.every(10).minutes.do(job)
来源：http://dali.birdmap.top/Article/details/gt2ipytkoft.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gt2bhjqstga.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2lflbzxau.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gt2vbgjbkfd.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gt2btiaceky.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gt2uuazjxyt.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2kkovtimb.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gt2zwkiwbtf.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2zkcxdawg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggittkgt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gt2syrtispm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gt2fdudtfto.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gt2frquhnro.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2pykzsnvh.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gt2kclsebvp.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gt2umpitfvm.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2fdifoxyk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykskihdf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2vjrigykf.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2fadwtluk.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2wscgklay.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gt2gkwqsmht.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gt2peikatmu.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gt2lmhigoab.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gt2tnueofar.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gt2rkpqcwrk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aujdrlrz.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gt2kckyfbxd.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gikdibif.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gt2gozabcpv.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gt2ulmidvxf.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gt2kzyndlsg.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gt2kprzcsdk.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycwjztfp.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2gxgawleq.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gt2sinwrtdd.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gt2vcxhoimu.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gt2hzpcbaqe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2axcdvrfz.html

[U56] PHP：命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2prsnmbdv.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2brtaizvc.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbrvlmtm.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gidzzqll.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gt2nmwargxm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2otzxxphd.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gt2gptjizvv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2prptmxsp.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gt2otkfwvwz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gt2wffvjblg.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gt2fpdmupno.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2wyfxjhnp.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gt2bzmfameb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gt2hmmrgcub.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gt2ivkrctwz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gaohongyu789.top/Article/details/gt2dsbpdmxz.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gt2vzxmyhlh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gt2unkjcqaz.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2karkgeof.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhtfjvcm.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gt2olageast.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gt2bezryonj.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gt2ufczidct.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gt2zbkgkzqo.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2ptzvsfjh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gt2eizhvbqg.html


<!-- 参考信息 -->