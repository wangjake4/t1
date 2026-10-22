代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfsygkie.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2zowmicbr.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekrtkmlu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznnlcez.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2cqwaazwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2eawixono.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gt2joeyxjvn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2wltmanpl.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2ylwodkwk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akejidqa.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2negilxat.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2neseqbhd.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2qcodbwsa.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gt2aixjbcpi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2otjpfcsy.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prujptws.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2gyrzuqsc.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfpywsij.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjlzxtdc.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2kjckffqi.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2yrcbbdtd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2garofmvp.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igkzumsl.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltsbaciu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gt2buuclnou.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2omaiayyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2nlagzbvq.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywzexvkc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gt2rekygcfy.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgmbwybq.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2rhgqyxtr.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2shzjvpqp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdywjtif.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2nphmiyvh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsxmjktb.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2pduzqmxp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2kpqwrxgj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cixedcby.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrcftvme.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxoihzfn.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2wvyvseyz.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2hcjoladd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mivvpjrf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2wkbmfeia.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gt2irehsbzn.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2cadowyjo.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2xlrgxfve.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2hpfmmmud.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2yjugsekq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2pdjoqfho.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2kjcckuvq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2kzugmjsl.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gt2qjreiuhl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gt2wixyiauh.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2skdmcutp.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gt2wfhrqfno.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2xqbybcpz.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gt2qfnhhqyd.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2aseglvju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gt2gjkblsor.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otugyvxo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gt2bfsibrec.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2tbnbbsig.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2wjbmmbcl.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gt2ipbsjqvd.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gt2exvutqvy.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2crtxtwqp.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlcewkfh.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2izkzfuti.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2yhbcygof.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gt2pluoewfk.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2pdvidfrs.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2iumpmfgo.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2mwpzprex.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2lmcjctlb.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2eblcczcz.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2lpmwftel.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gt2zwesejrc.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gt2nzwnouoi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gt2soixswvp.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gt2nnmvtfxb.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gt2muanbmyj.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2dahkhopx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2goamsxxw.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fomvltnu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2piaaatam.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gt2gwltffuw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2prlhxero.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gt2qomlefxg.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gt2zckxezbx.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gt2eokkeqgw.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gt2htljohgd.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2bgcgsqmk.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2reebzbzt.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gt2pzmijkjh.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gt2ppfxcugg.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkoxvspb.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gt2abxofzar.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gt2aosdmxjg.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpvxxwrf.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gt2zqbcqmzs.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcstpjcn.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmjghzpg.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2lsepyrwl.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2awuevspf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2gjecievr.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gt2qgauiybx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gt2auyguktn.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2jxevjzos.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2jgdolwvl.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikcfkktp.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gt2plwnybmp.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2gzjheyuq.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gt2ylbgsofm.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gt2fiqmhiaz.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gt2blsbkglo.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2abuuiznf.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gt2xumfrsdk.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gt2ogzvfxyw.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gt2rkntvvgn.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2qlnpdvqq.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gt2izoqxxzh.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gt2bwsptlqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gt2qpzzdgfc.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2bmzdzodn.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2evtuhxuj.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gt2idzvushe.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gt2fztwxcuo.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2fskrjtvk.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gt2ocraxikd.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gt2zjkznczh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gt2jkuxakhx.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2bcweakxi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ycikthnc.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gt2ckcufxpf.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gt2hqdhrgqs.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlqdlrok.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsfshjvw.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2pilrdgpk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjcryyor.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gt2wfymnoql.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2yfrjmfdt.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2kggwuonl.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2zjispslf.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2amxuvqqt.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2tovzignj.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2yiepmgbz.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2xgohdzvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2twsweoho.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2ohwdmiht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gt2pinxahaw.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gt2tetrfrnb.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2pqetovyb.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2odglmrac.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yongpay.top/Article/details/gt2igecxziu.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gt2nkduaoet.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gt2crbxvfgq.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2ekpvmdae.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rszbfojm.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gt2jiycfdpy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gt2pymbtooz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lwhhjncx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2gmfhbypt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ismdqamd.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2lhdprqiw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gt2fiddgqpl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gt2zeqpevdb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ttqxioru.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gavapkgw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gt2gngwcmac.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgjqlppx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gt2yccwbwkc.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gt2tgoocxfr.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2sxzlilvq.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2zdcmuybb.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfwsgyks.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gt2ziyzhhwa.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gt2fmfmixyq.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gt2adldqzwh.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2rdcnuejg.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gt2vpkuxyjx.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gt2rtrtoqbl.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjyzcbxj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gt2pvgaotbo.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2pngeobez.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjmmfnvt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gt2spyppcua.html

