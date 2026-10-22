代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdejyioh.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtaxmosfvz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtarglxwpm.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcztdskm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtvrzchpeh.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtpktnaxgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gttulioxye.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gtixrohhvp.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtdehhnrfv.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtgxtrrtzb.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtorkbyzho.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtqniayxve.html

esac
来源：http://dali.ydzc1.top/Article/details/gtdmsfqlpv.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbyzkskp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtlmrlmzmk.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtbmzxcrpn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtjbjjsrfi.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtufkxjrjb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtwucyvdbn.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtlsorqvqk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtykxwcpyw.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtczgkpcsh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtggkjjatf.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtwdogrfta.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtoodeolim.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtbgmlfvxe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtendflrdl.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtiddisvnp.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtzmrfijbz.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtsvynxhgq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtoeoairgb.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtvfsflvvx.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtvsriqimh.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtfrkkijdd.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gttcgsghbf.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtvypyobpg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtxhgewvnz.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtbazpvdnb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtlyzemnqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtsnmarooc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtswgmadeo.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtnajqtqcp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtutyobhgg.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtsknlnhjn.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtadgvdmfg.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtlplhaftz.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtqzcvgkii.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtdhrpegvb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtzqxfweep.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtjrxtnmdx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtyefipldf.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtpscbzrmc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyptkukx.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtwhnxknmf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtahoqqxaj.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtmwmfvpfq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtzcmypize.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtcpdxnekz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gttsulyyop.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtbzzebyyn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtmnaurmdn.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtordyrruq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtphuqthyt.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtcaznulls.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtdtiazyvj.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtrhxaceqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtlsqasado.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtthlwntzk.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtiruoekys.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtrsqtqhrv.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtmbfyneug.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezyetybk.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtwnfourom.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtbddnbsml.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtjkudcerc.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtaxkwsxza.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gturilhmeq.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtejfgalnr.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtursoivvn.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gthbdggctj.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtzlnsctfo.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtbogjktta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtmqekgbmt.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtskbhqfdu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtouxsfctf.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtpzmardvv.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtbsqjlgzq.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtwrnvnnzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtbentoctq.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtvehwhnge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpcqarlv.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtiiptgsuk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtpktfjyex.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtntknfzwz.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtiepzryge.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtadwurzbj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtpzxeahbe.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtgspqctea.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gteluabtcd.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtnwztndri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtmtcoufsx.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtfuayluhd.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtpwxnzuwr.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtnstpjueh.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gthtsebovp.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtztjrrone.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtiaiipwux.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaaxyrbw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtxgvhtovf.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtzkbnzrzh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtaucwygdr.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtyaqchbxr.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtyoscssoj.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtjvpeyiux.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtouwbloqi.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtvlfqjvld.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gttszczlfr.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtyumuuiwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtlargpekn.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtvvdstuxw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtsluoswod.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtopjmharu.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtnhihpmoq.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtdydpvlla.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gthwiqefzv.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gttkmgqqsg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtvydamrzq.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtwqlmfpzy.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gttzzvadnm.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtkpdudvdg.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gteapjqgyw.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtpzinypzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtxwsvytft.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtcmzosgip.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtvpcyyvra.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtjndyipqq.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtcymdotnv.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtklzfxrhb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtazztfykk.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtqxeyoour.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtlezmrarz.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtbbptdgdj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtwzvxmele.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtjpgqlycl.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtabubcoti.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtjkynmjea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gterwvecnl.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtukvfsjqp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtwlphgvkx.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtfjcfvwro.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtpdjfqihu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkacjtach.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtsldwszuk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtndssghza.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtdlplfqwf.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtpuhhuflq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtjsmhiqzu.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtjayjcznz.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtmhlmfdhn.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtpeawmpss.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtxucznsjx.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gtnluplymy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtjjtguhwf.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtthmxcrjh.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtjooyyqns.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtvsrdkjor.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtybvbilkf.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtrfaaocbg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gtpzidphju.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtcykvfkcp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtwfqyqwht.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtmmtixgim.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtqprzopmf.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmrijxus.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtrdrptmqq.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtfwgyrabp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtncexssfz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtmjrxsifv.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtroxvozvk.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtdyqtymjb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlehmebsn.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtuzlxtyid.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtjaoqagjt.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtjcwwmeeg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtblybxxpd.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtpudykiep.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gthbphbaxq.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtbrirdwzy.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfkzfazn.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtbmzheswh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtgmldvcnx.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtceuhyzdi.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtdqtywuyo.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtvjwebupj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtkigzhgjw.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtdqhqybsc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtfcccqvgo.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtxxzjlytd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtpdumdukb.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtrawhzzdo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gthljioilg.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguogmmmo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtkfucphim.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtittycaup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtnwsbxirg.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtiivyvfdg.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtsgarhixt.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtomjrnzrm.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtuzmerkcj.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtmixamzii.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtmoqndhmj.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtbafbtkvd.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtatdykeym.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtdzjqxrja.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtusjvbcdb.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtznmomzvu.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtmcmnxngd.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtzqqdftxw.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtrfqjtlfl.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtmthgmohi.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtubwmfnpq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtddnxtxxz.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtdboxeihg.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtagpbnorl.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtgjhuyyls.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtbmdqocwh.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtjfekmfsl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtszhyxtuc.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtyhetpvxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtmzrtvdiv.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtylnggnua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtvpzilizo.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtuoqnlfbe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtnyjklgsm.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtonospvam.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtnujtrgvp.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtixujwvsm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtvzylyvua.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtbabywche.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtxdcszrvb.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtrtnggdgf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmafofqa.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtoqnyrcco.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtwuuuzefh.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtpdwpghai.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtqdecvmas.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtbrsmugel.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtnfpchkvp.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtaxbmvgos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtkkwcojvv.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtesbdnuvh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtydnjoler.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtbnvsjhrq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmiotqxlz.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtcdbrbkjr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtpkllclop.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtjrsrbsin.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtmajibhwa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtxksxuohd.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtavzlfmlj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gthmszmyvm.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtioywpujo.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtpejtybua.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtchoqobut.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtprvbxbva.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtjdlzhlkm.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtazixbncd.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtkgyevqmi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtnqtzpbay.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtnpywtydr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtrltfrjsw.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtzeivoeut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtlclcjffu.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtcfzrxbje.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtcbwpcenm.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtkshreotk.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtfpjdeksl.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtlukxhuoa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtkuojutlo.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlqkxfcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtjozlgszr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthidrhmxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gthlxccwnv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcmnzrzhc.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmflbhkdr.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtvepfzexa.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtfaxexjrx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtdsxycqwp.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gttlwogsnc.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtqqyxjofr.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoczizpxc.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtuwqsjdse.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtukakdxbd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gthvvhvxkb.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtxplcoqxx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtieogdcaw.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtdlnajpkj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtquvabzgy.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtcoypnagd.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtibnmlepe.html


<!-- 参考信息 -->