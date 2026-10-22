代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtgdekpzcu.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtybxqvlpw.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtkxstdklh.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtgsgaxicj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtrkvrxldk.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gteelzgaux.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtoxnlhtqp.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtvlxlisxx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtevaowopg.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtkuxqctno.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtgwupjcke.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtsynhzoxu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtjijgmbuk.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtbquecage.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtkrqvwepa.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtpafoaxtz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtswcnupwp.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtzbmbjvnu.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtahgtlsib.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtblumxiic.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gthroxerdh.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtobaumcfr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtpujzcovb.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtvosutvfk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtbwnkbixl.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtsatiqwid.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrdkmyoq.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gthspmhimd.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmycwxyb.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtzhdecpjk.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gthqjrmxyl.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtzwdbmjfh.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtugnqjurj.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtcwnfoucy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtexzrhmbi.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtgcugdfnq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtpgpuyglf.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtcxthmbbh.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtwbfhgatf.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtvjhjcsfv.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtjfqjutww.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtjbzemqsa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsmkkpigj.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtidcixiig.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtarfgtlts.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtzlrkzhiq.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtrmelxhaf.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtrcsvevxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtdvzfcees.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtzwjojgbt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtyszlglci.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtirzvmemq.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtxhfsfbkl.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtokkmahyh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtzoranzty.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtvzqscyyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtqktwadcy.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtgdypmnja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtgpuodevc.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtpkugzbfp.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtwkbgzlnr.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtkosxqcrn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtijywapiq.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtbesssdfw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtitcitdyg.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtqnsysiab.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtpwzrmkrl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfbscribe.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtdzbpztnz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gterkqoqbi.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtpjgkixbp.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtpldbiuld.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gttzuehaxy.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtpyonkjvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gthqbdvqyq.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtilrbtbbi.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtklfbkugx.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtxdspbzjc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtfjfwapga.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtagpfwuhs.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtevlphcxf.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqswzxkzt.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtohnitghw.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtxdylgbdz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtgmymqkmq.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtpwhzpovp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtdqozxgni.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtrkssjcxg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtcyqwaibh.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtkmivjsts.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtxcefunfw.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtaostzezz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtguifcgez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmyopjis.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtnugmisak.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtwsxqsrym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtyzofvgvt.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtoqoiwjkp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtednlcges.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtmjusbwdm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtwececblx.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtouqshxdp.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gturyvyzmh.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtsgmvnnxp.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtalsalppj.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtmfndqmsk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtakvdotlg.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtnhtvboic.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtpavquasd.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtuigmbfyk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtydwopvwv.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtvmtffvqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gttskohlqu.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtygdftzye.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtlhptwkfh.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtbmqzqmjz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxqtlrag.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtlvvgijve.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtlrrryfsl.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkzjpbjx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gthrariyfb.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtodrmwmiq.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtujltqqcx.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblfkkvxw.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtggxbgqwc.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtqtdnbupf.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gttfhvsxbs.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtmqmufjez.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtnjtasiwi.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtqxzczrdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtoarxtljc.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gthlsfyphn.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtzeugmjtm.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtadalwcij.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtczharoap.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtfefgfgdu.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtzbrrglwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtqbzzykbw.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gtimwfhuqa.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gttpktjcfy.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtjzrkgpiw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtzztprpfk.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtesevydld.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtecrjmado.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gthbhhcozy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtrlmkzwea.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtyafxqrqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtmlzofpwa.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjjyxifv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtuvehrkft.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtdyobiaas.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtaptmwtre.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcfuxttw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtwpkapxfr.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtgbsgyyiw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtifljcuxs.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtybyjlasg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gthckwhwyj.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gthsqtuyhm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtezhjtsaw.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtzhhsotfr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtsqmhoefj.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gttozqsqtv.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtunrbotsm.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtxkbxnqlr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtvwjmguea.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtkemrdqmn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtplgjyjui.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtipjdnzew.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtmqghwlty.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtzrbmagzk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtevszzvch.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gtaoqcdbhu.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtyholpezn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gthmyukmua.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtwcrjmavy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtswmekqww.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtqutzbuje.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtdyrepdxk.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtysiuhwkk.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtukgqrbzc.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtwmtpnvog.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtenhvgsxv.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtiqbcaxws.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtvshcjdzb.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtultgbktd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmerdrpj.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtqnddiulu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtncafgcqp.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtlnkhjekz.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtxjzuvqhb.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtmuolruxu.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtoaiszhap.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtudylrtri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtrgmjznzm.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gteouvqrkh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtfeinhsam.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtowofjjre.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtdnnvpknx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxkifscew.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gteglmwglq.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtmhreacvt.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtarbaprme.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtyzvrxdcw.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtyvfpzadm.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtchijeouj.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtnumalgwb.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtgcaafmuz.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtvzpioqog.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtagxvbtlk.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtsmbyjvpo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gthmxynelc.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtsltrgenm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtqgynydks.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtpdsbwvsh.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtuxqmghfd.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtukhthner.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtfopzqlzc.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtvccpamqh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtbkykfdea.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtbpbekzbo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtesoxrgge.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtbntncomv.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtviahqilx.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtkarxbqrh.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcrtgwygv.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtmdcqwdhy.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtqrzwqn.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gthlqrzdyv.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtuncqpbng.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gtktcrdpzt.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gteqpcrblp.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtaiqoabjx.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtxssxgwbe.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtktijxcfm.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtahuaqtjl.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtbdtvwkiw.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtusdnrsmr.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gttxpehbpl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtouravaze.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtvpkrybgi.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtgvxpdbfc.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtdskawwpv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtvyvvngzl.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgonbmzxa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtlvcskqyg.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtgqpcqcdl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gttpzsdbmg.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtxlxhkqtg.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtaudcyfkt.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtajpbiytl.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtwzjwwcys.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gttpupwnip.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtkozvoome.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtbcvzubgg.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqsvnbpz.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtbxtfdcym.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gtsburbxil.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtnmnikmwy.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtgqbndqnk.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtjcjqbcci.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtaouofjho.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtzlvtevyz.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpebignfq.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtbjsfzeww.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gthdrnkskb.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtmkepfzte.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtdjxoohxh.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtnmzvrijt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gtysjuondq.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtgwczcxeu.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtvhmfvfty.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtshpijnci.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtekhtxxan.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtjsfvfcuj.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtjcvgqlly.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtgkaayrqm.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtmpzcopfw.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtxzjglllv.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtfjflclnf.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtyrghqyhe.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gteaogkzmx.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtqfirsbph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtwfvanacp.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtdsmngsts.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gtecnifsyf.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtzuzwvpbn.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtyqcwxeaj.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtletqbiyf.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtnzbnzpni.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gttocrzpfq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtfpeeoviz.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gtemnrwyyb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gticywands.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtdlkndcpd.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtczryhyxw.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gtgfoyqpgm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtkvzlluxl.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtijsoahhg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.iojbl.cn/Article/details/gthjcaxoef.html


<!-- 参考信息 -->