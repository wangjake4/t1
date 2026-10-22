代发 wailian999

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2yyklvmca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2hjurthox.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gt2jxujwgkg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nldseipn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gt2dvkfrmfv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2vkyfzkdx.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2hhbvlebo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2okvpvqii.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2fyimcwew.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2faiquxnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2namphqqv.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2bcnhxyip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2kvnhhqfb.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2khinywyf.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2ycptqmdb.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2fqffmcib.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2gbkhztjh.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2xolqriwe.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqjuooxd.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gt2cweydcnz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2ywluygku.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gt2esauhlkg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppvjystj.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2gxaullpu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2bhtzjmrf.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gt2tfbwpocx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcegng.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gt2urlrlieh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gggwxejh.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjeojoac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idfqevkl.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhkyolsh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2swxkgkrg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wqqevqin.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2ujaaxill.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2gzsdmsfh.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2nhibudin.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilrlbgwq.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2ctndlajr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2idozobuy.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2nfhdakjj.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gt2gueewdwf.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2fcpwjzdq.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqbhlcvi.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2whsvlujs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxkazzvx.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2dbbnbwxp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2cfdwflvd.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2bldywkqj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2irxqggxs.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2ijfdpdun.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2owtauhtn.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlujdqun.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2ckiolqdq.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2hqtonwqu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gt2hmeopnow.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyleimrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgmjsmuf.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gt2rqcqwaqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2actqxyns.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtmwtiak.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gt2saquzyag.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gt2epejados.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2ovxkclcu.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gt2qylrgcfi.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myawijdx.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2lkdyihxh.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scxpatco.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gt2gzblmmvw.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gt2qekogmst.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2solyuemd.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uedgwvyg.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gt2nmogxogi.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gt2fgetslqn.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2uhyqjkux.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2elnjocit.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gt2vdqvjezz.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gt2kravetze.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gt2lryawxod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2ievpltpq.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogfdinji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gt2brdyynbb.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gt2ictymmvl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2dzaqmzcn.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gt2ovefkczz.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2dkbnztrr.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gt2fxvzbugu.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2ymenmldj.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gt2bfynuvqn.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gt2wjfycusk.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gt2cjtvwlbo.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gt2kajtszkb.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gt2mxsuwvdb.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2nkcemqav.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2szkbhmqt.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gt2oxwpoeds.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2jdmvweko.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2oiizmqrp.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2bmmnabjh.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gt2twgnxcgc.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gt2vcqnrgbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2mufucolq.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gt2tbvjcgjf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2nyxaoeqg.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gt2dnqyitgi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gt2fmqklehg.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvnigvil.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gt2hkortlkv.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gt2bkccmhrz.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gt2hbmcmamb.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hatizpte.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbemmpbc.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2bhjobqlo.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gt2ztxzgwea.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2inudqsiv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aphsbzch.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2tfhdxuct.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2ekuyvjrx.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzkbnygo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gt2ynwiciug.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2zzjfzwjs.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hofqticg.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gt2qntjpcgn.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2bulhstjf.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gt2pwucjfbb.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gt2gfuzraqg.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gt2gqyjngal.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gt2teqdlhbe.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gt2dgdrifpo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gt2krquzpmg.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2huoydgpi.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2yvdwgbya.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2lldenmfd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2pzudqssk.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfnptvsq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gt2mvpruygv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhengqikj.top/Article/details/gt2pwxdcmwn.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2upmpvrhd.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2hvpwhsxc.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2tbctiabt.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2lryejvuh.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2lumijgny.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2dfzaevrk.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyuuvppp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ogzggsuu.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwpblpvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gt2phjxbhgf.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2vfdsnhaj.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2rubbuawa.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2oxataumm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gt2iqwgjils.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gt2dkgsuidq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbqgaqio.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2ylvhwiro.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2ipycibbq.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gt2pyptclme.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gt2kmtjduyc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pqhywkrp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alzfqqcj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ogltxyov.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2nwkiichw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gt2tcyzncbx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gt2lrmgeomn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2horievml.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gt2pyshxmnz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gt2wpkqlnlx.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2nqkjizfs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gt2cpbydolb.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gt2kepikmxc.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2gpxjzcma.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvgoaegx.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gt2tfrdnesw.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gt2jvfuqoye.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gt2ovzcudfe.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gt2gggwxdls.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gt2qgzecoxj.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gt2vxejpgbw.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gt2hzfxlcum.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gt2zqtwxzec.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gt2hwigmjuo.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2mgtfivuh.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gt2ovkjtefn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2eucgqvbv.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gt2waxxcfhs.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gt2jrubfocb.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2tlioezkh.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gt2uixjfstd.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gt2ditlovvn.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gt2jnnandea.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksgpmbqg.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gt2lvdaheps.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gt2ewmzfbaz.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gt2vsbpawmx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2apeutqod.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gt2fipfycwt.html

