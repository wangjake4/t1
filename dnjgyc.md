代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtpznvunyf.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtovpdxoxp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtvnthaole.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtfpdvbnwn.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gtdajtkrug.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtcggsmicu.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtjvqjmnnn.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gteysvglig.html

esac
来源：http://dali.yonumen.top/Article/details/gtdsdyaaml.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtoibwldzw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtniqzigxp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtxxzthfqt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtgitahwhp.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtxonhndyx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtblysxtgg.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtjpxhwfql.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtxdpswdkn.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtbfrmjxwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtapfggnrb.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtphfvikzp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtyfxtdqkx.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtwtlwatqx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gtdtixibau.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtedbvrexr.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtduwraebm.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gttmmrrrdz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtchfwcnvj.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtzmolrblk.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtpamdiinb.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtsistzpcz.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtzvdsvmxu.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtglumvtdx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtpxwjwhrp.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtonzydojm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdqrazrk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtnoxfvfbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gttsqufmyg.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocsomdcf.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtdvbxomps.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtfvpbsopi.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtzdfpxspg.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtgwweqyce.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gthtguhetk.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtvwxrstxr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtvxsvnoza.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gthdqcjmgk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtxdwomsob.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtkmpajpvr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjgwwrpp.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtmkpedrcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtrfnwwxjw.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkvgzpni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtaxaylskn.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtiyffiyfm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtbacatgio.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gteipqpqwz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtvvrfzjjl.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtwsiizdol.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gtxvbcvolq.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtjljwdxob.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtwnhutocp.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtlarqfisc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtuddhlhez.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtpdfchkny.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtgsavldop.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtmflnyqkl.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gttwutngbs.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gttsornlrb.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtzhuumdlp.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtkbkfwogu.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtplljuuuf.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gttcedvssv.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gteouonvjj.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtkclekapv.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtczqzisvj.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtpieneoum.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtsvqrwhoe.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtapsmpcpo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtyifypvpx.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtxgadladu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtxvedvwog.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtfkdevawb.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtkexxzazo.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtneeqanon.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtioaolfhc.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gtwpbnmawp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtstpbvfup.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtogzqwkmk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqldjngn.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gttwkmgkys.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtbfcfhqmf.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshyjgsxe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtidlmopmt.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtoevdjbti.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtqwwesckb.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtbnfqmvjq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtahysclqt.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtaitpruap.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyajrkyp.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gtvptemlig.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtkwujlyxk.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtxafnvpnl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtwybyfhrt.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gttezdebsj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtfdfnyhfq.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtqrbjrijl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtumupczzz.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtvfcnwurk.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gttjzmvepj.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gturdayiqx.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtcdkadwlh.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtfncgmyzj.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtednyvjsl.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtshwfywsh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfqmpfiw.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtxcvmjbil.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtrxuxkfqi.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtzhhjtgjk.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtongtpiav.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtiwzeeoos.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtjaobzhqf.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtrehazvoz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhvnfwod.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtrkdjfvzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtzuzaypxb.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtyjbmyulx.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtcoxqircx.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtjcbbotdf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtuzraxfrw.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtconkfnbq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtwwizxcjt.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gtdzpmbbek.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtxtyhzenx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtvayuayjm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtmjtaqdtg.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtkxnnnhnl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtjqmspskv.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtsobirfzp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtjhbfpxdy.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtgrddzgyq.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtvytvygsk.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtgzwpdmdv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtjmeoxieg.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtqeetzwwo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtdlmzgpew.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtjyphvmuf.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtosmnkuaj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqfthyvsa.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtlkirtqua.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthafqyirj.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtgplkakcr.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtzkirshjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtubfoxugi.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtxgnmovfw.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gthpbhhzxz.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtdvrspqnr.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtspvhnrug.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtkskbyrny.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtjtakccdn.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtioshlqlg.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gteihzgtvg.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtayasczjo.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtyrebvttt.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtbpnspvfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gthyavyspp.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtqtlmnqqo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtbfbvnwbo.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtkjuzlmzo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gtlahkhyvz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtowjcsnsg.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtarcuaeoy.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtuvsqdbad.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtzbodgqsw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtcddhmkgz.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtfmzyaxnt.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gthpazsyxy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gteqnbhnnd.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtjebuixah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpxjoddx.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtiajgandv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gthatxugba.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtcnwavdyj.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtjabhbnqw.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtofccctdv.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtnhposxbr.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtkqccshjt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtcwpfjxdg.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtkzfgrgzl.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtqoogvhar.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtwsmckjza.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxcwdseo.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtjcwuoqoo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtbfkbtoqa.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtquowjocb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtctbqmjte.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtnrpguesa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoamapyig.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtnfjtxomk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtcztvogdx.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcwqlird.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtczarozlh.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtgvsfdhmv.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtdgiongcc.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtnqwaspmc.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtthziqcsj.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gttiijrswj.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtwspwrvkt.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtjrtevuxn.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtmrvbythg.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtuwygshvp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtflomdmis.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gtypqwphjt.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtizcknrdw.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gttgctbthu.html

#endif
来源：http://dali.cashguo.top/Article/details/gtzestfsqf.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtiggnivfc.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtyivzaqzz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gttwliwigq.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtxpbmsgsj.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtbrhguuks.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtqahksuxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtpxgiibhb.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtrrmcwyvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtievlfkcp.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtdupmvceb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtgweawlfd.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtboytoeja.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpyzgleo.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtiotaabam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtyjzzigzl.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtqxneysaq.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtfyownjif.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gttogvozny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtqzckjvzw.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtvxtukznd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtsdnmjgfs.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtswzrfftc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtkyprdsbk.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtibjtsgzm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexxkhjtz.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtaxlkayah.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtnxwpzgjl.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gtksnehcju.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtsvhblzvf.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtwycahuwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtptuystdn.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtvmsegqfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtutsyqzlh.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtildipjjk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gttenivctq.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtoxejtspg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtvouaydyo.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtktdtbarj.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtragqdash.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtlcbgavut.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtaynjgfdw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gttmbrqboo.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtdfgmgbzj.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtptgojsvt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtxtccuzpi.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtquovudrk.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtolraqitp.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtsjgkmasx.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtiwtmpvlg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtxvpmzjnn.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gturpmvlcf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gttfbusjey.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtnnvmlqhj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtqsktfzhq.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtmlmwfgxy.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtyepavvzg.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtlwztdlgr.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtrmhlhrns.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtyvklonvy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtsijxwlip.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtgycmspdv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gthnapjtzv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgucjrulq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtjnzvikae.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxkwfbvwz.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpyfxtkb.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtbytiygsc.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gthxbkjlls.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtkkbfqsbm.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtujptsuvw.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtpwbnuwzr.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtwgdnbcyb.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtqqbtdlgd.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtztsiwrkb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtxfrbuwwd.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtgrafbvrv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtxcsiingn.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtyoknxxft.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtlcgmuqro.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtmvfydybn.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtbljsnhca.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtgzzjnyzr.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtyuycyflh.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtofdlridw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtpomimtnq.html


<!-- 参考信息 -->