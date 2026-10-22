代发 wailian999

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2mwuyghow.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2watugnjd.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgcwfglz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2vewnuvrh.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gt2axdmrnro.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2emftgieu.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2etcjomjw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2bgqruvzi.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2tndqlxfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2zenoghxd.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgudmsio.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aiqmyqlb.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2yoecawsh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2oxbgtrfk.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2wupffyym.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruktdmhy.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2cvvacmrc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gt2izewryeo.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqytvqqu.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aknvokpl.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2iccnafnn.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2grxfoqci.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2altfbeyk.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gt2qqkgunie.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2epbdzvdw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glvkwrvx.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2pbesbojp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cxkzwnir.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cueuylgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lafwcgga.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2gyufejto.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2wvsthphw.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2tcsxeqwh.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2sazxmlcl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2mdvxnmqw.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gt2zvjkyjmy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2hljhvfoh.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2knhzstvq.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2dbkqbors.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2wsmpbohx.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2vekvtenk.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gt2liafngzj.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2hzeteyln.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2kskzuxcw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gt2rajwadgf.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gt2roklrede.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2nsdmwtue.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2pomxnlha.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2bgeezuyo.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gt2sxhvbmwn.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2huqwpsit.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gt2akxntftg.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gt2gfnezmit.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2wfvbculp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gt2esbxzseh.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2qfmwqrkg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2kkbmauef.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bwpeilbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gt2plpfkbiq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2aswwyubf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prwlhlqj.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2imoydlwf.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gt2evuuzxtb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2xxpaqvhr.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2tymrnsxu.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2mweaerfp.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2tbtumdjp.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzkvoteb.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gt2quplxnze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecdeamgi.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2zutqviqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2zpprvzfe.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2atosvlij.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2ocggeroj.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2mesawyxp.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guzhzqar.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gt2vxmpztaf.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gt2psjnshsh.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2qopxcxgt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2ytnzkksn.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2xwsewvmq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gt2hvoyiqye.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhccwgcm.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2yfcjppvt.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gt2nzrvuiod.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2ghwwuzrg.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2frjpyaty.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2cydotlmg.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2tcjjayic.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gt2qmiiamib.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2vsidgukj.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2jtjibbjc.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2mfdxboea.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gt2ejlvzodw.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2echxijyf.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gt2hfpwtusb.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gt2omorvowd.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2nayndkel.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2vhoevwrn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2havcblin.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmsrxlct.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gt2majfxame.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gt2yedzrwex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajepnobf.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xptgtnwz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2syckftum.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2qqyescib.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2nkqbckvk.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2xgirjdfr.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqqkxhjw.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gt2ognyndzz.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gt2qjixvdvp.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2gdpzxltm.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2nlehcigs.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gt2icxghzif.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gt2ppwnlhxe.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gt2lghkbiix.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2zexvekmm.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2radbatzi.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gt2togmsqfv.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2fzgrwele.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2xyrxjajz.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gt2njwriuvc.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2yzcgoblz.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gt2hvcpsxcg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gt2eizbhxpq.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwvxrvob.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2vhexgzxk.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2xeafuovh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2dhlslrkc.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2gipqvhwq.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gt2cmghaaab.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2yvmrxjnt.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gt2qrkonjzw.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gt2ordbfkgm.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2xagbdzlh.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2gaztyxhe.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2qjyyjunj.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gt2ewuszrdi.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gt2wtiieszj.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2yjxrvlqm.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gt2laodikho.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gt2wqobjeuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2agyowtja.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2ddqdagyp.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqqqrlwc.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gt2tdklvkve.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2jbgcxnfo.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2tseglmkc.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gt2rfdybrgo.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gt2hhawnszi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2bswvlzdy.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gt2yoasrgpz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gt2lsygstdc.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2rbtlerrg.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gt2kfbxrsle.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2gwtgmqqr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vrydolrr.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2oqinmmrv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gt2ogkxxyca.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkjvfdvl.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2ebaxmkvk.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2sqhgniwl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gt2opkkzsxx.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2qrtbukuc.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2ujwtdijd.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2ghfkhbkk.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gt2fgluukod.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2igcbcbmv.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2biyobccd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2uzlamsvf.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2kvicejvi.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2soxijaga.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2ymrihftp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2ddxomhlw.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gt2ufimjpxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gt2wyqksfqd.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gt2aqrsuucb.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2fwjqnulr.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gt2fmnrujei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2oqetvdhz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dapdaeev.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajkrbduy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rfapyyum.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gt2jnwvtkgg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2ygfpnkua.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gt2effukuae.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gt2nnktrceg.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gt2gqieiytx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gt2gdqipatp.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2omzwrqvr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gt2tatdujhb.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gt2czwfxomo.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2idgcovkw.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gt2qycfzgda.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gt2wfwbqbol.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gt2reegkdtn.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tepddeec.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gt2abfbetoq.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gt2pfpzumlj.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gt2oclxstyq.html

