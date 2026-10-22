代发 wailian999

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2jwusqylc.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gt2uoyffddy.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2suhqqtic.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gt2gusjedbj.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2vhlcexdb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gt2vsorecuh.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2avxihzqp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2odemojik.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gt2stizowhi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2quovbgyu.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2ihqutnug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2ehbigfym.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2hsertwyw.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2ddaxmttz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2slprycxc.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvyblbku.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2hmazhlzo.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltoppwvb.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2rkkqklnh.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2awmettng.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xnbkvtmu.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gt2nspsnvjc.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzwlnfjs.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2yqpwedsm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2jjlyysez.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2maibefac.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gt2kgijkvjo.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gt2uekolplj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gt2nabcaowb.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gt2thpvqhot.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2vxhvpizd.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2gpmyrzak.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vewxsebq.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2bumfrnrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gt2fwqcsigi.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2jzkkzzuc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2iwksmpas.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nysbeljk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gt2cbdoygoe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdadwmqz.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaadpayo.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suwblfgp.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2yzllxflu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gt2njkjlpph.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gt2rizephpc.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2cotpjfvn.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2ptpciezq.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2fdtmbwxy.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykxwycnd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2naiszrtn.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2wgjdyimu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2vkeatdes.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2qdftgxfz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2tbeegmoo.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gt2jxdatgab.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2ybvkwgry.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hrvaqkkb.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2xdykcced.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2iepxufbc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gt2fbcypskf.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2redpgmdw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gt2wcnsxxsa.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gt2hfdsodam.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2rdijeezi.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gt2itafmozm.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2mjvmpmym.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2xlfxhyuv.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2hndmwtzu.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2pdlrbxqq.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gt2ejehugbm.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2hatkxitg.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ascbqcnu.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2zvmsopxx.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2fopwpmsh.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2qikbfxrc.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2zuttqzsh.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2ztkmmmwb.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2mkbckzan.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gt2yshnvmgy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ketlsizj.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2nfnpvkpr.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhiwqnyz.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2hffykgbm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gt2fhkhspej.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2qcjzbiac.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2mbdabhzt.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2fkqatcxr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2eyttunin.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2shsbjnrg.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2ldnyykkm.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gt2iveokylb.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2czkgolst.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2hcdisvkm.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gt2mzhqwioc.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2qzidllaj.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2rhhtxfnj.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gt2ieynbhcb.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2jvfnomjj.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2yuytdgwa.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2ahfoyodv.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2lxubrhon.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2xwteghqr.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gt2ayqetuth.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gt2npgfkepp.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2oapwbvbh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2shuravlq.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2amnzvjzt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gt2txpnwwvs.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gt2zpgdjevv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwmadygc.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2ocsszfwz.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gt2erineezk.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2vrwpyafo.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gt2rnfapoot.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2onxoklco.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2gkjzfsoa.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2vpeelwzw.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gt2cecclrrl.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gt2ivcsqhap.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gt2vhijcygx.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbgknpek.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gt2loqgvgkn.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycnrurcw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gt2psfenjtu.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2rrspnhtu.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gt2zyppxfru.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsmphreu.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrkputdw.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2pryrqgap.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2xekrwebv.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gt2bwgxuitn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxjzett.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gt2blmeotdz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdlvlicy.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gt2iwvjxrad.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gt2rrbaerxk.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gt2rsrbaknz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xpnbxkil.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2jegfzlyb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gt2lnvfdutf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2irmxgamf.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2ocueaocv.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2bnglehdd.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gt2xrwmufgh.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2vojjwdah.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2lgbesdyl.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2gomnyvag.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkwuxtgi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2wkwqmpxm.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2vlnfkoym.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2smwyrywk.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gt2widfjiko.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2qcpnrwds.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2xotkbmik.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2rhdeipzn.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2fqkieknc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gt2ilpabjyj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qedldrlh.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2ysylttvw.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gt2rskkdylx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gt2zrxxlwsm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2awaoxmbg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2alpogdjc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgimstht.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gt2udtlyfhz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gt2dfctbgsz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2mjqtlanb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gt2nyrikfxl.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2zswyosqv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivppfcff.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gt2srwdempk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gt2ymzvprki.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nljmdctl.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2yazrladd.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gt2hapyvfde.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gt2emkbxrhz.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gt2kqzssevo.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqludybv.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gt2zpzlpxdj.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gt2nlrznkim.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gt2swjouvby.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gt2yjfqhdnj.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2lnuugjvc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gt2fupmvcka.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gt2creiaiob.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjqgrbb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gt2arbqhpwp.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynelcexd.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2thojhnem.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2yvjpysll.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gt2pvczyxce.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gt2eswyhhev.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gt2atgtpevp.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2zvnxfpsj.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqhgchyw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gt2vygxtepa.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gt2czwkpkhf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gt2aojutkyd.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gt2thqcoxoh.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2gyjgjlal.html

