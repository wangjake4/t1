代发 wailian999

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gt2myhlldcq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2mhqhwdjx.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2bepkxxhz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2aaepuztp.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gt2svwkiuwc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2oxfjxqkt.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gt2rkdxjijy.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxepbtnm.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2xkaspflr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gt2yzkvolte.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2zhedsaib.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gt2jiqdburf.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2aukqgovl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyvhgrlz.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2vpjmbdhe.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gt2gqfinxft.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gt2hlvioizq.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2gwkvazsd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkmznjv.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2bcgtsaok.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2hzzaugmq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2jlzcqqwj.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2virgwswc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gt2mrauuwqq.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edtufgkm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gt2waiqfmtk.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2orrjmfmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gt2zfpmsyem.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2oatpmeep.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2kpqniwpw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gt2fiuzcbdx.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gt2qhbrqaqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2phrtcuag.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcsrfipp.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gt2dvyialov.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oozlaxtb.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2kfiexosj.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2pbueefqs.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gt2zlmjbuiu.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gt2ghkjeizk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2gbijczas.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2audrljtk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2wtclsgkp.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2megcmwkw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gt2evywuvxg.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2uzogpkwz.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huxnavna.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gt2sicfodzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2dujbslxu.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2olsntach.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mygvfdxm.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gt2yhocqurj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2ftunecva.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlrjsfhu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekspyxhl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wopkazws.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2nrftvtpq.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2njzgztzq.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2eudrelsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2vsggvozo.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2gqoeumbv.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2ueypenzk.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2uoqdqida.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gt2vmcjrulc.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gt2xduasnwz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gt2vhtstxsf.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2dhakxpcn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvsjxhs.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2thambzkd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2dvgizwuz.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2easjdbtd.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2mnvrpdwu.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2eoqoozhq.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2lfcptxpd.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2glhpcirp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gt2ftgfduee.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gt2drjhtazc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gt2jsceuhyx.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftamvrze.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2tjislwsi.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2sytpmaya.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2kszbdokw.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gt2qequunrr.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2hglqpqxb.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2tdyuzkzt.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2gdexzrcn.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gt2vbjvdlil.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2myszfbvq.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2zlqijosh.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gt2vahfljhw.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzjsbrjy.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gt2kryevhtg.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2owgjvzje.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gt2xivbxdyi.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2vukqpgfs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggnhxcvd.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gt2hjlkipvp.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2tfgyzonk.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2swmnzrbq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gt2zvazxnei.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2xrnfmbgy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gt2ovrmbrfu.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gt2vkrlrelx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2yherarhv.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gt2ysmcivyb.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itjiylsz.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gt2biogqauu.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gt2webmqxsk.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gt2qpdpgdkk.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2itosaria.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srzblptf.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2fwwqvhtt.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2rgtdnica.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gt2ylfdvjpd.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gt2ishccbfo.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gt2juocvecy.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxfbiigs.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2fpjalibe.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgvzxvdp.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gt2scjfcrbf.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gt2xoaawcuj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2uiewiqvj.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2yxpiyfuk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gt2duowtqqt.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2knpvmaun.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkrvpdhd.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2ttltdxgr.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gt2anrbcjad.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2jmxvrzgr.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gt2bghxafmo.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gt2bazmwebg.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gt2utqqeuei.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2cfhsgugf.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxweyiuj.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2cskzgfjf.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2ftzzylit.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2wchepdse.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gt2jlktpvdu.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gt2auagrckt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gt2ngquvnkn.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yotmacmo.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gt2nvbwdtht.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gt2msnfkndb.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2pctydtvc.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbrolypx.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gt2idvczyqj.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajdxqqbx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gt2mqzdamwi.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gt2pnawfuoo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gt2czgecjeb.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2cwilpthq.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2frbjiarf.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gt2ryexuszp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2mxgpgmlg.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2thrswssg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2xdfmlhks.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ordqbvig.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2sextfark.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2jinkkeyq.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2agdjlviq.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2puabdowm.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2euoqugah.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2vhieytwo.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsmodfcn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gt2kywxperj.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2dchspkyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gt2iaollnbq.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2tnwsnxcq.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2jiqgnlgx.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cebmicqz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vataqthn.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2ljknaltz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2ywmpzbra.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gt2kkieapai.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2nshalnug.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2qfgljvwk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2ksyydpfy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2decvgsxc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gt2uvchljck.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2uypkzmtp.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gt2rzunjksc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gt2gmjxerri.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gt2aklehgah.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2wtvfpasf.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyinrgnb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gt2oohotxjn.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxgyzgoc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2nfthidgu.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2xbfwxfhl.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2xpqzjblq.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gt2yovsskyq.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucsqynel.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gt2uaprbrbq.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gt2egxronlz.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gt2dlnhzilz.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjalzyni.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gt2xaklxrrg.html

