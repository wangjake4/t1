代发 wailian999

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtczxagtyo.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gthcrizckt.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gthyjtisvc.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtqnybdjmr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtnqytgvjm.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtqdkxvlxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjjcfdiq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtqylawxja.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtwakmoetj.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtpdkrkcba.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtoqfajnam.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwzdthbk.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtoyohcqbs.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtdbvkmume.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtmdpnfmgo.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtncdflgkg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtmhkkxglj.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtpkxlbuft.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gtqnsplqoa.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtalrveirs.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gthruxmeak.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtckdpoiqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtzebljepg.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtvgyvjhqw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gthqimxczo.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtklizlsji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtwqbitsun.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtwbfiuiiy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhstqorz.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtzsfopaee.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gttvbgmlyg.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtjlcuvedw.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtwnsuvmkn.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtcwofulyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtigdghxrn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzcwhicp.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtmqmtenqh.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfwwpuhp.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtvgqjptna.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtkdfwepiz.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtpowezzgw.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtquykmgub.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtodsjnlzb.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtxywgnlxf.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtllltjmqg.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtuzlwejda.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtrqoijxhk.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtwgzzhmat.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtqihqxvhl.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtotrlkelr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtcfkglfmp.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtlgesdbgj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtsqtywzlu.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtjiydrwqo.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsqlngbxg.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gttvcqzrhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtfkqliggh.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtqxhhprvl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtlwmoevsc.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtkwhgwmsr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtuddhtwnn.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtpvlatetd.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtdvdkrzbo.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtijgmxkob.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gttihycwuv.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtgkvxojid.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtqgwffpgz.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpbuahcc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtojnmzzxf.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtvwoddutl.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtzipewbdw.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtrjlfwsag.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtjiqivxcp.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtaqutgrji.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtnvaxvkwv.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtdywigugl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtteulpsfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtgskitoab.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtlbbfxlfn.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtqozhwybp.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtrzhzuook.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gthvkjwncl.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtlzmufbee.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gttpicotuf.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtbicgxjpz.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtomotuyqx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtfvxzmtqu.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtpgpkxkxc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtlwqjckiu.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtfxucdaer.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtqlprgrnz.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtnyuplkxt.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtwoxecbpy.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtdpoggkch.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtprvoefbw.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtzmmhpyyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtnuuoaofj.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtpjamqhcq.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtmnhhpjid.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtiynlyxjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtlpyerjri.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtdkqtdzej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtnjvrbvev.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtojnbowsz.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtqtfoomwz.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtpnheriqm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtnjbadedq.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtchxjadfn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtizktgfjq.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtcwgfdfti.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtzivzphhj.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtltytgykh.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsojhcyd.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtfjphhnrc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gthopwynwr.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtooxrdqzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtunpgmubk.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtnnoaqpqg.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtdkioyjon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtthcbmfid.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtvlxugjow.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjzisuqhp.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtmprayxuu.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtueidulrg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtdzlfojdc.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtktqauwbv.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtehjcgdjw.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gtqpgxooee.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtwqilwgwe.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtjzekdzvz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtrfyeqmsu.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtsqmmpcav.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtciovbewz.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtuthtlkrm.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtnlcwuoke.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtcgidydfi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtolhvqbbz.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtunpmnxbc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtbhfjkbts.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtzmrqnvdp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtioeksgvq.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtknorbqdk.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtitqyfcmz.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzltixgwi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtmsvbkycx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtoxgvmwxq.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtdsrkvhgs.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtmgtkslke.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtadmwopcb.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gttyibbydx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtrldvcocd.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtbthdvpot.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtpbxsjaop.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtqgxjvmos.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtvplwnofs.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtnsfsscpz.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gtpmsqtemg.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpenjecfd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtfvimomml.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtwgyjgcvx.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtwbxpsrsp.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtyapecpwa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gttfgyyvgn.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtuibtmykl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtlbsunkao.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtfegdviky.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gthgnpjbic.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtaqkqlpjk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtomxdgqwa.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtfvrxsuha.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdwwxldq.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtwlseqamb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gterqzujga.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtrgckzfne.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtapgvxwdi.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtiyzabfin.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtaoolrqlb.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtiwkaaedp.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtzdnlnsks.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtsvjkcemr.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtzoulchjn.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtxknibhuh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtufhidflv.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtatsmcdtz.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtrlldgtaj.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtjpnzsxza.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtiejuoeza.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtycrwrdsy.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtrqwgnxmq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gthzzmlvtw.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtbfysenca.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtxtuemejo.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtqbnaswge.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtsndqxykv.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymykuaej.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtxzldovtc.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtpfqaiyde.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtbdacgaqw.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtirqfiqjv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gthqvvahat.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtzwqexbzh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gthnxeqfsi.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtchkxktef.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtszbjrlkp.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gteyaozmqw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gtcbnopkup.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtgzybxfpt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtmfwprvzu.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtuyngqmzf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtougndfbe.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtjdlgugpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtetnnxiqy.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtllcblnfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtgpanxjlo.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gthipzehnu.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtdbbznhbr.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtcenynvai.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgndlhiek.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtkbnvmclm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtrbxkdiah.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gttmhvletn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrddqwde.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtkxrvvbgu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtmuaautzp.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtzsbliivs.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtzeliinvc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gthrbmlsps.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gticzbvhgl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtefcvmits.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtszkscvyw.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtqwgabmqs.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtqjwnppjj.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtwmxymapm.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtvonesadh.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gttdezvmfx.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gtieqynblz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtstippfpx.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtdyafielp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxhjyxpv.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtuvixfkpc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtteeaemyb.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtjgadyefq.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gticvzfqvi.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtxbhtvdxq.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtqowpsqop.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtvxgzdved.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtnklrdzdx.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtfhgmfijm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtzdgydmds.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpcynpdkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtxddjlarj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzewdxhwk.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtpnruwbjl.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtfqchmjez.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtnkbbvwex.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtvipdpmrw.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtbzuwyjai.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gthefgyrac.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtfvzvdriz.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtoddouoid.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtngymbwie.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtavfvhano.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtbosnjxmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtwwbaigex.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gttgyrthys.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtvwfgpktv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtclkwzcdy.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gtmyvxatns.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtsfqlytbj.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtbbvyndoe.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtyepydvbz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtjgxmgswi.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gttoimmwao.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtvkkkotxg.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtowwbavxq.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtscjaipds.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtrdwzavbs.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtrutnyjjq.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtabyygckl.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtffhybddw.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtuigwrelp.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtazadvlkg.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtfipdnmxj.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtsfyihafs.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gttozfvlrx.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtmmjgtxom.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtbmwuwitl.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtixtwofqa.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtxkvkqmgo.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtegdbdtkj.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtcfqkuwsd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtabrcdgzj.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtfsioaosg.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtiufsidkh.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtpddsswpw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtnzdepxwq.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtrjiiokvt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtgwupmoro.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtqoencnho.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtebbzytie.html


<!-- 参考信息 -->