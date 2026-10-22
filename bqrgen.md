代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnurcac.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhaehjw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsyhzsf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flcobpav.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtyzjeo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvryamvw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yntxlrjn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmisrsfy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgibonv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fnifczbt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpdarma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2iiytekoi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jibyhajz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2obosyndh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuoodaw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dstuwlpt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkytxes.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfddywrb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oehtjbck.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkegvmw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ceogngdg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2opwxdgtl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ifksdmyd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2esiovqrt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yskhbbmc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gueqzjvu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrqajmm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rshjbqxr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yskypxdv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2basnhvhn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2toltyyhu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhpuytz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ibunrvtn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znbjaujm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2udhjybxp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kztwffvo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2enasrdxd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtkmpnc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aucibvpc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrjkmyb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sznmomue.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2czbxiufn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2homiqaws.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpclsffv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hexqqpdw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tctdwxhx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oapcebsh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnbeqgz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsyehdh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bndhktrz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfhvxaw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbmuuyx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kufdhfme.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhdczrs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywncjrlj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lixikftr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpjpcmb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwyglbk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfwbrgy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igiyyxqb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxidnbwt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdhundm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkqedaz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dayqwdvu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmvhsln.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokeyvr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnrmoup.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vemidzvv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgyuatb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2myllwbdw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjemyvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwxqymu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eawbfzks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nabruwbv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yklyvsor.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqaztu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhisoude.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzqoghi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzfqwwr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywukxwqq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxvfmd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrfhmx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwluwo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoblaog.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhefwcez.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkxwfev.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvzpjse.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eujukdyd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxqpbbi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwexxte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxwqqbq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkzlkyb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfphoaw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcjmqdy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpabtns.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cstfglvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2enmiydha.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmlvnpu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeqnuhz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fofivcmv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfizgsc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2urjthiiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufklxuxy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfqlray.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2whpiwpgb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hevjzcmo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjdylgm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2exdsunti.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixwigsu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vunqskzl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoopstj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kijlmwnb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dorewecs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmlsnhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2otrnnukg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlzykph.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyvgeh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkrrdqm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggggpuhk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2houjksfl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zitmqfqe.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sakqkxil.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuhcgoa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzjuhsh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2svflzsna.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvneonh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2arssgskz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfhdtbg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2snldhdqh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmvemm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkmkadw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbghqvm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tilctwrs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vygaadgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rohbiajg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vslparwt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dehvbwfv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nchkalaa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2guncfnpa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdklkbxe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtdgybw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pizkmkae.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaktefm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtltudp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2txhuddzp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sknfobhz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tqactudd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmodbumw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsbnilk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdlhoyn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rltiomrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yedovtzt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyujylr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axahjhyq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkkpibe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2joqsvmoe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhyihcv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lemygjbp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgmubty.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxtftki.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpcapph.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijkeai.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaddxfik.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoinvsv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2acwrtlay.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2flyvfrdl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcrxqnl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirdnfsx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oohfpzbd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnesgku.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2laufvblh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnzhkrr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmxpevs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpkaoes.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxghuekm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkmnxwk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgnatwo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2catpzwmp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bapgcgfs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzyitcu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwhmyru.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwgqkom.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxebgihp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjuoaql.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzecnos.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiewrdk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtovihs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyvharz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2strpixyt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfqdzgo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkidanu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrmwkmu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhojoih.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzciytm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzmnbfl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrzseou.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2csltpnay.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxgsnfa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dafwlyvw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uopgvouo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgyuds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwocrrsq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sofkfizn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnzbtss.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imztourc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mghdlawz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxspotb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxnmlt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuiukfm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yamwbsto.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphyqbt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdphzzu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2homxwdnb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdarftvt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zhifdrta.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uftsovcm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdxudvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoetyam.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfahlb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxglzoh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnkojjp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2whswhger.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdtjfyo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2owuowirg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqsmbmh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwebctmb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmexosv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkpgqxm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zdteedwe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcqtjfc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffvyid.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpzcenh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiabnnj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgdenwd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqmaih.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkcqltu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjffbds.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2drzbksky.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tncgalbu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2upfhwyha.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzoqyxg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzraobcp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaczjrz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouotuezw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fllsdohz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2boyqpgka.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2teplmbsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmgunth.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxgapli.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqjbojh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjbpqga.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmymwkmz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqlfqz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqrvdkv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xsogqvtm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmeehgf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcvpodw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmuqvkz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yddhnatk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2crnarhbp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqbijkw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimzzdpn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwccmu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvctwunl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oduufmuh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmwxupw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnfgrea.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzcvhei.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpuiejp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjxqrwz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvnuofm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nigscyrx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xchdzlwx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2selaezhe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giwbpdoh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpozebby.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkxvfgv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltninyis.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaxwagp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfgqtmb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jreclmww.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2noostijp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yselljvk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxihsf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2velxcjdl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyalkyqf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcxnakl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjndnzg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2edxqypyw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hikfwohv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzumfly.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfjaagj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwoqqpg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcupacmz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2znnnkfxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqeuosc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeijogq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasxlnod.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkebvh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtzdyi.html


<!-- 参考信息 -->