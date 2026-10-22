代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thlnseyt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzijxxl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eithpouv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnchuwc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hneagfia.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sysppbik.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmpcgpt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2egvntldh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbznrth.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuywsyvz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtygnvm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfofiwqc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoiynre.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgbyrne.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfkuczu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2izxqudvn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfeivau.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyxfldg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpwkide.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kozfermr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmxlsth.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsntvsv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2malodmwr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeybjon.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2croaubbd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfwhkac.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvvpnjs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzydtku.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfllhyzo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkmrnwb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zujefskj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrerwzh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyokdedt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvjbuho.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvmkpsi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfktfmxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcxpsyl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zznqybnt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqyqipx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eonmxirv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rphthoqq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2egdivcqd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2usouyyjp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfdhnkr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmiutcb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmutnvt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfoaue.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmhrhit.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2efgerlib.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbevootk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyznurpf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crldukrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yugiimyr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzdmkvs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atopnljl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uioakvlc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiuqhhz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2blyjozor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dfobfjph.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwowzy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbveozbw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2atcreyxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2urqjwwvc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrwmgxi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubccxoj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dryspqak.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnhexaw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hujdhnfg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yboxbwhk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kylsuoom.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxuwxbm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmzbbyd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gghrgomk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2skjvvpsh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iezzljmi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eifwjyfb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2czfszyly.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iujuvgkd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvehfspq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpldlsg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aubzptpc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqmzzjd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjbbyjo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2epsfgghz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyikbxvd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgctmylt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aayekdmd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoksldm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjvrwhl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zszccypi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkzpian.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rtozlaek.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhihsef.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxzrkhm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqnzds.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2askisjak.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xendaipc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgygdiv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvizhuto.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvwfqlo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wymbmtjr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jilnqoxw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbrxuaz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxueafm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vchfqvbi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkvtosy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2djxeztft.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgoeoop.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2smwmmfbh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2izlfwdto.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdodtrb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmkmmer.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2osohbfzr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbrghv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdhupfx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqtcopi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tgghilfp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bqstdmcd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2igbibbfk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2khzptpxf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoiupqq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhiljus.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhqkxgh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2petcnenz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yplcbzlo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lehminyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zznyxnej.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqojqzdq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlabkxr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoqnwyt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfjcfjv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwgqxgz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iogyaaqt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrgfkui.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eprhqcka.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dmangayq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhosoq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhlrbco.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdrkabu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhszmest.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcgwnly.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2objnluzh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2naxzifnt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbulbyvo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qupxkeyr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxzpnfw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtxubar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2plfsragq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wostssgf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aohmbaqb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ydukvwom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqwidfw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsinckjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjdazj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwstmas.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmroxva.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhkdfq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yatqypim.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnyxlvp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2soxyxrcd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjglvsi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2alhrocbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsikhrtv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgpada.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziypbwto.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgiyhgr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tjudqkse.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ioymsoor.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvprcuk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsovwuw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaaxcbl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nslchlnm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lcannxhi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbabbxcy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tboqwdoe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofydxitm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aogridrz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrujyyur.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wboebtul.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xruxvwco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvgjwse.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmywnzr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcihjhqh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txgonqun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfuzfhs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sngqfjko.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdafbbfz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ksotyhts.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaokrvn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkdcacy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvsqmpa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlywwuzq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jatslzjy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkdhziz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzmcpyq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2avledccy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2segueguc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jofnequs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbulefgg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedzucu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbxcywm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hktczxlo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2npczaslw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjgijso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclxaarg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2azoudzra.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcamdrqo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwvhfqy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpxskdt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdnzixg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkxisip.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzhhvxm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cissuccg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htkwyqlx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcziomzp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lniouzqo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2boiqdphr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvnbcgy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2btejewnh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svzkzuva.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfsrids.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdjsxwz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zntonzyl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2domtzcmd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpvhwid.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2famuepka.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2drsvotex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwbeqio.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hivfspua.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwijdthy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgretmoa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xganiicy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbpvydz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwffluqt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkjjmbt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfqkgbg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqscuud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuairsp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwakaxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwnnlbx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elblurjb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wikbsojo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmdkveg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbitsjrn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuimmow.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbojvxp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuqqmiz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjmmgvy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sikydxqp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ougouwsm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyfblei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfldygu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yihqppzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebnbkhk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwvejxj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsseiln.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwqrkev.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlnyawm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2enhybovh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fjatrmdl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbalymdw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2loycgwxk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xepjsgks.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2irrtnurf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjfsojp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrklrjc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttgued.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpivxgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjowydhx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfybufy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nidsavcd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyjivfx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjavyey.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2godudzjs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvegmrre.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjontfdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjepzqt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqgdtn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcrcnrm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tcncsjqn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqriqht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zenlbvix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjpiemw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoegdzu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btbsrnhj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyelninu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfmjfxw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfugubk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwyoor.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozabglkv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbbdklo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iesdwiya.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhmgbt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrqvzyh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axosdbpe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtlgkbn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rydpiuxq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvsnppn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgcojm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jirgzpmh.html


<!-- 参考信息 -->