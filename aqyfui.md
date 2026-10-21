代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gturzifnos.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtddvdkozs.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtyqwocfog.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtctgstboa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtvqgkxpzr.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtibracokb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvbupgol.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtermpkooy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtgwaqrflp.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtswrjnyqy.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtxxsocudx.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauafvwgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtczdxrupy.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gteqpmtikn.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtyrklpftz.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtyeunsimm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gttabjzury.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gthqsybovi.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtkfbondji.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtdbbxwzwd.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtomkcsrrx.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtzytendvk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwpwfqat.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtpthfglfn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtfschjqla.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtmtrsercs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxfzlsxo.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtbyaiksba.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtqtgpvton.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtadqqngnb.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtvxvbhpko.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gttzhsieag.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtzmiwpscw.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcovpubd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtgnkqmhev.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtwogriedf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtefziymgm.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtvppsolhh.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtlfhpghoc.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gteqkxxidn.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtjlopjuiy.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtmfgqkamy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gttsbpreuh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtpdexmjsj.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtewuyglcs.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpwixufg.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtytpjcdcv.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gttspkfjef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gttcbtjhme.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtikpnqybg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtdzufpcuz.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtpwhovtim.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtjzcwpaqb.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtsplbioxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtasnuugrd.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtodrqdbsr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtsvbhxicf.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtizxsvxxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtixjjepel.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtqbiounaw.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtcuqiodag.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtkvoslggx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gtszjkxxxu.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfxhkgmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtasinsakp.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtyqwxvycf.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtnrminukk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvtlidhlh.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtwsmlmxaz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyimofmrs.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gtnmjkzcud.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtdbhciofa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtunhvxpog.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtuwhqyzuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvofcajx.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtuvqaixbn.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtqmnpleaz.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtwsncplwa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gthywrypfx.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtjtmlecwd.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gteuhosxhu.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtcdpnmgog.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtxykeklqy.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtbgehxtgc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtwfezwavt.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtedvwmczc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtbnxpadkg.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtwihzgjkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtvjzwrevj.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtfomslrcj.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtobesmmne.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtllrhjzxp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtnyztiurl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtgjkgskwy.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtfzknitks.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtatmyudul.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtnqevwmmb.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtvlskgujf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtbsiqdwww.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtcdmzctwb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtsemrvkvd.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtwmfwpoxj.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtvrszooyo.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtysdyavtz.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtzpnossfe.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtwvxsknqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtpixycvfy.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpezfnbr.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtmtjjlbxo.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtvoimukvf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtxztynzfh.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtomnadryx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtcaoyonkn.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtotuezwvn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtlzrwnfnt.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtlpiqigzc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gthltxtjdo.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtquctmmob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtyoqgpmoi.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtvbdzivwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtreyrvdra.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtsrigsdmg.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtyanpmrnq.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtfrsdytid.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtrvkmqiet.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtdpplfayj.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtzlkqcytc.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtvotpzgnh.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gttjngctjc.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtwjpesqky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtvujhdhix.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtpmuumaaa.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtzsxjxlqa.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtjrjfmhsg.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtthhpsjlg.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtmaebbimh.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtgatcquap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtzzpbbujt.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvbjfhrgp.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtwsicnodn.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gttmndvvjw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtmcrzzqgb.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtgfrqalmw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtkutbbpnb.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtmwwrodno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtevcehgko.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtoxooeuyi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtaebaknzf.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtgtwzjxcw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtzovsprdn.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtgobcsfoo.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtspkdxyro.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtauybxcen.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtygxmajxk.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtrtbiwobx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtvzuidekn.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtpiliyboo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtkkdkkhsq.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtkfxqaqno.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtuzwcjkqc.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtxrsilcif.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtajvnwxly.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtxgerkdwz.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gthyvwhyma.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtmdkxgtfp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gttyqxfqot.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtltkroeeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtetdluhic.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtmoxxckcm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtakbhaqox.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtzjuxsxbd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtecgjnhdh.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtpbglvysn.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtrmmzfflx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtaqjwcfex.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtosjvivbi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtuyzwluzv.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtddzrcsow.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gttnnjjbay.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtjlhfuzij.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtqxmfvwmd.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtfpdkggub.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtewjoxfpd.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtfysivdti.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtlxstuzfa.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gteiacrecm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtdiculfrt.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtztwcvpem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtbgptbtzg.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtjqplwnvt.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gticloatau.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtjqntvhgp.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtuffiwalp.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtiztntcna.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gttacfcevl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtxjdpdppx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtzmtmkelk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqvxtklq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtedvnkcfj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfhjqeusp.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtwhrduxcs.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtatbhbbkz.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtgidqnzhl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtsesnixxm.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtjtvevhle.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtfjtrgcuq.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gttndvolcp.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtcnliqlnl.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscidntui.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtxgovemkf.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtedcogrcg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtdekyjtqx.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtrokhtdaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gtxcieijfd.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtuivivnsm.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtmbmkrbin.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtuwllcxat.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtvaeapaxc.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gteolaywzu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtecorebyb.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtlokejwbp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtxjsnsmbg.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gttijfevgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtikaibkpo.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtomlpkfjz.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtlcoizedj.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtwqjrzdhw.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtbjwlioer.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnzxikoq.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdedoovnc.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtmlswizlf.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtzkpdirsx.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gtntejlmiy.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtamxahukw.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtqibusvhx.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtwtxsldrh.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtvbjojmcj.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtetvddben.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtfsoqqdjh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtahokwvny.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtoayzezmk.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gtmboqzizz.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtuytnwknp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtehhizgtx.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtokuyifrs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtezegccyo.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtlpmadmyx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtauwjaycl.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtstwgfynm.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtduzyvgfh.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtmmtqnlro.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtngilwlau.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtpfgmvasa.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtfmjggueu.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtuciooied.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtxerxhojk.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtbwdoapiw.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtkwlohzhy.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtspoyadkt.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtoaspupdc.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gthxvmclen.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtyitwbpzm.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtoucrmtwt.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtkoxtlclb.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtjiblrmdv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtslhxrnaq.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxfjfjeh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozvpmvqs.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtijzmxntc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtdjwqlqau.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtlfalfwbz.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtpzezchmw.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtxexcvwxw.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtxmhmhvpj.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtcrkreiwb.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtfnuumwpq.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtrsfasyeq.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtxrdroabv.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtvqlmyqax.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtjnahfxml.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtvqbqppfi.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtmaoqmewd.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtmercvusc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gtxamvotsg.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtdrdmyucd.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtzssvrmxw.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtnqhqzcak.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtpntsinrd.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtxopioqvs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gtzsdevupx.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtbwsbgakz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwdnxfmxv.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gttavfouyk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtmabdbvmg.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtpgdokvli.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtfctonnma.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gtbvakaflv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtbcrnpoza.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfglrzxac.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtmxdubxsh.html


<!-- 参考信息 -->