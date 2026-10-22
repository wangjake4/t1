代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2peuttpax.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2peofgoun.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfegcxmm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2touykbls.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoemhys.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgzdyxm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wijfkplz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtqiwbj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbgtkzt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkomybcb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgajpxrd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2blsqufzm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmphyax.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmxelis.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwvwgnb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mflnzlji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwpttpt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2abctkugl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bibfvmht.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nacgnxbx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvebgpha.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xilmsjbr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dszfrldh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wogmbues.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whuymwzn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjxyobm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ealbwize.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pquipnqw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pumtwbek.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrflxu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mutyljru.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwoifbn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aivwvjkm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaaesex.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxatiuv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gywbbcpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obdxxegg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pamgrfwy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtauyjwd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pticjwib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mviioxep.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgroibb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzkyvsl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hnilwmga.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyytwadx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnwcgkk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zjddleck.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfsffms.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mipjerlq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nwadtrbc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxarqthd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbsiau.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgctoxtb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhjlpc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrnjesv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwqiahj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2keohyevx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xozgzuyz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzhczmz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2huaqgucn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnshxgf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjglffab.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkadzuv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqptnlhl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2layadxqo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdcavyu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrflefz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2calzhwqb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adjewkgf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vgurxdbe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2obqovvkp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uhedygap.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcebteh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwsayxq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jojdhjhb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsidcamb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2auymwhpn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpnixfx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiolbwo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xwojicrt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqiyblb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sdynggti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgxaphz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2axvosjdr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oawgprdj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqnmbka.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blgxaefq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yehmckud.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ujemsztn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuzwslw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxesidd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nmecewco.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdyqhzt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jliuegju.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzvqbhr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aycdauvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gotioxpd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbemmcmu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kezizoin.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpvjbng.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2khumxwuj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2olmdxmco.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aslehbym.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2phoenkbz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrwyhxk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fiszgwkd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xszbjeqg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqlhebi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwvgoof.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pslskivh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rbquibsg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlkirqp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2afgxezfm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qznasyfl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhclmat.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwartsz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rsykuhxu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ximjjbki.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnhikqh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vinlltyo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2syfrgxey.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gypssyya.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2husqkzmx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmtlhrr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlvtuew.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqlejog.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjizdipj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pscdgjci.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwjaljw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfdhtxy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2epmxqdbr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wslhuvre.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2igawwplt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bkttntyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnjwswh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvljica.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmxgyaa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jppwosfa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwddjc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ousaizvz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnobsbzm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbvppmi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emjsxgwg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xthbmsdn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qesgpqcw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmqwzlf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shlaqtqw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qlivtvxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acgjlbct.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiwctix.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rcatcgmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irtwrwok.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzysznov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mownrwdj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmjhii.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfmqpsx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaajgta.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2smlqtkdh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhkzepn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owipdqgq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgpmjdq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2efzipyaz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2meovcfzu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btubfhxs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwrtqmz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idewbbmh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhwyhrx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bcezantw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jakkfnta.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpisndu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqumszdg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkikqcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yktzjaqp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvymzgs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2puqfutyy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wynvymiv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2whloxssy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gorkdfxp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlptpvw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gazcgobm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gohrmuos.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gaspwvld.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeprnqg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxiuukm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mryvarqz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmrekuj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmejtofh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2htgkvhur.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiffskpp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpneukd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsbawha.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nidawulj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvesamn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsycjrj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yypjflll.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgsnoko.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2deybwkxa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxorkaym.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfuldee.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsovued.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvourfgd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmmpkrt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoonwsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hguzscpp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2exkvkfgu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zlypjhwx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2snpprdwo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2anlxagbq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2htoffmeo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjlspce.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhasgtcl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trfcgvpv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjqojfs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2depiggie.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyksrfd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjekctf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmuqdhx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2doxytnax.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ueplhsgr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dihmwlvu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sadkpxrg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bggdxuev.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcovrho.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwicqxx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fagnxymw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lepjnrrc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwblekh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woyzflzb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyrsote.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txceegso.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2shulwjnj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xazzdymw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxooeek.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmfshrq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jattxwnr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhbpbsh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmlxqlj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjdmjvu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuzxaor.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnxxdgt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itcadltt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvsnfmq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeewghvz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nscpwcrt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeeouhn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dukhryvs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxuhqyx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giqhsiwy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlyxcth.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzxgpiz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvuqvze.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnjxsth.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efhjluts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuilmop.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fobqgjsq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdveggu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weqpziun.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdfqepb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaltpvq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pweimzrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gskqdpqa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkgirwv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2isudvnnd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjhwqz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnottbyu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdwtovy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbafowu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hhknqcju.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsboris.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzaanzd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedwmjvc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ostznrbo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyocmyx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yipnswcs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbrwmmq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2deobrscu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wezjxwtp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwqsubt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dthmimft.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrsgeam.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yykmucni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhnaypm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyghovm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdikbyax.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azspojvs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvlsyj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efgmuwrm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbwqnmr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xzssieqr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtibxhl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhjdgme.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwctbdvk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftzhny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cojkuywg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dywxqmih.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elobrnvk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuqaowl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzofsjua.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nklanasr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbelaue.html


<!-- 参考信息 -->