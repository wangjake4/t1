代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmmxeiov.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2sduzitjm.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2sgdxkxoi.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2psclvlbo.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2kwiyhakz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2tmpqfwpz.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2wyzgjims.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gt2iceapubj.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vbhnbboi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gt2pkoaiznc.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2muorglhm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gt2jvdpvttu.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2vjrkvbtf.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2jolfagkv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2lrzmxajc.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2vbrxrtby.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sflnwizn.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gt2aqxxzsoh.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wukbqntf.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2kmkwcffr.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sflzgvwf.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2ugarfhfp.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gt2xlfzkjdq.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2riahldyi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2iiuktmqj.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2sjitxuge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2dryatayg.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzdumlnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gt2pghteshp.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2pxscehwq.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2uxrjfjqy.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gt2ccngyytv.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gt2nirnvilb.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhhuswst.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbfvsiqd.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gt2qkbgqdmk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2vcldpnpc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2abbrdjmt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvyeagwy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipyomtfi.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2srfqlqbl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmalqgu.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2vlwfojlw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gt2etxcfsbk.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2rytiadla.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjebefwt.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2gcebybqr.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2oavlqzyc.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2hmnmyolv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gt2uxmenfer.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2eyjzbxmk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2qhbbuzwk.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2fwcmamro.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gt2htevxwec.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2bmrsgkyg.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2lbytszdz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vgxeyijx.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2bcnhgejx.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2wojwfzkg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gt2vmbgupmt.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gt2nxniqmpv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gt2mfkbdpkw.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gt2vrqnabec.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2gobxnmhf.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gt2gqvqfdxp.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2vmvzrzwu.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyvmyqey.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2arwgynjq.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gt2nlnemnve.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gt2kxbvgghd.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2mduhibdv.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2ydienogt.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2felfxllc.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2uoeyvqzz.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2fxnombcj.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2npxfiaki.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gt2rdmsnute.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2rcmwcuty.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2mtrucpqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gt2pkwvvwsv.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gt2tjotvhjh.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2kvworaze.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2naetpkks.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqhykjcb.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2ipoeajsz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2sccpwwww.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gt2nceacogq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2mlhmfbsl.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gt2lzzojxqo.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gt2epceukoq.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2dejdaafa.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gt2mnuqgdea.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gt2izexwatc.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2icbulsyt.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gt2vhbswzba.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2purnsije.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoieqcid.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gt2fpzharvw.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gt2dprlmqju.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gt2qrxxkral.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2dveebwoj.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2wfbzliut.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2goghaqej.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gt2pjukqkgq.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2uiloodrj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2jnwshdws.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gt2yxhiobbl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gt2nmublasd.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2wjsixcqg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gt2dmquqksx.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2ioxczujb.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2lrzqqjyn.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2ubcvdiqm.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gt2gnhlhrrb.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bizkmyfj.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgyzpylb.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2pmomejut.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gt2lgebnkdv.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gt2ppeszylr.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axlxenaw.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2rzjxiihx.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gt2ywksgqft.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2zoqkpjjz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gt2femymdbu.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2jhktajji.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2qfxneuht.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2sdjqsbtd.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2mwyfcyhz.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gt2ooiyopgs.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbdyqwma.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysvquzpv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gt2oostzyrr.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gt2pqakboxv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gt2wzcijqhk.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gt2pmikjiaq.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gt2zqzxjhiy.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2goslvaay.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2cattbcuk.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2ivafzrdp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gt2jronpnlu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2bmjwrgdf.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2zxzkfsgn.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2iaabeupe.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2egqapjss.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2asbzlkgj.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2dzampcnz.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2agrlnqom.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfjihtce.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gt2oomlmcio.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2mibeoqtq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2todjlbsk.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2outzedak.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2dmlsviyr.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2cljlqqgb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2ytmfjuir.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gt2efxguptd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2anzllmcr.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gt2viegapgs.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejbgibcl.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2axxqxkaj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjwxessg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xmlamhoa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2palgxyjv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pingvvzl.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttlpgymp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gt2ycmarqju.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gt2yymfhdij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2grxcskqg.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydkdcwvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gt2fkvvjamm.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbvpcxui.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gt2platpjcl.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gt2ngbvocra.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2ladzvpgc.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gt2ccytdnih.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2xphlcjxa.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2hblfbuqq.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gt2dmmwvnqo.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gt2fgmsqnjw.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gt2lzlxpyin.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gt2nwalaejf.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gt2mxqhctoy.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gt2forphkxn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gt2txvjgucq.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2akxcanyl.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gt2nzykzgoo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2pvemkofc.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2dbezmugs.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gt2mxgccode.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuarwtqi.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gt2rmsckbnm.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fktrhvqh.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gt2cfjrefgo.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gt2vouvxnxz.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gt2wlvqlwoq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gt2djwwnsmh.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gt2fvkjrzeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gt2ttuohbmp.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gt2pmdvobqj.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2sfdealla.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gt2pvqvzmpi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gt2knbobpqx.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2xuiwibxb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgqsnghk.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gt2xnxwvhdv.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaealbff.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2wmpsvrgj.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gt2vubnuequ.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2vuguuitm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2iyhhegdd.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gt2nvgydboj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2kheqyfez.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngktsliz.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gt2inapmwff.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gt2tlxplqrz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gt2slybfgxv.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gt2ladxeghu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2zwvdnqpy.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gt2gwwndndz.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnpncfob.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2vfrvxpzt.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gt2dgyvvmzc.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2cuymabhh.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2dadkaokn.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gt2elmjhdxu.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gt2thryqmqf.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2xourekqx.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gt2yugrimia.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gt2wihrsqbn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gt2iklcbggn.html

