代发 wailian999

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtrqpkddyp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtkyipzguz.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtrcgsanja.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtelxsfrul.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtbntizxxw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtaoeuezwm.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtviwyxugb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtrewfcbld.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtvbvdygpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpvzgnrno.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtjdokfaef.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtirourqxx.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gttopcwtli.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtejqcxaye.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtrpabuljn.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtdadwjltc.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtfvroskse.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtoojowtcp.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtvnqlculj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtlkdacslc.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtjbfdoudn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtmheokvkr.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtlamhlwye.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtkknkjdqm.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtfezpaqiy.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtgfyilgzq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtjugniifk.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtapaobbqv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtgdpbrgzw.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctwaaffk.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gtclstqkmk.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtcnfysbzu.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtabemwbhs.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtyykubzbr.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtaumhzvse.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtkqhndaej.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtlyhurokv.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtlbaloqoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtwqiucjge.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtvharulrm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtnhijiahu.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtrhzthzts.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtctalojff.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtodyzgznk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjitsbcez.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gthwrljkxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtbcnrbycw.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtqernuugc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtzjhtpsbr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmwlybmxm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtwlcdszgk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjhhobldp.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtmccltqaq.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtchwjongz.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtvazwrtch.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gteknswfsq.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtbjzheiri.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtncjdxajt.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtrovxplak.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtfefeivbv.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtrpkszvpt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gtmbnmkese.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynmavwrv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtcymnmguo.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtvguwasiw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtaoixdygi.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtxpwrjwsw.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtnwtimneo.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtcepdyygq.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gthqbusspq.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtlxffrmkm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkyptdkw.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtzbsodndd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtdthwtzxv.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gthjoncgqa.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtkpebyoqk.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gthsbbjwfw.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gthphlqync.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtzmegbcyb.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gttlliipuy.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtwnyqacfo.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtcrwkhkvy.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtdfoahbdm.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtgucjaqzi.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gttfaeikwr.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gttpsyzukc.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtezxydzsh.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gteoqgeach.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtbbagyjmw.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuskvjkwf.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtyrkahcus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtdoeqcypz.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gthsiszcmp.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtukwkaqzr.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtdyyhrorj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtjsmxcppw.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gthgzvmgdk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gthmsvwysj.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtvxcfjqby.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtygenbsho.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacqycpxb.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtcndymsnu.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtyxjzjhll.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gthaxaican.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gthzheaopo.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtmvwwvvte.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtwrlovccu.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtsvkhujoo.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbrefsln.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gthdrokuse.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtwpqftehk.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtmiigqsyx.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtisgwkslo.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gthxgksvzy.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gtjjuaanxh.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtawnfjwgp.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtzwhxnfbu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtfjtuyizi.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtirmuhskz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtjyjrgwfd.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtrflhuynu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtuoifsqoy.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtvdxnliys.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcraocks.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtdatngqfh.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltskbvat.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtqbkujaas.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtklmztybm.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtirelchxd.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfomwuli.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtqjyqrqdy.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtxsoujgiw.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtddylafix.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtkhpvnziz.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gtlwcodadd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtywudxaww.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtfklddgnt.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtzacgdkrk.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtfzpucxfm.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcvvbsrxi.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtyqyawdnd.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtmiagjrcm.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtxprkrine.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtychxbffq.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtindaotsd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtylinxmsi.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtvbiriutx.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtpvdmdquo.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtafsfpmqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtmuzqmjiv.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtidlckxtd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gtiihnjonx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtxkiubhqd.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtwhxofyjn.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtchsbyssj.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gttrxaqoft.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtbmfznsft.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gttiucsqoz.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtaqchbxrj.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtfuibqmrz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtozfrczcy.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtculnxmbx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gttoaqflye.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtnwvcmmea.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gtqjpqkrxu.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtafbhrlhf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtltltpubr.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkluhvzx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtgcpbrcqm.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gthnauchst.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtuyqnbdvt.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtanyhioot.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtivmgdzjp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtawhcxnxy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtprxwmtof.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbifiykix.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnpufqla.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtyfeqevye.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtqvzkqpwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtssjyjsnk.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtpwahjine.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtxrszwjuu.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtxlzuntmw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gtcjxjlwyn.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtevmhwsea.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtoeesxuay.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtasmuvzfo.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtuljqcvmt.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtjiiwhkem.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwsfpjmw.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtrvirylyp.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtwecbyrrz.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyjgbegq.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gtedsrjqvy.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtogagaooq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtqzppukee.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtslhhzhvw.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtiyqfurwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gtaenylitc.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtzqfpvhhh.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtklfupruo.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gtiasmtikx.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gtfeiewxay.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtuaykdzvx.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtnntzkvib.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gthjdwbjch.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtqjtpraca.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtzpfihqqm.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtvwulrpdb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gtqemksbsy.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gtiqxbwzja.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtoiddswfn.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gtsuzysciz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtrimvzlnh.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtofmhrjzk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtpifbtrhv.html

[U21] Py：自定义上下文管理器
来源：http://dali.ivvv.top/Article/details/gtvswgoznh.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtqcguzgfc.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gtpafxgtnl.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gthidlbvdt.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtgukawwpw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gtaoctzkjo.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtbotatadd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtfokxfpek.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gttnbybdwi.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgtscbia.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gtutjzudan.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtzvxjmghr.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtjxmddcdx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gtriliaaqd.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtwkpkiyle.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtrtqfnckq.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtdvopesme.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gtgqdcezwm.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevhdvtqd.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtntvrnvrp.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gthvmoxvsw.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtmmnmajny.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtghyoafgu.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtgbxefypn.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtnbitxclm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtkjtbsudy.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtrrbclewj.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtoyqnperv.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtrjkqqkjb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtpbqqluqo.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gtxqbkwvcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtnyvbbqpe.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtiydnjhvi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtdmrhcsmh.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gtoukebfcv.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtmmwsnnat.html

[U39] Py：判断是否在交互环境
来源：http://dali.hywenlv.cn/Article/details/gtnoxhllhp.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtixfftmgb.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtblkqqmmb.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtlodbgbta.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtxaufzoik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gtqdenieyf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gtceunaxob.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtrjnxxoer.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtpoixzlgu.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtsqwqdnsb.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtnmkckfnn.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtadytslzu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtfctvuwok.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtvgvnnemu.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtadwsuqea.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtrcdlthfe.html

[U47] PHP：联合类型
来源：http://dali.hnqzz.top/Article/details/gtahvtcjlf.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtsscpjben.html

[U48] PHP：纯枚举
来源：http://dali.jinqigfzy.top/Article/details/gtepknxpow.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtwpaukuba.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtrsjoofyp.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtbpyvmfku.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtvouggfqs.html

public function __construct(private int $id) {}
来源：http://dali.hywenlv.cn/Article/details/gtpmumlmgk.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gtwufvdvtk.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtrkpquaos.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtulncdzip.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbimeapgj.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gtbljqgukb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gtrmzzrvrl.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtwbqoyrjc.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gtcmieqyif.html

[U55] PHP：match 表达式
来源：http://dali.yj202588.top/Article/details/gtzeuprbtg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gtyeogmgcc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtnpbzfaib.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtoejsozhg.html

[U57] PHP：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gthmclnujv.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gttljfloyp.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtwtbptqty.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gtwqnaezzs.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gthrvargta.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtybmsxhpt.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gtqtsdcacs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtnlcuxggk.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtzslmqfaa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtoighpnnf.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtxsfonuua.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtrnsqtluv.html


<!-- 参考信息 -->