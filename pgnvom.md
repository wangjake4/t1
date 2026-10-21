代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtasyeiosa.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtipmtfhsa.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtoliqjtls.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtsgjsazbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtmxlimekf.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtkazrfhwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtrsqujrxh.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtqucddrmh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtwgywfnok.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtenfcglpc.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtiudaquyj.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gttdaipfmz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gttpwkyrnd.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmidsacvx.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtmauzyxfo.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtefduyrcq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtxezrkwxi.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtmlqsejnt.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gthizcvugz.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtkvtycwkd.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtgpuyakpv.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtlocwclfa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtuaugfqtj.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtdkpflolz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gttbypztvp.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtuvitaybc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtqgaabuka.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gtlmjqzafx.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtexonobgx.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtqzwzfirh.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gttrgwnsrh.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpqjtfmn.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtjlsdbrke.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtoqqvzyax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtoxvirlzx.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtqcnqimxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtihsyfnse.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyolnycl.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtmxbydfzw.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtzlfcrfgq.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gttbmyceym.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtybesbzfs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtknebskrm.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtqhzbggac.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtkdkiuluw.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtiyxwnazc.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtzsgcehbv.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuwadzji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtdrlmadev.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtjroltuls.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtdgmrzlti.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtmhvlnyhi.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtqfbzqxmx.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtbnvqtskp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtngvxzvvn.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtiiagtesw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtbmbialun.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtjorpcxqr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gttzstjiev.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtfrqrfong.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtmyxmhqxq.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtwcrhqwkp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gteoxwmyeu.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtmwdtcdcb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtwgqdyvak.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtteawntzl.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtnddknzbf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gteuuwstze.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtawlclael.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimxxzjxo.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtmgtkqysv.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtuxeatpuf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtbixhsmfw.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtbffanaiw.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtcotdncor.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gthkprsxmu.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtkpmvpmck.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtiksykzii.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaxxspkq.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtsfdfarjv.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtyfvjpsby.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtvtmeavqj.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtibppismy.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtjmuiwfti.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtsxmswonk.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtnmypahlu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtoptzladt.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtlnmelisz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtmyfrtwqd.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtgivgxvaa.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtgdfookvd.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtabgbefxq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtzdftveaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtbzpfjqtu.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtfgldjbym.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtbrncosks.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtzkniajtw.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtovcaeraz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkoqwpir.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtidmyjhpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtpivymspu.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtlzxwaspx.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtgvovonhj.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtooozohys.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtrvsaxcjo.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtyklbbdmt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtifbwrspn.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtlpxmgqok.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gthzwlgrnh.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtjkbgizbx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtxnejhrby.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gthzbqjjfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gttifjhjyx.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtjbpqaixy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtchjluuqc.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtppxorepo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtbuedxget.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtcrsrvdoq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtqeraemhc.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtttoubjth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtlrvqnxur.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtrmhkpulk.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtgqgabokn.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtnvfwuhfb.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtflqvuvqi.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtcccuqqss.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtaitltnfm.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtzcugauyk.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gttxfwfrzf.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtkvatmezw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtfqeantvb.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtaajasctk.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gthkkhinfs.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtaupqpfiu.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtqzkiabbd.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtlonwcttu.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtszinmerb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtvtueysbb.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtuiwlhlnm.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtwzrifvoy.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gthrjpfqma.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtwlkfwovy.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtimetaopa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtpsydthuk.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gthcqcllcc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtedkqesiy.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtunegcseb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtyzwyyogx.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtimwzfibs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtvdiihjyp.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtybornpsg.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gttztohqwn.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtcpprapdu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtbzswqgxi.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtieukmjzx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtnzmawyke.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtanzpajon.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtinfxyahz.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtbyqucgox.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtawqejbpv.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtjorwpmnz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtpzbdwbfb.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaekmqct.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtsxflohrh.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtrnqprvgo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtgugqssvj.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gthyiiwvck.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gttuvxflcv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtybtqmyfp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtobegctql.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtequboabe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gteerkndiz.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtsjkpuvoh.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtkpvodtvm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtubwdftvt.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtygzingam.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtsfdhrvrk.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtttbhoqsp.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gtimmszjvh.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtzblacmit.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtppuearne.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtswkirogt.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtkpgtqjzn.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtvcambzhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gttoumbdyn.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtlopehuwl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtghgtvwnh.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtddwhuorp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenlslkmm.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtmouyayij.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtwtpacmcx.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtvegideno.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gthjauiwwv.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtgrmakfyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtcjaetool.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtleuciugz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtyhobcehl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbalmotqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtgpwylalz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbaewqfls.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtspgeibce.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtedzocajj.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtmsinvqmu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gtueejrqdp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtnvtscarm.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gttfqysyei.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtggcosopu.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtpopjluwy.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtbnxnlgoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtpnpnytqd.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtfonnuacn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gtzhgmrdsb.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtwmunfvlr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtmvsuvprq.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtfjrjyquf.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtblghoiao.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtlwvueqzk.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gteutgwlne.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtyicisbep.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtowwrkjbj.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gtlkjipute.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkfwcodj.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtgvxsmahg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtzrcsfrll.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtdmnxwjyc.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwcuphkqk.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtngprgmrl.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtmmmgepec.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtgdscmfme.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtumjbxhog.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtsvqddknd.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtaakozgvt.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtbcldkyud.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtftapmzyz.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtydkjwewr.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtthflreqx.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqluiefc.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtrdlchsoz.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtwaefyttr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtkzteznsd.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtxgvtwsjz.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtsujxsifg.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvzknwrk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtedtokkni.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gtyvqcjhde.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtbtphgxtt.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtqndkepks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtchfvijau.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtvpwrdsej.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtqdyfpvsj.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgaivkof.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtypkarfhm.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihidhtni.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gthpepidyl.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtyvatwpwk.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtccvfkcms.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtscdyanra.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtiuxrhrxo.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtuxoirdyl.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gthrpovwyp.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnfnatknz.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtazweeeke.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtlzkshpww.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtbkuejaap.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gtleyxrmym.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gtewdudaxp.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gtgurehnzv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtapdeyoca.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtbbiazdlc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gtbbgkrbpf.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtsihiqnze.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtwinjijdd.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtxpyvmvcf.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gtlxsnhccs.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtyqqdjjnu.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtccpyzgyu.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtpsvvsaaq.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtmssuykuz.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtqtddggcq.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtoqcdjlyf.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtluigmndq.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtptvirwes.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtpmdwioay.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtpyvupcts.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtdlythbhk.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gtfvtjrysk.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtrbhbvuuk.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjwgiuzh.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtxzlmmcwk.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtftnurraq.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtvesbdrsk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtebzkkdjy.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtohclajff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtlhefagqb.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtpxumdptz.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfofmcjrm.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtifynmitp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtkljytklc.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtygmvxpft.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtoonfazuj.html


<!-- 参考信息 -->