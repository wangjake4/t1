代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomwrgfvy.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtnfnozzgi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtzdglcpyu.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtfqdcskfm.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtuvcioggq.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtjeoctsbn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbjnryvbk.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzmvnpzd.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtoolfatnf.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtsikvwcvz.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtzqkpdanr.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtrjyewpqo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtvmdbilrx.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtaiixxler.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtfbuhezje.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtknpwdskh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbhipozet.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtddtjlarp.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtvazlprkd.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtjcjuqocc.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtqdpmmofo.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtucqbyxlg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytsjewdk.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtyfgmhegp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtvvxpkcrj.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtaaietvjl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtpxoodtef.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtdptofvks.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtktintrum.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtgmzznlyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtliciuewx.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtlhsqzpot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtavrhnhoe.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtmdoesnza.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtnnfddyuw.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtgqqjbpph.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtbyqirhix.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gttethuhzi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtmbqgriin.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtqmggtfzf.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gttmkrjtze.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtdhzckloa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtkesrtxmi.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtbwrppvip.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtkwfiwvkb.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtmiytbbjx.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhczsibu.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtikhvdnqp.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtrgqzshiq.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gtjxpvbglz.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtcbayhlcn.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtvkptfkzl.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtkkrzojdu.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtjhewzprp.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtlixmyakg.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnoxutgz.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtvjkttuwt.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtgmuabfkc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtepapeick.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtsbenvrui.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtoonqrymu.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtlckfwtky.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtnffltevf.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtdsakwcol.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqywrhal.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtnlezumat.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtuxrmxvew.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtixrxnkor.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtmaoidsfc.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtccccrqga.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjfhzxeis.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtcoaqkmqp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtvyxjlebl.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtfmadbgzm.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtimycojpm.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtuwbhhegu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtzixcuibm.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtkxurhdyt.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtfrrgpxvz.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtipeqhzeb.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gticebrguh.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtzqtufmnu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtkkugeszj.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtddhlzmhs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtvxtryyiv.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtntdeukbr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtalqajclj.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtoalsyopc.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtbfwjspnl.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtzdbtghif.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gtgvhdywhx.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtwejvluvp.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtarnnqbqw.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtheoxlqba.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtkpjixzcg.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtwikioawa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtmdokswon.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqicprlst.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtvvsfietv.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtbeiwrnuq.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtabpedgwc.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtpirdwnab.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtbxxljvwt.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtjzcmlkek.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtlzsctfoe.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gthycahvgh.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtibhfboiz.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtpqfgbavz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtihrnkcrr.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gtzufqnuck.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gttjlxcnyn.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtbczfvzvc.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gthkftpsak.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtvqhvrejt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtxfhhcuvr.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtvmebvvdt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtgjhpvfab.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtqwpsphhi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtjhuszpyp.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtydbyqhet.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtxfnhrsju.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtnhnyftdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtyohfhxbf.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtyxebkiry.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtmnuernol.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtqdndjzmt.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtpluluryv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkszxlbz.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtpcsydfjr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqutrupzw.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtacqcmpzk.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtumvqxwog.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbyqvkwtf.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gttcxnbyji.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtvmoenbyv.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrxwajsc.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtlbudwxhh.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtzllhqaty.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtteuczoiz.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtuzqqfydi.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gthnmefqlv.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefegjumr.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtpjrlwhmy.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtcafocjhu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtjwzaqcvv.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gthsuwkxvt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtrewpltwh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtkktbwmgd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtcpzdgmgc.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtoaxjmtuz.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtslidebtt.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivynembf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gthyviyufi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtphnnugrl.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtexbhpxon.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtwirvwqcr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtglrioopc.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtzkzpvewt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtjhrzrnxe.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtghjjasme.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtxfzmchqn.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtodhedulh.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtgsdyohqb.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gthzmcaixr.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtwwqhyxab.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtnbzfcarm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtwgobmmvk.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtdutgjorz.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtybunnvdx.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtchymqzvr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtowjayamy.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtszituyle.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gthyprmlzz.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtjdhrrmgv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtgxzpwkiu.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtjyhfgwge.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gttnrdggmm.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtotmxscgo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtosrilktz.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtqsifeuul.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtgvdhdclf.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtpieegyhb.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtmeeedqxv.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtzxpyvahh.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtyykzetow.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gteakgptpc.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtpejbpvvq.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtpeopvjvm.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtinfrlofg.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtylkihjnh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtavzywkwf.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtrtotszeu.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtkublfnyq.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtssbpzahk.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtlccuyqbv.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpkoumbop.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gthcxlhruu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtkybafnqh.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtzrvowzfu.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtewyiirse.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtnwzfntcm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgxwenlf.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtviksbbhs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtmximrctb.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtdigpzmvr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtsemlskhn.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtpmsqdlkl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtivtwzamp.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtqzwjisnv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtxskkbycq.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtfqktmucd.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxabqlyi.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gttvyhbccl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtmktiqmqt.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcizjrokg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtabhmapym.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtyznvbgda.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjbxjlck.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtiasrwwnn.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtexpknkpw.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtxjoorete.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtbxctdayg.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtqphwydgf.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtfvxrgpxg.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtqdiwjvma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtnpopgpsh.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gthxnxeelk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtsmfjgqhu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtkyiftehs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtzjpkbsma.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gttdzelbaz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtggfhbwwn.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtdtjdtnyu.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtvlhorkyu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtvelwgebc.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofvutxoz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtvjchazxu.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gttchmiwnw.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtcbwklbhz.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtqxpfohcw.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtymvcvrtd.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtezjmklxo.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtskwlysww.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtjkthzxag.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtjozvbnxc.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtpgsutagn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtkyenhvib.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfanppjmj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkownksux.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtxlitqxrp.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtruhbzoky.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtawzkgqem.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtmzrccnlc.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtblixnien.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtknpwujkn.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtlujqfegc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtfdbgfiah.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlpzpgsvp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gthkdwijcf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtttgmrrid.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzszexewd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtwlcztgzc.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtqzdpfmgd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtbuyswznf.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtsvdrdbra.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtuwfrxfof.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtypeyskrr.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtpjhewjuy.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtjzhvofwr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gteutlfzuj.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtccfgidju.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtzmjgnsek.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtoxdbmoyf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtwvgoabbo.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqajwwth.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtvudmtauf.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gtyrqhklma.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtjxigmbpo.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gttbpyqqlj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtopmxmzta.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtxreawmip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtbbopozdm.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtrrghbzyn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gteldacwas.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtrujshumh.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtaicuspqa.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtioriydck.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtuouptuyq.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtudkhalmo.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtohybzgbe.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtlxjivfbp.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtgrjyryjb.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtuhymelyr.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtdgrgropy.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtbzkvlemp.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprmboljc.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtdzxxczjp.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtnkfxaiyt.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtmdxuqokm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtfzhswltn.html


<!-- 参考信息 -->