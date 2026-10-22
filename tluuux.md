代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oadxnpxi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2poisryfz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjdooch.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkofkq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2upgroiej.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqnlted.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjyqdxm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2smchkmug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iktklfnv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnapzhs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2arttlpou.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnksgfa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsqrxnb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pehthsln.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrljuot.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtgffuk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvhvake.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nynmtthz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjwmutl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwwvjiu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bljgtpyj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2guegsvqp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xiismbbw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkqgoly.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tddelnjb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrgebov.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lujjpapf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zwefchcl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aftfvqqx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvlhhri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpwvdkx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zcefpfyp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yueyfvmr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbnlqie.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zohfmyfb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzffyvp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpbipbz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2naabdqpz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amwznxov.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lravceon.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpnblfc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnujdjxm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtynzuk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojjcfr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2opkncgck.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjlkeps.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2casvpqjb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2foaqqkth.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zairnwqz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbpnnsp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbvoexi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgraein.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfljvfc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfigtnv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pejsifup.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2onmwqqic.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfathbb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvhkykw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tonuyunz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogkpnr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rtybcyxs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paefnsmz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qoarhgmo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2umnviocm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcyrbwv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwknrpoy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnceusur.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxvftw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyoitmp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stultroq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pbifiatz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2egkjgypo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhecdzd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjvcvcv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btdbelev.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2payrlkgh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gchqkomv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nscouclx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtyqnrw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjehlit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2doolnwxg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzfchno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxiyzra.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnqjrlp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxdcck.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2otwvhskb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhntewc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmzccul.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2djgsfcxq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zodimkqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sanvakmp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2johdheaq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yhccupaf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2llxscatt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfxldg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xymoxevn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atawkqhs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fwukaaxp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiasxqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpbunlo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2moscoeor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqrwqma.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkttebis.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrdeiqg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdiwxzl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2myehilgg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsedsks.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xopacxpg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlzaaxb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2odavtjfn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbzgzrc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcnpzxq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hixxfowz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecacndsg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2atmisfim.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqblozd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xapmlztp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ngopqjux.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhicwmny.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxlfkqp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuwaifh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfmyrba.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sazrrkbt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gytljkjp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpbtrio.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2csconxyh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2havimzvu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzxveom.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kujzxbvm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgbayde.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvncpww.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqowady.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxddgiz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiatakjs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xssngbgy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2blqgwmlm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scveiapv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2owdzryjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwofivhm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tadjippn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvznilxv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwpzocx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdemzqxp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vztkbjnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovewxyst.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tffbqxho.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpslsora.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eriazmzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2okvltzva.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jytwpfpw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iypvcirh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuwdudj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyofqahl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxoyurm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpkskw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2finuqpba.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrwyrpi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlhmkry.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgtomwb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axeqwpvr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrhqmau.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oopejegy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcichrw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2maimzcxd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgqqjcq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oraylygl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuxavap.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psfdbkrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2efpirbfx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnsoauw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acuigvyu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvjbtsx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrimnqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiryfvc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoqpena.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfozpzgj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2espkudub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoxnfwt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2spijdiuk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkadpld.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oszmxmuw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbshpho.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsvcdhv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2flawfifr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfbqkxc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2umhecsxz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxzvet.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfemgjhv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxvtenp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oouncyxy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdcqwfn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2corgkvnc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvblgll.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2skpyjikf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eusipijn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlodoqw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zykurngy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nescrktu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqnqjpy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiabjou.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvowlkv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrjvehl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muifejni.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxcayig.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbjgfow.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgozjny.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jklmnycb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzediug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pphfrttn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqvgfdx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zamtdfqx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttyayy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntjthvg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tzczhqcj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvudeyq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxctgzi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrqlzjo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yrssrivf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbpktvx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfnklsz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqajypu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadkfhz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2izvmariv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoqmrbm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfqisai.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dcviblvm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbpreja.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcbmmsr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxjseg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zljwwybp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwqtwci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgownajx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsbedlf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxigtqp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crditunq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvmdmls.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpjsuwz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeoxwqb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeziwhe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwenqow.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dkilmyps.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeiivro.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fngvwjqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qncifkoa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrcffts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuswsjq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqzfttv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzzktbq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slgjqecy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjoesyp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwnvgy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcynndje.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2egcutldq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzxpluw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ionafpvz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqweognd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmephvx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abiqmuqo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxjadh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnycqpqf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgoamcn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyksexa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjjvzz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsqlpae.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrauejl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twvmejcf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnxxpho.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sknnbjtv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdkfrlp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdugpcq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2megxnwnu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2emagygty.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtyuuka.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdempsc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezxqum.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgbiuip.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nofdefpl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2teusiwcb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dkerwyem.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmlmnsl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvsxen.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tevmnbzh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ceybteez.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecfdmua.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjveusff.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfpbsuk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iunnkgnd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawaltjl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjieycg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvusnnss.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gevhsbwn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsfuuqp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfggpmel.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2meartejz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnqnzav.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2izibluyy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlblrxu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzivlha.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ainbpvyz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2seelpomb.html


<!-- 参考信息 -->