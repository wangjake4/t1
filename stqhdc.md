代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtmsajpwvu.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvkwtebn.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtkqguozzo.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtnlcyltvx.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtgwcoslqu.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtahnllcdd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtttkgzjmf.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtyqguxkhw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwcfglij.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtdfwycjbc.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtxkeurygj.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgddbfqs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtaggagzbm.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtmgcjgjhm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gttrairzzp.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtddbgkxyh.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gturcqwpsh.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtyfgpdmtq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmhhcmtoa.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtuslhevam.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtlpztlfou.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gthhvqspvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtnqgaymkk.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtvmrutkvo.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtzgtudaof.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtnnsehssv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtuytpqkvz.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtlraktvjh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgesetxt.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtvmovcmtk.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtfhyyqehg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvvkdtdjf.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtfrezdjns.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpjdthpft.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtcyiokiou.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtzfvhysdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gttuupsgvg.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtgczbyxex.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsxasrfi.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtxqepeytj.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtkxqryirb.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtsbnqoslz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtlolojpig.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtnwkhsblr.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtgndnbfnu.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtuucogbbo.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtzkczmlhr.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtebsxobby.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gthjckdlph.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gthaotfect.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtwchtovcs.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtixyquwcr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxyimrue.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gttccofwfm.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtdlpyzovw.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtcskgxyyr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtxbekyotq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gtmfshpgat.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtnzumhyyd.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtdeidxwmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gttauitwgc.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtxdzvnwbd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtnkfqwdod.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtehepywjk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtsvigxaci.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtqwspajky.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gthhpaedhd.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gttfjbqhdp.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtkcpmzzuz.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtuexbdvxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtghoprvdk.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtndugfcij.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtogbckxwe.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtfdemrcvj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtuanpdbwj.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtzxnfuqrm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoawotcm.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtafbslrso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtdlsnaels.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtnusova.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtoiexayyn.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtdeaufqlo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtkfbhridt.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtlfufvnpa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtwxeioxfn.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtxqhdkrfx.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtvywdinfu.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtahoorztz.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtuujzaumb.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfaokqqf.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtkppydplm.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtvnnaosdv.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtjhxecyji.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtgtkhooio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtudjrkjdz.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtypqnrzjp.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtawnxvcnm.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtiqbhksbo.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxrmlowo.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtogjpjgkz.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtnrknoaua.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtomdstwss.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtxgimsncx.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtorhhkzbp.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwawkpgn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtddyvbpbj.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtrikcqsqn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtcerglycg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtdxvfmxjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtazkjsfsw.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtkjenpkoi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgjcoxvo.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtpujhfczm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnntvkir.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtsgsxsffy.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtyriqgtme.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtfxaqqgfn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtribwopwd.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtxdzuijkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtdclkqsoy.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtawqndfwu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtlmnzmfmq.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrbgfnzag.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gtkhlopbkz.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtfhembpus.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtauodwudv.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtyewnvwhu.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtltnzopvz.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtvxxfuljq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtclukiitq.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gtdroxasde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtqdhwqcak.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gttrhuxmxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtsllphdey.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtetqpuecr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtvxjkwhbu.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gttnqluyzx.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtpqmcrtwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtqbrvzgxv.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtutggyrnw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtjtxpxamm.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtohtgbqhx.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtipcyskuy.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtvnyllbqq.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtywrtgisa.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtsgqmvvfp.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtgufuarcs.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtqpgmfbow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkctrzlek.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtzndtnpaf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtjuihguno.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gthrnsagzq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtxryeuyaf.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtvjzkhkiw.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtpnevkbwl.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtizpigfmg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtnovyjcwf.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtpjbwutnc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtcnvbbrks.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtwarrjaku.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtzwxkgstn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgtrbcfeq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtrxgwjakj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqsrtesti.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtkfpkoscq.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtjqdktyzy.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkbiaydb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtlhqidvpl.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtcyyptczs.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtssrnaztw.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtnafddkcx.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gttsliiccy.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtvmwuccmm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gteyzoikvd.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrpughlc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtqxtcytkc.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtddfetmby.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtrfwqlolv.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtgiskpuyp.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gthagdpthi.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtergkdkce.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtpnlnatsu.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtsfnpwisy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtgxsvyvpy.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtmlgxwrii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtiraslkgg.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtnoyeawwo.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtxzufpynk.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtbxnfjoml.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtalvbjxkz.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtdfrvreui.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvpjpkzc.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtjgvwjgxv.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtqhensmwu.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtetxyisjj.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtahmsehqd.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtmvkcxvsn.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtfxenyshg.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtirjjmfbc.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gtluwetqpf.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtmvgxnjua.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtejkcnzzi.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gtvicdpenk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtaqcizwqc.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gthyrcgaoz.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtdiafwkmq.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtzlghncgq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtypexdgdt.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtxrwdcjer.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtywwzbbgg.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkssxnaq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtiejziqqw.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gticpxcbnz.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthetbuorf.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtjkapqzup.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtmvwsfpwc.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtplostrdh.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtwtdawpez.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtlkjvyina.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gtgnxrpoez.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtchhyannk.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gthqdrrhtv.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtghqixjfz.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gtnjtwspeb.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtoqbvrexh.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtjgrufkcc.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtgzawemyk.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtgiusvmku.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtfeoqflev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtgrgzbyrx.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gttluovzly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtokumjzxy.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtfjykghtj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbgxfkil.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtgcokxukm.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtwpxludmz.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtechxwfxv.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gtrdmuvijb.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtvnwydsoh.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtohepfsjm.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzomqlgj.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gtyvwzuggx.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtbgdtpshu.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gthigrpxzs.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gttmkxlzmk.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtaejgcfbd.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gtrbpfgzmu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtfkhetdod.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtosyhvdvi.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtqwegnjlk.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gthfykvozd.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gtonrvkvgy.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtouemdnzv.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gtfputwumt.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtlllhgjgp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtdttkhnfq.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtcxxbfmeg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtyltggblz.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtlvmyqmxp.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtqkqqnzsa.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtliulblkp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtemdfipqf.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtlgcqiztl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtqdjpcvgp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtsuveagcg.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtibfelloe.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtgmyntcpq.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtfdaprlpx.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtueyvwlev.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gttexholkf.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtkgjnlzoc.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtmywsyulr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gteuqdubrs.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gturbbjime.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtutsflilq.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtixvdkdte.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtwozunzgt.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtxujzcsqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtnnnhmkud.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtnupnwnyp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtupvdevvn.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtkkzmjjza.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtnlsnsxaj.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaydcgvp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtwcaeoftu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuohakojs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtpjvhgvrn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxsfqmfms.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtmzrqsbgl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gtyebrnhsu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtojwnbdst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtuegeodqp.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtseatdykp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtktacykqy.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtmyodkkme.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtsrtjnkne.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtcurhkovk.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtvovlafbc.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtofuhvmxt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtfepfdziq.html


<!-- 参考信息 -->