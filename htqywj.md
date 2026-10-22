代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kloaxval.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdqome.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwnrqya.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqjyfrh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddtrpd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsvephz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2elehmyvq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlpkczs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cccrtnnt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoxocvv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uocahchh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2phfnghvk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2clsshxsq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2thdscoxi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgflhdl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbrflzy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vvucuxig.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjgzwxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihjjwg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfguwfcl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsviwoy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltkcwj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avfljbjb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juengvsa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oesyiqoh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvrduk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdntjkkl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eameqkyi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpszsqzd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gyljhpak.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lktsnxqc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nuboidpi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glczjgar.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kblxgllr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmzhbeu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrllyngt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2werdzgip.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocirnare.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgvlxod.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwojxcwr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruckswqe.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhpkpr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpthhupn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmitptn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kukqwaiv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jysqvtwo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gexfmjcr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ckssaojr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaazjaao.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjjkyxw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgtqndx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnimxlo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qplpyaea.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdzdlhg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2egrzfgdx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upunylsl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfemkhub.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsskikm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jouahxhc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2phuorfmv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjofaiz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vjietmmg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvjpszx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqkzwvg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbclzkpn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikirphoe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vptmpmmw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhdymoi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stmfxotj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfrhlcj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wrircplf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2thcnhbvb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwdkoya.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2htqffktk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkjvbjp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvcdpjw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlxjhqr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfyhjks.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cywwfjux.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txzcghkj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2avpurths.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lcllvgrd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmabya.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qexvowfv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpenlj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnppepx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqtzztw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnsmfbl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vliceakg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxucxycm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxysia.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqoxfng.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpoczac.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2grivusfm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2innyaajb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2udmugbns.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mawgiqtj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqygdoi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwureqtr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ampbvsij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tufvoyaq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovixxkob.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpubsyo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2povrutzy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2akixiegc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tolqcexm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnnxqmv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpuvjxn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlfdzan.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmowpwui.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oalblccx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2etfnjdir.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsnpyzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfqsbga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqolprh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaftldb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxiyme.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmjrtpy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mspqcprr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2thghdvbm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwozfmk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2orremsgc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkenmpok.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eluiuknq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbgkkha.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qelzmumk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fyehzavz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtbtoqn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbyaynt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpueiaad.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gflthgdl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pntqeryf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uegrdzjw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2koxnnuzi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kojlzyvn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnnxelc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdudvb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzemtqu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eynimvei.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzvxahl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaoufac.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2atyokthj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hokcvogx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipafmqnp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrajryj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2konidave.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcpkav.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcscipg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oomxhenk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2etgchcnh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czcxagym.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vztqlwqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2doecbjum.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pobycgbc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcppgic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmuekg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgzceex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftudrwgz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzlykqt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tilhofln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfjmnlf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nithtxug.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrwdqlu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkcihoz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcadvxjv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2goporyip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpbdhvq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuzldpd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexifpj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aljdfplw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xenxgldq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uieswexs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mejfokmn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2motpdnjy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcvxojl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xeahjaog.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hhztwlol.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnuedwq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbcvtet.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxwlqgx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oauynbdr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bljqhyox.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxgfzfw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwrxjty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzknuou.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvchkbum.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lieibczn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmstydde.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqtioju.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgngtepi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bexgmtvo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2plswcbtt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trcwyarn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xglartil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sunoolfr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afbcezbs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzoospv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aedibnru.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2docmcrjp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpkexlf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhixrscl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2igydxmem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpttdyfx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlvkdcj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nprohqdq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdqcvrv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtmdvyh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rziewhxs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzvnqja.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeawnhr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyzmrzz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ignzhmpn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtztqals.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2usefrpel.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdrurex.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aneerrqd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwgjzff.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dygczgoq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2femhdbgp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzdymar.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vvihlzid.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gfukvdpj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2phpzpxjx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxdmigc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvvsqdr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atstzldz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhbgdoz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnegokhd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ixucyyul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unthjtnz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pknnvcge.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjjmfzl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2stqfctet.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cskdqknr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvdrysg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qppsmudb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzrbpjc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubklhqki.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvykjyj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2scstdhkr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2daeghrop.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyrupdk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzoyvf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsbekgc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mriegkwd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbndmiew.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2artuvqvt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtazaxde.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqnkzqr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkpugku.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyeayya.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2refzgiff.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxzwugh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qecetqyz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qituwrws.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpiozac.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dacjlmls.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuujvwb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbnuwxs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nauowixy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihupkcs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmnzxgo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwtacjz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2evslngwc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfygyikt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2djeuwqid.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnciyljk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2awcdouzx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqvxvkn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vuluakwa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2randzenl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fcahvwne.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzvidqb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkttdus.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fegywpwi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjschsc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvtsxdk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgilhujt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwhcxl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hnujpmps.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpykmgo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shldcwcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmikraj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjezbtde.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lklzklwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oapeiekd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvrnfed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaxpprf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vderzxqs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whgkdsgd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsedudv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsrdivx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjhagtn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2josihttc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cuntxrpx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbligel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaqewts.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfflgupc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxukelr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhslrmym.html


<!-- 参考信息 -->