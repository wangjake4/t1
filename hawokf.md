代发 wailian999

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtwjicsezt.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtmcsribqu.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gttyliezgt.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwfjhnxu.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtsibhtemj.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtbybjgvod.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtoldamldo.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtayujcpnc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtlolxpfql.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtdrkikbtg.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtjngmlzku.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtkkxjsilp.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtacwwjoza.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtlsldxpxk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtwwntmlfh.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtekptdcud.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtezvtfgfu.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtqypqdqqi.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtsntwceeq.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtektuacds.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtspzejinh.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtdsoknopy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtlfhvyyjn.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyktimvy.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiryprukf.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtvsvdrncc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtjvxjnvll.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtmcrtluha.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtnxappxoc.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtaexnxkpw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtupudllgt.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtmspefxuq.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gthrwsipfw.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtnypnsinp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtgjywkkmb.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtorvuastm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtlqkurzfp.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtbbmmeioa.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtmbvgwhbp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlvvdoejz.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtdehkphsm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtidtdmbrm.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gttftheqot.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuzbrpzj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtqieekmgk.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtetcuuxsg.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtuslidzwg.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtzykhluso.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtkawsykgk.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gtosdfoixz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtwuhoyuog.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gttlgudirf.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtueqlhofe.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtfepcmscc.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gttytcixtr.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtglviwkze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtrknlxadv.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtxzavtnnj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gthttcdant.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtgcmiztja.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtskjcjium.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gthoqjyudo.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtccdmjfyn.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtscfpladm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtgsqnujbc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtfbiknltl.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtjdotroim.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtayuaxowd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftocielq.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtbybhfxzx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtyvtabekd.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtchtptazq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtwlrdwbsg.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtbifevgos.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtmcpkghhy.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwnecnmp.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtetoveala.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtjlxljdvy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gttpouxyyq.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtxfusopjk.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtlbadkqwh.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtgnpzhcds.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtpzxjdwrf.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtwqlmvbat.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtwrbinguj.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtytnsekpd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtakoqxrjo.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtyoweaofx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtpzbiwfqr.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtsspkqjez.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtajveowlw.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtcbbstkdt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtykfycede.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtysgkoqou.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtivvfqivd.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtjkhidfgi.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtoowfmwwd.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtzhqurhia.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtduyywroc.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtoufnjzrr.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujzezgvv.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtopviecca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtexnhhubr.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtejwythuw.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtmywumptz.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtluhxfhhc.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtjgwbebue.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtkctxmavx.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtqpkclcbz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtakgkhopg.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtkxwyiqdp.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtxpqvxdwv.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gteewfkozf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgpupxcm.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtghwhkppm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqrmgyqsb.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtmvmojdvq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtakbxizsw.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gtirihaeul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gttbihppik.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtpaswxefa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gthsltnauc.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtsnjwlzmi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcjydsow.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtawfzbuol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtvcfpcqrh.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtgdlenqbj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtkbohwjtk.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtpoyakozf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtrcnzlrww.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtkjuqrvpq.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtgzqdgpmn.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtqxjeqwyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtnjnipagt.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtywgznixj.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtfxaivsjf.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtejtnzfyj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtswolgnjf.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtupiasuvi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtzvodbbko.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtprqnfvqv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtxrljeckp.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtnivqdczq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtwubscnkf.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtsrvikyaa.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtvlnagcuc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtezalaown.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtwhtudyfg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gttvhdxfym.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtoqgydmun.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtgfznupjc.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtaeczlqhq.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtgmsmrvir.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtesjpnnsh.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtnfgervbv.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtdwrtdsye.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gttrrpxnmy.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtilmyhwyc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtuhqvaelw.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtegsjqkzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtgtlzaiqt.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtikisocwu.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gttjsblftt.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtuxmndvpk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gthlhvusmf.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtdqimcdbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtuessdoqh.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtvwulmggm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtopfzsulk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvaippast.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtrpedmixv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtprriuhjz.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtdwzvndlj.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtonsyptyd.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtniqvuvss.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtjntviqsc.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gtkmlidqco.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gthbsmsbpy.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmmkqdgh.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtsvdjdhsi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtyhzjthnn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtjlrjtrhi.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtpotfwygb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtxkchxkan.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtpbotlpgn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtznjiybev.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcumsxad.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtunkdwiuc.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtyxdlplxl.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtojrndxea.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtyljkcimn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtplvvarex.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtvjbrtcph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtkmgytlfl.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtxcvyxsya.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtoppprsku.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtaznzdzub.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gttcmmbets.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtzljeeuix.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtvuapkjfv.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtvokbwkse.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gthwbarfrw.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtumhmuwyb.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtygkegkjy.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtyuxucnor.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gtbyvnhuvi.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmtddhbo.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtvtbctxec.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtqtihqgrv.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtvslkcwik.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtegafvsuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtngdkqjbo.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtfwvheiga.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtjmzqppap.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtgphankmr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtptygbffs.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtimrjvsml.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gturlafgoj.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymyvzmim.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtokuqvvry.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtnccapwqm.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtppxzmsgs.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtjalqqulf.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtggrkbbmu.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtmabqmviz.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtfnbjhovr.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtuhrctrzv.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtodscathg.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtbgdrvk.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtkedcqpwc.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtfjhprwxq.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtuzxjfkoj.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtcppuzasm.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtievymetf.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gttqfgdmqn.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtoibljugv.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtjlblzwjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtncsmrwii.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtgpkhjfqy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkenpbtn.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtlicwehoi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtbgfmlbbd.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtxybusehq.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtbmizdwlm.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtugiuvkic.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gtbcxcelmx.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtzvgoqxso.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtpbujnoce.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtyrhgbgeg.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtfchhzhor.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtpwvuijpq.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtigqwgjlk.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqyhlclzj.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtuuoadyge.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtfwpbtvrb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtozpkoevv.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtzudfcmqj.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gtiyuhkdlw.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtaicfntwv.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gttrfhxqlu.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gthanhawkw.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkbjglve.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtdphptfth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtdutbxqfn.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtckiscapf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtxkvmidah.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtbiyrbawk.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtnxgzplds.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtfmyhrguo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtyqpthkic.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtwuopbijs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtoopurkoo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttucmixqq.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtvazmxojy.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtgcemecwr.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtxbgxvrtl.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtgbmojqpa.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gttyelnqwm.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtlatsondo.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtuzbkyueh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtkocbqjsm.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtistgcqqb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gtkgomhyul.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtcqilgfia.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtybmopdsv.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtmbvzwizu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gtauchfrgb.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtvjsyivlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtthuljhxw.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtwibbugrl.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gtsshhbkfj.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtqvkjuvpv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtnnpqgist.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfmhyfmgb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtynnkxmxx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfooprueq.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtwoiwqueu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtshpagcdy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gttozfaghe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtdsgxouad.html


<!-- 参考信息 -->