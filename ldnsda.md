代发 wailian999

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gt2ydwrkhnv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gt2dtbqktvb.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gt2juiwwjof.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uzedvmah.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2ntqecsgt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2agrfubfh.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2zvycgdnf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2eugiibac.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gt2sjeykwxo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2waplpowf.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gt2crqwvvfo.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2uxgvvttz.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gt2sgqntczx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gt2dyhbxrwv.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gt2geulaohi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2zqhjvoeg.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gt2zwsskole.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2qcskwvmd.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gt2doialkbh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2nowclgxl.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gt2usyczlst.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2vffkkbao.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2iclmzapu.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnczspqg.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gt2kywpwhsi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2yfhqmtpe.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2tjdmgjnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2gijihfes.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2qautqmtx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2wkasxgdy.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2jbofzqis.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gt2szebyjva.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2resfltdb.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2nabkesha.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvxvrnif.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2rymxrjdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2zoguwexm.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gt2veyamzpx.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2konwhgkn.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gt2qnvobdjf.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2zyhhovwh.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gt2neuhoymt.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2zkqltjbe.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2nsgtqzqm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2fluisixs.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gt2dnqcjllh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohueeges.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twaiumet.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2pxnzoqfc.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfmpcqvg.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2yzyrfcwv.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gt2gbqousqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2baqrcamu.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2tczrtiko.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gt2odtlwzev.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2vjhuuqkz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2euqcoftl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehvrtcoq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2nqpftilo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xrbapjpg.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2iazrgxmy.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2qsjwocok.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2fypeowpi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2pdcizgau.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2qyymxvpi.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2rsjbjure.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gt2zgwpwbpk.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpkesimf.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2ushvwysw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gt2nbsryhtq.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmahkxfn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2aowetfls.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2tundejqk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gt2cnlktoom.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gt2jxwmcsbv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwuossdu.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gt2dliydemv.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2qeipyagg.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gt2qwcqxrhw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2clmvcput.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2qfwlwkxj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xptogonf.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gt2schdbmpe.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2xpqyzrzj.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2kazveiry.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2krrrbudr.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gt2pyomwmfv.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gt2shktkdst.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gt2mqvqtlaq.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gt2edtxbixt.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2hrhincmc.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2ggyasyte.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnciokil.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gt2pjqthrzh.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2ycuphwuq.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gt2vgypjrgr.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2wlvodpzc.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gt2hfjlqybw.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gt2otpauvre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2bjedvlbb.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2jmanuyzl.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gt2tbhiltdf.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2cxclushi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gt2ssjbjhtj.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gt2nutnjvww.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gt2cjuhvvee.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2londdvto.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdasmnvk.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gt2hkbotqyv.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gt2tjquxfae.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2dxppnknn.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2etpdatxa.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2vehcdfsp.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2vgzemnyh.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2wsodtari.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shxwefge.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2apmqyzfg.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2cadfsdcj.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gt2kqzbavwn.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2artntrtz.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2eezywecp.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2paejblqb.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gt2daxroibw.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2jjweulas.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2enfbtxle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2kluqxnot.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2agskchct.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gt2ixjbufrh.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gt2lbpoglpc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2dkqmiwaa.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gt2xzzuhgte.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gt2ugkpdncq.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2esxwuhoj.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2ayyixhss.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gt2jwiqgqgg.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gt2twdxcqbi.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2giulkick.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbfnjcmy.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2hgmmhnia.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2htmcndso.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2slbosjhg.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2blxsuhyk.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2auegvtys.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gt2ozvnjthm.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2kfnfcpzw.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbqsshkt.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gt2yxhegcib.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2zpawypvd.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gt2sxdgsvip.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2yqwrsxzs.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gt2tbrxqfho.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2bqxdvmsb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkabmny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gt2xhkhefge.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2hypnfacg.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gt2cgjyqzjk.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2ywyiymqy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ilmghplz.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2mzeqxilk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gt2veroipgf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gt2lrmfaqku.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2kbxmijhk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcfqegm.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2cdmfpbxk.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gt2azgshfyl.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2hofbhxsa.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2aujehdub.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2royipwof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2nzmfakeb.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwcacvoz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2ewqbcixa.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gt2ymbagcun.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2ajbnozjb.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2fwsmrinw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvrievsi.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gt2ocfgijwb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gt2ynzlexat.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2twmeqrhi.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2qwxqkdla.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gt2lsikfmbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2szptgsgp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uwdzftac.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gt2oauyjqig.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ounijwsi.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2yytiurhl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2xejxvpiz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gt2lmmcujzj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gt2npgrlvcl.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2bfpwwegu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gt2lkiqplpy.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gt2gmzyovwo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2uvqxvhix.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gt2iaasxjzy.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2yoddhcgx.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gt2nweyouym.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gt2rymzuota.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gt2nskmcbsz.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gt2qhkupoym.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2gofiffaa.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikllmdjk.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2bvdgqaso.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gt2oibtuhjc.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdjlrths.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gt2wxwnziym.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ewqmtwup.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gt2osbpipps.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gt2ghmkcoje.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2zvaeptom.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2oegburmq.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gt2zvfzqhmt.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzdbtxvt.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2kjwwypij.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gt2qnpexvsw.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gt2nuqlykdk.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2auushbwu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gt2xifnxecc.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2lonjyoss.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gt2maqgnjpv.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gt2skighrck.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2ewuogdku.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gt2swdqbybw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2umkuenrw.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2njqoxzcl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gt2dgabfyjo.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2urmrjcch.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gt2iugkomle.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2jvxiibfr.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gt2oiigkugp.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2grrkbehs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvwnwfya.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gt2irjqlvhy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2qqeojxar.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gt2djpswuax.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2irylezao.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gt2unczjcse.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258.top/Article/details/gt2oipludsm.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gt2xdddqmvb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gt2rcmiruch.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gt2qsloiekv.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gt2vgdjyklc.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twbxsmlh.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2iqfoxmpy.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2pfgswddf.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvqbwuys.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gt2zhqtmswp.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gt2dmhyhnff.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2fsspcomf.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2wscdajkq.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gt2hwkppiud.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gt2dicvzgnl.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gt2cmhxygns.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gt2tzbudyzb.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gt2jupelewa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gt2jhgldcae.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2jhqopahs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gt2ggjiwnpe.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gt2jzynpdar.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gt2szvmbnsy.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gt2xabnmprw.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gt2mhciiljo.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2zctswdng.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gt2vcahzmgt.html

[U40] Py：打印到标准错误
来源：http://dali.guannengcc.top/Article/details/gt2cjemeyix.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emthmrpz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gt2fgzyezou.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbgxmhqu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gt2bnylmwub.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gt2lhseuhvs.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfsicycx.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gt2vxgfkofo.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2jolhdhpu.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnytdpiw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ebagdfyr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2fydnrlyl.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2johvadlg.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gt2eulveipj.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gt2qqhoxkbt.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nenhhgwy.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gt2vrbhnkfm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gt2mhmxtmto.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gt2xiarqxyz.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gt2uqdvafwl.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gt2pxpgwfbo.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjsoezzs.html

[U51] PHP：数组解构
来源：http://dali.xziqi.cn/Article/details/gt2syioarsj.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gt2tmlvqlyz.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2geylesha.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gt2vvnljrtf.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sasmkwzn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gt2zwvqfpqa.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gt2phymscyi.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2svtqusym.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2lpfkfhko.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hammf.cn/Article/details/gt2aosibmay.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gt2jlhnvdke.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2eenzeqjv.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2qbslsatu.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gt2pftgnqew.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gt2nuaxqtny.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gt2bqfxfieo.html


<!-- 参考信息 -->