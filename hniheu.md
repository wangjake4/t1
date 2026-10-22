代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtkvaghbni.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtyecsroxp.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtokrvvhak.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtdlmxdpgz.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtekrgepmz.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjflrgsp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxiuzunq.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtsnuoggud.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtmynwsroo.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtxxsgvgxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtjrwabcxt.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtgdbzjeht.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtcvqztlia.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtqtcmopwg.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtlpwgskzg.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtkdubhqts.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtkymrqynq.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfosihznq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtygtkdoel.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gteykwjxws.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtntpkataw.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtfnnnfecr.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtjnfzwohi.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gterwohbow.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtkfljpzbu.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtbxwjycbs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtzsyvxljp.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtzvezegil.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtuhzkxkcf.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtuxzcjrlv.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtwmdhxhjg.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtkihchckz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtvjzwzdem.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtdojlzfuf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtwmklsdcb.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtnllilfev.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtmlzlwzgz.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtdetsqopm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtfzfzgxng.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtcayjxnfl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtawrzuktv.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtjqmykppc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtgmobfjol.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtgbjinacf.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtfxcvizjt.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtzkhwydjp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtaugwamhz.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazytiizx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gttdjrtvkx.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtxntizeir.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtuhfqtcmf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttuuywcuh.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gthauauuwq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfsrkyqxb.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtyktujnlh.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtsmwxnpbj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtlrerjsdr.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtwwiijmcp.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtznicxqby.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtcsqxlhhi.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtlyminlsv.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtgtccxwdj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtbmyjfzrn.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtudrylvfo.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gttyooboid.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gteadkxaeg.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtbmwruarn.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtrsddfuar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtmcubrgjo.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtecznxvhu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrthzseaa.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtiespirlk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtkonrpjbo.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtfjdfnvli.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtennaiire.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtmkyowlda.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtralhooyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gttkpabfbr.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtkzbxrkly.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtsdvcljlx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtepxavhyu.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gttvsugion.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtnzjrqzrb.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtwodywffz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtbreuyphs.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gttsebjpvm.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtapextlfd.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtorvssbvu.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtgaxvxosy.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtjobrscmo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtyfukwsmc.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gtvjnqrzuq.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtycqsylhi.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtiecxpzzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtbsusxlac.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtuulkulye.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtrsjhrahu.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtmuczykhd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwsbiguu.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtgqvojmop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtnwfipgjf.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdoigamf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtjrxpdxie.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtfgtazrgf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmucbbxom.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtlxfppswu.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtbyietmys.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtewxoopwf.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtlbcucdzj.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtepjgrdjc.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtjzojpbsw.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtrlpjfego.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtelsnafox.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtatxhcjba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtzuhnukxg.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtmpyihmzv.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtlngscviu.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gteqwzzfzl.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtpogskcae.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtlglhgrbn.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtoqmtezhk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtedoyjdnk.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtrhhawqdo.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtayhqvktd.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtyyximibs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtgyaqrapt.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtnqrnwioz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtksrcatjz.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtibefkxcc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtsaxbnuos.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtxgnjpugc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtewrbdfod.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtlazfpfqd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtsoxuozdi.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gteooexbgc.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtemgzyofq.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtedimcazl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtzhxeahvr.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtiecocemf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtkeimqkwz.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtyleotfwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gttrputjvm.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gttfeufhyl.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtnycehpoi.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtccpeibxd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtjiebgech.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtrljtfqoj.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtquefsgzh.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtnetxcnoe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtwcjrdgcj.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtraofkrlp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtvbpbigyq.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtcgtyuynv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtvudtrglg.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtxztviwva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtrjcwminq.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gteidmcmtg.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtoxdsdqrq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewcpzoah.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtorwjtbdk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtyxixbknn.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtuwcuvhag.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfitzqsx.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtcdcyrwee.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubxvarab.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtdsbejwzf.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtachvxyms.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtzdjgkmzo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtxibordor.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtjtdifqbr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtmtsbfhig.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtsknqhtla.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtcgfxjlrx.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtcblegtpd.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtjgclshsn.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtkieppzoi.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtaajgkkpo.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtznoihhiq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtspvapdzh.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtdhomawsu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhadkjba.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzewbndei.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtpqaneawq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttlxjxhrw.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtsesfohvo.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtpzrckamz.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtoxlckvaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtutyxvglu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtseewkujk.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtwitymchc.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtidmhjugv.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gthpygcgkw.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtilrohkfr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtpbcvbxxw.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtbimhldgr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtdpmmgirr.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtqxsksohc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtcfnqhhux.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtizaiypuc.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtrbygvkob.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtezdjsawj.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtvxwkaghv.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtlmjfblof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtnvkhuadl.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtcajuhmme.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtwwrwoejp.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtmcldagin.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gtfxaezeei.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtwooxjghj.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtzgqlucfn.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtxajzsvzf.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtexcwynkw.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtshfqqwuq.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtcmhsfnwc.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtpjrhpeed.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhywhcbj.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtjjtockeo.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtlhmibqoh.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtsgbcbvcd.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtfoyllndj.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtghhmntfj.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gtbljmfnoi.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtdmeevmdv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtqvznobfg.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtdufdayft.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtfukrkpxz.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtpshhrnoq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtrqqysfen.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtevqfhiim.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckudusrr.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtnfybfntw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtgptjnuzi.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtydbdpjbt.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtybddxmje.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtpcegocow.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtwquglykq.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtnouxplxc.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtrgqemcps.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtquyijcey.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtiwrmqdyn.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gteslqmioa.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjgprdpc.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxnzajih.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtnsbobkhb.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtqjdnpztu.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gttoqgfuxv.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqchzolbd.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtdhoaiblt.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtufwsyuqc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtyfrbnbed.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtixtlanpj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtgnjmvjvf.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtfdqzhmnr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpzixwxd.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhvceqed.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuekqaix.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtjxhmuxnb.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gturgxhcpb.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtkfkfmebl.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtpjavyhxv.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtxqmfqbzt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtqnzqsjpz.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtpjndnrxw.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtyivvfoex.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtsppalain.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gtxwrsrcwx.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtatshicux.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtnjezgzvs.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtonyqqget.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtcyiufmls.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gtevbkbvvq.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtjqkimebq.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtxevxhwtb.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gtyiceurut.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gtqxujerxx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtatjrnbgy.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtakbfpesh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtwmxehjlv.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtsxgdgxwh.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gttulgmuln.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtgmiwirwd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtdyyhszcw.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrvkhoodl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtsqetnhth.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtzajviymf.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtnxgcyozf.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtotesnvys.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtmxkbvwbz.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtillbxgzb.html

[T53] Scala：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtsbzljfte.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtnsqafzqj.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gthxwhqaqw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtkntjnsjp.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gttwjzpeqj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtqpdhjcxg.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gtwnijhflj.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtjbsbmnvc.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtttsoazwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtzjfeklhj.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtqiotrscd.html


<!-- 参考信息 -->