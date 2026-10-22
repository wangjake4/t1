代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aaccxlwe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxpiedf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfdfkjt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyutepg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lweolhqo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtdczgv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrzsinv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pizsucxz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hasxvzsg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdlbikt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbakyep.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2egsytlqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xkijhefr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hunnfwwz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuidwsfu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwypep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkgblxz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmmhxwi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aktwliti.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2swneizmj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzhvvej.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwpzal.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzavimg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvjaawe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjuogcz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2foxletrx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpxkbxz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjyecal.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgcucqq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjopxddg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2afwgavkk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jzefmtao.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtqlhma.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnnybni.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaofqix.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwvbqbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwsczj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrmfeiy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbuekml.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiirddf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbuwvdt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpefdcro.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crknurwp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjllbvov.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qajhbhsv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpezfyv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgpoezq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnpaqxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcqmndl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjocgzg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epsblimv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtqjtln.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcrlhxz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvcxquz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hksukvhf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pofrhzil.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjmesom.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkegpasy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pwisgqwi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdhqjuw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxykvm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjsrzus.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rdluefqn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnsyelf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awtjgqvp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cytcevvc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tebefwce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvbufgg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vneyzgkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amszoxoe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzmieao.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2udgzmidk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgslymsc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmgjonz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqagaph.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nstripha.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxusigu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgozjpiy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2msnwrikb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfghhyu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgmarbf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ailhwlpu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sespmeqs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fscxjeat.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2swptzwjp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhkcmiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpktsjuz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdewnqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqasxft.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbvrpin.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2emvexfpg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqunhy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdranyyb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cndnrkui.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcznmjd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqgsomv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2foqqhcok.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2czcuzhoo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2irtwhpjt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hxudfomq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yedomwxu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznhlsw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbbbfyc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjzxgxc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zodjdqtv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqdxqrh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaybopti.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqfycbn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijphztyy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrguxtr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eywfyxug.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ceccjqoh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuvssiv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvbkolg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrgroyf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoudcgp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgfuxls.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzeaadg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jueuwugc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mylgzoxd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uymovaca.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkygvts.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2havineqp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zudyebgk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tacdpwul.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uedkvmpf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnzkxou.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjxngtf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jndhoufp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnuuiux.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswlmmsh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gckxgoev.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxhoidz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsrmami.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyvenxi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsliwo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2awgsyamf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpufuwi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqllccvs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtnegew.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2coylifjb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkpfgeu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fncrteip.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuxmyrx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fggqxgyf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpzxomw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2owodhnfk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyubner.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjhmdl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeqcnqq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwgntxx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwajqar.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mlksnksl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vibcqxzn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2omtleidu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oahijztc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhyyari.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofokumes.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiavxtu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2srmvkzfi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqcwoep.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuesvch.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rccljjxl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axipgpdr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxkyzld.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2auhvddpv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzcwsfa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvybdkk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgmpkbi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwesnmsy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiccilp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzilpnsz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2udskqqqh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhkijjq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqniihcn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwihpwl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlzlhsm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuitiwq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpciock.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2enpspeae.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rutmlmav.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2buunifef.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2papfsbwv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxexqlv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhuhrsj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xazbhfec.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqjiyt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2epyitjxw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdzuypz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsxizgd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmydkut.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2osyepiuo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lffnklmk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2csuhdyrj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2avvyvfgw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2naowxabd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2guqtttqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlycauyq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cskrbakm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkcgssj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbxtwuu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2horrhold.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmytwip.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoijeod.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pkutquxj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqizwdi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oywcvuud.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnthjbk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thetalxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phlrgpgh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xshslqsd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcmsqax.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdvphqz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtpzwyw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtorryfd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aefdubcb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swlqqrqf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eydduksb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jblekywa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lctmpble.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vryhurxt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xacaqoxt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkmcmtq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxozzeu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2itabycuc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpphcmrq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkptvlj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudfczlx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvefxos.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxascjz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2leznlbhw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfidkvfm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzchtta.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brinwdhk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuweqvn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2aegyspqh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2otphxxwr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2otzkovyy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfbzycn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqmvlcc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcacgki.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwoqsca.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tchopsdm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmfzmie.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxodqqvy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiivfgox.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiyywam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeuwhux.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlcppvf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbytnbu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzcqzat.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgjunfs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcxfwju.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jttrbqjq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hckjqbvs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgnzce.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igfkoehw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzoqdc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzxoqeb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqanfzd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwgphgi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wquexymy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2celbzdwy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nuouzjxe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2flrlcirn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vqstndrd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gblrsxis.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjusii.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2abvryyyv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pseaiqmd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uldfrhfy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dekhiirc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfpjbjm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuwerth.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcqgbcd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyikkek.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvisaezd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuoitcw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjtxgnt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgjnhh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dljdgbha.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuyfbcy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ychaagej.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrqwkcl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhopnfei.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmizyon.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2biutrpgh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmunjuo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqzsust.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dushnhpz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luomivhy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwwjgob.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkphwag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2salhseee.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bupcokvr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhxcbku.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsbfaax.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oafognpc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emukthve.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fricyisa.html


<!-- 参考信息 -->