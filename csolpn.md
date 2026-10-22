代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2twxkfvvw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avmhvahe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2reniiwet.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rskmrhbl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxywsxj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htjdqoty.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kojuadtv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbzweni.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzfyjdz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxatftm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eddhpzmy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbopscfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlimhrnf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgtsrjt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfyonpm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2afabhyef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nypnvmag.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uieqctwd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iiszfzrk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtnoeoo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvvxlqf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkpiukv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xulaynuw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2presphvg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjzopme.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgcilkq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rabsywaw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2blsqogoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuykylch.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwpulbz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lklixmeb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlihivi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeltamx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edkxrorn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqzklzw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2musxilnv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjtxyxy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtfykw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxtjyvc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrjhrxz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eytrjlbm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuttesh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsiktvj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfnsumm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pczawccc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsztqhd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mywaqedx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnzsyqx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jewwxrva.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsnzmlu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qppkvzvw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbvsbdg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvdnqk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsugwkno.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ybddozvs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqwirlk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oozoyyag.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaqwdsb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zakasmgb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sagdnpql.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdiqrca.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ddybvhlx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nqntbern.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tdolotyx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqtbxxn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qivkzjar.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpmzfuo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usavksnx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jqenzsgd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbwzau.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bdibmwqq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dmszrzmd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uexwsufe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gmehuqaz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2edsdgshk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojioanfq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzgjeki.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhwopbk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crnzhipj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmoxoo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfzryrx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpcuvcs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjlxynu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lkckepup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjvqmuj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqgsclf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvllsxdz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2isrurxpx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kfohvavy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pexzvago.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2divljchd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkjvzed.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2atqookjz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2owxqsxva.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vohtgdjb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuxnhbi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pollkcqc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsnmino.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2feyvlafb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yczwwowt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lopwbltp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2drmctwzy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qokcbhyz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2swzvkadp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kkixmttn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhtlisv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpyjiua.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhubnzxj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlbguw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvabcl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2clprnksp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdpqahl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbuexfq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2burrqwei.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2odxjrzls.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbyjgfd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2towsrcfu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbiuekg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fawaduhv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2abmxrikl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjjitzs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tbekbyjd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwiutil.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwdoiez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2elpkgsju.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwzrsyp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqprpqti.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zclmhkww.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aereezuw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yruinngo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiahynq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tskdyrtm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2umvqckqn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxovydu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjuwwpr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzklckv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdesluz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhjjssw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcwquxe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2icqelvox.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdepgxc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jecufwuw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2chfjdvtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssupudrn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wypdpjxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmxtuem.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakrjld.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxqtmfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snnokhto.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xntczsyq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhldsmw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhfscmb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2giolgair.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoelbgh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkzvvc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fztsfzyx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwrhtse.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emmzbwbt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqcsbiv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgqvnhb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwgmfzr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrhegve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsncfww.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uapzzguc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2brxsyzkz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkfeaig.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmgpgig.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgwqpzh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmnghbg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnbogms.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtunbzjs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaexedyz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2htuvjcdv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbvfrvb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2alditugq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvxpmqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mozlmjny.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2opygxcjh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxrmgpw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2appkrcez.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krdrsagy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2strrptkc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkfkria.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmaifjx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzqovwf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2levstytv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtoffre.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2soxftnbq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygffjpr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kkukilby.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkaiqj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hoegmxhx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uudcobrh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowqyha.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrpriip.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvdtaoy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hogvphtu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2buakvrxu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzmykuw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphoqcp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlckret.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqjnacx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsotbnwx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjitmtnc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2geerhrtf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfvglyb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipsonj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxhzklz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2prevhgmt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2azrxzotp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2szsftnze.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vatkgfom.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bipsmgil.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sedgmjve.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjfgpra.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dughspdw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bijoffed.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpwtghg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgdmskt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgfrxlv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmbjyfu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twwxdsgb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaitrob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myffcjco.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsdvbw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdegyqd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tcphbbar.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2khkunbav.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmznhab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2owstivvk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yhveauzm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkmfpfn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlgbvxc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrkssjs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axfbkdnb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhtaldv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2penzuldv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwxbmef.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lipbrmcl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzsdekm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qayvnwbl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urzkhkhu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kdszgdjv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msdkieke.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrrcksj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwwiuj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tljzcpgi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrxocbr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlapmohl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alykwimf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhqhhkq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sgciqcpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuerxme.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2apunjhhn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaipzhc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lzljvzhc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oadlcrlb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2trokqmty.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2siwdsddj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaoanln.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdyfzxn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbyqzin.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsyperq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqohswd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obepiedj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uakospnc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxssztsv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fscahhbs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2roizarbm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qwutvtgi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjjikxn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbqusru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoejhbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yapyygyl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2abmgakwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgmzts.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqzzqhg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlieycpz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhecqgw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmlwhe.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhifzzr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgwfbju.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtrepog.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cosalswd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvsnmcx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsiuqmy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kugfybei.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2isvohdal.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrovldo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkynojfo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmfhrbi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2akneoxyn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtifru.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlrrcso.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcncvry.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mteakixd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwppsdq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjryjqrw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ylixbjti.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wguzegad.html


<!-- 参考信息 -->