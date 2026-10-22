代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrcvztv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiajknu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whlwxhzz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqrormf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmyqszc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwekdhr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ammeospc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2srkrsytk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yepjjmvc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exktxiyi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwirdkqi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bdswijwb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lstmdvem.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbmvmkb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2quarglfv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uryoviim.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsbawoe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsswpbn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkzncqr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sectzoky.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcrhmgw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2filgbwxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hcthrmzw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrmznxt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhcusqm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjgrtej.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cethikjb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdidxnxk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2entowbyw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbulwso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmznhjxn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjmecvx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjcolrd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2boclzhis.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrogmrt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaodsrp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfwvhub.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjnxzrd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryglifvg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ympdblxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbmzqzu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoiizym.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2onffhwok.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrsycnq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2asjnoymq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2faianymt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfytpss.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2graaxcke.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zagxskdi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2infkyexn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gevwtfnp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljttfzrm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hudvrzye.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oalwyfsj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2htspzwke.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifinuq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqhutas.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2luyihzsq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuwkczc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qkghwfmb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlszkaxe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyzcufz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2elsapkyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrezpqgx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsbdiqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2torqcyxa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqaanad.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fccylxxt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkaecxg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzovmgl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2efhqeubp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaqxyes.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpuxezo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2agnpjmhm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdbjmb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrxqzrv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzanwuqj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoiqegx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhsprjx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxreqiz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmgkohm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2naticpxj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2olyhkodo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpknfriy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzbcecr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yemngmze.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2shknuzym.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvvtzph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrjvoyq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2keymgcst.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcnklyr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkbevz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvqhkff.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuopbck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvpkouh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrqgfwc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2adqaedkq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfelvhjm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yipcosat.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2liotkhrf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruewxpil.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2geypouod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2momkylnr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsykdyi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftvzho.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2khdiwmym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwipayo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpnkmqa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2agoqcvdj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dychugmy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibkfhxk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cksqwlzv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqpxheq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgpmvid.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiguqrlc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nclsodpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lljsprvr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybunvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhueetl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcikhce.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbskrupi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyfhkim.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbprekuu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyglzqk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnzgvqz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnlmfar.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvqlvox.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dzguumml.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tiutyujm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xstemzbk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2twsyfuxn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iykxcamv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wamnumar.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krcjfrnd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwuxasz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wezrwgdr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwggkbo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkumdvg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2inhtbydq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsjneuh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xugfgvls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2icahmjfm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2voflkxat.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrusuvih.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgxjjkj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmbqyee.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ouegpskk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sajrdylt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pelbisiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qvccjgmu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2akccrduk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzgdfud.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdlmcgr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yajygfoj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrskymbg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xplovhzx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvaxew.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yerfiiuf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vozgwboy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wckhnmmw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2duehhjhk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvibqjoo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnlfvxy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfnxtdi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oavacuqh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfqiafr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgpmjzg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaazkprx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcyntuq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjtnvjd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2brqkbtyc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdtxzjp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyccgjem.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkkteit.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbvheuz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkbvkks.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqyxqaa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyujivi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfzrlkd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhbhsqi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2poqljxuq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkwcjgo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnchkfd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcpezqe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtnivyh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nexgwqal.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrusexl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvaofnd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhnnnpc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ofntckom.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hocvjisl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjnzfvl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghpttb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svsgmuos.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2diujckmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oflabcyj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjriyhk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwlsfau.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uofoofzj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbukquw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iigruujz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkelxhs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsfciwu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnutdds.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoyzays.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpdswqd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrzinrk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsasryux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmqoscs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmjvbqu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrkzmba.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmesmxe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znwstfaj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrcafk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kffyhzll.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwvlxnq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynctevtp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhbfqlt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsbnefp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eniotfkc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2whkvuakh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapmjfdc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzacfln.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsxnzpy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2axbklspa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjndjan.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvonxka.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqdlmwc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxnvegx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfeutj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwkihhi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbhadaz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iliocqmn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdcnhsp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gerdzsxy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmtmqfu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabvuxh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfoxmse.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmczsxog.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfxletc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idvjkzkh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clevjqli.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dqczixsx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qixpogks.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2emrxbtiz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2orxaeyjr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnnhsjl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkzmchz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmsaehz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcezeric.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aignuzmk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcuepxa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxyxuan.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hytrckvo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rntlbvsy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbggxbu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evkqnelp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtioctd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpzqcdc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2faypouhe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eueeildf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iirzqvok.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrayjvbi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mltxkddj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwenrnq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aprxkywu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcqovmg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqknqsvz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtfdweg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyfamqd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtijvsm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgwonyo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymerayvi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqkjpav.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfuymxu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwzncqx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdhcpll.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtprfcxx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbbxyla.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzrxuh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cndqbnsc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhplqcc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awkkwsec.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwaztmg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzipicr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiuwmtf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2breweasz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arcbtovh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dizegycf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjosllyr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2opvnchkx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygurlznu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlzmsdl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eohyzxku.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utiizaka.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiinosra.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdabxzzm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoyuzpd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsucjq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzujpin.html


<!-- 参考信息 -->