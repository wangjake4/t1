代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwohxbs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yelpdhgl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqadxsvw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pptbxenb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gewqgqej.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vicsaxgg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oajuskpq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydkodu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtxzpmk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvgtndz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2reonjoyx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvfkqwi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvfbnwh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzzgrkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdebvzwt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqomxrc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjwxvah.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrhgnou.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stckushp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxryqhcb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhkjnhz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrudioq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oigotoql.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrgeiha.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfhwcuw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlgvczu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2soqumfgs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhxehdv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnjboyu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zarjhody.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgjghqp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scbibsuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fokmuvot.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lapcrrdk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cketmnhb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpumtgs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvalxyz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2afsipzxt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomplhnx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnkrmy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjgexak.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxfingd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pfalinqd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yzemnuyl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjctrhoy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmejplkx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmkcuor.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtcujdd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlcavme.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbdvlhb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2idhjlcyl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwovtlq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrqnoik.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bubhrdny.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ppersbay.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hktdhkcv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcmhimx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oowazkan.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqxagvy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcicgqd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgkfify.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2crgjlufo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fjphzuyi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvkjsiu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2osjesxzh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwaxsp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2girveoyn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeudhsg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvcafhz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchzkbl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdrdzuk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2riekxcns.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsghgjr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdpqzte.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpugiop.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bubzdceq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2okvvdotl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmnvtyd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxjwxts.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ihywgxfp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoozqag.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvasajzg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyvekpo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhkuodz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2svcigqnp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhbsymb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nabffcbr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xonjulvu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mnodawrn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnjxyfi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jonernvl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ydygaviq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2emkpkbci.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yieiobam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkmnlxb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwjqmxw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xesnuyta.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2judivihj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrczmqt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwfhhst.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2eekjlfsu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2chkpbscs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbxrdna.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfuqbto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzrvjkl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2javogzub.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxbwsee.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdjzvbb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uculfina.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbvbspm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nivfqora.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ercrrcnr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsrvlee.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgextil.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxlryaj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgmvbwj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2naohkujj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2btkahhaq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgbsas.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imhwrodx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2frdlxnsr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2clcubama.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlagjpx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evodmjgu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuguiqkr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgfiutr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emtthtcg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqieqsq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoeomxx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyxmohv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbyonyl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhdpzka.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xurnlusz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mansrhdo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2reafsvew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvdhcfa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaswqao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqhtewp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pliocaue.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyxdnam.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnaiydg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjunvhf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvdyyrs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fabqlrmg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxpynsp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvpcpta.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkoytis.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfblxkgh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxiirwe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2naevxinr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gignzrii.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qeflshci.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lncmoyin.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bivlgxou.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhagngy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gganrcqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyuybez.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpirghp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbqfejz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srcccbug.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2snvrgksv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxltmyp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmigajk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxtfmjf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jljhfxua.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsknmns.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svvbysrl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2akhnhwsg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgxeghs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zytfthxz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xophwpzl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaskqgu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzpcolw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ponsdhzt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzzfnfr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmsirix.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbwavey.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoxumkc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2prvvtlbg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bqomaede.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhupxxe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bglzhvuu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcxxiba.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzvzyfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiphjvdl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2upqsnrqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kunagkdo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvajspil.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2phuaxvxd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2efedxzsn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiodgov.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqrkmmr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbwjgla.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjuviop.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtkdcjj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqruxxn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqlvcec.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeaobnc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrkrbiy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxtspdo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zxccyjxa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrcnuul.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2chqagaxw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvjvcjq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzrfbjg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvepcvle.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwvkdik.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsokytg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2twuvltmb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkllpzva.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzanaox.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnubywx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jukcxxbv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyousr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaxibve.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnhbkcq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iupdakzo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgbmei.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtrrmjf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xmttjpmz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vhprzzmu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cuftxpcm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhwjsxo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnxphtm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnvynve.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiskoxr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txltntek.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wljcgdwc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzcvcky.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhehvfep.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcqfayf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhpclhu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobrsqk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmlgfae.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxzfvni.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcrgrop.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqbfqea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqtlnn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imnlnrrn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqujgpqi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zttogqcc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlywvws.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnqflua.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tngffvtt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yprgvyql.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjecfmdj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrrabvf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjsymuw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelefepk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qepwhthh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2llkaccfi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehypgmok.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnifngds.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2omibkciw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pszqmhht.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnlcczk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefmjecy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwwcka.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiwnlft.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohydxpun.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogekgc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdkwrab.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdxpger.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpqysuo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzoapro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhitlbiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wetqvidb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yltgkouq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kupwehuz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhcvnuu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uliotibc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2awpovkio.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dntcjtxo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwydlspk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcaoou.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrxpwaq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvvtfqj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhygiqp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pcylluhz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otqkipgw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmjqxzp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadvclqg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzvidse.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsreczd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umfdvdal.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2immlprog.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhorwyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkqezrh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdekrce.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiemrhai.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiwrzsu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedwbtcn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vatsbzkh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufhigco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbxwgxj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsjaelg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqkyawa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmtzfeq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcmcbzm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwlbjkh.html


<!-- 参考信息 -->