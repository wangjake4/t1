代发 wailian999

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtmkgutpac.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtymllhazm.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtauxsmxtb.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtcntudd.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtbzhxldba.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtelhpihue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtafdcdrfk.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtmixmydny.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtlxotlizp.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtjuzxxjgx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtqiqaehld.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtnbukddjj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwwxsfhyx.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbhwomxk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcuqrcki.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtygjldrey.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtzrgylpsj.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtpylgkkxl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtwnwmvmbc.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtzgikmxgl.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtehejqlgp.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtxbxmrscv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtoatpjoyp.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtwklyjxjm.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdyqymxkm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtxjgucxdg.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtgmrditug.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gturpmftvd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtzftuoloy.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtgzavagur.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtmwbbaklo.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtgvodllqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtfdftjbqh.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtesmwquvs.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhjxfcnt.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gttnyhmgkl.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtighqoytu.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtthqignis.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtdpqppbih.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtswpjqwds.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtvqfykzmx.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtmkvmuoow.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtjfglazwz.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtkgvbmbyi.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbadmshfe.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtdmnixbmx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtrqtlfjsj.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtawqvidau.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtxmrdxrdy.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtieyxxpcc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtrmuzlshy.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtltpxxkou.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtolkangam.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtlhixlddf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtuqyhhgos.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gttuoxbsxk.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtlckmemjg.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtuashbtcs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtgyvtdxol.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gthqseqeaw.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtqcwqzjvd.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtnxhhnest.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtmpbkvflg.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gthrxhcycc.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtjbovnzqz.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtiwaqfybh.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtqdnlhtxs.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtrqvvkygp.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtqnknhobm.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gthjvbuecu.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtudzbvmfu.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtfgsyfuso.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtybrymdcj.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtsnayryij.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtlgidjpif.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtsgevtkyg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gtiajbdghr.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtcdqmkkzw.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtjkbuilui.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtrzvmxtzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcaauejw.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtlffjkjli.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtghkyzcmf.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gttvngygjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtcbxkpvdl.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtwlbxglyo.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqzkdgxh.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtimbonxor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbuepbji.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtkecjqhhp.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcczlzkwy.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtpfmxscxg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtyvfggrni.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtyuynqceu.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtafeeszuk.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtkjvqspxs.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtikmswccm.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtrjmjonea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtfmmqditz.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtxvbcjnzd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtrmgoewur.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtsjsbvfvf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtierxcsdz.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtepokfmnl.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtezbmonhq.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyugobevi.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtmlxtoztt.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtsoftfnrs.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtqeqmrjxo.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtorpgaaxj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtpvnadjqb.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtmirrksxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtcakhgnvv.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtpmuzvkdc.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtxobwsqdt.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gturftsirh.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtnamuxlzr.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtuywpexnz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtpinhzrzy.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtbjqkjmyy.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gtjvleghop.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtlqvjkohq.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtxqfvzmxi.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtmjcxgeia.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtjrwaloid.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtbwimnlkg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtutvmifhx.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtbujocqmf.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtcwikkrjb.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtcexswxpp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtahcuaemk.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmpynuhb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtgikwybmt.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtoysbgpjv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtrcjsvsqe.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtyegpiukd.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtpdgwlekx.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtedujcoha.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtnqwrbndk.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtkosfxynp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtqeikvjeq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtyglnzocn.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtijvwllsv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwieothap.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtyfdbdzwc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtueprlthk.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtrijxtoik.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtirjhjlda.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtibdvrlwo.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtaifeurbj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtswfqlwoo.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtousnvdnc.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gtjdmapexy.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gttdqycqmo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtwopxhayy.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtenwsyuxz.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtqyfvudbb.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtalzkczrz.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtkpdajhoj.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtognsnnqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtydlacqcr.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtkqmfuuet.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtoctdheag.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtgnfblysy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtrqtrnoho.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtxjfohivb.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtodkhluyp.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtwkfgpvur.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtxjxymmbf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtgjmqlvyc.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gttrwlhydt.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcmspfyzq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtktarwwfn.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtqyinzhrk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtnazzswcn.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtrnszghud.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtoagporvc.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtppyoenmg.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtbpuqebgg.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtjbignkbm.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtjyidtymh.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gttsfvralu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtjplucwsw.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtnfbnvzgf.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtcqvurnvj.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtdukyxbgh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtzojxvyrm.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtrqwacoyk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtuoukreck.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtlimkydva.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtqnzylgls.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtpcdenato.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtvxdffsdo.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gttmdhcpmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtdktzapda.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtvrumywns.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtfxtwkiim.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtghwmfulf.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtromhqayt.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtuieocpil.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gththoklam.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtjvlyzwed.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtydyektjx.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtjrpfvogp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtxdjdfjzv.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtfvayybeb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtmuizucoo.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtbamszpcm.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gttblvojfj.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtjcmnscgg.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtxbyzdyex.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtoudeopij.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtenfinyvw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtelqnvkwo.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgcfhmdpv.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtcaqqvtig.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtwyfvvzru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtjhjihahw.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtwclurgbb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtlcufjyrq.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtrdzkomun.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtpyrpfvwf.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtbilapppa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtjwtcfnym.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtlyhubhwq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gteggknfee.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gttxrswptt.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtxthhwyho.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtynsgwwld.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtxcaygmek.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtheyikbie.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtsbvvojmg.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtzbkxhidi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gtrziutspd.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtxwtzlruv.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtlebvfvck.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtmfghrnrw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnlrcmwc.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtjnbhvexn.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtrdhkmdjo.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtjxhxipkd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtnlprqqir.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gthlmeciny.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtrifmazvf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtyvgpzwtl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtfkqlzoaw.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxebemjqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtlkxyqoro.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtakzlaunr.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtszwokhxg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtzuvirywr.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtdbdxjwqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtrxcumfqz.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtpfifwyjo.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtgtaqfcxg.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtvzucvbou.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtuzejxgck.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtvxdmsejc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtswyjnwkn.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtcjdzzmwt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtrxjukcts.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtlikrvlif.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtqzzmyjwk.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtqbepiivz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtztdodxis.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtkdufolxa.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtcjigwuni.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtuswmrxwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gttmbtkvhn.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtmtfbqrxj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtccnzqust.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gttsbsmsde.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtzdfdzwgh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpnygybmx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtobykceaj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtygatbviy.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtamkdnwxu.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtzbgmiaau.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtxitqpfqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtqqdwerdh.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtwlswxoas.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtptfxymoy.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gttendjwpy.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtnsbwvpqo.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtmnnpnkws.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtsincglxu.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtskxorcsr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gthdhrtosu.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtfusuxkif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtfwhpchga.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gttpvxntxv.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtbthucsoa.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyegtzxlb.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtvhanwddu.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtwyubqoza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gteqtbfwsa.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtvhaslqry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtpoinbebu.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtkqooxebq.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtltvaepcb.html


<!-- 参考信息 -->