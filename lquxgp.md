代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqftlbd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcqrtqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2suxgxifh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2btffnjfz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwnrupb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbjlcaa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmcpjvx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cntskrjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gahkbuhp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yopmbojd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elxdqqxi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2thepejfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjwqrlc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxupxjmt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqdeguh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwgrxxf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsafrmh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idozhxnq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbndsgoz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jezuiafx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmndehm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfjlguq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmjwtmy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qocidijv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ytupbpmx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whgtcxqd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbopijx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ytofqkwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvddeeq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvmrqbs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sxroesln.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjscepq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uktvelqb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjsota.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pesmcrzy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvozlvt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjjujgo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvjkqnj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2umntwvgw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvyaiiv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ravoimri.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jriiwkzv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzzwabg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfyuigw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwmhkzp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfctgsq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyeujte.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rebccpfv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2plgxizhs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqotcmk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzjzjxl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhlavus.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwhaonx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gktocdrk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdewtmat.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xubboirv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnqofki.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iiizednm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkxjhrf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykffbkqm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uawzidfg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bugkutpf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aiftrxoe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iogvbejw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2snrbqnmo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhduoss.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpvekiu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqvqkif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrashji.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2deczkewq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojjvjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amqshknf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2crgihmaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeflvfzd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyztprwg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hejiixka.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljgzyjx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtdiaq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorufqxq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bffwvsdy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbwjmxt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gmydhsne.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxnzrus.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgthqeks.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyitgjfq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2przaffnk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ijskfgji.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cbabjmmo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjqatxs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfpbvmf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyytjxfd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxwicqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcqucv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpfylyw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kseqdwea.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxwaeay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oufoxrvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyomklo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqhnunj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndftmaxm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgtgqco.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iewsmwyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfjdyyf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cdseuduo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qngyplhv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvzitfc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvwmtfg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rnelshdr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axratihr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2movsator.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilechjvw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azmgqnxw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxmxrlk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrelxdwv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wobtvcrz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oukizjkd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbjtygy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uclbmpuo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejseafnq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xokjzrgy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2auuwczyw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhhxtof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fekjryuu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cezmzmgr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwijxfw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zenxhbxe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvcdfcg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqzufls.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllejzxu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrnxdfl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhjbjo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auadtfzv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbugiujz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjdhfo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwcqcgu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zazdjsng.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmwgtvv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nltniouj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwabafp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zevgkxxu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqkvdrg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaqxcvk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djzmxfsa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwgbbkr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgpaich.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyowybcu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpmzatj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maajudgw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzrsrad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlasggtn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ciivldue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiczgdk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjvdno.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sryacrff.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lejmcyzv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2issgcsxf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfqnipt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ttflasyq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stckbpnf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eienaktf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqswzgli.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnxdqwl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwglfyuy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxwaiot.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zxztuixv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryabiwlt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qbegberm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspcelm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjncziu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txcmzyki.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kngfcovt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trzpebex.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnitagns.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suegrgko.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeogqjhs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzgqqxh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsksmas.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2repihuim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kznhovdk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcjpolv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoexjroq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxsjfiw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xaucbmjm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xieaxeya.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznrfzdj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gvublwsu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxodqdtv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2guwpfskg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jisivysp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2numryalo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozepmppm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzlysvv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsbkpln.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iphciudy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2axfwsmuc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2touebwcw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcojuiqi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnztbdv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqayspe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlvmeys.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oykfikwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjksdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqoaimd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlnlgit.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzdrnli.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbhglkl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jymwotyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2skrnvtnq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhdddzq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cldenlms.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2icdsgpib.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gshlhlvt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slrtfsso.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2thvybfcd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxvpmij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdwmwh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zopurkge.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtvocvg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ighwkjjx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfhrhux.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smnifrzt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsksvck.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmupghqw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpamolwp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfzopjp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkzfylb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqycigx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnguqxv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2daglmxid.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiocvog.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2klegirim.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntjbono.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kghxkexm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnafzjx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nimjsjws.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqpdbvr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xptdkagg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nivqhlgx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxixyui.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxyrcjq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2scmdoxjf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqgwtal.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwwfnsk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqxkdwg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeblrlc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezapbyj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtqcrgc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpcaids.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qavvupfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmgacwd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhcwrgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjntxqbj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmwcszo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mljagmxj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eajphlzo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrvrjts.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuafyyj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2guhzvxvm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xyghypqm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdscvzz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkegova.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxbzwix.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxrrhoc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2suwjqqnc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uyalfgrh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhirdkyg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prnvsmym.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hirumbea.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckslwrhq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmgtsr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwjolmz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcqhsim.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkfghed.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yclzizsp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpwfnuu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxjwle.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkqjxsd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggesqmgi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpvwfhx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcsjxns.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2buztudsg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiahjrcn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxapack.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdurkwbt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myphbbzw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hafqxyst.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjeqfjb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxixzyqt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfplrap.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcmvrjy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsicvfwo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdmykxi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkfgapg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abazeren.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otgcgenh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeekmrar.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mnghnilz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvpmkqf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjsekxx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfuqtoz.html


<!-- 参考信息 -->