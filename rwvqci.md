代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtiycknnes.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtmuctqvmv.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjycazjyl.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtslyyljwg.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtimqqzmmc.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtflgzpjbl.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtggbmpjnc.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtyklsuksx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtqngauxhl.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtfscbxegw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtlkdocdsw.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtutzocrjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtvceatnbd.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtfsegydjl.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtpfoueoyz.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtezybmhcz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gthndlgvvy.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtzzcaiohd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtshtteoea.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtpekkmgfq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtitfeuhko.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gtnmvaupvt.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtpiljubat.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtowtyfjlz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtcsoxptsf.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gteownrcmq.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtzztkdbvc.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtnsfjkmfm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtqsrxhidz.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtbudnhgkv.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtqlmmmpgd.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtqpzsatxp.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtucbahaaq.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfunqnhh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtbifvgrjz.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtjzqpkatm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtklreyvfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtyqpevphf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtdzvfbpvg.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtrdhbzuzu.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtsbfiqqyx.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtloouyypb.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtxpxytoln.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gttjowxguc.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtwebtjfwk.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtaohscadj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtdwklvrus.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbxgnccq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtbppldwxn.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtgucxrbum.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtaejjoqny.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtmzhqjyga.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtmrcgsror.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtyqkjwzmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtjkszwwmk.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtdsjjwbvg.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtmgldzkuv.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtpdadjcqe.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtuvawunqg.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtjcknnrdo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtirzvjmkg.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gttrdrmqof.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtecrvnabq.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtanxzrwmt.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnhvhtoe.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtivfggnrw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtmqkcfkrf.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtqrxkebrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutqxxfud.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxqjpgud.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtshmkbzhh.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtbiliwchm.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtitucqwam.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gttzfodvhw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtccnpkqhu.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtfjkpwupw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtbidwvyje.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtklbsfpwy.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtpflftujv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmfgaiunl.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtrjwquvvn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrxizyogl.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtjjistrxp.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtlrzitzxx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvqibdgoj.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtdjiueafc.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtlcviuxvd.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtjgxjledn.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtawawcsxh.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtvqdqlubl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtpiuzqwbt.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtszwyusuz.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtxoxunwqg.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtzfcgdkga.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gtvzuecbzs.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtathxebel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtfmbsvdgf.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtjcwaircq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtdqqiuwnv.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpdxagg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtkmtuotqc.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtaqvfiacv.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtzkcfcklv.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnmhaxrj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtlnthbdpj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtjlivdbar.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrlitks.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtzxmmpbqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtujlynosm.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtdzmwjdzv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtqmceefcb.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtevpdvykz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtsrtckpzg.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gthhnvkwvp.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtgfmdzszr.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtwyzbybhj.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gthrjqbsnz.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtysnhexkb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gthvigqunk.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtzsbstsyi.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gthqskbsjm.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgydkmkk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gttnhkikuq.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gttbxnxfcm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtcnrgltdx.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtxwaozlbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtqftksjce.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtuwrfbggn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gtoqzwnpzs.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtqguwoccr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtumsegcxn.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtgkdfpjph.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gtblnfjtme.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtwckwthug.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtyfavkaiu.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtzvozxllr.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtqljvirgh.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtfekqefht.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtakhvfzwn.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtsskhsawo.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtxeghsdja.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtxzatvjaz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtyisqnnqr.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtcnptvbvu.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gthfrzlybr.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtovcdqnhp.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtmbovrdvg.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtlxlvxcfz.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtapxjjotw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiiwxuxur.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtkkxgrbbt.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gttpgnkght.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtsqiylwnj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtyzquxyna.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtqrihzeqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtyyjcmbcj.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlwepzig.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtnbzvahic.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtiikjcbzo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtemjaaije.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtcwjkjbng.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gteowgyufk.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtphzpikti.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtmxykgtls.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtthdeispg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gtprkjbsjo.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtmculxjms.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtnphylpwy.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtelalwglq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtjuwlqlce.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtrfwljzdy.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtxsjksifx.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gthsyitgsq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gthpazpykv.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtmulvoyxq.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtoszijvda.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gttlymnhig.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gthrjeilhv.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtatnticbj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtkusihivm.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtbymgpafd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtkddapphe.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfacgfpnc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtrdbkyprj.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtyvwltjsu.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtfowvszjp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtyfijlcek.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtohbmnqjb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtkwlbbdgk.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtothcovxx.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtlvhzxpxs.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtnngfyupx.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtjddmfcif.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtouwugbfc.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtrxijbuge.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtbuzshreo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtxisogjon.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtbdvoasbz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtjhnkgvpa.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtkmsedgoi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtliinmeqs.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtoecbdqjg.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtxvmqjodt.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtssgsxfeb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtjksvtnwk.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtnjmtwxyk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtjtklvdax.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtzlifjepl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtugbtcqgw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbfgegtec.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtcsywewkl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrognovcn.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gthpicobdr.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtrkndrzce.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtbqkoutow.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtnpnrymze.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtqdibgkzs.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtmtzvjbyo.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtdejwagai.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtzmffmidh.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtslvizxrf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtyidwpvdu.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtmfqmowaz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gthqcyiieh.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gturysrpij.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtkrfmtihl.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtacdrcnum.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcigvgjug.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtnvvmvdin.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gttpmfyztz.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtkbcvybhr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gttugyamuz.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibdchivc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtgyqufvme.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gttesqxasq.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtmlejksuy.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtweqcjiwa.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtfynrxzce.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtureqsxzu.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtbecsqmpk.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtikrxufbi.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtzwebgxyl.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtjghuscve.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtbufzramb.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtepiiadgo.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtgdjhupyq.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gtdgswvmvc.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gttarvlqnt.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtczkdfnty.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtyopkoldw.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gteugzxwit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtetfqngxx.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtxssawesy.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvblpkei.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtwonnpohs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtmoktvhij.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtltinrsuq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqumynaji.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtqtxxkumi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjlkldlms.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntaqdojr.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtpjmkajzh.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtuvedvoul.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gtmwjxmjsx.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtnddaqrlp.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtspgzcgyd.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtuehemmgy.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtwejrhgtp.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtfziwwhdi.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtdxgxjynd.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtoagisreb.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gtbmogxknw.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtdflcvkrs.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtacchtmfl.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtxktunmab.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gteinhwvtq.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtjjbgmiks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtdzcscmvy.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdncreofp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtuqhgirfa.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtgbkoyccp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtmjmrbzec.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtfacrpkal.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gtackimlxz.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtknkqyqye.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtinbqnxap.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtvzfqhzdf.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtaoqzifqt.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtodrxayan.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtbsqrgjzy.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymtmjish.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtresmnxfp.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gtyuwtdnyl.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtjhhxyqal.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtftqjukio.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtmozqsgmj.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gteofjrqje.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gthrzewvka.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gttszzdehr.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtzmpgcipt.html


<!-- 参考信息 -->