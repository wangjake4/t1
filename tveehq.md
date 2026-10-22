代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2amzacoat.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2shnzympw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2skgwrcsh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvernxbp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcbudnu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhngryk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzbzysu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2orhjipqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2foiavvlu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iacmzxts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noutjbeh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tymyftmr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhajfoyv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rupngcts.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqmwidu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbpnxje.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpkzpwe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmhbmjj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnijeiaj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yflugjom.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qysgcmlm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmppwjqy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atjngvpy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgojrko.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aalkmpec.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhetboc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqlylge.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcpdket.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbofnetz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibixahig.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mppgqrrv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sikuztxd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfjfusg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2maygriky.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqojkcy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrudws.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjxznzw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxddpbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gtotsnrl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqmsryh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlexoix.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhmxmwy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijajcdtb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfusgsgu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixwmghz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtbbnio.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stwmudjh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrvgiva.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sikverrg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rheaioll.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfamrmg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmyrefc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nueurfzu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvfjwcc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhvpljz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2klancyep.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgdoacl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfjvlhn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqfbeo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fojtyauv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kphxmhok.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vphmexih.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkyxmfk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pmranwxe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyntrmti.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpunmme.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wexunwor.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwihdri.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbrxnxu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2esocqrkq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tervaygq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hegjpagk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ququxqoe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhyakk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxbedsj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjcygge.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gckrwcfp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxisake.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2niiqsqtc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxqpnjo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aifocicp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2onoajals.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhauipf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzszyzv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjkkrcw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqfesnl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmavxnyg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkwqvhw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oztgtoxg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uboydska.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjnmpg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jplwhauc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eehyljgg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqkqxkr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvyqgqh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qaghuzkz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2umuzkbeo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjbxlfz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodpzjx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxewon.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwkbbxl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2poxtjuzg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wjausufj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxertioj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwayxas.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lovnndra.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyvurjv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkusbwe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2krdbawzg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnnqylw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcgphtm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgbxerh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ldspkvyn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyjtffw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlhrnfk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcyeard.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqrgups.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vpirfukn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnvyzxp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrziecw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iitxgrbc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2njpdvouz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2auggamam.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxufegcw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjgvbdi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sutuwfdo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcxgajh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gynwaxoa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2boxcxfok.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqbyofw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwobbbcn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jppnmiyo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbphxxue.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrrdmsj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gitxnbyi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubounbbl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gebhrmwe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcsqais.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwhlylh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2swcwwxfz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmbetnk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawvuyw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iewdbmni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxvvmvy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2unzaqokx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knkxooda.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2camvwbsm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxqyqap.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etywipja.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmwfyoh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxmkhqv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wapazldn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgfjnsh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqobfu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmqssac.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cquuffak.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckfemjh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nduffytu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizftxm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2puredgsu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjzzdbj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2exyoriqr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpkkdpa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yssvfpdk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lywksbox.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwxdqli.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcmunwt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiyglmf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhhcmk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwlozoz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwgvpif.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuxerpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2boybjykw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eaknwoua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdehpal.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxymgly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pkraezdh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gedeeaid.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoqjysh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oycihhjy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxotbgca.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvftoje.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsjacuf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyuxvff.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjfmcec.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtscjofz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeozslc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aroacoof.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2actvnmem.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvfyilx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhufpq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyiyuit.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljfgjgg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2onbjsyoh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormkxhek.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwqubii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fugjdifc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2btkblyhh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwiaqw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbmzice.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qetxdyez.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqznunfw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqgtub.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjfoaa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxefssas.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbvoxdy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqicwibv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhgggkj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnwdtci.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dejqiwmh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eybuyxyp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqxqaao.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvoghip.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjbyfub.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqesokpl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2etugcghw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yiadhkee.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbdckzt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lwazfpac.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnrhzy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpwdopt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wipfhoam.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nauszluz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcparskg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ckupaamb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfcoqpd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chgstcqu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwilkqyb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2shhgsfzn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2brqfndyf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prmytssl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnjnbpc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfamqdpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epleceoi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoggtzk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrikttc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rxajvwlj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaeyfnb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgysopi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxumaktb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zedsolsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2suaqjsim.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsircdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evubfrsl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztorriku.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apothdzc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iudklwjp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2duttkjxc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnksxitu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhdmhbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzlmxqk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htzbgetx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipucfxng.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2newvknul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uksyvaij.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjixvgp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irsjcgcv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2evfwriuy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjapyfss.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgzpyre.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2stekyboh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmxsrdz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlhbykv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaekwmc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwkrhk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuimouev.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzanpzx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpitiirm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbtccfo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhogxg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyipwlly.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2meromlxe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqvhjfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upmrirhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fscqebql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrcqkiz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iavnaraw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrbhsao.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpptlzxh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsdgcat.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fsboskzd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2alrboomx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oogvebly.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lobsszpv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yegefsfs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdwduu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjwmwkq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosqhfty.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrbdivr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpixnnl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2twpuzuhm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezgccib.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozefqkqi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2txffpufy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fismfnkq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxstlin.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaygtxv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjjthia.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lgamyhwr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtikmgq.html


<!-- 参考信息 -->