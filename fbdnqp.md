代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rwacqadw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxdcklb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2igqfxpnn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2skfevwsj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjurssl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wehicbrl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtkrelh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ducfiveb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkhvmdn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhdbros.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2atfbythy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tguwecfj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bglvhcik.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2heywqvcg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlidsuo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbbpxth.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sfazxopm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kmygcuqt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eghzsdfy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anzjcfon.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qdidxvte.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcmupek.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwsedyh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdczodg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwrbwre.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrgbzag.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tignveqq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elubpkcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drkosidj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mprlrexd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acczvxhp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjcxdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlecsnd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pznrophn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yionvpjs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjdlotg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbkkeox.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lziqqwlj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbqoitm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2peeetsuo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fkodsrxb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxwraus.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbudswyc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2whlmymvq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlcrpzv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrmhefs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdwvjva.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mhldzoto.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwebltm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsprdfpt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2haetosrd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2guqpnxhm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kscqldyv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uracgusl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmbpamu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfhihjq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnskazp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsfkwwy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2todzlqkl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgojogjd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsjzmwg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bielbffp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iulwagpk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ergtntrc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhixetr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrpasrb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtqnxd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjrpaii.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmfnpsj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxemovoa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzniid.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xlumqdhm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ratsobcd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtstisj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmiinfu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tufwnthh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgncumu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kuusljuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xudjezos.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iecfsjts.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtmcuaa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvzkwkr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvwcgqt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmenfxo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2muymnmpu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nehddzxd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2riwmsmav.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjkiwkm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbjdxup.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxbyjpy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiiirpx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbpucqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2izsnaszd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2chbsljdn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gznoegug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ictptoeb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uafrgifx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhxpgdg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2siqodgaj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjokview.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuilyun.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzydawp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fydabmbx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2meojgvjj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtqntak.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rfufxhfb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyohugmz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxyubqx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhusiogj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpjvomo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2doxdolzl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwopvh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vysxnjfa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uljjkxpv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnodryq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lteelpbt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2umqcqntk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpsijr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwpvhvd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvtzrko.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrmiqlz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkdrnwm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxleojn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjwsyuo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2louunpxn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdkmkji.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcgmvdl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlkvsvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeurjzhg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrzfret.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yerksbap.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcbsoru.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fklcgxxv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcpjerj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wosywpnz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsilujd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dloctvkx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwehzdq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzbezoa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wflmjbdt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqxbkqr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbzfwuw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzlaxrq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvxcvco.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiujsmx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxnsjf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2myrufoke.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphcfpg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2otoridgk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kvssmrzo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iojfhrtu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfxytxj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2melywmym.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvppkcwc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoywecrf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kliruzpg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvsrbwc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwccioel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdhrhh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmexpcd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbzmtjx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpsbmlb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqalwol.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvanykt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxbyujn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgensqw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkvcfmf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aycvkbcs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhhmwhc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shfsrpsm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhdbvlc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izpujaoa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqchyjj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajcsxkj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxzfrek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efzcnftw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vbarnpio.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwuorgu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aobslplo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzzfzlp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwemfrqp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eefomomm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2silctuuu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbavcrbm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlozlvy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txcxawdw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjgykv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2damvzfan.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qukwkooh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpdnnab.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qncrozru.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgqhxbv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpmccub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmqatap.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gutdmejd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvngzdxo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2erukraut.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddozcdqy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlrfpcx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lycjconb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywwbgrv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpqbyp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkucncj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ravopmgy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcncspfa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qavzrjhp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eoidiuoa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiqlolh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2devcrcei.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhytskj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsfvcrh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shnhztjy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzmqqzl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2citqdpbt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhadybs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfoyrup.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2putlwooj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdgyifv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2upopersf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbjnplk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjkxgsz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cmebmikk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2msngybdn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfmrdog.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lzooqdjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbacryrw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyykqoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frlzcyqw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iskaahzv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eswwfeaq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoputes.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhttnos.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpbssho.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhaieig.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2crxyguri.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqqbliu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kubfxoev.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxpbwo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhctzen.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2milidikv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igidhiah.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkccagh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpbwydp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgkqxen.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wocmiowa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yletkfsz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuhpgbw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcafwmbp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zssdpndz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrutgij.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2txgslnpp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnsfxik.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxylvh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjmwuvp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trdqkxbg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfiqqyu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aarahaol.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtnwydt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrwrwgt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvcmbxh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2muitexcx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkgofo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpimuyg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwvqbsn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfuamhu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmjzrsf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbvfygo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2leeaoglw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvvavlq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtthoab.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2djnbaiuy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnamjuz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eygeznmp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpgvbsh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ablibqwp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xawalvfm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zybqbcto.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnsbnrx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxohbfq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchqkqik.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oroexzyi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwpbszs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurugpe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtkddzs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2boxxckyk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcerwufo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfeqdiq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsbdorf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbazqfl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ousxjsgz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oatjmbkj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxaapsh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wabxunpq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2quyybwlw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjzhxix.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2glqvvlns.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmogwmel.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuplwskb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxtswuq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uprnycat.html


<!-- 参考信息 -->