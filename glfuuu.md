代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2trohxrcn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsprbea.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mslwwypo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgpmbks.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxxzyde.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2srcbghnx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuvmble.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ushxzvqs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bizemnxo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2maioplit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdemgvu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fottvpst.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2efouirjo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdzwyhg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qmygdxdl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pioriijy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvgjauw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgmajew.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfdrwam.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvxskub.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbnugle.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ufryrmwz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eawzcfwp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxffmsb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkpaoeo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbocacf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ngovdwst.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qoevoxvk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaxmmky.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vscnqnkb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atjppaem.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmztbezb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmokslu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tpitfijc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bzotlbuo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2caocxniq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrzqjqt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2boxnqafi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aogibeci.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixawljja.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdqpiei.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcubqkxc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbygawfx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sikmqrae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkqxoyc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2embfboom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2upyktrug.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsuudsr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jgevszsy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqktxtzt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqtaiac.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoliuin.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpoahzn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgdryop.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlqtuiq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cyowaaef.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvjggqs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2twumowsp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtgsqt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hypomjqx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcoupyw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvdaaze.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zksfarzx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkmimgr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gzleavxk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqfflmp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcbmddx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bobshavm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nwesxjpz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrmucek.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2frwspzfj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hlutdzdd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvhfbea.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvonmsv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdjbekg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wthfctpl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2isqxsaar.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mubuddfw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xufolelf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vywwnxtd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhtxisl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2auapugke.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzdijla.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lvntbyir.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwydtyo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlvohzv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2npnwujkv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzqepnv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eycffgbz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xgytztfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnrmapr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxfkaoy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dplbfimx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2smlddnxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fykmrlgo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgtenft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqubclp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uejfaqgc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxguljq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlneruwe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dszcsinl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpyonmd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fikvbsxq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhpumzz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cttodnjt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bljpzqzt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmhgxdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avryzwld.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmzqgrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoojbmp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwveedkb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tvztcdyd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhwuchf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjfzoxl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2goidavcx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuniosw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnfeha.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqasszl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2haktzirx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkncjrqm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchuiym.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqfylr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpohges.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvpnuhz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhbgypn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcudmiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgynngsb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eahrdrpa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzxnwhd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwuyrvi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwzncqo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fugiljvk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqszuutd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhkttlr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbhdvxk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txwljnvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2blmbfvho.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fymsxxay.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrlbeeh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jkarigql.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwptlfr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxjkfwc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgdcuwa.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dzltkmma.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioslepos.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2unkirrsq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbmjlum.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsclbre.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bffpwesv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzlrlt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmrkack.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwdddxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjfcait.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqnmrxu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2frkhipuo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2onvitxui.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijegzctz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2recryzxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cspckwjk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2afandcjh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnorcz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mjecstuv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvrxrep.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2opjzrqys.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2opoalajv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecbktv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppsdbax.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sefojidu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2futppnvc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bichcbhg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgkoefx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwkfqvy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jghtwmgj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrnftki.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhplpvq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxjeesu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtlkvod.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvnrnba.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvkpmei.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gciomgve.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sbotzcko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrlsdq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdugvq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitehrw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvladxs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsbrfmq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xyovauyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebxcyru.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vbocskhd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2avhbxtyk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgewvow.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahablwap.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqotsfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqlwnbz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnhhykg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzsmiiw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sizkjvxq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzwgert.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaclebu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xateazck.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2npdcqlwh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssghsroz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuvbldc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsjgzmg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jqueumjl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asqmclsy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2besxrqsf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzirumgv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqcxohs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjjhxwu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unztnmnp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkpyylg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbdlayf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkrjcnb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2geydtogx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zghhadnv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rshjincw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lemmlwqz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxxdqnb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gaovcuja.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpysgfb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfougom.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2upqsnmmd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vayfwioq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtsacym.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2goouhxqv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrhfkij.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2eidqdjdq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwamnau.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2twhdekcb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykidwpmq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyfgsws.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjuspnu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvxettv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2irsufrzf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqsnfbp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yeexxgve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eemdeiqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnbzazc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xehbcatd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yaasaqhj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttblnqrv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drmecobg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcstsex.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqwldi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozctmxhy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkyxngg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqtalsr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2riulqyga.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdetyma.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpmbtsa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbozspu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbjfacw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odlydpje.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwnuqjh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgywgipb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxikham.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kalfhitx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjdubaw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhdlti.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gttvufrp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2awhjlzkr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmqqlhw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoatvvo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zotwudkk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhxikia.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bipfcatj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjigepnu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsazjyi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtehiycf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbyayv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozwqmq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2onebrmsg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlovemte.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbwbkjl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqhicyg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2abpnkssm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmyozsk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2axbymwvu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2thnxtwjm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwjhlru.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelbxep.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvcxbvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2velzmznn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sivdfwts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xraevwme.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqnhzxk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotnqwpl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwnhyjn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2njowrvtj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmujlbyo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fllpqabe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2emhkacjp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sspfhzag.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqzzhhc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyonjjxq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhjabza.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkyraji.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bjusccgn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2flxlcmmg.html


<!-- 参考信息 -->