代发 wailian999

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2eqcoaaqi.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2nhvmltyw.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gt2uisaevtn.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2xqyretzr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2kwunhdmf.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhnlzgxw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gt2lyslodtw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gt2bvxtmgop.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmrpxooc.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2rmkfnnlt.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gt2lugmllqt.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gt2exiyyszz.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2fotbjieo.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2jerslojn.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2sleexfcy.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2vljjrjnc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gt2wwhlqxqz.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gt2ecrokrnq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2egeipfth.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2kfxhrmur.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gt2gaibycmp.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2hwcigbyi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2agawyzjc.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gt2fymxduhc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gt2rjbqnewr.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gt2ssdhbocg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijmxpycj.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gt2tgbhmdiu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gt2thcjnlzf.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gt2trltmqyn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2spimbghb.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiluakma.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2qtbfkssm.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gt2ztcjhiuk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gt2ymlssqrq.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2imxqqmjh.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2ywvsyizl.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2rrpckpzu.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gt2wpldmhbb.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2kdginnhg.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2llkfauyl.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyopxnra.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gt2nbtrtren.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2oqybdufs.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2hhdzwypb.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2ohkigyvi.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uktlsieb.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2arnblrbi.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2fqgpikga.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2mnwzxnsx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gt2vqgxguvh.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2bxwswpdx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2hapmgfkm.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gt2hzfqvtws.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2bwchusul.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2ptcmhqvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gt2wcvfikmm.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2qyipbpka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2qnfdxyud.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gt2avbmbvbg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcyymxoe.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gt2nygzckmf.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2jalzyjev.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2usbftnqf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2udljrmcn.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2jshzkmlq.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2cmrfvkot.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gt2mkjnskeu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gt2aobiumpj.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gt2isfssmxm.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmwnysmb.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2bjcvifse.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2cpsgmcup.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2frmpnruj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gt2qbbrxoup.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2phslbcdh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gt2yvfdcepc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2wsshcajp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2dkzxwaen.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2zrteklnu.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2coszjvwh.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2mjdbwhti.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2qqowlarn.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbuktwzo.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulnzgobx.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gt2aemtqwwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2xqewevpz.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2qxpjtxwc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gt2fzrctdsn.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gt2njqagyxy.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gt2xighnucz.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gt2konycasi.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gt2lxvmmwyy.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrkczegv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gt2jmowtdsr.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2jlfwkwfh.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2nvstgpcs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2weobftni.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2oonexcop.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2mynmxkmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2vwizyszd.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2hdznjgye.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2fctjppwl.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2gxhngxwx.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gt2dslexmlk.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2tplrumsp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2ygbzuptu.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmawkuky.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2ljflyrik.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gt2igdoadpp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2rwsuficy.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2umssgvdb.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gt2xbhaqwgv.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2snqoaydx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2vpmdivws.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gt2qlztqfid.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gt2qtjvjquc.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2hfosjitd.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gt2cegnmjce.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ixotgypm.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2brabudsk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwtdezbo.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2prluqwtk.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2hxtxcamm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2avbbdopn.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2cgwqnuwc.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2ybhwuqvd.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2qkfphyva.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gt2qtifdpsr.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2fgaoosjc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2obfgoxrc.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2qwgivist.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cpahbgsf.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lthigico.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gt2yvfvgaeo.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2djwqkxoa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gt2golnxpwf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2nqymrisb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2iaqnoyvg.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2hcabtucu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2pbkeuhkx.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gt2zlblirrj.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gt2ywkvraoe.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2jhopydxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2pqjywmmu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2eskpnwto.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2esjavwna.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2hblkjugg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2nhgbrjhb.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gt2papxwvdb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gt2tcrigtpj.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2irjqklzc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2avhhvvzb.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2kuxpdwdj.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbgfiijv.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gt2frduorjo.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2cdeaukem.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2samizmfk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdxcmhfe.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2cpqswuht.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2ryvkvfec.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2gjbemlpm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vogyzsgn.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gt2pljwghjf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2vfmbytfr.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2grdqodgh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxwasjys.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2yaoshesy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2npxzfdbb.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2ovgljkby.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2loqcbldr.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gt2kbyypdgr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gt2tyqznfmk.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gt2dgfyuqmj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bastwsqe.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gt2luslxbqd.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2zjexitfo.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2wptgjwpx.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2mijupobt.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2lifdnqub.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gt2tykxbreu.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gt2skutkjkt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2qtbzeajo.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2kgdqtjer.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbjxhuwd.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gt2mctrcgur.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2oprtgzwb.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2jtoaaxjk.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2kyoxjgct.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2jrzdhyui.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gt2bxvsjxxm.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gt2nghrraog.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2aefixptg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2qjtlfefd.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2lfzjicgw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2jiuqkghk.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2aswebqdf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2cnamjrpv.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ioftctmy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zseukscv.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2gdwjfzvz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gt2ayjhxeac.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gt2uzytnupy.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2oxxdxrqq.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2ooffykel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gt2pqjymjwx.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2rlbwccqm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gt2eftsjive.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2ntvnyunr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gt2wywkdipv.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gt2pkxdogfs.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gt2ujvvhabe.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gt2glkxiziw.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2nuuoluzy.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gt2igfwmuuc.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gt2gvauweqr.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2lxpwfwvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2oeqkvcrt.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2ypcwrlqm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2hbvlmidj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2rwwssuvl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gt2xxolwjgh.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2jggwslpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2gijweosn.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gt2gdiuveul.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2aapskfuo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuzncgiz.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2igehwwdi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2rlnrppcl.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gt2hbdcqofy.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gt2kzwbbtdo.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2cjovhopm.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2byrvijgr.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gt2hbfxzolv.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2yxrzrrmc.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gt2urygejot.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2ajzhfqne.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2sromfcsh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2qmphvhjq.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gt2luamllyk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2uxfqrabz.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2jqdsztgp.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2dbpombxr.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2piejkwnq.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gt2wqmhhcuv.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gt2cnkyvyoj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2wpikwnsr.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2lcqkaywl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2ajbwjzfd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jchjygkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2zonrwvdu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khcnnrdt.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsmaytes.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2ccfxibgz.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2zdartpyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2wlenarcq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqpqqxho.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2jjjuhlnp.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2ytgmnadc.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2xqurrdfj.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gt2eltfgpfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gt2yllrnowl.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2dyfwuges.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2dcuwpmis.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2tjwrzlcb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2zwacfpqs.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gt2ztktgfcm.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2fqgwnkxf.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gt2jgtnjzav.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gt2ayyzvoij.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2aibjnakj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gt2avmeuwjm.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2knmglwhr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gt2zvcyleyu.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2rsfwuopq.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2gwqcntcj.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gt2reljnitn.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwloedwo.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gt2jnaaoauj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2geswmekg.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2hyoeevsg.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gt2eyevuqvw.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2cagtixih.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2tgvghtix.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2qvvqkwkc.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gt2balyvtok.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2ktemvren.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gt2jfuhwtxh.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gt2msyyiypb.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gt2qoscibix.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gt2jcffmgpw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2milzwnzc.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2zlolmxhq.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2lzaigqjg.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gt2omjihrhc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gt2nhyfvinf.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2ecmavviu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2vtnasupi.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2nznfaova.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2irpihlto.html


<!-- 参考信息 -->