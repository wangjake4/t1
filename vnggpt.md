代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgbhwjm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2agmdhnlp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgacxoyy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2knxoegnv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fprsssmg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuaiknv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazspylj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyyuyue.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqsrbcg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnmrict.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yngxqfpg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lihymdea.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbogkotg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqacxyja.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gviirgoc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzskfhf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigwiva.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2omxcegjq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dccrfvwz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdqrnqj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qctlfkcc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hjubiihm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2thltcadu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaowpqz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eehuqoal.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2urwdlgcm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ruypjplv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnehqubd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2utuyltcj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrrsbcz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oydwqxkk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiznvnw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvaeqdm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eocckyvq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqouvmmn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hraxrhou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqwgmte.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkwzjtr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwczcekm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxofduhq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rmixdzzd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmihtwp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esoardaq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zycxubma.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmdbuii.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2grglpoed.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrhcvfu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2muglsaur.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyfmryf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dozsgeft.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdrupyb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2svrvefsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlydytc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkdekvz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2atssrbwi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxprsrm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqrxbex.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbtykpn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfsijyy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zegnaycg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhjozif.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2suohuimc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wynpbbjn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aryebbzm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wksywuyb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guoehlkg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jheucypd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnzhdub.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrzekmx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujvdfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgnyjm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzrpise.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuuisxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eiomxacy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2euvuzkgf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvwianc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwiagmv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjowpsp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmouqsb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jiruyvjz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhscust.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mhylnjen.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2snjqrccc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuspohw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdlavnr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzmlkbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxssbpan.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dodhwtwy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2priywuyv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbrnrnt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzvbeib.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txwwwipx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskgvnt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqnqrec.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aohnhnlv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rzetzsgq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzkhhnz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zdknxamm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqzfrqy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuwbxwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpcdgky.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2agvdwqdj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oyikeabz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aryaveej.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaptohz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvkbuvo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fupddcfr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpytyqq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnlncns.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrxuylm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mplnomfo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2farnmphq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvvqnae.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2orwxxcit.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxcqdje.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lryclzso.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeckncux.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfykpgce.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gjizaivu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2udztgcjy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxyjdyp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jfibaucp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cawrprvn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdajbmvb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkstfbi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyvbjhv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvimirl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuheqan.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfcwmwl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xczorwif.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2anypwshh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tparyrnt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejznkans.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfyfeuy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkyxcg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gxumhrog.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkduuzy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyvostv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcqwpzm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeejbka.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oilqtebw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzrmqyj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoazlji.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aantfeew.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwscfrt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdqfcgt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgxhnqy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qwysrrpk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjobqlgo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmqoend.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdwwge.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyyeglc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqykkao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2czyhceqt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzycwdlh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoxetpn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdufmnc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jftpwbln.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2isstejzq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxedddk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpvgflj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wijgfzfq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2htzjmboe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhqmdkd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2njcruqnd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvlhsl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihqvtxd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxrvby.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ppenshxk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqgefqv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoqzigg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jviqigdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcucsi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orbuepsq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrzaspc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2byiborhc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhevfqz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcyhpuu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nybmpkje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmlzsko.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjahvzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqhmdhs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iosgmyit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvqugl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhzdixg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkckgftv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsjmdtm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tikjcouf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrgicr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2waxulpiv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oaasrtyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfheyvn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzookxbw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2seozhtqj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rurhvytq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2erbtggxv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlfidva.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsiwqjn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2szkbtsam.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjplpdev.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2thxidlpa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bimyzaja.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2thwnbrcj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duigbwhe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkplqjqv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikvsltw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstweca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhrqbbg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrizqtqr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgoobde.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzcyvyb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcjevff.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqijszv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueclxwet.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqmlwfk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2slcjmsnl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yciffjrw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2leuqdowl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2slvxwnyb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwcwogs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbldmki.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2elicnkog.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2puzfoegt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fozqftjn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2updftbss.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2euchqord.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2quplzzpl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zskivepr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aztzlxqe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwijlgq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkjihjs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqprgcl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xuipwsew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amorstyt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2naafqcep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmibwdf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqtotov.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akkhxkvx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpumdjuu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkjafle.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhuqobj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsjkyoo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lzptqdqy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lljfdbtm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vptzayqj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mulneieb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zlprfmpv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mafulqcu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuauzit.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nipwvias.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxakybnk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aszwyscr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipceuvuc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfwgqvo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuzqhcy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmetesk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeyqzow.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxxteuy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ucimexkx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspvfmkf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqpgjrr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exxexssc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtfnncw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbwqxkd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cupbrllk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvxazsx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xihfoxpr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiqawdk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfmjicj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2trfksgyy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbbvsma.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjgdnno.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdumilm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvitghm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ynomrbml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhkgmyw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwekjsz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrojnuv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zgthlzln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aeadcvzo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpktvnk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhwyzrw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkhmnqd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bztbcmjg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpanhlk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpcqvdz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwbltrp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticqmeou.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kctigafv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elxwlxnv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtdgadh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupdkyrg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgstrep.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqanims.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaioots.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybabmlt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2potrnaqc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxpzhxt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmmrot.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2veqgaxmq.html


<!-- 参考信息 -->