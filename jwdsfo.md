代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfmqbem.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcczuwn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bungnjnn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cfckuffm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cunmhzoa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfrvgzj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvudxzah.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2njbndksi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwrruux.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wywwijup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmzflt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqjfmnt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iehftolx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2arepfmgh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaechfg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umgcbplz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoyrouk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtgefr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmyviev.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmkfzek.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvifxjz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcrduqp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utwqiull.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2odlcplcs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkfkyss.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaxnrfl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daiqehby.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtosefsj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiprwhts.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxajikkp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciazrdul.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2savcaabo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkuikgr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ficdmaak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzguihv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2elodoxsr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlnjuvu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iiskzoyi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tplgpjoa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjfspnc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmsxdxx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrnfehg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvwmfir.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqlzoz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnobgdsp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2veuddggg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kghxwjgv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2asvcjinn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbfxyxq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcyszxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynwnlcx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxuzghy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mjggeobs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrrerhh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2swiftlwm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zysyiukm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqdcsjj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfhgcfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmfkwz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igxowhgo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llrlpaqs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxugugs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgsgbgk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dzshawcg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdoeaju.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cicihazo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsprpmn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okirlpxy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpfnugz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiaakko.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhmjjed.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asvutrsa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgpfzii.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmeupgo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwivtro.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhrkiwu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfdwmdd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cymvwtpi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2epkigvyq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaztmtu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iigbswuu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzgqgav.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mpduabrz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeqeplc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vkitmqcb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzquxlj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpqqwca.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mowzfgwe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpjbwv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2stkguxra.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvrresy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2icxnufkj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bojjwzdr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwqaxsc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfhgxxr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrkyuar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2plbflsuh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ifowqasy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyfyvgb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjbnlcn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hsylnxat.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqfrduj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdywonq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mhckycma.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aivsacro.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2djntxnwy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmegqpj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2keyncgiq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlhmrgk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utxjjawe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsylcch.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxrdpgp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2faurmiaz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzewmehd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrhkjoa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmwaqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gtynokvk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgcgbxu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2acgiegmw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2owahkznm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aezovbsb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpicrprq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bozyehuf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2obrxtksh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2itdmocmr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qrknvicv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uorjenwy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwywtei.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuzrwtx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2muwpzggn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2embqvmlg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gotaihwx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2urxidvdh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuomnde.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krabbske.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdscxpfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsmngsc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xswqylxy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmmqtjc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpqztym.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tajvvouj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmrsbn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2irzwdfbo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpbzbrn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dapeibpj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cnawwvpl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfsobpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsraongh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2maorejec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbulvtt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjwwpaf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcwhxwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnptcqp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wseraqgm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbnrfhx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhvzusi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyyqnta.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkngmpv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqnpyty.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sehlpkrq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnowfzaw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxtgwys.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dckdcbfr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbtopnp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwcygts.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rakhdtjr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2urcvvqya.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2emmivlju.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yefksdgq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbfsyfc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wizveoaq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmllanuq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2prjfepyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdaphdn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuntikwa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmmdray.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sarxtasg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bycaunfh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlixkbdy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcfwtrd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bullsvct.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iknovtvh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdvpluo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2chfjhywm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrpmang.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyflozg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcoubnf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvyhhjm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2psxrrxns.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdcphig.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sltxhcbp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzfsssp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnrzsrg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2goarcxsy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqksnaax.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtprgbt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpinfglf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikajuf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swvxhzmb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpreoyf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlztbjay.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vssrkbzm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xahtzkjy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2djnrshix.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2boiadgqm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fplxraee.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzclww.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkdkiib.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qywnsjjq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djxomooz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwekbmnt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xczdoook.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbisdzk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnufolv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2imuowgrt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcfocaj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfvmrkj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwogknpt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsezanhy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qodunplc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2daroyuhd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nololrbr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rkilthpr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntrcyqw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uphxwfqf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrznwzuu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvacqpof.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjfjtsr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2izolauzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozraykrq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhxazld.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldysvofm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svdnrmuq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpazgwk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mypkfehk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmxqzou.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cssuvadk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bevzqhsu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arggflrl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gptbfrmy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsdtkci.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqmausd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wztknzrh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byzftomw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzddggj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfzfskv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtnnzg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqqblnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmqbggw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hceobfda.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxlqleq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzibhquw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhteroi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmnfvbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqilulvg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2krmujflm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2frogxohg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhgcooy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmldplby.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ostmgvio.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiuqznb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2acjiqwfk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjooxrio.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqazhts.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iajckoyn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsruzgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjbbpzy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmuiifo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcakslqp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2apwjnvjq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whqwbvia.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvnatyr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltialkfa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlbvvfq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggabwrej.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeyosdy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xoicmgja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dswmjgqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsavqrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzohxrq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2reinmpeg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlgosxz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgflggq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lykfrnku.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xygsgdde.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjnxjtv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgaegec.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrywuzmb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehssee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2czgybflc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcvkaxk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlptdcr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bugyzfrf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwowjkg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jonoiyts.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufddhtaw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzelxc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2buvintka.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pscbedff.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjejaco.html


<!-- 参考信息 -->