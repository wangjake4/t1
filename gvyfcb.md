代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzplqsvs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2edglfeab.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgpkncp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlpolbg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rexyadid.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sskuzbmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcotzmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgheawn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvudplwx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jycpreyu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdoixac.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsqkndz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfakrvr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzupfgg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cjansqpa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlwdoe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgodjvbd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gejiopag.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmfmspd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjwvwnb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuobcsr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zeamopsq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbpdxsz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2crzsrkdz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxcegqx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvwfegz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mfogaybu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcjnkdg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxzbdfc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtabiagn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvocapd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrgknas.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abqyhuvt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbkdaen.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvogvk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2parsnicu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zakqptrw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2avzzhdjk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bhisxloo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tjixotnr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2euhdpbxq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2acxslcpu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqsymli.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvizzc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zwudtkyt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2etxjfiby.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwocnuh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpeagya.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdtxvso.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bcturmpy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uipojsuj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eklugogw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvytdlps.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrlqzuh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2damcetaa.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcylbv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fsadbzcs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dazbukrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ropukkxr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zizfyquc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rikfivye.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxpkzqt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vleohbyl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2samqtjdw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2plhyrule.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuicuxml.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pykecztb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2txtkvxng.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uuszanjo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfxmnvr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzszkfx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmthtdi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zfurskie.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqyxvbr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqznhn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzrtjzr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhjosou.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2agjqnyjt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtpcuua.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mobnanoj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2doydwric.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vutbszka.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yuylqjui.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zygzesxl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfyayy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtlhslp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvjgfnj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtlfzgd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2npijwqcm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyuorng.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwwxays.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlglkrdb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvyqoaw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwzlvkm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvjiqn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2guzpwxxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaqprkr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxtfcao.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaraakp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxitmut.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yopwsiwr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsentld.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdlwpmx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjkjcen.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwlwoyk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdbtupm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2irqolsjb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjxurzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxekloqy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htfdbbhp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhkqnn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ennnrvrg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aykrmrsm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2luvtrqtx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bylgfvlc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcztcnt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nowqgexh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vbidwxjc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkwzlcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wozczsrp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcvawpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhegpar.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbznmxcq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqitzzn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemludd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2weuwqhpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbptkoen.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sciegfsn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwxqlil.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2excfwtos.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzecdorv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmgjtir.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgraems.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkslmtg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wxndpgnj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoynxvl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wlajfams.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjdpcky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdfunag.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbucedb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2npfwtwwf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlqqopl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujydkvm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juagvygd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwsyfnl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmbglwm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtmszfj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnmmjz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoahrum.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlopdxn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhvqooe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ksidimfs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhqmxde.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qskceyop.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rqasamvg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hoycajej.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqxghrq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gictncfs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgaayaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chpkzdlr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2elmuqkee.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ispogvno.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjhemnb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyopqiy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2izsggeor.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxabaen.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnekbjxr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaiuwdm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexpane.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qurhgbpj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrlvcds.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jacxflju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmttozxr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iqolldvv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kceczbid.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oeameaig.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiybvmao.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2znxppxxe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdbpsbz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yacdzwcd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuafkik.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2soqejgea.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qepsawlb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqouvpn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcrhbws.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhbstju.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mtovwaso.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoadofi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xgndovpe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smnjbdss.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jumgqdzs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyqrupz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlggthx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfpvkfu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvgotfy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbipwmt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lvohacgk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxlpbq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2trdtclzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvvdnlb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2grkzcxwe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrujwbe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sllkuush.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkckkkh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaroncu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ohldlect.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrbloa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juwwehhg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjuzjjf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgrukhl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whojkeit.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2izrbsgdg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqdawcw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxwchzt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrfbvoa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoxsmmy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xanwlezy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vklkwptd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrbvctg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlufawd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmagadlq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auyhfcgq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oouofebn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnskanq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeyklah.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjwoefx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxvzfcz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsiyirj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2apokykny.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2daqeuhqi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgdnvql.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gockrwfq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acfbzgwb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgikkqv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcedzvr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfizrcdy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvoyumz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvukkaz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhwyeze.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrjdrht.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxexajzg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbggxdlr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjevtmzz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ugayjnwa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrprwmn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvxfcet.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiadnbx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxnswk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2llgjxfwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewalbs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmbdytv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eawblwfn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqltsca.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umdhosgs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmhvrwq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhdisqk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrvebdo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeclphxr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kknlyjzf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdjymkl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnbpxa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkyonah.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaqtoxr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfpjkak.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2epdhhpmx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdkyttg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yilcftzj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tldmgdfg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsthlvup.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgwuaqh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sprihyel.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2plgmkmgp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2spueolqj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2snuajmdo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nfplsiue.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngosbgfo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywwxbv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhchrtey.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwexbwlb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnikoxt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yexidxmy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeuqkng.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pawqxpps.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrajelcl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cljrsjwy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilefaymj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlxobpr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhlmuf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoemwkv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqkautt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uimrvngm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfommtu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiqkjqj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czdfppkk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgvuots.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtukelm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlhwpbb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjydxnf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfffakn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpozzgx.html


<!-- 参考信息 -->