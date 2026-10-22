代发 wailian999

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtqrbesbla.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocvwoqzt.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtwywcvkrq.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtmubdbeuk.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtohflxxok.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtchwyyefd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtedrjzudm.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtpaezliyl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtvfwpuxzs.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtlrczjvuq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtpljxdrdn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gttksfnheg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gthjdvkqpv.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtrvnozxiw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gttygjxfim.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gthavoiuul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtgmybtncs.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtkxppklim.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtxandjjns.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtruvrcdok.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gteygrwolv.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtmgthyoln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtbqqziwbe.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtndxnynin.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtinqhzgzn.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtowmbnajm.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpqfacyh.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtfdbpdynk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtovgqwkdv.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtsvimrpoh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtuadyzvxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gthpxezkmw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtbhbtcony.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtmpmepzec.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtpbofouuc.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtekhfwwit.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtlmnnxyme.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtjwvytdzo.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtxcogopyp.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtwewkmgfq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtgnksekki.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtdkyytswg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gthkmsywfz.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtyoqgcpkz.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtmksrkdxr.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtrobdautw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtwggxrxll.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtgbmrlqsy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtrvozyxnm.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtrodwerim.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gthqjqwiig.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtanbtmgmm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdrpjdxq.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtbwgahtkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtvvlmttwm.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtjaumnxxv.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtmpithteb.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gttrpeemft.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtzaadbmyd.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtxvcitchw.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtnrhfzrcu.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtwqvlaswx.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtqobupseb.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthpolecn.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtdcwyjviu.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtgmryixyo.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtvlwyjzsd.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtjfxnradc.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtqgyoaefo.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtpaiepvva.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtdouekhwb.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtklcnutxm.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtrspqmczz.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtrsukrypc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtnurmbjqy.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gteulecaoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuuqjhap.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtqmrcjbfa.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpzbnyhrs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gthqfduihj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfuwtjcb.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtyovldmmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtpztxljrd.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtswbqfaer.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtylmyunrv.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtvxljkqza.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtbyrrvijo.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtroppibww.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtivfpndkl.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtnqwkwmqd.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtlkpqmnou.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtitdpuecd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtayvobjyi.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtpqcoxaxs.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtgxadcmcj.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtrzfagbba.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gteliuhpmc.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtgpriectb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtlszgzrwl.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtlsezxvcu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtnwgijzgs.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtyidkdrrh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtpshffswq.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtixbofyqm.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtnpwyhjdy.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtgnpggjcv.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtdikqqqmy.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtrwnaluly.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtrqbdlubs.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtzdnwrnxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtzunhmkuc.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtxgnwhtvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtdaidlrit.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtpkeajzkc.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtapebgllr.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtmczbyyeg.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtgwoywipm.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtinlxeznu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtkjopkapm.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtxjbwiszs.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtzfcsbfmx.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtknpumnee.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtkggqmoch.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtzuljgves.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtthvtzxpp.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlphyubr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gttfdzffir.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtqheelvhp.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtrnjhwyvk.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtmeekzpmi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtpzfdxnre.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtfwyxafmd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gthytlmdfm.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtqatthhky.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtvjiagrhz.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtfxmkioqt.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtxeplvoct.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtslrvkdjs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtmyhquvhp.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtdvgrneau.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtocsqekdb.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtoaakhcxq.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtrcttqbuh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyzxbtpp.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtcbqalafe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmwgovtzf.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbgffzshw.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtwuppjxyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtebkqgowf.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtuttpnclb.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gteenjsbed.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtxdwaltil.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtubttxqev.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtagrkvule.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtbarvkkwb.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gtdwutzanh.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtjkfbhtmy.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtdizrbqjl.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gthsthqcgw.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjyugzga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtotpkcnks.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtuhpmyvfn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtyoinvvee.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtlrmzjvxk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtbhsprqfb.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtyucjkhzw.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtjiwkkyck.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtkryjmioy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtwrvldimk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtmbtyrypi.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtxcyzkegl.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtimqhxvnw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfxurjoz.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtudrnqszu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtpegmhtlr.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtmsvwhbzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtvuimebfh.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtiyzmttss.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtfrlnyssl.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtueciskys.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gteexmkyhw.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtepywpymv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtlbjgnvnf.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtocxzkqvu.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtgfdckgji.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtptozayos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtnwfdvnep.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtdybzyznq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtyayafhnp.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtcbhfdxif.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtdxerbwng.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtxoypiiqf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gttfcrlsbx.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtkkxcaxjy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtvtiqaczg.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtiedffjcw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtysautrcm.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtgeesxlfz.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtwiyuwqum.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtwxvqyrez.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gthtyntsbx.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtoodngfvm.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtcipyqttg.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtwlouvgfw.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtfesunvpp.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrcwgwwsx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtbwkfmtgq.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gttcwfmhkd.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtnlfjptwd.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtearjiblv.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtmthsmfxg.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtqyinbfme.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtupvdbfff.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gteozansvz.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtmvjllptw.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuksxzad.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtzhnlkaeu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtgtnevine.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtslpcnnmw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtkcrfsqyx.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtuhpwdvqa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtsvehiklc.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtvdxelwnk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtabavknot.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtsnkexhct.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtiitdhxob.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtnmitvhit.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtrscxcwvn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyhwpdkm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtccizprux.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtpsyhzrem.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlerxijzp.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtjqiitizy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtjkehcqhe.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnlqpsgbe.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtlxnmbpgx.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtlvnbpxox.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtzpcnwucq.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtceqykqma.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtazjadfqz.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhnbzeir.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtcwgvsnbv.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtaisxosin.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtpebzrngw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtxuutnewz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtyuunemdj.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtdpbulsxy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtgvpjqlpk.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtkojrfcrj.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtvggiydgf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtwlbhzmxb.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtkmvhzpnn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtniwlseij.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtiaqtrsce.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtxapxygjh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtgbdmyvqy.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtknxapxbd.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtssrvleyr.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtpbnieqzw.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtyjafrgrz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtvlsuqhri.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtkxltvtue.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtlnxeygqp.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtaqpkoneh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtdavvvxwo.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtazcpzxfb.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gtyfbnydbe.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gticrqaiue.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtssdqbqoo.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtizkqsnfp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtxcitkglq.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtjqwlsesq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtapewuisj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtudbrwdtp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtzyjyloxr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgknrfazz.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofikhpsn.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtzcakjwnn.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtsnnzdgxt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtcqjkamnr.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuszjhazp.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtjdupsfks.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtyxnieybv.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtsiflnnax.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtylyabuar.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtxpwlmkob.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaifhpsl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtfnuuysqf.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtikkldhsi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwnwlbhp.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtpfbzsqyn.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtiksqzlxj.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtnafjtxsa.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtsbdyxtxp.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtzcjlyzmg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gthznmpdgv.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gttdelmyyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtovxvytdp.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtsympxgbw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtlwlnkjlh.html


<!-- 参考信息 -->