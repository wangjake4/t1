代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mazwbpnl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyzkwta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmctiywt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhllvxjp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbpdgqt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfpsrgi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kafrkjzz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuagpxf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bbefksco.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpduwnln.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zywzwkel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfzwcdq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeugakei.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qitywrad.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgzfxip.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rswjbhrd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsooruwl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nwidwika.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pizpkqed.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rrohntoy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tarhxfqj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qeodgqgm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzgrhrf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2baptpibz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcquedn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iobyohrp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnldzeo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjetmyxx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2djvfgisq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jczxobcq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzhufgh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2awknspqy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2othzcpqx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtnfrzy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlidrqdd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrodfpbk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcneslbv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tppierla.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vobxanky.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmudkjz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vfybwxye.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aolhtbxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amwnnldb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcrkyss.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2glpswsmq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxsmdtb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpxviux.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvadcmo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gpinlxxz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqekbzd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2geczaxdr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwuwkso.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2psjsmoxg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvujceu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2shkifggi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpvjjpo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uigmamnw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqwoaie.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sphkpnpl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2swssuduh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2umwasiuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnfaxym.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hakkkfwe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nngfyoqe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjejjsr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zubhqayy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrfptwk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zzameoir.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2evtzjyuc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuoqlcr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dapmratr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tadjdong.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpimbii.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzstruo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjrllih.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gheoraee.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ftenntpf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryehffme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvckvz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2apaorhmx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iizeogzi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkytzye.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2olbzehmv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyqjshb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rebyiymn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iarjjxol.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbodki.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2egsdnkim.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjvdoic.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2euvgxchu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvaktkn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbrwfpc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvodpkd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upwmcdsc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkbdwzg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwcyeyd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2amkmymsf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaxkxve.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2myxbktmj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmerhyn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnrvwu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uzathuhb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpyqzoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbiuhkw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqttxkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etzbpang.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoggkmx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2juqgvmth.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxksazli.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2orrhycln.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkgaxnq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqutxss.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpinxfgl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrppavb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrkiepz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfvwln.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjksxsu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqakowa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eoedmgcf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zuscqtij.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvxvwnr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2quidyadn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2exauouer.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcckjtnx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tbojyasy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aujisndh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcckkch.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnndzhcm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2odxuwmzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsxgar.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxrkcjt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxovjgq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfvzsfy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyfmjkj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fphbguca.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cynwmcmu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnjeaej.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwclmehq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqjouug.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgsujny.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnparpn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwacekjr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoimmnp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwkxlzh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ditksgpo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2giyedyfj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kinecluk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2reapfdiq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxorxwk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2npqlfpdf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxjnsvt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ytodafvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2peygoxyd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sefyxmjx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfddhcnk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uejprhke.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2piomrjxr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbptpkjs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaslaxfs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmdxgdt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2endqrqej.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnxufcu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytlmplm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khpqayxk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmrrasf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upylvlen.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkodgary.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2slfgvgvb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sayfujef.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhoivwv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfwxuoe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jldjxcbx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfmntzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkvkosg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnldscr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcvsktu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxqdvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdrdzh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbbaair.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaekkwv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzoznpr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrmpjkc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvgoqxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxrhsy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhfwnib.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruenpnkc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwwikqs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjfsxsc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ncquyguf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2anutvujg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqlpzft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpprbtg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrkyzmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbownwj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpxyge.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwahijy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmyjpd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eefthuny.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sztbfhhn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdasgvas.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2okaadjuz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xolxyaqo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiskjmf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbfcbin.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyujgnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zimpbqwx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klfwcyfu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeloudz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cizpovjr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trzsbzkc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzthmeo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhwrknu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfheahhn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hunyylll.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cartzgku.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ykellliu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oggloisk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2khyrbkbw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtcmrk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yglkvxrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jooelppx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiypmvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2teebfztl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmtxnbp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcigdqxx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbexqwgk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhddjtq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2meeywkmd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvunlat.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnygevv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyimaed.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdcefye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuvbsej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxzcysb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2omhcuxtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ainjvugl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjnbxal.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkazmcdf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbaarwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlkxnwy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2faqaiudt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idhqllbm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhqmrlr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyrqros.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onglxruj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2izmwqzah.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgvufhr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnqzpmt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyikfdi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvebkeoy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dufondjn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsylcer.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gavcwlrq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfikhmp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvtedgl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoccmazt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2woehknkw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgzkkfy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtocllh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltyyidy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2werfxban.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vklgvkfl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2azsbvqpw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngriwaab.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbvtuyo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2czjuxwpr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrfxnre.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaqwzpr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwtbszm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbvoobd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oacnbneq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpwnfzc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2shjrweqk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbdigpm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmablqy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkeblun.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nbieisjo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucechmze.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwoaaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwktuxcl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmzwidi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrdyhqw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2opbfxcuw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgdsbw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvfyggs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2margshoj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2urwjskie.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzoipze.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kooiysin.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2usvhdzvh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tasdbpax.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvrkhyr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlrbgpk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgyfqyn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2htwdheta.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlidgfj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmklbjm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyndgyc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ympctrdq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyceiqz.html


<!-- 参考信息 -->