代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sibmkwzn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoxeqoh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvkefkp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvylujq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2quwyegww.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2njblvmrc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwylnnjg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pouhmfuf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhjdnr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2viehydkz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclyxyl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lrchgyyj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2seliphkc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dytkivkl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkrzzwb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tftnfqqf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vojdgspb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dlykdjhp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2huuolwpj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2waknbfbu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpbhcdu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvikpwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2osuhfovm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdnisqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2anvjdtly.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwnedzi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2msbyqlpa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2etiinfud.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwrpbzx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mymkkkxd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpsdmhe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbklcrwz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zcszgkey.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhsiczu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qumbuhux.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkxfppy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jexgsrzz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2youlgbsa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iugvhsae.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oitgjqnb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbkcwpd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxbfzhb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qokwadzv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oitycako.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbknkh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvtywcv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhahahh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qrevybxr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nywkpdyp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkaufvt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoffees.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yncpoaik.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfwvpss.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxgmvil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmeykh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etbzmlwn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmwnpac.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uolvanaz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ksymkgak.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnxlldl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2azadnusu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nuagculz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxyfajn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ganhgrjr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfexjqn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wtncprnx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xkghusyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuynguk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2trihntjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2goioexxz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxpvjx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjlypdo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihkifdf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwahjgy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xflkpuwp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eizneafg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqxyfjv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhgsxfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oilibpoq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2papkdmfe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phgohlxb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqwsnlr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtsvzup.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxreupj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jozlgezz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fixoedpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2olhrtrba.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvewdbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dptjyrfu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfumlhk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwkrriu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duazystj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2axyhuuzv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mowyfpde.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2furtbxif.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2forhmtuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjnfuqp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afbnllki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwalshv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjlxkgs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nonjvfqr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2odpltfqi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mooqborf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xsojjoaz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pojifsxw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqurczz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcarsrs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtidpfa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mponagsu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lyydvhdq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2csbyxhlz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxirkjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscwcsi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjtrkwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrippza.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxkates.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iecosivg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgjrexf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mglkbsxq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyyynki.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2skzbzubj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtmdts.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmqvpvb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbobgls.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2upakixzx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqhnxns.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocesajs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjxqmqg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdzfzkw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfaomaf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxldpb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2roclvmjd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyncbzs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhbxvol.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrttdte.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pffsxgey.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hdspomdo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzblvbw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdopctrc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctijunhh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmdajeq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2isbgthst.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ormnybxa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2simoalge.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjwnuiw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvxmldu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjxoqpm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmhjxen.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwekvat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cigaftjf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfozzjw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbodxng.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbwcfcy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdmqvch.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcbjzcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlaxvyr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cphvmndx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmttrmti.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mucwfiyf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqyldod.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lpctafjf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljroozbh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwxmwvy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgtehxp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmterma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kndiipgq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2blqejjnz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqmqsss.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onwlqofc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzufbvu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnrfwwq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uejmfcnk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xofchljj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoompvj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqckba.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2szddgxdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yajcsbmd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xccyqpjc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlojzkw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2brydmmug.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqmynih.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yysdhpaw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rueezmwu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjbhxkr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuvrsax.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2drmgtcwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2omyydrmo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rywypulw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdhbont.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yezwtddk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtwnovf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiatgcb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2npttesbs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wroqaqxx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2igcqgorx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnvgieb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbkpjoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsacplc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fejoleoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpenyluq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkskxbcj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvmvyfd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdrgem.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkbrnhk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcqaxee.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbxtxyq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2drjfffkc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2enraajnm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlwsfeo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlgslxb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2anpwmihq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxtduvu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2saehlxmi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqbsrcc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfxrjnm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblqztjx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgnqgci.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vluqedln.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sosayjqf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjwinrt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaawtqk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nubcogtx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bozfshqn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzwqfhv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrvjjm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjayutwv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdkevub.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdbaudt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hkozsxyg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffqsgut.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2momvrrkz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoqiuiv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2snxkvjkw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oftelarg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhrcugq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvylsozd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uvojoglo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cncgjsyy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltehcswv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopyaiu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmcsxtu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxvdxrf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyrtybm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjsbygh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsuvmqb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevgsfru.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnoboy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fltwqoys.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aktweirz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjsvfat.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lockkkqw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2unrnrssv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bvivghrp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvohzgo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sntthxwd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhcvexq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jkutness.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjpdcvf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ughuhtyb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqbrdlc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lsitbeys.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gogkigyi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kuszgdom.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xyekwhdx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyhxgyt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vctiunff.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrzjgwi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxilryn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhulxqw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlnwpyn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkkqxoj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2esfsapjv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzidnlq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmflztuf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyngsqow.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkgixlr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lemynolk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuuyhwm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iasoogod.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzevzcs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wystmdtl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaoupjj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2guiekwur.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueswloll.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eotrngns.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnbcuyb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwayhpsa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyklort.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kidhcnfq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvgprc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sukruzqh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjikzd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2unsdsfmr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flhzttsq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwibghd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlyuzsm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbquhxqr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbebnjp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpvzkxv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2acgqiahy.html


<!-- 参考信息 -->