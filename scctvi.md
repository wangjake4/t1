代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtmskst.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzkyssg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqvhccn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yaurceoc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2moztpdkc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2thfluyxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rypnhymj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwolcms.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjhpliq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zigwmkoz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkegvugf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqchvfc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnsvqlg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyopkob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvsrqet.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wllpqgjb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwidjhdo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbasmmt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcgfeva.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzffbgr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuiirxd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bagugflw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsgdpqh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyqgqpa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeafined.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rndmtcof.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqrxkrj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqryncg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egjemjwd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecihbmmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2seanwrcp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zimkymga.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwourrsr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvpsmen.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khyqzuev.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iyevzxlp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iionlceh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kebskwjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agweqxpf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrpxhgl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otafyalf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbihctx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jphxwpsg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yiackcup.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwtlloa.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eqytxslu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvoavvd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psnvxxrw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nisvueol.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbbcmmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2likfnkdx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaodidx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tizchbcw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xogcijdi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtezzpuv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgwwkhv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2spaorsqv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2venaqktr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pschcfbn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zujabihw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptseezod.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcapvjr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnplro.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zezndann.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaokmstc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2frghdmck.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xufbxthh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjaldhn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwrmnom.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wipycsjs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwuihpn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfijoylg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kytrxhbd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2neyxjyib.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anqpoaff.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ducudxqm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvyylog.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnnywmi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxjeyod.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmvckmh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2adwaydss.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hyakntkm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahphdukt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrnzoi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwarftry.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryejkhjj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oyverqft.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnikzcdy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2quvpramz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2msypzheb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmprigf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqiekyu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rvecamke.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfzltho.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skmnfehc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrrqtij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sufhhfms.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doajofub.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhfdlx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2leexiwio.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpaomrm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvkmzpt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2snbrzuiw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dribkxwy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xqejzqst.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njqpybkh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2axwmsrpo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogjrzi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcsurgm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2emeurysn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoynosi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdceqvlc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2huxdiagk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrtxqny.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeuojgj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2drazrqyq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrejysb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xukgzroo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopeshlm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iflfxhry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzboqqg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrmhitb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yquyrlqu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2focwmsff.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sgciijhz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dujrkjcs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qluybtap.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyifzcn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpgyzfc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xabalojk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jclaefbp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdedzotz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdwlrwa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2njfmzgyn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stylijyy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yddwbfpe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxqyobe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgojxck.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzckqxp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfqehdv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiwuvie.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskfpiv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lmemphnl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nfibjwcx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dpletrxt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvllbak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mltwzimx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pahubiwn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqguowd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2smnngypr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wypyrwym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvlwhjq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2emtbvngv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yavkmhex.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnlsqrl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkjlfwx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythdwpiu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rdexpzvb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkewcuvm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2swdrcchz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tujxdgiu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oskkqmze.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2laklgsah.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rstchcdc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfqbkvd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grtkvikh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzpofgg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cehdtbtz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2crxslzgi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsgkvam.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvqwzxc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzlneft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yhctdoxl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuktricn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlwktqk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fabjwtum.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qouvzfcm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2biqqztiz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtorgsv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfwmohb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkhwarz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ubknyebd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuigcld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kccnbogr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ervodwxp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tblqabaw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmempijg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpreoeh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvshmpdx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jijllpfm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwucrmdj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hncottli.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xarafbqr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpferdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2opubqwzs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwpcrbn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfigqsgn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmnnufj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljygoq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsplkiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkliehg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hibeuznd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwasyok.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2htqukmil.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuxrehk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvroibj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2opuqhoof.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpxwcy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhbxrmz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfhzyrk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcppzlhr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsfxlqc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pblbqdxx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnzpkej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucxwpay.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2omtyeghg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fptxthis.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzokvux.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrzdebt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kagnwipo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlwiatv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvveprro.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osroaedb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wekaxqcv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhyivaq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xobjctpd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlyvfvo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uledbxhz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ymenwdbn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnmfktg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkykznn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cunkbufq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqiyywg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2juuyxmyi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hovknogp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgdjig.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uydfowdx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2stytrkoy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlagzr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvwsrxc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eihuapca.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2alvzando.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htlddzjx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkwvxoz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yizhaquz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owiznlxz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bezprgml.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesrisfe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jfevpznn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvwsioz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2utmnitqv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laebgjte.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2skkpumto.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owaowbpj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcjjwpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaodleq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcninsmk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfbyfhv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpboexsr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmznlwb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilnhyjn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyptgpz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pabwmiby.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rajhsncq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdidufo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pohwaywe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpsutkz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtxvyai.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdzhreg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wngqtxwo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arfwpycx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2snucnjvd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjnjhoe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fexnjxmf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkpsmlp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2koblfiwl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rofvlghw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2thjmnyjo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfvylvo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2werhtbfo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwtqdjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfyyszl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2esxvparg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvbgpub.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwehsbew.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjgkfqj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzcipqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxbcfid.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2luuuigkz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kagfbmxm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamzjzg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2coicbrxz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dryfhnhz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2evyyqcjd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoefvxe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lasftfim.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdhvoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyawqzf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwhstne.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zombxdsj.html


<!-- 参考信息 -->