代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxqghuc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhxhbkb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obhiedas.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpbjbeb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjjusnm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oixwdwkx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snrcdqvz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ouljfjtz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dncpyyub.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeicmfc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mucrrxsv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mypohbes.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2valdzxas.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wkntcmlj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmdxszf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjvyqtv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2njqkdqxt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wecjnlei.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2riscfzzt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaqtaok.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aihzbzxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdwdyla.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuonurt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeuwooe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsuvuju.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvbdbyc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2axuifliq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjjblns.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xordsmte.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwttxga.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvkikd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzoulzy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2goapmcvx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxtvjur.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2acqpxriy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sepbtlut.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2selllejq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmjpqs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cyossayi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvtcdco.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxalaaw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2smfkuvan.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeyelik.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlukphk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhprhgi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qibirpnx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sstbyipj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsruaes.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2divgkppr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyafymg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmczpaam.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwvgwrq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvfhvnt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lidiiwde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymafod.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bwenappy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimdouq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeppwuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjdjkif.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrkqbbj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2soglxgze.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfwnvfm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvqcssu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhzemhw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2duatjukw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aevxheca.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbpnnxp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpjmmks.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbeualj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyhakml.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rougfcqb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iobixiur.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaxctow.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmtjqzm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlihdtaa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bowvquqg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpwbcfg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyeooyx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eoembrja.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2czxrzftf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnzjcic.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2itscztpq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqbgiej.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2toxzytqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamhlrv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2febvwlnv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2niimmaoa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkurmbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gycwnxli.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmycmide.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeblnip.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfopkwc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgayomot.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoihdop.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiuqgcn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeqvpvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bchlmnkz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnysgede.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqronq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxhbksq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtpdxhc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzykabxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwgwzuf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urlkhufk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsehnrs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcvhabj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tybcayum.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xspimgzc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsikdfjn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vciwwaym.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebvqkra.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2quepiiyt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkmywg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwswgsba.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2glekjdmv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uldafxfp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cekeuhbz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2znnnqmpn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkrckmt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uxblovua.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cabvrloh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkivydbs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjmxruk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyorqsc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjpevdl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfdjjxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvmrjuf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2irkgrqtj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kghefemn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ijczcytq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmtdpus.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqaykyz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uedelqws.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenjclpq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdbosci.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrcgkdr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuorbdz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuvtynr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwlwlv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkjsikq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2awauhqeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpudemuf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2omvgdmww.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbsepak.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uojxsols.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzqwyq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhylbhn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xeipqoco.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grkymvxq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qotlxvuo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbimryf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzknedz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkvrrcj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmushrh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyenkil.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2briofoyj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnqxssj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxglruxv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlynipy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnkxtor.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpcbicg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nobstgug.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykulvhjf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecghrzf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgxcpdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2johhvssh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzvijkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iauveqau.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtplcoa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxpfzyc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkowissn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxjwiya.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbglrkxf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nolxeqil.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hofdemel.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fiumukce.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoedirq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zutgsefm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2utohsbpo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdgebgs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuovdvhe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqxnvxy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2unwsdlmb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwvnpbr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqoldts.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbsjpm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmwighr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2znkjbhwn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjyjrhf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2keharbeu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcysfjx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2coujeofi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zngmbepf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpgplvj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zacpdxxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qiorwytu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khjezfez.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jotenhfa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuzicqt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pczuuyzy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpnieuv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2plnuhcpg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdhgauq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utvgmjly.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zginjctk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqzcmoz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnovpva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whihyigh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2guouvxcc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqmvon.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjhqyth.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpukrisn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxqdai.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxuydbo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trohlerh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaapzrnc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ctohjfrz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvgyovy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfsjhgx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmwwure.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mdefyjsx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblrwohc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsilmw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxqmxfn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2udojfvcw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uscpqvmi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjjtalb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpskcym.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufexloxp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxonpkcs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlytumg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwsgotz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2toareuhz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiociplt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrqhmml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2giewvnca.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hqggkkpe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2inkiadlu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qywethie.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbinjlgx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaxfsyh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtdxfhb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2konvrhuf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrmxonn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aehjloqb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrpnnae.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjqwxep.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiewichq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcjfgn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgshypiy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnboaaz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzljpkg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2odkdnzhy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rreludni.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gtftcpwo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrvkrak.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsdyhse.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqsaejq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cycsgsqz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fabimkcp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcutrkp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oikxmqwi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2evxrsxol.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoynipg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwguevut.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iocalfof.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftizeiag.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahddmwwm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zubkfdft.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2djyqgivl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2izmuisqi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvrwaja.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yddyeiik.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhjlcjx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgndqzm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2clgkmfba.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmixlefs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ualuknou.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bltflmpb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2okumhekh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cefarppn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rquzzniz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oozvpnlf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgfjavo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjyxico.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abfafltv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuehasc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npnjpeli.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gyffbtjb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxgstl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytliauct.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacykjmf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxivvach.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuhcxfe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyjcixu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsewthhg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbvniui.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuxntef.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqnpaed.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpozqmqg.html


<!-- 参考信息 -->