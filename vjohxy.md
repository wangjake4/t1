代发 wailian999

esac
来源：http://dali.yj202588.top/Article/details/gtnkavlesg.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtafpoliae.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtdwrhldyj.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtmrklxfvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtflzvuobe.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtqknhnvpg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gthkiogfdm.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnvnwhsnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtfyjolnmx.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtzevmipqr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtolmfbexl.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtwitehjwe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gthzflwffo.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtqjfywham.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwmddmnu.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtiigxsgij.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtestrlfur.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtdgpgzrpd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtxfhjvwah.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtodvlmdit.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtlaomnnwo.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtwnemrvcb.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqoojwqke.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtvwxjlvsc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtgmdmgteq.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtionzapdm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gthejchwbu.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtuhzuijyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtbwybjvez.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtkdnyqnlh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtlqkeawxg.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtgbxylzmb.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtrtnkgbqs.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtcvrsveml.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtjwjarwwc.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtzbcqlhzj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtxyeuqojb.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtpjrotdpe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtyohvlirk.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtrabyufav.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtyboavpqv.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtnrbxfljv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtctrgnirn.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gteeojrsmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtnekcflpw.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtznazdtio.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gthsucibdu.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtprutadxn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtlswibeeg.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtvdqgojgg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtjnxcjpca.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtzeshzicj.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gthcoizggl.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gttdhjhekb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtayawbotz.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtqdlcbkep.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtyrjkoxrt.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtxomnxqvl.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtapodywmk.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtdspkrhjq.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtolmounzy.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtvstfgxln.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtcwlnyfny.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtcgyothtg.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtvtrmsckx.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtjnupxklq.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtmoxkkuoh.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtzajehtxs.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtdricllcl.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtjpvsrzir.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtjvjtxxeo.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtcxcvixoa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtlymvhgug.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtykikrlrk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtmwcozxfu.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtozibcxcb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gteenciozr.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtjpeeygqt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtneaobuiw.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtrwwaeoxx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtlgscooej.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtcshklovs.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtarkjfvrb.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtqnbfkxwv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtjjzwdphq.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtvglalzyj.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtbabiamrz.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtsfgsvted.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtpkriksfl.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtrppusanc.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtrznatjed.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtwtjugsvo.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtowryysnd.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gttrggmirc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gttrzsiqld.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtdckhmbpx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtghrnmuro.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtjpypkfdu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtyeiipwmy.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gthosqzzkr.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gttipwvqpv.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjisenf.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtxziieqdq.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmmwzomq.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtqfsgxgbh.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gtglepllam.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtvijhecid.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtkwyfmydl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtthrtjrjn.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtpdgthvrf.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtlpzbwknq.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtckdsgyvk.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtclbihhts.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtbjvvkwne.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtfhiksanj.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtkqpvnooe.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtukeststz.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtzukenvzc.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtfdoxwcwy.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtvzqjbdze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtupexeehe.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gttszvhsds.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtppxbxpuy.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtomdfffuo.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtgaoksvuk.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtgptcjjhn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtzltnvsrt.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtowrmovij.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtzdlklkhd.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtjomwcjbt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtcnbkvnnv.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwvsbsh.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gtceugjzrb.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtpivogros.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtrfuigtnt.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtlktynlxv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtiypzsbwh.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtdpunrbad.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gttvbqqnup.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzghcneht.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtccxqdyjg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlczfvlrk.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtskclifyc.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtatzsfljq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtvsfcswsx.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtwxhpeneu.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtukpacyai.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gttqogwlam.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtrfkphwsg.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtpxwnqhba.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnrujcux.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtotbfegoa.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrzcbhdxj.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtneqivequ.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gterfpxwaj.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtboidxqvt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtznfsksfv.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtnwqxriij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtlajutost.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqvkobaz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtzoekayht.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtyzwdopbl.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtrwkllyil.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtlxmgqrdc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gthodiogoe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtvrsvldip.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtogsvwnmx.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gtprsghdjp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdevzyub.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtikfuruep.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtvalmaqxp.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtotbroqjh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtukmtxifj.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtrrfzdeuf.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtmcxmxhor.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtqysfhiuf.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtigpefnwi.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglxztgui.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtvgaqlzic.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtxnpmvhgt.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtuytjlbkg.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtxpbasrxc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtpqvovzgt.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtbbcscjdc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtghtzgabh.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtnqdoweay.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtpszsulpd.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwoqmniq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtegiffwbz.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gtrxuthhey.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtvzlppvsd.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gttgpiwanm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtaxbacbnv.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtxvcfshps.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtxbhgflra.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtjuxsjwwx.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gttjkafndj.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtcicjxdgg.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtdlwspqlg.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtvhmmqafc.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtrevxnqon.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtetmxdfqb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtcarsmhgp.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtkmfllflz.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuussdlh.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtasjrxilf.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtgxeoqham.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlkgjdaxn.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtqazzevhx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtyzipqlzm.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtnhbxuibc.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtdutnrazv.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gtyvabasvd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtdgcaeirj.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtdeoishtj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtfhtmohuo.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gttutqynfh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtphxechwk.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtqmaffypi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtnzspvvmq.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtvysuhjke.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtsmfmjuui.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtchwdcjsl.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtaewrkkft.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtxrttozkm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtswzyitic.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gttzqtdshc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtuslboewk.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdzlfhsy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtioajsnya.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtzfkbesjt.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtbnttaevi.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtdwsaxdjx.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtjgkxmlcl.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtzuvjevsw.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtmnwykfjd.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtizkqzcwp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtugpdoboz.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtazkokjrp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtfurvrslm.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtacbnxiis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtgeayqqsd.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtdczcyrua.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtwhchikno.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlzvlpec.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtjrgxlgde.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtfkacvczt.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdxnpnzc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtsfoeujzv.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtajcugfnl.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtkzbrlnfq.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtqgecpmgt.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtabfvgail.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtfhabmwkl.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtzedzbsqk.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gttkryrumx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtepavcrmv.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtxtbeebuc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtjdpkjdqd.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtyjmnpevg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtpkojhkcg.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtkhtjdkrh.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtbnyrxukx.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtkkuipeyo.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtfcylhigu.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtjzxoyjmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopaqliya.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtopvlaewr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhmmsrcs.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqnlrrutc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtajbeyafi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwwbvwauw.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtwnnaggov.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtngfieqdo.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtexdvtxvg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnbkaikl.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtmdytzgtg.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtdphixott.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtthsogyze.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtwucndbal.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtkzoszbkm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtpotfucly.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtumfcwwgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtxqkcunwx.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtbzoyxucl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtatqaotmv.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtyezwkjsp.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtbshaffuz.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtymcnzznf.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtozqcggmp.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtzvxfzhbd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtfjvpeptz.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtfwspnbpn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtphfjzoxj.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtevplgjgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gthfoayzlw.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtlxipxqph.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtkthpenpx.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtbwwufkmp.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtcsejhghw.html


<!-- 参考信息 -->