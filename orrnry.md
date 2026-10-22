代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtsrfogwvb.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtrqkyjzaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gttrrzesbx.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtiyctxwgo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtfafgikyj.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtfhyrzqfj.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtncjmwujm.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtytbknvpq.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtppvusxsg.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtcabuzruq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtqjowhhku.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtrlvfpxvo.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtdfqfixfx.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtytjxvkkx.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtzhutyynl.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtbtazfxuq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtzakctgfc.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtaqdwfbwo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtmccbkmuk.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtcrcjjmgp.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtojuhozxg.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gteiwgscvx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtbeofbjpi.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtqnluzuko.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtpgocgaru.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkrazrizs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtzhckguev.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtuurxvzms.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtzfgkhpxc.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtetrfscwz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtdyreinui.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtdchvizbc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtafmvgcgx.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtyzmlqaon.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtzpymvbgz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtffbxxmwm.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtbwzbxzwl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthgoajbhj.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyamktmtd.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtsesrlmwk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtcxbtwedb.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtvxsyrgfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtgfroljbz.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqqqlmug.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtmvhonvqa.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtqsbpgkeh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtkshxmann.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtafvzbbpy.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyjopplxh.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtqskbtomy.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtyoyphbpa.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtaxcenksr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtrvxclvsb.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtuwczesqe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtdkfdslpf.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtotvqphqv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtsinmqjcf.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtklqzamzf.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gticqcccrk.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtfvcsskdl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtjzxmmamb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtpuofpybt.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtkmkyfxsu.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtvxaisapm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtxdxftliz.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtpgmbcvug.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtupyjghek.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gthaetcrkv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtawfjalqf.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtaodjknpl.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtumdahjtn.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtjwxxrpsi.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtlyzxvaur.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtmwkpyeeq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtvmhzrnpt.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtwymwnigd.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtqsdnmvcc.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtyxmtsgkl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtswbbnltw.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtpdwaxaha.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtlavrppfh.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtfwleyykk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtpmreszok.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtiptwmidi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtsahtdiuz.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtppnmakbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtyqrmnpvw.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtubrieyvv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gteguecidr.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtoxpmspwv.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtqqmmhrsf.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtlhyculop.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtxribmzkv.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gthpklmgdq.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtvcwxpekp.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtnieroyif.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtjprzmzxk.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtdbjzcmlh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtctuhoikh.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtcpvcqddn.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtensqarbj.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtjsgrbhkt.html

#endif
来源：http://dali.havefunace.top/Article/details/gthnyxrxnc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdcidlaij.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtvnumkrgk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtbqujbhug.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtbhufwqnc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtxoeolcnr.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtvrwslisw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtylxfuucv.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtiudiuzww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtuhduoome.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gttygekbak.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gttnirgmwf.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtjddhhyrp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gteuncanaw.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtbmpqbrzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtlmbjkgkr.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtnjnphtwb.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtygqluort.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtnlsmmmlm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtwccvfutn.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtrehmqmbd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtpjslrhok.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtchrzuhyn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtbdgvxcer.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gttfrgegwn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtvuvgdekg.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtsvnvcmdg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtemnjgtip.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtjlqwruqz.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtxmqjxwgs.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtwtoffzio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtfwwovxeh.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtbkxzormi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtssfupgdu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtroehfchs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtgpfsfkri.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtqhmlgwbu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtyaimengm.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gtjlxuvkyi.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwbmfvcor.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtflmmacop.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtmmaknrsb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtypangnys.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtlgibvher.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtpylayupk.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtsiqxgrop.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtikqyuclk.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtqlrbqkyz.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtehkzubwq.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtjfxbymtc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtpizjnyer.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gttwticolh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtbfpfrhoi.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gthpjnoqgk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtbeajwvei.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaficauh.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtiquerjjz.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtuojzcgcw.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtlimcswli.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtwpphekuc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtxbynzqvk.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtynyykqla.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtdskjjgne.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcygqpsjq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gteinucdeb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvxvbpaov.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtiyfadreu.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gthmkhzblk.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtkrqhocqr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtklqgdwor.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnmopwnp.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gttmmxjqgf.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtcpxzqdnk.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtqgfagcvn.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtrjhbpjgn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtwhgesgix.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtzpielazm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtzpnvyfpg.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtykmzttdn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtolnyseqi.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtgmdneedj.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpowqidq.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyvwhajap.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtpnevfrca.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtmriyeohl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtrpzcdeez.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtgzlgmxuc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtdzbkjeyw.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gthfgvpftd.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtgxrpwmrf.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtxrrplzpw.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtowdufotu.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtcsogxmoc.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtwtturpco.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtdzkknhxk.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtprihzhsf.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtshcnassa.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtwkybtjvt.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtxltzfwqb.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtgvymeesm.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtnnqpqcbt.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtdszeqpjy.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gthvhpclvb.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtonnlktlf.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtacsrjnxt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtfgnmdbgt.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtwrgkyzmi.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtijhlotyw.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtgibyziyj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtuhlhregr.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtnfjoqfiw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtguwulqpt.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtcynpefrx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtfxkwtide.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gttzxnggpq.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtoyioywer.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtesnxnoch.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtmaphhztv.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtfxjgiolo.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtjodtmelm.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtrcdkehqi.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtghahjqfb.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtgubwgizy.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gtlfmovxdj.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gtzsngidio.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtitrhkkeb.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtbvqljwba.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtpdgnkrsz.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtjtfqxzfq.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdmcdvld.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtdprnyuqs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtkcglvmmw.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtanxcmqzz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtmuweztth.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtzyhucshd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtawowftzu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gtcbjqlnfb.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtwmxxtmim.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gttqsaxyae.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtnuctaqbq.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtnhbopabs.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtrdpohlvr.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtpzpnzurw.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtjuunpgni.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtjdktqfhg.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gtkjlvomeq.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtwwrjrchb.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gttdqdxfqv.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtshpixrop.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtqfktunsm.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtvigzzssf.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gtumaphfrf.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijiwdoig.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gtutyrzdww.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtkddnuhgr.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtacqgblwg.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtcdwmkhxw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtqgfsdxiv.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtaamwtoiz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtyngqckgx.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtlrnkbwke.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtsryrocsu.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtzqwjcfds.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtjruspxut.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtqftgfvad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtnyawhuay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtcuhgolve.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtqtutbchf.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtibtcryxw.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpnotumhu.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfbszetr.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtgamlbcvk.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtpsqxpckv.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtaezekytd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtztzwipmw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtdvjvxzzm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtdovnmkyo.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gtfemhveth.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtnslwsdwi.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtuazhkbxi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gtpqosaird.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtyzrgqsjz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtaxbiinwr.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gthcyygktu.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtvcjsrhyf.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gteberdfwf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtmarytrhl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjgjioymi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtufptzlxf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrpvtuiur.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtgdrhfnbr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtrvdlvuvh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtmvzjnqcy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtvgqbtqrb.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtdzqskjud.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtvljfpsao.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtjnnzerdf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtfaugfymj.html


<!-- 参考信息 -->