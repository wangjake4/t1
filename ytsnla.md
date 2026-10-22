代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnepdaz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkbocee.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spbwprwk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzakvye.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzrpfkg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqdehbr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzidtctj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfqqbni.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oetubmkm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2drefmnnq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcxzllh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpzjcfu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aznphgga.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpeujiv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2daybzdif.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rhylmxqs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ansfvmvn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvzthrs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrhcqck.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bduuokqh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgepruc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icbvfaqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyzejzb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uphhijmw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lihixrkr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nozzugux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcykpxp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkmukji.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfvguv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoarrcsc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhcoadz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivspvvwh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2voyyfeep.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtlwwgn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtatqtus.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2venaumgj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eudymmui.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtfeksx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2poprkdis.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwkhkg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgandp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pioolxvn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfrxwro.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdopzmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdrltgu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2epzfpkea.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqacogn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgowkkl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbtpfog.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdvvful.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqellybp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twhypmnz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gnarsiwt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tavgrajq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bytykwyl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjopcb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dshqbgmc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkqjxis.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2whlolxjj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfquycu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwynza.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwxpqsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnjcmp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2asgvdlzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnawbtr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcghvgd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnktgrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okkprawy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2chyesccy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpqxouj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pstbthan.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jfopwtae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfudiveh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqnhbuh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2semblsdn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnojpv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdroucin.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfntifp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnywsok.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzkuljg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yccjiupk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfhqnfq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuiokti.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mserfecl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zicdxrhv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnaejdg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqibnbw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxhpmcw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrhnpns.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oniulgxt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxkifx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vximrbdr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtxdau.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrkhexa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeqttij.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yffwmkyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjejde.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdkkfpc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fibtdywn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iecddcxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ussemrny.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouonvypf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rstefspi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuiycsh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxusfqnz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjjtoln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgolqjqo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lahyykxf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbaajqi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ngenobux.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ortnctyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2atqlgzzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictnonot.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqttoc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsczuspn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qrblzxrn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2orqcezml.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgezsmx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cckoioss.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lntitcwx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsvpimh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nimrzhcp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxizhye.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pivzetxb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eharrwkm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwikvcuy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxznepex.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plmtbezh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiblbns.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiecfmcz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlymbka.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbsqwvq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxuikzg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyorjjy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwzefar.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ajphqkbf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yrremvhr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joysqzcn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmjrpuy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlovnezz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrncvmq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfflmlp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwsgjqj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfiwykg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsflehi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjavtnh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcdrmuy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irznddhc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cydcxuhg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uysemgpm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ooddatqu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxeekrm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmhwpz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2spmtnkoq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsiaplv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wywhnxvj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iutobobm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhnwsq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anagepdo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aggsuiuj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gnltcnbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgwbqbu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ycccmhsx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxidoaio.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzvkhwt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnetjcu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cltizybt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnacrnct.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtujruvc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oarrjyuf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbfitui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gebwfnti.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpdlijl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvrukwt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzmrtkq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzftzpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vandzkik.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuwcudh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2azffnieo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2eedzilve.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeajrgog.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtagup.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxilstqw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2btllpitp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iamnaerw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sutxvaln.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2brhszzyz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2boefsdfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oouevpdl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sitckwet.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxnymrz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2umneidqg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgfbyfm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2crxngzhr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmfthai.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgxwwju.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxopfvhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gztbsmvm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsahokg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtundqun.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuvpkvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoxaxnn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bggrayye.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2plgikgho.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2chnspscv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrlfsjs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kumctokk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpuuhid.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ewprrtvw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvfytjz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2snwtqvrt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwirpkz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qckexgrt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgwvwnp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oynulihx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbtoruq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsygizp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvoyrqf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uumjwazd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nayomkeo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2stxafqau.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cewrhshk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ireurraj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnwwesi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uifqhmmt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyrosdv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trgpftwa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnazrwo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiygqkw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbbjmjz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvuzqqc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfpizdm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcyinck.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyubeiw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeirhzgr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfctbjxt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pplfzjpz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexvhldp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojywcxic.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfrtltj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2poajmuxs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2admlsrzp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gtitqlfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvjisav.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlysrabi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvqlvhd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcjcdet.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyearvni.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fopqelyr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwsjrxq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qoconagk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2imkemiyv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltryrhrq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfxddib.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtghmal.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjilyzl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxpbhlt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeilyqgx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2odwctdur.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqwnwtk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utemodrx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zggpogou.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hearrmpj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnkbtqb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfevfsi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrtkqcf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpclvaw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wftkrygr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nluqeeee.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ceteomhz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htspnkil.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkbjizt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihaioz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2miezycug.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgkqrsc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrzsfwb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zfogvqwz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkvcadd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdcgycl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzxxrw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slxhgilb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbdbqzk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sudxowct.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dioqfwpx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcajqpup.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2maxllivx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijarfk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyxwvmq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fszmopvl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqrtycq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pbetwkuc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgvzmau.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cactwdws.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnsizki.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvlhofh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmpbckg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkynxmfp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrqthku.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnmwrml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftezhdqr.html


<!-- 参考信息 -->