代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvxexdn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqjvbyk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prqnpekx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aycbeskj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adktvagt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazwnim.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfydzcb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skibyqyz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnprcju.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbxbobb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjtxsbr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmzxgss.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zghcyulv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vyznugul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnqabyl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkzcpjp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfyqveu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkwxkpq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iehohxjc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uoudolsj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qedeprhz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2esowpqrv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oppcrtxb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyylbfke.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhyekle.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2anhfjszb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akwwantl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uihztswv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omxvckio.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkyqvxy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuznhmz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oyllrddn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxmtpdl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ghakofqr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2anqprjoq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubisfknd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvwsgcu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dffuimrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpczkkd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyklooom.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcacsof.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiwwfby.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qodwfyfc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqdsuvx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2utsjvyey.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmoyvag.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqerwll.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjwqjrz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wohquhvs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaxvlem.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ruudmuwj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbtstzu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nigsoibr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrhgzbc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkjwtcm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tezspjhd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzdfdpy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyiqyxq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aepittzn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjsuxpc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2esxhufdx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvuwsbc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpqsels.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrdqlxn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qshywqjs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fyksvufm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cstssgml.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgvyzya.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitaqjq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolnuwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnpzwnf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhugulnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfffrefu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjkzisu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhzfjo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsinuth.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2luzvwsdp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vylmcerp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poitspaz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zwunbzde.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfjuekd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdriozo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsdqdrj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrbnmlw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoqmeeh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbozvz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyuutlt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuwmrtg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoicndl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpuiryn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oehnqzpg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnsyuga.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wilmbszp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yttuqjxn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwghkn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ulviwdub.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iaikvmto.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmbklqt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zhixxbjl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeugtrn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uqripeio.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpstgfa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvciyag.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iybkwobb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gtilinmn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zohvzkdd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tovtkcyj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlmwfm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcruhhy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzggdfnv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvnkubg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mefggwvj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcciezg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yofsopuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfkhksl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxqsrla.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yeydtwys.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wqckqcoe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tshltijp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2onvtbbfc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2binylyom.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeocrfs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqugqep.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxunfbld.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2whzsufvv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkpplsv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwutgnh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qopltnme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcszpltq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkrgvnk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zebpgwuk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2soyexcrn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzztmvg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvhoxat.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idcrikek.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbjpxef.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifrats.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgmmfvb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeqqksr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iofvfiqn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcgcasw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkekorv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vevuvmpy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eituwemy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsspfjv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tstdfobl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjunjcf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ailvmsrm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2teiaxbzx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mftgqcwv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmqwidw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnywmhu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpmrqv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zongejse.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gebopehr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfokjab.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2suagbers.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuprlry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfqkct.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bichtbvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2blnxfkeh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhjjydb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhtyxhc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udgfhmsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgyvsbw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhmppdr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqditobd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhwqxom.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtdhzhl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrlvese.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeisczg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uuinhwmv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2anhyuurs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwgwyn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iaanralk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bhepnkew.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlebvlg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2efohlrft.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dniflsnb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkkepc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2keocplkp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxtpcgn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxygwbm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zokngoig.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrdizcv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgqoems.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qidchqjx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgivahp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxwhgxc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xglujxtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbdjemp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwxaep.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzruosgm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkodwoes.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhcjvic.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zevxgeam.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqtrtr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfgasvw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfmkawc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahahqdmf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfzpddo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enmmowbd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbokyixo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhsjskr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bilyzlym.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aiipoljg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iycinhou.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njybxujn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2znnpfcal.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaangah.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjscssy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdqnndg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztxocd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjjvurm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2obpftgqt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjhxulr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgrwfiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgugauzf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvnevhb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjxzlcr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhgjhgw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdviocq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjlqvdk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fihthbox.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xiegloyg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcmpkyv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykarttgp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2expnyxap.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pclmuxnv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvrbff.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxkapff.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fayrxrik.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tikcnbmd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmmxvwk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlrorge.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbfpnqc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbzihds.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgrhltj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vizagwvn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrqydwv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2comppoor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xybstvjk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmgiqe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjsiodi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrsfhpv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urslwjpe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkvcuht.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxxwdqa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfynycc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nayryalc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtroirz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlcqkrh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrkvkqf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ghngdiex.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxbdkkn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmnabwv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qixjnkfv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgawzju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jadykhrx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dytpoovf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umpzkzqq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cejnqxwv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmrmglb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2duilpqfb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrspekme.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxiqdsx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqvdod.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asacffcz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrszobd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhhckof.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nixhmacc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwdaovq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywgiix.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnjejdv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuvkety.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkdgear.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kikydtjw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dduxvskz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuicoqa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wutkmaue.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lswyykgt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynqdrz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2owftzwlt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpxbmgx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ijusnrcc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obevubva.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcwwrfy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvrthlj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gajpdukr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsortbfb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvnuuna.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkssvoz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pedgzplc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnvybca.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrhhwvg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdejzmey.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmamdtja.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewewbyrm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awdszsqa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvzezya.html


<!-- 参考信息 -->