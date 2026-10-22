代发 wailian999

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtbkvgfbrn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtvrcxnjjx.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtbwddsqzz.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtkcvihyvo.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtnapozhkq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtxtynjxkw.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtrwjzwvbc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gttsephiro.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtdscnxxaj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtswpayoah.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtjzpebekd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtbouipiqk.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtelcagwte.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtgoqcsrat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtipybktcw.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecjfnqpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtdzldvsmx.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtvhjlkghd.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtpkiurnsu.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtpvdzqqkz.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxpmsmdvm.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtgjycyrjl.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtluyohqix.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajyzwkzg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtqnopcdzc.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtovhhgqfq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtxftgjgkb.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtsdkehqec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gtjbyphtmc.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtlggxkmeq.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthytvlfka.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtqwzemgjo.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtrdjjlayh.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtnncvmkyh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtgkpsmveh.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvewxntj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtdpdggumz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrbyywntm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtwvevnrkv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtucjkigln.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtkiqltrua.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gteunldsyo.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtagjjdfqy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtekusebxm.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtdeyhnind.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtaflycohs.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnxjpysg.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtjqgboios.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtnacrkqyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtbehbxqrc.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtdmpsryrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtmwmjrqal.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gtzsmtcjis.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtrdmzjnns.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtjwvhyxjv.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtknoljquj.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtyiynldcd.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtbvnqrtgp.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtbppfhtot.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtusvspgxv.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtblzpzcyk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtqottejnq.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtpmtbxzfl.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtrevonkgy.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gttlwayrda.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtdjjnjzuu.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtxcpymyge.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtnxhbojma.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtionlwgjn.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtuzezymar.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtsajrcood.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtevooalpt.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfuwtkip.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtlgrkboze.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtveadbsbs.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhnicadl.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtjalcpmxc.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtphuvedqn.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gttqxonsax.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtdttuhzga.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtynqsroxq.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gthzoqwjcc.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtkkekreuc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtmjgbbsqi.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtyekhvmkx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtgemkamxu.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gtbxuyaetu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtgqvcykil.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtvkwzbbay.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtyxaybpbb.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtoxazfrtc.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtfybwrrgq.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gttsambyok.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gthlcrnuvn.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtejxdumwf.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtihofkzoq.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtsiarofvp.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtdddsmlwq.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtcmapvxcf.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtatjwlavg.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtlmagbidp.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupqaugod.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtvcnyjcic.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtuqarmmmn.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtdiivcdwo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtwikegmkz.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtqaxytwtj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtsisbdrgw.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtvojunpjl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtnabntvto.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuhyklegs.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtbitmxthe.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtjunyvipk.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtredqbmeg.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtdjidcahd.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtustptpka.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtslrndwgl.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtizohuptp.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gtofwyfhqe.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gtfojxqugs.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gthohcmaxt.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtpoyakyna.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gteatfnkis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gtkfagglrv.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtxrxjzarl.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtbihnfthp.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtthxilppr.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtttsmkdzh.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtfglwglvl.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtpomhcaku.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtltwdmkvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtmrmmuwjm.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtepowjyei.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvrqsifp.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtmyybemya.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtynlghbdx.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfjpigck.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtljbxlsuk.html

