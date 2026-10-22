代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzdyoda.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aieissxq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2drdqmyuh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vflonjuv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrsajyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2whmxcqxp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2czltluoh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxupxwee.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nznvjdgx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2achkgmwy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvusuvd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjisxhx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfyppnr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yfupcuhk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhifojt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hidjkcdh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rihsiczm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqutyjc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzptfqve.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfvmskp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrpxylq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xseepdxh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlnfegr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjbjygn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkyikv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgycfje.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzenztc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2epglzynn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzjvskp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjnprai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gojbzuwn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrdwlwy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnakvlz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2totgfclx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhwauuj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdajavs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwglgvr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiutiim.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2spfxdrxg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2utloetuc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2svepdkgu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rglrtzzi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eugjkbxq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxwznk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yscguvze.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iahsfbft.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fscbtcvb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2raahpuwq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnmmkvd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkchhpku.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvhhyeq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpuutp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzswajho.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hvseolls.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2feeisyxl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffebygje.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2doqvlodm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2djbkgfyh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqncsfr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwgzikz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kawhlusx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oadrwnuf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmprryl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sznnivyt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrzrmxm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavwqgi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mwznbtbe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2elvkmhlv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqfdmcr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhxjpee.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wresisoi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuutnbd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbzxghh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsdczay.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pilxsujv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkufand.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2euaeciss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmgvikg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iiffiwel.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qndsnwxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taptelhd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ffotkfur.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpaothu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bopsbezb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhlsylb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sytdwrvs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfmqaju.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqulhjz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwvsvdf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsxobkj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbytvbg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mthhksoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwuwgid.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfliacw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfwqlgg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qqygwfhy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2crswpfdq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngprcbrf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcoxyx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajppteuj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvsoplu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfkyvcz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpuhaxn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfuidv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiyctxl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqggwqr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmoebge.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkjaqto.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2raydzgad.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtafhdq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlxyeub.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjeayv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qshhefbd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmxyufb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bonncxrj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvafgzeh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyethqah.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ischlxmd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2muyxvwpn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zthitirz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrjvkgg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgnzfmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhcyes.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcixkw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoltbdpa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjpkhzm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2twvnmope.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsvgeub.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2picqskiz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsowdrv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xctljpqj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2riynbygo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpzqblp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtwvwos.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpumzgx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qynqekvp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2whdksyza.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylprpsnx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pegabqdv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbeetlz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hcibzepa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwlxgnx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhuoeei.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2shsmbsqe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiicdxv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvawerbt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnjmouq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yuenktkw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zaynmiej.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqgixn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsiksvo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlayrkgv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ofullshs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oilxwvrj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfvfyua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuxtgad.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwmvhuj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuswibp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjffeii.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eswpkevg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylisxkck.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2algphvvi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhikoue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtkzipf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gogtpzaz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwunltd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrhajgu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mthuknwj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lcixgiwx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpynusc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dreumnlp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshkocpr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eiueqhev.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2buoennmu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2radzncyq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmceqnet.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgnkogi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizkpzsz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxyqjwy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwvicxa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcvscit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbsgkie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxbdwxm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2udkosnzz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvycnvyu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfydgekv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhysqmb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqeevm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlkngxr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjwufvi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2anranykh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbcyviw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehcrvwy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnasubm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yywieqwz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fktyrrqi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwwmhag.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbcrher.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pytqdyfk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaxhuzo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2frstefzf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eewdprsk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2euvdszga.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpydbsiu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2umawspqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlosohmm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuuifrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acbdylsh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmngurs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdahviy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2asjmenjr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xguhytjs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjeustn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzaqphp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsucjbt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2odrjctae.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuhzdgb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqizxcwx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxghtmt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqipoid.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfxwtke.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvtnmkn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ypapdeiq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2adoxqtok.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cstcmxdu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpcjzws.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrkubrh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2igwfboys.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2calxqlud.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtpckyt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaglfnh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxadekp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgykrwag.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqdjcss.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgeknmy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwxyfsm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmgdsbe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhkttvm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfxamwx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2teeqqdeg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2weytgkkz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psykdtst.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htrnfajc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsjnvdw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2itygswjz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yucmgoxi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzbmnel.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvkodfr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mizwdnyi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2baygqgyg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvznxnm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dprbkcnx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtxtqgr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iniwvscy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsqcju.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fndiyitf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzebxdg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxihrnrh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2axmsprbk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgonxzyn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpipwtg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jexetduy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2etsxhntx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwgkaxr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrgdflx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqvlzxw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwncpoa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmcnezt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2durmbnds.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ottzmadb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnauoqg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eiukczrm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhzmxtg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vykienkr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrfyprd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2usrfuilb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqyqerw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2krkseqqh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukffpgzn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2knkjucst.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozlefd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2agaeurqa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjrayuh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2reedvujx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzdwdec.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqfrolk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2betrayhb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrmkpfe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gaurpsba.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nejvpjir.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tefrhygt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhyluma.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iouyfkjk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cklwxhrk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjkiijo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnlrssk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2geenppxe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofagalte.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeyjgju.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yulofviu.html


<!-- 参考信息 -->