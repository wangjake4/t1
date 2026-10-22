代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxbnakg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtsjtl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvljxnu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aynimgse.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxwnpwr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2svbduumy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcigkfod.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvzzjbp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwqvlrc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zppjdzje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnbfvnj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okjthfgj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkdbve.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxnmrq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omfpoqlu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzjodzj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoiprzi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuausec.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvqhlee.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjmrpxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cblqaiuy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqnzibz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2faruqhep.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlfoxvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qikeyvgd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodzmewm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsbjrtv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2caolzpex.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2irxdolla.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oyewxjbc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pamvnqst.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwuqllb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrdnure.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahbtpx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2abxbqcii.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjzporm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxtzdzh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2atrbyfhm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmvowcf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnpmvvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gxedhmfq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2upffdtyi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoxqahb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlljyyk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2skgbthom.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwebwsi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyrpwqe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkneaec.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2faeciyvy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2clqfvoeg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ykolnrol.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbiitct.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvhzolt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqkvwbv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoczzlk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qstxooqt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpgroud.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hailxnaj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeuffvf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sptolkwe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2obcrmydf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpudpxo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsbkxqf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pszdtswd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfbktwz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhnirdy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdsrfwd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsylbfq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhngsjvj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpszexpi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pghtavsf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqdyfoq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hmntzjsy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcdnxmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfobkfk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2syyctfrn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2exzaxxzt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pderixul.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwansgfo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgmdsga.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gphtzhty.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwuvfzn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxwrcks.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mkolvlan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhtpgrf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvufnap.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyyjlag.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwvvytu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hystnupq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sutinevx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2agdwpfaw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwhzzb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2biphzqzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnlnoef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgnzsh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xebbsnkn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqykacp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2babyfotp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkvwvxh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tafzsinn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsnphtb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqqvzdq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwmcip.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfonviv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjivdku.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsyqqv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnzcihx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiygyev.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2metjenxj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aizpelzd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjltdbh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkazjrnw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lzskuyrr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zonsprrv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2noamzjyp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxyxjhf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkpikeb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2arwvwpdn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbpdldy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmukbums.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmdsti.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcpobmw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrffbstg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svjrfkvg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnehnfr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psrzlhim.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2civqmkeh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cugqunpw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zooultyn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eltzrbpl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hseawnqp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rixdqojj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyijoqpj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnijise.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2llmtsvil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwopiph.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gthzkehl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgpgszc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpcmeuz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2stjmbvnh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfczmqj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzviwapx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzagips.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxwsqzo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpqjtvh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qqabssvk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2idtouesz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bddwbbrz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxkgwvb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkodkcjd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tezugdcm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kfclyfkc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjgjgfo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkhskjs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcssgpot.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zehuslyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrmhopu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqenmvc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkktxegm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jctezvbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgmiyv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeobmuh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uubxwrhl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkljos.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzogmtz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afdpxvyw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oabmayif.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoeqlxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzsbbc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cufzywjc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxghgzp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbfipha.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnooiwmp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2linhlpbu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcsqzqe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzdbvdm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgcjtpu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2liilzfdq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmkoynb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eyixuzme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtudnhf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ljthewck.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvcbppz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhohqod.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgnfdbn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjzakn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqazfqvl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnhvfsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnauiwab.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjoxydd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqibfdn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mozhjvgd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkntxj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbsbtvh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2stokpqhw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvjrurz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uywilcxc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crgiwhsx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdawopt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlognbl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2evcpvscm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkcxmel.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkqnmpj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gneaarjn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjyybdc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcueysqo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzkitkc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzomelwm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2doeafpan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzbotlz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zcohhoxt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owuvmxyr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ukypkere.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2seskmect.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivejavfj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegzvium.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pxacozbc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhydtmsj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgodefx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnmdop.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fntawknq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcqruuy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaieesy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2npgngrlc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkatgyio.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtfhhed.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqktdipy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbysenuk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoklgdk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhdkhl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrrihpp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcfjnqs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2chyzadhe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhthdq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxfhrax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reiddaec.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvviibwc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bomvuyze.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqopwhh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkigvbzv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkycdfvu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqltxfa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2izsbtjci.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbylfgv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqdlqwv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhffyrya.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzfvzgp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2phxkeiby.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgyntsl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ceixpeex.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsddmbh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrdycux.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kskyuiuh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfoymet.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgqcrnl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcqeirf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqzubih.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwixnros.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiuizej.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tluovgqt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnktgrsf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lugvpwzf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrzxyy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxhqpeu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxyktqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwpismi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2poojukof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjnvgus.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spqckatx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnhtcss.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuugggq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mfndxpqz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gktgywqm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijscftur.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgcvysl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqgdzi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmupwdek.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfawybx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjlkjls.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkhjfkm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuninha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxcdufy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlyywy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkitrno.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uoughpst.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pisgqzcq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsikifm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdtlboq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2whbhzpsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qenqlkgt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpwlmci.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpclihg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwtfgby.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzabevb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fumioise.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbykebwf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lfninyyi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2edbermnx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtdxsvc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnydtjf.html


<!-- 参考信息 -->