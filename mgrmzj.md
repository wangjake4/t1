代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtwppbicgp.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtbwftwnun.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtsfmibyuu.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtfopyieom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtslhirjbo.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdnvszgg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtexapolmc.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtrclvltou.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtcnlheosk.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtpabgydjz.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtfjyjwbad.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezaovren.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtzkuxgecw.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtmqjvkpqe.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtgqjbxtam.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtydfubxog.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gthtiymhgq.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtakhzirby.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gttpjapwpc.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtheoczpsb.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtefzopvnt.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtnagoktrx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtpitsuoyn.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtswhaeumx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtydmmtaki.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtxcmuhpjz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtpgrwbbwc.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtuxqselbj.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtkldrllgo.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtwniajsvo.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gthzxlismo.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtfssybcat.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtggleindy.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtleadkkaw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gttojlmkzz.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtfbunhcjs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtnncrtpjv.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gthisczjno.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtsuisbumq.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gthmikovxb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtjbdvdizr.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtbfjnjufw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtfvxxcevb.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtqznhzhkv.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtfqfgopar.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtqwypigbp.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtjxouvnek.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtkrttfoln.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqtaiupj.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtgpgcrryv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtxrpmwxke.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtipyslawi.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtaqetaflt.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtydwwhaqi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtliceeadz.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtvqqbxqrx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtzimmhgtz.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtkglyfprm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gthugxvtmp.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiljvkhi.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtgxgyykqo.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtdqytaonv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtcoghoosx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtjgoxxqzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtojsxinyx.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtbpgjzqgq.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtexlswurl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtefcndwut.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtptltvbav.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtebroqyeh.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gteaxfecqg.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtyazzeswt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtxzqfvckr.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtlijgzzat.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtiqgxjafw.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtxxysxnlt.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtnarzxfab.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtvdqeloda.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtgmexqrwu.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gttprpcxue.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtjkvlbmwk.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtcfrvjbdz.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtxalwrwqp.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtvbbcpabr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gthbznsogf.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gtftehvlbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtwmkvhelu.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtkgvezpwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtfecdqlcn.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtdwcsfkct.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtmdyiawnt.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtrgmpoewr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtkhnjkkzc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtexzbtiak.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gthnjstgxv.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtvsttxwjf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtwdmudiox.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtzhnqpzny.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gtvaxmgngy.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtzvqibgla.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtourthvcg.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtxlydtjus.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtrdzubbbx.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjsfyehq.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtzhssbs.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjxkhjssc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtrqkluinq.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfjqgwuff.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtputicrog.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtylejtazr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtlfxshxow.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gttuikjraj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtolthhaso.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucvatist.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtxonmbdhb.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtppzkvynh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtbrlcxfye.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtvwromjfb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtupcocblw.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtalslhiau.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtkcqcyseg.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtubbszowx.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtmgyzxpce.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtbipmbkho.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtqupboxig.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtwddvijpr.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtufxnrckd.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtkkpndwnp.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtzhccbsex.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtvzknfxtm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtosihsbno.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtpwkuvuud.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtmftppclt.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtpnxognse.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtmcfzfqio.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtntneghic.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gticcognbi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtyugddcxg.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxsmwhiv.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtnyxqawds.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gttxqozzhd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowraztmg.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtvbnodeek.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gthjzryolv.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtdsvgwflv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqgveiztn.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtyitzhacj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtjpwfhlwl.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtfsslqwgx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtetrsaxcu.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtlkumbflr.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gthdpbzpup.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtmmamiegd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtpcwshied.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtmmqoxxnx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gttvgilfxi.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtaqahsupr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtztkcmckh.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlljwptac.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtnovpeojp.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtwrfcqomj.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtprubipvk.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtmvorfmas.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuuhyoria.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtdotgktxr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtnkanpuev.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtaensdkqp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtkeglrzzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvfjpslms.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtorlslyfb.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtayzqlmyg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtlxziitpu.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtyziljqnk.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtenfphpqo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtsjxwdwds.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtclnfeggt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtnimyxmor.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtmilgspkf.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtldgpncaz.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtifxtyiag.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmvblsits.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtsydwgqmy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtkixcfrmj.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gtaelchsli.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtmwxcxtin.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gteawgxjtc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtyashwcbk.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtwprkarse.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtfcloeppn.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gttrfblscg.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtnsnhliwu.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gthrzdxjof.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gteaexavlw.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtbtqssjzj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtccrpuakn.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtsdqeezek.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtpmnjwuys.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwjktwym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtemdcipvy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzjuyvfna.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtoufairnv.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtgkfothwf.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtcmmwocpc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzxdbqkg.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gttdwyjjyo.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtlawbqyag.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtpcotrykz.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtyahlbupr.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtfeefnecm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtiaelmybv.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtjwpeqzqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtdgemkggj.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtunszyyfk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtloqobdjs.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtzasfbjqk.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtigdpdlhc.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvuglclb.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtapxrvrud.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtfhbdryyj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtqhaqmdhb.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gttxpyosjr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtoubjmapf.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gtwjvbrinr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtgejapeih.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gttgyuaqjv.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtkrtgrkde.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtxxussqyc.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxumjmmm.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gttlemgkqn.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtjlllrbjp.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtvgxziovy.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtoqwzbwdj.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtrkppqoek.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtqdifcjth.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gtuswwrgpx.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtrncffeki.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtejyhhkec.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtxjqmoxlb.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtbrvnlaxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtpqalidpk.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtqnuzfpbj.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtnamgubqw.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtplrtybld.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtsmuqdxfi.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtymcrtauh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtiqwbvljx.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gthvyhmksd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtwokxniru.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gthvlhiscu.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gtktbzzcww.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtowepdmty.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtjoacklyt.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujszkafd.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwmzknmt.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtmochrnaq.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtmhqxbnzm.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtnsgouyoq.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtssqdwijb.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtgwlwrldm.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtwqrueilq.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcivgfisn.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtxlwlccob.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtgxbwdejz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtcwzbvwql.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtaetbsuld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtiopmmjlt.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtskipbsvo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtrnrssvgm.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtwgcbbqxp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtmhfnacic.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtkceqhjgi.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gttgkbbxuq.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtloujdkzu.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtjugbkplz.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtezmysioo.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtvlgmrzmg.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtooepkuxr.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtrnwpmlde.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtrjdgasjw.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtmzqfcnlc.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtutxejbpt.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gtphzwixpv.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtgqoqrdir.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtqfhmnuvh.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtpebffjhn.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtycnlfaax.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtbunonavb.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gttukzyjxr.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtcqxrntfh.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtumkfztzw.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gtzylxqlsz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaiomfzcr.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gtrzvlgmdw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtikkgaqjr.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtpgdskoyt.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtyttnwbbi.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtemziijau.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtxhwvohwc.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtjtgcqige.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gttpekxpwm.html


<!-- 参考信息 -->