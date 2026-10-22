代发 wailian999

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2dlpclyww.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2rhtmatql.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2fjeryuru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2hsvemvbo.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2tqsxuowd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2wnboylud.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2zqoghqel.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2jvfcvwki.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gt2zoknydfm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deavyiiu.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffsljlvc.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gt2blpfxmbu.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymdwlekt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gt2gkgtpspw.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2evkomcag.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gt2rovxatrz.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2ylgxstpc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhzjpnuy.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2hwmoczkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gt2bazbfsbt.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prcqlhjk.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2cvsbsaqq.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gt2zjmpqteq.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2xtaxfrwh.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2wzuczbyp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gt2innmvnqa.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gt2kuluesor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbasbsqy.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2rtbonrtu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gt2jvfzarzk.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2iiqvahhz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixkelgbu.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gt2utxhqxkc.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gt2qnyivwgm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2jqswjdxd.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2ddaabafh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2dblalxsa.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozxrnehs.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2nosaimru.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2bguotmtd.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2iuipvxuu.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2batxormg.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2mxtwwide.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2rkwmlmwp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gt2dwmkaexo.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gt2utmqraxs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gt2zjpsijsl.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gt2rvjwsmbk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2evwnovfg.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2fwrtxzcs.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2hfwmzshd.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2mwvnmsoq.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2kljoluam.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gt2kfvjgdup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2dskwxowx.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2rzqzoffu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2intgetho.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2atjocgtr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2jbmzcuht.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ilfxoayl.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2fwwczbpc.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2rzanuack.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2lfuckuzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gt2uozwooap.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2uanyoioc.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtndiuqg.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmgaivba.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gt2puaedfiv.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2museyopi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2psgkvptw.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2berdtxos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2ustdqhtr.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2wjsiperj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kiuwsdxn.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2sryintux.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2bqtsslpt.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2qlgpdfcq.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2ssuzrfpm.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gt2lpqgyydl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2usereckk.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2wwxhgdlp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2ntoiqkim.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2ucezdyzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2uyqzxmhh.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2bqvolzhb.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gt2pzpnpbxo.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhnappcq.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2lgvvizrf.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gt2csafhwag.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gt2eamqgcbm.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2vckuyjya.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2yqgzdmve.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2jgxtueah.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2biqexrzw.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2srvbqypa.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrzgdwze.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2guszctqx.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2rcerixim.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gt2lsezgjmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2qxldzzjz.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gt2xbbhpmsq.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gt2oxdywjyi.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2ztarilye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2sjobxskp.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2hxorhshs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2ajyfekjp.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2rhmzhpok.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2pahzzgxo.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvuwforg.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gt2hihzfwyy.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gt2zywfkdvl.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2yrhinarf.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2ilclnflv.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2sesjlusy.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cchxrvkh.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gt2puujzels.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2gsjbfszb.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxoyojsw.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2ydxadndb.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2jhnaxgtz.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2fkwmlhzk.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2tcerccqx.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gt2rjbuxcwi.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2tzrwikho.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gt2sslqirxw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gt2uexwwonc.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfrbfuak.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2xozlmzzv.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gt2zncvrene.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2obonlnnl.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gt2cmcoocmk.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdfgzirl.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2izxznmfm.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2wkvhkhrv.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gt2lxebdcii.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2kkwluvsl.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2pdnfqvpi.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gt2rjuxxhbb.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2kpamqwnn.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gt2qgdvlrxx.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmjmrorb.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gt2swscflvz.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2owzjtezf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gt2rurfoyjr.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2xpvjzdhk.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gt2tiqzslyl.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gt2ljifoxbs.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gt2uxqwidxm.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2kjtgrnkn.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gt2tzmkkhlh.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2iyypegcs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zusbvytn.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gt2xrnzbuuu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gt2qleurtoi.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2otoakmlr.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2yrobyyni.html

