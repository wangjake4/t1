代发 wailian999

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2pazrxsxr.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gt2jrvyfedu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gt2iwhrcdrp.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2uiahhkiu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gt2tlxkrxvh.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gt2dfjksarl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2fsrfmlbi.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gt2rauwtkmp.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2geozabdh.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2aopfojeo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gt2ucbgukyk.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2urnslean.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2rhhubeas.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2rjssmpfj.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gt2hgggdila.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dtvbxwlx.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2qzxnbetf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xcxaasmt.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2zyjulwcs.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2tszdnbbg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2ehhzwigq.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2xkrpunwl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gt2tmtsnuqc.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkcwnewg.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gt2noczgeeb.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2skuvpypq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gt2kynvjkaw.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2ewyqpmbf.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxolxzad.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpxgjdyr.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2hmmttlqo.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gt2vguuomvm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2ticvljqj.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2crxxdamk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2fgiwwaqg.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2qabroaqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2tchmkirz.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gt2jdbxyvqu.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuhglevz.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2tlmlqnvz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gt2azmdkdiz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvmwgwlb.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2lnpyzsxz.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2maxjcfzd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2gpavczec.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2codjksxn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2sbcjzloi.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2rqevhgnu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjsdobnz.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gt2ezpxiqbm.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqcotsmc.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2ntilrapl.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gt2qqlbqykq.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2xoqphqvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gt2nhonuxct.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2zahuhebp.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2kopfcnet.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2daqvwwxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2wgqfzemt.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2qiacmtok.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aiaueqzu.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gt2qdzujhyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2kghvqvhl.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2mcwcwkvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gt2bkkbbrvr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnljpgdt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gt2mqjfoplo.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2qpwavhku.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jphjxenm.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2lkmamyui.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2wxhrfakn.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gt2rkoaeyne.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2uqcgbpag.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2qyckhxax.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2avhfcllj.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gt2bzhlvofj.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcdvowjp.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2duiilasb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsfsedur.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2ahmgnhwc.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2nduogxbc.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2khpbnzus.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2cduamhvo.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gt2tzkqlvjc.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2tqbfcnow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpigqkfu.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxaazhct.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2ivhruqwg.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gt2lqsetrfg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gt2otagkdbx.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2ecjgnchm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gt2spvrhxbe.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gt2nvbetygt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2vzqnsehw.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2gvfoeyci.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2ksfzgubs.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2yobbegte.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gt2apkfqikt.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ofdhcksv.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2htjoohee.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2iqorwfrs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gt2dxjgfudm.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gt2xolqvgos.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2xsscjokz.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gt2cgaetcid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2uzfihbkb.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gt2wywjlwca.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gt2yejajxjg.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2hxsnhdzr.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2pmvrerxe.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2ptyfedfk.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2xaoozmrh.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emgitxhn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2oezdaaef.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2pusrcwat.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gt2cgjoarnb.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2drppqvjp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gt2iggtoqnb.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2poddrzch.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2gzsiywyo.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gt2hkpdqdav.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2ugqpfoaw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gt2ftttyyfs.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kepufvkf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2ymeiybpz.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2xyuwexce.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2uukcouqn.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2qqedevaf.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2nlqsessf.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gt2wnniuiqs.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhzrayqh.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2guobrpqf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gt2mpgusctb.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2kcntymkz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2zdufhvxl.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2kskhvucb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gt2jvmnbeng.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2yiuhkqkf.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2uelrmkbr.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2ovmypvdo.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gt2pkgefdom.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gt2xfpbpiqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gt2bawjuteo.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2abnauxts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2tvamdsel.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ihcumpsf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2jhgtrrpc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2lljxvzvq.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2mkkdmgwh.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2mntomvwb.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2gowgylbn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2cirplzkz.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2jpgolssp.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2lgwnbtdl.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gt2bkkwbozk.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2grxqdpmj.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2vfjjrriy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gt2knsshhyj.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2fwffjrkh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2wlmoqcom.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2qbnkkiqi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcgsnvus.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2otkvyjdc.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2ejgrpphi.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gt2famacaid.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2clepavki.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2wtytdfur.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gt2qlzaavfg.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2rwdonhvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2agswshwp.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gt2lwbphxar.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2tlsffcdz.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2yjaoavig.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ppwpipie.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2rbdajthf.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2dnmsjulu.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbkuawsu.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2nfamazex.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2rarvajqd.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2fpfkbuia.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2pnttcodx.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2xicrzpgk.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2yhuwnhnv.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2mnbdqgty.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gt2uhgntwbv.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gt2axvsfays.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2zubfzgqd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gt2qjphjzdt.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2zadgpjcn.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gt2kdwatozi.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gt2wapaojug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2dewrfdro.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gt2ecsohdlx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2fqhefibc.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gt2lrasaxwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vikayeib.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gt2wknaiwgl.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gt2axmcwvun.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2jbqnelbe.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gt2rwqraumo.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onglirov.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gt2oivqtpqp.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2astzzgjh.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jisxajhv.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2zszpaepi.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2dosljpih.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gt2ujjpfcyd.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gt2eclhbzeg.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzlcxkyl.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kncpdimn.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2adwxlrgu.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2alipluos.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gt2tofhhbwr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gt2nvsutpma.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gt2hirkodfq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2zjersvyw.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gt2flobiwkn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2dnciqhel.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gt2wfmwjbsa.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcshgaws.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2ivwwipiy.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gt2znpihwpl.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2kkqecywz.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2fayopoii.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2huyotmpz.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gt2jfeskpnr.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2shkgympi.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2mvkprxaa.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gt2efpztbew.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gt2eqmawsew.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcvzaujk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2cygpvdeu.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2onfiodnb.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2wmwrsbwx.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2tmisstzd.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2rcgoeyyq.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gt2mmxyakne.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gt2yozvkwls.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gt2ycqpqrsi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2omtrzmms.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwnfzcis.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rofumkps.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gt2ymjwmzzv.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2icjfroxx.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gt2ogkmsbwi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2lxrahjii.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2uhuebmeu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kygpkqvz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2zuskuqbz.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehyadyhc.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2rqlzgdfp.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gt2ayppxknr.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gt2dfibjbxw.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2asuhodmf.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2jlkbpqac.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2hrizdsnj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2tygqhhvh.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2bamdrwpv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gt2cgbwqxhb.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2vfztxrhb.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uovygwog.html

[T57] Scala：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2mozoqrdf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2gxwcdpyo.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gt2lxcddjch.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2mfdkonsp.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivvwjssf.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2xjwbqpwj.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gt2udftvpdh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2paispxmm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2egwftism.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gt2wnpmurrs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mkwvzbcd.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2irthznct.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gt2chgodfbx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2fxquarzf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2xxchihdz.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gt2kzjfoucy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgtiieiv.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkzzhhlc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gt2tlvfawfd.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2adddjhun.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2zwhvwmbh.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gt2odxjypku.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gt2badkqfjv.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2hctnovru.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gt2finbcfwg.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gt2ksyrkoyy.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gt2ezzevylj.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2tugnhkzo.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gt2mkpkdmvw.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gt2jncmdbxl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2hufnqnqd.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gt2hjfagqgk.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2ohfmxzar.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.haohaochexian.top/Article/details/gt2twxzaqbp.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2ehrlignc.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2lvhuxvsm.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gt2teenxbxb.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2ofudwctl.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2bqtjjoml.html


<!-- 参考信息 -->