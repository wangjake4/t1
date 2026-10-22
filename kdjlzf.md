代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hphlfqzw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbwptvs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbneojry.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzyupgw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhqkvbf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvozezl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoevxoq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgycpurv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvibwme.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lnibcptc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmonsfy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkdzhvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ityyihcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrybawg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywiwow.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pofqluua.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlxmnjl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2knhkymcr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtkwddt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoetlgl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqckljyb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpbbvua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djsynedm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scapyead.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnmvyoj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrwvlng.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqicjbec.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zredwcft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwinkzj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgytjqpw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnvcelr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2frqwavzj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfcwydk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hroeuvji.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrtfitm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2boellfvk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlcbadr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dirlemzo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdzmxjy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcwswvh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anakczla.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2casmetlj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeagqhpn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrbizxc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfkncnf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2erupyjpi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsglgzuu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iixpehhy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzpubgk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zavmsras.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfyatny.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtlvxqr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2njnluokg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfwgukt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wjszgysm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoskdzf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dysucnjt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrmdjpa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wltwpyyd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nbouyzmr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxgnqad.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuwcfdp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lahtntsg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmrffzf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlusjrb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cjebgnfy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2woslrhnu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyqqrls.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsmlydy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2isiufhgv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbfzdui.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2plocjfxi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vgihdqec.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfrvvks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxztdjs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwbgwpu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fouuzjle.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2asvefzeu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfuchyw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvofyouk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwullzb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2khbugalv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cprhgxos.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwqesks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfrwkru.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnhizsb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2driqxogd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvdcost.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yavunduq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnbxdeh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfcgepb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vjslbxbg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzsbddv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2arqegltl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2erjvftiv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2elndlype.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsrdjyd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqvnoyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsluwyf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbsqlvi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfqxeug.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfmnjk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2btaelkvh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuwnpus.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yveogwbc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzjoknp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nldjxbor.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxeaski.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jacrbrnp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnpcnua.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nijvdwcf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjprpup.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgffmxg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnggyqp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbbkonk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2abzdpapn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmvbpxl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cautxncg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqodazi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpktgbu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaodmgu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrbxxqo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dytljsar.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuepjjh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2amombvsq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2whjqiyxe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tylynsjq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgqwrap.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgdexjx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpucwlp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjxyhkl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2muhbysow.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqowitn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvagdij.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jabgydsf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bakydiyf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcnkget.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dkexbobo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjwtumf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pleqkmbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csondira.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xngeykvb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cncrtwzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbymkgc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nmovveae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqigkfz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lykjwzgk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsoafwz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjsajtg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzozzrvs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnzbpfl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uabwgxoy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkhytih.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsxavpk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2myqyukrs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vavkbxyp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsrblco.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2astlbjsc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvnocpb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2blxolisc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pknkpdey.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxsyaym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2seyxzrfi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2szwdzswb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aerczvbm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2efodzxhn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcwbzia.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxiizgs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiwvejh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzumybyf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjcamjz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxsugsk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiicfot.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2llkvbvlh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhypndo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rubwvbks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2byqcoqbd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmacfwo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2intsmldx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jxthddcn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsxryeq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uccvffwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbixdik.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtzhuma.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhibexoi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixedln.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bszazmld.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nppivltc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxlpzc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlgndju.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtubqdpc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkmtosq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiinvfy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpvbppo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbsguod.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cdufvycz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rflyijcz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vhffjcrl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rljdxqqm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmmbmja.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtcrkbm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrzgbvw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdoizus.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmucgouw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2huouzvzt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuuerhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxliuvgs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fprtlpiw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2olrrwhsl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcwilj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdukuqr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eganjkdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxxovze.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htqksnyp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzbvyvz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2erowgmvv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2funvstox.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnusbxd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfkiaqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcgfaxn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qeottnfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvyjqmk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhddcl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwmvylb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbqyndx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfvxkuo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2peysbnxc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqaxsep.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onxoiswg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2solecofr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynauli.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2enaciudo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtthxzwp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrgyyfl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abvexquw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhauvtjb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dzooyuwo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkscumsl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxaccnp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvjuxzl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqgxzzd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjicyj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvslgwj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaqufnp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zogbwfhm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdupfym.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjttpfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fttyaeaz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwqlhtf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hembpwtw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2shofexxn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gseigoqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwklsyk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpdrena.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfbuaog.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aovupcgz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbzzbbp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xyirueiw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bezidxfd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgxxgee.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmdmywo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2waynmomo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhkeqhi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2etpxkzjr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthjljd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rknicjlp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrenqeq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iivmjhii.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2beuzrfvo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqmobwa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rejaahcz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oeekxwwm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybxtvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zclgmhpg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncagqysc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmigegx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdjhdgi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqtadjm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rojazoux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmuwkcv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgrfllv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzvxlaw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jpljufyy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oojojtus.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfknrocz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlysyvn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tymfgksp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrlwnlu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oputcqwx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybccvdpo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzorwyg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgeacsf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgugqtk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uklarvww.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfboupea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsqofru.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxsyqmd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjspeawe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzxmjam.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhoiygh.html


<!-- 参考信息 -->