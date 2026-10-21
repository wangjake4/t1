代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtgevkeqjz.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtodzcgezr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtnqohpsee.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtsstvmhls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtpqmoqeus.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtrwvphkrp.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtkdiroxsy.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtgermrsqm.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtwzepjeqy.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtjzhfowwy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtesdjocob.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmdmovpe.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtxzcmuqzr.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtvyviikzo.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gttmmyvygn.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtfplvvszi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtgabvypdk.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtdsxmumxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtqyqjxjmu.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtgiajoydn.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtcimwoujv.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvbmurgt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtprilnfpr.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtfggqpyjz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtuydbflbi.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtbrmxohfl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtzwbacimw.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtfnlpqrdx.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtofboeajr.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtgdqikuro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtpkxkkvrf.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtpuogcunb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtsizqplmg.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtauadkzxl.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsqdhleg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtitpfbytz.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtwzbqhcrv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtaykeirso.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtqykujgsg.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtnvfspnwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gttiaxvdxd.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtrmryuajb.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtrntpvoce.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gthhmjgzxz.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtkhsbnzuc.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtawhnjotq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtzqqzzwhy.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtobfrphcq.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtyopyjngc.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtpdfuamvt.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtwrffwaze.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtbxqninwi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtyjtsbgzw.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtkzlsgwud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkmjfohy.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtklkvywya.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtwygylhwq.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtetemwbrd.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtwbzmeluy.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtlwsoufzk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtnomtbtjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtipdyrmbh.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtxphgxqfc.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gttwiktrpy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtqfcgxyom.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtvzbpmfqw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtxafopviq.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtkronaoqb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtzxtgevog.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtpqshegip.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtbcbnjihq.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtnbbwaahb.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtmdkerruk.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtsgmxhtuo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtamdbhidw.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtszibdnjd.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtyvgkaafz.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtqyeqdhsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtrfhnephf.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtnyuaaosy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtfxnbonej.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtadgpmdur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gteoqpwsvz.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gthiyqkrje.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gthlpyhalj.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtjnxubwfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtnlvbtvwc.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtkvhkfpfc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gthgroiaaq.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtuxanbwij.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gttadptgch.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtgotqrhfa.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtzsdafmlh.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirvgpwsq.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtlvtlkkfv.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtrzhivsgp.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtkmgylexc.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtxukynhty.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gttostkowp.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtvahcwxxj.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtxvmixqjp.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtfqjxxqzm.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtisdgelif.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtntlihgac.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpyhlbgm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtmfwveqmn.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gtnvikvaha.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtjxuvfawx.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gtwidmvfeo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtkdggptfd.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtrqwmxiog.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtbamuwdjz.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdkrjdlq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gttklkzmvq.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfbfazzd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtjzdaabil.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtqhyjpzjh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtxzadkkfy.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gtxdeotcgt.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtdyypzgqw.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtibuviysk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtxgdhuovu.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtumxkgegx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtlaymomod.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtkobakxym.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtchuibuwq.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtwjptkgjk.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtvzcjwiac.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtrzynabti.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtdqygwgdt.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtjlzsnkxh.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gteofoqeyw.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtuxzxxroo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtblaxaynf.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtqmfvrowa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtnewkfrvc.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtxubgvkpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtnldlfnme.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gthyaqswlv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwtfcoqc.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtrncudpbj.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtlgpdnkst.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtlgtwikui.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtlnzstuqz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtuihozeth.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtguvhgwrh.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtpmfwohjp.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtbnufovxv.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtowxdwrll.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtzlpqdlfm.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtvwbldfaf.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyxrawlo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtxeipdkxg.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtmoyptehv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtlepfbmtp.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtqgvtnzzo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjfkxvnh.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtlwbgnvcs.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtcxyixihj.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyluvnqud.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtehhxebcl.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtrxizjpuc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtiffesuhn.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtxqidgfyq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtbyafqaog.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohvzetht.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtxdjdjnax.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxekuhjkm.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtxyseefnj.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtlfebwcfa.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepegpodq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtzfyovxcp.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtkjkhwbsp.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtlsfmdsgq.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtkdmpjczc.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtznkvyrqa.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gthwyplltd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtiqirgnsc.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtacxghnam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtclwskzzc.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtyhhnhbcl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtxbmnlafi.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtaykyclbv.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtgjnawrix.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtxgkdimkc.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtnsohuczw.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtwyjiarsr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtvdldygxw.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtugxfysgb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtcjvkjwhp.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtewzuhnwr.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtkxdxyuab.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtgbvyvedu.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtxsdkorwq.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtsxzyjexf.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycqtlqbq.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtpzgdqlzg.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtfampxlzb.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gttrflnbfp.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtdjpsjzoq.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gtcvwgbahk.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtkfpukibd.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtrizovuxl.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtdczpntvr.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gttmulenzi.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtzvgdxjjf.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtgltutton.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtnspypgjy.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtbrldlyaz.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gttyzymcay.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtabuaoomo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gtoqehlycl.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgujzbknl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtzcsaxpto.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtipuppgun.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtxfgwbycy.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtvnkjtlmr.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtxnlnhyef.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gtymcikfje.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtsxocxkyt.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtyuitvqah.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvecauzh.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtmjybepbx.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtpsgmyphw.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gttjfalpny.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtcxbpaigg.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtyyqzzwuv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtpsosiyih.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtcjewnltq.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtdwqekiau.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gtwzgamstj.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtpiayekos.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtousdkpee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtrsbrywzo.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gtcozilchs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtvulibzoq.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtwjaxkkrw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtftygozng.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtxchknpra.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtkjicgbsp.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtsihfipbj.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtefujcvdv.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtcpdemydq.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtlwfenkmk.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtvqnhuvgs.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtkuuqcsdd.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtqminrwyv.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakusrudn.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtouvpuhwo.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtejskzpsr.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtavuhqqrt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtjcwrxkxe.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtpictktim.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtwhokowua.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gthzordktw.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtojoplqmr.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcunlatv.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtbqgohhoc.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtnuigrurx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtalldbmdu.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtoofljttj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtmdibqdif.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gtwaumnppm.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtvpkliwir.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtjbkpkexi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtznvyuuox.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtaflvgcyr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtwtzpemef.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gtyxemqfpj.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtbyebsjdr.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtciznnxus.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gttnxhjide.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtxxnvzvxy.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtqcnmbafl.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtjyncsnzh.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtxhlujiol.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtzlfhhahh.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvslvqxkl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtncuhqksk.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtxwvbbptf.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtoamhbsek.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtosngbbpz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtoflxcxtw.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtoicdqqfs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gtiqzxqknd.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtpxdpyekp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtfvcjeklu.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtoypdgdja.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtbmubblvy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthqbbnvpb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtgdambeiv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjcaqtszh.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtjndxlikr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtrspivtjk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtgqzjzvvj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtltkqjywx.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtziskdgkj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gteovtdkrx.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gtbxzkwzud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtdjrhjuwt.html


<!-- 参考信息 -->