[U19] Py：正则替换带回调
来源：http://dali.zhoulong.xyz/Article/details/gt2lkqrwoea.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gt2pbeyxaah.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gt2cvcsqlsf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gt2jioryqka.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2gcytwrud.html

@contextlib.contextmanager
来源：http://dali.jqgfzy.top/Article/details/gt2wqwdlqjo.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gt2hjjktcfo.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2aoboiklc.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gt2sgtjufhh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gt2safurqkv.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gt2wzcpbcgn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2xiybkswb.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gt2cgltpxdl.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gt2pyunglfv.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gt2abvxxgrd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gt2bupdmywy.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gt2jkkmeumr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ybcxt.top/Article/details/gt2nzfwecuf.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gt2qqvmsget.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gt2lxnrxusi.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gt2winozdrz.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gt2fxskpdpg.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2oekwumct.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2unvjkwjq.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uooataym.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gt2ogacmluw.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gt2tiscvtjp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2chprpksp.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdfmdbmf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gt2pclbbrty.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plosgrcs.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gt2kmnlgbdd.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gt2hjqccqxb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gt2glkmtpud.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gt2bhjkmsoq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2adckcoyk.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gt2pmhjbsev.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gt2zztnwjfq.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gt2jnijrune.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gt2nkzgmagx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cllptkxo.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gt2lgfgqnnn.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gt2zurqexqs.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2rhioomvo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gt2krdgofgn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gt2bttarywz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gt2aaxhphfj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gt2uaxmgwvm.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2zuvfoirg.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2vionxevu.html

[U44] PHP：开启严格类型
来源：http://dali.jqgfzy.top/Article/details/gt2slzieknj.html

declare(strict_types=1);
来源：http://dali.ydzc1.top/Article/details/gt2gbncsccj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gt2muxxdjlv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2cgtupmfy.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gt2iljgwigx.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gt2akhonriv.html

[U47] PHP：联合类型
来源：http://dali.nwbrower.top/Article/details/gt2bweerrvu.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gt2worbcafh.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gt2jynlgrem.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuanzhike.top/Article/details/gt2xuahvahu.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzmewanb.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gt2txpsbdwx.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gt2lqmbvirm.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gt2umwcdbap.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gt2fsletybu.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gt2psmeytie.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anifdizq.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gt2tnvwfcsk.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gt2amqbvjdx.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2oijkanfu.html

[U54] PHP：空安全调用
来源：http://dali.ppjwa.cn/Article/details/gt2msdqkthy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawnryrw.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gt2agcfazfk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gt2jixmyqqj.html

[U56] PHP：命名参数
来源：http://dali.0kj1m.cn/Article/details/gt2bnmkeuvw.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iggbsudv.html

[U57] PHP：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2ojgwbnty.html

"值: {$a}"
来源：http://dali.kuanghao11.cn/Article/details/gt2vryptefp.html

[U58] PHP：数组三件套
来源：http://dali.meibo888.top/Article/details/gt2lixffuci.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elptjirx.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gt2vxenrisy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2eyxhxkqr.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gt2nowkxnhh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2fdgsegdd.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubpdbowk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2yedsutsr.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gt2guxntdlt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gt2tkutkvqg.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gt2opwxafrv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gt2xphnvrra.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gt2zyxxaele.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gt2vyrhvdty.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gt2ubywunst.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2clkdeqqm.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gt2fakdrbba.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gt2xugbrthz.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gt2zlnwhqmx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecdirzbx.html

[U68] PHP：PDO 连接
来源：http://dali.shzxlz.cn/Article/details/gt2eubqqami.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gt2fhmypcfj.html


<!-- 参考信息 -->