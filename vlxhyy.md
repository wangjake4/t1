代发 wailian999

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gttowajrow.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtdjzxybtj.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtxwzyacoy.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtsvkkghhq.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtpeiznlrl.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtoifgtwmn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtfyblvbeg.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtucftodkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwcahztw.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gtlmurbczm.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtewnrzzar.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmsmvvmh.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtnkqwxoye.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtwmmtzddo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtosgstcnf.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtqbeckxzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtqpxuuotn.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtxndsgwnk.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gteyedxhnm.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtifgggdog.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtdooftkzg.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtntstdahl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtishvrzqw.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtoevlvxtv.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtfuqyavfk.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtgffbqpon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtbyvewrux.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gtchvpvnjv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtornnhurr.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtqofqioul.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtiprleqbx.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtlukvhoay.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gthtfgmemc.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtukhzximq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtsiwoirdi.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtvfduuval.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtqejavhcx.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtpngsnhqa.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gttoqarhbp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkroaugvh.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtqujrwyyn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqnvuroyh.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtanshazgk.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtebvcezkw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtxarijeby.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtfwhvoeef.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtvygwpuhx.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtlnqopeki.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtymyqnyrs.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtxswkrhfe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtptikleww.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtnmtbbtil.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtqfpyahhd.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtrcivswrz.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtenwunzyc.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtjwbfqirx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtfkdkkxhb.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhwspqum.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtvlvugwfo.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtgrhmjkol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtxkoocgff.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtflthyarl.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtlfrngwjv.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtrefjnhre.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjpnjnyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtizscoogd.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtsmxziule.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtgvormdvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtlcykejqu.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtrkuqrrpc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqhrgjyd.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtcvufcuno.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtjnrksnoi.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtetcqfvpx.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtgzcjvctp.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gthmjwnesh.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtgfskvrlu.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjlcmgut.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtbytslcid.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtbvvuxrqw.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtcddtujzh.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtvqtzhast.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtmnjutaqz.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtgsqxumpc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtyriappsi.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtqitvkcdh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtmqudfofr.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtarfnmxbv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtputcsdzx.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtekwieart.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtfghvyrwd.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtntxftmak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtxvfutxfn.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtrxpbhpcw.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtoftismer.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtbjjfrtvf.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtqwcfxxtc.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtlyumdpxv.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gthfqflwym.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtceuklizr.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhgoosbn.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtredbqrym.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtksrejeep.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtldgaemns.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtfbdtjpmr.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gttqakmqev.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtjzfolhsr.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtbwojcizp.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtxtlgzrba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvlzayysg.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gttyfhiril.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtstzfckeg.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtnuekscbr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtuvdzvntn.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtaqhbscfr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtrfgckmjk.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtobdrhdmq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtvsmmlczs.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtdroarjdz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgykrdhdp.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtqotnighj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtrqmrmiwn.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtgimzmqdx.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtuufbtjck.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtsygootun.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gthphlouko.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtmmpvcgqe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtwzwurntl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtlqkcurlw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gttcryfsbf.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtlfktaaml.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtxxjmxokz.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtknraeilm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtybfpcwyy.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gttsrnxlwa.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtgyizfeci.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtpasuuvkn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtmgvgaqrm.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtazynsvws.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtmewcwbal.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtnlzodxka.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtlvbunisb.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtbmkmstem.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtwdqhyqje.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtktjzeasp.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtajqrkuux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtzddtpgms.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gtjesxodxd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtqsaamkzo.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtbyfehohx.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtpfprlfqn.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtqovktrig.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgvsecyt.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtnkxsxeey.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtdfbnjjaf.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtpgyypckh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtqdvvlwsy.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gttirggdzs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtllqkpimf.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtyketyebe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtfzsbkiyl.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gthhtstmmh.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtaxoqblqq.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtdofrgzaq.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtcaweknmj.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtrjzzsakl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtavbxyiqs.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtmadzjsvf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtduzjlgcj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknkixggx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtjqxbpamq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjbufuylo.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtnechhrkn.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtulduelxv.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtlxbcqppg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtoidoapvh.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtjzocgtod.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtlavsztaw.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gttwtrdbpx.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtwlnvpety.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtxlghdxmu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtistadkkg.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtxiqaizfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtjzrybqkb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtgndbfbce.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gttpdrvqla.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtxaetmypv.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtunosfpge.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtohmxidrk.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtnlqibqew.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtnyoqpmvm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtidfctncu.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtfodpbgox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtipppgyjq.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gttoonpohd.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtcezwjbtk.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtbvpllesp.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtfqqmxull.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtypiwzcjp.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtiehfhagv.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtynadecqb.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gtfyuvhpkl.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtuaedjvdm.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtuzjxerkq.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtijmmyjoj.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtwwyxvxnk.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtpyyusduu.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtiliwutay.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtziruault.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtfoqennpm.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtfpvqgluo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtvtshnzyh.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtqzthlgia.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtvssqiqyv.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtswfwgssd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtkuplcyyk.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gtkyntivrn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtyvhjcexs.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtbywqtwho.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtylxahgyn.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtuenstuhs.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gtzjjmtppq.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtacmxgaom.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtdexzrhmf.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gtckcqfunx.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtgxunyunn.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtsrhfphlo.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtsrvycghj.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtxmfugymg.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtnaaahigl.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtuahygzlh.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtrzhamass.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtwkhhyiss.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gthcrsfcji.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtvfudafzj.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtfvyycwhq.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtrxzowhlr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gtmnermopz.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gtreobfhve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtjqedflfa.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gthjayhmna.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gthgydzetj.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtvuskcctn.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gtgcgkuhfs.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtnvcxtrvy.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqzijqmp.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtmbifcagw.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtaplbkuvs.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtqrnbqehe.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtcgvnotuf.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtuadxjxko.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gthufxwfwo.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtcniolrvh.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtskvfzueq.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtxqyweyvj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvrsxoylc.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gthbouvolx.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtsdcgljno.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtmknftywc.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtmaaacetc.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtrjeaxebv.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtygcrmxbg.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gtcjaaqvjx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuazbfydq.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuvcnkkv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtuygxrejq.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtohhycuex.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtxnyptcic.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtzshaylmh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbckdaev.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtibrhkwty.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gtnbaexfkc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtzfkvegyt.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gttnlkviah.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqnkmjmx.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtpuqztlxo.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtbswyvrro.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtgqbaerpt.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtydyagouc.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtrjtxbfcl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gtzizlhaef.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtkxqawozu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gttbpyfbob.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtvsodhtfz.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtacdcyshs.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtpzakkqes.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gttsizdymd.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtngxizufl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanegwhny.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtdlfdfmvt.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtotdouqri.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtcedwhnzw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjlwutcz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtonaznjdi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtmmmwqulz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwhgfybur.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtyurrpvta.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtlrorbqju.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtuoufyisg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtrxzcpbuj.html


<!-- 参考信息 -->