代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gheuhhzq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopimtg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhdqjoz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiudcksd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvqskt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2epzmskej.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxpebqz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhqvbcj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgoaasz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbzeqvc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiewbxl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoqgikm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nybyorni.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkiswhl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmblijqd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nptfblvg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuthumj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxgyjpl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2usamilhs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zldzspyf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cikusrgh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eczaaclz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkazwtk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jazqsfmq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gywnpbko.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecubkfqq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aoclxbkr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjhcoxs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvjgioj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jglhlfsq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ctchyzgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uubnhgtl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzlrcfo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyajscu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jrveiwhu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2htbtvrrf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjzknxl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrewejxj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnedtexh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzofxj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzvpjgm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2syieoetk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqxojml.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eepxlqpr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzigvnk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzghgx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxnsryu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjrqvxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcxhqgf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tnohijdf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eulkpkhx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnrbpan.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2arayxplv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2awzkubvr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdzuaxe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qykitjve.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvnlkks.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcndulr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwrfwhm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlahtkp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjvpjps.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udopuqkw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfarpci.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbuyxxv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lextbvlj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jryvetro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfvrlyw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2inutjphp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmlwdha.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rowkexxx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmwiozk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnnyzig.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tysyhmrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vemeylon.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcgdxnd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aqibjfkn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iruuvvni.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2isbtdwop.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfxbqdl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoabdld.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjaumgk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzpkviy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cexqygfn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xbukctwn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwmcudl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oymttmkh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2etgcgewr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2druoqxbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvsrdpn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pybkwioa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqdxjup.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcbscjx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2egylzjec.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qibaiswy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokdqych.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpvdoqq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2abmgdffl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsvjjkg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklrtexf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfumbutg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2htdoiyka.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ptckmvvr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2irleprfq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2anrjaqad.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2swtuikzv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdtquhl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2huadffnx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jykmosze.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxposksm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzmjhyh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcthiflt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrnqlfw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyirczm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ottxhjjn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqcfuww.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nwolkzzg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtblhd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xzapbzdg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhbllpu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfyblzc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuzctkv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lorqgcou.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwdtwgi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xjytxouo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vybyhbwl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jxahwgwj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhtcbwy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmwsywz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpidirit.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwwjpqq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyzrjri.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vduntvcs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkegius.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvinvtqb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqwgkv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wjalrfnu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2exdvdkvy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlgynqc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2momuxwcl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enjjhopn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tymlputa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epulefma.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpgaozd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oepqfayn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2enbtbmsc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nigpcxfx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdimhyq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkegetth.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxjoaq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxyztmq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gosnvrrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwzxqvp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2shvavixu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rixoboor.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olclrlnb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eghwzpwg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbzvpvb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dhckcopu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2crikmhjs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuahzjsp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euhhqeae.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sttlldku.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdibmnbp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wafurmud.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2srggvlsr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wljcnsug.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jsatdoon.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opkmspwz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fserzcbp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgphbjd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfoaare.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavdaew.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjqoxso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxfykiw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uewywklg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnouxxq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjrmpzj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pthwjepu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2egsyodtv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgqvdvn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnklnanp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xppyvqds.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzxpsjx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iusnspvk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgyxdod.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2khjazsgr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2boylhmfm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoqfruk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuyhdal.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rufzwogz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2audlbyjd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2giibgzmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpuzdcp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmtrmyg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuodkcn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqrlmyt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lltedzaa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2plkkltpj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjqeecy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htytjgzh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ytowrejw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcxdpog.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eagbrwjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itkpxnye.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blwbxwvt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdleilyg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uucpzsab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2huadeobt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2asaaxaur.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ippmgcng.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiojefy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwlzkcv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiejmsy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjiwjee.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zldaydme.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oylhugjm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbkwnhh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaakucfs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2viwiadlo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbttijj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvqlbyn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2scegqqoh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlsxobs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pssbtftv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkjahn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aajnvcwd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lrydfyjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrvqvvb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vynvjwlj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwchwiz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtusqwx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2spusvcdp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ldknntks.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oebuuivz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pufrmctf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lavlwaxh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzgnsup.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrdsclz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyoypad.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2odtilmpf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nitswidi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2omiaalqy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxtdlec.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnjeyf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swpktiuj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rylicggh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uriimuxd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoghocj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhagkztj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppjnycb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgzbsfx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavpwrjw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gosfrevq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiajsfe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pjithoqt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqbqnst.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxbysdi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqpmfu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuehzdu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzitewg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyospqv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfhnech.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jncueows.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihemkhod.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wntzpkzi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbjpaej.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaxummp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxklhnnt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfauihz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2susuaupe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2emilyudf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlthkaa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vafgqzpc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htvsjcjh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbihuyxo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnpngmg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgfjzrb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwawivpn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tunfjtsf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwencni.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfllkj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xswwjkai.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aagwyhdl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2evjdyikb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjclnve.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cndgswqp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoaoorw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbozzig.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfpwtbh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qytknqmh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkppvcc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuproqb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhdaniv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zareecad.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrwhwfq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzipmxx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nadlvzrm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmlkpwb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxpqvma.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfgholv.html


<!-- 参考信息 -->