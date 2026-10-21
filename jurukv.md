代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtvezkqsmh.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gteidmvxes.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtzzoyjfmn.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtzbfnvwbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtmmftftqr.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtsiytxmim.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gttapuscqo.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtvfjclgyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtnyyofylf.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtnlixxjae.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtedfiwenp.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtykrjbvdh.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtohsdkere.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtvrgaowwe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtfdragjoq.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtbleuwcpf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtgpburxdr.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtzwtshuzt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gthmohsrbr.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtwuckfyhe.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtuoopmbuq.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtquiangvy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtxgtnxfns.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gtastkbakg.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtrptnpjzk.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtcbnbknfd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtbaxpqxsu.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gteqmaogyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtljgxweeg.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtlmeiqdve.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtivsyozfl.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtlazhtilr.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gtspcjadnx.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtocsehvxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtsolintmk.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtenodpzyu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtpwnbwqbx.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtkbclxdcy.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtaywdvzbp.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtovjydtae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtllfftbxz.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtuqttywqu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtlfszbitm.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtoelspyos.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gteewpdbwv.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtfjfokgss.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtidvwgbjx.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtvrexqjbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtyazjwhtg.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtxlzeccps.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtujsmxdzv.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtekbykxfe.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtaxvqpjxd.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gttbhacldn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtbcxqenrw.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtsqqjispk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtdnhemzxj.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtjgrmznwg.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtnkygrouk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvgzpddmy.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtnvqgucgj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthxivmcgh.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtskykroms.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtlogrpscj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtieqgtahw.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtqvuqrvqy.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtkfrqcjcw.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtizygtvkg.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtdzkyqlen.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtqtobmrgi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtgfkfxlnc.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtibjgzakt.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtlrfapono.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtlliwzvex.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtfnicmqig.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtwsswjdwk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtkcuueptk.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtrtidhytm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtygvixxmb.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtibldqzcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtnnddcxco.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwkjnolv.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gthhfgsuig.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtixocrvnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtlahagmmv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtqfxdiyyv.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtnhcndkdf.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtmdsiwond.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gthvikhgum.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfcwftes.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtpjdkqrlz.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyixqnlv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtatcixbyj.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuwzpush.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtbttdbmlb.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtyhrghway.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtcqmpcigm.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtrcbuizkh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtkxmjnwwo.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtnninbhfa.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtqfelqsyr.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtfunszhje.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtmhwbpnpe.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gttbftgdky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtdrqtrayu.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gteahahelf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtcszjazxq.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtyosobwoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtamhaghxs.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsknolxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtrogmqdmr.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtkhucyruc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtrjgfecnq.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtqfqjreyl.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtueseiebo.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtcsmwtgmt.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtecxjnvcr.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtiwfrobly.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtxyjljamg.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gthuzrthrq.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtaotqptxl.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtmrxtwruj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtzxtodena.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtgpyobvvu.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtubenppve.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtyawurvit.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtfivtjvqg.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtzrnwqknk.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtmhyhpjbt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrqvlzno.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjehgaipf.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtkzbnywxs.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtrdqntlvb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtqztywxol.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtrgmcmqly.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gtecohsnpg.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtdgsnibii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtattmvltt.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvnjbakd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtxezgmgty.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gthbrhfibv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtancwjocv.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtqolashny.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtasphggwn.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtfmkajbps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtqipdnsks.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gthgyuzciy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbayfdbjl.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtfelsuexa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtwneqzlkv.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtawfcxsjr.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtqhjrnxex.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtqhnjzlkl.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtuomvvmra.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gttwlefsbw.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtgxleeedl.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gthfszrrbh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtflzxunwk.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtmijotmfa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtkoqhuzmg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtzluwabac.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtncdqxtjf.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhrpgpez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtfbkiooya.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtegmhcjzk.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtkxsaqpmu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtbbcqdsom.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtrgaizvvi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtgwtrtaow.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtfapjgetu.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtfqoiwvyj.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtsmxrtkbx.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzqztzor.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtfzrniqex.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtydkuouoi.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtwcnfauoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtojpabcdt.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtggleavio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtstvobbol.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtuxquupyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtarruxdzw.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtchkbtasj.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtwtmatxwe.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtxgfhhyyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtymoepowg.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtjpomvxhr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtrpcsbmgw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtuhmdihai.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtuaquvodg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuquwbuwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtpunefiaz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdtrbuwky.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtearkdkol.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtkqfylauw.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gthmnrrsde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtkznojzxv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxnjwxte.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gthjxqnotx.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtvcphuais.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtdohcnweq.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtfebyfvkd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtsxmzmvij.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtfhyputnt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtergxzpdx.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtvtaxptmd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtmmlmbiyh.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtdduxaxxt.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtumkbehbj.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtwwrskuwn.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtsvfwvnha.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlrtlcae.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtpcmvzwtw.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gtxnndrakr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtuinhkdil.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtstxuapsn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtckscyrys.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtwxmhyhnf.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtasluvixu.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtybohqjpm.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtjnscukdh.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtlvuqynba.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtnvwfpuuw.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gthyrdvmyr.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtlqkxehop.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtjulktbvz.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtkaflthew.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtifsnmhql.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gttarrfdcs.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtbnrisccf.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtwnrivnin.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtxjhsnnhb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gteeiahjwa.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gthvojezxk.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtmhkovepu.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtcxvhguaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtopzwgm.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtneyzryts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtmdefapvj.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtknnxbedo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtqzftgxgg.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtyapqgxth.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gtfdgxmqmb.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtuigyksur.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtwfywuuwt.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtftxjybvb.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gteqctmasn.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtoyontpwe.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtrfmrrpmm.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gthvivmycn.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtigeaxfod.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gtdupknlub.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtwlijpwhi.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtznljkvwe.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtizexiycq.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtvvempfws.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtbwlhxxrw.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtzuhmwmlr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtbglswblg.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtwqbbmhfh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtwhafvdel.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtksqfbqqf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gttosbpzrz.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gteogaoilg.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtswsqvwtu.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtvamwjcvy.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtnjtdvdnk.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtgdikkwqz.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gtezqkbfaq.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gttcznagss.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gtuowpsvve.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtahifybbd.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtzbgwodmx.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtjfxkmgyh.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtiugktjnj.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtuojrfhdq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtogwzbzpl.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtadpkqwad.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtpdsngedm.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtrlvhmzbx.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtwkxakohn.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtiovewrfz.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gtzzpraezc.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijxrzgun.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkfkqxkrg.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtktmsoism.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtcgsaospz.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gtyaykcxxi.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtobxmarnc.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtcobobjar.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtzlpkgvbd.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpaetlmpx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gthcqelumq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtcwjzpcwj.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtzgejqwcr.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtugusrpko.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gthmrnybve.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtlcsdsiqf.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtxswwrudr.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtuetkeapd.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gthxicodzc.html


<!-- 参考信息 -->