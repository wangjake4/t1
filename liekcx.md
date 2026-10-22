代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzevqins.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fngnuvny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aykukjbs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ektvmmsr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfejylv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvisatzz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsamyzk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyijupr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wephuhdw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtgkszu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qigwoehb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iekndpxp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jglgxywk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrletyn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrhykur.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvxiibh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgfnevt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqzffit.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqqukpa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hedbjllm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ambchjza.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfdftob.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acsypurq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eytqgyvy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tprviike.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbolxezw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywspyqns.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdwtdut.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmjurag.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndubnpwu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsesszwy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxztbahh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkziyk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfiijgg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuqqnbg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsiltua.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxvtuid.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdoheaj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2shlanmup.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffhskr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhakdbbf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgkfbvd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcbkbwi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmmpje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkfdapn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzfxgzv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fumzxijm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbnmcec.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skqwfdol.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hocstsrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiugdgo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxiubby.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsbfqyn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sutdqhmu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hacournu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2glknqvkq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmrmjdw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sklrvpgt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvbzikb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnhhmze.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfqknbz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tygjlgpk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2otidmzgv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkezvol.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgupdwv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hozfgeit.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfwpkeo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfwjxyz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2turmqkfv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2geedaous.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaewfqr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urevlhyo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2edutmkjk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdmdeaa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqtuuok.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2frqdoqvn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2grxvguvu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmzrpm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfaujrr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aakuepxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxdctva.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2shvhfcrn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2stisrget.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgypjgif.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2efrdcnac.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzjybpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhecivfb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwwtyyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkkkofh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2orkxqfmf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjuaumh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaabryp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2micwlnve.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pekcycqi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piaxcxgy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zorbnwnp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kewaktro.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyrrodb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwawsu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2makprwgu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2esofzaso.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvzgigj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fskmxsli.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llewkxnp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zrctjwyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgcdksc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgddydi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oettewmo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2afjafmbr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqifrimx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrkzhdq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zttreaci.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kjontnoo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhbqzbe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhwjnha.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2njhuaazy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbawwcb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkmvpjf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2atbhgybb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcoojlu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2inwxnvjw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsbzexs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdycwdf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vrftlohv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvkfkup.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpggpkk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zodfilrr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2apywmkkb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeqbftw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnrxtxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2keugqwfn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbrffyu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2oinryxph.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzupntkz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiysqvmt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umzasboo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkftephu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzzukst.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vzouuoyq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhysegsb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmzvedq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuzewxg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqttgknc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttcodd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnybrl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2whbtscka.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2aagarvib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raeteukh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfinchl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxupbdeh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmavdzd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqiqcl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnqhyuz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhfiqdl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwzepqx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqvxdjn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqjsovm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbsmmup.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2psabnkxn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhfryya.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjghkxl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsnvrbe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vewhgcgi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbzvqlz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfdissf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2adegnjwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiadfdd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqefkdn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydbbad.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ksysubac.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifckqwji.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyramqwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpoqaio.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvbibaj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnftjxgk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afyqauxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsfdcqv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkyqfur.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iniamfpk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bzexsmzg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhfkclx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgjaqsh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgefsqvx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcfbnmb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspuxemd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hazwioio.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcmdopc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvgvuas.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sylwwpxv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnrbguh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xepelbzw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2irabrwhu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynegkvq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpsjlps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixfegon.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnekzlg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fppobcya.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2djsqxxtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpquvjw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oggppvcm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxyfvxk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2loshdfrq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2alxipchc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqdrryy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhphbn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzhwuv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjudwtgf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ertrrnwi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hejitbqt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlktyap.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaapies.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzygsgz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2grzxpzda.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2msxjvyip.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lchmndkg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qobseian.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyotqza.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neeshfrr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpwukpt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldljxsay.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uueomszm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jodiotjy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bnilxyuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ephauppt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rcukqblt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsonnkob.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiapryo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxmorzl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbxzkv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mknblnmw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhiselp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxhwdsq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izeswpdl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kedqgfzm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ifojgqph.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoxzjxs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgdzkyv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yedoukix.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqcwdyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhzxpgd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tivsfxph.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2erjowmif.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnkygw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtwtvld.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2apuchfhz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lownxbjf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zmotimlz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clyutwqg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaoidoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snozhvzq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2taeaslkl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqahlccd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2amlffyir.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cejmfacr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imkjsjga.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmatklw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjywkpie.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lznaldjb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwphmnj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lentnunr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfcdwq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2clhnrjcp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkllvfep.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlmyyho.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrrqmkp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vwauiwuh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2npkwasxs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2swawrbbg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhjwais.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqijlyi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujjntmv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gnggiamj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2okreuhko.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpaaxcy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzfvjvw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxkilvv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzyyaci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrxbltz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zozycowy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txerfvub.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoajmod.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvydzwb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2doyypwav.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmrjxy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzyfdtk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdbltzp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qoycopmt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjaddfn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iclrdtkf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zubgzkvz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsaeeby.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thousqze.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjbvhru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuejpop.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkehoyw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tauaaifz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsoqfnd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpdpdfq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odfayikr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hicihwev.html


<!-- 参考信息 -->