[U34] Py：判断编码
来源：http://dali.xziqi.cn/Article/details/gt2wvxksuqz.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gt2xdytwrck.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gt2rneilomi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gt2pkzgshkv.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gt2pqxmdntp.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gt2kjcsoftk.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gt2cjmeayze.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gt2jiwvqfzs.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gt2cnaozlka.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gt2fycuibkb.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gt2vrawrpll.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gt2cflztxkc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmjbjyy.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2gmuuztuv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gt2xchahzsq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gt2eaxmiyit.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gt2wetofhbn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gt2zxvatiyu.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2chajiopc.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gt2bduyjbva.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gt2cmynrmkt.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gt2lokuaubu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gt2funbncuf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2cbixvbgw.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gt2keexkemz.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gt2gsnehilv.html

[U47] PHP：联合类型
来源：http://dali.hysaishi.cn/Article/details/gt2cgqwphkz.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnrzavig.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gt2unstgwgb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gt2skxtinac.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gt2zqypzcgn.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gt2ckxkrsjz.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsoweszz.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gt2oblfpyoo.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gt2qsxrnyby.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iirtnzlv.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqqcumrr.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gt2deiwyexz.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlmvkhbg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elivfyou.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gt2uhpgcedl.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gt2gzcjzcum.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2aqwkjwqy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gt2yfogtqep.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2pxokdipd.html

f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2uhqlngsc.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2axnbjzpj.html

"值: {$a}"
来源：http://dali.bjfxy.top/Article/details/gt2gbtnhngs.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gt2eybayvlk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvnqgkab.html

[U59] PHP：自定义排序
来源：http://dali.yvedp.cn/Article/details/gt2nkzsrlpo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2htovobzg.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gt2rrsplgpx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gt2doyxpgmm.html

[U61] PHP：正则
来源：http://dali.zhoulong.xyz/Article/details/gt2pglhxygl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2kgitzepn.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gt2wblgieex.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twcznzmm.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gt2lnnfmfsf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gt2ltnlyydr.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlgpysmy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svlngezr.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gt2cniykipf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2rlpgueho.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gt2nzpnhksm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pycfn.com/Article/details/gt2zyylfnsl.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gt2zkypucin.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gt2lsfduywa.html

[U68] PHP：PDO 连接
来源：http://dali.zhixingplan.top/Article/details/gt2yahzwkva.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndqhwsbt.html


<!-- 参考信息 -->