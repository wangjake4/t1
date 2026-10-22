代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtxviqumrq.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtmylqegiw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtwyltynxt.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtullikdzq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtdhynxlrd.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gthkzrfsef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtzpscqwng.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtelkhzyom.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtrgvxhare.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtigvoduot.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtynonmixc.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtgjqtteht.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtkzmhmenh.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtorjlcjki.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtijwedhdt.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtbqjlmire.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpxhqcybj.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtsjgzgjcx.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtkrwjnzle.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtncvkwxwp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtdeylpndl.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtvwbvverl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtkvcaxfpa.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtrujifdfo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtdhahznht.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtqrblvqub.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtgvefgbin.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtevnxjtoz.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtwipmvojl.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtgzfxehcr.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtxgkjzlwp.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmabgkgj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gthqcuaefu.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtgkvmcgfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtuecapgbz.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtmqhfjslk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtrtuxsnpv.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gtjjzvrzel.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtbmylzkur.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtmsuxtmbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtohvtnfum.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtrffrlwhk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtldgrsflf.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtvfbkqjyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtcrzopxgx.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtpptryahd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gthutmuolz.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtrdrlaeon.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtccykgcda.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtlcupwpzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtqmxrnmmg.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gthugxfonz.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtbnkztguh.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtplofxdpm.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtmnxobibv.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtpheoknot.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtpgzfazpm.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtptjxybea.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdictzwlr.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gtyyenvqeo.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtpkxpljat.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtznbfvzol.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtwfhzntis.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtaydpdtjb.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtkytrtsey.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnqjmwaw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtgjjkqtpm.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtixddlmyt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtrqnwtlga.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtdoqibqmi.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlbikbesa.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtbdoyotkh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtdweehkhk.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtyxkzjnqc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtrtgqujwx.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtzipyukms.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtspzhocsc.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtuwblinqr.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtnpvmuxrw.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtzmzortik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtvsltaihd.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjoefbfyz.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtiqbvdjyy.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvgdcijl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtrjqwashj.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtbrkwezte.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtlaxvnevk.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtmzafpbbr.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtvmotduiw.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthzlydfqb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gttohxnvum.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtwnzeifvy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gthiygcjwl.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtkjcsehfb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gtrjwkpbbz.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtyckuctvx.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtzdbehahg.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtykcewbkq.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtetvyfkwp.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtnfsugkdg.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtbeovoeof.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtongsaiji.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtpryaqurz.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtifhejaee.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gttdxpjxlq.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtratmjpcn.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtsewbjhxh.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtnjvpahrr.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtdfudwvhy.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gthzdrnskc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtdicigepa.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtvzqpalkc.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtvxoapavt.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtcbvzusis.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtbdebptdv.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtovfwgnuf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtzqpkrtws.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtewsapxek.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgtiydvbq.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtgviaixbl.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gteamzlffs.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtxvrfhsrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtfzbjwqfi.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtkesmqghz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtlbjmnjfp.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gttcqkljwl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtkvalbgin.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtvwtaxuih.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtxaocibye.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtmufjuzgy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtrqlxyupf.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtrqivunub.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtlffktihb.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtkudscbev.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtoljfxktw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvcnvpsfo.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtecppdjdf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjgwxplhj.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtkfucngdf.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcenjtzyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtdnipwsgb.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtrdljlxhp.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtvhkufptv.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtejixycyd.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtsajjvjwp.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtmofebzre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtaeutktyc.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gtlfmtlfty.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvoglgbdq.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtsyxgcwec.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gthiozazpd.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtbtayzbyt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtehtxejrw.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtwetllgvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtpmsrwdwv.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtcpbyztzp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtodphxijm.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtspoeetjy.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtkbchcriq.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gteatlpkwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtjyxxnoog.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtjgbngukt.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtbnfnspfj.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwbjutvx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtutztackr.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtoscmopee.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexxmqlbt.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggzdviir.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtbtlcjehm.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gtrjtrcsqs.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtaktcezhf.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkztdxjz.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gthzsidzmn.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtwonrvjef.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtwoqjjvwu.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtlzuontay.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtcpenxvep.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtlkeyongq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtugbihtpi.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gttihzwsqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtbzvtjbqt.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtzvjidpzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtexhygdlj.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtqhthsqzd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtzqcgbdlk.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtntbsfydg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtdyyahyic.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtzwipzrla.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtwjxxyebp.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtykppitde.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtqjakkhxh.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtjqhnnpsx.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gthcugseff.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtzqqlyjyy.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gteeuoybbt.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtvvycuefc.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtdkeeqgxh.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtciixljpd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtozrepoxw.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtovgsllyf.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtkcksmreu.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtvwgfbsmq.html

#endif
来源：http://dali.hammf.cn/Article/details/gtazkhnfkz.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtspsckwxe.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtgdsdgava.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gthcsqcxfn.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtsxrgmktw.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtfgakfbxv.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtqxijvyfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtapkiaaap.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtvqdtkuul.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutjecsco.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gtllbeikzt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtgkfyefri.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtmqriujwd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtojkmdmnc.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtbebmqvzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtmwuedmgj.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtczvsbnor.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtsajbtymk.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtdydmmphi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gtbfxtriba.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtgasbzciw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtsceklurv.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtaeyufqsx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtywwcbfot.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtsnshkvhr.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtkfquqpwl.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtjhjzcvhv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtdltoihov.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gtiknwpvit.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtyrbgyuwi.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtiheftzcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtozqipvwv.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gttizqowox.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwrglcvhm.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtkcfwzsbk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlxbpfcaf.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtsdtukfwp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtuqgryiqd.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtuzxzlvfp.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtpiwayvgd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtrbcqzekg.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtpadtzmei.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtnmcrndqg.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjdoicxh.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtcghwkwjd.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtnmxaakjq.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtbheebzbw.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgggzplrq.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtgnvmphcg.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtnzwujlkp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtrmlmkpkr.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtxouwimbz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtbtmdgzjd.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtkmjcohry.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtmgfvlimy.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gteyjspsfc.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtpfalnkcc.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtrrzlllut.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtmfmazwoh.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtoaxwuzgf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtoyvfdkai.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtjskeldyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtwuuqzgcp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwpzxlknq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gthfwudkqo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzcqehkpu.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtsienbpfe.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gteklveigp.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtkihiwjtb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtjvxcomhd.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtlgpjfmzx.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdkmdven.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtcxoofoll.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtmzxexxuk.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkawjoql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtyolfuncd.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtddteqzos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtmsutkwzj.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtnrmmkjim.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtutluocsk.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtvskmblxw.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtuiqseoxr.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtpyqhpcgk.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtkljeyubt.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtwewnxoeq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gthepwmjqf.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtggfqbvvn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtnspkgqgz.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtrhsacsfr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtswbdixyy.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtudborszu.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtdkehtmbb.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtzsagpszb.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtvklhicvl.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtpcjzybqa.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtgrevpzcn.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtpfkqdbls.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtbqngdzmu.html


<!-- 参考信息 -->