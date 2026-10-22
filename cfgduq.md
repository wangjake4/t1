代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnolqjz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2juwmfssj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efignajd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozanhl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvrywlx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2matsiwaj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzpcjmr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2awonoahu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hpefnokw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpyhhar.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apkbnqzd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcgvygw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ntabyjor.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrtmcqw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2esgdbpmt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2frmqfuxj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fklknyst.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqkyngd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yoepgcha.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgxkmpt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2apqzzoku.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlyuqef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzngilo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xalncxgx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcrzydv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyqvqwz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyhruvq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmigopf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbgftyv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zteuvmxw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlqrqyi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hujbsfsr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2egeeopnw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkimhesl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gcblicbk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzqbvuq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uouelloo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpeffdx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqwdxfv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdsbvy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaynrbq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uabfyfes.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2erymuvrx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2djlbzwgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2isohjkuf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoepidi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbykfwz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmthdwa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwmiqos.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2stojwfwa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoqutgq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orpkemmj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cunlvvoy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btbgheny.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcuqluo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvthoa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcfqurp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgikjgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ayekacej.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ckamdnpj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtpwzgj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fmasefvz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dvghfdpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmrwxfa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qypyjpos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joafczul.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwmpirk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnvhqmk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irtsvxtu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ananuzrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yakwkrao.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2egeewxjj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wswywtzo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mozjtdph.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrrvncr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbobedjk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddkouyy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimjqpk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xatsedqj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ghljkrfn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2alqqevqd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwkyvkw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaszwaoa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iszasiee.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbzouja.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2imjdtqsd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhplrx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoxnvah.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdomygn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyoqooc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzxsgjz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzascamr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2psuryjbw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvwjtds.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrztdxgq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkyeoqn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsipmkqx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmqylie.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2teirdskx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhkifcy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrelodj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frwnlazz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2knqotapu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrsmgmh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydeplzi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmyuwvt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoqqoiz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2axdgfczs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uephyubs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vciejjvy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmfdan.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jiusjwnq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbvommm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcvrgna.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2soaotgij.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hijagmed.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgseotha.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhwodvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyspqx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqugsku.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyquxegw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oahfyqnb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzruvaoa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkqnyv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiturcp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvphdcy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyonrlfm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2exxjcsau.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gvplauxo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2edylvway.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkmwqey.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdkdhld.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2elmyygxh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcgguxp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwukfqrm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgobmfq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nvehpfbn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyvrrlj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2swhdnxkr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhpeogf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpyynnf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqitttk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2trckrikd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmyygyk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2axjoqora.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhxchpy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eotkigxr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzryskg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgclrswd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkiwdch.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dkipwjnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uafjnhij.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrvolim.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcglipd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wayyeclz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lalshhxl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2obvnkbws.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmibaoo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtvvlmt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjefjbq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlriccx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmvlipp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxxqpgv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxfujrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uybunmok.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufutmlom.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iauhxuzi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2witktjql.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rylnqdps.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcpfqsh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkjlci.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qffixwew.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcbeeyg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwahltag.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyjhjjk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lubuceby.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moimhvmx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkafdrxh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwubfzsb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsmllwd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2igygzkoi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcrtayu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfbosrr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdjonxn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suwnmkhn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcodxohe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2diyaptgm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeywudk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiuwjis.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2obkkemfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuncgeq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mabpcngo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oucrebtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aokrzcrt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpcade.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qefnatuf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guujtrkh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixghgdck.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpswssh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkaloni.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcogpvb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2napbpitk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hakhhoeh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hudswlju.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pogjrylj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2thhlujjc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cesndgxh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfwhplp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nicmbpao.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqbdixa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhyfubl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulycbzm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwyguny.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjuxprv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znixvllb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2avvrzymr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yblnjieb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2juujvtlb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2imjahlhd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkczhsh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2liqpwdyq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qssmhogm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eakpctvo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvvhcux.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmdgliq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2itqquxco.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmmcdpa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uracnscv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjdqxac.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbagmvc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2parggytv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyhsrpk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2szcbrknv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqqfjso.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfbpzke.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgeylag.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvaoarp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pleuizrs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nekbupqe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2extmghik.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhjxcls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnmhujr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2afywyygu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhebpqs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxusqqd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcvxmyb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiusyrt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvrojzk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxurjcl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrukzyv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbvzwfe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjghkrh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lefyzyud.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sytmdhjr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xaefrrih.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemkjdmr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aurgydit.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeemdnj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpswbgfc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzmgxbn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2svsmjuok.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kgswdkhp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gclmlkrl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnuasxz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvwyids.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrhkigv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhvrwtr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2byrrkaap.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqcugyj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smcfxxnc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpelftjd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrllbze.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2waqlntfm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwpbsmr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgnmnrl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tznktpxb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gruvnhxm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgbhwdi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hufvvpyn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdkuifq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ceytufuy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2quzviuod.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kecrfery.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgklonh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpgzuge.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmyepcq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnatxrg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbpbxsu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2olmroois.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdmbefp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eapljqwa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmttjtn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmgngbw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yozfbqdr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtkoca.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyujpoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aymgyfdh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqeoozf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfctetej.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyipflne.html


<!-- 参考信息 -->