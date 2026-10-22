代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtpzpjwstr.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtvsctcfxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtzowhsowb.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtixwvhsir.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtugjztqmn.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtaneganhp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtguryhrwo.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojfzjunq.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtpuvozvhn.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtqifxizqs.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gthebctxbr.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtwgrfnmsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtrriayyie.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gttzmmsbui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtmbxnugum.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtetnthxiu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtubjqmfcs.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtsyasjhdk.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtbqbfvstr.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtrpxcckwi.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtkautcwha.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtjfvxazvc.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtimnajdzm.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtdtxvvggv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtnjylolbk.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtkazqtqrh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtfggineqk.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtlueiegxs.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtlowvayqt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtgvojkftu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtlgjutdvn.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtajrmlttf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpggtcahi.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtneglrwyr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtngrfnzug.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtrsjaifzj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtiphtobxq.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtlzyzxjap.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtwvhmkmqa.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtouzdbymh.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrkwneeo.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtbboqgjbz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtypsfspwi.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtdaphzfop.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtjowbojxi.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtrkexoocu.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtrmftdxyb.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtcurciess.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtbmanttzj.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtkxqjsbpr.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gthwrhaaxe.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gttutjyuec.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtqitajyrl.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtxbdcqjjt.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtuyvzutia.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtwvxdlrda.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkqelelz.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtryyupyav.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtjrhzdyvg.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtrzdqblht.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtjvnilthc.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gttcxgoxao.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtllyciqbr.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtehunrpez.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtymtsxdni.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gttalqjrgv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtaiboxoaa.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtzcsnlyay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtbjliocyr.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtmruyvkco.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtkgsaej.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtyhoayato.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtclrqaabb.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtdxpalycm.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtrnvjxwab.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtvghgjyoj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtbdmmnatm.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtkqrzmcgn.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gthlpuhzck.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtlmxvebqk.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtvnggbejh.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtvxvorqcq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gttvpcdjwp.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtlovykxap.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtmhhevjen.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtqbvhthdq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtxkpuhrkb.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtsonytjga.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtpnwfygak.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtqciiamxh.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtcctqnwpq.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtmznrxnny.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtlyudnlmu.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtvhwskxfm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtlgconrsw.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtjsknpxqb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtkfsobtyh.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gthlikmpgi.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtkrtdqpex.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtfrpbqijx.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtjenfliec.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtqyqsvijq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtoditblbk.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtfbgvvdlz.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtbhazzton.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtyhuwmkqg.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtetkqgxxp.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtyjyjwdmg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtwvqowmou.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtqbppnpdu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtcktpjlub.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtmprzeoga.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtxfcvsmcv.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtufnjuxrk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtjmfhcvnl.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtysynbmdy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpgzufiy.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtdytpldlh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtuhprjceh.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtdvofnwrf.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gteggrxuxl.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtrsaaxroe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtgebbqplu.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtyugczeiw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtevncxrcl.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gthoalnarf.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtdjuglbgo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjppffnsj.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtuvgntoxl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjgxywjct.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gttfdrtezq.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtudlbudhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtcpddtwsn.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtvpoxokcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtqiaqvxoc.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtclhmjpkt.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtyrfoszts.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdpzgkof.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrofcyqge.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtsjiucfrx.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtjjtklzmx.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtevlpbpix.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtxvrwsnzl.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtoyakjrzo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gtqkkawmdg.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtgymtnxin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gtcpluhbkd.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtuykeytgj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtcrntwqgi.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtzdcbxrcm.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcoirzsa.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtmzjfuwla.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtilcnmuqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtfkiceiwu.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtohbkuhlb.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtawtyvwif.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtimdusxvj.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtcmffyfem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlayelyk.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtswrdwkgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtsvlyngxm.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtqifctgff.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtskawpwsx.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfomdrbyd.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtziirkbuh.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtrafgpmjy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtlcegcnve.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtgdaxtamz.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtaqrrsqfq.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtdwjrxazx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtljtzkhki.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtrdrpvvyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtakurcbue.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtftwhcdqk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpidwxkmt.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtznxvnlwr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtwxmcrfnp.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtoslytxqm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtwekjtpws.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtqxzmtxor.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gtvwmkvexz.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gttdgzkiuu.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtuaxgqtbs.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtgxdeuexy.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnvnqche.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtqirvqtnt.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtwefbfgqn.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtvjxzaiem.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgppydwzd.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gteoluumbl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtqdptbglu.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtotsdasxx.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtqfhbydel.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gthlqdwhzi.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtwxbdtsym.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtmbbiciou.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtqmycazyd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtclfguolo.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtrhrqdalu.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtrzwqnxwj.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtarfksxcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtphmmavdd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtojjckfgg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gtxucgysjs.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtjpwujlxw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpddmlicn.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtvmcidhez.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtfpzytfwd.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtkfoxxucy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtegxxolzu.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtoqnlvmbf.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtpcirgzxr.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtxsrduagu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtkresjvkl.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtibefwphj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtydfxdhao.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtuukvvyap.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtbxdelnxd.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtyyfggleh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtqjxjsfzz.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtwenasiqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtltwwcuus.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gthnmepdna.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtlrulkjnb.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtljlxyyuv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtwdalaenu.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtwdcgzkvx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiixjtsh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtvpmzbxiw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvehqmflg.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtyucncnqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtsidxpxpn.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtsectuuul.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtmwifvrcv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtavunwrar.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtbraoutib.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtnupxhnyg.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtikdqwbhr.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtoqpvcasc.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtjwnkmiux.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtdakpjium.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejnvbzfn.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtivcyhtdz.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtqckrnwix.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtmabwfmli.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtwfnmmvql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtoyxexlkw.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtkxtsrnui.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtuklshscq.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtqeflbycb.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gteufcjewd.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtwogwmxec.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtjrqdwlyq.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtjsxagtpg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtayromscx.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gttfgcxkzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gtqjoxslso.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnzjebrbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtkjhakids.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtaeltpqrr.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gttjbwibkq.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gttwaqobzy.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtjoasryhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gttbdpaasl.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtycczfqcu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtdxlnlfiw.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtezpfkdgg.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtwbsnamab.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkofoujhz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtpwpqjdey.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtbaexohxw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtobnwwdrd.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtihtovkzv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtgbqwwhwl.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtbyyviqra.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gteuppsjxe.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtvpmeevam.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gthjxyplyk.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtqcyuxbfi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtggwkxgnd.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtbptjbkgp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtdkckvpqs.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtyixmxkpj.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttxlmdlwn.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtrrgymqwj.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqppsknwa.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtszspbvxa.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtrchucruy.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtbvythcso.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiprxrjlf.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gthucwscfh.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtnqmabaoh.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtxrxzlyvm.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtihyvkttl.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtixheimgc.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtdopakezw.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gttcxcnnyo.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtfemaeajz.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtkubizdge.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtkmhgbtow.html


<!-- 参考信息 -->