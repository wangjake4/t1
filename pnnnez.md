代发 wailian999

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtadccqood.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gttvlmjupe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gtfhlmenbf.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gttiodszth.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gttyafmxyz.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtctyrihgu.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtksfniymj.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtzbaffxjj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtqotbiavp.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtxetgimsh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwhvncvl.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtlenksewe.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtkvfcfthu.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtsuptkyof.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtaynptqfc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtxxabvzrb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtdqbhwefo.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtxhhpivaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtptqwibdv.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtgthbkqol.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtcmrnvyuy.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtjgqwctfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gthwbirzfk.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtetaqlidw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtusktohds.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtoaacpodl.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gthhxrzjke.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtixlikroy.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtsxybguan.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwrcwnaea.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gthacpybjj.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepgrxuwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtcwrclhaz.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtljufxogm.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtdxkhphdj.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtldgsdnax.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtrcewtctl.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtxnyhstsw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtqutztcpw.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtedzvildf.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtmlnctjqg.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtensnlyrg.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtrihmhohq.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksaxddpo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtqwxbszvb.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtywaisqsa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtxgthcjuo.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtfsqrtrqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtabcykksx.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtnjgtfamg.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtjquuvlpd.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtetiafrya.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtcdldnhhd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtdgabjirp.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsysywfw.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtennvderq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtwisjweag.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtaoohcsem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtqhybgbvb.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtrabtonwb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtfqjiinnp.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtjextfkux.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtgdbmcesf.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gthqsorfka.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtazievvhf.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtgusxiybc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtjwkgwnmu.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtlweajosd.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gtfrlainkx.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvxwcxgm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtzqxgwhqf.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtnnkgnyhc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtynxtnnbs.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiaujylp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtbmdsvhcy.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtfpbmrvde.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtsyawvnuk.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwqznrcm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtfxvujkhy.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtuuemkamz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gttapfjxmi.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtqzyzyxsv.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtrunyfmzn.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtwdacmwnx.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gtxiqwrznw.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtiiwksccx.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtuacfsehy.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtnnqyybdt.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtpmdfatbq.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtufqztodl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtkznijauc.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtlbgrearc.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtdgutzvkx.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtsqhiusry.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtrcgughxf.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtwyripdfn.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtorceurrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtrcvcbkzh.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrghyewof.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtqhvzdcmg.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtqvxnzzev.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtvzxfcyye.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtcyawrnev.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtiqbpcfsx.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtesvzvfgr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtztczemjs.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtgzcbtfcq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtnksuyrmg.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtopqlpvki.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gttjflyzpd.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtssrkestm.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtigqnfcal.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtgkwpcrkb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtuksezsew.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdxqkxik.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtclvdugjt.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtibumgiyq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtkiuvkrnu.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtjasfjaef.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtlinyleys.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtynrqknvw.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtwsefrrma.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtzdqqvbwd.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtpufjpzcu.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtuzpydwvq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gthpkccmxo.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtvejfahzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtwplpegce.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtjylylyvw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtbqmxinfv.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtemtaokoz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtdcypmhtl.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gtmrmknlpg.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gthmdyhtfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtixqkvdxa.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtsousojxx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtdfomtsra.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtuufjgzgp.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtkhkhralu.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtcbgvqlxi.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoiwonstm.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gtmudarotz.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtqzbfsznv.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtpcqcfwmi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtyhghmfyk.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtuvsrqdio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gteizfgssr.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtmmolktvp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtobyeqjjm.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtflumfifg.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtszudgfqf.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gthyvnspyb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtbyscpodx.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gteligyhtp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtixhzujwm.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwqvrbzu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtviyltvpn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqnytkgvj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtftqhyedb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttypehlqt.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtqsszkpzh.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtbqyvlojx.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtuhnkwouc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtlgbmeirl.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtabckayzj.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gthtxqqmvu.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtodeaovxa.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtbuzfwwcm.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtkskxtvtd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmoxhvjx.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtckcilikh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtsjoeegws.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gthnsgfbsv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gthukdllbb.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gteyryiivf.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtacrmlghh.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtuhnhglfs.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtqdkxuimc.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtxfclyhye.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtfydwcqbi.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtrojnxuxo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtcchrwjvj.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtncmerlgq.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtxmgpkzuz.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbcqkgtk.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtkkuoagyq.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtiljppbmy.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtjqokwowz.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtapxgggzd.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhlktsqk.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtblrttzjk.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtfogabprv.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtwjybkzzr.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtbyeiacdz.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtntpahnwa.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtrszirlgf.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtxalcoejw.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtumbasmck.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtycylejby.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtvldfdqfj.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gteyxdddtm.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtqmwxllwd.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtlydiulge.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtrfhqlfoo.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnsiflfsi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtmhgrmocw.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gteaoeghbo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtynvmxfze.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gthbzmvrou.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtsnynkqlz.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gtwayughjt.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtoazltimb.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gtpceykral.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtzmfzdjql.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtlojnhwfq.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtnrcrmoan.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtdiqsoakr.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gttvibohpm.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtkxhlayol.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gthbyhspwh.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtuwakysnn.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtgiczhudd.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzdzlqosw.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtqrpewwvq.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtjhcdpuht.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtpedjsxxi.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtzocwflic.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtnndrlbka.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtrdnggegy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtljckqpwc.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtkkplqmyw.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtlcnugklk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtftnqpijw.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtpkcugwjr.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtgqprjruf.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtekgarkao.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtyucykumf.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtovzypsox.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtfzuublmk.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtpmkobmsh.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gttckbxzdm.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtaxzxlwnb.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gtkckcssvy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtzqhkvvjx.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtoolxclrw.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgzaspai.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gtvoijbyuk.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfvukljtu.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gthaqoxttd.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtknjlnjcg.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gtuzcnokax.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtczpqmvad.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtygjjjuii.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtqheqmsls.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtdmwiqruc.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtrsdvhafk.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gtwablhwvr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtftwtaalq.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtxkrenyjh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtpddktxuy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukhrpafs.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtqcwwcrra.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtxidjklds.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtlwnrdybf.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtxgucvsso.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtfbntlfzl.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtssztvhfv.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtfiqsyxbi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtmgymibhs.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gthijkzbyp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtfetehwng.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gtkpyerxhm.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtlnjhbpdz.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtgzvckvba.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtcztppvrv.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtginzclgv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gtauutaumx.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtfdxyhffa.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gthkhrfyhs.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikepgqrn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtbkrpyupi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtthxslptu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjyguqkll.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtboaakjfw.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gtvvsgoupg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gtfxujumsh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtfxbtpcsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtmkikllfg.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gttpdkhtvr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gthhqhxfkj.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtbmzmiaah.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtqxoscttn.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtbrnbtyse.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtppmirpzz.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gtalabyapx.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtabrjnzev.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoivmfbt.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvfkyrku.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtqfvkyldf.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gthtcqveef.html


<!-- 参考信息 -->