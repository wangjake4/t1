代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkphkrcja.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gtixxyaqtn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnnqprmxl.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gthfiliqks.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtizdnxxfn.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtebvfmbxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtztxnscty.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gthnvzhoic.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtawoypskv.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtchlsamjq.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtlewkhqlk.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtjyvsapyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtgyodlffb.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtfjuqkwej.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtsfjkkhrg.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtsxskkufx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtadttkszj.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtshromswp.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtsssmntyf.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtfhaidumu.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtjkfdzdeo.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtkxocfrhw.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtwpgykbxf.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtoummdvmg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtzatgqjht.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gttibplnii.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtutvxsgij.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtdzaaxass.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtcmtrqtpo.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gttlqkmfmj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtkgoejmlb.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtiqvunywm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gtglnpxnlt.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtlofcmxsk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtupvgyhgy.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtykosaosu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtocbbjqfm.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtjiphpbef.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtwbcailyy.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhcqmiyf.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtnmqrqmeq.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpmhpgq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtwemorpqx.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtpcoxlllg.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtnipmcqjh.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gthenlmiyk.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gttdefzlyn.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtdhsxxdgk.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtjzosdont.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtpypoyesf.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtoktkoqzv.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdazbmmrd.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtdvxuguqc.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gtgwggthxw.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtajgyffmg.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtvqemednw.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtmajioihg.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtgfiqyhoh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtlqkvfsip.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtyvgikohy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtfjrqxtoi.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtxmcgaswb.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtyolmeybf.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtbpmsuqoe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtoueybctn.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtumxrxdar.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtfmejvthx.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtcnjnivhl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtbezysxwr.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtmpotczvc.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtrzmavbsl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtkelgclmx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtfulziyex.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtvijzlaqe.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtvkijpqmm.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtffjmmrdo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtwdtlgamt.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtcsaademl.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtsuhvnwfy.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtlgaykaou.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfoakowh.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxrocoxp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gttsvgqlcl.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtavzcvmrl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtcbwsttmv.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtuzkdcdne.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gtwrkgklsr.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtqygyvpdp.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtaphetlnv.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtqqyjpljm.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtbphpbrte.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtitrwsyak.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtypymkfpn.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtdotqoafq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtiiyjwfei.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoqlwuee.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtgiijegyu.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtsmthgkrb.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmhigqkg.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtqifkvpng.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtfwtjhabh.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gtwrdatmhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtnohwtpgs.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtfbdeaelw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtuhjuyoph.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtmnyqnngq.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtzgaoypqk.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtqbfwmirs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtmdlqwtlv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtwrddwydq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtmjnqbhrr.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtcfckypvg.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtnihumaiq.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtewlrqtgv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtbpnoxlkk.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtchfynrto.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gttshtftwu.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtoyogckav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtbbrtfasf.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtmumkzynf.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovugzhdk.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtyrgopavg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtcpdahmiw.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtbbizmzal.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsmzatqof.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtdbnbptnn.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtpvxmqsnu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpmhmmegx.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtkkylvbxl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfxqfpsrs.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtksclxzfl.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtvgulpbcw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gttjnakmnp.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtuzhgiqhf.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtirngvdqj.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtveqcytyj.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtweykbztg.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtmspgcuwf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtyiogmrce.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtgogslpsl.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtxzuscwbq.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtfdriinin.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtmicrfkah.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtbuxzwbuw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gttynsiyws.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtjmwskump.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtcmldzxiv.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtucygeqmq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtykfgzift.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtqhjrmeip.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtbtwehnpj.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtuuunoysu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtowmmmitz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtgvgjisao.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtjcdtewni.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtaqwmrpfw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtaxmfhbrx.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtkjbtisrv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtjkzjfrnb.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtipdrcrno.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtbpzbmiyb.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtpkwdtaqq.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtscartwra.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtznmrocvh.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtckjwwlmx.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcfyecat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtiitxfprd.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtchfmxtnd.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtzvvcrgjq.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtgftbnjiv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtryndeczy.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtkoqnouvu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyzbrgvg.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtxbjwankm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtykzvlqmg.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtbwgdzkmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtcqjmjtoo.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtvpjgqtev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtxgruyaxk.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtlnooadjg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtqpepklkt.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtnyxxbind.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtbxwihuqv.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtlzemkgqx.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtxkkcdaxz.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtqlolhxit.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtbitruwgv.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtqmovrdtt.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtptxozqto.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gteghtyash.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtksliwbby.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtvrmbixrc.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gthujobejs.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtwmhmjznq.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtjdyugrlc.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtbygyahot.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtirkwpxrs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtqedjlleg.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtbzagneih.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtfwasioee.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtusulvfda.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtfsvubwjs.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtmuxjsmvh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtftknotbf.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtzkohajmb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoepvxpkm.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtfcxcrnxd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtmeohqrpr.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtrsgjkdoe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtdniuizql.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbmpevno.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtwoqmpmml.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtzvbqghyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtngqgbafl.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtdiyelmav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtcmohlmph.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtfyvypnxq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtzwdnghtf.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtufxqvcpv.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtgbejrxpz.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtkszxyvuy.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtqsqaeack.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtalqxepuq.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzgjktyww.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwzhvnr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtbskoeqrt.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtbzormbhc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtoghnajyb.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtpfjcomys.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtliffmpgw.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtqglgwwwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrswqolj.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtcsbpvsrg.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufjhhenh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtzinpveiu.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtxaiopkhf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtffjphwyn.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtmkbvrnfa.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtqxzwydom.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtwtnjynor.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnddinsle.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gtncoczdpo.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtitesdmwt.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtvbqfvnnq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtllpmxdzs.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtxpkcntzm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gthgpuonyu.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtvukckszc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtiydpqmvv.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtzeiwjkcx.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtxorskyri.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gteekunamr.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtvbtiphpi.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtcmwirmar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtlhzigvjd.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gthqlqpqlk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtnoildopj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtywmnkmkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtspfkmaog.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuveksdiq.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgchnmcji.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtkolsdtsm.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtmuwtplnh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtbrhnssle.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtybyfakmm.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtyrrkdoaj.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtmkkqsbdp.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gttkxyhjds.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtsnhrpsve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtfcmktibk.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtdtcbfqgz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwztptmb.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtavnvjade.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtswkfkapu.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gtpqyailtl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtgsvatart.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gteseghugo.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtnwiegile.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtfptdlauj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtxhsgwwmt.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtjhsbzrwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtqbaomcyq.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtbpghghrd.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtkbfuygtx.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtdeolfqej.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtszkbqgwg.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtzfclxaqh.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhcoazxq.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtweeedwjz.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtknplysqa.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gtprfglmqx.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtqchzqpuj.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gteydsakqn.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtfsisykod.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtxecqthus.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtbdifrevf.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gthylrxhlz.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtyzefpvwy.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtgsecougm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtrcfaixna.html


<!-- 参考信息 -->