代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtcfxoyurm.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtdstnjkic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gttvnqehcc.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtaeblkcvf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtrviqllix.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtrzecoiqa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtkavlaray.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtmrhvrrrb.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gtnshiophc.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gteamzovjf.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtzwqbmvza.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtfyeagrsh.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtuvmkrrrp.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtjlocvtor.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtwvsvtbqs.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gthyrytqqy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtcltggjlw.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtzoljeufq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtyjckifdn.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtrqxejxxk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtpzqptqxx.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstoejvlx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtebukctfo.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtremjvvbk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gttekxqfni.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtnnsdlrnz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtycyfrtng.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gttpqeaqeo.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gthqzwrave.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtaynajmjf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtqtvjxevg.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtbfzkfrby.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtbrhfufew.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtactbtbit.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gtohxoozce.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtknxsycjh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtyovrmifa.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtzweiwfrb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtypupqrpw.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtrntzjhfr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtgttjfogx.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtirnkfoko.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gttxklcyuv.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtfosxsjkx.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtmulycjdu.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtziwofpun.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtqasriumn.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtzwmxyiaz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtbbjujhfy.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuwdqnjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gthypfwvsi.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtxakwlqju.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtfgqfbahw.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtuiyaskao.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtufdyewuy.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtryhedxua.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtwkecqxyv.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtcqxujtvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtafrktruh.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gthtaonlqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtxzhqlunr.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtvkjdyaoy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtficbyfwx.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtzkcrkzxq.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtrngbyfbn.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtuljxvbxp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtvtqlltrx.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtytnejhuj.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtktvdkpqe.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxhlwwig.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtnxnrljtc.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtyymbvafn.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtxxxhbnzi.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtaqddlomo.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjcepqlid.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtehszdmqe.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfesvawh.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtdztxvkif.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtjutauseq.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtwjxkxpaa.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtuxekmaai.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtuubwdzpb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtnvhedzvi.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gteuihilvh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtetqolrfu.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtsoegltju.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtduqinfjc.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtupxcippj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtiisckcuu.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gttuomhfhg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtryzliejq.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gthmgkyhxx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtbhjvfrgh.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtbwhdiwdd.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtqhlcjpcf.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gtdyfxazsz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtdooaiheg.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtlfjpeqcf.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtdkgcpfbx.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtairpexyc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtbsnhczzm.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtnshvojts.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtdzuhiyqk.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtlbtvejrp.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrddujee.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtszxnctmo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtlgurgesr.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtxdrfpmuk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtkfrzppwk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtfgpninwo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtqfdrfufq.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtaanbmmng.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtcqkktoon.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtflcpuxtu.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtmmxwktxv.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gteishpgrp.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtpmlkgztc.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtgowdtvwf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorkzngjb.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtlibavvdb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtzmjdtiuj.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtdeurduyq.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtnaayravh.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtsddenhqj.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtmflmljxi.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gthoowlkyc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtmynhkfdc.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtjnmiskdy.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtkxuztbiv.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gterccxyaq.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtsipjrtjh.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtblfhvsgh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtzcngupja.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gttvucgdre.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfxdphyt.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtuumpaxop.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtrtsqneoq.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsisrvcgb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtrvqlktnd.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtfdzqyzkz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmnowew.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtnkhvadyh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtcriwdppu.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gttieqtcln.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gtxdtoefsu.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtzbmhfpyt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzswtniq.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtefircggb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtjegvydpr.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gterxkuhco.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtksouuxdc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtndtdslht.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtlzyjvesm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjsetmyjs.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtkagoedva.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gttjwumsfk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncntibkh.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtcvsipisu.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtyaygcksm.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtwtighgpu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtipuuznlk.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtjztaxcej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtqqotnyjj.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtoicypzha.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtskegtcac.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlemsgxqy.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtzuuefzbm.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtnyndhdlz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtnequpmig.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtaoxayyed.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtnfkacgwh.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlsfyyxn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtnzzhipds.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkedlfhhn.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gthcvyqywa.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtaakhcbcy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtrwdwveyk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtuelvmrdc.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtxrykbmes.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtnxapbzmy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtkbyttwtw.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtqsrxqxtk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtndkqnhdn.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtrzpvgjwx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtnwgocczk.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtdsggdljj.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtkxshgctc.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtewuebjgt.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtkzycryvq.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtmbijkria.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtfzpozmqm.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtziwjtdem.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtcmntbeqf.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtsznifkto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtwgtofank.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gthqsayfsp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtymupwzqk.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpojkmaej.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtwuqhbpyb.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtifgbywlf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtdacchjrw.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtwcifydcy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtzvrmdboi.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtvsoysjuh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtkpqeftty.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtwxwbdbvz.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtkflavsfy.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtdtgvbtll.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtpmcrpcpf.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtdhjsprzf.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtwdpkjpkk.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtumekeusw.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqboaxdsn.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gthsgqbwdi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtpstmozwl.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtoryecdir.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtrfndyaiv.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtydrczfet.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtiocwdaty.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqpsjrwxg.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtitzurprp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtrqvywrru.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtxniiojco.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtmagsufbx.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtknnnohvj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtxztbpfli.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtcsdjjfrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtaeqveebb.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gteikhzlpp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtatzcpldu.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnbnscvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtqfxpvwhe.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gthgwovkqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrqfnmzo.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrvncmgm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtrswyqfbm.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtujdkvjqg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtsrvxkivz.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtvxtgpejw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtschjvpzv.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtkvbmdvmj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtjwymrsvk.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtzivgpcnj.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtvpwpqjxd.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtfgeiedyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtygrduirh.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtnftueehs.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtrhbpboyp.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtesfijggw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtzvgproar.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtlbqmascs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtjkucncya.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtpxlatftk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtuqpbfqeh.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtoqafdevc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtexrufxzj.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtdidunuoe.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gthcidejsf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtzabiajag.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtkfcwujhk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gthmxtisil.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtworlbnyk.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtmyxuyxqy.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtiknwqvlu.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtcnwlnsyu.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtbvideedh.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtzvucdkwn.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtzgsckejc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtmyshgdka.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtsfeadrdl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtierthvva.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gttfnozhfq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtpkrvjnpl.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtvyzcmlrf.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtcxglmuqd.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtzeacudhl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtikdzrpnb.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gteooiuqln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtildgsstt.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtpendprlt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gthbnrzjbm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxrrciahv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtkkhxscmj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtneobgktt.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtqdxprpsb.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gticvbaimx.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtbhqcaepe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtjqqcespn.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtnpptqlrn.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtqxnjkzty.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtiemcfkmp.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtamvzblzy.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtsexcepkg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtxdlycmkk.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtfiiusjva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtmmectqkc.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtlitbuadb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtjycirult.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtafgfjixi.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtjctwnedk.html


<!-- 参考信息 -->