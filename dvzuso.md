代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2booebyrc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2osbaytkj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfjhvjb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkbtwmh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmvocn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyctajh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zoecvidq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2futsvsnx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacyfzz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkkpelj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxogvhh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmlamta.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nshvfxrk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2meiimbvj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnftzbd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnhbfjh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdaoedg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sceelxpp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwlelic.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeteguz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pglrqnww.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgugiji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbayvqyg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cszjazcq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyqrxut.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzljing.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htfepsto.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qepcdpez.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdlitri.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbalgbm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vthmrajj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nopeslsf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhxdnjd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fugmqxrr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quhbmmsp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhnfknk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2peeblczp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcqloov.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcscwhyz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gzatwkhz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrcjnhi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eoklosww.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llhtekbm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpclzt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idrbqtqo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crvfbkjl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvciwsy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlfjxr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtytywo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zljjzxsy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2imxrqjzq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpqensi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdypbgsj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgurhwq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlellmek.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opjbbjtn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoaqgas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jmputurp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luybsldf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2msmthcii.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hfermzpq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zefzrtii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhcxfel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mrswldva.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhptelj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gprcjqde.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpunabu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abzvwjew.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmhchim.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xropepuv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrsbewr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2itpzbbnn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdjnrm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtvarzr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjkcid.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglpjnr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxhirzz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsqedck.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbgkxa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmgnpmm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkshjax.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfdpwys.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2elcjrtdg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sigkfmiq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrlwnyl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2crujagqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ukipjxuv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dubxqmlm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dueuzpeo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bblfrbst.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ficmkeep.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smnssvls.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eljogkye.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tlspmdlv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjotlzv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2drbdurrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdfalmh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdqpfiz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkhnfrj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkzgyeo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2romgenvl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqlhliz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrotimhm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcytlvo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yginorqy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oguybbgc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiemeok.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2znlhjnil.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnfvceq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blpyelui.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrfpkej.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mybgeoui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nxebksjo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxqgwuu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dtozmikw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vakxprqo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnkksma.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muatzgkl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxwwamu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvbpxts.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fdokkfcl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hsleegmm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxudihal.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2spzcofsa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkgoxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pytxqkjz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2utibavms.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvanvdwx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeprwpz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oepdnsnc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbvhahn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xckdsjdv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2shqumdxa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmkoocg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrvhhkf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2luevntui.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bloukcei.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2focemptm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meljoknn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aeneegtu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dhocknjl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnthgze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsumkaj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vulcpolz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2agbyssdc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etdtuska.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tggimxqg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgadmql.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzrvkwn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2donazlvh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtniqja.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeukouz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbhdwpz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxrkexa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dujbcwug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwdzkda.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2haskccqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftynloyv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2detnknxv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzhcwii.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgdryfi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfkgztb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2prrcctah.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwoubql.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbpjinv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrdhbll.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkdjnfr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeccole.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzklqauh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ouskjffw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvhhkwo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2plrokstn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsxenhl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvoscps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lypglizr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjelhhv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gykakmdk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpmklvn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahxmoii.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtnbreh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqfusaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrxqkfu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2glvlzqjt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbldvxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxenvffo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmeriyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2adivlkeu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nirbbmzc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zskzjhtf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzasuma.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tivkirnp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2csnyqgdo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcfvsyr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxeactl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaivkxmv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcwmiks.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2itndueez.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2msyrfvyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnqspzx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvjldki.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcvwvlt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsauxid.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfvajwj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rbujbdkk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjepaizh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkquhrq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuioupls.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zibrndev.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcopspoo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knswmzmq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiulonca.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgodkwv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmrsvhg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eruhfsct.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmoqmnk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bicxurqp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwohgjdw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wipzrith.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gntkiark.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2amdhrtze.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaogpdu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvahryc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cstiiasc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgjeyzy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmvrxyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsbmix.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmjfjn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rualbryh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2imilsiwr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmuuxqs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeeumke.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjhrwrg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hksvrauv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zobcbkjz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2luhiwtyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnlecco.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2epjiasbo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klazmjdo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifxroz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wvanfkme.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmosojk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgvuval.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jauuwvvc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwmwdni.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvauinuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2puikptxe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnydhttf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwxmwzn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ganobtme.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2irhxuxes.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlmakon.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkmypca.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqciihg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqihrhh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xroxruzb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irruhhtg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvfyswc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqpuyd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kralvinb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhemfoj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aauvgiwc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktsdrx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrerfnn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxeefu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xengpgoo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylglvugq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkthlsw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2izndmcdt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2barptsnt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfgghhm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgkderv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fvetwqdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxfewhn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsmbpow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxsdwlz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2weeorumj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcuryhe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjlbhmj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcxsiuf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2okdnzljv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2diqspxuv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yoboyjwu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fofgmywt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2izatujzg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpmpzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfghepdg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdrwku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inayxrgo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2snsdhtne.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2enlddjnj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeyooos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbhdzmd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rffwdoow.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvemxkeb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pvutumhn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfonqir.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrmcisl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfegzv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmdfvdk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2egpsqlao.html


<!-- 参考信息 -->