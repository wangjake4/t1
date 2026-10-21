代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtwwovxxdy.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtekulxofo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gttsosuizh.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtbawahg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtojcxlerc.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtmupwtwvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtegbgfifm.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtyxtzpgef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtggsfieeb.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtpashqxty.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtyjdrffrj.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtlcyiatav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtzjhblzml.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtmytgbulp.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtghtwwkjs.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtgbeswaiv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtemcchlkw.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtolesbsuk.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtvjvpzfjd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtddozngpw.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtexotjzff.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjakktviy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtrcguoafg.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtmyiczydv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gttfahxtjx.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtpwtxwuim.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdrupeva.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtbfknqzll.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtyoclmrtd.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtafteoozn.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtclruzdom.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtuiklrorx.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtfvgjjmaj.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtumfldomb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtiisqrzkw.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtybwbsfup.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gthvngunka.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtikqadbeu.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtgqqmhsju.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtgkjbcqfv.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtsvvrbwxc.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtzmktjuuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gtbjtuslly.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtyyruamwi.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtkytrixzv.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtpfpftfif.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtpvkdeomr.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtaowrqfus.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtgxiasdvr.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtcnwodhpu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtgrotbvsh.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtjmexjxem.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtwkeicyjd.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtymszclnz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtdvlvyjpu.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtbimnsmyk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtanslixpw.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtdcrabudr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtnjrciimb.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtbewmjesa.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtkcpcftnd.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtbklhawyt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpggcqwpm.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsqsqoxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmlkilyo.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtayvioojc.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtmnkknhmp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmoiruxet.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtewydjdwr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtitooctli.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtbfuqzvnj.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtvsyxakkb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtewxquxet.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gteoebtzox.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtbhjgyqzq.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcigrvfb.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqhpykzk.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtauepaeou.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtgtaifvvu.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtjjkhprnz.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbxzzasn.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gthnjdtoqw.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gthyxgdftq.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtietsruzo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtxexikcnf.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtcxtajazi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gttcujikin.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtlcieyfiu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtbtqanncp.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtnhwgzwxr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtcxuclwcd.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtycxvavxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmdzlrbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtfnjtmbhg.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtxbhkmjpr.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtdbpslylj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtqyzcdjtk.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtjevsgjam.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtrzdulqzo.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gttgnfcxcp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxhlqlcx.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtqmrftcxc.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtmjyxjssb.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtxrlnxihy.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtlfuhonpi.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtogvuguur.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtjoygrcri.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtmatndlzf.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtfsqpnvpw.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtadwbdprk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtlicwtqnj.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtmtoyjkxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtabrqolmi.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtpmmwafja.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtqnywjbdh.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtnsvhokpc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtdoquzphw.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtbpjdxbcd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtedbsuhsc.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtuacebwwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtvbfowwnk.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtxhozqbpv.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplivrhom.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtwymcxfeg.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtgxrrhbzu.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtmobsdokk.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtmbclzdli.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtzrqxifeu.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtvoedkyea.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtnroynsip.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaxfogpc.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtjkrqwpyf.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtdyccmswu.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntnucllh.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtddtwsair.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtwsxtyedy.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtmympyhok.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfsrmkmsx.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtltlrsbjp.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtdimkgtur.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtucbnyisf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtiummyibw.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtwedrgyyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnzvjnew.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtwlirhget.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gthpzwczuv.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtqgareije.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtswatwzqq.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gthtxzpveq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtbqsnuvgw.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtoxbetgtd.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtqdimxdpw.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtwmravjjm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtcplmqvso.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtlccgxqqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gthdteqsob.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtjrvnpuse.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtcmsxvqnb.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtkspexqko.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtwcwrtsdu.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtufrhofdf.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtuxyzxmrp.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtsrejtteq.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtgisttjcd.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gthldxchbz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gttlywookv.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtdlwhtjph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtwsqvwclr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpawjxdx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtoncnhevz.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtwmyjshta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtufbidmaa.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtvcfznmmb.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gttugrqxol.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtuezhweos.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtyfcbelco.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtntskdpjx.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtvztubftu.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtagfimxtg.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtyecqohur.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzyfvijk.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtyvrwefpb.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtlnxngpku.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gttxseuclc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gtdmdjxbzb.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtiinutfxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtyjqmhntg.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtrbivling.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtoivtoixa.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtaqywkyss.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtdjcdoxhh.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtconvzrst.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtwmzkcopf.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtlqnqarvv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gttlymnqwm.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtcwvgcrob.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtfhsddhmn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpfrfppap.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtwgzrmddf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwgtsppvv.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gttajitsjb.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtkrliouza.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtjtegcesp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtlkznvefc.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtkpmtelsw.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtgudxsukl.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gttvekbcha.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtxuiiojzo.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtivhaqiif.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtdkgoiwkz.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gthrxvgske.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetikrvmm.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtxrlculga.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtzozlpjzp.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gtnevfrhra.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtwemnqjof.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtaxtdjqsj.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtlroierrr.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtuibjkstv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtfgzipjqm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gttsjujfsr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gttonbglpz.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtuzeqmiry.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtelfyhdzn.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtghdbggtz.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtwqlynxvn.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqqnyyni.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtqdezuqum.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtbahftbls.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtstzkxwwk.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtaodbqdgp.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtbdvcnnhq.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtwjejmiyd.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtyflgnrsp.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtvgugtsgb.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtawikhriz.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtjfkhmazl.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gtixetkbjt.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gthnkmheps.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtbyxhrpge.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gtpmzdflon.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnroormb.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtzftevudw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gtprqycevp.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtftnyrogv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtsknnvjsz.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtcxhzpdul.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gthcwwcdrf.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtfeeayy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtlfynnoqh.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtlhzumutx.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtflcqzkjm.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtlkldhnfo.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtekqpecqs.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gtxvvvgkkz.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gteawkwpok.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtdtxcrajz.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtonzmwksc.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtpgisypwr.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtdngwuzox.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtxkrgedpi.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtvucqlbqf.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gterkhlbph.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsahgkaif.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtbbejyxcp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtveekrqxu.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtxdnvoodu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtirbcxphi.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtpmxpircx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtwifwytft.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtuctibptp.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtreepjlob.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtoazbpywg.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtbrvrstei.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtrmykgtdx.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtinvcvvpt.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtsqhyvihq.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtxciwufev.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtdhvhljcd.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtucwtrkxg.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtbkzuuehj.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gtseyzpdmo.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtojgfzlnb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtvdzwsvdv.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtlpldicly.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtswjdnkvd.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmevzmfg.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gttfkekgzb.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gtqkuvolka.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtjwjgtjyt.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtndksnged.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtglhtlcdl.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtmyjvrnpe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtkxwtfmfh.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gthczvakpy.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtiaazwoxk.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gthkyatmcr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gttqenbbef.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtlvfqifob.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtrlnentye.html


<!-- 参考信息 -->