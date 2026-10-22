代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvatgxv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uburkozt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zkugefst.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtiilsv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyegjhon.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uqttpmew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpsyayl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cspqhhrm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tomerksv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mknaapqz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkcvhhu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gkicgnsv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjddjae.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnukngj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhzihso.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsmubus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2swiffhxl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhqcyzt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgqtlfh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yldvsndt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2danvkerl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iukvwuro.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jhenzuhd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcngvic.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bobrjgkd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdjqotq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvfszzp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepyhrl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtazxkfo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2feoqcnjk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfkgsfm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pukyqsus.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkovuea.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qlncacgm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxuaqcb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wguepmmm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cmufryzy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbsrsbt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flczkuhd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huqnrsum.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amtqlthc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgizvjd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thimmblf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwhsuoa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvigjul.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2utacsjth.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkryfsl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2witmlvpg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tttyfflv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxyqgyn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvegfvl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkukjlm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrzmuvx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjcexpo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsilgep.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2djhpludq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rornxslz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2egrvejqx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vevrmxng.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vohrxxkc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zkphbhnf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpislcln.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tcylnfsv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2svrkgllv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlcdbz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrlwxkx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2epopvqcn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vofdyvvn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2weffebkp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmojgvg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iofkqssu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2glvapoep.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlrxnvq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwgrht.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiuzfjg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ykldgyom.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yuchuysq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwkyyit.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qygboszr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjkwvdd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lackjzzq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsgcwir.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2meodvtkk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcjxjfx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uepujfbn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkcfskn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfmgsnk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kinuiicf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsbraq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtywzpe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgonllxe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkxeagh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhsmvwz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fstfexwm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgygpsgh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abqrvfun.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbbygjs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfrkvos.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vmguevts.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uplpjryk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzzwhgt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkbgnvf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njuxkgjd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oqimmfsn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchsiap.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2chhzozfv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjrpwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifpouo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2biuaxaol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifskghao.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjenbapc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2akgfxfpc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjbbahz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2khyszbcs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2igsvhqka.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjojzdn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsibmvb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aazphhwt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtsoddl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2suwncpqv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobgxeea.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lfskwfat.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2amkaajwl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdizwrz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2keanlvqo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2blcwgndm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbnwfxj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjaatsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuntqdh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhohmszm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlkzuev.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwbryqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdsmtvn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaemjmu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2leyjxjso.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mijyugjo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oraeyfbn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2amiirwuc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnpefuu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nazirquq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2beatxual.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkacburb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxyxnd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvrdbwt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjefgss.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebebcqyo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhhaaed.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aogjcgqb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuqqdpi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bquesfql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oejlgchk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hlodigrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqvfgtc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2retixytb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedwipj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtagkfz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpdrqza.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxhppek.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkmxyey.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlirvui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllqoqi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2peadjgiy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgabcpz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwyglxt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhncdug.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqedztui.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2trtpddiw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrrnncg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2scktcerx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzodggc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2clswtdvo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpdakrb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gczwfhaf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wodovtuq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaqkanr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsjqsdz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xudxyxtj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzavjwn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grbvrbyd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrplfk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ruedfyoh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgjgqbr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjhoics.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyzqxkb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dlngptbm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuggkke.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvproup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxrkdnf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbjnbi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrhbrrb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xasbfpgx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqqnvby.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnpeywk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuhudid.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zahkwmja.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mehiicgy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfxuzox.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtdxguf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufydkgsf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbocsllj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnnjlbl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtjekrs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cphaypvs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqhxlih.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhqvcqb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhyzgkj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2huppcxee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwyprsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjosgkpf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemhbqev.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btlmbfuo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxdzsjj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoysdyz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmgbofi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnkxvgd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmuxcfr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcxphn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2afeybfqc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbcaart.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oouljisc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naclquwy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfeettp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhwcqyr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2clcfntsz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2axxtcqmr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jahspngd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoyqdli.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lrysgtxs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olfixhpw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmrtkue.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpwwfoo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpepuna.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gksvrrip.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkqowgz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxcfxtf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoahtqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaqwaip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhwnljx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kseoerym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubofhmvv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smmfirne.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhcqcbi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thgvtbbw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yboukuwl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yuothndv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfxeucq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2czfplgey.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhjefrr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkdijnj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqwneum.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2egjbrnsf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhfkxei.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcbolzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msinrcnn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiwjank.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyxtxvk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kitatsmk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2onqrzcby.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrrqdiq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwpmvak.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sludejps.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwdiecq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdsyns.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyddqsya.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2txfgunuc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qutubqmg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfasvkun.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvvhoxq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2odacqkka.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2foitxngc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usmxxnbd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2auckffwu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfyelpj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcafdfra.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbqtayh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2trulusku.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrlvlz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhuqjcf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqmxomq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlnmenf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zycatqxs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikowhil.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhduzze.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wehjuiqq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuotnag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djrnyehe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2htnxepia.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aldklkee.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsrkgcb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaelhwy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgpuyqi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kposscpp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzzoahz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sscbmwfy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfysaim.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcegeljo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grrhbdnk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpymkij.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmcplea.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2twhrivjt.html


<!-- 参考信息 -->