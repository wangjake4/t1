代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qujmkilf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuwviqx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtddrmn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoecozy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhqjgkm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fofuhoql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtiyame.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrfbnrw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axzihrge.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vielkvqx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbspdez.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2roxqtnph.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oajkoxbn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqbecju.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czhdjqwh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgsbaub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fskoolbs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzyemrl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kreybkni.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2klzissaf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqlsfri.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwiqnvp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcmwuwj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeekxis.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoupdmk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqktgjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2segresau.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utyhtrkm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnsvrke.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbydufod.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jktswckc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omshdebl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cabmpvym.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnxilvq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcaxmyo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnzvxtn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2njbbigsn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoxrzlg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhlbbyn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnlttck.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2baflfkwt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzognlt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bzurxdok.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiyxmkn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exifbysv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlgblep.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oocbfvpg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uhenykwz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlvrqfd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdioiwjz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnsuiwo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwshyzcx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmsstf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rznlpgmz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2woqhnzll.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmppxsdu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bccqsxnn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ainaogrm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwvglnl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqaairg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ztftrfoe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nkasjmqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2neybkjsb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2euulgrjt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vclayqqe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoouxds.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oylrdgfb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efbyjyvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyxrbth.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uogncded.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klinbkcu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhnifc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmsffze.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfivlyzk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eauvgjsu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ooglemrx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhspmap.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqivbot.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wiplfmni.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2semcdsgo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2togrpkat.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sahdadxy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pftlmwqe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgbnib.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rbklarlb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkqzdxg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2andtqlis.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pvebstrb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqgqvbq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mebruxvw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tsahfnvt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjremcs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nekdskjq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qczqhzqr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yqawfsmh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsimkcg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gptnkjoq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbufdzjp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrfyyen.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozugbmog.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoyeijg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfltsegs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkbwqtw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuplweb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvexuxu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrojupf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2homvtidg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2guhvhddb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yuudfwtt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wlisiktk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kuefdyyt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoszxnn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdivlfee.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2khrqjlha.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2felnhstn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rublmnbl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgukzbo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2avqkgxzq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjncers.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swrxdulc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtfdxfp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoeryfo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tprfluwf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyarhos.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjgsexh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2krsmzgds.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erystpts.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2deyqmjrs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dncaopba.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpmxrcs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2phssuqig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zquxqrxo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjtejjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxjkccw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhckoltj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhuzesf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldgihg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdmytp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyozxl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mglngoss.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnawgzqy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbibsog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrwolf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabdyxb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uurnlxto.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaadrgn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvtjudu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkbzjjt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvngtxs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bashqsfv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2robhmknp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyqkbfs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlulvta.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpceklz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmeexop.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gayxiocn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlroslh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpcjvsg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnlrpfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixplersf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgvngoa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmkvudp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnlughm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xolnbvfb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvmuzof.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sflvqjiw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbkhyol.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuybivc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkddeban.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmienn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyipiou.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoamajh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmltkqm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ympsdgqn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqferhea.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvmdau.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxquoyrd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ybglzwhi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2naniubos.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2auwzmett.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfqlqcm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2areuzdyj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuxiyeq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkcirow.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxghfho.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvqrmq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qttbtzzl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmddizs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rafernqp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zujmpafy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tipcbpgh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpevnpe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjcihyu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxovay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqzffkt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oawbzvfb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjbxeg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhiiihl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabikxi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zepvzzxo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkdvbng.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpedevj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbfzqsx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxlctof.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvfgyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoysxmr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2epfpdhwc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuikuloh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtisdrcj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlsfsqi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mrenxwod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmajeuau.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sohxmxou.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2veciruvw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrogkirw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2niecbzif.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kaodwdkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnmzhdk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtpxtyi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnldayii.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfooccw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhigjasg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnxerhy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwrpdin.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwsnegu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2adzlptkd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cysojspl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvzdlw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hdduwwkz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhuzjuw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oimvsyge.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiplwgl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxjllnj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uswjmdci.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzumdiaa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsxmzap.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aatuxbtz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcqrmxn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfbkec.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzxuzc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxhheu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfwzcod.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqzouus.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kmahnoac.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzscgil.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjmoami.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjjyvsr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2atwsppzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zabxtlsd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2trekiuok.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjtocun.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbpivhd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmanlkf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvrtgfx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndavynsx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2abixlvuy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pikbhyka.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2edvpdmuh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdxgidd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yuffywml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hahdewqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tewtdzjv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2egryfcdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiwhafm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rghzjwsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2frttebki.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baibruqc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2flgoopft.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgrkoa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyanixw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2csjutnjy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dotikpwm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2odwncxdk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lphxrnzz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoogxjq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jemnekps.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxqnbko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbnebjg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmxccte.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwenemiz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpofppgs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yszovcqh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nniwurcc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgxuvtl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxyvsqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpabujba.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnhlyvq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcpqqjz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifknqgii.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcaimeq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elzhrqlv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhnbdlb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rfduvxgh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkgysml.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxapecil.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvffpgmh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnctqfy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpuavwj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjjchie.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkbkafb.html


<!-- 参考信息 -->