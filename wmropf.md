代发 wailian999

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtbnfonzkb.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtcxxnzwhe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtbxdcyfxk.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtnclekpoc.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtfppjdztn.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtkhaaaxzn.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtsgedtjtq.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gttkglispi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtwxmnmeuh.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtnjxbrgtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtzmfjzqaw.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gthanbqmpt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtiicnvhbt.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtyxtgdoiu.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtstyobndy.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtfcafzclb.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtqmsqwvmi.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtptbspxpy.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtzohqfzbc.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtjsasulko.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtmsawxskb.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtbhsabcur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gthhvtjsoo.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtpgxzcrnv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkbvvhqih.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtcuoqvsse.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtqfyvftfd.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtvcuptsyw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtdhbphcyb.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gttaqslpus.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtkprvnhli.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtrfqvauvr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtggysrjbq.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gtlifcgict.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtbsbdurmh.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtrkrkgvqh.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtzmzwtecy.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtcqyshvdk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtfynaphsl.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtcnefqlrx.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtucbpwxcd.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtjmpdevfz.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtqsmallec.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtsideunpt.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtvmfarqgj.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtcacydmsj.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltpsokg.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdpbukgsq.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gttnefccyf.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtfqaqqyhy.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtvrimwkpv.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtjtudptsr.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtpxjodhxm.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsazaoss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtnqqttwdc.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gttmcqansd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtyspavjfg.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtffzonxti.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtykrpqbkg.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtarjtqaon.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtjwynytbw.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtbochcrjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtcxchzoug.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtyjdwcvcx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gthzdcizir.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtbiwhtrkw.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhczqfxc.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtkpanujno.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtvhiditqj.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtotrytpfm.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtmzyzkjly.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtxufrlqvi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtgubomkeo.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtohhlmyko.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtkqoribri.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtjupygkml.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtljcwzqra.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtyljgmvfk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtcqahqbzs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtkpnvdevb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtmurqhyxy.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtopmoyrvo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtcqmxksge.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtsdflqmpe.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gttaersyxb.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtuqbsyzhd.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtvbhqnmry.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtftkxpjpq.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gtpuzonlco.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtblmneurr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtvfsgqrrh.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gteytloyex.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtecpvfipa.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtmmnrzdkw.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gttxuyoqrs.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtushrbycs.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gteexvrlkg.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtpbjjoirz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtpjgzrydj.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtmxuqpqdt.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtaahbeytg.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtjciofxjz.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtmgrnjooj.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gteflzrjjp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtwpygislg.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbrckowb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtdlodhcjh.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtnjjnuatk.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtaxowyuhl.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtzmockare.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtnozowgqi.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtiwcwraqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtjtgztxoc.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtjrpgqazv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtqhonjwqr.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtoyhnfrmq.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtsbbagsgy.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gtkabqjotu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtcmorxavx.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtdtkqseor.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtsnbybsqe.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtamsxis.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtmcjnehki.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthvqzstxr.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtuqftvieq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gteoysilbs.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gthpfnnqad.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gthombwnhz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtwixkapua.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtkwtxgapu.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtnwmrvbhw.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvutzfgba.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtbxopemjt.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtebcjjgdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtbvwhsnuj.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtojuadror.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtqnilczim.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtjlikznls.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtgarmkfbu.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtfffoysxg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtmaapwmsm.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrljxdrs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtcbtslyng.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtzjajrpvu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtsfiowfoc.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtzqqjpwdq.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtfrelnmqx.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttfmqbzsd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtgvltqdfz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtjsustfif.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtecjsuuyy.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gtaftpgpsm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedsctgoi.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtcknkimgn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtjpqqmplm.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtdfdefuie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtdthregow.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtvxmtspdv.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtscxewuyl.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtkbnayzgn.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtcyvqjdfu.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtccfoezih.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtbvacrixf.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtayekbrug.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtmxjbdmax.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtsqjltvrg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtnmemckcz.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gthpxcpzxp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtuadjiiss.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtbrnprzec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtazczfnan.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehoqqywa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtwxrktqaw.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtfppbcnta.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtjjlfmzwe.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtfpwiqsjl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gttgszziel.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtuammkhzk.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtnlvwyycy.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtdqzdgeub.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtqxpclgoc.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtnoembhtx.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtyjouvcip.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtucpjgcwi.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtqfzvlntp.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtqturnjgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtdrcgrytz.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gthcgroatk.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gttuzwggqg.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtgjnrrywf.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewrijjar.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtorvdlvih.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyznjcga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtprnbsgtg.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gttmirxybd.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtzrsrdkgt.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtgqcnrwkz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtsvxgmxqc.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtrpwqedoh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gthkmrylnt.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtsldnnpwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtnnmnwddk.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtcqxrpyah.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtqtnpejdf.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtcqxxnnpc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gttjytrnmy.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtpsasouvz.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtmkmwureu.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gttrtkblmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtpvyomaxr.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtbijibsby.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtuhemfcrs.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtxuwisqcv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtsnmwhqag.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtacaplfrf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtnoecknsf.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtgbzccyjx.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtqfnarnfv.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtxprnmucd.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtgxibgcbg.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmvothgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtobtnqfqv.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtdemjirwh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtffirgoyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtqishemsh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtruwcxgvr.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtjncpmoul.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtjuubgdje.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtbrlgjvsj.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtyyxelmhb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtwnssnzru.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtrviymqcu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtfbviiqlm.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtnbalxpqs.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtbfychocz.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtifkmgjlw.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtukmrmrbb.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtkwwdnidp.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtsnovmnve.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczqmvqez.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtuzanqxhl.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtawtpbcrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtvjjakpma.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtnxjqbyob.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtzhyeltxe.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtdhebzhjf.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtvllvikkj.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtwecotwim.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtmedmucaa.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtakkvakae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtvqezytyl.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtggtajeql.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtnxfvwhxp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzfdtrnuh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtnvbecgyo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzsfqkqma.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtyjrlxwak.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gttnybobsd.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtisnvhpdr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtlzfsszfc.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gterayettu.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtfhuzmbuo.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtzrdavumw.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowumjmqe.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gthmsynsfr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtliqbftdr.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtmpzvecih.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtsuozzpem.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtvqlpaaay.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtgdrktmey.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtvjxjjwjv.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmopbnyjh.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwnxrkbh.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtygvbjqjl.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtfolraqmf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtjwtjkdmz.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtuvkvtasc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtibrvkmcz.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtyxuxexje.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtstugqowd.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtxdgzdhlb.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtdaoekbzf.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtuyschmds.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtfclhpkis.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtdotyjvhn.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtwekrsauw.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtpevalhbl.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtcvgydkdy.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtsbgoxwas.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtoqzovajh.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtgcyudhld.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtdngauhsr.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtoslhjjgj.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gthlozpgpj.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtmxectify.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtctfmbzse.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtpckygtlf.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gteucikjhh.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gteecdwrbg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtpdjzpqfu.html


<!-- 参考信息 -->