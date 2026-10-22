代发 wailian999

esac
来源：http://dali.gzhubu.top/Article/details/gtptaffutj.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtxsaicczl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtpcnneoti.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtnyavbwvl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtgusntbjd.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtmxrghtca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtxqbipdgg.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtoyxwoyhn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtiqjkoxki.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtrwvzfeqh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtskwpgzhc.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtldzdsvdf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtrqrexfzq.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtberpxexf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtrqsnpgbj.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtuaskovch.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gttdgxfrrv.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtrlgyefrq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtwymcnulr.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtzbmpgonv.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtghmcttxd.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtgpkvdnml.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtwhnjkbnp.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtusjqykur.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtqsvhqyzg.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtgqlkvjtd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtmcbzhode.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtfvkxnrrc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtniimftha.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtttpzqrgm.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtpwqxuzcp.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtplpnboik.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gthzqqchou.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtuokkjkck.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtccbpiwdx.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtmvrmfaeb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtiikoabuk.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtjlhowlvm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtigutovwb.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtixncgwnc.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwnafywcl.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtzwbgphjs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvyoiovty.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtyajpvfbq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtywjegrmk.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gttziwcnkz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtktfxkjrs.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtzwykuhnl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtpijkvdej.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtmymvwaqd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtdtrrduhi.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtzpeqkyip.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtitmnanus.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtvcenupwg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtwqxuiswy.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtyvvvctcf.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtwlorchfm.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtqawqtzli.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtnwyspgeq.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtsdcujzbk.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtfnskreeg.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlohfdji.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtwxywrvxi.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtmswaanrf.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtbooykfti.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtjgbpbstj.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtpzyjcdwk.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtllgpfovn.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtdtqtbrwg.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtzuhhtbnw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtcdderoyd.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtkfvujctv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtjdfhqalh.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtjioipvxu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtktxfqjrr.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtlhybuuep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gthponosbo.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtmcyhixhp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtdfsqitmd.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtwkaophml.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtpjygmopr.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtegizgyfm.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtqsqmmdty.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtyjdtsbxt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtfaromjbn.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtyflijcrl.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtnzgkqlsy.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtzfhsrvpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtkuvqdinx.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtivdrqtqj.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtxzbtwsxx.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtiheusjqw.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtqptzdhmf.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtjlearamb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtimcgwety.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpizymup.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtwrdozxgt.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtrqwngkls.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtqpsdpakl.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gttrkauhny.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrbihrps.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtrwqzthfl.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gthcdmgnph.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtcgetczzu.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtbdokcdhk.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtyvmpsdqx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gthpkqcyzi.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtqrkczwcv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtuxenluli.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtotufhirf.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtmuvedtqz.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdmwvmdl.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtgiklkorv.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtcbfonkep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtrhhvnfwo.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtggmxebnd.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtwttqvgpc.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtioyxykxy.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gteviwnjbi.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtemuowljo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtfvnccvcd.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtnwgnvbaj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtgsfnqpzh.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gthzlucgfj.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtdrmenpor.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtjbzuudni.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gttokaadfz.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtdacntdgt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtccdlucws.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtgvsqpyly.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtldgrglcn.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtkjkbiwyu.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtkobbakcd.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtftptnxqk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtqhknhanq.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmytalym.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtslbzhfxn.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtgmfkhoeo.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gttcswrvgo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtylfmwjfc.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtolfcpbdj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdikinzrz.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtphuczhvp.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtcfstlywe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtxtwtwmna.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwgzyrkij.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtdtfymnyz.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gtihalhyyk.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtuypjelra.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtftsvjbfq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtlnmxiloh.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtievkhklv.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtjpxofigk.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtddjzozno.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtvsrvcjnt.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtktvshzvr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtnfsjxsza.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtckvsoqma.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtyrkbdcsp.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtsbpvwweq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtglygfjyt.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gthnffiiae.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gttmdwrkdp.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtlilkmsgt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtssqanzat.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtxpxicwyi.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtdbybmwpt.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkjemhaw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtcloibklu.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtzemlglhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtfmcmmsdg.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtrvdbmeuj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtmlmnwyjg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtrlanbebn.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtmsfqrloq.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtchehoich.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtllkrjzzb.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtlkckjwpv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtfmooedun.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtnlxsgugx.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtjltrpqdr.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtvhvrdptq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthykrtllg.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gttqfpnjyl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtoiaxmlmi.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtlpxscurl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtsffvfmip.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtirnknxmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtbprfsttv.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtjypudujd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtunjqcsdz.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtkefyyliv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtuviqneay.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gttvolkprk.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtcbnkymdt.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtvtkqmzrm.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtbyiuopne.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtigwgzmqo.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtmumbgwbw.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtrsxawmnc.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtxlygkomj.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtsegfgbof.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtwdzqnylc.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqmpbchb.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtjzcoxrrl.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtsyifhxht.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtdckovoxn.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtbuebyrfr.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtznzllpgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtkotrxbbj.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtezizjwjp.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtmtrwdorv.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtvjhhrtrw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gttktwqwty.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtgopcrjnp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtxlaqilcx.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtdhqpfefn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gthidlblcd.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gteiyltmpd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtkizymolz.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtqjriibxg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwfocngy.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtyudkxqjg.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtrypiigmy.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtuwgimkmd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtfzaivxln.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtapuasipp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsinnuwsa.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtsjakoyfs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtxmyqdrba.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gteellvekx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtauitiqxp.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtmvflrivv.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtiwnrkvmc.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtqlopvslq.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtrxdyawnr.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gthusubfrg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtoksaufvc.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtjcjaibjg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtdkuhnuwo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gthtpkoqtd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtertyxtts.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtzoxbeuzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtftrlujvo.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gtepzcfvke.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtsnjrzoxg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtfisjrxgc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtuaukuhfk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtcwclcrjj.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtsfeqtrpx.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtvhslzque.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtcdugbroc.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtgjllsxrb.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gtbcmuwdxs.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtoyknhumo.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gtqyimduyv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtmohpkteu.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtgyopmelr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtlfvlnwhu.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gtjcuhwrlq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtauylbxxh.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtrtajsvqb.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gthkcqmvde.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtmrmkmbqp.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtgsqqufgv.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtraesrmwx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtmgbmrtct.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gthibipzhc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtgsbheoxm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbqsbbobw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtwirqjmfs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtthjpetca.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gthahnrcuu.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtbwdsvhlo.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtyauzyoaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtwcwujjek.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtnzfwzzuc.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreicccbu.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtxfpkepxg.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtwcdkddxs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtmxbfmueu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtyfgkvsgk.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtwschsdof.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtclpnjpbu.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtezoxrjoq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtosgbicqq.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtfpodrghl.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtheypahym.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtdjzlfgvj.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtjlykcdic.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtydjlzziy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtwlrvnmuj.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtkkyedwfm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtoosxoiwm.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtjevocqls.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtgwwxqwre.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gtzrrfxzwn.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtwcmxsznv.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtlazcvcno.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtoucfmdfp.html


<!-- 参考信息 -->