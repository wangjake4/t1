代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvzninx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqwqlte.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hklgsiwu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2spschtmn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfjqswv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdwtlhv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnjqgtc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czpuwune.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mblekxil.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2itxquuei.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcnhyew.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsjklww.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytxyrl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdeqly.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjskqgbn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scmxfhsj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkaaaau.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2egywhfrk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vakjhaub.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pcriixvc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnufdcyq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyzhscc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpygoesr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mszdahih.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgniliaj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ganrbgvk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nbenmvgr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkimhxeo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adthefbw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uitpvhsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmgepgb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwxjdao.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwtirjs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uyurfmnw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qftkepse.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2blqkfveo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mcejypey.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekawswrr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xskznifs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgevgkc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmluchw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qarjausj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ubijsmxf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzlkbpe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeeqbvs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2srxrmknk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaqbbds.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pawsmiak.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpxfpyd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjnhgmz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sabaydwn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rujhpotn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pummchml.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xiusvtml.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpjwsju.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikayfhfj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tyomyaaw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjomnbc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfjutm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcuxaap.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnzyewt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nudsihsj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlpurbt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxthnoeb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnaogld.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2elgcvyod.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbzpev.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2primgjfr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qzopbort.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvhfkj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cficsajs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tfianhhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoxmtyj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwpshfy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crsiupxq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2brhxtcds.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvdmwby.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gozzitxd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnvgqwq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgpwzf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zrswotvm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gaugbpkb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2biokmtzp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2frtxvsjp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tagnkhjn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgzzhwl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyjpigr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdbmwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiuwqwa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkvthbr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dugpoaqe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsciepga.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xprvslxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uthslyqm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdqfid.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtficyar.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wrucitja.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kygbxqfa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iynluhwm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjocqscs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tugpuyzv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtlyjvp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2frjkgjsq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyrzztw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfidifu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tyylfugt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psnusabn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqmhkqj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wprvcgim.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2krlwwohz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmmvvqo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtxwnwu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkmrdjy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmhewlc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2udyxcsju.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfowkrov.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bphicriv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsqkvfu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbgujot.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkdzbma.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2scagqxof.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyahmah.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxvtnrc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnnzvjl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2emifldgz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oyelahek.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dypwlojq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsfoboy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unxorihg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zchgkeww.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqdsfnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igizefox.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ecknvgsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phzsleca.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvkjyxl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2obnsuyen.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrrksoz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcpkjvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdendyx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2frwpyynm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2stirracd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfflczq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbpurtw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpzwpz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2njwxypzt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohevcrvn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gebcpwjl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxpcnxd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbohovxc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2haexgnou.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekvuhgc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpouhwi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wjouwxmj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzsusgv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2thfenhrg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pivfacfg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjoajh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkwtaue.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oodkskdn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rczqovqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdnwwkz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2epovgies.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaoknqx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxutowc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oowchdle.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdsgdyx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2onyawnhz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoyppth.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bokehopx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhxntza.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcopcaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfpmzu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepflpda.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxakdtbw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sekwasls.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2koqteukf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gowsofxa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtnnnbr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtyalhw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxztzrxw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuqdzpe.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2agqjzqkg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcvhnql.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uobfpsrb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdkaulz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pilbfwgd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mesxppbn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpzfuav.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjcbpnp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpzgcef.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vehgpusw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbmhxdt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cerlyxzm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvfjqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2algorhsz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeqgyoe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bsouvvqt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqnbkgt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2huwcxwlw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdebyelb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlgregu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsyiigx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auwpyjcp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kazarwym.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qktatsdc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qveggany.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wxujwmju.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqystmd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqotnwgr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obbupgyv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsopeoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bclqlngz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xrugdlol.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xekimppk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zehmnzjd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfoudow.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuotajh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwplvdo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2teccftdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsjyty.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elwbyloi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmxlmo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rujomlul.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjjeypm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyerdon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjtpps.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zifzkpqk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jviwloxv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2apajgjql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2akmkqssv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ogopdjgc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhhenc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbrnuij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgnvuwb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kugsbcku.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoowlgs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftebojcu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2myrtuuzq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iufuxvuq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2seytgsbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aexsnsom.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zklcijvm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsoobuu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzwdii.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqjrlqp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvszeacf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxnnyce.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2clbdmcto.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndufijhr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjisgsm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbkaphn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mawnpjuz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcclxvoz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyzbsem.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2boakjfdi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdwpvwa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxqqyuz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfeltmc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvelzfn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2caauafwq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kapooywt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdpeqta.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjdfgxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idgymqcr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eudrpjkz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oivwjilz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cphcjwcc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mtszktfr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuxlhyn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2omsywubn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2etdavspu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbscuk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2atjachlg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eflssabx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqiizem.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfefgvyw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdnqusc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnvcazr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gddilhgb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsibxijt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwwuppd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cifurnkd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfoivmu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2asbinxlg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jreigpvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2unncypqa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwunub.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuefcdw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kyirkvjn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwymppw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxouiv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeumqoyb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lekckibl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2clzdyufv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlcxuti.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiskock.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shqsjahq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hggidufn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tisphxpo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzewpgxi.html


<!-- 参考信息 -->