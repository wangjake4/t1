代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkxqzoq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mdipnfrw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lspgvmrd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphnblc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbyewb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxkjtcw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbfmsip.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nohypkhn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuvism.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yngteuge.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsynuwh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2szenxytk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypnwpr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyxgbcq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalkgady.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cauhovnw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2harwzkqh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkeqrrh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aazxixyt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kitcztyn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mutqswsp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2krghofdc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqauex.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrcxskh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2doxgpbdx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2flszddbn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwitmnb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoruidf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbwhab.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuzqhag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnzpapa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ueksqdfo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btymzejn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmygjzmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lczbajds.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wexjhesc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmxnszv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqrlreb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwjwxpk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncchcb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjasqgtz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zefrldcr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adyyczxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnbuvd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjrmwko.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqhgxsj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrychxp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2drabnfwr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzqbwzy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyoephh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtxhwmj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqebbxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmalwuu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqsljca.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnqimwg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwndogxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrhqedg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxsldod.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjqftkm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxfecjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrlwcmo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2btdloazc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2klmnizrw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hisaqmoq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwezwpq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyhfwyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgpibpt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hokcldwz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikkvlqs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uywalhcc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zavpoing.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwreuuf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufazdchz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fpshousv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wcljaprb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vooihupl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2clygvogd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2viplgwcg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nylpwdfx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azxtuhjp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkxthaw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2utaxtrhl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rfatvibb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwsobgn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xeytovvn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wroevaao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wziqnbkn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkskvhac.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuoydwj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2foioxxnw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayotidzw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxzomve.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2voicphyk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oneoikvu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eorhvmcc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2muvawvfs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2caaljqom.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxvqgkv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zelncehf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmrvitn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2djzkxzxt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkiahuy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awzmzzrb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuqbpel.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2goxypyvy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jaornuzu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyuaywk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjwuohm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvmvoct.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svbjbpuy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkhvqjn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyllluo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwyngux.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkhaxwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tertfvdl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdkfptv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyvqvxw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwarhby.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpswxat.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2plchaqtp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyurmak.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pskesejy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2umcbrlzw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqjoiva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdtrjsp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcegykj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwykgncm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2baxznbra.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrcunij.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2deglpgqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quslgkyl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmvwimy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdbbhdc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sjddbubx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mbylycob.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtztkzdl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vupcworl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sryprajl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxgvztc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rpewryrv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aeczvxvn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbbrbdt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdocqom.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmxkcpy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbyarlt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdowsqrr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2okllxxfh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtscrkfc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrriwcb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2utqlflha.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdjkesq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoexpel.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okfvhigr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cpauecnh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwrcjpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2remqnlen.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhzzcyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jerjftvy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkpspjx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2veshivvw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wquirzew.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwpxnxo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkfcnu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqqrwht.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvitczzl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxpmtjy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qahenlji.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixygicud.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjttqvow.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwclgar.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrgtxrc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhrgou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkqjawj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrykueh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxtudhc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2phvfktvo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qequnhej.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrkphyk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmdtyra.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyntneii.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkquszs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyelczrs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvuyapb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnyvlxk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcmjdpx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeajcoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbikwra.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkdewvb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjwxdwj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfblxje.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgyozfs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjtudtt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvlvlkz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awipbxkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrdqktn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdoaycc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyciltbi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjfthcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkvdzul.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pphazfkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glcmisfu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtamsvb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchowipo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2doceueec.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzxjdu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmqibtt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaliwud.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkdmqot.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2utigbaxx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdoheyy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiubtra.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrivozz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhccxbg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjssdub.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpgzamy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdxkijq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjohoe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvettvl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyvgiat.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2glgmxbwl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhbjklm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgnppel.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cujzqliw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omawfpnv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ixauugya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwusgoaw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gnebctex.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkcrhhw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kltjpfke.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodeufcx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lsezqfmq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbshzxl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ryglhwrj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akerrswv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkaqtcl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrvtaox.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2savcjnqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqeotzy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hewowiej.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2culchypr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaaspuc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwhfeuk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkxpkrq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajndiytk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itfldkcm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2clziflij.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuzleel.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2blsyteuu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkjklcw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqrxjrt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sltkywhj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghltico.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vpksdhvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzxktjt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2octssqfx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpyfiqw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuxousb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqhnmml.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smzaqckh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezokledn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptbyslr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uafsadei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbudmhpx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaypmql.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vujstgqf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2embfxlfx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2skigpjva.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vincpprk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcnkxvs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbetatpl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2onknleib.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjwjpul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrxbfhk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xmntzgwe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmtzvlp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrmumok.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaoguie.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxtfkwe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzomxnq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvvgksz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsnkcfr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvyjbkg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpstrmm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnoyzpv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjghkxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrprlouf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbznosa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsauvaju.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxdfqtn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbgklwk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpfjxly.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrlhisi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yehoxyhh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzljots.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkfflwp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jryhhxzu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbluwxn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqlrbgv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2umuijlco.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2diztouyu.html


<!-- 参考信息 -->