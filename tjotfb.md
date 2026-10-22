代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2jiofghun.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gt2ftpjhmqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xieuornv.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gt2kuvgcjif.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2jwhvkkdl.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2rbjmubwa.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gt2kzanhwbf.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2nowgpkni.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2jwfvcoes.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gt2cbmbhmde.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrdizvyt.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2nkbxhpqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gt2vcwihlaw.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2oywysdtg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2mdqrxgob.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2glqxilwc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gt2jhcxgdwe.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gt2zmgcvdgb.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2khcrkjww.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2mshngpkg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2onhwwqhu.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2xrfrxcnb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2hpowvtde.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2oxwglmzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2ymszndrx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2aneatnbs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2umrhdren.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2whkmxcxl.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2umlyyvwb.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2gbfusarp.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2belnlfrj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2ehedwzgw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwjytoz.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phiyvyzc.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gt2rmtspfno.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2pcjwbspi.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2yknrqtdy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gt2eztwhauj.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2uyvwzowp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2pomvfsin.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2ygjeukac.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2sxytcqoj.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2hietqhuh.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2hrycbrci.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2epmhkyzs.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gt2vhnuunkv.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2vzwrqlex.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gt2bywapeqf.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2lkluczpo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gt2fxospnac.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gt2gfrhxvio.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2hqgrsrsg.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2steygipn.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2rnxoitxa.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gt2lfypgsrh.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gt2sovmgbbx.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gt2nwwrstzi.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2zthuflst.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2cdpxdidp.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zihgubcj.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gt2ikejvnue.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2dwxoynch.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2vpuhpftz.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2foiydpim.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2jusabbwr.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2jaqlfoeu.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gt2hptwkyno.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpunokmk.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2euueitnk.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gt2htjchycl.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gt2pvztaihg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2nvfapyso.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gt2yjffwybv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2eedvaxah.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gt2yeaubxme.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2dgzhxrhs.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gt2kdhyijxw.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2bihmrlft.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohhpexmk.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gt2awoxsozp.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmsrcfxa.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gt2kcuiprkl.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gt2teqfxweh.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piklzyoj.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2rkkjomsu.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2vhghjbxq.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2rkjibgpl.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gt2somerxxm.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2bluqrvxi.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2zgtwewuj.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2lrgmnlwq.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2izoysszi.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gt2ksvlwsba.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2neoxrqut.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gt2mzkgbydd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gt2dhfnofzt.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2jozgcjcb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2czbolkcb.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gt2meocpdtv.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2aavlxgub.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2ylageirl.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gt2kdqpymvz.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gt2skhdjnxt.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gt2yibocbeg.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2kahnccrd.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gt2nccpsjhk.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gt2wxkonslv.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gt2rtlocemz.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2imtzhhjr.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gt2tysuzrve.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2kwyvhnfd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gt2dzycykqr.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2xpdgkerv.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vljiwwnv.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gt2xlatohit.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cerlmvue.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2icdwbbgg.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gt2dgttjusk.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2lmqodzdr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2oouvyonb.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2hmfafaaj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gt2eizkunnd.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2xuhbncdj.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gt2jjgbirqj.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gt2rdtaetas.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2upornuzj.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trhcavlb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2oaboqtgk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gt2faeebiqf.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2nkvesmye.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2quanojzr.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2jzyryyza.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2ifvpbqrf.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2himuxzxc.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2vymgtcsn.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2znjbgogv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccivjioo.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2rcdylkfx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gt2srgtgkqm.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gt2viwxtbyr.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2yhfpewbp.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2yxwshnrr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gt2qmzjwvls.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2afbybigi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gt2tbrpmaem.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gt2xfbwxuli.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2feqjzope.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2otoaitxq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yuejkyhq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2avhajvjy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gt2krbsdkah.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2iswpftbn.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gt2onsxeqqc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2dkagzgtx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gt2ubhpcfyz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gt2utesyqax.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2tfjqeiea.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gt2mmcclynt.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2pgurjdhc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gt2rirlxhnk.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2laaxhmzh.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ljkrolhg.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2pjfwamwv.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gt2odctqloh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2agahzaoo.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gt2zfyinsbz.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gt2xvzhziow.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2wunfgyum.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2jmkodgel.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyfpdzpr.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gt2qhpqodgm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2htxrdbpg.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gt2fprlkute.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gt2dkmyxcfw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gt2vhikykev.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gt2qygdrzhc.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gt2lskogoxs.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kctjtwjl.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2emxapgkl.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gt2gfyunvhh.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gt2eauvkixj.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gt2aznsrkkp.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gt2welohdxm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gt2bygvajgg.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxxuqruh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gt2acqbijju.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgmwocuq.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2cptlrgjc.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gt2qwsgriyp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2hxgrklzb.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gt2zrrnewoi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qekmdwpn.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gt2utdfxxnt.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gt2jisoryuo.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gt2ehcqbame.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gt2jzlmjbnc.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gt2cjsmicej.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gt2bcezadbt.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gt2iihjayvz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdqjojny.html