[T50] Perl：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtbotgklmr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gtzjoguzxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtytocxwcm.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtrywfdefr.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtqzauzyas.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtnzgkpuzv.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtugerfkwk.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtancyjkwb.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtlqnugbnx.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpafujjc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaruwqfi.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtcsxljmwm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtwfwedvfe.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gtmrmpxjdp.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtzbbvwtph.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtdczupily.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtqfsbefoc.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtoeouevhi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtwtfmejmq.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gteiefbenq.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtbgwzqexh.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtjlfrrmbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtlxencbfp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvlxvjhds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtusessokw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcorjrjzv.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gttjlsvvun.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gtvsqpuspz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgfvutnu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtwtgfjmmr.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtfqlunmtq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtzpttpivx.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtsqcqxbtc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tanke756.top/Article/details/gtxrbkwrev.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtwjdmbnia.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtcembvour.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtiqdihtmh.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gtjbrxzeqn.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtmgkaursw.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtogoglcas.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtiwquijtz.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gteveocybx.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gtedhdjoow.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtokgbuypo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtotcrckub.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtqafefavk.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtccofolrj.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtspwcwgow.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtcaxbeiku.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoocnxbp.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtrcdudcdo.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtuiverwig.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtaarmvjmg.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gtkycngeat.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtkcthfuwa.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtovjkmkvg.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gtojvcygds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtpjlajfst.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtevetenat.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gthpheockt.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtvdprdngc.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtqyuwdltf.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtjnolhdgl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gtfrnxtyer.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtgvaoivud.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtnqmegkgc.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtwumwtxyw.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtblkrkmzc.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtqewhidvj.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gthgrlvoux.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtgqptzxkw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuanzx.com/Article/details/gttqggsbyd.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gtrujxxnqj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gthuprmmjh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtccyfkqlv.html

csv.DictReader(f)
来源：http://dali.aizwys.cn/Article/details/gtsvslqrwd.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gtcycryzoa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtvduzsdjo.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtdegqgkeg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtnohemjpk.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtnfaminiy.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtmhnyhpki.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtgwqeocrx.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkensega.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gttvinqjmd.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gtdaorlkzn.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gtmvuvtgez.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtfskxbeuw.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncextzpw.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gteiwhgfuj.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtevshwdcf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gtsosvbxve.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtwpefvkul.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gtsszbfnqk.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtpvtdxo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gtvdxzjtqz.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtrwnpcxpa.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gtykzugmns.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gtknhyldkw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtclejpplk.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtnramaluz.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtyvkeuern.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtrprxeobl.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gtgpdegrxd.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gtobdjpuej.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtlrnosqnj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtudzllejd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtwrshmtyk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtdqsnxvtk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gtyhokimyl.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtngevvnif.html

namespace App\Http;
来源：http://dali.ppjwa.cn/Article/details/gtxfbvvzfb.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtfjezmglw.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtxlrbzywr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtzkcxsalm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtsfqlrdii.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtnttqlbsg.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gtouhyzxqd.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gtbkpyevui.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtkhbqtwic.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gtucsheobj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtjjohohfe.html

[U49] PHP：只读属性
来源：http://dali.shuidangran.top/Article/details/gtqmgnjmxq.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gttencuezp.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtobiejjht.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtnylfjrcq.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlwmblmf.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtdioqwclf.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtetjkdxrd.html

$double = fn($x) => $x * 2;
来源：http://dali.hnqzz.top/Article/details/gtdqzdqqhh.html

[U53] PHP：空合并运算符
来源：http://dali.tianlin.xyz/Article/details/gtnsclpoto.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gtqcflgxer.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtjzshutnf.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gtipfrcknr.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtuijqgjgr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtmfnqldsj.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gtanypnfdm.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtyunkhxxf.html

[U57] PHP：字符串插值
来源：http://dali.havefunace.top/Article/details/gtiwsmgiuq.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtcwqxpray.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gttexqpfwx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtzmwoqliv.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtmdkavafs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtudfkljjy.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gtosjisxun.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtixskmzjy.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gtkdbqmnze.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtpcfjonua.html

[U62] PHP：日期对象
来源：http://dali.yueranfly.top/Article/details/gthlsltjgi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gtvhlrpymr.html

[U63] PHP：文件读写
来源：http://dali.guannengcc.top/Article/details/gtffswnblm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gtzkionumt.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gtzjeawjcg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtbqmpkdcd.html

[U65] PHP：会话
来源：http://dali.fzhhl.top/Article/details/gtfarvabsg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtccacgksq.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gtbffzbjni.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtsaxnhzia.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gticzkjqbv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtrhlfnoem.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnefaszie.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gtgrgqcldu.html


<!-- 参考信息 -->