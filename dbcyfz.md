代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2veqkwmsx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2llltzyyf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lbinzlel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qynwbsrm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqufnit.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eclseahe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cyidmucu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjqxjmn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2reozmdez.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjvgdmc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2izdgfcag.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oflkwsyy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lphtaalf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdsnqmo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyccdjc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwfyyuv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqthurgg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wdruhvqo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yryzwevv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdljiby.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrigwsj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2inojvxxe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2owohiogv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yebgspud.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2egdihkuc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrqtvot.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsnnnml.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhciterw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzrioxu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkwuyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uefcuuva.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anuyvjqj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgzifq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcqrbzz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glgikzly.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2imvwvacs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bubtlail.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnadhux.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vquruggr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ednrmzkm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqsgaeh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2httxasun.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acdylkgv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxqsrz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jwssbljj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcedwjsy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zeidlnzi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhublfy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmidisb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxmdndh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiutshx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnnuqzk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpyuwi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzogzihz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjnrweb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdqxhe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvwnzxl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzltbpj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovabwojn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjsfhom.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qxquciou.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlrfxay.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsykcytf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxvkulw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2attoyius.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwjjjon.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uunnmuqj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2knlgjqxf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgcypno.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjyfcsn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wokhpdyi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkwnypq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrlrsrr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwoneon.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvkbqbm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhdcgdc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2moyxtdrk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tutdruct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rifovued.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svdcsydc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnnupci.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lszjeydb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwaxfaw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmxzutx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaszwqn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxhmpoo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xclefuis.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2swruionn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmpqfrf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nfremsgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmefyez.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmzjjc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obdxejsg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhaqpjv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gclsbndq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcusbhm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2orpzaoqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aajoblhb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvvogef.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpryvae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlfnzrt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hukalwbx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdboeraw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhgbknd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlezewov.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kijgkzqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yopsswfy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuehlec.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeglrue.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2myutrxvi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2chigudpx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pleyypbp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2guxnifhc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sacsqyyv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbkkash.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjlquk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dsctehpi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxstrzvn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbacwztp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pesnotbb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcgajfz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfwpnbc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvzkyji.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjylrxy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlymgrie.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzcmuvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jigwvhyj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ditujdby.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqyxqyh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbdejyx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvsfyay.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2imcxgotv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiymoyh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvdpysr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpwoyoy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xoorbsdk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvdduth.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdqfasl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gepqfwnw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2crpwhimy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcniall.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dclhcang.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlbuxh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeoupkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbbhlwg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ficfbgwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnejkey.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcjxjwi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxjzeiv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhwogsi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsvwrce.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xteadnkd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhzlymg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcztjimi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwgnocz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvjuxeu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgvpgsp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgwgyls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjoeooo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kszbupol.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyrjsuw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2abweqpes.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbiqnqi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtsjndg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2poequaoq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsrahoc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2siaeblny.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdztzuni.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiyguho.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyugflde.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmkkwsp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chizhzbx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nijdgbqy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flfpjfrc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eupykngw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlpodbf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhkvxvf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evncdnyl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aedjyxsf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlicwhfb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfnuqxj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qaomheht.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqgiybp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2beghvzoj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exdmkdue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eedthaxx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiqsfnq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcmcyou.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkhwzdd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwgwqe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqvddwv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqeqplr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnyorpv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaybtew.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2afbqaiul.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yequctqu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vuveyycx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vthpzdja.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jytesfgq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2suoxdgsb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hupdzsvp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdetrsz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzavygww.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsiqgxt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sertzpsc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmquoibe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmhnls.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2artcnlzo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwpicd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aigwxxjw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sajwdibe.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrgtzta.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewofqwsu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2arhdgxfj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlsvbsv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlotqxx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qajqxqbh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmkevqd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqyzphs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gamycowo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwmilhv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2itzsvdkp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pippdomo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvdmxxh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2avxgsrxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrwriuu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aerzjqqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lntzcaek.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfqpljj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uymwasfc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvgbcyw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kquxdxhl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jxadxlfj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvpnwbh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bskswzxh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgsrjnp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tswawypd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwmjuex.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mbycpoqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvaexyb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxybmlu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdorpmu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcbbdlc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rthkreen.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiidelu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbphkkwm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuuuush.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2levadrsx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2flujszrr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2msmvzipe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oataupxm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bizrdodz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2allzltvg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adqfsjtu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwyioo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2euhkbpkc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lzozdyog.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhviwxwj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuivoaa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkvuqne.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2myyzuxyi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnbesim.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jekgkrnk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtvcvas.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyakgon.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nonsserf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuxsrqq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkjaloa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elaypvas.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntfozct.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cddvmltk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhbzfop.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvvlpqy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sisakmjx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nsofnerb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhnumgt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsmbro.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjyltrj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kapnrpwl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbbpuhy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdoytkd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdcepqk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuwcrcr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqeafht.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhdcldu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlrxkja.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cyphhbhc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqlxrsh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tgobpjau.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvbsfnv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqubfrap.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqpzsm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2etlzonxx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2phcovxzx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lggugupw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kczzpjmu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sikccskw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsjcvhu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thpdftcs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqihdup.html


<!-- 参考信息 -->