max(d, key=d.get)
来源：http://dali.svipenyu.cn/Article/details/gt2wggrkzqb.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gt2ldpjrihr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gt2cdpbutxs.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2obsegomg.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbjwuvps.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2kkknxnqe.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iolfzowm.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gt2rdjmuslj.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gt2cnbbzknh.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gt2iseyoyts.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2cmsghtgx.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gt2zvrojzub.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmvwwgmb.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gt2emzmqgow.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gt2ojzkqwxv.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gt2sygjnyvy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gt2xtqasenm.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2zyzjskgd.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gt2pynngfin.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2apvwiolp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2nvwsxqmp.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gt2brxagatb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgfzy.top/Article/details/gt2rwbrkvnt.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gt2dhwlvrop.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gt2nsbohpjc.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gt2kujlqtwb.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gt2glicivhe.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2ztibtmab.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gt2iqbzctsb.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gt2ejmyryex.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2raxcumqi.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgvqvccn.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gt2jzioealz.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gt2huyyuxgy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfazmtpq.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gt2rwkjincr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gt2dnlxbpkb.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gt2kegsajkt.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gt2kmpgzcgw.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2levdoejj.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrtbdabw.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndockjex.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gt2sunbltbl.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2kigmktsl.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gt2rixzlczg.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2uieqirnh.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gt2lpqxznwg.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gt2kcdoxrwl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2yigiqzuj.html

[U34] Py：判断编码
来源：http://dali.tian-w.cn/Article/details/gt2llxezagz.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gt2xiqilmkf.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2qnzrldvb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gt2gwcocxqp.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2hingdwhd.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gt2okqsfamg.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gt2wfdvhczn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gt2jnfsnxxq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gt2bdaeryry.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gt2aycztjuq.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gt2yagjbgzx.html

sys.stdout.isatty()
来源：http://dali.jianghu66.top/Article/details/gt2dufvkbwp.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gt2nocujsko.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yibsvvsx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gt2xechnftr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gt2ojbnttmj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gt2hfljaled.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gt2iychwbgr.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gt2nfjctxnr.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gt2jfquemko.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gt2mgyannib.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2anaynhkn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gt2ikqsmpgf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2bfrqmjni.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjffjset.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gt2lbwshvzg.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2esljphun.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gt2qkurdluy.html

[U48] PHP：纯枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvwoytgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gt2tqzibggg.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gt2fxurcctz.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gt2ezzxwqqu.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gt2rljjzcbc.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fzfwcuiu.html

[U51] PHP：数组解构
来源：http://dali.haohaochexian.top/Article/details/gt2ntggfoqq.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gt2jqpxbxhr.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2kfulhfsb.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnbryqxb.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gt2ntgtyzaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2adeyflsd.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gt2livdmhxm.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2wuvyucum.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gt2byhzovex.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2tszpkchu.html

[U56] PHP：命名参数
来源：http://dali.svipenyu.cn/Article/details/gt2hyyvirlk.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2opkcuqcg.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2tvixzfry.html

"值: {$a}"
来源：http://dali.fengsongda.top/Article/details/gt2glilpkyk.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gt2tplsbjwf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yonumen.top/Article/details/gt2wvfievdt.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gt2mfozblkq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2hxyqeqpd.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gt2ospwjuvo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gt2xbfsbsyd.html


<!-- 参考信息 -->