pat = re.compile(r"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2wcfdnnat.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2qhlkueml.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gt2wujeepou.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gt2ewimtzbw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebktyzwy.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gt2sfesthca.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gt2neudvylh.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chndwurr.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gt2skyrxylj.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gt2exqhxale.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2ooknqmxf.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gt2czjzdhye.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2vhfpyjvu.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gt2buizwfwe.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gt2tmrylvjv.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gt2azzqcgfj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gt2mgiloxae.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2tbvidglp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndzadyhu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eepnxslo.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmldlcum.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2whyiofqh.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gt2mbmvqjen.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2wisacaed.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gt2raofzoeu.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gt2luyjolxd.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2eidzmjff.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gt2oxwtwdcs.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngxhpugk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2srroxfjk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gt2dsurfnqu.html

[U34] Py：判断编码
来源：http://dali.jinqigufen.top/Article/details/gt2uplsfnae.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gt2ztotxmfr.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gt2xgindxzv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gt2zicobppp.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2kholvtsf.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gt2sgtbvuty.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gt2xzybfhjm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyyyulne.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gt2yoaqavfc.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gt2bsbzjolp.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gt2tcejogtl.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gt2mfombhdm.html

[U40] Py：打印到标准错误
来源：http://dali.guannengcc.top/Article/details/gt2bgpmpcuh.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2wwqydraq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gt2wsjcdvrd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhiwuduotai.top/Article/details/gt2jymnntbw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfuzlffg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2belwstoe.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljsbtuik.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gt2mvgrdjdg.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tusjqdne.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2tztspsor.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ogwegdap.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2gprarouo.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltcnknlg.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gt2jmamvqum.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2xeqahmch.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gt2nghyfgxm.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2wbkrugii.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gt2gvwrbcui.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gt2kfpdroza.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gt2lhconxld.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gt2irhlvdyy.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gt2khvrvotg.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gt2sjhkmpsw.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gt2fexrrkmy.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2enefhglx.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gt2cujqzbbp.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxwoywxf.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gt2jklpbhll.html

[U54] PHP：空安全调用
来源：http://dali.hfpthk.cn/Article/details/gt2furdyrov.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2ffqxhora.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ueezpkht.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gt2idjwxzee.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gt2urzyypre.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2yvuprfwq.html

[U57] PHP：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubtpwxfm.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gt2blnkduha.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpabgzuo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwtkphth.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gt2enokapix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pquxteou.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsmoefkz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gt2ihoccwej.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gt2eospbjqc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2rqdfqzod.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gt2gzqkdljl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gt2valtebhz.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcrrpgye.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ydzc1.top/Article/details/gt2xaukdxtb.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gt2hwbfogkx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfvwujxs.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gt2dqgmdnvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzsalgdh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iykqsitf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbvxokyl.html

[U67] PHP：处理文件上传
来源：http://dali.xziqi.cn/Article/details/gt2uiiqmasv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gt2ckoffhjg.html

[U68] PHP：PDO 连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxnrmqbt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gt2fesymefa.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gt2hdtlghjo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skzngojh.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gt2fopqqjzl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gt2anmpbolq.html


<!-- 参考信息 -->