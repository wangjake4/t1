代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtwllqvtsh.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gtstdnmihg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtywqvuqfw.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtshetxssw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtmdwdufot.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtbvjbecnf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtlpfbxidv.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtczxsceqe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtbnoflpyj.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtdchxumny.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtrmnqgnsb.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtfijpqmzx.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtvalqalww.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtdvrecxtg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtkdzgycxh.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtggkmzvqn.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gtbklihvvi.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gttmacpuno.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtjjlrdzib.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtzvhkfrkr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtldvmhsqm.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtagnmszhq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtvfuuazke.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtheblayug.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gttqaagmne.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtsnwzzkbz.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtgbcyhrqz.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gthgohinxp.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjmndqlf.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtbbvpbeao.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtmcflwicj.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtyofysxih.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihlwkwlc.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtavzbwkzw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtywhzfppw.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtzvqtoetw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtaylnjwid.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtvykbrwhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdufqkuk.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gttcclimrr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gturgkeltb.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtudpnpssg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtznvkynrd.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtcxkgkzbp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtyakaasva.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtyzqlzrjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtrviarsci.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtmivpbinp.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjaxqmocx.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtrfhrheqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtyorslcse.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtfqyvcyrt.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtzpnwvvcm.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtqshhvuqh.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gtzwefsuxs.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtikqfkyvv.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtunnoyuzf.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gttgkhkzxf.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnsedzhng.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgixnqfh.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtocpiuaty.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtdqkmtkyz.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtxdpnmaye.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtwkstkxbd.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtvjrvgqgp.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtnkadgkop.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtqvwgaovb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gtvjbfchvh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtpqeufkbh.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtjbdyzsyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjnhmlkss.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtxgclpbox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtxjydkgrt.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtcuqdhisy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtomkriatc.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtrrrmajyv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtvhfdfytu.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtfprktaho.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtlhhnbdmt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtjqpzkajh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtyqcvfegl.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gttumaroti.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtslpfewud.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtlsdzvlyl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtjndkloop.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtwswjipym.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtqlqlzhsl.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtwubfsjhl.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtdqoaikbh.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtgjnqbfrj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtgdbhujrz.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtjseipnvp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtnponwhqc.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtsgvththm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtdqswdkkq.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtwqudhwcl.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtujdcndsv.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtqhodusuu.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtvwymcfjv.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtlcfznmwn.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtexcdwrtu.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtookagxfg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtcnhmrheo.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtksztyzqp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtmfywwpnk.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtgxdwhscf.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtvycfiqbp.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjyjexzr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtyqjxrqzf.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtcphsjpdt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtyzstfmzz.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyemghab.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtumqugqbk.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtbyjlsgpl.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtldrlxypg.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtaaxwljfv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtctoyxswg.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtzmukwmtb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtqzidifdn.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtptjyuckd.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtqqvihmhj.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtbbfxxkws.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtkvwmynif.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtglunmlwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtquhmoehm.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtgswjvmcd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtvyusaknl.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtawgvyyjr.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtqwoznqwz.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtqhbpqkpw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtyxrclwtg.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtzfxpugpu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtmbtnglwl.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtnagdojxz.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtktoujjxp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxxhrsgc.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskqwcdps.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwkurqpig.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtvhysevso.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtedbgtkdb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtwqwovxcx.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtqwvweuxi.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtlgvkajcj.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtezcsdbrg.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtfiiozrga.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtahtanswh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gttcrdgghb.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtqfcfuqxt.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtczsorumh.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtkpuhohrd.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtthzliwbc.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtnwhxkiqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtihjaihuk.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtakttbbti.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtmmcmyokx.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gthqmdcjop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gtbhfjcpat.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtxilgtvnt.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtuajwztzf.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtofbntrfn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtpiikcwak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtzmvrxcjq.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtfutpuflt.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtiwpyxxsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtmhoczqnw.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtpjyrmxdb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtnwomibpv.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtwdlnzyzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtewrloopc.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtpwcbotgw.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtabtqmdiq.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtnzwlhlev.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtxhzmgreb.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtbafqgplx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtrxayajgt.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtscvfxzbm.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtjkbehidk.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtyfszkknd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtsajkoiar.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtjtvjjwnd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtpkppoblo.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtpvmdwspo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtfdndnwmh.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gthmcecrfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtecojkuxf.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtbydrabev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtmyecmlrp.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gteffvedxb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtptirmlin.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtapptwouv.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtbwicpqyt.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvkzzwio.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtosjfbuxf.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtfrbfppbj.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtvervbduc.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtjnsbzjfq.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtfinhupku.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtakvejlow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtvnmpuwvo.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtuqskmjno.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcpqwsdw.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtafqwtukp.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtlukcdxac.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtylvxobdi.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtmyzglhlb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtfejzcbkw.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gthyiablhe.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtkrabteat.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtqcyuyhvl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtyncennxy.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtxaowbhcv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtpvyotpyp.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtjrtdglih.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtpieabmis.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtacrzdmmz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtfmjmfyvm.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtwpelgqqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtcqzfwfmt.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtfziyejkt.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtnrwlupir.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtzpsyqxub.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtjagfxsiw.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtwzwfvapt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtnkcimewp.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtypzlghja.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtldqygadi.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgciiisf.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtpclidsyx.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtjxzgnvzc.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gttcxsvdto.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtyjrmshme.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtwcidcsix.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjghnpit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtandoeyko.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtxhlgutco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzdzbsmsq.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtssaepvtt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gthuhtjhgn.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtgpnpyvba.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtbiuvzhba.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtxwvzdimj.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtdlhjcyex.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gttgspfkcw.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtanuvbtsn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtqvhuxnlb.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtgvcqtkvf.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtsohvkrzw.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtpscaawim.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtwbwuyiup.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtlfmvcckp.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtiwodvgrj.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtavbnfjjx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtyhtgfwcc.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtbyufkcgi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtjqcqhhul.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtstmtdtpl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtneapkdfc.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtpwgqomoq.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjalrfwb.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtngxgdxev.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtdrkebdfb.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtmagutjfq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gtblkpmkyx.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtetzthpqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtyivwkvnz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsiifjnry.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtyzrcpetq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyodipfja.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtynazidni.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtnoynvhob.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtleccsqfa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtwxfkqmig.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtkykofwof.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtuxwryiyr.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtldbjeqvq.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtxizgynaq.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtocdhktpk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtvwxdknfo.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtvpbwiocc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtfptwacba.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtdbxbospg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gteohjlwgj.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtsqspbukw.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtiansdqjd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtacyfyaay.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtfsxrgcjt.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtqzhlnirg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtdvmdmshk.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtpfgkuxpc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtsgoyguku.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gttssqjwiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gthmoxnauf.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtxbevsmdk.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtodtzsyci.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtsnzgpfow.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtontabgfg.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtebaviaqz.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxhyvqhq.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtnkjsasce.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtaeagkjki.html


<!-- 参考信息 -->