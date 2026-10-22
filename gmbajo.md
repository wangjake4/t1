代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2liwayrpd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iseoqnby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyfmvij.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkhlbyz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kighslrn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhywqpeo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gafytwbc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djjiekuy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkbfqhn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbxbgmk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fomowtuf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rofinlqk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2towgvuor.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcfeklc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iejdjqcd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qouetjpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgkrtdd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eahyzntg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxxfmmx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmtqjls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugojomnx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgmycsz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kirrlbdw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tymobaid.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqluzmb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhuhjer.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsartvq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gowmioye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzrpckl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lttijphy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qryhhwiu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tseekipk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiabftp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvqkqfq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjnkxdd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkqozqc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfqevxz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sezrtrwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mczurwxo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhzehik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdxuhbr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqavcyg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdmwrs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiujtegs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjemvco.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2axobaepn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qfamwymu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrknlrj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2afpwjskn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iswfilvn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kurbiqqx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2igynwovy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iannauoa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgbjxl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmlnfrc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsbyimw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2saivvdqp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2drisapdy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rycjnzju.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyjnvoc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kminlrwf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xlszoumx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lboenqkr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evdaymny.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzwvuar.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2usbedqqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiwvnvc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwtjmnz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbqbeqm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuwyqlu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdudyali.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwlsqqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cwathadg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtgkmtk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hennnask.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzokgld.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xzntcfsz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsmbflf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeraqwt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2opxfcoer.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuwezul.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kpstdtvl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rtymtyks.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyqcuse.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvlwltn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhjiwnw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxovtr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uduchfnc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrwerhf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvjoiya.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2awyvwsir.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2blbhkuxs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oyffwqow.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuexfyg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbovfmb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqfaloi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfnamss.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oaskipgc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpkmksx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tcelstha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqyzgxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cboybnhf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxbpuxm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqdonwv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxsayd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcawbhyp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvnjhdc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaayngi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kesulabn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gqesnmwt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2diszbxgj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2peumfccy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vryvnjkc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrhlgya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oexahcaj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfyeofl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2venoxahl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2djsycgsv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgppqejs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhleitid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2trtewcoo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzttfon.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzxqrop.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkmvrbn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zonjwoal.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2baekhsci.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxdgkrx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaskgsy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdphmsrn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2arkmlfdj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vflnrgzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unshdbtr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xljllnak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igskxnxg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjoarhp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmusizc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpyhacu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vurfydyd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcbsrlv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrorhmj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2shxzpdjk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrgbqrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uadtkqfw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2snplhkwg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndfydo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvroxdb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxgmebk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kaozttoo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2marazcfq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzpshjk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffamylnj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hbardzbp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkfpojj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2porzcqxi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixalxkax.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzppofb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrhrplj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izvrljjv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2glbuqrfp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vveexoxr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtwhqlf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2msjizrrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsrusdo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2onewcwoa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2isesmfen.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzwslbo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylciksdd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsjfxph.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcuxixt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfecmeu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdydbqsc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjspkeb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdofzsay.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsciblbl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2audmejly.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogelou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uciayxoi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2viovolee.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebawetdd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2snkwgbuv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nedbxdyf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyysxlzr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpyiekt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dklikbex.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2udmkjfou.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoipyuj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2esghvdau.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2clhazpfq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfncrwmd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hurquauc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpsppoh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgzdnfn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgasqagy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yovsxojx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwydquw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdqsndx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsnbnye.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgglxde.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsfierq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrdnsdt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbptkuj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtrjyhe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfnenkf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2npazzcew.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarxyfb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxaantu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtjplyy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iowftzlw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xzihqyxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azrbvabn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sebjcpmg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzgheix.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzjszko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imemkfvx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpypxpor.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqskgcay.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwyybls.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2avwutvyl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blqhzgqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grtzwasa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sroazugt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2furzzftd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqfuqvh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlooytu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwwgdst.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2apkgosvd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mvslqfue.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwshqebk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumsvzn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjovhkuv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjtxgz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmwdpkr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhlsner.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsipxkk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2leczffkv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yabcddcr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprslclo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkrvhop.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbraiuj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bgizgeyc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tybwslpe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgmqthi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpadaaw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cegcxcce.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlwkwgy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtbdnop.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqmbyed.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cniuppve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2twnnbtwq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyxcguq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyxepwl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gawrsmol.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsslrvlv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvpqkzg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjhpbfc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nelsjcts.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqpncub.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiniwtq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2whmpmwre.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpihcvpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtksmdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clqgwrtv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2skjgltol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpepklih.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvnykvn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwntjnw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlfjlkc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uwftzwrk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2azngjmkk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzhrqww.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqfrdit.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqhohtb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2smjwdlbz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyghjwj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxvqgmj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbarfvm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2evycwuqk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcmdskc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvpivaq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qznnywfw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcktcum.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pctihcii.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uscsmzyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2etestvjc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zucsuegr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabyufqh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2avslfceq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wefqeolc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ribwcwae.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khshktax.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcvlupy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbhbxfe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wglgmlud.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpirsytj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzejbtpz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyttwjt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2soykujro.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlddqsp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjarppow.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiqmcrk.html


<!-- 参考信息 -->