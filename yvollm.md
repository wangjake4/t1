代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imazpige.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuemtcy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmconfom.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmuxabi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvynweq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqenijoc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csiqzkhd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkzfjfm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trijsbud.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2syddqxgy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcmeqai.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ndizagiv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzczppvi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2diwnxkou.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbclqerk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvuewg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqifuozu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zaprspxl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zevjihji.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfjgnq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2usypspsk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsbmiql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xylmwmza.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjluaik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clcpxnsp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdwwun.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdptxkih.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yaljxhyo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcyjuyv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2etkahemo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqkyunf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dadybyuf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apbpmbtf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcvrff.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeuqcfq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhkayl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azfbkfau.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjyrmov.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjkfwxv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2klgdzjpk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdunjjd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2foohgqhr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzhbqvt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dshigexh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkoovql.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjzzdzb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfmzmhc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kauhxkzv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbextwy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nulkhlco.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2devtkzrb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eathypza.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zykwcthe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jtivwjuj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpgtkmz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hhraassb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwecbns.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgwrzug.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcitkgja.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkqftg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cryghmmy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2chlqloyq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjvkmws.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2befclosg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqliwam.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kirbkede.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uibuzyaq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2maxuxipp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjarexvm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmrbrep.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilplnewc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xueivnuz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjllagg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ynimfaoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrbcjys.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhpleqf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2otsouflc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrwtidb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrvczdd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zkczzles.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbrrrfv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlizjrd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czsvxrzc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvhwqxt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mrelibpn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2axjwpitb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhhjjfm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2enjywmoc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2akoqkgsx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwnaskh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2epnfdztz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfujtkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tcthyhzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2viyfhavs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxvbyb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dymcdktz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnriyev.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyfzmsw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aglgcmco.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wpetigmg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyddaqs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gckziqnk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiklnsvr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcgijk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lkchnyzc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfmzked.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqqefbd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vprmxcvx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2puqzurwb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjrtun.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xakqegjq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aycmefwv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qzovxlfr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlvkhrm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbjrlw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2anthhhzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsmbqgh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqtepal.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fthdwaas.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svjiirhh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tequyikx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oidrgmko.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hciqzdzr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iphxrcfm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlvhdzi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxcxffc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bhypmknz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpwwyo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsrcouz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjwsraq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nsarmlry.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gjomumdj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyaegzq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxcuqfr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvxglku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yemkbhff.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jybchaur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiiiken.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaguvdb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2okrggvli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontgymbh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spvvpaua.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjslopj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcnhali.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxxlsgz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcnwzwz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqhqxjz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qyntziua.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhcivkk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzknrhi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjkflux.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrcrjq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2suvdouvf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtnsosh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqtzldh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfisaare.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gadkpmrg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwrlhdz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbcjxse.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsrxjkn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnkhdn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrvpfrm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjctvul.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeyfwie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkdubjk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiumwvg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wunyftxx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uttqywxz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wioaxmxx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmwnmst.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkciisby.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdlywzj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxlwetz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qihajpzv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhlkydc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqnzspk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmzwyo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhirkwv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcebchjy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2urfnjdwy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2labdlpae.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2piojhkwq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrvzwgm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bqclluba.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdkiqny.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmovhzay.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdwngvw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbvsqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoomawla.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2quauzqin.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkryrdk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2obbiqmbz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2azlchkab.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awxlqgad.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmasaj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucckcztw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2plwyzqlu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvgwie.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2doqfwbuf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkstqpc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjqxmkv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjvevde.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnxavbn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxnzlev.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2spzizpzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmylaxl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajngiznr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qryufdsx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwtehni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqdwrqp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxgldsf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmzbnnv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2orrlqsjj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoojjqb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fqalevbv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkbuoxm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hologsjs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdozxyz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgnzmcx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pamrlyia.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszqlqv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uomhnlvy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hixwzrxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sabhiyed.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nldufrsu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyreahd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tocgwroj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2haotqamz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjtwqcy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcjrqfb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lquzbenc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadeobat.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvehupj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acyfpqqh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2emlkijsb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ionekkgy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlwpngz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mclznqzm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgszrnc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwneduji.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqlfvvk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzfbwmk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2efmtiqks.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmsnye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcacgay.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybcsxs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjktifu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2prdsutoy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjwhmgp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcrlnqw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2smsieiln.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2orclmlhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmlvwti.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sebirzii.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qinjxivi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnmbuii.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakgnnwc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaktlbe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoypbhy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dloqpvho.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glxikqdd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvkfdwq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzbiwjx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbfukm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhrqllc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyrloud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2stnayiwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwysbcvx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pglesptt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpdaanm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwyyjjl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxeordb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrdyznm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwiycvq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2imueyski.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2launioei.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2knajfkvy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtiecgc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmazvut.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfigpbp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpeqimh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okgkvbcu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyrfcyg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqfvnc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vodivqbm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcunlsw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwphpdmv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhehogsn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrjafgq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2swutnnpw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pemctzll.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkkrqfg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnmdnpe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzubaww.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvyxteo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmylqbd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uotfjzbi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsbclln.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxxpdct.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yteommst.html


<!-- 参考信息 -->