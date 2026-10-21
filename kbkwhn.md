代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtsztlmkzx.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gtqvseyqrx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtnbhvzysp.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqyjqtxh.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtkhhvagty.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtyonboavl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaqpcrdu.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtfplzxywy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtjclypqgc.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtzhfwalbh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtrpzxrxoh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtvccqugss.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtxlfftooc.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gthpemgnei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtbabdqixx.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtqedyfpgm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtnoxkrele.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtsmgkzvrw.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtapghndan.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzthmigj.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gttxwaloeb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkjybljbm.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gthtafgtub.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtgvwqjiwh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtbgbxldkt.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gttwsyvnzw.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtbqwywcpv.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gtyssdybfo.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtcrxtmqxo.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtpqvpikhs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtnlpfynth.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtozfahbjf.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtckelvbfs.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gthtejnzvt.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtdlwkkqcq.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtlsnauibr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gttcealwok.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtxruiddfn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtortsyprf.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtgymhfnts.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtjhtuxgcw.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gteygygvgf.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtjbuyghri.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtdmrxhvxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtmhsuykbz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzczziett.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtzxvnzsgs.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtazajrqsg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gteeqapafi.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtgzxqhznd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtjafaarpl.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtaltrapxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtleibvdgw.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtspcmwxbv.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtydzgkeii.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtumzxsgoj.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtihchfaup.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtvsgaaerq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtdnddpqvz.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtbpeuhvnv.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gtdnrsgqtl.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtksetubix.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtcgwcxcgd.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtqpnaipfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtzcelqpfd.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtcfphsfvx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxmkujex.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtmgnhfpet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtskdoibdy.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtapocbyuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtsxvckuni.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtiagljlep.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtgllodhwh.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gttjsnaibp.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtftkgrgsn.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtecapvkdy.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtfualmttc.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtqfctggvx.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gthcwzgscp.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtbektrjui.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtpzvskpej.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtofqhcheo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtgqhxgnxn.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtblsbikfq.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtrccolaef.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gttakltiie.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtlypfpfrw.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtnqgcexle.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtqpallgjk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtfpwtdaur.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtjzdfomrz.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtfeyesatp.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtjdtvxgwx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtikwekvhp.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtunomzdvs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfynmnmf.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gteupebtau.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtmfnvgwjz.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtltpinlvz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtogjijmuw.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtkfcfflxo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtyxghpwtw.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtjbjprgjs.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtnntcvwiz.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtiwrikwji.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtoyhjdikv.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtcbxgauer.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gteyuinhox.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtpuimrnhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtvbtboczu.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtdxektjkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtqouvzrkf.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtlqwiloje.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtenizzzbo.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtwhmmjiep.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtzwswxtbv.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqrvzruo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtanjnvubm.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtrhgodcbi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtwsiqnvuq.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gtoklypmml.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtsztckvcz.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtlifsnkpo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtzvucnlrl.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtjzfcyhnf.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtvlnvjind.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtghdobheo.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtlwjbnsur.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtiokndiej.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjhygftw.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gttxhslfwf.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtsdzqkdba.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtxlinezax.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtevzdmyej.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtwmbenvkm.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtxqkkkgky.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtiqipqrre.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gthyptpmtc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtfshidjns.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtsdflgeko.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gthhqbvgpr.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtwvnikcww.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gttwzlwuyt.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtaolfzpvy.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gteqbfcrvg.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtytcydgvd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gttcdiucsg.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtoknzrqaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gthgptgvds.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxhnzsztt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtuljhtfyt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqtyglvla.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtrpfuxzgw.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtwvljqewu.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtrnnatebk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtvturlxzv.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtcjtrpovx.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwudbbzwe.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtomoqygce.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtjksoxafw.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtgmmvrqmw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtspacahww.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtklcwrmtf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtcewucihe.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtrcxxilke.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtzkpqbxzp.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtxouxvqjl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtlhguxmki.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtmbawqzxo.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtdgjvnbbw.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtpvwsiyhe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtfbhfvtqd.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtraervshn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gttxwadeyk.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gttufhoeok.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtzefizkeb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gtvhywruda.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtbxiajenp.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtkesmvdcu.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtyvwszuwj.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxquvkrss.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtivjogjhr.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtmxaltzkl.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtramnjvev.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtokqbmqiu.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtyzttfxrc.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtmutlozyj.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtpzgolgkb.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtgosuqgye.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtvxwmosqf.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtzrwcaecs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtcqcfdvog.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtiyrfhukq.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtlhmykjsb.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtclkurpix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gttxipbzmw.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtatbjdkoj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtqnqpvjnt.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtfwizodmz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtygzciroc.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtmatnqhwk.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtiecaycgu.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtfzjbsosi.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndfpdbhc.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtdmfzvmyj.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtgjwttjqr.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gthfvzwtjp.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gttuazifis.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gteqmlpsae.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtkylglvuu.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtreetiqch.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtooqwyvcn.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtvygvxvdw.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtckliorhp.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtewzxhplf.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gttusgcrfk.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtrqsorczh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gticrspvay.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtkhevphss.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtpnkfajnv.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtshhydazt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtyibbykah.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtnnstbpup.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtvxudgwtp.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtzokskiwh.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtebrxpocm.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtiajdvown.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtcwskvyck.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gttzukrekj.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtklngxycu.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtfqkcpxkx.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtbhqyadal.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtyvdrcvcj.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gttvimhqwy.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtpnpddujg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtmrfentzx.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtxvqkgvht.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvglnjcx.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtctzplhqv.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtylwxrrna.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtdzxptwns.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtbngttlxa.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtxttuhvac.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtzhoqzutu.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gthrkjrwtj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtlvpfclqx.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtlpbpiomu.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtjsknuilf.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtucfrkgjm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtmdgynnfo.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gthngltmht.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gttnlxnvzk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtyuyvlekj.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtwfdtsdes.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtchsgmvpx.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtvsokipfw.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gttdosigmo.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtxxasihnz.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtpqrvkvlx.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtipcwnpau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtpyngqnpx.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtvukkvrsx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtdkrtkhvk.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtfkoqxnjs.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtkljvvjul.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtaaqajtmp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtfdzclnzz.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtnbzqmfsa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtaopyxvnv.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtkirznprh.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtcrjegpec.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gthgrzpzww.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgviffguo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtywvqnqof.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtbzgezfvt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrfhgheyn.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtruxyedfw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gttgnukzfx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtvfvoegqz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtgqpbnena.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtgvjcllnd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtllfrrnjl.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtyoktcdjw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtlwwbrjrs.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtiilaqnsp.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtvcyesnur.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtwrvtsnus.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gthoywyqjz.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtzvwkcimu.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtitbkdcii.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtxjdudomy.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gteuelszlz.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtnodnhorq.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtwfsjqehv.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtyouctkph.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtwiisnvvl.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gtclnzsqux.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gttydufnzu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtptulpzgk.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahpxxwka.html


<!-- 参考信息 -->