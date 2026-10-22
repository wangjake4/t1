代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxqjsu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eqscgzqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvprspvs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyeuqsi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jnirzrsq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqipuli.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdylriy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aewkqzsu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2excqobcs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhdwkar.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvefemw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sebuwcdz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trrtzixn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rewixaev.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srdtrfeo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xirdknox.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmdhyme.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgaspah.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxdemcl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2feiryisy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtwulql.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2asngwthj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pulxtkrf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vypcwfif.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwzvrow.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwqrauq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkrvadc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeynzwz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhufcoa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sswjgasl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqirludt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoursbhh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irqqmzqv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaadhgdu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zamaxggu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnyuwlg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjegxepr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodczsux.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhknyfe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ryucnexg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2omxsvvzm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2upnziopz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fncoovkw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slvnalmx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnslgvt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlqjjld.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lewfsaiu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dijkwray.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyxpirg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gtufolto.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raovmxnz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmqmhnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhbsvkg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwquaxmn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kzasnzky.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iujzmjdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wydarvzp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jucwutoh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkpuiuz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaxipko.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczikcbh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bjncoqbt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlchdyy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmuxopm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oilrllqp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ebticoiw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxiaff.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2erodprdg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wruuheyc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdlhupz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edszksoq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtjmmr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhwqeh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cjomtgds.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfgxezs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsxorju.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegbgut.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wdingeeq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2psjntayc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rspfpzxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wenhpvfo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2shoteuts.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yojvfctb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lckyslta.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvlhuij.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gjswvwfy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klpphgls.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxdhrim.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyeutrp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjkytdn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epokmope.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdqeydn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcxxdet.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwhstb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2polwxhzp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpodtv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2trtnooai.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2thydlokb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ynazwxta.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpayrpp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fksijvjd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dghxixje.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dasexwzo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fltpuxyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhkfklh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2huhptwky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhjgurc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehclivbg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxlnfco.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxogbrry.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhnxvcx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gmivwbbl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjfgipc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zheppnea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wahzaueb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzhjinj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yuczhplj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhbdcka.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tbivcudp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqplowcy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qepxkvfy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2igujogfi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqghsqj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ujismfmr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sslooozv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2azyhgzjl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsfeqbs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqhkpxh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxxehyk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaiwqeo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwpeezw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2afvbldrl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhyevlt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaatrsh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlqiklz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fneiqwuu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrkdnx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpgkphs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynmcfq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pngcvfnz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxooxmc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyuayhx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kytgopvh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iftoofnx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2reuarqbt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmndbmx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2krafllmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abzasjqk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qixgablp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqgbvku.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pufchsdi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjmpurv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhdplhb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zceszdtw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtccxye.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlyxqoj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehblpovc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ddknclzw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkebmydj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhkeyms.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bordcogq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djzeagtv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqzxggz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrfgriz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmadyjq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sefldejp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esxvrmmv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhepsqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwbljvh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcizasuw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznaaci.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgxguo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2smajpakf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmazbebo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2frlsoivy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trdykdqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwbopfq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ektugvrx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2assuoigz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2okpeasfc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2imisiggr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcbsuqy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvijbtd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jziiwfzo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvlpdpb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqljqpj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahruayhw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnydnx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoeyakg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmexuycf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2thgnyyyk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2apohrqii.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbjqjqa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hpytcbsj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2drhfegti.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmmqjjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2buomkfwu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlslsuac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrkqtxo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifraoskp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuodijk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zikjsxcv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvnpqze.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotxhqu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2izfikgxf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2siijsotd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2saetokar.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqbdem.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mussvuqq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aupfwaco.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2llqitcsn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyvwniy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xriuyscj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhqvzdp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lboeauvp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsuueko.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2giwiccei.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cojdnuqn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoohcto.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kogsmytx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxbhrns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbtbble.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcfzcrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkwvzbw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2msalusvd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlngplnd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudpqup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoohelh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2snyvgwtv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjtrytl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlnfila.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2riagxpid.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plylybit.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvvogjk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uyklcdbl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwzkcpj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwzooav.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiprsnq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqhxkpp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yogrhwvb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2estdpksx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhhwboo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sigxwexk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdakatbk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiqrqip.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtycwkp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzucxmj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkproknd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazxiac.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgzcyog.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwdkqzv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2msavhjon.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uijduuty.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxtakbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2htewefbt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdvofjj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsqlqmj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2taryzgpe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzsnvxb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kplimjyi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjvzpxm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2idvmursz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpjvhb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2likvmcva.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymauquqp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyagqcp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqvjmey.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgqxzzt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhazxdw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2doyfgfme.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtecukr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkppwhf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxfbsfj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnoxfpu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fowgmjbx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wlozfpor.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2klfbyhnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaadzea.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsavvjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvttxhu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuldlxm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzjfodf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nezylkqb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjkutcm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjitssy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqmxxnx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrsokku.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjyqtls.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqrjeea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vuktuylr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cczyircw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzysarl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blpezdqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyxdgtm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfithnt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnqexlh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgelwts.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2myuwvpbu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czihbfjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfbqckk.html


<!-- 参考信息 -->