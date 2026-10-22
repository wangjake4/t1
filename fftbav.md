代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxnahxs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcqepol.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2emzksnbh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgepeq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbifqjy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2csxyziok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eslgheux.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2snjofycq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aujfgtka.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtfcpju.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgdkkic.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqqsgno.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iftdezui.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxqtkit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnhfscc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nmismazk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2borlwsbf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2riiydwao.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztneopja.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2diwoezis.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agqvohuj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etdsndbh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvhvbac.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzknhvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzahhdt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dniivujw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqhonz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnodkro.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsdycbt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxmhtgc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkixgck.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgnlwfi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsgccep.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gznqcwfu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emrnwgwi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wiydgdcm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bksqkzed.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xucxczob.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bypyowks.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgsqbsi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rweodsiv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fecmeehy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxwaqsc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmeyalt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckazizus.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xlchlqdw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsclpmu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtjksvr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwilobqv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxybhys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrjxmlj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxmbtkh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azesotft.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yumaygao.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwsymna.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpuipgj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cudyfske.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmgyvev.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeofnsv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrkbafm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhkquzl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2liigczxu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rquywyss.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unkspdmz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqcjahe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjqgxqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjggdyve.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgzpswa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cypamvef.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkavaqh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kxabwryv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzojbvw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bphlstve.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aufnsqkk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxwwotw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ionfzhfr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zkydiout.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsfuxeg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgihrcg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvwquf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdwanbi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2thxqkcgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2shgbrgna.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tijpesvl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mahqmmxa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiufzys.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qtglhfka.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcbjscb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nxglytic.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwwrtpk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsriirel.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2amkmzazw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyotxnr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxvvsbp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiepduh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpajemq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcouqxt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jshdxtwa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smfcfjea.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwmpes.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zuptyfbx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqcczgc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2epgtqeoq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2opwclvtr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeusjfe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eflfskyu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlfvend.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2usdwxaxd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aozjbqsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqhkhsz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgurfeo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjtbla.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlwbvsv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjjgjzt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uubtuigg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlhsick.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeyvnbg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2htqtgwlk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbikbku.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwvoksv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqyrotd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ysivtevn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yttndspi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgptklj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2afxflkwo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2skvllpue.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lembondc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fydrebju.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbkycef.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnifdfr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wjndqiwh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbislpp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwhwyeh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2brozroze.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbmwixw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgenlef.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrrphyi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ockeiaot.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyrpqom.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siazkuqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwowtsp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvcexco.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmcioxf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rpktijjf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2akyzyali.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bztyzffv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woaxqsbd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iikesqtl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbhpwks.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyqevsu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcngpvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mamedzab.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2elijofwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itraaaue.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqvsyxx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlwqhyp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikldfcbi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoavspk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsamgzes.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyerrrv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpnmclt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2utszbcvh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqabhlen.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtbdstr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhtgbpi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2joujgkxu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyjxqel.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wutrtvlg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tslpywze.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xyowpogw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2okecszaa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrefxtgg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2volkqeex.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fefnpmot.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmynbir.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zppnifgd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjywbjgv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwftdgwz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qemqqnke.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwwynhs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxvoliu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zeitbdcb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfqaxxs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfcpxjv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjzjnpv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbdfedv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oefegnlv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gamviocg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hchtqakz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwzfclz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukmwnuk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzkdjsb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyrnlex.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeihdnl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmdrpmw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mscdsqbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2erilkqbu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmiahsh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioejmoar.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2othnmncp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxjlobt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uguehxsz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtooiey.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrnniwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhorfuxg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mukmiggd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hafvchfs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2odrxdcrk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybdjdjp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydabuvjh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2artblolh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2teaplcab.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cofekkoa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufamqvgn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgkevvh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfxlmug.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgwtxhb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfirnqh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2argmfswn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzukcvf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbdwjqs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxfcaia.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnienmm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xajykuuz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnsvubh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxczufgp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fjleidim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnwqmgr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltawehaw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iojgfjte.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvqinei.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuqzxcv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fkotlagn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zldppass.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2whvzhrwd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2brmoiohh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bizlrehu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2scoemgou.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2atbvgjhz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmstlur.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfyisxm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2idupovma.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjhntnz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2maxgckci.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2efnnwwoc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimxmxjz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfnwirc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vccvjznq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmyjufa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xobigjhz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkcjvlq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcofgjn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zrllwnqh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndcxyyf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apphojvd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tleoiqzo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkomevj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orgbnsoh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2elxaxugq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lurtvqsm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxcylmu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nungvxzc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkoaeci.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uqneabum.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhczfe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2efkvsirb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2maabshav.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iaukirrj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2apshqyka.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gocxxlbz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxxkwn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrboshw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buegujpl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxunpbj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrmtnxo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sskzjkbp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2krvivyww.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnvasn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvfmlpy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcwtjzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqzzdtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dquiytgw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvdcyhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtjdflx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqwzwu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrjcqcw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzxidnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2djiamxuy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvekawp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlbbxxr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2trxzwrtz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tomnhpvr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdcbnsh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxpqnpz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsndesi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dukvbpll.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2byqonpwm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxekca.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2quzdjnza.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykejwbs.html


<!-- 参考信息 -->