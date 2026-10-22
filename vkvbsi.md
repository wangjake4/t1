代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqlylug.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmrxnmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mwckfboo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiecdbo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtglmqyu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2egansobt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2syemdnxu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyxfrcw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkxphoa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbuhgzd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbkjwxh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgumeqnh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjgtkgz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2twpnzmvc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vycgpsys.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzgvpfa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2obpzfihk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnznvyg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyeagqp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prwncjgr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uflbkzva.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcvhspv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsjbydy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtziiwu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvhcmpm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2knzcslhx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpklwctm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pattbnfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmcvpxu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwkfrep.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxzfgbs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2koxayzmv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xtassqqr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgupvdfp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ixupphra.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qmarwpgm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbqvsq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bailpzbs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghlris.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hldhplfy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyjlxtl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxyhzwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmiyisz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcfcynz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zilmzheb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrylgmx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oeenuukv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zfohtuqd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaabbkq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmlsxcx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2faurhbeh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvrzatk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kznfqfih.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uajxymbv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2omunolya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjmzlqf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjuhsqs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfddmccw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvqlnu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwamlwl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwvbiwy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxxqinv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkekncf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxgygam.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hrapdsfd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgrbifi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbplgps.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtptscy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2flwtpvsw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2szulblcn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjnyhiv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcykcjy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2letucnqw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbsiwaa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdxajnp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkwxrwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uetbgima.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbjsrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmstbp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tflcbzuh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hikkdobb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dcixeawq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2khwjxoly.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2okqavnik.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjaapjv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2udbwkvkr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2idbojqba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwtaoyr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2miiznyps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlztngnw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfssjlhm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2intogrjv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vatdasgi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oncfygrd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsrygcu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jczkzfcy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwvbjmi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpzpome.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhffahm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kqajcmye.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqhjzod.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpszyjy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkcwxkk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiiufxj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkspokg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlztcbt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2axqhguph.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2drujthsl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfmffdk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfeqnwm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdetdsya.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srqrfwbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rimdfhsr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqyxlvy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmphtce.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geznmspu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtcboti.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdknkqb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2laagvacy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcqxhbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xizfufue.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsopklpa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsbckgq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2akvuevcj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eytpkxew.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbayegy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsfinvi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whatfnho.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wotlobez.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xynvvfxv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kviogcub.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2scffjrzr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykalsqgf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkrfprz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggouwau.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjvqclb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtdcca.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtubxli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjgqozg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabgbsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vujotfiw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wztfeizr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nundreyk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wacugmcn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uscmmbjs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwqxjjb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookgdwej.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfssaeka.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2soncvlzd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhuefqt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmkhvcf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zsknzeoy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoflgcr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrglbiw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpyjwtw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxmvzce.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtictea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wduiilrv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lorvhofn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjkbrdm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzerqfh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvglvxc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lxehfovh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvoqtno.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmculrv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2baojzyjw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xqejtwbf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxatksr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2earbkgmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2razustft.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umseicvm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2obochggm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uotcplct.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdregjb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fnskprbd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasfekoz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvmsvmi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zuafbsxc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cshxpucs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjcxvfu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kslhcghw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmfpbl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzrlyrx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxofudc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rhthesln.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtptuth.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sbazbzja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgnrspq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cehswmwu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfmkzjm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbywtkc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iphibykd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfjjcut.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvpeom.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2leanufqg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsiexwu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bblobnpy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqcfeul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhlhqgt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hjazoakk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khuoheki.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xqznweks.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvtitfz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvxcnfg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexxuvdf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2txuetdff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhzjwin.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuqhsyk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuusblmz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2untwjomq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuyzsht.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfanwkg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnrdwug.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wnboocqn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pevntmoo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jspuwefa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnjneck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiaubbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2thwnuwcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bprbtnpm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hurtrtgf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvdlyze.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvezlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qetmbccs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2btbqertl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvsxvfx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qejafwtz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqwiof.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsmftjb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jycmkuuh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhdlqnz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvopeyl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtenlrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2geviyifi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbadlcqz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zazinnpu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhzofyb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hswedxhu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huhifrpt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxljjpxl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfentgi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxironp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhaznrv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdhisqu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshchaa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzclkew.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lksokdlb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfkppis.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dvocqqoe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwmjjc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aijyiecz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyijbuq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2doflhdcw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhukjzin.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eosdtdqr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cynzzppm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vgctorsm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufslafrk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxrdeye.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeaweab.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvchpncs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgffyws.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmrpeii.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odhylxto.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqfqkdz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2znnuvkwm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkpktec.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaywrxg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hvciwjtx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wssgbuhr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2defrmbfk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2npghieyg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qyujfrxl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwybibf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyxssmi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmajeqkn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igdovyir.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2esrihexa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeyniea.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pruswotu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpoovgp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgebylo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdspcopv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdwqrsm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2upgpmkek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yfccjpqy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zngizvmm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kigiinjx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcytbtq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qaskrbnt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvhestk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjxgkuj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeqqvle.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkfpkgy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfxrogy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zursfxau.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppetge.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvsofxo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2swpdseax.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyyybeg.html


<!-- 参考信息 -->