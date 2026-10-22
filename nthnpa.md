代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnatovoh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlecpnso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmcfgsx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epaewflk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uudunxdq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvkgodg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msszyqxc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkqeaqz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2swgkhjvi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cedfuxfp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yughwimt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2euctjoum.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2trlwrblb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbjdyig.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tetbgive.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdxzemh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byyiktmm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tahnriao.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rusfbilf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abixpigo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzxthna.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaohmpw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqolcqgp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxurxvy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiutjoxv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxoqhkr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flfewqcc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2empxcjfs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjzdtjy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnijboh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyzjroo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qynjmysr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yppranqn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzznrof.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llbkhqtr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2suuvzcow.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddskkkaa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2acttipva.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cznsiogt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2emerezdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwmyyci.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ychmdrly.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwhopin.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpvexnx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsznrquc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaphgji.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtkozkn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcfxgdj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2znqcnwre.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqpysmh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoipmqf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbwtbsf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjtblbh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwnnttg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdgbmfm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2llglpqhv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dbozwdjp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgixulwf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaknvtk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsbmrqx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqvlrni.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmhsgsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjhyyrs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uarkapwe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnswpthj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgwyjoy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvsgkty.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyyyxlx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfblgony.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvycgrx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qkerzyun.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjlxeyk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vnthcdle.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnhgcsi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaogbau.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhicviyy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgkltgx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvjnfq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuxfejb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiajyjo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aydvgiwg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mphndunj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2inynptyr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoaewtd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izvyoozg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjixspzd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmxowfh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmbppgh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mxitnntk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmqgufr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpqhzle.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kdafxuwi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgaqbbl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaxrcgz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rigwpgmp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hpibotmy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yspcrvrk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqapdstp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnsjaom.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2plfptvel.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2onrjtssf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsdsfck.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2piajsgrt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vknvvyfu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsdhevx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lprjyppx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2atvxpeje.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiutukd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2deefsdgm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqvtec.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2byxhozaz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvovwme.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2havlpsvo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvhyvlz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzhylxd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ultkjpom.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrslmug.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuwykta.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yynpflaq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjnnof.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgjdqmi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrmnubf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jlujodwi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkylgtei.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpzipbh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2guinrrwn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oteoewgs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cetaevow.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2srkcbcrq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kizwhabv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vijkhgzv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nktpvkww.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhndywy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtkabaa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjtgbuf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcaycsh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2etdaxngc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fzahavqf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otduwcou.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umsqjrxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrpjtbx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qifvripa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdmcczi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsjkioh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lluqdjvh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgcratx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byjprvyb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zewtjpcx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gacqrjnz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2egejeyvj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzjpcgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfpmgn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tiroaelc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpkylur.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjhatxc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtmocaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtpguxi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gykpxxai.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbubxpx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lofduuas.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpeolav.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjqdll.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwulmxw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxvgcjd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqzfgkh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgedlgp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mtylztep.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2onylcpxs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxlyscf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzvvrhv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2slajadbv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsnjzhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yloeoyct.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvhrwxn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjkfywv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wexvzdko.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtqxpss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2widzqhxt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlselsc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvuujdi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2drutnjgh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbyacmf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tazardnt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzawbbw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyfzauo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgcfwdk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eykfchxj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2thlohzup.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbeduhb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeutahz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvaywp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2glnehbay.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizdqjjn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmogmdtt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2finnrcvk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlenvtb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiczkjx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrtvhpn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhewicl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eamfosra.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhwluyh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yypdnpik.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkqqtaj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbjajua.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkncvcip.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmwxbgs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfinoozz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sqljwedz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjkzisj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdquluf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrkkzl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2moxleiok.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcujxjch.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhlorve.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeqfnkv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gipgukuq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmrpoop.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lisouqxp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvqwmwh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmntufqm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrqrlqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oupezbkc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrrzvg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjzsbvu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzrynzj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiokcyju.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsxlznl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggapkog.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtaxbx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgeqblk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwwapcp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2biewasek.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vszzpenl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmseydr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsogicq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkhstn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpfsua.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2slmxehsz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsqqfvo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gztzqxqa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efvunucq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvaamxg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sijgsqrn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2owrhdguo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvtbdti.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnszons.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpoynaz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkqjytn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2doqqpztz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjkfmpq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmnyul.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficpvhzc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zymubjej.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gduhpkqs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrslmqfn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gisycusw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncptpwn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2durkvxdj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnazeqt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxcwghs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbmqgyu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfethwv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzsepmp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cbozrtyj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgcqljt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvcganx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxznfaon.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyxdvro.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlbxqlz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qgharnsx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjnlbxm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzudlfj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzwrrwf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njfovdpx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncetcrbv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pefcfbwj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmpjrhz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbkqutg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwawvpd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmuxrzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zthaqxct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfkklue.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hffdvrsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eneflwjg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrdmpiv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aygvhfsu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhialue.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wrweljkm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mghufgzo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtflcxo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwfwxy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqgapvj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azjccrzl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2juogddoj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2slxdfhwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoqebsh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjqnfa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagkmtan.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuiylmr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurydjhy.html


<!-- 参考信息 -->