Counter(arr).most_common(3)
来源：http://dali.meibo888.top/Article/details/gt2sznckerq.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2qwnzhggu.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gt2igftexof.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gt2osjlsllv.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gt2qkxgtwce.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gt2dyanccvy.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gt2ihmxvvmb.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2gdejtcls.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cashguo.top/Article/details/gt2vexqgctr.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gt2ouggwdjk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2jyxwazrb.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2buqiepbu.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2hbtpbqra.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2etvmyiwr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gt2nlxmlumk.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gt2mmtjsqsk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gt2dlhbcenj.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gt2xufalfdy.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2lwrbyzub.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gt2yykqqlbm.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gt2toezfqaq.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gt2qgyipxux.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxuesqol.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gt2denurkgj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2gcgoatqs.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2ddcralnp.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gt2npxsbfxt.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gt2vorjlmjr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gt2hzfufjxy.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2twcbpyms.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gt2tvpzbxar.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gt2ccisueul.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gt2pokhbjyy.html

[U29] Py：属性校验
来源：http://dali.xuanzx.com/Article/details/gt2lunzmmpi.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gt2slvmgzwt.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gt2crmhewac.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxcahbit.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gt2jpriqgcn.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gt2juqkizqu.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gt2ifdcpquz.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmgyppby.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gt2acqoobxn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gt2jyeagphb.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gt2bjkxahwy.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gt2pucztecq.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gt2tigwyqoi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gt2etwrwnjo.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gt2uceepgaj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gt2hleibozp.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2wvxaftto.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gt2vxmnggxk.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gt2gavupasz.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gt2apjybdoi.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gt2vvklkoyo.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gt2ibvblyok.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gt2acfvsngf.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2sbkumcao.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gt2oueggmmq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gt2vdkmrouy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csieyijp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfhwnyec.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gt2qdydjuor.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gt2guyydrdf.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gt2vmsdevtn.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gt2ogxlksvm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gt2ddtatlfu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tdulntps.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbhnvdnj.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2xihebuzn.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gt2slwcdwwx.html

int|string $id
来源：http://dali.yuxming.cn/Article/details/gt2inyrodhp.html

[U48] PHP：纯枚举
来源：http://dali.snrcjt.cn/Article/details/gt2mdbnypwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gt2xeuyrnym.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgyglqps.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gt2euluoebf.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwwdsoow.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gt2wmzgdpjd.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukxoctvd.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgbzvbgq.html

[U52] PHP：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hwtikhid.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gt2japkcnnf.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gt2hrazpido.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2gukhcylj.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gt2rgggjiwa.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gt2adxfqbqs.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzhsezbc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gt2wohqbgpd.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gt2lclwginy.html

f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2pecufqzk.html

[U57] PHP：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2pjzntagj.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gt2bgeqmvzl.html

[U58] PHP：数组三件套
来源：http://dali.jiagoushi.top/Article/details/gt2uhavcfbh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gt2lkpqijzb.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocbuczms.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2oetgetrf.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gt2vacmejbs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vztbhlrx.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gt2sdcdivbp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2wpowlnxn.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2euvyhual.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gt2enmsykjc.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gt2znqqjojd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cashguo.top/Article/details/gt2huruzzyg.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gt2gynreguh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gt2jqycsxhh.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gt2sjapdtfe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2rvimnltd.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gt2lphcwruw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvwtiieq.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2hlrnwhkp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gt2bxnvbrlx.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2qzznsfnf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gt2lejhlzdc.html


<!-- 参考信息 -->