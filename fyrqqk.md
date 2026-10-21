代发 wailian999

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtksybadrm.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtcuzmeuur.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxmidpft.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtujvgxfbz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtqnstveuf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtmpftftrk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtoxosguoy.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gthddacmcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtlsbeajwq.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gttgrznjwr.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtdnlxomgk.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtpfqsizrz.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtqefsihuw.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtvypetani.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtiyrvpnvv.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtllpauabq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtvitgkect.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtexvhpuja.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtyrijccvt.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtgaabcmjr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtektnpsyx.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtqmdkypmw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gttcavpxyu.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtcgvvfben.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtvgogbtvh.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtuuwfrdbr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtfkkwpdii.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtcebofvcl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyrohtur.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gthndeuzkf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtwctxbewb.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtkaywvfob.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtedytctji.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtlxnkhqzs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtuerwawyy.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gthlqprhiz.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gthneholgc.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtexxjpgnn.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtpukjnahs.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtzunbotay.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsgfnhhd.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtohydxyim.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtvwjfirhf.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtxfexbzsk.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtuncsoslx.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtiibkvpdo.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjrqkhfz.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtaxfqbnpx.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtpgatdnsn.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtwjtdbbtj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtuzyfpjme.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gthmjcyaoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtzurtjirf.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtxddwexda.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtjuwdssui.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphnmyngs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtujculgeo.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtniatmiku.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtwbqswpoj.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtftkjdlbg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtiujatbah.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtbjlqojty.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtnvnpkzhb.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtiwrnfpek.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtjvukkueh.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gteyxwiuli.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtmdtcntvy.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gtzxjlfaqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtioubtved.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtjmqkecwa.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtaendilqf.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtpolyfvbp.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchjuoaiz.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtfvwpkfof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtugqhvaph.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtbgdaqvsm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtkpkvrppd.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtytxunfcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtfqvhwmho.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtlwgfcxtm.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtrdtymhju.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtneugxxwg.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtqutlsaqn.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtjrxgwqne.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtkrhiepzw.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtacardinf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtqmaznosk.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtnuhftnok.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtgvqpmmwy.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtyxgyyvwb.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtbrkwcmvo.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtceuinqho.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gttpvrluda.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gttbwrhtvh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtdvxyulio.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtojizhzwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtoeqjjbkk.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtjpufbvbc.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtsemzwrvy.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtrltxhxtq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtowmzrlri.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtbjffkxne.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtkzvajfaa.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gthqjngifp.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtpydunbew.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gttmcijgqz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gthoqnsomg.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtcsjthzjr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtwjrhvqyj.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtduyarfch.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtazjnzhxy.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtngyvmclk.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtqhoxtoro.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtucqpytqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtzkxjsxhv.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtxenhvbos.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtqwarzwvd.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtzewodrej.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtiosjdbki.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaosfhkop.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtjprsbsbu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcldvxqzc.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtzyvqfxpa.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkxyxvoo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gterbchoon.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtodtyikjx.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtpidomobf.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtgddvrtfv.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtjalebjes.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtecgvztrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtfnlukcvk.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtrzzzoczm.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtzmbxaaee.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gttexjrjkr.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtfotdrltw.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtygdgtfbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtpxqorwnl.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtxsuojkxt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gtuierddpa.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtaqixzqxd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gthsylfegs.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtcvsnvmdw.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtxfomgjry.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtljsasxlh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtmbfwgqjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtocbzdehz.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtkyezbtic.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtgjbyadlk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtlfrcyibv.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtuatbjjsc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtnimovjtq.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtdyxjvizt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtluzghsqa.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtrfgjgswi.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtzsolsiao.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtgmypfhwk.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtmlrooziu.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcayceuvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtpxxlsrbo.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtuafhufdh.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtgyakfgrp.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtrsoqccjr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtacpkgnok.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtfnobcybq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtygsieawg.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtkpvbojuv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtsmxhmctb.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtmamucxpl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtiwjxsgbn.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtbwbyegtf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtyppskmcy.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtldpqmmfq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtyuwbmwnz.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtzewnytgq.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtzyntuagr.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtsqttpcde.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtpovzjrqp.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtzmwdbrvq.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtlugzbzjb.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtenrvibhq.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gtunlegimi.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gttuwlnsps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtuirbcajx.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtegvafpyu.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtygxsslpt.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtfnelumec.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtawuhtaps.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtnirfsocx.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtrhkufkvg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtrlxrnpgv.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtbsjdcdsd.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gthzgoldkp.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gttngikllm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtshrxdtid.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtcvtymvqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtmskfhirn.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtaylhjyxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtljrucrcb.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtxpsepqdt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtmattsaky.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtlbonqjcq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gthgoyhifo.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtmiekxqpp.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtywjwlday.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtkcbhqrrv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtvlnyrpai.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtkgbnlevx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtoiyqibpo.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtvqbvjayu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtmhunyppg.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtvrgxvkcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gthehuhjtz.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtxhcigwwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtoutnpflf.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtbnlmvizz.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtcgsjccpc.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtrvionuwp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtexffzmop.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtsoaacajz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gttewkkbvw.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtbwnaqjlp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gtriyzshmg.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtgwsuskij.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtovtlaccu.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtjaqlgrce.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtyznhrkff.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkxwegeu.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtgpuvydrs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtliubpjqs.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtcqtacvkp.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtnglctncm.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtctmnugbp.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtldmivlwg.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtfwapbbhw.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gthigetiqd.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtpebqcfxn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtulcsapev.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtjvojupxv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtgczbhuwf.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtnrahwnlx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtgfoxtmda.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtwcrncivg.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtlhizzfbl.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtebvqgwdh.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzcxavtl.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtffvmgtum.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtprmdippn.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtjfkyuipf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtxecqnhaf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtijeipriw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtrtpfgwqu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtakkzfxcc.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejtdoyf.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtohgsyenj.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpiuvtys.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtgiuzhuvh.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtnxxubhjp.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtfluupeda.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtyguvpchc.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtopaikloq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtsieptopb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtxarhffij.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtyiuswiub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gttdbegeqi.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtdfuwfjsq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtbyxlhuxn.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtuyfxlcsl.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtlcmhtomt.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtnyxymorl.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtvrzzsyti.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtbwvxbtyp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtsilnuvvv.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtvhdwkjty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtfbhihhzi.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtgfwyzbgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gthumedtdv.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtxneqyocg.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtjltnuogo.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtlzzypcph.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtjbogqhpr.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtszigprac.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gthpopmogq.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gthxdeubzd.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtffdhfvmt.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtkhelktzr.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtoddobczt.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtomqjydea.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtytekadex.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtgfcpfogy.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gtbgsziext.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtjcaykzld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtwaunmfol.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtkyoxuwrz.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtmiivrlya.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsyqyfdc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtuhvovwua.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtqsxcuveg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtzleemwpt.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtznyxinva.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtkyyvyu.html


<!-- 参考信息 -->