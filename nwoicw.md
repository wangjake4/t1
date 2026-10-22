代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwzyeyd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdohddpz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2siuljwgj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngawyzab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfwjsqg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lulokcto.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brswvrye.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfivxsb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnseenv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvjipql.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqggkef.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzsajy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2faxuxzja.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ynacgwrw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2konmwyyu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ginehfrc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfivxbmu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqloxtvi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2itygckel.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsepcoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqggbiqd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2npxtgdjj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amppymfn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlcyijo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxbpkoc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgycwwqr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwsqyxz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bifihsvc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nasnxizu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkylplo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dguasasx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqheuvjr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzahuqn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfmizgp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yaylanlx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pzngyqdq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2onhbdsqc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplsuxv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2luecnnta.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qambaoww.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibhltz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cttewwiy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2neskfgbw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hndmiglx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxphsbi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wmczpgqc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2okarjccn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2enoqyxzt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qphmosid.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdsvfqo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnibors.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkavizqw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frsqsdzc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2snvsthsr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvafrtd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xldowhoy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrabkku.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2agtkpcbj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aruvwhko.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nypklxce.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uftthxfk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxdiflm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvooowoz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbrogfl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfjname.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xenolvac.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbfojrn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnffxpp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcyvrbo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fykhxout.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrzpinm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hdasjjgo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2candlwtn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhtefzr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pedshqdn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtwqptu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbdunrg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2paqzimnm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeiewkz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbvbshj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xbodtyjp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwuysww.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsjqyqu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qusjfock.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2svrprrof.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpkreco.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpzufkx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtshrcw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dixqcxcz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyckawe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmhmkhe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xikaancs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqpnna.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2webgibfy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crvrairq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ieodqdty.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxvdfcj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uajppfgl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdozwhi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhrotqq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tafdclvg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqloihh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrljyvy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmknaysk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwmoeiw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qlokgfva.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eowmhncd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqclzbr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsibqsf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbnpdhm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlvelhu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbmzvko.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdffkn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2itqtkzkc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2revzyilr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2odrdsimn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgatgxs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2loomlohh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2acobrvnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vapupbuy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yydqktwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adkecyhl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qvawwyas.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tipixsch.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpykwdz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgthlij.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwnbqh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvxxjuv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfdrtrs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjljvgc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcwyail.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcqcif.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kigzvjpm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ophgecfw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pibhjfog.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ousduqjb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2niavbrmd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgkjmhw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2edefykrw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iblokdtm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkirgot.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwplwnhl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjjeibn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kucxzpoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvcbjmj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kndmciwe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2beghzgwe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsupodw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2riympzgf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpkgcvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2djmnneup.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzddlbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfaycea.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjdtmv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2biphumih.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhfymei.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoxuoqs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkduumu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaebsne.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wierlfhl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdaxwhw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zidrpugj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzsxhjl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2korpatdq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtlqsuv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjytkrd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgvbxz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2szccxils.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdprtmc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pabahqhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2brijoihe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dkklgdzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxleuwwy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dxguqbas.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsjeudt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uadjgrym.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2thabtkrk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwxvcmi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwradpfw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfcmmfq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmshhytu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvjhsea.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsbhhff.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlzwcqx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yywzxunj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqdclhw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuwefaa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svgluvpe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hssuhxtl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyastmdm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfroocou.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oonyxaww.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbatkmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmicwsg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrkgmro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaaqdhh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2shlixtjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwswpmg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvjwoor.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjzgsbf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxauetm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpnzrcc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfdlkqc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtcesjn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evjjgeyj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyogbtq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxspctrt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkajwlj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzajgyb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aprjadre.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjclttyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrszdlvs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrwvjil.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2chqlrftm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2brhilxhp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqwjgcd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wehtmavw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtutqihs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsejxea.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uitdcrda.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlboggg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onlvrgaq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxklaazu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiaapri.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2joybhhts.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqldbwfm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyupnnn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvaewta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgxdalg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruruirof.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2asembdzk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cirqaohx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkwawrv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cyloszcu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmdvbtr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jspmbzdk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbaubca.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofanetat.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnxyqsu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2efwkouaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfjgklq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjtsjfx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igkzsnng.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvbvclc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsfjosz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvsvkdx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2goascdpv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icdzmjnn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtxdnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtahvik.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxdkgek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjmashs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlqndxd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjuxdjp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpsclf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kapglefj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhaiqub.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2itsaxtqg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhmbnvh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmhkwit.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqiqgpo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dvabxrsz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cndpnpeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxerfvhh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jiygdkap.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehojcii.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vapuavem.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuttigq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpuhdic.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxzrtzn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izwonwas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfofrkpd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uaecrghe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblhxzot.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjltjwd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgudilo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbniktl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizvlrhf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2onvrnpdi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuccngt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeilngm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkmqqeo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awxgpkgo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcozhsft.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogatikvi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqmuilg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwowbyq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyabfeua.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhworao.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2etenrvhz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdqpujt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzkvlet.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwhdrqm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhwochj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqzdwpt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxiudqr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icdglpya.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svpeqeoc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rcboxnqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwmrxua.html


<!-- 参考信息 -->