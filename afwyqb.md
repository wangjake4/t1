代发 wailian999

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtcfokmlwa.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtcodxwmqc.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtilvcwvki.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtxqkpmszb.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gthucycxyd.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtuiksmpus.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocityndc.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtynqwhtnm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtfxwcqyfc.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtxcfzahec.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtcfovykcz.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gteajawbjl.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtcpwwxgbc.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtpgwpchxm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtqyuucxuf.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtjqzgzisl.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtmwdnyeta.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtrmeogyhz.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtiissgfwh.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtrlbwbaqz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtmffsjvdj.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtuzkgkxmq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtfjmctrzd.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gtcmxduyxk.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtqxanzlxx.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gthjluuubs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gthekwjnix.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtqgxqnjsz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gteqjegvvq.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtbqazpgqa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtfocxgqju.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtvyzogkbt.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtdymrjoqf.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtnbagzdla.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtjepsakof.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtzfeygbyn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gthlyhtuwi.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtrxnrujct.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtkbwlsltx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqwqftqja.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtaecsbqah.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnyjtixms.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtofqysjor.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtmddbsrtl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtclvuwmov.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtrxglxmed.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtzmwrxdhm.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtuhdvpztg.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtzcxfwdzs.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtqnasmuiz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtgqyivyvt.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtduedvegw.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtcycqlwld.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gttwwyieyz.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtlfhxhkri.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtgwjlddlo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtnmiegwjf.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtfutaldvz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtrrnaxnro.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtzwqyiagr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtijlxxhlx.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtrceealwc.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtcdagolul.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtvayganii.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtdemhjphx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtrrfrewby.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtnfxourls.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtuyyvvhvx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtuctklduf.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtxrjamtow.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtkgzpkzcr.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtlafhoczq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gteesvozed.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtcfwgobhu.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtfvimmqyg.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtknkamoar.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtlhfdxxxx.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtcrgmqpnk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtpjrnnfli.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtpsdjjxxt.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcljssziz.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtzjyxjpna.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtzvucftla.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyxinvzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtctbxdtfa.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gthubewwul.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtkkflhmso.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtvwiabrti.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtozlkcmgg.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtxpyhewts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtdpycxuwd.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtiimrhrso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtmwcesanx.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtmsrimpfi.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtxdwzkueb.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtfegyhabc.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtxvuyprfq.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtpjdfgijc.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtwtdvxhai.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtcsngznhw.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtthhdbrmt.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtxbwvhtzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtirbeadmj.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtwhimrwwm.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gttbeuukjd.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gthkgqgagb.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtllvdtiip.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtksgeqzaw.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtanfxvilo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gthajyymlz.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtelyxawvo.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtainhorzw.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtpsszsnor.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtgrsmagnp.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtlqsbjbaa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbhhrqczm.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtfzeiqrzh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gttlzqunbe.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtnnbbuebc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtbornsesv.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtmvhsyjwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtbexdfmyw.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gthquavxtr.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtnizskkmm.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gttkkutndz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtzacztmsv.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtubxsrhaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtmpgjvtyk.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtylfmmxlf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtlqrwcikz.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gtbdlsvzzi.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtemccsruf.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtjtxygqvd.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtkgzuxkxs.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtjmowpczs.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtjpflbfbn.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtrgzarfxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtvrjvozlm.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtwqmtpjbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfntbsehn.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtmchwnttr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtxnxddqsq.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtpuvnrlkj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtcgafcpmw.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtfpuhlsse.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtebfciwga.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtryzggyfa.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gththbkqpt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvblfpgea.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtpjrkxoul.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtecdcguxi.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtggzcmozt.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gttxmpjaae.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtbewfojjn.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtizxmktcf.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtketuxtrf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthufharlf.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtjbiuddbw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gttdctpeqn.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtwplemwxs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtsgvrthje.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtmxktjzwg.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtlrhaumbq.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtyktpzgbq.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtexhgkwsa.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtnvujvcgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtnysvsctt.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtnfqbfyds.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlsijpbr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqaafaysd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqunxnubs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnjhsicii.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuguymix.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtbdondcxy.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpyfrzvfy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gttzrwyofr.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtqyjwtduw.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtcjzjwwfa.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtxmqqvoky.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtprxjjiyy.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtyddkbmmo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfbaqryy.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtgcivalqg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtkdnkrbeo.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidozglky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqoveoint.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtwirspjog.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtxcfzqwcb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtvwuuawze.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gttlhycwmq.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwqrpsvc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnobcygyv.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtoehvxmwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtvaliwukg.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtlgwteevb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtpytqeiea.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtkbquuprd.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtqvpslngz.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtpdywpttv.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtsxwhicvk.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtdbspzcny.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtpwmqytxr.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gtfzbixtiq.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtotvqclad.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtcvqyzqen.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtgpighniq.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtcukjqdyr.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtfgzriyfh.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtqkcvunyq.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtvhjklrlr.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gtgzupcgmd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtjzrulvjg.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtcdjhstqj.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtizeoncln.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gthbirxuqt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtlbnrwjan.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtejcccjti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gtddaqybwr.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtkuaskeml.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtajymlmal.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtcclavidc.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtkhevwoen.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtcpiefvkw.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtgpxihhsi.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtqdfiavrp.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtrnutjmxz.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtblwcjspm.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljtuwvsi.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gthrrkdzyb.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtqzrtrvor.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtlfsqbglm.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtzcwpgkor.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtiejbjaet.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtqunhqroz.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtxrvjacfd.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtfnwnugpa.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtwpjciryd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtiycgngpi.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gttdhkijqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtuamjulda.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtcbeaomix.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gtphlpewsl.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtlkqwmyby.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtbibosnuy.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtretuqyhd.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtahllsxcr.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgsqxemr.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtltyivuld.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtrmdwaffu.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gthhvtevip.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtrhzelcpd.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtphsustmm.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtichbcfll.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gteuxermjd.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtjsrbjwpy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtjuqnuidd.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtbrxuxgvs.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtyfsqscxy.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtehoonqng.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrxuyqmiq.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtfxounfch.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtlolnqsji.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtpvbksgmj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtxhzisuqo.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtixmzkofo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtjirrpxpw.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gtdyvkqzhq.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtbueujxik.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtmldmoqtp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtfzhbfafq.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtgmmdhkwi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtbqjmotgf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgeoeoins.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtbostubbh.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtnwfuzgbs.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtzfpfzivl.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gthytvqiar.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gthszlbfhb.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtwrzbqhrw.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtgrtulhnt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtrfboqyxt.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtlaywaogi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvuszela.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtuwvlnbqp.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtiznuojdh.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtdemwbogq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtgwuqdhmc.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtbtzvugqr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtqguhupwy.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gttqbimscb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtbicsjioz.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtnpweotjd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtabmyistz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrklzpwak.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtwxrgezig.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbnaszjqs.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtxxcqdlco.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtzaqlsshe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmixmgybm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtkjfrolyp.html


<!-- 参考信息 -->