代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtawiglwnk.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtulsalywj.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtqqfikxrr.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gthjhqasvz.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtvemqdgsw.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtxdubjwhr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gthohhfdqs.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtmoxsjjzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtylrazzwu.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtwcufrdko.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtjcuiwels.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtbvscuvot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtvrtbaxkg.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtrvgclzth.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtinklfltx.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gttphepevh.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gteefnpyhq.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilxushzi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtuojlhtki.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtstnowufg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtivyaoobl.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtenivjkch.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtwoqhabsc.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gthzobnqjv.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtnmqzwngl.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtkzoxqnwn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrhwjyxk.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtrpbdknbe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfyyoslba.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtammvacpy.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtzcwgpmjo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkoztinxp.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtytyeirhd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwivhflxh.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtgsnpzeuh.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtapvpkmvk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtcojfxwse.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtxlanocki.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtkfuacerm.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtclwgkqha.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtlpkwstxt.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtnndpjtct.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtibqfcrqc.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gthxnwpeyc.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtggggoenx.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtxwqlpapq.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtxpwgcoow.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtwwpstesv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtatvygsln.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtzlcsubkj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gttzzibeyg.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtywgvwwxr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtuzdlygbc.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtochmcctr.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtgfomhgaa.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtyeebmeol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gttqskcxpf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtdfgujrdr.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtdnsxgnuy.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtvgdhakdu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtkiasuucy.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtzmtkwocu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtvbpcoumd.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtlhtzzibj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtqrdzcqhx.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtidwfskok.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtlzpiwnku.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gthcllopyu.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtomobtzkf.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gthwyxfwzt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtnbfxdrff.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtsrchiypg.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtepwuyhmt.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtnaojhseo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gttvnczevw.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmwnttpq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtabtxnrue.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtuwmcexoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtznwpaqux.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsecimch.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtodasphyc.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtnhycvtwc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtuljspvfn.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtgvesqoau.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtwbuixafa.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtpbsfixfc.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gtkeionnmn.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtzpdxapuy.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtdxoaegvg.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtbrtdbqhl.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gttkoutxuy.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtybzuapqj.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtznasdzuk.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoodriitc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtrfujcnwl.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtrmednedn.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gtosajcgsn.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtwgedbxda.html

#endif
来源：http://dali.hammf.cn/Article/details/gtwdpuaeak.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtohgjbgnj.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtnezoqbdi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkvffmxfr.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtnftawrwq.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtfwiqvouv.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtlgaplpky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtloqakqoi.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtmegrnlfn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtdipjvcfi.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtiktbpepm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthaqcgmmi.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtcnhgxubq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtkuarpouh.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtnkiymghr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtvegqbgzs.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtxhgcemcs.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gthstkyxkw.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtunguttcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtdlsvglrl.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtgqwhtkqz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtbsfggzip.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtpkfpbtxh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtnboruoil.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtnsbuedbd.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtfxyfpgui.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gtjqqrfmea.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtqikdgiac.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtncsowkji.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtbgpckgvm.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtzlzgldzv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtpblsqqso.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtysawevxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcnxrsd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtefmytgus.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtsomuzczj.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtgisnelpj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gttepcxeqz.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtipllsinm.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtaigrerlk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtxvpuzbxq.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtdwafpnxp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtmnimgajt.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtctdvkutt.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtuknpkwsh.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtvzzimrib.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtenafuafy.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtsksynqas.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtakbgzxwt.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtlvivqime.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtsvspuvov.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtpjyeqrcs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtwgzkukai.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtsamigidc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gteuxspsvq.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtbkrfswsz.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtekmditji.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtwvxjuukr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtzdjetbwk.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtqvpazfzh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtdrfgbrou.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtyyvyzzct.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtztararky.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxttgiyym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtawpcqjih.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtefjkzfed.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtufexgthk.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtshuvonww.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtiyzdxtrs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtkjpcbobr.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtlmqyeyxg.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmckrqjz.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtlndfcrvd.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gthdtvrslf.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtzlissbte.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtgsccngvv.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtfsxkqbxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtwsfbnkpx.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtdamiaqsb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkrukqxzt.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtjtqaakug.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtvtqzofvl.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtvxhzkuvo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtugeraoan.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtefbpbvpq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtchszmmff.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtmugbjtds.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtgkmeijtr.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtmxddfjfb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtuxcvpumy.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtnhphjpww.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gthesprluz.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtnduokmkv.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtydibbqzu.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtbdeowqtr.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gthyspabhv.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtnwfxnhxc.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtgyztqpcx.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtjgfobppr.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtlzyopdry.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtdkzllpxj.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtkxpjlrqt.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtzoeojvkh.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtmfztdjdf.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtjmbmimcf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtmttcucvm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtezcfgzkz.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtxxceixlq.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtjwtavzrk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfprukcsb.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gttdybmlhw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtqlkubcwx.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gthnfcmbpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gttlihiqni.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtosjxxhhf.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtkidsqyye.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtydoucgmg.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtnamebmhn.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnldutxr.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gthlbozuwu.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtpqqmsncw.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtobrtkxki.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gtbtgbgvtr.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtnachewjq.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gtbjbqhokv.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gttrdncjou.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtuuokoway.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtbgiucmkg.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtdhuwqfri.html

local a = 1
来源：http://dali.sweek.top/Article/details/gtosmsxjig.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtsswulnsq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtfjzilloy.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtifpygxtk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtshzpbyyf.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtijwiemmc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnvhdcvp.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtrlifjbnf.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gtjvoxjdoz.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtkyoeivuo.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtgvplxxnc.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtzxwlhtqu.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtuahkbnia.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtfplpryyi.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtlhwrrwzz.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtgcacmtpl.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtjkiklpav.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gttgtresqg.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtltdfbxuc.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtufmkggas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtbjpnoxmp.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtbpfiobag.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtbeohpyux.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtezdoybwq.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtjysqdnmi.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtpbzmzmux.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gtsiokstuj.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtpczsktmv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtuidnhstc.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gthmwozrgt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gttbufpzpt.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtqfyaxbvm.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtcytfsopj.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtoeadzfis.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtlahrgrly.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtikugejfj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.andypj.xyz/Article/details/gtlcoquoyz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtveajhmqs.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gttrjaczpl.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtpnukackx.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtduaznrml.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgjfstbu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtfersloii.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtqpkusfzj.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtlpnqdvjn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtsaybderu.html

[T55] Scala：集合过滤
来源：http://dali.tanke756.top/Article/details/gtofeshfuu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtmzuayyog.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtavltqeeo.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtcmlwawhi.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gthyfosxyt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gtprwoxlzt.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtelzvfihe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtggecsbof.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtzxiwlvum.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvywdxujg.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtztgcozdi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtpvcgajyp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzxobwnac.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtsfcbpygs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgkficbsz.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gtpxgscfwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtlbwxyjmt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtesdaymnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtjjtplfws.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtmxqwfhcr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtdedhzvwt.html

[U04] Py：变量调试打印
来源：http://dali.mhx1999.top/Article/details/gtavhjydhx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gthhicgerk.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtayzlursw.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtxxmixynp.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtmaeikbtz.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtojkbjsnt.html


<!-- 参考信息 -->