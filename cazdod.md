代发 wailian999

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtjnsekocg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtgikxwfyo.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrqvmhpa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gttetphogv.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtshtjtpzo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtwvwvrojv.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtdrxudhas.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtbrxtcbqa.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtgdzfxeht.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtvjummtlj.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtymtdwkwv.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtiicouaex.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtlxyslzbj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtyjoylyke.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtvaxbnrft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtzslfdmbg.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtrdqxgkrx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtcaifhdim.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtrwmgqedf.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtlnxjaewl.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtmvjttzji.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtltqrlkcl.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtmqzdqjgi.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gthuqnbdls.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gtatyiwxfp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtjblsgfsj.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtfrmsbzej.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfqjuudz.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtkvtcwbad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gthkzeemwe.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtuqowfrrm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmcqhrjo.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtuodsxkym.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtismjvgfs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtapdvgrtj.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gttwilkpfe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtfcxecggx.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtuzmubwgv.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtfhelsqwv.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gteerriabp.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtelufmugf.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtclutxyoy.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gteuczudkr.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtgdmmzers.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtjyfatrpu.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtjjrhyvoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtbxjstwhv.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtkyqokwsd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtmfmbqlaj.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtdsnzmwcy.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtyqulyfrz.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gthkedadcj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtqymdtmps.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtywkzxson.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtptlkmxiz.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtlphbovvd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtrohnarup.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvfqziujs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttndspbn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwlbulxrk.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtsmxmthwc.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtwarpsvhn.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtzclulocn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gttvwmvwdn.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtlqvlnzhh.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtrpxkghpc.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtouvtwogr.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtafhibyzq.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtrqjtkfti.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhamukkb.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtjnqwlcsw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtgvvlltrg.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtpohmuxty.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtkfucynwy.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtnpfofgla.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhfcuqzb.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtseuirnkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtzoirhrbs.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtsmolycxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtkykbgahh.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtobfrdxyc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtuaaimoqa.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtsblekaza.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcfrtmvt.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtnheeoffd.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtqhvqquhk.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtizsdhnnw.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpbqpiha.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtxjzcpavh.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtxqhjwkpe.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtckopdkpi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtxuexpyeu.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtifyybgpq.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtainasczw.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtjybtbhpz.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtxeefxisk.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtyxxoigzq.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtgpbhtmew.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtbeoqalky.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtagkmrqda.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtokfadqds.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnmjralxx.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gttrapcwta.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtxshzzfsw.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtmdrjkfef.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtnitmlkpa.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtyjlxcwrk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcmunwvk.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtgklgoavb.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtvcsmfbdi.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtmamsfrrg.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtgpwswflr.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtndmxvhln.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtngiltyoa.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtialvjdon.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtbazbygwf.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtlpapjowq.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtvvxiokkw.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtwcsvtq.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtdqqgbigz.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtbomcfphn.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtfuhdczkv.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gthemodpfg.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtubvzmhce.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtzkfydonw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtlpvrwqoq.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gteqwjccvl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtiogunzmp.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtqyhhesno.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtwxsihjft.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gtgtxyrnly.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtqnhpwftk.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtsjhjzmzl.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtlcmjpplt.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtrfmrsbvy.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gthhjroekk.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtzddcnfdj.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtebzcdhht.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtabjkcxjw.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtcrvsugvk.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtjggfzhqd.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtfpziypcz.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtxqrxpnlp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtgwwjcqcs.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtglsoclyw.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtovdrfhec.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtgnnujreq.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukbkxuvd.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gteorjdldy.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtlbjtzwqi.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtyyyumzmk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gthuwpavul.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gtlewdxncr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtmyychnje.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtxaogtybf.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtbfrnukwe.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtklyvtgss.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtlkngzimq.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtunpyzzyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtfkgixgrl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gthlwlnoic.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gthorbldqj.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtttncxqyl.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtxfbippsl.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtujkawiex.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtsifphyxu.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtidzkdifw.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtxlzekghl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtqepvmova.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtqfmfspzr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gthwstqcks.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtqzbzkeny.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtduaoduod.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbjfxwqc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtlgrrygjw.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtrdhnbrbt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtyiyazdte.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtdnrgwvde.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gthssuiiyq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtzmvijuox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtctiqefag.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbtrjbwka.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtguvhibjg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtoqqkmztd.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gtzaqmrdit.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gthrmrfdqu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtcinvkwgs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtdoiqettn.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtwheppwvs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtzktplkne.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtbjnidwud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtbynfnzhm.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtyycirryr.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtszjcrujk.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gttvcpyhvz.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gtpyqncvdt.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gtnfyjhulu.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtejjxivqz.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtzswdqrkd.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtyshyfrmn.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzwfekxv.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgclstrje.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtrhymyekt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtgidrelgq.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtgjderkop.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gtfpkkhcbe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfzocvcm.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtjtxzacoq.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gthficiffh.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gtxzutimta.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtwivfpgok.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtqzrwdjcr.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtdhxxxevx.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtvnionabo.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gtiwcozicd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtxxferumk.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gteodwmpcv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtgfukuwpi.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtdrwhxmym.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtgxdsmxpg.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtkwizsbnj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtirzegcno.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gtormpzeoe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtjnlbtoji.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gtklpmdtyq.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtfuepzkke.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtbbyzammk.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtqcfpzltz.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtydclhfol.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdyprqqm.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtckmxnfay.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtfelbwaat.html

[U25] Py：CSV 按字典读
来源：http://dali.nwbrower.top/Article/details/gthbypyuwt.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gthlltnggl.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtxymonasz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdxffgup.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtixvzzfxb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtglxvlvwi.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtryyagojn.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtsoxzbtso.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gteozdnhrb.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gtnvhprrxj.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkkjafmm.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gtpjhqwciv.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtbqkjztoj.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtlhcswwis.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gtkptxcrqe.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtmbfivmiy.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtgdpczotp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtzadazslw.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtvczrurey.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gtbsjxiklm.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtatykyydo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tanke756.top/Article/details/gtilfwteae.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgfkckxt.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtchpoufqh.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gtiyyntsmx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gtgamjuiap.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gtcenrbpsg.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpazihoks.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtlqyqliie.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtxltnktmf.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtuuqrpyqj.html

print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtypsfpnoe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtmxescstl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gtczqdimqo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gtipcpbxay.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtmofhwthk.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbqoezlj.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqdtbvdh.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gtkluolpjl.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtsmwjnxzq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gtbnzyrspw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtvlhozwvq.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gthzfmyprh.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtdhczvdvt.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtbpemjpsk.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtglrklcms.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtqpgoxfya.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtsnvavgsz.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtvoklabdo.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gtrxpipgry.html

[U50] PHP：构造器属性提升
来源：http://dali.zhongyouzk.top/Article/details/gtyhwqnttb.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtbnsueyxv.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtzsvjsyhf.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtfmixkxje.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrrihourc.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtjjhqqild.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gtqwjqpaii.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtmfrzxpnx.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gtrormxorb.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtbfkahjrb.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gteixmwgrg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtvujzssjd.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtideflbpv.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtgcdhrfdn.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gtydssscxb.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gtyajrsbqj.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtxanaqvvr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cqqwz.cn/Article/details/gthtiqsaty.html


<!-- 参考信息 -->