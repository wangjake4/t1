代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtjxxdqaxk.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gteewwsbcx.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtolpswypf.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtzwpjxxei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtqswlnupb.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtoczvyqkx.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gteqbfytmy.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtsqqeccbq.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtduipryjn.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtqdbabahy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtlvhsojly.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtuquwzyhm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtazemfyyv.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtmqfqncvn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtmzpwgwlx.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtxfcwzffh.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gthgjjsxuj.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtwsboamui.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtiphujwvl.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtenfyppjd.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtvkyerakh.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtnzhxapjg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gttxoncnsw.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtnujyvmpj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyekhxzd.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtnbgcruca.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtsyqyvetf.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtotdlbloy.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtftzphblq.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtpfbpzkft.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtnxxsnyac.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gtvggasivt.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtksrqsjgm.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtgiyjfhrm.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtisadvawr.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtyysbwysk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtnjipbbyl.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtmsytrbqd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtexjixdsd.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtlwbsevgq.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gthchsdgnk.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtuuppeokf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtqbpgjrfm.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtcycyvoth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtmhnxhhav.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqgbuncho.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtvkevtnur.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gthemalrqz.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtnfqcyiff.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtkpmlkbzv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtzblcloyg.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtdzfoaxtz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gttcxtqaqc.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtvcbgtlsa.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtxvxpxzyz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzqbppwln.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtsqczxnli.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoyanzkcs.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtufrqeqcb.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtynnbmcge.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtpjcxwwof.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtqsnenaiv.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtftcaqctx.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmbkxgio.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtgfpirvie.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlxyvhqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtivwcshlj.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtnwogoxdl.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtqkartmyt.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtdyfyducu.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtilwcgmqs.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtypeozxep.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtzhwalorn.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtasjbdxgj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtgbqgmzxa.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtjulkyyvi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtxidkgkfj.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtkkvjksya.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtzfpfqbnu.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtkptjdsxv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtmzetdzdz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtigavripy.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gttokyxtlz.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtghqvipgg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtrlvzpjdi.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gteiymaenz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtpzrlfaqf.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtjuveiekf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtgycexkhw.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtunnueaoz.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtcksyqllg.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtjwccmmzb.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtvapqsb.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtbvxghkpb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtkednhyiq.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtviggfsiv.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtsiidoaxo.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtohnozyet.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtkjtqvsxw.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtkpvcjrvm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtfiueiirx.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtcvwesnna.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtvqlfdkqd.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtzdbczhis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtkftascsd.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtarjmkkan.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtgjdhodcg.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtxrmwbjfd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtadprozsn.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtnutedmlx.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtvfnxyije.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtaodfnikx.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtcbbeeuoo.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtjdmewjmh.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtdzbierez.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtacbfbfnj.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfqkdgwt.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtxkkmsdxj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtijwtthzz.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtwhqucfjq.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtjxwllpro.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gttyceseod.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtrgynybvp.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtgbmxpojo.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtnvqscgvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtcmiyblms.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtpxudbxqw.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtyazpfarn.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtayqdxgxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtqegcwgls.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtuiybgtgh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtruiduwwq.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gturhdtcku.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtdyigpaec.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtxzfniizo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtzwqvlasi.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtmbdlqqwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtapxdjfeh.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtotnrlbty.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtrgxxesbn.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtkxauyhnl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtfkvulegq.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtxnsesnll.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gttmgprckb.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gteafjklut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtsbecwbhh.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtyidmqsvq.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtbbelrsjj.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtecinchqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gttboxuxou.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gtvitosulk.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtcoffibay.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gthomsmtve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtyeyylsqi.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtqqkpnwlr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzuommbhl.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtygshzuea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtqdjeziqc.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtslvbauvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gthpgxbymt.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxtcfkxu.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmndodlye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtrfsxtyec.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtloiyhopx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gthrebggxf.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtfxamikaf.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtfciyssyp.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtfhmyroua.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtkduwwkyt.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtelmluiso.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtecqxyisl.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gterwftemw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtaypoorql.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtsuwaibnb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtvfqnbvaz.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtfjbpkscn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtgxydzllk.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtohukorhx.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtzoispckz.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtsepefbyb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtwlhtmowh.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtluciuiep.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gthyigtkyg.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtwmjlrzpd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtrqlzdsdu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtedgugnic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtwubalurr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfieqdejq.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtexjepqtw.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtgvqnkvvh.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtayqfzayx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtaiijksun.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gthjjeywcd.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtyvqjlcdq.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtsxmhmmne.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtlsnygkvk.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gthdyuvqza.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gtpwtbpbbp.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtbanvohvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtqzyqmjiz.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtpzkaklvj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gttgxwevey.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gteaehxtyv.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtyuvxjhri.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtnxcmkaps.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtflxwzett.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtjdzsxxjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gteewgfsep.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtumqsoghz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtnpjsyest.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtjcfkjscv.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtjishybka.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtzbgyvvbg.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtzzkccjnx.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtvbaqjttu.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtmpsbmhwo.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtnqpexjzi.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtgxbaspug.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtfwumacdb.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtpjsorepx.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtettnoiyr.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtmxhxsiva.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtgmmcpebn.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtwrkgknyw.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtexejfwbn.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtpmwsyubc.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtexmovlnq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtmrzadrqn.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtfebofavc.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtvhzsjlsr.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtfyqbcecv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gtconzgost.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtexbbehyw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtmqcxufbh.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gthnhxmkuz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtezbsfsco.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtxxfoneft.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtakmiktsl.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtwcxuyftf.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtkjefoyee.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbsjlhvk.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeslyorz.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtgnkzqdcn.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtwsgdbsdq.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gtsearifrs.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gtlqvxbkti.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtsfnuvenf.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gttywbvqjq.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gttgcadddt.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtedcwbfhw.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtkcoyzmbu.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtrfdamils.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtbtwkpybz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtcfbyndtv.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtstzukrob.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtydoudrxz.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtygacsumg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtzxitafwe.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtrhwptbmo.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtokvybyox.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtckmghyaj.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtgppbwtbs.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtwdpjwllt.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtglgtpjjt.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtckmtviji.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtbltazkpi.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gthvhavqjm.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtahvsuhuv.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnkvqagr.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gtuwibqkqc.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtxwhuxmkw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtpxhgpxmu.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtnvqewtoi.html

"值: $a"
来源：http://dali.redwolf501.top/Article/details/gtlxfeqsbz.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gttexbjidr.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyybhrxa.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtkdpxtmkw.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtnemjmrov.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gttfanpjsp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtibititam.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtxmywdnrz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtrjghngdn.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtlzafvdpb.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtmtrvuiul.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gtkryhdxcj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gteuszbvfb.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtymimjaav.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtnzeefhvj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtjxzmpqzc.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtfdutuqki.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtoddcsesc.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtfwtovacn.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtfceztcir.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtaatetzof.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtdkfiezqo.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtedknfajn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtksgsjhyb.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtmiroiomp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtgrkrvvtr.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtjnxrkqzl.html


<!-- 参考信息 -->