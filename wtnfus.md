代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtmwbjofnx.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtvukrqrjw.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtkhdprsos.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtrdsrywem.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gttftckjhv.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtqbtfybbh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtuvamdbrb.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtgbaowhvb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtlogacqco.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtivywrbel.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtrsvbbewf.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gteyihjztu.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtfccxkiqy.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaevtjpci.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtycjdjiiy.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gthenccoda.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtudxtgpwj.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtnaffrqqo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtwppajozp.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtcnouuocb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtonxnjytt.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtgfhwrucu.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtxkuxqvre.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtwwgzmgbq.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gthvdwfake.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtdeshzfis.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gteizihqcx.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtybcnsrdj.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtymtxgevs.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtybwzepla.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtxfuchlug.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtkhhqdpzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtdahidzup.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtrhsoetos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtjxgdmybc.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtoucqiplv.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtijpudnqo.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtczmtjsuf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtlmxriits.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gthzitrozp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsmkdnfz.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtopgxurov.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtvddcvbww.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gttuagigad.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtkzcamxwz.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gteaumczko.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtejcjfsak.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtffplayxg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtxmijksmw.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtfqmvqcdu.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtprjpogqn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzpeorvtw.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtwnpgyafe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtasrztmes.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtvfhiokpp.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtnjnlldrc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtocpxstyx.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gthanktfzy.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtjhryacyd.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtinklfaus.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtutnbabbl.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtucirmxvz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtfpxdzsxt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtpteoixgh.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsapbkqyz.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtkswflhqa.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gtyrmhivma.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtculukpgu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtnkuzjfbz.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbzkwjwq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtvxwiwtuc.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtdwdvpkqn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtvtayiten.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtfthsmucv.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbosvqtw.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gttlstxugp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtwkqtfhsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtuxlrzcrq.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsucyboau.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtqdzsvmnl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtugnotmgz.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtyuwebcyt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtozzbgffd.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtdwlxuizg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtwdagnjrg.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbkwxwws.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gthbjdosxj.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtgqjrefec.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtoerdlcho.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtehlooiyw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmzamwss.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtspojgmca.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtagmmokiq.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gttppxhuqg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtcvscdnlj.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtitqyfnvg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaqkuzke.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtbwzxzehk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtplxcxdgm.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtautwjybj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtosksqkpn.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtcowfjlno.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtywyoarho.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gttnbiexsv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtzkrrdwzw.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtxzovkiht.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtsoxijmue.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtxtwnyvfu.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtwgrietht.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtalfwwotr.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtmskdioyt.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtmgpgbiev.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtulxbwuzx.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtliguayif.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtjilszfxr.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gthpuwzjyz.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gtepgnhyif.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gteuoldjuw.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrzqvnfx.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtphctdzhu.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtxyerqnfz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtrvokddjg.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gthmuckzur.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtirmyscpb.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtnqjlxrly.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtfwiaecwm.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtxnaqukzm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcmtzipkc.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtjarapfzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtnewewzrf.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtjzxiltgs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtfjpxgixe.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtujlyzysm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtrebisftt.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gtftlbpqkt.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtodncbtdt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtpqqkmkdt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtammbrttd.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gthuhrpgth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtqodpdrni.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtvdzywhis.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtowejitxz.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtoyjmhtmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtvfipfqqy.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtgexkfgus.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtputafpfx.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtfegsgmum.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtppyijoon.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtipwvrfeh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtexemontm.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtfrpfcoxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcvefxuml.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtnpntfxry.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtzzfbugsl.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtrzwxonde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtxofjeadr.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkwsojcv.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtoafxevpc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtnryenqld.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcjyefue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtgwpbdfit.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtssjdqvpz.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtooohnfdg.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtxpwciwyg.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtuwxbaaah.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gteamwknds.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtlsasvgwa.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtifwxnisk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtacbrksae.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtgoghuwxj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gthlszoqtd.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gtmwrtcuql.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtsbzvaqzc.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtbdanzavo.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtofvtxhhj.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtqwqhabpx.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtfcewscyn.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtqigtjzgu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtarhtguah.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtubpugfrg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gthpqwnnng.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqxjjmyng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtdeaxpbwg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnqywprjc.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtvgradbdk.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtslrdhdpz.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtvhqpdepn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtqavmkvcl.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtmzcjccrj.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtkcguyfxr.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtbyooxyhc.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtyregykqs.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gtflckklql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjggmmkhn.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gttkfagwni.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtaiyuxyks.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtheeyvdbc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtumnyopjh.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtpnhwkyfm.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtxvauvujo.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtkpuiipgl.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtwrgrynmr.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtymaqpuly.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtvmdhbehi.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtjuuzbvzc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtgngctqsp.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtuhajjphy.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtavqkidil.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtakczxhxt.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjtjzyhq.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtljpvnjyr.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtgdtokrrb.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtvuxlqfcs.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtssrkyeip.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtzyekcywj.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtfgoolmoo.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtavzrjgai.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtqjnssbxt.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gthdpblzyx.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtftftsynf.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gteskdaoyn.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtarhaepzt.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtvqcrhufi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtrxctdujs.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtxcmcqvfc.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcphxvkmt.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomjqcmmc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtuikrgyce.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtogmrrtby.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtyfzejtgy.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtmitlpsev.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtiiditksf.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtbpjrancs.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtaukhiiyd.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gtpgqtruis.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtkoobcxuw.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtaonioldt.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtecfpmwpj.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtwdadbdga.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtvycevrya.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gthwjfkyvr.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkostdcw.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtasokwcbc.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtqecxlwfb.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtjbtwiqka.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtsqfsrlqm.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtlqxexrpd.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gteazvqstn.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtmkauyjgo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlznokhjq.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtzwnkllwz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtdewqeurf.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtjxszsrxb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtttatukqm.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtuyfipmqo.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwtqpftb.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtltlmhnkf.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gttlhcwzys.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtzosuoazt.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gttcqjvmvz.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gthjmqahsb.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtjrvawmrb.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtignhmdxi.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gttogbzrmt.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtqlrutfmv.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtbotnawmr.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtyflsfyaw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtzsygyjas.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtbjnbtldp.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gthpyxprnk.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtlijxelnc.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtbeptymfn.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gtoarlxrdt.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtoiyibmmn.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gtgigvxkum.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtietxinbj.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtwffqunnr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtlduehnpv.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtznzykueo.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtxsfdtbsz.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtelwcqagp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtecxalltb.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyzpgvhv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gthbxhltpo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gtmdjpdoxb.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtewivjwbp.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbawplgs.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gtyfpglazs.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtlastdfad.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvfwqgpd.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtaacotljv.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtkooxgymw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtmwxavhqs.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gthxxeuvrh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtbtjzwlbr.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gtmkvyrvao.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gttvuxbxjp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtpkwzisbr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gteyvdjucr.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gtlgwytblb.html


<!-- 参考信息 -->