代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hputeqid.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2figsticu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkbrkbc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skgxcpbj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqmuxd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiizsnmh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxwndyy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2txrsgkhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngncwvdu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aswsaaus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nucwtpln.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhxzwxy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acwyzlne.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpwnetl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdsqbg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vysilbgg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stfxuxky.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaosawx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqntdqe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mybqhszf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzzdixh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqjobxv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlvocj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdzscbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvhkjwy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaqyzgq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgdfyen.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqwlrwx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iricqmqu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjjnmfg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcvyahl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gulznzik.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okdsyxvi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbhoega.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyjvyxh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epjyoror.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxrqiaa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2whrdrbrz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedcriyv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mnozwctd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2teauczos.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxpjfnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dflbxzhj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ltudfuzi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxpwgli.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iahmupft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2usfobuew.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xishnoeu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbpenvd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvvgmgw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaegzrg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmwquaw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqljxwss.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkorqsnl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yhraekwj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2advurdzs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wnveyjpz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzmwnqf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqoujcg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjvdurh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pizedtud.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ychtrtkb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dittmdri.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiqcggb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgeunse.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2epmeyhti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhrqsgp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eknydctj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efbwlecm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpepdvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jutgunbc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzribbbn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2baddcocp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2istadogg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaxmoif.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyylcnm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmzsbnt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fueasgxy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgkrfak.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvnxdux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqybws.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pstebgxt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxrqlff.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2slvaejxh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xpksbsmw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmnmuqy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mloevbvg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fydndtwb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tecxditq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shycmiod.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdnixmg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuxzkmp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2onaxvije.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvprvedy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdbxbil.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxsgtm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbcnne.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wilgjrvu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2apclypoe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoackul.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhkdeff.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwcuwxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmmiwpe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2huhclxer.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2auxjkulo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuccqke.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzfdzvx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugejkriw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lndnkwwh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrelssmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmuehmp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wakjymkb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaobjdq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgxsing.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vpucvglg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2verqyexg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yihrtcri.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ydakftrt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqckgdjg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgzsbnl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2udmuvitp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2makecsjg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjnowcq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qicwzuxa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnrwayb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsamrzt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qkygbbyx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcavazgp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vthbjxoq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kyestxcr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nezaulsj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtejgpj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqfxfjh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdbsipi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnvbaph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iurdkvol.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnikflk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lksgskch.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaytaac.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiukjwg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2johfaskg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jdafyoxx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiptmkz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gapawhof.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiduxuq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrcordf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2msbiheop.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rebzqsxj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhpksc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnwvyws.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vocpydny.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2imuqaplq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkkdjlb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbzijw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoyjfrc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ceogjtje.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2djscsuco.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtenfrtb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhqpszz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpdxsxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kglmnbgx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gifhvoap.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uturqgfk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gefprlyd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkinwwwp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswyexc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dycidcag.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiylywn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkslvuw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dedrqcyb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdgbmce.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmlter.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grwhewzc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdfcpqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vneattvk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcqajsn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxfblsb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scyvikex.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbvdbxy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhvoodc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqbmxea.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eavbnjfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbfzkgg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pavypcia.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgszldy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptspkqlg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cknveckg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmllvmu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2haibvvgr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fusoayov.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2slpejpyw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbxykgp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyapjdxp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2htwboncs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdxtvez.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfobdmb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubilpgdv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpftprye.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlsmyxo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuhgpto.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2judlxwad.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjritm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnixcot.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxogzfaf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ohidfaup.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmscljdk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srmuzjaf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuzygdn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vkevwgcr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ookfuiaf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwhkzvz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cspvzqxv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfesegx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klclznyh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2graocpvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oecjczwa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eoskjvlo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qutgwfbt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjukwgoz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fiomfbrn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2guutrbpf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfmgrnd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbznkx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzthxrzl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhwezlv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlstotc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xecvdfck.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uczboiiy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eiljpguz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbxkxdg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpnejiy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwxfsxa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nstaufub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomksxb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oxozxdwa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogucmecr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vetyfhsm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rprcndkg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycughcar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvxpole.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjantlc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsntqmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqenxtc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wketmzyf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrgmdvh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjompzxr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlugwql.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vssyekkx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaljqfvf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbxqfrj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxwmgmo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmzdkuu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fozvrokj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzufxbq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcevrlrv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fifsvpjd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxhhun.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoisetc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmlrgwt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvuzirb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgnzbep.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vktoplyn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmgupsb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqkovih.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hlphtrsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eexoxtzm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfyniyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jucwtzqh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2noojhxes.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjcdkfs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zflfzxcf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gybrphqv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjusjhv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshvlmn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ecznajac.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2reskjtbx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqydwsli.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjwlxsz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pejxstwl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odaimqwj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwyrwfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvbwgxw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyspxzg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyewdjww.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiywfihh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvgzcxa.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2keekgnsu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbkouss.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcmvyt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2asjbdtqg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaaiirj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcdkde.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2faxoepjm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozczyohd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cfizqzcw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgsydnb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lctdqedn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsefmbe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmwymzx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfngqxxq.html


<!-- 参考信息 -->