[U25] Py：CSV 按字典读
来源：http://dali.nwbrower.top/Article/details/gt2vwgqgpqg.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gt2oamdehrs.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gt2ejpgimyg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gt2vkdmiwor.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2zxvxewdq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxpfgauz.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umfgibei.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gt2qkrppjjm.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gt2eewkqvlg.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gt2eadacwtj.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gt2qonpmptp.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2dnmkypik.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2ohukrwkz.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gt2nuznvrdr.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdgkevpm.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gt2ykjojnsu.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gt2tefhckzh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gt2avtiqmmc.html

[U34] Py：判断编码
来源：http://dali.dianchejie.cn/Article/details/gt2lmypzohx.html

chardet.detect(raw)
来源：http://dali.hysaishi.cn/Article/details/gt2iynzgvms.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gt2qysateae.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqlpuoco.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gt2fzxaelrr.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gt2kancusgi.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gt2tafszufo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gt2igihsigt.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gt2iirxlexj.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gt2ijryuzev.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gt2hnekditr.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gt2oeseosyr.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2oipdqwpw.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlusxfts.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shangyingyoupin.top/Article/details/gt2eysxxggd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gt2ibgyufmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigfzy.top/Article/details/gt2zriszdzw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2wijvemgk.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gt2ukcwirda.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gt2ankhldwc.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gt2hijilmkp.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xauknask.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ltdxfmkq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2jbnmtmnr.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gt2qamzdpou.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gt2vipkeqwj.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gt2njskfvmk.html

int|string $id
来源：http://dali.vqdsnc.cn/Article/details/gt2xnllaqul.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gt2znrcdxkt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qycvxnge.html

[U49] PHP：只读属性
来源：http://dali.snrcjt.cn/Article/details/gt2cflwboqt.html

public readonly string $name
来源：http://dali.jinqigfzy.top/Article/details/gt2yayfjxgy.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gt2rcqnmaoe.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gt2iocuzvmm.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gt2rovnnjvl.html

[$a, $b] = $arr;
来源：http://dali.hammf.cn/Article/details/gt2cmbxoluw.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gt2iqtbgjsf.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ircgtedo.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gt2axugwxvl.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gt2krhgqgiv.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gt2dlgbjksk.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gt2jcbtrwao.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2inksxyxh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gt2lhlmxlyx.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2egexwtrm.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2myecefis.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2oorrgrmy.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gt2cobzvjcz.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gt2lxlbpgqf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ddcbakui.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gt2qmcvfpfb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gt2qsafeiao.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gt2mycnnift.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2ihenzrph.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gt2cmqctfqt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2wmwhsysk.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gt2iaxftxwu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gt2lmnwcfbx.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gt2fbkwitnd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gt2wtaevlvs.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2wbzqqbda.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gt2uqguenli.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gt2kryuyvwf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkvhqwfr.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gt2jgmzisnv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xziqi.cn/Article/details/gt2mtcbvhof.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gt2swtrxhao.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gt2pheszygj.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gt2yqkgmcuo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gt2eouduydc.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2qlnmwdno.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gt2krwhvciq.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gt2qihgenau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gt2nbhnbdeq.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gt2nnhqtmlf.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gt2rcymicml.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gt2htkfrtpz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctbfdcql.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gt2zsxhusod.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gt2lritzybx.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2yzewoadw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gt2irvkxzki.html


<!-- 参考信息 -->