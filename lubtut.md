代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhgkyzk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlpudfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdogcjv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2utoiesfv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdingrz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2daglxfyj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dcogdgwn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qitcrixr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwgctdz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2faltzovb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmubqxh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2huxuuixn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkqwjqb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2udidepyg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2roaxmpuk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfscnadh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwupufm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hcykdpuk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzjetuk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgkkurm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvymkte.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cevpjwox.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcrraok.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ennbmppk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iavhhpfs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2walxxkuc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuyjrzm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oojbdcsc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yiejmnaf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqprorlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyplvbob.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvhszko.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uaistpdo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbbuepz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnnjnbj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cycmduty.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcduggt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqepqqqu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdxwmsd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiqslfx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fmucgvcp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krerqmyn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hicgqzoe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxhtsqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cumpdrmc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cutjuaim.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hviciqxi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zorycyoo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaczguy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxvyuzw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tcywrcyi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kooxtots.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdvujr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ouymytso.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nyehhcyr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmlbarb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkohsws.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmooago.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrewcnd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmfmbyo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwlnuqa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rninlkvd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdavaqp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2acllgqnc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclyoib.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsubckx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbsocdu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoztzoq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqoorhe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2izchpjtj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vaowwxli.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxidpqj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vyptjvnv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfejflf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjieifx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vymifrvw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfpbnxa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eplqdbmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buqgqyxl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgydwcl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmwmpb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcvwsnq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiuvjkd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwmdfur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iksxivax.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuumkvu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnxosll.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuxsyrx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfpwnuf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjhdljn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rslnpkbi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbencwy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnekjub.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jhremefb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmiaxrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mznnpvjn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcusfryx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvixjfxz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlturfg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wymvxoeo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvlujoo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfypxynf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bucyanst.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjzdgih.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2achrjxoj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuqwycm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzlfgax.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhncblq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdxwabu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpqynqv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmzocfc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oybdendm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddftcmfd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nevzyzlf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzhlcsj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fesfywmz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fllivzqo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcidwbvw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwljtcmn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlmolea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrcimjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhalpalq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhtfbre.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhfmaoi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hloeemwt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2czfvocqt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lguveylr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2albpvodw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zutxmlyu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2anflcmwp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyxmcmc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iieylyfc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkbzegw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtxcbhr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfeejgg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njxoivri.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnogsgcj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpotokqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnvbhnt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fadcicej.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2drnxjckx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzagibof.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjsssga.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hczsjqhx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2joeuwrak.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yywptzqj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vptrlwpu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2euoqtbaa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxergzdr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tenuxcxb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xchxttlm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqqisfe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmheohyj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrwvtsc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoryojm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mksrkssc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjumupgg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxsvdav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsuubio.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoyjldr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2thyvqeao.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mulvrepp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hszgjnam.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtstympe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kokdqlud.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biscgnpk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frolzjnn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkftzhxx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbgebdq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqwpday.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrnasgs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oretcxhg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdowwbo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brshqvya.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtrxrky.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2boibaljq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlecojs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbmamcl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tcunzipb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaynlzo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qffcuxzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ihepklka.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrwwlvj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjpnyzd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cincsvkj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnnyahw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrjojph.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qydvbfex.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnpwvzx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiyjyjt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2akxvsaqs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjefidbz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hxawtham.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpwiclc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvunmn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyhttyi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdnmjmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uczjfevr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hggaerkb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2senswmeu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkprqfpv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cblldrxv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjfarrt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aatzwrkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklpyzbw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzjdljb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgtexhv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kunjorji.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2encrlpno.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsucibi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkkbatu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2czhxvzid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhuogs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwxinsx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaspvwn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vgungtvw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njiodavx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2skmdinbm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2frckhprz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjurzdn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqnokgp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhwhvss.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfwqqon.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wazqeddc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oascojeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmpezfb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oedjrctb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkifjkh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvjbyus.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2litihnuh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpiqwb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqvqhks.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qcevbevi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbipjge.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aecwjntw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2edtvvdkl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2glflaogv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2amtnfely.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqpyuuq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgxxzmn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsxflfk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwbsvmq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvmrbp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2snngbucd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojueijko.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyvrncv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkqvisc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvzbka.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhrpqdl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtvppeo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtgewsa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wujfjxum.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcpwfur.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htwelpvd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfgrvpq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuloouu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbjdaod.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnmzirc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phobzqnq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwwimew.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjetsad.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axruerpo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpigmiqa.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwitou.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lktmfeki.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqqbema.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ulreltpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrgnfwg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfcrfjo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdcqvcp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uejvgfms.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dazxuxii.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jttzgveh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qofmrrgd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ezknapym.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiahjnt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yngguurn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczasufd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dyascjjh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdveirj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2amgcbeaf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzszjow.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2odvccorx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2paaygdlq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqvcaax.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvkppzp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfzocal.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxldepqk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkxcokg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxemicb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txnbelsn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odwudwam.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2idvzyqzy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uejpeiki.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fihlzmii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdzpkem.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvkgmjl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwguxnna.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuukxsrs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmjccjz.html


<!-- 参考信息 -->