代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkfknme.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufanjear.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhqausm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoxnamp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmquqxu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umfpsfso.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ofejwgda.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jicpkqrr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvegbfih.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2glpyohqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfedyeri.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2otvfzdfb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiawohci.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoygnin.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyxzwig.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnjjzrp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqdfdkw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfeglpq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpfrgts.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yohdhrxc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omxstaam.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiwpuva.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwnhpov.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2waxkhsvu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzasokml.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2drslfhnu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iutyesaj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhsizci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsigpmw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2botbpzuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoiskqw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlslvda.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmksyfx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hjljkpad.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxypktw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfuuzrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xsilbvjy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2udssecxp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kxprxtmm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qskkodvz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvviaapr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcequbbb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2erkdgcyf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2reyezwcf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjelvvq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwboofu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaniegw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2knxkkgwh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqscgwqb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxralb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhrfucm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjnqbgx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gthqygrg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfnoqwy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuddudyl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtrloxl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dozivapt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhsvsgf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wwljgdsi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2chvwkgdf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wodhjfrf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dllmpvlg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aomnuylp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kibmzsdd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnazlu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aigwfwca.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yarxcvso.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmgymwi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jbulnphp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxaztyw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnghfag.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2appfnqhi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2odpfeksk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlodsndk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efrbigyv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fneupbpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pduzahtr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbpejgp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzftahyd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrflnnr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzdmrqy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrousyh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyrrnrf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaqpwuo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbotociy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txxedxrm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kuceuaql.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bngyqydo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqksysv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2clatgmhn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gnevxiac.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2irpvxwbb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2drvjfibw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxkcgsh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvmwsnw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjttwnd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhbshhx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzyncmf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxkkiqd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xansrkap.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjlehry.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2phpodcnd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxupljmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2auhqoulf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpyatao.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tktdcqai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hedtlfts.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkcpfif.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdshlvt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xidmsrpy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bhadpfjt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvceeyds.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2auztsadr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwklllv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxybklh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcvhksl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfrlygu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tjntivqg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wegzwfdx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymasvfyq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkeccsl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwxhcyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrcfmgv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hihvnkmb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ttinxmfs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvznkev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjlgzsc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiywcvt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btlfahjl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wukkmcia.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpyhxom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiusvjeg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvizhhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgcfudk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqnoehb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwxujfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxodqbsq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvnebld.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqkkmxi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdgrzks.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2btmoqvof.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhniko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wleyvnoq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxrywxm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xicgkarf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsbplgw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhctka.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wiykjuzv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gppauwlz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqykcot.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esoxknna.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhriubm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjbvllh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2egmvbrdx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzvdfjm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyucpbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnwjzlb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssebacvm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2buxbtfyb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkqbhwq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidkrst.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oamamcyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqxggtn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxkvryi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdbfbfl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2juabneti.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2esrcmdld.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmwubdo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxaysr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pseznehq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrbtchr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmdkzz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjauepq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joodjdjs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbawywz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gonqzuwc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqawxug.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kffssopg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtywjjxe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2deeekjjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2orcrfohn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmvfuas.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjlcgje.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2inykwvkw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcbxlst.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrijfwd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2guzsgeuu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlijjjg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwudvuo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmovcafi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekmogjw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlyqpma.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzxbsdm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rphfaaqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tispdpzr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhjroxj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2symnfbwi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nhptwuyo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpblubs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kearachl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvbecfd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buzozpns.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2masqxiin.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2efpncmxm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtuxnfn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpgewdq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtxycxk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnolvze.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqafypt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eseveggf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzgsowc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2julafsbg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvdnkcl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqwutxb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rysotuor.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btewdyec.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrjaqzq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxjrfzw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddotolkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrncbmu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkcfaop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqswkcb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inuasajh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzjtxg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eimsijku.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmjucbz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjooovq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfhtqxo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlnnrwr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yeojobyb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxmtngo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hchzjjmv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2baveiede.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgpokwg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2logxhxmj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vakhytrf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zltfqkml.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neskogwm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxkipfc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcffnyo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhjreaa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqerrcv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2omtukpmm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpfewas.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyujhifo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbzghzf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vddpyqej.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thynhgvl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpxhktg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcohhee.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttgauoj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zltmstre.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqbhap.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnknvzp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsqaflt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vnclepop.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2onziwnur.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zezmxuym.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspcamw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nylcjqiz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qdajzmhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leacakck.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yveuwatz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2degqvgot.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okrvagyc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxcxxiu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzlcnlf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmntftl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrelco.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yablduce.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yndryxdj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdppnrhy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpzkbml.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgzufz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hksdkcfx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgdhtny.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iadpzzrq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgmhcnb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2geexhfcr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfitxudx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxsgpj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbafktdd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lafzcgof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sefkhyxd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2silslfoi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnomwqgk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gaerebwl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfswxcce.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nctwduap.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rddoxfzp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pngdzbmp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rozyicbt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoyjyhz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqacydy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgbpsns.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbylmbx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pilqhxsd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amglvncj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rozlggqf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpjkuop.html


<!-- 参考信息 -->