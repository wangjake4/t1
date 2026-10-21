代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtdpcfqlju.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtohlcatji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gturduwmkx.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtlavcjmjz.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtpowdcdfa.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtbporrtld.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtmicklwyx.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtbtotmrni.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtrlhaogld.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtvrbizbqe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtgglonnkz.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtgguhstku.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtvsisghcb.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtyfexcput.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtpbatznfp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtitokbahk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtfbvlpkzs.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtyisjelip.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtpdpbocwi.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtmzgpvtak.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaluwccna.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtkikovlbr.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gthsifbczb.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtlwqipuqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtcsntbxpc.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtkxiziofq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtznauctpl.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtxrcandsh.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzmxumja.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtpmqsigfg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtzcnftwbe.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtlbovvycx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtyvshujfp.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtkyrnnedg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtpneaunhy.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtdxprqajv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtxmcynceq.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtjkzfxrrr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtdzupviaa.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtovvhjogj.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtvwpyiagr.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gthhanvpkl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gttqdahjeo.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtyehrknwg.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtbmkshmtq.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtaaxmgfzl.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtrrkijnlq.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtsnsyxyeq.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtnxxmtyvt.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtepxmbchx.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtmznwqqvs.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gtbkathcka.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtmttxiaoy.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtwmsakkob.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtxnukuwwx.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtubxxgogw.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtqcffjanx.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtvahtyyst.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtxrnlxgtm.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtpsekgiqn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtfcvfnjfi.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtkyrpnpzz.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtsqliaojs.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtsvxkxkds.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtldwepysx.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtvgxdvcbn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttvmhiexc.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtqxnnzdwd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtttffhnow.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtxifdqpya.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtocdknrxf.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtmnkatgmn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtzdvsdrvw.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtpadaavbl.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtbonnrgxn.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtxkzshsld.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtjcopfwey.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtjwncsooq.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtaynvznwe.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtgaqjtjac.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtumwmmeaw.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtxxleihid.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtsvljbgww.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtniaazfgf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtinlkspfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtfvypekib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtmpvutvci.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtllavyuqh.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtsmxnpenq.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtvuelcdcx.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtckmztbfe.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtmnimtavk.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtkmiragne.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtkgvpwgxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoyzluql.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtsnapokvd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtqynpgcze.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gttltwknna.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtlrkailul.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtiyfhxsni.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgjiduew.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtbqqwogfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtstmufzuv.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbpwdenu.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtbrbmahgv.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtxjcgqsal.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtntlaslec.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtgtjerpuz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtbygwrbts.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtrwerhmsp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtddyskjwu.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gthwqgmscm.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtujjsyfgm.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtdgmkobaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtwrctlxia.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtluqewwxb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtlazpqfxt.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtddabuvtc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtchnvsron.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtignybyzv.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtznzrsehc.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpuxfwal.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtomqxpbwn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gttgpduicm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnjhsrjfm.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtdroexftt.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtkaokuzoh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtenojyste.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtyylplzvw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqmpzzari.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtsuxrvnce.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtdrqglhrl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtbetbvldn.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtabtwtwsz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtqhytvrry.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtonpouxui.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtvliqwbxc.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtioleazri.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtqjfcfzhh.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtibffopvt.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtnujymmbi.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtaiubosnr.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtvwsnvfyh.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtmqgpzqet.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtifsquonh.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtacluxmct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtxrvgfteb.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtjtdjbgjg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtyftrshrq.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gturzdanzx.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtwhhvybmo.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtetctxhiq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtenhqjlza.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtiovtxudz.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtgxlqtunm.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtjlqwbscv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtjbmatfgn.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtasnboghb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtunqtusqc.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzahgmgsk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtqxywjnwm.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtkmixuzeq.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtdbpxygeh.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtxjrtsalu.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkgyworw.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gthcpymusb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtprfimybc.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtntxupyek.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtcmwkxnbb.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtetqjmxhw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtpaqgotyn.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtdshrptjf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtmamejrkr.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtlcprhzyh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtcpgimzoc.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtxlqzmrbp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtfemqrhsn.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtfcuugzks.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtkzxyljea.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtvjqvzjbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtftiulxhp.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtdvcrgoqt.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtgekdxonv.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtayxqhlsy.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtgaozzege.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtnxlofrsd.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtkhhkdlkf.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtzdlhqyss.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtgqufpzeq.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtftltdebo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtktexrsyw.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtqqkmojlu.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtxewwnzgu.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtulnkxnbg.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtihhmhrtb.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtsxipiizc.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtchwbhmyo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtiufubvof.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtdknjypqe.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtbcdaibwp.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtqpmjnmbz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtteznoqhf.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtkdyeuaum.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtczrruzor.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtkjywbulf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtrasisvps.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtnapijuhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtorpvntqs.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtuafhtrxy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlnoreac.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtdlperfqp.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gthtknvfla.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtirijipbn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtalbgmjsq.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtkfivnbuv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtekrquagw.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtvmuhfbai.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtksyierno.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtusrrtpne.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtqdjeoemo.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtwyjvbxmp.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtawzztggu.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtrfncigpp.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtvvmbmxig.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtsuofjhfb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtzvimzauf.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gttedqmlxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmzqfvujq.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtaroybdqa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtzbyrkhvo.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtpvdlhaui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtvescenph.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtvrihuxxh.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtithqghma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtypxqxapw.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtdggggscw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtffopzwzi.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtomurbkyx.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gtagqtroiv.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtlakcxnui.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtuksbbsvt.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtozuukefr.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtugakyntb.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtcuybyznv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtrtfmfwyq.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtwgsahqnb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtinoleocz.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gttujaeacz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtbcluhyss.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtezsctrtl.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtvdrxpdlh.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtbnseefkn.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtjfsosvgf.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtmqnemarl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfmoajax.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtvueqxxuu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtzwyrhnty.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxrwsuyju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtrghcknfc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpzbpyfni.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtcbgxmcpy.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtqdkfnala.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtitozfvwr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtdscjtanw.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtgsvrjsgv.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwfisxvc.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtojsrujmx.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtbkoxlqnh.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gtgwwkfkge.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtkvhjjtja.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtmymwmrtk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gttbuuvqlk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtvlmtcmjj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtdzzovihf.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtphfnpmug.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtscbnbkoc.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtpfbzmqdg.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtnqtappzc.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtimmpovbe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqmwgpej.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtlmaeizuh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtijgpjqtv.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtoqkdbksc.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtlsndnfym.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtmvbcajlc.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtlychiejs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtwzjnuqrv.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtcgnjonuc.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtwdnjqrip.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtqlkbzgyz.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtqoxtvgjq.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtsvoeoxco.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtfljibvzw.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtdvscrvqt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtakkofhog.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtxgkknejd.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtdxhbvjdv.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtefrqmrxs.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gthxstmkwk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gtswydyxfs.html


<!-- 参考信息 -->