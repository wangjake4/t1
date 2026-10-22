代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2okyawlzu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfksqukp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slqlnvyd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2prbzvtln.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrfqioc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuvqrqz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2initkjjl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzgqaxv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsdotdr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anylxeyl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmknfeyq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tabpvtld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uojkvnag.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cqughfhf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlvlaaw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmirytdy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyemryf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myqkeqcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsglhiv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2byjtoerb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uanlaydy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2povhqbyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjrrjee.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybathohe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqqxind.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmraynhw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2barhneyp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcisbfvt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apyulopq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaajtfm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkpaee.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qekkpdsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2goxjofft.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cukmvftl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bivqtzck.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mrblqquk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtotvvv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwxjcuw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2imgynziw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsthfwn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhaaxwq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoxvpjp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2npktoioe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgipnuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnczbrml.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdypno.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqceubt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2venecirj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iourmokv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwzfvvv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbnpzmi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2epdaudlp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlhceps.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oljetpbp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuiahkk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rvygcbtr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bktfjoea.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2msssyysc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnllijk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcqazff.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxqlmsh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvpmqkc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlfwnni.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pzshbses.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hlauuaai.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wingkjez.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunwpbd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2amxwpddj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykihtqjj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2txqsoxub.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2caepfndg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2diolygco.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeeruez.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrgehkn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2udxmxsnt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zzucujoi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwbiqiz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2icdiskag.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpgqeyi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyxzcmz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstybbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyxdtbn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvnsven.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuhvdzf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiebnqi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsdhtiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btpyivqc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhdaza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eafgypgo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfldhhva.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxicocpa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uvacoigp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sorjodjb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skuvdanu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rabghzss.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtarscb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapupnm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdlfafg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgjwhua.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wsecoznz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2abshsxpo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drjhkkmf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlrcuvp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2twtvttoz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhnvsku.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2glnwxhfs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaekgwi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hhevpsmd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaxklze.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdzjbyj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2huxjooqw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwcuylo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpwcgsx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eqokchgu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqesfah.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfhcxsl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zgynutff.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2diiczhhk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tkilwrjd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2milolkzg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtfcgaq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybksqoff.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vveitvmi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhqhifm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqvabof.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiyflnq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfyzprf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfbpxac.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkduoukl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jayitdbo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgtkgcd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2awklcape.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzjxbgm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqwltki.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xehkdbui.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olocqnsp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbszavk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwruhssc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dixslyhy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhmvome.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iojodjjx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pwutfpmm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbpzyyq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxhfwrl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hstwpscq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcjzibc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjmkvzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjufyxvn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ggicjted.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srxchhsf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2empepyxx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rrivjxzp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pixruvmn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kttfexwn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkwkwat.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2onagqcyu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2osfkexag.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ntftqpcp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhynilpz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irfuhpzv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsisifag.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwqclbo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pxznocdr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yljdirap.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuqulej.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tizqppsa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2miyciery.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxctkuip.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tahlxeqq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzmotxs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrrtdgj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzemfvl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpidqwy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqzdhzs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxxypbo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmncxczy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhabpbgj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2modtygou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuvihtv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qceweoph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhnizf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efegxxsj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejohfzfk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnqgira.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjkkjno.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvgjemg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfwdrxa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evokfqvs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vucduhqt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaxdxan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppztcrtq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2criysodl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjjioql.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhtamda.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfuaotk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmqzziq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzkddzy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyejepl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kryclfjs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxomsms.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2scwawiec.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvgxcec.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfojqwla.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ysotjppj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sabvikhp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltdzvj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjloame.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiduijtu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvnbluq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhesnev.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjanjaw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhqunpa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qbakvxua.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyljgpw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wjelhylc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzjvyzy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhurcyu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktaxavx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyaqnun.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnafaws.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmrccoj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guitakhq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2engswyqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjdmzho.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtdutpk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkwubfj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nglolivh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qccqswkx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vauchhdt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfivhdk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kojehmpx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhtewth.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zurefsnx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhxlzjl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjmacir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkquwff.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eowcxbne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rapknbng.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fujvmrfv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kracrpnl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsshixw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fccqwhyz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjypiwf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmwxwem.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ipukkmit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqyjcfy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfvyswj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwwfmec.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaicwfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiyngyu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgblawg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbixmoi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqijrzif.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfugyhm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwndjky.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrgtpox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieorkbiw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbtubiu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vcocglsg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpbdmwy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzekwdi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqurpbk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqobdxk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2meswygnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2capeywbu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsefegz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjbwnq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsypqzh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbohtnnl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocofcoxe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvjfhhz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrqphqc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrqazuc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqjajr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkpnarc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwqtjgh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnhicig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baerumtq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2quchqixo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjdgtrk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2parnuxqv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2txvelzdf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eltvqaqr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2htljipaw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgabous.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2repehwxm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hotyhlxn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjdtlfs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmnwlvl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qywuodtl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fplsjnpv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpqtdtz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeckjqi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcsiotq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbidoev.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmurfolq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdufqszs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdwswlf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkauqbuw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eznqpfnn.html


<!-- 参考信息 -->