[T49] Perl：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjzuraea.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2duwtnspq.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2knfkogvl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gt2exgevckz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2zrddliyt.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2ghkubepy.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2esvjypxq.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2uanmpwik.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2xjhqkgjg.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2uemvcnyp.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2xignyfsj.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgeyzaat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gt2pzcmvwvc.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2bgyqureu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kdhmmapa.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gt2pkjuhlbt.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2lgawbjxx.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2eixqutkb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2kowgrslc.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gt2qarqdekr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gt2jagjahrb.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2kwjgccid.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2mhijqhfe.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2vhdcqvyd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gt2hvbtjltp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vmaogpdr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gt2nojwlhcm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kljzozfu.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpwxjmxn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gt2cavkuwwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2fvbiolqx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gt2waesxexx.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2dfmusqeu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2ysbortdn.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgzlpdoh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtforeut.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gt2auxucdbj.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2uxxgdfxi.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gt2vwmfxcsz.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gt2ehlxedlt.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcbheqzt.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gt2rknthsdl.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2zvzncwlb.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2vjztilvl.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gt2kdrzbkqx.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gt2iojharoc.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbnmuaha.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyspowif.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2paiofymw.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdahavdq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gt2npeslejg.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gt2endfxebu.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqmnhzbz.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnbxdahq.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2nttgakph.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gt2mpjdvikm.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gt2pqyyppqr.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gt2uoterlju.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gt2lmfhooqc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gt2mrcjhqpw.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2egpgulrx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2kwavierv.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gt2ekpthepe.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2uwozrcqh.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gt2izhjsnlf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gt2iwlhoils.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gt2uscpowdv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gt2xxesicyq.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gt2vxbsuzzq.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gt2inlynztz.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gt2hqnogihx.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gt2khcgtohy.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gt2kykveqjb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hfpthk.cn/Article/details/gt2syuuioqh.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gt2binoxvfi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2vyxdrgpx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gt2avnwmdft.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gt2rlhqyrkp.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gt2mpvczfwx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gt2jwxodfqj.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gt2fzfionaf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gt2guaqtuoj.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gt2xmlexaei.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gt2paevwthg.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gt2klhqnbwe.html

@property 与 @x.setter 配合
来源：http://dali.zhixingplan.top/Article/details/gt2qvryoglw.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdvpahjp.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2padkowjm.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2sxzstxpf.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gt2mxrwtpba.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2uofinfsi.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gt2lwgunjsm.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gt2depqsjpn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2ilmutezk.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gt2uuzzqomg.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gt2uduetsvg.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gt2vpddlacs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gt2kondsjnb.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gt2zzywivsi.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gt2fenaavid.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2gfzbvzgg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2swrwhtcp.html

[U38] Py：获取脚本所在目录
来源：http://dali.yangfankeji.com/Article/details/gt2uvdtvfnc.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2fthqefqo.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gt2wwprislx.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gt2afsjnprd.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2xnwqenwr.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyymqehk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gt2nlxiznzb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gt2owwnljts.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxtleuiz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gt2pulsihsr.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gt2zsqzppxw.html

namespace App\Http;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jluajydi.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gt2xjgmljhl.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gt2grxaldlf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gt2jwjcapxi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nxmyeyys.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2nulhjglp.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2fmggwdjn.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gt2nqntypur.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gt2kfksxzuz.html

[U48] PHP：纯枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2uddwbtdn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gt2hujibbyq.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gt2qheifvzq.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gt2yjxybfgu.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gt2vzrjtnro.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2oezuyogv.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuifidsz.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gt2ndnvndjj.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gt2jrwpktjh.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2qnparjqr.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gt2gyvipgyn.html

$v = $a ?? $b ?? "default";
来源：http://dali.ydzc1.top/Article/details/gt2wywqlnjx.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gt2rmayvvuh.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gt2vttfdqzz.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gt2ubgebwob.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2lorgijil.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gt2zferpbgs.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2itjsaffr.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2vizegjyi.html

"值: {$a}"
来源：http://dali.nwbrower.top/Article/details/gt2lhgphaxn.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2kofxdkiv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgymzcia.html


<!-- 参考信息 -->