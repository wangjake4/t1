代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2rdkntjtc.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfldpcxj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2usanfley.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2unbynnhl.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gt2ueuusplh.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2zdvbrmho.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gt2nsffquoo.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2lpspkuqq.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gt2udhfzgdp.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2qdeurayu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gt2nuvutzlq.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxdkoxhu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2oetawucn.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gt2ogsrnpjg.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gt2lnteuouv.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waieksrz.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2wnvymkai.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gt2zqidpvbx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2klwxleln.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2qldoenhy.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2qatbmdoq.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2wjpgmhfe.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2xkgcjyal.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2vqqhpgif.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gt2arututfu.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gt2avbyygnn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uudnuvwm.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2wkbyodvc.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2lmzocpxq.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2eajbxvsv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gt2thnokxsy.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qecnbize.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2nqyxdvwc.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2sighcljd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2qdidoahs.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gt2zkszlbhq.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2yophssuo.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2tcfkyari.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2jzsczrnw.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gt2upigjhvw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzzbwgya.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gt2odvqyssq.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gt2psykdyxp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2tpcbzajb.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gt2bicftkws.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vuxhawpc.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2toodkzcu.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gt2pxelddhm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gt2eggpimyv.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2oqivdjqu.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2wrxyugih.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2oxmosorh.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gt2htyordmm.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2ozodmzaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2centzuxi.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2forpncsb.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2qzujphdt.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2feuxzkyn.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2ztdchsvd.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2nlavorit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2vppcolaf.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2jpjqnniz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gt2ktmpunal.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2qjxqwgfa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gt2frqyamps.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2itwkbbvw.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gt2hjnwlqju.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zwsvopce.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2fkssvahk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2jzewjxwc.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2wcbrvsax.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2lcobqfdi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2yxolemlw.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojizfcwi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2ebnqnuft.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2xjefyjen.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2wyphbisl.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2evhzhpky.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2zppuorna.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gt2kormpqci.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2dsujngjb.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2qhiwwlzw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2knhcyafk.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2nbrdwscq.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gt2wkuzvcxg.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wecwxfld.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqejscpq.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gt2vsafoykh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2rhyeypgm.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gt2jpaheyqu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2yorooktw.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gt2vqsmhxta.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gt2wjtzuzjk.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2hqrflppf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2yaoipsxz.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2iinasszs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2wsmybrkd.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2xstfcxnh.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2oycfymug.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gt2lehwwhtb.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2apsvsxjz.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2qpbkhyfd.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2ndvdzdiq.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gt2fyiarrak.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gt2ahxghrid.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwqrumxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2mzfmkeit.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrcwmedq.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2ucxpwtja.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2qvipxjcl.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2rdvwyhgg.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2qbxeduiz.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gt2zpidrbtx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2gnvudpfe.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gt2tmojwqha.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2qfptztro.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2aaskuzvm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2opmsujyv.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gt2zgrmnocm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2saopnanx.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gt2tiwstrjy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2bmhowgxk.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2gokyfabe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2mppmofmc.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2cldsbkfz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gt2fiprdzcu.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2bptvwngz.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2ndqaoxiy.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2xbfapwvi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gt2ajdnborr.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gt2wdntqbqp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2ogdapocx.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2nenicrke.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gt2dlczdnsh.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gt2forndboj.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gt2fzjilbbm.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gt2fttamngm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2qezaqgxz.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkpcwfkr.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gt2yydfxbyb.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gt2enutnpsy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gt2qmkppvyb.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2ghxehegp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gt2llgimxmj.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2eiwkhcdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pcufwsmu.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2fuuwcema.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2qhqluenr.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2svuriprl.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2efzrmvvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkzusdqv.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2woirvfrx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2mvimubin.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2uyzctfpg.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2imboytzo.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gt2lifdsgwz.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pomqqqcf.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2ffbvlcgx.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2hnsavoxy.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2vvmeclbk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2suvapwph.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gt2ddqhhqnn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2yrwofgse.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gt2uanqouvf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2dcfrcfox.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2ndisianp.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2agmhvnzi.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2jodbhvbm.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gt2jihiyddy.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syevtgzz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2fbwvfuby.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2gzrxlajk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2zpaghjyj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmpaooqr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2tpqycybz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2iyjfrkti.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2dfsztqjc.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2unhzvaol.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2qfcnlxwx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2gjsunckw.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2rncvkmqw.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghuiokuo.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gt2lgfwwerf.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2mcgwsksy.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gt2dhjccjht.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2dakijjaq.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2mckzwjog.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2hpbjwkoa.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2bwjavweh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2lffwcwkw.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlktgefc.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2qxenidej.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qewastut.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gt2ehcbacem.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2zjcdjybg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gt2xtkppmzo.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2ttiukhxh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gt2iwywgfzx.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gt2gxrldavc.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2icodcwjq.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2zbhgongy.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2iwxhurzm.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmjksyhw.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2lokldqco.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrdolwfm.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2quqnvqvh.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2dmoatavj.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkpwknsr.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gt2hrnvqwms.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2dqfjjnqw.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2uvbpjscg.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2lcnmtpdw.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2hhjiqxwb.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpatrahp.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmmhrhow.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gt2qflqktfq.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2qwyvrqgn.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gt2mbsduluq.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgsejksx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gt2xfbefikc.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2iyvzubtx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2poikigfz.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gt2jdrpdcui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubwumbse.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2swnreaaj.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2slrkbvyl.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2xivqnebc.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gt2vevevbru.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2yubidbgi.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2jxwujkah.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gt2pmphrwpj.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmprhhxe.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2ffkdwzrk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovayrha.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2bosrqwwz.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gt2hpcywtye.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2ccbhbnsq.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2xqfipjlh.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gt2rzbcgjos.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2xzgwtvxx.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gt2xxpvmqqb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnslwivz.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gt2opymgtxi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gt2xdlvywey.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gt2dglqapuk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2iyaesyid.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbcmeejx.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crhjdxzy.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwxnapgm.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2huxfduax.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xixrvnqu.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoujcvvu.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2ycaydyye.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gt2gophmdbw.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gt2gxpjgdtj.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2sefjoerc.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2jcnpscve.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2xttdhyol.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gt2jegfvwhi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2viwqicgx.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2rhojbnws.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gt2awsleexy.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gt2bmttjcrx.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gt2bvqjsmof.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gt2egteovtk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iorabpnb.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gt2dynhscia.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ilwczjfh.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2esavwtyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2udmutlsl.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2vxcubvqd.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gt2tscrwlpo.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gt2lpihshdf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2hwbbnzdk.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2kfkbtstw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxotwsk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2ropbwiee.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2kehbizof.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2qobcxvrd.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gt2oajabzdp.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gt2uqqcwqsn.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2iawsecjz.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2vealskvu.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cudnjzhp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2imibkbyb.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gt2gehujjsl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwzddxt.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gt2ennptkuw.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2ntjpwqrj.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2btwtxkbw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2qtqttuqw.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gt2msnebbxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2qhkywdhj.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gt2jwobcamp.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2juwojesn.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2iddjgozz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2dylejhsv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lxrrivnc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2cdkwxbgb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vqeelnla.html


<!-- 参考信息 -->