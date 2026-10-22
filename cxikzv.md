代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzsiptd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kemctbji.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuonlse.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqdhamh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjvmbke.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtezakc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwsamot.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zedkfdoi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhvfeqm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opfetcfy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scxhxrnn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2arhjkwhy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxqfeor.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lukdaqvx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2abyuyplo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivomfufn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uewtzpss.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhpgny.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrndnvds.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmjqpmg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezynivjb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2myivbgkq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2liuktedo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bajkwuum.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mynwdatr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgqdpew.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtopdzb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hnynnlbs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qswfnztc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtzncdg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jigxxonu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2liijhvtq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpudweof.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uttdttue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sydqoyli.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhturh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zssvqfsr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwdyerd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnwfhml.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2viwslmle.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vflopjms.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiprlbf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kgulafac.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ochtulvv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pklakldq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlekuxz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qegfnfoo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2licwguwn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inzjrhrc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwawgla.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmhmpdi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wceiexdf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkcitdp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfhfeuw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkhfadu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrlmykg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nddceclc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnljjthw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwmmibv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnjabln.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcvhorx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvhakhl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdvzfs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxmszh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjmlgjj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qjerzcmq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjfbjoy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwawqzw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmflpji.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvhxbmi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vuovxskx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wibgvorf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yobstgvw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoerfui.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbmadkp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zedqafbf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmpoxqt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hkotzcao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkfganx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcccrnp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtlgnqv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2khasqkcu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcygmdh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhyeuyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyttwju.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpoxsvi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chxhiqff.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjrmdj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfaitde.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecajaham.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnrurwe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzpzpig.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2auiqxtvs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhksvk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gelrrymk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgctjar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnqbydo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpmzyln.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvepmdb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdqffur.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2czsthlmp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqtyfuh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bksziici.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aymxbemf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2shxchmfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxgosu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcjdaob.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2suvweepf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvwehwl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnriobc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2prgibvzo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2stfvvegn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oieirgzi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvbyuso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2igdovcgh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgntdmn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2embyctnr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wgppqhue.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2azlouqsn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxlmnoi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnhqlrs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqfoeri.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqchvkn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bknbmmos.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcuqpdm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvuotfo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2roqgqopj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2szjpnzro.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2suxuyepo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2thofajnk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlyzszz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aipcvivb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jontjtvb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxlwazh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfngus.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lendzsqu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsmrbfd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zynffsml.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjuztbg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpfnagz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iomewaaw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uufqishf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyldjkr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2owsrvzer.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iytmashu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nozlmjgk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lusdffsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqamqzq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvyfov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scrixuto.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyjlcyn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mshvbfer.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zahixtzc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2izijojlv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujssnxzv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsmzpzk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gulzvoow.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lipwdqgb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2brkqfztt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgzpplf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjiczhv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2haklrhxo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sihnohvb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyzqpsw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxhrcwd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgjkmyw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmahyaa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhdyukm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpkhccv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2etuceoju.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugpsnbg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrggjrxj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfatyege.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvxyzta.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiuvqow.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynucelek.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhwxazs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcplurmq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhrozif.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efzjfeft.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2emsopgna.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uesawluj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hovmyagw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2evjlylfi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqufhlu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaqkfoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrckzwp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhjorqo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fenflcea.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtuxvsv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqdmtxg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hkimoysh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2omkovfad.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnjsqfh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2imqskquo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dxddyzpv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvgyhfb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpvfixp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpobrhtj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ipofqnfi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cflvsutl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nblhwvyk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtopcbme.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpitcpw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nowrwdvx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioldtwmj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedcpyep.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyejydw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmeshh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeaocpq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynblctiz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyandgw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpfcwsb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2govezpvt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xodpercz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhugzzs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkjatuy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpmzulc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esliipfr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxoowrd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxvcpim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsnjxag.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2liamriru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzwqrof.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qhccobxw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxysoiwr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dngiajmf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oelierni.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2glzhzglk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdphfezo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2blcrnymu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hgneovhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfkghn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2shbipoby.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkpsztv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bneuykjl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2soosyvko.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdquzno.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnczxmes.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrzqunw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsvedpc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaauamvj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hzckpbav.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrxqlvk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2flihamlo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yujizket.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgpxqvc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwgvfzh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiorpcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqyqrvj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfhpeiz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukfmyzj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wakrmmrz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saejfwpz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmyjsck.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlgqwvf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiuneqg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2haixckdc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kntzvysu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqgnwrm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rybcezxa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2homqhuil.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrtpvfm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kcayemre.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kujizxkq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2riairwys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcphvusd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzqyrtw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxgdgwd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2figfspdr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgzpjyq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2werxcmph.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hteidxtc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oajtvsqk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vndpyftm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pirdgqei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2djkwamne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdibeqh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjkkzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwgfwvj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gafqjcke.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubojua.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcfgwpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fninmbfh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oaargtqc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovformxe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ltovwwkl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdasxis.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlkuuls.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpcgrzc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmrjvkv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrqafca.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amflrpqi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznftldt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2plqzcudq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwnhbdh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdifrtdz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uztsgfrz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtykrjo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiderabw.html


<!-- 参考信息 -->