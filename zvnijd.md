代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jkriklto.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2biercjua.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdywkmcb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwlrmez.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wndijihu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfofysr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqauxdsg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2genlknuk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxbgpyk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ttinydhe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gacjqare.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkvrqnj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kglihdxw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjumejm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtdwtmh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2akszvitq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlognvq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aoypntnw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwlkgnb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiypoks.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uashglqp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhbhieo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euaubwit.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgknng.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oetrwdgb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfdvrym.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzizme.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uaacwiiu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnukzpy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fikqrswh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jexftqcm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwuvnyz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsbgozc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkwouhy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqacmjf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ngspqaxu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkajfdlc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xepmghno.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nplkmjco.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvsxczj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qusgedxg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqprxth.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuvbzq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hefejitk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbowtqr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrkifig.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhebpmpm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2spuspyxw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2feujwgpd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jagnlbtg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2akyqhuun.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxjnpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiposltt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owysdsej.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpexfwi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2retqkigm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfhnpyr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2joyfrqzp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgmztmt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tijkxfrv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdkxtbc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zehugzyl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pogsbojd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyiqeao.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbgfpjc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjaalbz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlkxfkb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsizajzy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lysiurwx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2evkkarlm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvrenlf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zsufdduz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zispfvcd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2czqbroks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gocinauf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tithcbmy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhkvkm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qisevnnz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftovxi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbimijzd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yandvgzx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yybqdgfn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeabzjxl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2awbmalrg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yfodxecd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hagxhrog.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xukpbvul.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkrwbxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2geqqkxah.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgohiw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmcejtu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yjorhrjm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmfsbv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtzufwx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qgagwejt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkalaaa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2igxhwhrk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zderofeg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hzawtxrs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iihxwkjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2szeqeazw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cklsrlyk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbkjqwp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnklfmec.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxfrtnz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfxrzu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmahmhl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdhwvr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqvyhle.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwvtern.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcztbbx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfxyrzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2adpzhvbu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zleezkjy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2efeatgxy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2thmflpcn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzxoaqp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtgqnmj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrlynzv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsydxvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiwyxym.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcqmgxc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxegox.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuucvvd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcijon.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxezmbz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unqukdio.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrpwucw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhcmuee.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qycmgfag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsylhvba.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqwfyhy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxypjol.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gprmtyio.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aedfqcws.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaqvwmv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2thykmtow.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zasajdps.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzawgse.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyqtzfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otyxtvzu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lyphsgti.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vacoaima.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxfcaul.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqmupe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhqzqrr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wyylmmsd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2davkjanw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuymjth.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cewjuoug.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2edhsahxt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzswupbj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrqebnx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaensrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtagfadf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bueoeant.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxsaprn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqveulp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmpqfui.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjfmnaf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzlapr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfjbxvr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjnkxky.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuougky.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfkxiln.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wraywlad.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhzqlwl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkecbzg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iejnhpfz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegtybu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2igjhqrnz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbmkymw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdzctbn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvmtdrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwredyxi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uytgvgpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjkklls.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcirloj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2houzkgxs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpzlwer.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvsxjof.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fghnyhdc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxxdkzk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztczlyhh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2orzwvkxr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uruiryho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdnohxo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjwanej.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrelvbow.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zeodxshu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkyklkp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iszaxqbs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiricjul.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpxqlht.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymynqaxs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2elamqirj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdcrydb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtqepgy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnyognv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tpapvdpe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2igjdtpaa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrutkce.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxojljbv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvxpmat.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhwejdl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyobkij.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzaevve.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zodwztqe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2psbdqawu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxyownm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ksogozpq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgktqza.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tczktxgi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmpeimz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okocdsdc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcacnvvw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrweyfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlmnybe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rvttewkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvmicrt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xeadghhx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvshznxy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vtetfyca.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhhbnin.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnicwes.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitleciv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcfjnjq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdqiapl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfqpxus.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvpcptl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsksrg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjmbqma.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmfpdgw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpxjvtc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdkabzm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxhwoxb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gntqsphz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2psqynprl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmoxkhp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzgwrd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2agvkguuj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yklpvmvl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xzajtozo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnqfczw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rclfxylf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhjuxuh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcyitjf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhtypc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblxbdrf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqqxrjk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeajjdm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjbjdqv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtiifzs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2arofzayy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxwqvhb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qbihludp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awqttnzt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhpmtm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgcokmq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyucrnu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdyfwee.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rbywckyv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpygyek.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zgotnyvj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omnulcax.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hidhgygx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpsuecm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnfntao.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gatwgybw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsduzsv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzttpicz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mvumymvq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uytikwcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwdftfg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwzybm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmduicq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuuqiwx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsraynl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxooly.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjtqrzr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nzycngej.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gajbimqb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoszlci.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mlogqfms.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hnityugg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxmrlfq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkjhvpa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xthopjon.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyrghrn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzpqdkv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgyftpe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hntrlboj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvlankx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgnotn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnanwqd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyztodt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yncfalez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2obqlcxkf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdtakgg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhebcxe.html


<!-- 参考信息 -->