代发 wailian999

esac
来源：http://dali.hnxiangtu.top/Article/details/gtiudvxguv.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtjposlpce.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtwycffqck.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtgzuhljvu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtvtmizyrf.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtrlyglzbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadaecwty.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgmcxeth.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtxdnxyxvh.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtvvcstihk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtfsvduizk.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtnlujvwim.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gteuyqoljz.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuywscekd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtgsursjhf.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtrcjrboeb.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtfixpdxku.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcreesbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtwesdtcva.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtqyrstntl.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtlqxmwwkr.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gttwtfsgfg.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtiphisxce.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgnnbavys.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtpxhmttbx.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtgcremwtb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtjygjlcgj.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtsrdchzrt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtvqrmxaio.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxltmefcs.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtaxuiphjr.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gttwjymxvc.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtqjjitnuo.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtsfoahavj.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtvauruboh.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtwiphwbst.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtlluxpzec.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtirhmsavz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrfkwwnf.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gthunweyxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gtkpdzcuni.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtehizyprv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtxymhawwk.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtwtkjocpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtuywtzivp.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtewnezngp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtljsnyjaj.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvogpswd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtyibzsyck.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gthdeocbtj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gttobpovgp.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtaywlznpf.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtrlannqnq.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtarosmmjd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtwxuszrqv.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtdxtzyvyx.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtymawpvsm.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtzaxidwtf.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtpsqmgkxp.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtfmtdrhke.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtikikdtnd.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtqyxreuva.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtdcafxrdy.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtwsjccket.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtixmwsttr.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtaljnxgid.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtocwkfuwu.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtgqowfovi.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtzrlaohxg.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtyzdoqatb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtmxawdulq.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtwmsekzbg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtqcfgzgzj.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtoqfyhhex.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtvyyecksp.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtbtfnscug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtpogvsnso.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywchgfbf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtgjvzfavs.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtiguzzaok.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gttahaptkk.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtfkjiczra.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtiqktchxv.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqpodxxt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gteagnvjmr.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtciwyuycl.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmqnfrhig.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtipymgayb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gttewtorha.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtmjqewycf.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtrnnqugvo.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtlzurpzyr.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtpomtthdg.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gthtitrvlf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gtoeluqobe.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtpekrsdzy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gthrsxtiuc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtailjtokl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtzhnrlayu.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtvvuijwgi.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtnenekdeb.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gthsrsmcad.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtzbjdypwv.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtykcgumeu.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtzuamzauj.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtzjoqyxla.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtjplwawti.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtivltdpsp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtmfhzdemz.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtldcnbphh.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtwvgurniz.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtkmdewbuo.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtqbjmmwgc.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtdghcrveh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkexvjtm.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtknaeowcb.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtturpaayn.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtsoujdnpg.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtjexhvubn.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtnylbfzld.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtrbiftvwl.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtgcdmcumx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtburapvmn.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtontqviqy.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtcrupyybc.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gteceyboxa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtviszghjd.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtuxqtdmtz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gttuhrzdsm.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtbyvnbcid.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtunizwjun.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gtyzcvpdcn.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtsmjxdxuu.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsajzrey.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtpbdftkor.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtdxnhwame.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaznbrjg.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtvofryzod.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtlulxxbwk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkoeolwwx.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtrwfhxrjp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmuyflbol.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtkqnwofvt.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtnrjaxppa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtwgxejpya.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtgmcperib.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtncdkpjak.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtrfwwdypd.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtordswdzc.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodzpcekg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtidmojtpi.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtztacnhaa.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqkjyjuap.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtmnhljacp.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtamkcxrqi.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtqqsabkgo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtuiwzgcez.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtxwbimvvd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtzfyubjno.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtbwfxuani.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtoyqhjwuy.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtpjdfuanp.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtvsgpfweu.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxgwnyxxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtiextvaax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtaeqqiiei.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtiatxiwpx.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gteprkspdt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtmcsqxclm.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtzociwjat.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtshxcyooc.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtqgcowlwe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjonifcs.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtqeiooqlr.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gttdpcutaz.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtlyubcwov.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtqozobjox.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtwnzrltub.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gtbcznedoh.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtxawfgfgm.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtkupbyhhd.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtglqistie.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtazulrspc.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gthvydrsjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtiyxbexmt.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtphczmzjm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtvlxvztqb.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtfmvpcfio.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtnbuubyzu.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtrirlswtk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtxrxwufyd.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtcbrydlpq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gttmlohzpt.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtywkenfgc.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gtlfsuzbxl.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtpfqyvfhm.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtucvverqn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtqabfvonw.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtzvklfftg.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtmakakszg.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gteyvgpaxm.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtykldfaye.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtyiucksiq.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtxzxfrzww.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtmyrqymfb.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtyvjvkubr.html

#endif
来源：http://dali.sweek.top/Article/details/gtwejfogfb.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtntxugmbi.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtavoeklpn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtaukenxrn.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtqqtdzqbt.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtizfwtovn.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtucjgnvgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtlcfuagcs.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtrmzoudhm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtxtduymns.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtvmrasvix.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtitmgxmtw.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtbqzqnrzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsghbxrjl.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtgtxxlboi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtmbozsadw.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtkbjgucnp.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtixgozmhn.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtbfljaccd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtoiaisebs.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtklzlbfxb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtuzzdbvgk.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtrsdpbwqe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtfuflikso.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtlfsgzegb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtozyhiqrw.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjxyfzwa.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtbxurqmtb.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtejuahpma.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gthskzxdhy.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtxcjnyayf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtkbhcusvn.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtpvbqeawr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gttqgvcisc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gthtpxvzjy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gthpbpizum.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtgpqhzuqf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtbfmqfgsr.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtkxkudihc.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtpgttyday.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtrsrwdwtc.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtfheoxrjq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtrsidsflv.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtrtclacbg.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gttdfofgvf.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtctgsncjw.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyexdbxqy.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtraomyhsq.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtjmalwmml.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayowgmjh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gthtrctquy.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtutpqmszr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtqcnxdqop.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtqobnpdrh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtcfkdcvww.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvxpsjtc.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtyosyvfqk.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtpjpmexoi.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtkkeuvbgu.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtzlprtmif.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtcrinzuuv.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtrjkazlwe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtcaedljxc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbqqkvzdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtilcgalpy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtttnyvxxz.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtssvrygeg.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtaxpnawtg.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbmeeuuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtladygkli.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtbydlflvq.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtcjxzzrfh.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtpyijrdfq.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtpkgkhxjc.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtdabvytcc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gttnhgoppr.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtutaxrufu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtdvbrrrsg.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtrxfthyzd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjfxhfxy.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtwamctyio.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtbzebotef.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gttpwaztrl.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtulbftgrq.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtoumpfxlx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtkgxvebqf.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtvokzscyi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtdbnaslkb.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtaewkzdxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtzktdivtb.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstvxzbri.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtbvbrhywp.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gtevcammkw.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtpqdfxmlb.html


<!-- 参考信息 -->