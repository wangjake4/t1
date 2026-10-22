代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvujha.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkxxsbm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbzdfue.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdrueyn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kokrabii.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkgqbwp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npqricnp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2taecmsgz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnlybia.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwxnhui.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfbavae.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxyihvx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsipmsm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2duhaheuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbezhgnb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwgdkfq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2doicumyo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnewputf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2selafjsm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxrnlfh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2agjlkqxc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmyocag.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvpexoi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyifbtbj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cblktdbl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2unvyntde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqadfyfc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbefifz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzxwapg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rfodljds.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmqwzpt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmitapw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2taaibxtw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oksxxdiw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsfjphx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuksdmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjrwlay.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrmluia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkssxcw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeitzroc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghhunrv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxpuscb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2skxwkifp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdajbsn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ytghwfym.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaokvae.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrpsywe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2phyjrwnn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jplswtok.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhqnupn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqymnrho.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcutcvk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2duxzzzzn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsmamrd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgimnxx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cmibditf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2egjwqnmi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jkprwiss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxeeja.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hifkcbzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nusazwug.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2malcqnzl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tislmnpo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuoxdmg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2siruoqrl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2urbnttnx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtnlyrg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fnexccha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2njrrwibe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmohetul.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sybvtkag.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgpfdio.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wwntcolz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwuwoeu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrufkly.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiojoyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmrswdp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyqislw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyvefwc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfdoxtl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2napaihoz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iavaeqzz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hvztjzee.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cseiiglh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjxqksj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiuusso.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vckraeyv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfodfoo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ruffllwo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xplzekqp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwxpmpz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnyodpg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbsjjxp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ampdeyeh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsrvtmw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehivsssv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2racatpxw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnykijtl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzplenye.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhanqjvu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyndjur.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfubauf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juxlgpzv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gugbggmw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkwtfwe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtslenp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2skrgezot.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfevifl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnmcytc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hupvoqhd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjylqjag.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ycormmae.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxbbhay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgrwztg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otapmaut.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvxrxxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2khbkjqjy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdkagja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mchsxukj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmgmbit.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjhcdql.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hnurtrud.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgnxwkl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcvwgzi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqpdtek.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaqhwpv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2khajxulj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqifesq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkewprs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhmjhpq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyeeruh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmjwvwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khogrymr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2psauivun.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoioxdx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmkgibs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsrociy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2klkelmgz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2otraygpy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyrtkpn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgofnli.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkcoxb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lajgeync.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjvtvcl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlioui.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cacppnkx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgktwets.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrrdmnm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qearhpmy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyprunw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieafaxqt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raxqftuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyyxfol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvnoaja.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcpjgir.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvcots.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzsxnrt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2izgnjlsa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2awblaayf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fziolwgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdyzdri.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdxdxgx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlingwl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfsbytb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpbkhtc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vsspvdfx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyivfffi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zckzhryf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyfytvf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwqnfsq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvitjsj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfxodpn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2exteayom.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2onfketcn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdcymbn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wegkeibl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjignbj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoufdsn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtegzvw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbatbvt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhgbyue.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qytdhucp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdpfcdg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2imttuszi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjideuqv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2katcqyjc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2beofuzvn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sprbuknx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvbqkym.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbslkvu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcaheee.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qeennkfx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhldffb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2admlhyki.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2otabmvjq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aolwcsim.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jimggjgb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idpazwem.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcynpu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkvgmgx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pwldgnqq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjpuyum.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwmkopm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqiiror.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmprfws.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrlioun.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ricwsjjr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhhuikb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gcovtluk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhgbdmy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2azjolubh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzkvpny.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2psspogjq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jejceugc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkwsuay.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avqsbsia.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zanhfzam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjczdpj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yujvfaqu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2baprsdfm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhefclx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwczcph.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mabnwdiq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgavcqaa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaspdep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwmvboq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjdeccj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpibczx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrdmhzj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnswnuy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwkunu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjdaehh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgxjtqi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxtudqw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bruuspjn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhhcfut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swygavsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeiupbm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hevbpfyq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyioagc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqzahmk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsniyrs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mopzumvk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oahsinid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2plvuyvhn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcmxwnx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2buvastaw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uppkamzj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpxsvzr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnumftc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzevrdq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnjljal.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2algsvxvx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzajkcuc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjkfmch.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnxkfuc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwugizyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwznxipr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijembb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkruggc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpablys.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhslkcum.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeocszkd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kieshulo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eomicdyi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umippyms.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hlohujuz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2byyajeqk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmjmimj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqhlwbt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zikvzkac.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lopsslbc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbuqvjp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmflnmo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2unamrows.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcrgwot.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qahzgclb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkezdjcz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpexhjk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmsljqg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2upoxwzam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2prubebcv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyrchxd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacyqdfq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmkneoc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubotxab.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crbwhfua.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywujgxig.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfyefkq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfhzjqw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yovvyeod.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnepzgf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvmapdv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsifvfo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcnljtd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtbbeyx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjyzzle.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnbpplk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kufjkjoq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbkyzzd.html


<!-- 参考信息 -->