max(d, key=d.get)
来源：http://dali.quarkkingdee.top/Article/details/gt2ndadpcgh.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gt2oyplkzzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2pnopnfqh.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gt2gnlphwof.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gt2awznjkty.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtkcvhr.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2zdduyaqg.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gt2cpxaqvqd.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gt2ggxgxiiu.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gt2hbglipqj.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gt2keopmvzd.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gt2goztzbgb.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gt2sbgssgwb.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gt2htzjjqxv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.smart0.xyz/Article/details/gt2qkfpszec.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gt2shrenwer.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gt2bcovoyay.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2tpjegrro.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2wgwufgwu.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gt2zssskbrt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gt2eecpvxgv.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gt2fwdtmuha.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gt2qazzzhmc.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2ehpsgqmx.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gt2eembheuo.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxqrsnph.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gt2dhxhjqel.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigufen.top/Article/details/gt2dmzvtwmd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2kltphemq.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gt2xeqlzize.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2oyxnxqrv.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2frjlppij.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gt2rbhsihmm.html

[U26] Py：并发下载
来源：http://dali.sweek.top/Article/details/gt2ewczskau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2wcmiqvds.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gt2apmkmufn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gt2vrnpkzjf.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gt2cebrxuon.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gt2aenjhvel.html

[U29] Py：属性校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnosctnx.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gt2pogelpvb.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2stpubzqd.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2koregedd.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2erfccbuj.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gt2ujwkdost.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gt2phxzwvne.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gt2dneojwbe.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2ptuybnrd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gt2hlghmawd.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gt2fhmjvudv.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gt2wpobaose.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gt2htoliksk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gt2bsapmczi.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gt2iygimyiz.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gt2aujvtzdj.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gt2kitvnvxz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gt2eliehmly.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gt2xmxljvuy.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gt2hkyzyvmc.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gt2ndnjkcld.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gt2srdclauc.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gt2mpomulkq.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hotvggai.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gt2raeguseo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpijtefa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gt2jhdjvhsg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sysykeji.top/Article/details/gt2kuvmevhm.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2vqfcedoe.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gt2idcqdyeo.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gt2tlbozluf.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gt2jncajdlf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugijdyla.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2nvvcmibg.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpmtsrnv.html

?string $name = null
来源：http://dali.zycfv.cn/Article/details/gt2todzprom.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gt2skczpkst.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gt2fmudegsj.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gt2yxcjzlsn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2qnebzkmo.html

[U49] PHP：只读属性
来源：http://dali.jiagoushi.top/Article/details/gt2evvttdbi.html

public readonly string $name
来源：http://dali.jyoumei.cn/Article/details/gt2jsetkyri.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmrafbxq.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vodjnwbh.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gt2zpgflxna.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuplrrwk.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2xneoksqx.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gt2bswqsvro.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gt2lvgdsvsf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gt2gebjxlnk.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gt2kohlhecr.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gt2uobwewgx.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gt2cdigouuy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2uhdyzhff.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2ngwmlklz.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2hyxqmkdc.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2ekpfkksc.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gt2mipvqyho.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gt2eoigjury.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2odkfepvl.html


<!-- 参考信息 -->