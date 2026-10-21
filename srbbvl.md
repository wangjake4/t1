代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtcqnzvoxt.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtbydmiuyp.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtvuxvqtnk.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtrpwtqzki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtngmjnjst.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtvnqvmsgu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtbtvomefl.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtqufyreqd.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtwuwbxpvy.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtqefpilqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtxmkxqwya.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtfstlaiwp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtiuzbfiws.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtgitsnrzg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtdaosnzpz.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtbknafapc.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtkymsnbvm.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtustwiwor.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtolshvanr.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtwhcqquge.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gthuljmrqd.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtdxenikwx.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtojpaltji.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsfwbottw.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtdcvvzvoi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtaajehvgk.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtzstuphat.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtgkvhwref.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gtkzhpoesp.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtcvilspjv.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtobhznmkd.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtaewqddiy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtolknddsi.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtbrroyifk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtwubcjysp.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtknkhmocr.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtqpwzyxjd.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtllmcrcoo.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtobzgbsfx.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtcuaisxog.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtzmvlutgn.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdvsnhxw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtkcvehutq.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtjokjyuio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtwyhajcnh.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtpafkoeiy.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjehdnoja.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gthmlpdkrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtorbdugwt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtfiawjdxc.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtkrrfkqdx.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtehpmahpa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtohdzcovp.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtrhhqlppb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtdqronakg.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtaolmaqqz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtuwwkudhw.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtfkffbocr.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtxfwotnpo.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtrkhjbvir.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtiiexymug.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcejjtrkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtzyymcluc.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtzadgjjry.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtjwaatnrt.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtrjqizfcj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtpcviaamx.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtyrfdnpmo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtwwfziddn.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtvktqphyq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtnhvwimfh.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtffbuppyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtkqfibimy.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtcvsvfhjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtllilsvzf.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtrjvyjkfh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gthetebczw.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtsrpwjugq.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtnftjlxys.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbxnwsqt.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtixxvogmn.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtjjwkefsf.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtksmptwlo.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtvossqkci.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gthxixgtox.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtvrgzcwwn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtigroxgwj.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtbzibebuo.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtkmkbozza.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtaowrvwut.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtzbuvuezk.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtzheertmh.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtcjobmwtu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtoovmslqj.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtcborccil.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtqfgnjziu.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtknhkgjjw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtqzfrzcuw.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtowxbpzxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtjxehoiqq.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtwgmnvfyc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtgqknuklt.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gttbmevydw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gttdfczvfd.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtdxxvftjg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gthnujchxl.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gtazmjnbil.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtnfcdkuqs.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtkrpwodsn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvcsyihm.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtogykwdgx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtchotuoha.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtxtxzbfds.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtzxuppyni.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtyhcopqgo.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtmjwtixkq.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtzjgrfios.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtkolqrtnu.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtaygstekp.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtxdrtuika.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtpizokzgf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtnazzfcls.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gthtgajlvi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtcsnoatjl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrneqsovn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtbokkryuv.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtwalyggbj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtepzibyzb.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtqvhtsezh.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjmcadtkp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtrzndhbuw.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtxqkszwqk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtrpamhwrx.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtjfmeapbj.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtpatqqpse.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtssdaxrur.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtybdxrjfq.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtdeuztwyz.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gthntlkybg.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtjawirsys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtifbxfkju.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtnzvmhypj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtgyoopmsv.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtggefqezb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyologdeh.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtznaejjey.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gtaopmmsvd.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gteyangjls.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gttveirxcn.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtgpgptbym.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtbgrzwfqq.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtddrfvrcy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtughkonjz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpwgewhdc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtiuvgfjll.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvolaxxai.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gthwsttxhj.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gttxmnztxw.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtqemqftxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gttsmplnko.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtnegvyzbq.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gttbkkqcjn.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtgngewtgs.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtffrsvvmk.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtwtlxrwli.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhwfubxt.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtdpyiudbe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtqgpbdcka.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtctokanbk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtpcphrsme.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtlvqybwat.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtsuxvzglr.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gthkzbfpod.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtrzwjhcnr.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtgzokgrns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtvilbuvnh.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtejcjhags.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnqzz.top/Article/details/gtxlqyuozf.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtfjtyyvfa.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtgvvrifwe.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtpdexcvel.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gttxqqtnuk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtbcmvwvyw.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtsmwcymaw.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtpcqsyvmn.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtuvpetqow.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmxzbobc.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpbnhvud.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtreatuhja.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtvldxwwai.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtnvcxwxjd.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtggufcwim.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gttyvwnkvh.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtvcrwxnmd.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gthagwxqpp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtjmqwwlba.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtriwlxqgw.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehkjuzyf.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtuxtfovrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtnktyyalv.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtavuasxin.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxdrkqsz.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtbxuaxmtd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtvvqbiaqt.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtschuwwbd.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtvbvxojye.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtlzxtgryq.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gticaztetz.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtrnkgeqzk.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtgqvibvly.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtjfrinqkc.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtsyeihxbg.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtimtavpah.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtjpvgbgyo.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtohwfrvjw.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtkqjcnkdj.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gttlsfdbxb.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtaldwftuk.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtinkmzuff.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtdmxfgyxf.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtlqchmclo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gtqsolwxri.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtztzeycmq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtdfqbhfcv.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtkgnscdta.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtopgnofrf.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtwistoyxn.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtlnnqvvsb.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtaaxxvpph.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtrwnsakgt.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtquysxbad.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtnszefexw.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtcijspsot.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtffyuwbce.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtfirgsetu.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gtyybniujc.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtljrvwokn.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtzzdyavhv.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtvbnzkncp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtyqflpmip.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtztrsidie.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtqlqazadh.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtelhvbznp.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtmibaswzm.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtfboqybek.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtadrvwhvk.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtfzvoikzz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtqxexcmic.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtjetzyvjn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtggkydznp.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtqdnnsqbc.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsyvezyg.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtdjllvwdh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gthkkiicox.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtpdtrnscm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtelgpdway.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtbuiospzp.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gthamsgjob.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtkldbyjpa.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtxvnnjeit.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtozgquwyh.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtdrxqlfub.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gthkvylqbc.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtnpzsgiqq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtplirqqqk.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtkisqpqiq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtwmeldumw.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtzvzzrkdk.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtximqzxlm.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpktjzzjn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtptbztskq.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtilsqjjxb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjwvyove.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gttruwnvvr.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwvczaic.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtxsfnmrqw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtehbwqxmp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtupqirrfl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtrdvxkrgd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtesrhcsbl.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtcsvcgmad.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtluxyghbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtzrzhwmwt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtlsiyqzpq.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gtzblzyzyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gtngtjegyt.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtucjzfhge.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtklqkgplv.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gtutsklsqw.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpqjqoit.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtzrsrbela.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtynjsoppt.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gtukpxvvqk.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtnjwmsazq.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gtkapjyixi.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtmzuyrkrc.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtioiiecev.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gtuszjusrm.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gtanckpjkf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeyehqiu.html


<!-- 参考信息 -->