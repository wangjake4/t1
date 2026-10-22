代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fneyncal.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgeswta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgyire.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izcxzbkd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oinelixe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyeeicp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbbrvct.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2splavpol.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kopbamnc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtuaogy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkgxvwt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2phugpyxc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2krizxlun.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aelkvcjg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeghetw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2usopsbaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lahlsyxd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqsrjaj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwglekvj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhcgoor.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2acdxwftd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhehlmid.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrmhjnj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2morbftjf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuvwbio.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2melgnpor.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cmauvqkm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2frgwhvpe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2enbddtni.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmrniyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zurwigqq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nudquxaw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2euhmhwmd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgvzkmk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gusdseny.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhpkic.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yhphrbkw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jksmjszq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgeutuk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsofpeyv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdffyqw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzbkjzf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgmjwjb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mncotxkv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2syyuezoe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmfdirp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqiksvd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqukcox.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2byaestao.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2axxrrwzw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwoizs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfozvztn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wancfzbe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2whsxitix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsnyems.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osavmoqn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvcthip.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtlbrcn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxdceky.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkufmgai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tndbnsle.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmuyftk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnxworu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcolqqxp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eausovol.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdxnddy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rajaluyw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuanxft.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klaxomee.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2noieusfl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zckwtqju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwfkjjk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsacsxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdypdfjt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skvvfasa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2myggelkr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaenabcp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoteujn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvlxnni.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxlquba.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2azxuqbkx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysybuvok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pegtqbvl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xficsnzi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xytpihsp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjcxcdm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2giveyegn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwqvyfz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcigilhx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdyxkmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmxsifm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2btqkyunu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2heffbopw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfjwctw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfosmnfn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fonjphor.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfyafjx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyrilqx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuibnj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byxhpvww.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjaohji.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kyylpczk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdxbiik.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txzpwbkw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgeosjo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czjtztbz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvggmeky.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnjkvx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zablroyt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpidnkyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2osmjfuvh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwmchtw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2atlznwzf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqidian.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2guucxlgi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfshelk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2erhodgyc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2owqdmsue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtmfjwy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrqshvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgxsyer.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcndmxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxkkkox.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2muizrikx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlcxmpg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sabauksp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgtyjv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2npeofzdk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzyjpa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpznsae.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnoueiv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acoqiywg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uppdlmrg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzmnonn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuohllb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ltolhkwv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqdmsyy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrrwctm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuxapcx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejixviqn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yogigdcz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tndqqolo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjrfmdx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzauozzt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqccwkt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmvlehe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jlndbjby.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkhqatl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wiprqhnx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnynwoq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2phzoksgh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjwgycg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxoaeab.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjgtujz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gowenoje.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvmwihc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otxowmjn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhbvkqr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvntpgqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvwfpug.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdzhmat.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtpyyvt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyypiss.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeumzyz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2igxgruqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2azneqrxt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pkumhwcv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbtpqsm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxsrdiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaenhplc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ryssqsvp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolnfnuw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eujgddcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrxbnft.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfamjne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wenebtdx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyhfukb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttinsnem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxlozcf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyilewv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjgzbxw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzrthpv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjywzr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwngyfa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htyslmyh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxtedek.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwmslpy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmrato.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgfrlog.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwfxutf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2csobrvnv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojijfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jskkcukc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrdmajr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwtokon.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hepuzkex.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjxvbko.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgcfmzg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjljtrcm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eljxtnvw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlmuuff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gshawmke.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdvjkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsxyavo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitepii.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpifdji.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exsuntgt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gnykorum.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxiauhg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzpqqjl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpmcywo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzxvrcj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjijxar.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpvccph.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vatndpjs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkgzdyz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cywdyzjc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbfqudi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbbjxel.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzryyma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcvtfxk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uybcalrk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxhuloc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtkmfit.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkxhzug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbmheos.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sillmedu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xclffgvb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwevzqbd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtnycgf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oseircxa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvmlzrm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2okfbwuwe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxdpczg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsklcnb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfbqnty.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjyzngq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmymanvx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2plrpzits.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2curhpumw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdcxzii.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfprivqt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2axewvctk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agasionb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjvxoac.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovopzep.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zramulvd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcllulv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elfzotht.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljozzdjg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqlmggb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkefhbsy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qvklmcve.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvuzcdf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnmsitx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqlwbo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odvaaqlw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlgztxr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsgmpvj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckftmtfb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsmetug.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbewwnr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzgehpp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgqwim.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibusrzei.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfpvaww.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkntrkol.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwpdwa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmfsodv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rustqkmk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rcudelwe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdwhsn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2olyxvcqr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyjxgdq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luhumvvc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cizobglj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2thszeipg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiasilvm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hciokfad.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrsveyo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sleucnii.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmuteqb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwmcoda.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2akqbyvjr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2riiatkgu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzezvgvd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqdjyin.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvduovbs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jfadzqpc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbrsldd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2biztklan.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdiylru.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aozurnfe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brotuxbw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qyimluau.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdepwgtv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtretoh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfzoyzg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kufxfeiu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuimwny.html


<!-- 参考信息 -->