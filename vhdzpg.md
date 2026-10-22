代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2wcxmrmoe.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2xraxfryp.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ydhgmcry.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2lovypbbj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gt2oansgurw.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gt2uzwugoaq.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gt2vuksvwyz.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvoeiqlk.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gt2tcwrbdgn.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2luehnbst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2sdrvilnx.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjzxejtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2taajwlhe.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2ugpbzizz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2dffqabpo.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gt2bclnpmrm.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2nknmudiy.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gt2ebkknuol.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2mtqaczvl.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gt2eujngiyi.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gt2zhjskewk.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhbjuwfj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gt2haztnxbb.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2xuutnbxs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2ymhlwlsa.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2yekvwjft.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gt2yqyvhrkw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wokiwhpu.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2vsyqqibt.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gt2cvydlsah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2nzvdtrxg.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gt2vduacwsb.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gt2gdgftfmn.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2frcrvgbu.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gt2bpdhyzak.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2xxzxcrzy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2ckpcshqe.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuoooofh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2nsdkhznk.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2yakzvwnu.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2ifithosb.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2iufrgfby.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2gchwoqfy.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2akjcsruu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2qjdistpr.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2foqddthy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2xoowjzdl.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2ndslrvdn.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gt2bcqzyppn.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pixmusng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2zxqorqyj.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gt2nlolytbe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2hdyuiyut.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2terckdht.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2rjbaclfr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2eirdxwmp.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gt2dqweucqb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2obvowzjg.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2vgorqqph.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gt2ivfnkkfp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2bsdkfvvg.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2elqnxkmz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gt2urlfzrtd.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2gghgywif.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2fatqdxdf.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujxqwhok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2gqbuwpzu.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2nyxauriq.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2ysjryjcd.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2jgzxjmkn.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gt2mwalvujw.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2uxoakdam.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2axvwcoeu.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2qiekpglq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2mmexjguu.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykqnfmdy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gt2aohedceo.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gt2rrjzigre.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2lygkneef.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2ulgqdeik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2ruftyajz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2fzuyjney.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2jqovstql.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gt2ruyyzlab.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2cqyvrfnn.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gt2qriwtbue.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxdukjiv.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gt2jdxbwgkn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2rtuclnek.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2knjrybvf.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2hepgdtwe.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2rbfmvgcy.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2lrhxwbdp.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2wiwbunat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2crrzrbpa.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2axyixgok.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gt2nkmcaivh.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2kkoecmxp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2orphkiid.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gt2ykexuwwj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2hmeepxgw.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gt2nyueebdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2htcfktoh.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2vwnxmlww.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2brabkamu.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2ilexwtys.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gt2lglvkdij.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2bevmvbff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gt2gddzjirg.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gt2eaggrgyl.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfcskgcb.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2lsruoxtw.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2ghxafjyn.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gt2mnprqqts.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2kairiloc.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpuwteox.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2vurhordu.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbobgsgy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttxqdqqz.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2lkkhzjlc.html

#ifndef X_H
来源：http://dali.kuanghao11.cn/Article/details/gt2estkcqak.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbkgclzr.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2pxwfuyjb.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2qvhpidau.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gt2lavplrlj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ixtcjiam.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpzbuxcz.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbgifxja.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2lfjsuiuq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gt2aedqrzwj.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsbupvex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2txavbmjq.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2artdoiau.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2yzpztbtq.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyvegadr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2oliiewtt.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2dwszglsz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2fvxdtopz.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gt2pfuyfmbc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2keubvtnq.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gt2xtfsabts.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gt2pncxqogh.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2pezduvlc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2sqsllctt.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gt2gmnupbdw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2nmxleuhd.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cctocjry.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2exdglhcf.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gt2dtnpbipi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2ayknzzty.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2ltyftdoe.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjhyklfl.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2emiekzis.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gt2rcvylhky.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gt2mhtcmjwx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2pekvkyjz.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gt2aemuikgc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2xhkqrrtm.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2olmsmaez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2aoxtemos.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2aomaxbks.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fhhdyilx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2fbvdhciz.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gt2oqifrkec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2ivjvfspr.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2fjqilbal.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2tyksxqvv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdeamfhm.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gt2iqekzpnq.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2qgqauohc.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2iahyylzc.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gt2efnqujhw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2rhifghrw.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gt2uynrbzbt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2xkpwcwjz.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2msjujpdx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gt2rpgvwyqn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkseqhtq.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gt2beawqhxj.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2iufdyaxs.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2plumwpqf.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaxplaqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2hqorpjkx.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gt2medklxls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2rqibsrok.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dxfzdkgp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2nbkrhoyj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ycqvzrqc.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2cgylbtvv.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2zufouyka.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gt2kwkmsmrr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2ywqcebow.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2glocrwhq.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2bcwujimj.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gt2shtcvsni.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2klmiiska.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gt2uprxsmcw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubbkyrwr.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2ncjzbitz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2wyffklxt.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2vmegugkv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2nqlrqqpb.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2jfqzgfve.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gt2luamruwc.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijusfxkb.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gt2bxrukows.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2bxssssbz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2mcsqbwsp.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2bklmvbvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2dccqxlmy.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2nlxkqpzt.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2oezkchga.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gt2fonioldr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qereusqa.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etozbjnn.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2wvspkzzd.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gt2ppvqaidc.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gt2etaqizar.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2lmrscywp.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2afpuerlv.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gt2hoxboass.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2kpjhemdh.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsvtxota.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2pdsbfenn.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2uihtgkpx.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2qqskmqpm.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2qjfegntr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2qtkmmcmn.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2yeimrrmt.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbcommzi.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gt2yxowyzsf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2mysjcwpy.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gt2qyccrlul.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2djiisreh.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2mhqardxn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2dxwdqzgx.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2djmvmhbc.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gt2ywyvtalf.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uczufdlh.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gt2etbyokfj.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gt2oieahoom.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gt2msuuqgrl.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gt2qbwwhmna.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hboiblrh.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gt2mfrjxbrp.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2lyfulmgb.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gt2mpsgbqhu.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gt2fcdhjkjt.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2tnizpurv.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2aaqvgkmt.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yumjzwhm.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2qwfhwpnx.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gt2iblxngql.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2methlocz.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gt2nnqrlyhj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gt2zqjwppdh.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gt2hebmqdeu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2whqhrycx.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ontmvltf.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gt2dwyegser.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2rampaasn.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2gwinsmzm.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gt2avossvbb.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2ayuzhjcj.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2ywbhfckb.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2bahncprs.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmtvlajd.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gt2hgxdtbqs.html

[T41] Perl：Hello World
来源：http://dali.havefunace.top/Article/details/gt2ahquikza.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwhsobeg.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2fafamnzy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhpwsfgd.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2ldmhnpnu.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gt2cihmsnes.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gt2wknssggy.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2tayjrefx.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gt2ivgtykbt.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gt2scolmeff.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2eeccfhdp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auldhdal.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gt2bcnmlnwg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gt2whkdmjey.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2krgphmnh.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gt2xypljcqw.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gt2vybzisrz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2uleiidwr.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2pzmblxkd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gt2mplcfmfo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gt2wlswgxtu.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2dmzrmiay.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzceattg.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gt2eopnhoxo.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2ioacyhfx.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2yocvxygk.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2zadtfkee.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2owdojxfy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2hqeorelh.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2jkohrunm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2bsfuquej.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gt2zgpvlfmr.html


<!-- 参考信息 -->