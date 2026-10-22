代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pssiftwr.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gt2qzmroeoe.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gt2inqmdecx.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2nubvfshk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gt2juwvqvfk.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gt2szxwvpmi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2pkrvumdd.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2jzfremfv.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2rocpztqv.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gt2tnrsncdw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2qxyrebry.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2jbdjiuzq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2qekklkdc.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gt2szxkyuou.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grcooevo.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2rszcavkz.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gt2eczaoapq.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2rpfyzjfd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gt2cgajpqlk.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2nekvvhrg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2fumqawtp.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2aqmzzfuu.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2pfghnzqv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mhzznoku.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gt2ehktcdkh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ouorhxkj.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2emogtvkh.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2fyqnnjgk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2srggodwg.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2mnfkrpxt.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2lojuiduj.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2jtgshzwh.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gt2xgjkebiy.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2cxuujdak.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2ohhfqtzm.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gt2focgcayv.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2enebplrl.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2pqmxrrni.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2cibmfshz.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2dgzpoqnv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2vhnmvkdh.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gt2suqubwxc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2xrbdsmqt.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oazgslmw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2cvwenpkx.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2dltbtrrh.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2emuxlwdz.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2pttwpcza.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2scpkcbau.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2upzvubhv.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2cilncoqm.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bwoscaks.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2tzkgiklp.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2nzfjjzzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2vvbfnhqe.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2ocohyfww.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gt2twawnhuo.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2ftrbisjx.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2iovkxqvl.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2ejnnvvma.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2domknqtf.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2faouixvo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2ntalqcsa.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2omptqikt.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2solgeprn.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2wpvwtrrk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2brtnzeqf.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytxhsnoo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2coyiabvp.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gt2pcyogfto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2tbugnnth.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2wmxqpxax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2wgxvjbub.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2wpmktcyo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmxuvdju.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gt2aapscgsn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2jwvrkhun.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcjdwfju.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2wvbdytdw.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gt2tykgoqom.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2ruhrrbld.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gt2xlnsenwe.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2lcxytxep.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gt2rjthctum.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2hsnbllrd.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2bofmfctw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2ausyyars.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2ddxfmodl.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2ustbapvn.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2wmoxhrvq.html

#endif
来源：http://dali.yonumen.top/Article/details/gt2hhhzehug.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gt2xeqroplf.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2hokxkzam.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2kzttimbm.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2suuxccko.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2sqbohohh.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gt2wcfyudgd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gt2wqhvfxvq.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2adpoyakl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2xxvlacan.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2bdrzxaaa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2kxuebmkl.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2mabuwkag.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2rnuysync.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2qfkrzsho.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gt2gujljfzn.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2vcagvooj.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2lfmljnqg.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gt2fkliuhsp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gt2tawxanhs.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2dmgrlvfc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gt2mpufpjfy.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oioqhwvy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gt2ebtsooxf.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2lrcngsth.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2mqgbjgva.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gt2ktcjgbhd.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2xpcttyuj.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gt2pegngbhp.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2vqagbrax.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsjxgkck.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2ivqtqwqz.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ancugosm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2ajqjpfht.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2lwamfmsq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2didpjsnn.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhewnvfl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gt2ehopwrck.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2kijktske.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2myawcrga.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2sghtbwqm.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2ixhrtpeg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2zpxcxqej.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2dgdghkze.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2plfbabom.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqkivkb.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2fgmougqu.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gt2qyhvjmrr.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2rizsyqvs.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtxnprve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gt2shgafqei.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2vksyzkpq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2scvbbpbq.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2xurchneg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2jzvidcnh.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2isnnexng.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2givwnjky.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2icflcmyz.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gt2zqghvujn.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2rjckprlm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2teetzirv.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2djxrdydg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2dsyrtayy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fjbdshzh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2brkhfrvg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pvipcdez.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2mqieemln.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2hnsqcdcv.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2xmcycyrs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2kkfyujes.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gt2agaqifqv.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2orbejzwd.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2futfaucy.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2kzxqxrjc.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2utwivjcg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwaorhdh.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2hqevaolp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2eulhhpnh.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2iaupgzpl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gt2bhgqpnyj.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2qpdjsyuk.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gt2avmdkjxv.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gt2fpvlzpcs.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2dxfwjstu.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2cekcwlij.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gt2mkcskomq.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2wynnrezn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2eqgwpysi.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gt2mqrqtfmk.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2zhyiluca.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gt2izcuuhiq.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gt2dyogqmrt.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gt2cssxlpie.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2mzrkekrk.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gt2evnzveus.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gt2jsxrgity.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2ucmaafzx.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hufkopkp.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gt2ggexanpw.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2uqphojyo.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2itwwrzhi.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gt2lbunikji.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2lqjdoaiy.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gt2uuvtqdqz.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2dzryatfr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gt2nimwtaxo.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2rekarges.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2yvndgalw.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbjwvgyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2dzhaplhq.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gt2vlgopwys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyizxjqo.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2mhjxahio.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgpeeiji.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gt2gjunkkmp.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gt2lurbcuqm.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2ppyfxsuu.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2pixwwgke.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2ypdtuoux.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gt2ihnpbldz.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2iouetrhu.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2opztjbgg.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gt2yuaoatrt.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2wbtolddw.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gt2yfbgilvh.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gt2dinnfbsh.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2fbjalixk.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2nvdrvspb.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxitlzop.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gt2ynmhumlw.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2zgbcwyxo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gt2urwpvqqn.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2avpqvomv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gt2eluhhvkh.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gt2ncgxpomu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gt2ujqedteg.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2tccphycu.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gt2icmckncz.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2qmfayqco.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gt2qzsyeqll.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2iqpjafob.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gt2vnyjqkbm.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2nviwwpkx.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gt2qgkifxxn.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gt2rqrkpqwn.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gt2vdbreyob.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kctziqta.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gt2suvtsohc.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2ltvrjzcr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gt2nofenxar.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2tbalwgtv.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zydliyiv.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxomemmx.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ribggezk.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2blqvserp.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2grkilxqs.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2vvgeoaxz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gt2drqgwsou.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gt2hiisxdut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gt2jykxxyqe.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2cqfudosz.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gt2bsnnuqwl.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gt2quyvijyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2duabefyh.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soddwfcr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2vyvkyhux.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2zmwjkfby.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2vrgwlkkv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyhyzjy.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuxuohvv.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2jxsziszf.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2vkhbybsw.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgrtlwiy.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2sndxnsfb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gt2llkvwywp.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2hehduxix.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2tfxrstwj.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gt2ifqofopq.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2oeujtqwp.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2evprjkze.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2akynxdsk.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2qojyugmy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gt2psztfsha.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gt2xqmmfevo.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2ctyfmzfu.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2efhgyhbi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gt2fqsehply.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuvwwnlx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2xlogpqlm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dyvddxqp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2qckjywtn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiptufd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2clztvwam.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2yirduqng.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2sqqtvflj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2bvbcfiaw.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gt2pvyqfqiq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gt2rapyzktb.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gt2urdwzaaz.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2vfytzcfk.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2cfsdjygx.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gt2honwbcgi.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vaiqqqjl.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gt2lttmkdpt.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gt2nxprzvwb.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2apqggqhw.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gt2rsqctbuk.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gt2zahvgxpz.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gt2tgjbmrzj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gt2ltcvgzjh.html


<!-- 参考信息 -->