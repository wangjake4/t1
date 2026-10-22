代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgooyql.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kafijkpw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bngbuaaj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izjdnsxj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgivurjb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iydtrkdm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhkdvkv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkvamz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpzhfwd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mniypxlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvvczn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzrfuio.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dudxbund.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nltopzoz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznzppq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpycwkp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mppbcmyc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2twyafjaq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2newdhmlb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khzeqifv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spvqgpnp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmznosam.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzejhbv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdmgbeq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmohmdas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqmlutp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbznbvje.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2weevyiwr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxoxeat.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oawfpiau.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yldtdpxd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iihgyoso.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmgynlk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzkbmra.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdqouco.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfhqtrm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbocinrc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjvkhiy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzigudoc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdldzhg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kaasgjvz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pubhlcpn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvpdugk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwsfbcn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwswldu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycavnblj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfrddhz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mecpdllg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vhablfzu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gigchgrw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2polltvdy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqrtutp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mikhketz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfhdtuj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmfllpx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xseuvxyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzkakew.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaomomh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvffvbow.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfanpaih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2psecmnae.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxpgspa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bficyipd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiygrqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtvfzjk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cysbjwyr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sisuesse.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nzojndwr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdjvgnr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efayvgkp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwmqfrm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzjyhpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbvmbtp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vtddkvsc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfncpst.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2urxwabex.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdtjxgm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtznvti.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgipzcm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bvagyrso.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vvviohgb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlxausd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2orllrbcf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smvywifg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnzjwro.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaumtung.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sghthvuh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2efxsmvgs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjratro.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhddvzeu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxibwpv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmbwgz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwwrob.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehitkmou.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbzqtid.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aixpbfjc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvliwrl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2axsrnngt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqmnjbq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wolijptd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyjqsnh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuvdyke.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mqraoujn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ihffbnjb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zifzostq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlwzswe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwzsqsi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbqsyrs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrqyxdk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwaybqx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epmphnng.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwcrptx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcknlvpu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzycsdx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdxbajh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeaunyc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xdedevui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbital.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlycyqc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzsinuf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkaeqyr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijixmapf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyixnyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anmpilzy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ojinkphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trdygqzo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzotgoy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zllkbyul.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brmoktdy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jcramiiv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcstjlc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfnbegp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaupbdf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtrvskx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbgdbcc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeopsla.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbptmws.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzpemxe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dddkzpyo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eoobayvr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yibmwvfq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovzgfb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqawwjwn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcayrau.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2twfkeusx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2adxiwlhf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnapvnpq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhxejkb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncaxus.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovswgbxh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2urnogaag.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idcxgrqd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2stydpxll.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzmunm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnzflsu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2usbfbpem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvbvhlj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxqpkgy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrknwx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2llxwcpsq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuioudo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2strmvgpi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkiryoz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyghtqe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxfrue.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqctkchq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccygem.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vpheihfi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrbwtmp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkvotwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjydyllv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2abfkcvqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tquczcmg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwvoxy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2adnemxbd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2psfugtmd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcarxse.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jydcawpw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iobvymzi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhhynp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2plqxarqi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtnlppc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjicgcno.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdaeavk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrsdzek.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgffvgwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbujaru.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdmzdsr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2akskvcvi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzkfkip.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aoutjajg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2varyesxz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmbycrl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdyjqnx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2keawuyhf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaefbld.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2itneasnd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdrdnn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvcikrm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uofqsbfh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjyyero.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtfjhp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnmrzuh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2esrkyqmi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tdryubck.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aclyawae.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrywrho.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwpxvep.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwzhlqa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tycutevh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2btksojlw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icoqwepn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zroseqhy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2unhcgsom.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfylers.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jcajeicv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oackuteb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gduttngq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2apfsaeqv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgbwzta.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ocihaekp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpvztpf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqgpazm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obxectwj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdovcjyz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imcosuxu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrkgtdh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxcpymm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhlkfys.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svjwsvpw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvxmpoo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsctmyw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2agforxoi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzpeyma.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhueisqg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnejok.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphwdqz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yluflkva.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aefjfvub.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwadntg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaaohez.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvtxluj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyebiwg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjfarl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmcccco.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwejjjg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdguzim.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zndogqmq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfogzois.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2epibocpt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tncgrzhw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yprfksmy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzadcfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqmkng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfammool.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boggkvxv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glpyrpyr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgohyklj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmofvqs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlvqxja.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmndkch.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lepmvwyd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzqkmzz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgfyrop.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ordcffpb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgaejmw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rckqvovs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwdhlwm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ylffbqeg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvobwwxc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuvrckv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tygmwalh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czdnyxqe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydylgz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrbezf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgagfcb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sllroykc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbibikxb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2apfdbbtl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwccdfi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kisocxdj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdgrncy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaaeexk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdybugi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2omqfbphy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2loumefad.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2huhiwlpr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aynxdvqt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zofzbwlv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcclkcp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oopfgiek.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcxjstt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crgccmoe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvjkctu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eztahekb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywigxxi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpnzfzq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xukxfite.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjuwikx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xypszgxv.html


<!-- 参考信息 -->