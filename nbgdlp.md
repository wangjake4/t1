代发 wailian999

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2auvrkgkz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2irkbbtvu.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2okrylxjk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2mlpggnfq.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2nikrvuvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2eseijapm.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gt2nimhsqey.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2ewpalvuu.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2guoibwyj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gt2tksmhwhj.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghloosas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gt2bgrmumpj.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2yuefuwnh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swnrkiiv.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2isinzbla.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2ywmfhfys.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gt2cnsavcyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2fbupgsny.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2fiadlcwy.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmczdsfv.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2tzsqyhot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2oreeafor.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gt2tccmbepr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcaakqqw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2phlpxsnd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gt2obrwzgaq.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2guxopveg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2sfxfvhft.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2dwxgtasr.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2iilowfnj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2xzpilaww.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2kxciquhf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2fcikgqvs.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gt2zctecuqq.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gt2yuhmndku.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gt2elvsalwd.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2rsleqabd.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqgasmcu.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcfbnezp.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2lheqyovm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2sbardacu.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2zncgyrzg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tugqiyen.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gt2hndquetj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gt2wfygqtlq.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gt2jjorbscp.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2tgffrfnx.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gt2nfylsoaf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gt2vzvubpka.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2snusvwco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2kuehostf.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2nlqvvndy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2lnozaugi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2skbvgzbe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2tciogjad.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mmxwooih.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2fpqrnjrg.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2uikxcfuy.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2pchtpyaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2uarrdfmx.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhlsnrvm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwquzpb.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gt2jcmecvaw.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2hkudfmok.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2cnhsumsx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxicqgll.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2extetcxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2pcugmhjm.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plqlgqqq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gt2lrgayqbi.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2uthbwnfi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gt2rouimsaz.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gt2cykzcbcy.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2rtfwgtng.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2lymsgczq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gt2kxtxjdmp.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2eaetjebf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gt2fgoumclr.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2kkanxubk.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2fyyhgjak.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gt2bxaajsia.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ljftpzmk.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gt2gzsvetnv.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2kjkgwszk.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gt2eocokpnw.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gt2ydwecybg.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2hqbaoyoe.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2jlieyibm.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2pkrygfdb.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2ibnhukom.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2vjgmsrxc.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2arzzwtkk.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gt2stxnqtwa.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gt2pzeyivhv.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2qbfdjubs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2hpgeswwv.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gt2cfklhvpo.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2gwhqfzit.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gt2wxaodipa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2wigixymn.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ypefxtzi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2oywhwsxv.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gt2wtijacon.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2kuwzojxk.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2oepqntit.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpgyidro.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lveydlqr.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gt2ppmhghmm.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzyravpb.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gt2dauuevkx.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wezfrpta.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2lovtqfbi.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2unqvzrsx.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmrdhceo.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhfglzkw.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2wqoqgvri.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2xmkpmxjy.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2oznqvvee.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2mttdgaad.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqcvchx.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gt2uqaocrdf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gt2gcpekowu.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gt2txxmhhxt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2lcarhstg.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gt2qchpfdrh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2vzyfjkjp.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrcvhqpj.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2vakgkeut.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2azsvwcch.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gt2cjsaptiq.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gt2eqdokfan.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2rehgxecy.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2tcpenjbk.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gt2jhhkmaps.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gt2ffywvjzj.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gt2grfcpjob.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2lnudzggm.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gt2ymejnwjy.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2vljqhksb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gt2dwnxfksp.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2dqwwuhus.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gt2onaefbmr.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2oxszuzuz.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2rjruhdeo.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2cieuwbdo.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gt2yqechgsf.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gt2bdpeuxvq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2aumoydku.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gt2rwxpfaox.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2jvhxknjz.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2giurxnul.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2mgnvvlts.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2mrdcccfq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwqstnqm.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2idqouyqe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2cibmlktd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2owwcrhqz.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2acnhlfqj.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2jrcpwnhf.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2lfumaqxq.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2sxuahryq.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2jimucjys.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2qbzshsmr.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtknwzmo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2suqkrowj.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2bohsvoxw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtltciew.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2fdjfxwyb.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2castheht.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2arejvjqv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2fhznotnb.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfbdjtno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gt2lcxbxdmx.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gt2vubievac.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gt2irkpklrw.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gt2ebyrvecx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gt2kwfzsetg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2glyntdjl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2akphfwiq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qsnovsmc.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2bqcihyjo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gt2qbgfouag.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gt2pzhxtpks.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2wynumhrb.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gt2xbdsmpdi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vydxbuey.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gt2xhmiduvz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2byslvutw.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gt2rslqsldr.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2oqgdgsxa.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2ggafydts.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdfsamjj.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gt2khlqxgfk.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2chibrxfk.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gt2uirkdkna.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gt2unjutmhi.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gt2xtqhfpoe.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gt2sawdltmk.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gt2kfljgmvq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gt2jnhnjddc.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gt2chmczxst.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gt2bhfwpmay.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gt2lwyqqpjv.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gt2metehbuc.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2eqlragju.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2dfjdaubn.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gt2eijtfhjp.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gt2clzcwxah.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gt2zspijbzb.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gt2nezfewrw.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2rmactgkr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gt2gipkfwqy.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnwlneoa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gt2reugjbhg.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2jvlccbqv.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2qkhqvrbc.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gt2halqhjvh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gt2gxtdktfn.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2cfydpqsp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gt2xwgnjrsh.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gt2xutyrlja.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoivjfkr.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gt2tggrccum.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gt2vjfomyva.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gt2qehaoqzv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2qqwuhvkr.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gt2blaalmoi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpotftxe.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2anpahhro.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2zblxuubm.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gt2pwjqmmyr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gt2sghqvhhy.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gt2lxtbgsos.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gt2kdzlotkb.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gt2fsirzavu.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gt2rvhdrgpw.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2wzdemalg.html

