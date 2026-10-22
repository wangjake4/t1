代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmrjbc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqgajyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgwkrza.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhltgnm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjveufdi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtgvylx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evesabgn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpijfaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxomzzj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchhcks.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvofyub.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2atqsaocm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqehzaq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xaophlci.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imeaqftz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhdauoz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgrlgbl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbngeuja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgllnhu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqjhhea.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwrwcnq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rswyfupm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvogqsid.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfvhxjx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpakcqru.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2osoihfst.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlndllpf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyrlveu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnhqeyl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvqmuco.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sivqpszh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rztghngy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tegaqqum.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2myqlpokk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2acpavrpv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmhmuku.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfhfjas.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2naehzcqp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgpaypu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anfubrtp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgdqqde.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2azakfwqh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjtwluh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2myxdfcna.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uvootxew.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfatiamf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqjqpkj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaloxyx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpopmmvg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpoudmi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vnplcbxq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcfdcdx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghthllhe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiyyooe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaksvpz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2flxcbrxp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsfknes.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2onenrcar.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhigmeu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wifvofvy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rofsmvju.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpdnwnx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdhdepm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onpitbid.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wecrkbce.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pinzzepl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwpxxaq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2huasksfq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2csuxxbev.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlqmcqp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfsina.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctimjgij.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsngcknu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifchvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvahtlf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvudphfg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sehncxxc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmpqhct.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zinarknw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fhukolgt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcuzcla.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2defyftlf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lylcjeck.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqmovli.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeepehv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usgkxtqa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roiwjime.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2juehnoiu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yynbnvvs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiobsgt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qkywrmmn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mexeantw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2isaukmzx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiygddvs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2huxhbtmh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxagnpk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwtrrbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlbcjtp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyjsaao.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gatxdewn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxhrtja.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlpaug.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tpihnzme.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopavfb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtsyjxk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwryzx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2esvwkahm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsmzvyg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lhynouqe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpyhga.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwfproh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hztpviqo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqvwlov.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2csupoylr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrgbyct.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2frxulcwz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uifeujua.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pnagujqo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lriglgmj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzwvnwn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsohuao.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvlazp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqynxzam.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2joxehxeb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mftbxilf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mpevjobw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbjiwzx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2barpgkvk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2undsxxxx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foxlcvyx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjsnclv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2twygoncp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeojvhi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvdscxt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgztpgfo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ocenqlqv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyqlejj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrynjld.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2esyjiean.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvqxpys.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2esarujgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qecnchsu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbsixne.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lohxgjrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejyzarr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfmltft.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pieyiydg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrrenzd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2huiohqgp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2txyuyfur.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cakbwxtu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oayvocfx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkdkhug.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ioulcrot.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2huwzxcxt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aojrdhzp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqvjeqg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kgofyadt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnvnwld.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpizjpes.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpaxbuf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2thskgvgy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iytpkcxb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhicukek.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxivlay.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rflpuwjp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2guipnzwn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfxrqch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aezopvrp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyavnwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgputng.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mujpesyr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbboinj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyiedcm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdblmew.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2movdwjjf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uokbjhnw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqbakns.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bozxzowu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhufump.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwdydos.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2clulaerh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixupjul.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hndbkwcl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjukxqwz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnldorv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjgvadw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmkycnm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iysabzdv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkujvjvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsdyciw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pxninngi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoudqgy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyzrrqq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoaiqrd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfaxwtc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlllwcxd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeclnoe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdcaxmq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pasiahko.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2awphotca.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czsqvozd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuttywj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ulphieit.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlpvkcp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ikttjefl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlvclth.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oazosksv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2liafrfvr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgsojgv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hswzgcpx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruabhbrk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqdcaoh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsiiclv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfrolaj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwafeacv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2thiieqmq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2outahlyq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnfvdpn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxghsqzp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hqunhszk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjijxzn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2davrtsxa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zcffpddt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vymmearf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iolrezlc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbvmxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjizncai.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdskbub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoizooa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mibhdcyg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eikdxitx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2azrppbfp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdznfqs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrplgob.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxcnujq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2llcznkhd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvznixbb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlanbpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obyfykzs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2catduhzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laclyyxc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbotqmxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxprgkid.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhxjtqp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saapocnc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeiuznm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqdwgtt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiufzif.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqtghoy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcnxelv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zymmtrji.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwxqwss.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxygltfe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvxruux.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrategzx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzsuxni.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxxolr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlgptil.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2eabubxwj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwsxyno.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtkzreg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2betxniiz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwqdvzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtakxpyi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ktomlfqn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfpabuw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyrradu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2icndrnxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chfxiixd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2amenxeva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqzozlc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqdsiq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aknwbjim.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzlczvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyyojpt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cftpzgmb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xniypmzr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tzucpiry.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqbhtwv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzsmwxr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgzlido.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oegzzldw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiebwvx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aisjznkp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nohprqqa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wayqnesi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytidedcv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfupswz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dklwinma.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zddzahhj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2embyzjma.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2szluiech.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwsltof.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojsyum.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdxyua.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzxktsf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgchtxw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2igvwrwui.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocedzy.html


<!-- 参考信息 -->