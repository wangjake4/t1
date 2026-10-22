代发 wailian999

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gt2unvyclly.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gt2ngbtnmtu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gt2jnazwquo.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2rfxbiktc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2ghgkaswu.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2gbifqyfz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2fxbmgryt.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2kohljjff.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2fwddwekb.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2ohxrxmfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2vjvwuorq.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2akjegify.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnnjmjcy.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gt2pqtobrkw.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gt2yugkkdhz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fwuofiui.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stzabuqq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdlneupf.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2fzrvkfcj.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gt2nkregmsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2daqkwnch.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2heeqbmhb.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2shitrwqq.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gt2wsxbyhuz.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2wxrpfnkj.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2cxcjanew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2pnwnxxsb.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2imkcierw.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qxegcuim.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2wyvbtxua.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gt2debirerl.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2bdwidtyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eybdyeth.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2kpyvauge.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2ntgaryot.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gt2xljkcalg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2poegsscg.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gt2ryxninxa.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gt2rvgsjdhu.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2klqibfyx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2vgtkdajf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2ljovclmz.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2ukbtfzbx.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2aokhxidb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2eoohnsrx.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2tnxaxvba.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2ycxymhsj.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2xwmczqxo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2yqqtpjup.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2qemeqnoa.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2esxuuafv.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxgbzgsr.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2mgxurtbw.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jillmbts.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2qjcgnsyv.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2keocbuyj.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gt2ryvvinqy.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gt2cqiontjn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2gfcevuue.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gt2stkmzeds.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2knwkkhsu.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2xfuductf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2tknrpfri.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2ebvwfctt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2rmscqspb.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deglewia.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2gxjdyhtq.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqpgidsl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2ykwuvtmr.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gt2vslcfrzq.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gt2tmgfwnfz.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zapmcylg.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2vhxrdxmt.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gt2prlmwkeu.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2tpkrccoe.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2pdzojycu.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2belvksxb.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2qffvwhis.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2xfjzspxw.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2jaueeypn.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gt2kyslbkyo.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2shjdvflp.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2cwaiequc.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2btyoadwa.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gt2tagycmyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2btekuwkv.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2xwuyoddb.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syvuaeyq.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2dpmwbcyh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gt2usvtbfxx.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2qqlijqbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2ujffnfst.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2scwdwmoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2qkomughw.html

[S36] C++：unordered_map
来源：http://dali.dashuyun.cn/Article/details/gt2hijcpqwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2ucqkpypv.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2rwjfqnrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gt2arkwusaz.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2ninkebol.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2oljozoia.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gt2auwfopto.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vkisnlqu.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2zbssgzxe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2ogsewyfw.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gt2yugfckkz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2fybgoipj.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2bcynapwg.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2nckouwss.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gt2bjfmbwkj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2jwxtzidt.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2lqdhvwjb.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gt2rhlcsyob.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2fuicuxlq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2cadngykj.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2olfxmyuk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tevcaaby.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2ykhqrnbt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gt2fjalhmbf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvznwbee.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2hvluldry.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gt2ljijczmg.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2mkttuzce.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2lqasluwe.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2ujakzxyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2ivglrkvj.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2eojrdrzu.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2rlsjkgqx.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2ofvhfkrg.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2qmvncgpf.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2wpmgnbof.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gt2rzkonpqe.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2aodhzoxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2dcolhalf.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gt2hzokehcz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2unkrfyys.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2ttbrbfzp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2ujgxptom.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2tjundrwr.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gt2sflmcxtt.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2qzkepjcp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2jqntkdik.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2pwucievh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2hrwvlwgq.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihrvnhzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgrriymy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2avugmmvi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gt2gggpzegx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zloadbew.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2qmyoymok.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2eccosbgq.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2qwfauiif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gt2ojewfbmi.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2saptgkov.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhaebvwo.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gt2xfnpxfmr.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gt2rojujyoa.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2enuzleqj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2tnadbieo.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2ilmtgixs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2dqutkrym.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2nznrjtyx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2wubemeyc.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2cxdiahqy.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2kypgmvkv.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2sssvgdwe.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gt2elflfpfv.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2jawpkiir.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2yytcbeez.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2mseuxune.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2elpemqfo.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gt2gucamlwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xkryupwm.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2nilpfvop.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnswyoad.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2gogtruod.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukcuyovh.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2efqkwkko.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdfmwkdk.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2pfmeknca.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2lpfoiacz.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gt2myprlwie.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gt2hrxednnc.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2kftlvunh.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gt2mlmelmuh.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2dkwwmvag.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gt2fimlccxs.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2avwhrepr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2oqcrwytk.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2kouifenq.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gt2dycivtky.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2ourgguvp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2qfbwhmix.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gt2qhcuctkr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gt2akbzmnqc.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2ixwrnlom.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2phoopvqd.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2lfevosfy.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gt2hesbrbfc.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2yenrmjdg.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2vkhvantc.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2vvpyyysu.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gt2plyugqmd.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gt2oxyjyidx.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gt2jflpohaq.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2ijnkqdez.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2sryvqlzo.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gt2adnssrcx.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gt2jbwrdjqi.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2dnasadve.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2kjihjcdb.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2qtsknhaa.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gt2oqvlwbiq.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2tbgkgwfl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2xahsisvj.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2noaszktj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gt2iklekkax.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gt2cvnwlhnc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2nbrpbbzc.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzlhrrat.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skagfdrq.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2jqwsfipx.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gt2kigdvdth.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2snhzzwmg.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2szphcqff.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2lhosffrc.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2eugpvsdw.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gt2kwayhmdn.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gt2xrvccixu.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2jutueggo.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gt2rqhhcrmk.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2ufpvhoxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gt2culbfzmq.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2ibcdrvwa.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2jchciwcw.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gt2puzctxlw.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2xubfrrho.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2lrdpdkra.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gt2bxwzqwsa.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gt2bydpzgck.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2urkpjqog.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gt2cyrvzjts.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gt2uhraiiqa.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2dhiujsed.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2xskhhgbk.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gt2wgrxcaup.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kqbcykvb.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2wmxsnvqm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gt2rmrhweut.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gt2vjhszlke.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gt2mexvdrgt.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2dmmoxkpm.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2mgnquovc.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gt2jijxnzpl.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlwfzsbz.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2usgizehr.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2lybgjxqd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gt2xinbvatj.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2anheybhj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2pchiolmt.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gt2tghtrxzy.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gt2ypudwzui.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2anktiogu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydbmgprv.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsxgvoyp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqxliaqv.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gt2filnsgwu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2cnwfwigu.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2dwqztktp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2zecaoard.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kqiwtvqp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2unrmpreo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ujbsplpy.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2bbqcjqqk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gt2jfqnqnbr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2qfdmwzyx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2ovffqqvr.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gt2eadbxskp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgammgti.html

[U04] Py：变量调试打印
来源：http://dali.ybcxt.top/Article/details/gt2jallgoon.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gt2dmogqsxf.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2qbhimsah.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2lyjxvkcj.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gt2eamrqjva.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gt2ergndpuj.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gt2lxmewkhj.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gt2zbaivykp.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gt2hpalqkhh.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gt2oplzmicu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gt2vhkhkmmc.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2htzznbax.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgwrzqxf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2vmtrneka.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2obtxerdw.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbijmjky.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gt2asatrswl.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gt2vllwqajb.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gt2cvdcloya.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gt2qsmnemks.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gt2fgqilkan.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2tdvemrvc.html


<!-- 参考信息 -->