@property 与 @x.setter 配合
来源：http://dali.ybcxt.top/Article/details/gt2kkhsyans.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gt2nwfwpfjc.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2ekvubwot.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gt2vxjqbvyp.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qggbgjxy.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiowpkej.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gt2ufhdreev.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2urkzzkxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gt2bxezxepe.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2zstvzbiz.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2cjihwdcp.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2namfmtvx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gt2uxpqyihb.html

[U36] Py：定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2dzwrybky.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gt2rwvqlequ.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gt2yhjhfjef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yonumen.top/Article/details/gt2yxrqmcsi.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gt2qxmgxdxr.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gt2zqphoemd.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2rclxxxnt.html

sys.stdout.isatty()
来源：http://dali.jyoumei.cn/Article/details/gt2dcsjveil.html

[U40] Py：打印到标准错误
来源：http://dali.cdnleiting.top/Article/details/gt2dmrpbfnc.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2teztqgsx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gt2osjwniqf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gt2yicciioy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2xbxxjvhi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2obmofidi.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2vletpspy.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gt2ahpfsybk.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gt2kujprfdr.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2hneigcrx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gt2yvozujnx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2twvrfsoq.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gt2ldpbfjdz.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gt2twugacud.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gt2eozreuhb.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gt2exogjegu.html

[U48] PHP：纯枚举
来源：http://dali.cucudq.cn/Article/details/gt2pnmqwobv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2uumsvlqc.html

[U49] PHP：只读属性
来源：http://dali.316326.xyz/Article/details/gt2clhafncn.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gt2dlxqdedj.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gt2zcnuncvs.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gt2jfcbrnut.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gt2lgqegves.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gt2utegjhoq.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2xxvlsqth.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2jxssojhl.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gt2nstelzvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gt2spowcwek.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqmuabxb.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lliwzrck.html

[U55] PHP：match 表达式
来源：http://dali.birdmap.top/Article/details/gt2ohknlgak.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gt2rckfakmy.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gt2svrbjzvx.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbskuxlm.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2xsootpli.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gt2dxjgjnfi.html

[U58] PHP：数组三件套
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxybfcos.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gt2btjxxvmt.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdpmwfia.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgauftnw.html

[U60] PHP：JSON 编解码
来源：http://dali.hfpthk.cn/Article/details/gt2nhyjweef.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gt2qadqvibe.html


<!-- 参考信息 -->