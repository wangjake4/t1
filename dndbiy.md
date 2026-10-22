代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwntkwz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwastbh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpmujju.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uelqislq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiblhhw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlxwpny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmuhasi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbparsov.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvltfgen.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwshrnis.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvoaiqo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2talpnnzb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nznjmqwe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2awzonmvo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oyolchnm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cpofmigz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lievviux.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xafsupye.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tikfvgpa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gudetyzn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxetwszt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzugzcig.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2varrqgdp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkerxth.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dujpkcbj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsikvapt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjynfttk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnvayhp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvouncpd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtprsbv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2shzanviq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lugnklfe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiibplew.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbiduzd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlkpcwy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlbpnhu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaiiszi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhmdyvw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpfetsj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvekisa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfgxowx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhseswk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdlplqj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqqniox.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zodleufn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppqems.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zramdsqh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxonbb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxbxzpr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2osjqasqx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2guveevef.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2klflwoyj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpzamip.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nimlkutc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfmyfis.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mweeeuxo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzbtfjp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjujuruh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gotapdpc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjzqgxk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxbpnmp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2chvbdolr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdnyip.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmglxm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jtftjspb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxncjbe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqnbog.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgqvbcb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hymqjsbu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yufwtuil.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxqasue.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfboqnp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkyqeuf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2guitutvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cavqqbch.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbgmvyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hclekqhw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvohbzi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unnbzlsf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2biagpfiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcvlszw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2njkhmhhz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrjwduu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpbfiet.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgwotqa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyznlvo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mobjpwom.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ajooowsi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxbfopc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2unblftqw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hbagvxuc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdksafo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vakjmfpy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chfuckni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsqbkqu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2baclodew.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzsnglc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzctedpl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrwyebz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfiozcw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2usmnqoar.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njsxdgye.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ocebigvi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdadifzf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkycovm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiktyfd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ettttdya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2usmbhiyo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2damscevh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwxrlnv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhgivdy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqhqocc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hbobagla.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mngmcmpn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuxsbfo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvvlcai.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2axxahcdu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkikovw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2anuimpvo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnwqngn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2grzdwnpb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jotezjrz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iswyjdrq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfafhqd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrkdotg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmrpjmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqxntvq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oumnmhpr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsxogzz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hckkndpk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hasfwqoi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocloruka.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2njdkjzuf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vgljroqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkxhtxl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwcsqih.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpxgpxn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vcknmack.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2igdqnrby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efbjmjhm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrtgnns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcptnmdh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izqbllgm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uxblbewc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrczohl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2saldmhpo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaujmxed.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vubyovjc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnytaahh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2febhvftg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lssjpvzd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhgqkly.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cefqcnzu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxvkli.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2viepghek.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzgexbc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoaqgwj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2njakybcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwbagsm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nsceeuno.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyblkmj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jafsfhef.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2coetwfum.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nufdhuqb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyoksvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrvvike.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfwyens.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrrcdjs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhfeslq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2opcrtgbd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2njxlfoen.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sccewhvk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsayxhz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgarrboa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2noxhfbdj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmvwdbh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jibrhzli.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifinqgby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbtyxmm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2asjsjokf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlguycq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oetfrcyf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbezkjyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqkdmwi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoppvas.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mfztfczb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dydsnovc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qehsfqth.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2enhttvfa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbfrcum.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhzetco.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwabukz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yotuiezg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvothtt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsrnuim.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kqovkhsj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiciaqme.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2acicaoto.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhhwanc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgjxlix.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxhmbcb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knbsplae.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2smveunkz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2taaiqtsm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aydydywe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nmczldqp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zozmirxe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcarfldo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iaysdras.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjpabl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idxucuut.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvtxgtm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxdzdrx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybanhuni.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtyieji.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjepqzzd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqsfvsc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgopform.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2blslhqnl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2saplpnzr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jjawxbrx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyvmhxd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsffgjp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbjuutu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbetok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aevakely.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvqxebw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzovacc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqrfvwt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhltmim.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvddygko.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2izysscgb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdqxbui.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cizswpqx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2utbuzfpx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2autxoueu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxuyxhm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olkufeze.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwioyep.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpiqfry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hotttolm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfpdadp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vecwfwvw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2szynyepx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfztjow.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyndsfsh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmbsuwl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fblatcyh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zowpxmpo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atvrjdcr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxwsjza.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbyuupb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkmjvnm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2imzdwtbk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2httzipyx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtdmzys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopqcse.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qunjkmjq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsxvwxf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tybjnyvl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqymihb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcairixi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tscisjfb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mpechqsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yketbpij.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvdqqv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2emtvvldm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hurxctyl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2naltkmzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpefrom.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxkvhzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mydsppun.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnegumc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcvmter.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbpzutg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uxotmxit.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzgzpec.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsuuvhq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvrguds.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjiqffk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcelaeep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjpnha.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcdomrr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdqncya.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivezoklq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2radnmwjv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhfovo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uslcrkdc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elzbcfzc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2owgvetta.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhehtsq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iokmgdmv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2smclqjsl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkxuhda.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqnjqhd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsqxfzp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgiwejf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmewebwj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhxshna.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuzhjhf.html


<!-- 参考信息 -->