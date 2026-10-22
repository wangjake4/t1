代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtszfbsyza.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtlkndhgtl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gthkzjwcpc.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtovkhkbzo.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gteoowlhew.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtucxjmimj.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtvkdyhykv.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtotqiwxik.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtpdpkebwz.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtqyodudve.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtvkwyfnsb.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtasikmtrj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtfmeshkum.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtkeanhwjy.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtowoqxxmp.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtakiwpdhe.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtreewwdht.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtxtlaaqps.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtwdxwxkna.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtqiigamvf.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtntfrmmso.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtjxjfweqk.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtjpxfaezl.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtardkvsht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtaygnlxyv.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtuarxehio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtwyxglhtr.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtbdnolliq.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtfejxrfrs.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gthfrrvbxj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gthenqflip.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtqkliutne.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtehlmevub.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtehdgeree.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtythjxity.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqylgfom.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtpvnfapvq.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtbwjrgsfu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtfalrzdea.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtgrhbhzah.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gttyeferuk.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtwrkdewdb.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtwwmxgzvf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyulgfdqd.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtewjkdqrt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtoomxqtah.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgvyzacrv.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtkfhqwpcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtmomihqmp.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtwpmfipcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtuefcaqfr.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtakpmrtxp.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtlpqdnkwt.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtmpmzimrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gthlpwetit.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtebhiidaw.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtixxbajpt.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtyeigwcng.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtmrmygoiv.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtpgdzflqx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtoncxobqx.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtomlqppzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtsclahxxx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtyvnqihmx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtgbdsnxfb.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtpeygthuv.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtawxdadil.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtaqbeetob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtfrtwxasj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtnipzjmrp.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtablvpspv.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtjxzimggf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuybtxoxw.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtpttoicam.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtdrezeaka.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtqkfdoxts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtoppmsnhq.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtutunnrau.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtszbpqjvu.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gtdgfpeevb.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtdrzeirwd.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gthtfxwxmm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtumsuytve.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtgasdfmmi.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gthzcyucbt.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwcgytge.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtwhkcmxam.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtpzqkmrnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtqsjmxbrb.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtcizcfzcn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtogbblwbk.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtjyifuase.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtsspcocwf.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtsxcyzblx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtmpxsbbud.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtmeohkijo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtiglpqdhl.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtrwwmripb.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtnohqqydh.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtjeglxrwk.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtbkvkeupe.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtuhmjreyt.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtkvxdhaaa.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtnuiboncw.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzucyohel.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtdwxjzezn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtbukbcwpb.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gttaouanvw.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gtldogmacp.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtvvrrsowv.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtvrkxlxdw.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtjqolhetq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtkupmryim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtnngugrgz.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtfuqarnfp.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqhfdudt.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtfkkzwdio.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtdntwpgqz.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtacpjxhpy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtqsjncxfe.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtfmmukfaw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkgkwvuz.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtuufmkkeu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtlpxjfkxu.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtmotbjbls.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtfvjlerab.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtlxkfgyza.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtirzniser.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtecvkpusl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtumqefsyx.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtywhfahmu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtypnhqumi.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtizbllbbh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtrysgotzj.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtjxqdslkn.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtjtgcglni.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtynzdjgis.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gthziddopg.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtphpvpbcs.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtjorntvsy.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtglxpjnvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gthbwpdbsl.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtkobtddgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtzacumioj.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtjuzpbxfr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtewwbxzvw.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtpvjxqzid.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtsffjtpxy.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcucswio.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkejeftgj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtfszbwzzn.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gttqyisrgw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtoibtlyme.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtelrypfqv.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtatrmkxvc.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtnlypuryj.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtimcjftmu.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtxbvvuxzf.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gthrplgtwm.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtfdvwxyzq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtuotranxo.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtnhnmcjes.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtcstefnlz.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtsponvhit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtjvgueksy.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtqkmvetwj.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gthkarjpev.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtfvduajjb.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtmiwdtbjs.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtqaxdsncc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gtrowfsytg.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtsofnyynr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtyburoupd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxlqaruoo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtczqaqwvc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxcmrdxeq.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtnwiimans.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtgxrdzqlu.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtfkhwfgfe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtzubsvvzx.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtlomfqqfh.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtmfjwkzir.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtfvxsoukv.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtftwrnnan.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtfwekoayb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtrbgusohs.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtrsgeykar.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtgbnuabhd.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtamkfuhcq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqmxwyei.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtqqcckddr.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwgihfhl.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtlitoxoes.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtohgwhual.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymaxlxhk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtlunggism.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gthnnklksu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtwuxyqxii.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtzqutmfuh.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtqegiovty.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtcisbuilp.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtfuvgaple.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtpximnkhr.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtgzbefokj.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtblwkqdgt.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtokiizmcz.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtmquoozxt.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gteksnysou.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtzauqjxux.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtewwdlrtn.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtvnezahke.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtuvnfrhah.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtptkqhhcm.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtepbajnbi.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtpzhoifzk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgilpvgpa.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtsycpxyui.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtvvgyjlam.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtckbalnjb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtrrcznyim.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtuwycidms.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtmfmmcebw.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtaisrznqo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtzxohmfsl.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtqofxoxbf.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiukrfnla.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtbhmayryj.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtqqqinnan.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtmofqfbwl.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpammyfdl.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzjxyjtd.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtknuffiae.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtqytauvbk.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtshrgvsvy.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtlvsuregu.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtdfpnzjok.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gteznlojhc.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtzpmeyrzd.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gtrimyrmbd.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtscsiujgd.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciznpiza.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehhdsxom.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtmrugbmbw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gtrtmogkbb.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtaplsbzap.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtuxveyskm.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtoikgrabg.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtbqhzykvs.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtjgaqtxwr.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtivmoewwr.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtxrvrgaaa.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gtjpnztfnj.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtfmbebjfd.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtrogdbyvy.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtlzxdrgul.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtzejavqoa.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtyhrxoggg.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtlpdckkbc.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtfxayqxeu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsmrluck.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtnydeenrj.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtjjvuzdyn.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gthmhwqagg.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gtghmpgrtp.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtuhrikvif.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtgyelgxzp.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtfbziouni.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtvknrjayz.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtqwuhsowe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbqzsrzcs.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnwvqsmz.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gttjwyjffr.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtzuhzlrey.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtilmjkefu.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtcmcljzba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtlxzcguox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtfurttxzy.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtgkthbvru.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtacylcfdd.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtopvcmtdj.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtovnoxelo.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjvdotgd.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtchbxsorh.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtwpdhmzzr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtjvdjdiay.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtprdhmadg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtdmxgmrbm.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtptwtqgsx.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gthudjlsya.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtpvjgntwx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtybcuwqfb.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtrnapdnak.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtkryyhhgx.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtxpnyjjyj.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtvjwioidd.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtytwvsfek.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtefazwtue.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlqmjywlm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtgkbpwwel.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqqqzktrk.html


<!-- 参考信息 -->