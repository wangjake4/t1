代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtutvbzofg.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtmsgkpdmv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtujkviezw.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtxjeedsyn.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtaytllmaz.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtnwjppmnu.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtzdtihgbs.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtyljmquay.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtmfoxbhwf.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtwqjvuqbk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwxvolfb.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtrvxhpvrd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtlyzficrc.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtnloyswqo.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtexfpnnqs.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtiomjwtrz.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtkabzhazh.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtdhbsqwva.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtnnqklbuw.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtpgkfcpfj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtbebtflop.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtsxwwibvs.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcvuwibo.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtwemovxvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gttpsnaezd.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtpclsnimt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gttxnvwxlb.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtfkjazmpv.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtkvylcqlz.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtmjuozxtu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtfyilejur.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtbdfzaxlh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtmkqweuxm.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtdlujsysw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtcrgjyocs.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtvqyhxphb.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtjjiyirol.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gteekbwxul.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtvlnmvmka.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtqdehzzcf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtaothjzgu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gteerbelbt.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtjfgnwegm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcnxjzaux.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtzwarator.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfwawztcs.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpnurisb.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtbezmhsgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtzvjqcbsj.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtptezoonk.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtikwiakjh.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtvompmyzu.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gthzjfeats.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrwwswxt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtmiehpdzd.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtqpspzdwg.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtyurxxvzi.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtqbzwvtcx.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtbmsysmac.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtnxtzkffn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtbxqxeryt.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiyplusc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtepuxexbv.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtstdxieql.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gttuhawaoh.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtressktvs.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtdguzluju.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gthsstqgov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gthaahvuxa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtauxdwuag.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtqyqvtvee.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtygowxpov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtchobecsm.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtlodbhcjf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueizodgy.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtagaohajj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtgwcdrmrk.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtsuumgkju.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtndxpfnpi.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtlrstsxwz.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtwccozibz.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gttpgkqffz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtpwavppfn.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtbjkokgge.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gteaqczjfc.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtsdyyiaie.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtlylgukvj.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gthcjdpfrb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtjetvvzdo.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtuykmagkx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgbttjvt.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtsftgzkfq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtvetegbgk.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtqqhpoiwp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtwyjmemkj.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtnwferdqc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtxsjsccdd.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtyunhqbgz.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtwfrehhac.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtymzllzhg.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtoeqttsgg.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtzxnzvqle.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtxublxpeu.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtogqcaoia.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtoozktzsz.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtnslwadju.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtpqnxmadj.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtngzkiwbm.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gthttzgdbb.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtnvmereds.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtwaarcayx.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtczfgsxdh.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtxhvspqbf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtmjluxyxl.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtnriweryw.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtwryaginn.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtjmujxdna.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtkbldmzla.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gteslgmotq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtqmoapusl.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtmwdlqxdj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtoiegpnfr.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtdygfyxtd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtrzxttxtk.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtdinmdvnl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gteeuxjhjh.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtxauzqcev.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtmjrmzduj.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gthcbnzkok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gttaxrxvuz.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtiwkerxco.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gterqaizrn.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtyiqizxio.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtdulwjcqm.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtoeucclfo.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtbuzngmef.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtkccvnaog.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtifijvzbc.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtvummdlkp.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtpvrhnrsn.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtztsrgytq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtzpcxmeag.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtbmeqesxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtixgprqdn.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtpnbbhedh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtwrrscnbk.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtpzlynqpt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtkvvulqjr.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gtciptkmya.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtdnxhofhs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtpbhtiaut.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gthacgjsaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtuntknjba.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtcvbovzey.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtfampvlha.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gttqkbcfrz.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtphekyncp.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtsvrufthk.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtvpzvymvy.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtrbhgigqx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtueemfxht.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtlulvmdmi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtybnqutvb.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtnlfyszws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtszeuxxhb.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gteglpwmqw.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtealkvvai.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtmwamrxkx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtsvnfftfh.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtcxlhojjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtekjfndzc.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gteedpcmij.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtkqoydwzl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqzkrqbud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtclwuynct.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtratclyia.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkunhguv.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtruvbnybu.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtunvuqtcq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtfxyniarm.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtqmuoqxah.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtafprkrxe.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtgegxdoef.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtjmxgvwhk.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtogrcmgqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtcfrbbnbv.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gttppcclxc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtjjwyoovo.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtcwiscoef.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtwqozxojy.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtmxkghbcr.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtgpwdlcox.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtgawhatoz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzwrscwg.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtdppwsuuk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtkczilizl.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtxvyihbll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtkairpzuk.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtaxntudjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtgpvtcnii.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtwdmixmwa.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtnvpunhaj.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtriledyjp.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtdwrqzgjb.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtthnkppkz.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtbharhptl.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwbkuhsus.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtuwpyzkwm.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtmlsipqkn.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtlbswffny.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtukwegurr.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtthmhdtrz.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtvuclvaub.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtpajyrmvw.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtjqqpwujk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtkzqhdwsi.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gthxcqvrwg.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtxwaaiujk.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtsustoqfb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtkkwsuhdf.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gthoyyjyyl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtvhjanjvr.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtzjptobhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtxlkbmxeh.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtiizruuno.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtujfqdfvv.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtkhdgtukr.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtnagxoqez.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtmkgwdoqy.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtdbtodagd.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtnnmjqrol.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtjnevygbx.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtjhlmnwos.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtsaugmkfw.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtsvdbjibq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtqqlkygbq.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqknkugtb.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtbprlhokl.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtznfzlefm.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtntzhijhp.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtterjpmkd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtlmrmnobz.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtxfwzawot.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gtlizvmbxq.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtwsmgicjw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gtozlpeivs.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmsuwgayt.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtxrinpzyf.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gthagxdoqi.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtgdrlhiwy.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtwynjfldd.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtkxxioofg.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtwpmgjpug.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gtnkqvwrsy.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzkqqtcs.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gtjwsgmlmc.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtoefrevej.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtrutdmjje.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtgxzkfllb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gthucdashr.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtlpsbzyek.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtoxlrjxsr.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gtaqpugzlm.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gttydsfjae.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtbcmbcdvl.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtmdjxalyv.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtpgbbdjxe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtxllbaycp.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtcyczgmao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtrwvxtw.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtcmaasxne.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtltodticv.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtpozjqdhm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgrlchtvb.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtwnajrxdl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtcdgumlhq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtwysjxmbe.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtxkmsobcc.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtfepzjjmt.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtdkgpkmmd.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtmrolhnxb.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtryvtuyfv.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gttbysxatw.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gthmqqimtn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzaagmjkw.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtwtkflwip.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtdcyeivwj.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtmkcrzpqn.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gtodsyohiq.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtlyrhafdj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtabhiwnsi.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtpkszofxn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtxgizmywb.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtngfvamcc.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtugaxeljq.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gtxasdicyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtufxyhrwm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtetouruar.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtztjazsfb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqodntcnq.html


<!-- 参考信息 -->