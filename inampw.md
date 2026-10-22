代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvfugws.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaerbeyz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjqcxgk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfqpsce.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhlrhvi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhsmgvw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnazsmcg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kightiud.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhijluoc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wacfurho.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqdpdu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yumyyern.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgiftxi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfiutay.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tonnnrqx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxcspqq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzazolh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtmycnk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzcydgh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fmedqigw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxoslkf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzbypjw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrmauyd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pkregjbr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqkwau.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2btcjgedb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hvolyzkm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzpehjr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrbnae.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwminaiz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqkqgc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omyjkxrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsymkquk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ulucolsw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aumrghot.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmyzxd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2avqdjrjg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhytvyiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pcovnqvx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuovvpn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjtows.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhorysb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mghrbgbw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egrnrqdd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmudahth.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2euflpsij.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ycffwawo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhswgmz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgcbxir.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2giklbnxa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzoctse.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cioxvukn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vydrcmon.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfsppya.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdznaxl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otwpwaoh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjevarj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyhjwre.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrdefrf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2olcbgdam.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2guwhydas.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpsdywp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpnrvyc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fforwjoc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svrbhbeu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rykftogs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dugsszdx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2onpzqusi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuauvih.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcinjsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrypge.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnutcrs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhhzuyd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pladreck.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzxritf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkdpawx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrumctc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmhrkay.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuzcrcz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgwezgz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiaqdml.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbxsvwy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwecpbw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuggyjl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlptbrrv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctevlaqs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2btnxhkix.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hztwllgy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmdsbnu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqloxpz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iybnxqvt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xifjmpzp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nehteogk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaepbztl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqiizau.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jjirrbfv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwzozsn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2doegdjna.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tydajnfn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yebtishk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2keddzvjz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcimmckd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkliqu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jilqgmap.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtdepif.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyehrrg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbdkoti.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjpndnw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2biwgajao.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtyfiil.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2aafubznr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjwlgof.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxpqfly.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzcnibs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdcnflh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyzqtw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ieghelml.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqlvuti.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuxiruu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csshdjqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxizicwi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzswlfd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxomqgk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfnbaue.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mxstelco.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2scryijkb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqlnkdr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2djiueiur.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfttqz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vixnngrs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2unzxmfct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqirlmi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrevrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfdivlk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycebzjec.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iflmkopn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koabbiap.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszcszm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcftkdg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmlqmtk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kullchvv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoohfmp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiiobur.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vlptikag.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oubkcozo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrfkvk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jernqlnf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtisbkl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxdvjpc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wohilyyv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbkvwjj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2atxcavhb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbrjvah.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tuprvrlu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exjqvkwj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrcapua.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwoxizx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfalqhpq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcwvydp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thmtrskf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2phwyhzqm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgadpwhc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eptzoqoe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwbilfb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtgtsfk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cavrpsdv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfyoseb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpmhrac.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnzzliw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpypnme.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2unmxkuwn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwktzldo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlexhrem.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jskaiiux.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dymyqdwu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqedwvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxtnuko.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tikxmvkd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdeanmm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnxiiov.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoplubu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2epflxbsj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmddnji.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoauwwe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aurormbl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iptxvhtz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxkwaaa.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2etndobhv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkvptaj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdnibvp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtrifcj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tifknjca.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofrhtc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utvvxpjd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrddksvd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzwyjpe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2liuuoihx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxvgqob.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmjnbji.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ssswknok.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2szhxbmln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diqzckux.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzybqzvv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjywddsu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uaasvfrt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jozeqhgq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hphofzus.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfbbdgr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmrnmoi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmnruij.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxibut.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqtjsjw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcaenju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqbpjrd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwmmpps.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzbiccv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrupytsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yieqmknc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrynwu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqrzszo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unhjcpul.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsottkyf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbugcu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iohckauc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqbqmqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfwmbut.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2noeyuzar.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuuhgsp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2imznjmfu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmdjftg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfvuvvc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsncusko.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxxjoej.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcegpck.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erduteyo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftmlccy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbdxzes.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgqsnno.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwyjhak.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiqovyf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgofnda.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvzvtre.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gweexsxh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjvwqgb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlszfsl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmfwaog.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxnbeh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpcfrfj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuimxpc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vggecsdu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gibkudzj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2swaejnaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoiqsct.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2khfopmfm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylagxyu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tblpwtnv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnhiqho.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopkcpu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxanfkm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qbngsymq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgkuhvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnvhbqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxbske.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnabiybu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utaxlaif.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmvdxmf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxckif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qptwzlfx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2shkknptg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhevivhw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pdizeasq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2krmcdixx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swbwrsox.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbdsch.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kammtsst.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfubvtv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxjstbr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnhatxe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqhpzqk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdsssza.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaesiutr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdwlzue.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2muccpqjr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2acnlpmla.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkapjuyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoesafb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtlxlon.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaafapf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmdtafs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscwkmje.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypipagux.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2enzkaywx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaarhio.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnzxzx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dojlccxf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2scxikqpc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbiwxum.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vicpoloo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chndbfoc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiinlinc.html


<!-- 参考信息 -->