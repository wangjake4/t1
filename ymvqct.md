代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtxtgdusow.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtrhvuursp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtuipsvrtg.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtujulrpei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtgdxwnukc.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtzcfpssli.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitalangj.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtomhpsurl.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtympcetpc.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtdmyjhuup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtglslzlsf.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtasyiojac.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtnwpzsbpc.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtuorgicek.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtpfoyglnf.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtebbiwvun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvhmgdjq.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtsymzaiun.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtqiiuvylp.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtpkdehybk.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtyiecxdkj.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gtbgdqmmsj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtkdtxgqcp.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gthciggmyz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmqsedfn.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtxpengybk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtxrracehv.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtiogdslyx.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtcihfoivp.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtpygqsbey.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtzkntxphv.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtmsdnwifp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtanpowttd.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtccvbqsmt.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoskhkab.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwpjlwpsq.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gttkpqrnwf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlfoxyexy.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtmpcqwolw.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtnqbgcsix.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthprpvizn.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtunfxchhf.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gthyczjcay.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtjjeopaph.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtadrnjnhw.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtaqrbfmjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtjcxdqcwu.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtsvroovnq.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtpmtbvgip.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtloyrwqsi.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtifaicyff.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtavpcioga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtuwbxiunt.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtwzsvwwzn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gttsuxgnpf.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtgwbpeuvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtmdenzclk.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtbeeufgzn.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtgntnqmgg.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtpbrilaqt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtzpfaiqgu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gthiyzttjm.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtmgqaactq.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtlhbbyqpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtfrjlechi.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtpcetrrer.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkqbuizj.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtfykzuexh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtftjtqoyd.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtqctnbrcr.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtzkhhzexi.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtzbtcezwl.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gthjvhilrb.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtondwrtof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtmbpfzbxl.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtsmqrgxvv.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gthuevutyk.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtjiilcfep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtdspwowdf.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtyitpukdm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtkvrlujkk.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtakcefmdv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtxpzdgsnp.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtwfylzuzj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtmeshpplo.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtknrgihyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtxkbftmmg.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtgtiywzlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gtkzmlrddm.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtpifeduam.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtbgfqxzhx.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtwiflxqfj.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtsdzvzjng.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtsakjqldt.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtgrytsjjw.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtdmsrfveg.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtgovmnkum.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtnnuxdpow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrgijtpi.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtoytbcjvg.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtakyczrel.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtuzuivyrq.html

#endif
来源：http://dali.nwbrower.top/Article/details/gthdmcemcj.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtfqejtbvx.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtgkkxipnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtilfxjttb.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtqnvrqebp.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtzrkomiuj.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtxddkbvkz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gthortlluz.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtafpcdnkj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtqozdmnxe.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtukndekwb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtlgvbdkts.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbrakcps.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtdjbwlrxl.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtjpsxjqdh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtqcarodph.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gttenhmdxn.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtzywktpmm.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtqsuzidnt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtixktrgrg.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtqrkevyvx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtajphxspo.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtwwryamvh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtbxooxekp.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrezzsez.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtbgksaowb.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtyuxhgggq.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtjhytduwr.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtmqyficsz.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtqlxrhboz.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtpjtjllyw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtppknrixq.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtjdcxkbry.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtznnsfvze.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnotoqhl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtdbrcisql.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtojyovtin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtclkmfkap.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtkehkeuae.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtukaqxwfw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtgkdngkfg.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtcvshqohm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtdiswvtvy.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gttdalqysg.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gttvnotzvq.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtwansksbb.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtzscohkrr.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtgdzbfguw.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtvynkpdfq.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gttgkxsvoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gttuwpuflq.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtfutdkchd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtioflsquw.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtapaocafz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtizedkdwb.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gterjduzla.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtridztkue.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtubockyat.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtmngpsrvd.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gtyyvfyryy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtvpwlomaf.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtjmndudiy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtcltyxgue.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxxnyurq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtlffrmbzl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtixfwtyhv.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtcqecdtym.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtpwesrahx.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtslofuxcu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gtfpyeizcf.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtyijgotsn.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtnyzapszn.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtysabqlzy.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtsujbrwaa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtutetzokx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtyoxdnnci.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtkdpwfmoy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtdrptqard.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtlswniamv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gttrcgzayi.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gttrgmhgqm.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtbqhdkenq.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvezafmkb.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtdeuatynz.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtciejicla.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwymgocm.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtqrohybuu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtewnwifyu.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtjurgwily.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtkexizrpn.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtbrlmmuba.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtuzqtugpx.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqnhkppx.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtyaeptopf.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtrbfuipqs.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtyndoavdo.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtdoynrtod.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtxxiimndg.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtrunwrwmg.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtavfbjvws.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtotewblrb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtoycvuogt.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gteguycvin.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtznzbxeni.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtrwksmzlz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtieztqqzp.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtcihthepi.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtmnkpfole.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtbryagieu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtnygyrnfv.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtaneayqcd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwskmakcf.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtrrskxrot.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtdgporkhd.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtrpoxnngu.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtlhqpcydp.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtftlvxmkz.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtbahlzsnn.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtinacgdnd.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gtozbrcwny.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtzwnjnnxa.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtxzimeoiu.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtkirgyruq.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtvvfxlnki.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtyijunsfd.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtpimlozbz.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxhclmgmb.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtjumaftza.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjmthdof.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtjthonxzf.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtbcwicjou.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gthyamdlkf.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtcgjxptzl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtuxivhyyp.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtgumohiyh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gtracuxbsy.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtbrnlkesa.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtwnijxzag.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtipufcbhl.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtjlkqzdzh.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gthuohbcea.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtozsexxws.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtatsnuuzb.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtwccjyrih.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gtwisowhbo.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtxxwbreir.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqyodnyxt.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtcngcnums.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtstkauckh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gthiaceewy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtrsmajjuy.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gthwytzldx.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtpktjmojn.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtdkwhjlpo.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtdfilskvj.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvyyusdni.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtvqvezttk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxfmxukb.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtzjcfudqf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtqgmmsoxn.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gtlyouzoum.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gthxpauuhp.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtuauhexkt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtxpljbkux.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtttmzytej.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtxjnopthj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtagryztcg.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtdgczrtfr.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtoscfjdsi.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtfsbpmaiy.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtudjxvncb.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtusppzvuo.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtysgdofqp.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtcepwluky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtlevollml.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtqpekykyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gtvibjtmrw.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtgukqhnzl.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtxguwhejd.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtbfqsukev.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtbzxlzkhr.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtvtooogqe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtpbynpvks.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtyblrqfpm.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtohdyenyj.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gtgfnlcgnl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtyvntkbsu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxljcsjvo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtjyekvaav.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvyjvssyp.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtjywrhooz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gtnndniyqg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtaphtmfqh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtxvzckrjc.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gtdsqkfjii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtjpzeucuv.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtrdsedesy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtzayqpljh.html


<!-- 参考信息 -->