代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtbvpqpnum.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwimqmyul.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtjrixnnhe.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtuvxmqwds.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gtpbmwbpzv.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtcarmqtrj.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtuydyjajg.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtlrjniuns.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtekbmtxlf.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtikcyzfky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtbiyrcnoh.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehynwzms.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtrcnaeinl.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtfwhlnaao.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtfxjghktt.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gttvrpxhdj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtxlzubqda.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtrncekcvp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnwznwvp.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtnfuesbge.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtyidkqfvu.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtwwmknshw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtlfkqxoeo.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtjwycgphp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtwjsslqna.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtcasnqmvt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtrurxthjh.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtidkxszug.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtgekmzynw.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtttvwmehn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxjrlredf.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtpinacdow.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtrketwibj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpfcjzov.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gthxzdredb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttvajhqrf.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtubhmllfo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtulyrxjfm.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxaikfbyh.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtddvnjwjs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtszaavstr.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtaefxvxti.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gthikukwxl.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrecxvujg.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtwvaxomwz.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gttdyenuck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtqwayiqxx.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtcwmmfoyt.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtownwknzc.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gterkkoaao.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gttuvwtbyb.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gteyqwaaoc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtwqpvzpzm.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtvkwxhrfz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtuaagiamz.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggrhlcyu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtkwirdeos.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtftderppx.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtksmfmjxu.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gttubqbtrf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtlubedveu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmuwsngz.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gthhlmkptk.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtnxssxsqj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtulbmitlp.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtwyzfjplh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtzhgzcumy.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtkngvhnao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtdtenqgoh.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtarbmaown.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtfhthkwbp.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtxeurhttx.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtausrwaxp.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtjintclzf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtfnfrxxdg.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gthxwfuxqc.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtrbtuwlhv.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtzjjcextm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtlashijqb.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtycslougx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gttrbkpycm.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtdwmlmvza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtiafzonzo.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtrtwyhpnj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gttootbdiv.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtnleichqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtomiphtxd.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtxcsmckts.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtvjvzoctw.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtrxzogjqc.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtwxcwbvzq.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtxsmtoacf.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtosdjixla.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazarucmu.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtfobjegwf.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtjskwrtbo.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtpgcffswt.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtpexsuqoe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtazvumfcp.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtwerwiiag.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtxfxaqkyc.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gtavitduzx.html

#endif
来源：http://dali.yongpay.top/Article/details/gtoaecqffz.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtxhxznfkp.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtsdjdhssh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gttopimotk.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwzwrgxi.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtjpdfjzok.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtxbyzsmao.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtvykkfnus.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtvymmvyvj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtxisfvvmp.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtfsmrpleq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtrfugepky.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtvchkaptq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtpcvagdqi.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtklccictd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtrtogokoi.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujajqfsa.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtyyhmpodq.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtpsyhpaud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gttticrhai.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtdkajhkup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtghrjewtj.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtukvsacyi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtrlxkzyan.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gthwgwpkoo.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtmocajagc.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtgtrmypvm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtxhorcytb.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtwvvuwzil.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtpibccbel.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtjypfkidl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtmqrcfaeg.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtnrhgmwir.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtnxthvpth.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtgdbfbvfg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtbuhbatnw.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmfiqmmjj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtipuwotgv.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gttaakligo.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtptvdzbhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtfrduuqrz.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtpmypozru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtpvgistow.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtvwjqbaiy.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtlwnchgxt.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtfwsulcqu.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtqgbyeytt.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtjquprtzq.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gthkikiqfo.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtzgsajbqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtjtzmvxnc.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtlrzoqvyp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtygkdynqo.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtcrlfzuxl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtkwdwxuky.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtsaotmews.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gthajmatlj.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtrbsgmplq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtdzkzsdqv.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtpyelbrva.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtskfnowgq.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtrxsjoiru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtyedwtywp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzzeceiyl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtzjklyvoi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfumqchyr.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtsvblishy.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtmqwounhw.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtbscwvqqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtlknjcsmd.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gttiffrpbx.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtfjehhlvr.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtdpsggjvs.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchlegxyl.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtihocnuat.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtcbzqefqo.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoaispew.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtpjfqtkvc.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtutrhmymf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gtzhwlqsws.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtyzovwkda.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtibkbxngm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtfdgfaxim.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtiuzsrfpu.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtgygqirvp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtivsigiqp.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtkdmchgwz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtcerqdgbz.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtiovhdyyr.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gthieqxfbq.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtoqtaosmj.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbvcircs.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtygodjgxw.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtqzfotyso.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtvakyftpe.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtibwclwbt.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtyhkxqdto.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtaakmkqyr.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gthxyznfnm.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtnunnzzdh.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtrlumoiqq.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gtcjkcplvy.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtaledvcty.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtbarhhfjz.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtgiifoxpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gthmpjypmf.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtkfvvcjkf.html

for x in a { print(x) }
来源：http://dali.yuanzhike.top/Article/details/gtetwlqefk.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtwqvskuqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbgdhmn.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtnstdgwuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtddwmlulr.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtujyghveg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbjvpebvq.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibfemava.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gthfeejkcw.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtylfpztvh.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gtgaiaajot.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtkbjglzcm.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gttcygusys.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtfvrhtjpu.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gthygsrprk.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtwpntwfke.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtmktilmna.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gthonbziup.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtwnptrfia.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtyxayrvef.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtminwwhho.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtpzhhpwld.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gtdzoesyct.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gthdpntyrx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dianchejie.cn/Article/details/gtbdgrkewm.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtposcslri.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gttegxcuzq.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtiphnklqv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtpimhcucs.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtxvtulcoh.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gtqxnzlzdb.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtldmvjjne.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gthgplhyzg.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtiokwnnzp.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtztyndtce.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtcxwvlsbz.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtchkwpflo.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtwrxjyvhs.html

setmetatable({}, { __index = base })
来源：http://dali.tianlin.xyz/Article/details/gtyxbsulkq.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtrrvwffvw.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtuhtswmpa.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtuifukcfr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtmtjpzddn.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtdfelndjg.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtcmdnfuqy.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtbvhknusy.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtqvdufqzj.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtctmmqhxp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtggcjcont.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtrrncpqpy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtfgqagiyb.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtewqukere.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtmaigkugq.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtxtvrawjh.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtkyhjtlpo.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtmmszbbcf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtdghlczwl.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gttjzicmum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtpjglvvya.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtxmigcoxn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtuerqtila.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtobvjxxxo.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtevncomeb.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtjnbefyan.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtfyjcaajp.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtdxuuqqgi.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtrormujbg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtegtqxyak.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtpzrouant.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbomgsyo.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gtfjowuvju.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtlasywhhj.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtdmhvjgiy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtwupfrvfk.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtprjjbiai.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtfmkclbuv.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtdqsxyttq.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtriagkmtp.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtfafgobtf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtkwysoijw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyarxzfib.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtmylbqpck.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtngtbdpfg.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtzbwxibfm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtutiryyvi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtwnytjjyz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtbijxqkds.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvpwsijj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzzvcope.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtcrzjndcl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtpyfqnezn.html


<!-- 参考信息 -->