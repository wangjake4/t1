代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpbbcgl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmryche.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvgcvdm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eipgvimm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bihevpwq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxfreeu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uonryeaa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yelbkecz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvijzdg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pmifxhyy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzujkdqp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgsowwk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgxtpyx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvlfxko.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grhfjtqb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnizmrgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chcprlcs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gjblfztm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clriszww.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxknhjj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaztfjk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxcxvad.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxzfyas.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uftusedr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzuifma.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyogrhbr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njyyngcx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jieabyhi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlblobli.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmnjltb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzveaac.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbobwdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrigaur.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2spufjkyl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2suohzrig.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfnysps.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmbpoeh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2stmxepnm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2stukxyhr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhdkqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2schnluha.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vutihurm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2opwcbtec.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jndqcjcg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzreggj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzyzwnw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbhuqum.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkvuuqt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jccyknti.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hoejcvze.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvbuiyx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2azwvcnoq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uywpvozb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oatbxejy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2svlkfnvw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixnxmw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpetdwmr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfzdsgk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jitrkcmx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jyptjhxd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vksmgswp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pimsnexh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyznkmr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevjxie.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2slndxksc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwknwex.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeufxhi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uieiverz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgykelb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mlytjenr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdycnem.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uixpuzsx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkudljh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqblqnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zawsxyqh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2velrzocw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2knhooxik.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeyjdwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qvchptod.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkbqvjv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyeggmb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bitaifxr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvadisuh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pgawzsza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqdvdbt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnjpncx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbhchjj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdzeedp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fuirapve.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haixnrac.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcutyts.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kxicmykq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nniauegi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhnfevz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvytkew.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcolqyz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmhmddp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnjvwon.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sihhbiko.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvskeko.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrfvxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqppxlo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rfijtubt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2susfenzm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjnosy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhceyqg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2udrokqsq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdnvmhu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2efxuqhzf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdtczp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2buxzhazr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qsktewkw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwkduyc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeeejme.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axfsyyln.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kytwewdc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfkvdpj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlazimv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxdrrdx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrmqsdo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oykaphyn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2saevnxlv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gqupuqys.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gndnlxhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fasevywq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pndrvqyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcflan.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrmuksz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnehhnl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zghtmzxi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zktjcety.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwtdvrk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdwdqfz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrmnxcz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2grtxfqej.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbuxanq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zgruivwe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xlukuohs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlmpzsl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbxlmyo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbfkmer.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rapvsnvi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gevcfqpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hifkvdwo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qaskarhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnaqnyz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cabxrjnu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoejrfj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmjztzj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tyudndfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgwpyz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bphflueu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2czatspcc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2krvhlwyq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzpalig.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcywufbf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcrubz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnrisi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbbuyzd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjhauyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgjlewa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gcegdwry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyunvyt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jooktjsk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nuclnjej.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcagomix.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbihvqvq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qghfsvgz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjcdoew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqppzgvb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyalrni.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohergo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjqmus.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2quqfqvyv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyzwoky.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2klijucje.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2asirgbyo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nucenhsv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxfdyj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdlwpvz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbxdppt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aryjhpma.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2umferxhk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbmqkz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkxifuy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qouweasb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoqgeck.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2peifpqwj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfkymyz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaygsdb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehqgsxf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2emgoxfle.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2usosvrxf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxrdewz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhfwdyp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2izktfusc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2llplfzgs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2utkknbhh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjbcad.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2moamjdxf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpjkqgi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxfsiii.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcxhwaz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bucaluyz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmmfrz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqexndyo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmxnwfy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmkbpzv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2idmfggqm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cyimucmz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kohgxiqw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aczlzyzd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qntukujg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fopkippg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuuiakf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmzxroc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hammgpza.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavooraf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvskshg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhngcnum.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvlrxrc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slzbmuon.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvenhbv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwhuwqb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzikhzd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zphxalrr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2quwlirlr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opebwiws.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnywgevn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zsybynxf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqekbdlo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2opqatjxt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvyuyfl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwqkvgl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwqiwdh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yepvuedy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2upviurbr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxuygsu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsmaqba.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxvjhdw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2elfhasvk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iztrjvzt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2twiswuqk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmnpgxt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woywitvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npstnacl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvbuapy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjebnhbe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtinyesl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyhqplb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoafmudr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhdjzta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemubws.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdsyrnz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2azioglcn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2govuxhta.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzudcnj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpansmtd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfodyhli.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ancwzqlf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dppfhiec.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgoxjat.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaitvht.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dluzfghx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbsanyi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcatiodm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2guuzcibs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbpodbt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uubmtzva.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ynedfxok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwvdtm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjpavsi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbhdqtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egdoninh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrexepw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqfinte.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaarhkk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxmsgtx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpydhci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnutsrs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kaucakqk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnfwrqz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgastq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyjdafx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcpdikk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrssrqlu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbfmseq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlclnehf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mknkxvwz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghglfdr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2obfvunfq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qouwcjsf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aazpqlkz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbkxqgm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuldgqa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmzhahv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbpqqwu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uantqxfd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqvbjdm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchvzglt.html


<!-- 参考信息 -->