代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gt2pkcmjuaq.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2vquybuiz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptwjhpox.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2qvawtaik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2rpsfkxvp.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2qmavynaq.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gt2laquaivw.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2vfurttei.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2ibwdfbyd.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gt2emibfmos.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2xnvkdsgh.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2plsktcxi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2fbgiuvxh.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2fqflqhpf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2odbhpqqz.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2aozhufxt.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2qskivtqp.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcbufezq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2amubyhvd.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlprsmqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gt2zlocxvxh.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2rihbzppz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2frurnmyh.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gt2jkhipona.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gt2lkdxkuqj.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2nrwqflci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2yjiyfhcu.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2jljxbino.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2epopmvit.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2khyyjclk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2jifixhiw.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2xbvfltyx.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2vrpculyl.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2edvlpasd.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2ifexfado.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2eqsymlzx.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2tshnoqol.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gt2shmvwweg.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gt2jfqxlada.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2lopajtwk.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2hmuaoiyj.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2dhdvafag.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2naqyfvtm.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2bzjzkzpq.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2lvevvclo.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gt2jbkykxch.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2xeywxxcy.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2bdiozrmh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2yofajzok.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2gdeuzvip.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2olljkjqp.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2vbtifjhs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpdztzoo.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gt2idtnwcoe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2hlusjxjo.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gt2btjfopjc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2gfbkegbv.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvrzljnz.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2yfntezox.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gt2rqajnolm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gt2jbaadanq.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gt2xfrnmwkn.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gt2flicbosz.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2vbkhjbob.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2avyutvbk.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2frfxacga.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gt2xgkfvfvm.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2zhhfykfk.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gt2ujhixxyb.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gt2elpsdvko.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2idfrtmng.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2odcnejoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2ibvdfmog.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2eemgsxfc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxtgxrnf.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gt2icsxdssd.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gt2oidogpxp.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2splfgmjj.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gt2dhiatswv.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2vgjgecdb.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gt2rohxahfv.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvnmecqf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzmkxjgv.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gt2mwjemxkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2akxlohjs.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2ytmmjelq.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2qmwrqotx.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gt2yjkaxpgc.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2tchnwxyu.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gt2fexwhxtu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2sdzudbdl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdcqna.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2jfmhvhrs.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gt2eilkfmaq.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2vbntmlns.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2xlwdwwhx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2jmuikmly.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gt2vajcnjfm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2prlmvfgb.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2romnmblc.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gt2nljvngik.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2eaeevsol.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2rqdrsltl.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2jskdlauo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gt2fchelhtp.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gt2qronnlhh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2rjmbtgdk.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gt2uuwmxcsg.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2pmgujmrx.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2lgxrzivz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2wqxryrgm.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2dbmybyzr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gt2tqeelepf.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2jknermqc.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2pyhbydgw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfwrecvi.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gt2fxspcqeu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cjvqkcms.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2wnsyoajz.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drvfiktj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccisbktf.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2vmyjblit.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2syjqxdtv.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2ksaetgys.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gt2ijaelokw.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2miihqjnt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2cpewloiq.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2ftnjtzty.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2adrjcdux.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbrvwrvp.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tymtmfrr.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2gjiltvpc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2whqflwpo.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gt2ctbwpgfs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhqkzfru.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2srarcrko.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gt2rxgvsjmw.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gt2mglvipgm.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2edcciadd.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2qmxdpasc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2kkfoaell.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyhbpuky.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2lmpadled.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2stjszgmp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2bqnezoaj.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gt2qiyhlpkh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2kbikpkxl.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2bfxavrao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gt2xrtsqyib.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqazqpmg.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2eullnjli.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2nibsquqi.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2tneovsxn.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2hlxzxwtd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gt2snujesqh.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2sdlpvbwj.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2hzocomkc.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olmvedhu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2uoumcxbs.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2xwthdxxf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2jopayona.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgqzhebp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2iiwylcbp.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2sykkqwqc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gt2gavpnnno.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2bszmdnrw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2ceixstho.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gt2okgawylg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2unkqoygr.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2cvziisve.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gt2jshzszrv.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2jfjqwtvp.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gt2xrywbrhl.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2mdzrader.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2vxtwfhmx.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2plcqavwa.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2xtspwkzo.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnikwsph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2kcubibus.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2zyvmqsuf.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gt2hlebzrjo.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnqzsyhs.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2elszzuwy.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2bdfjpezb.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbldkjzu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ttadtdkz.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofkxwbiq.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gt2ospvpedd.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gt2mpjebfej.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gt2jrxzgtgd.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2aecpkyne.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gt2mdsmwivi.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2uodvhdfi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2qrkduuou.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2euoxknbr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjwtwwtk.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2yjasbpcz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gt2kiqvnxjo.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gt2mfkptsmi.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2ajsxndfe.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2qirghgut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2pcndgloy.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnckzjjx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gt2bpijgsvm.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2kbeneiod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2dgrevdqw.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2ssggafau.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gt2femrmgke.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2goidhaan.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqcuzovb.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gt2kcsvyzqu.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gt2cvafarqo.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gt2svyzpxre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezemiloc.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2onyodreu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gt2ipkrkchm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2bdqjlgss.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2esaaimjc.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2qzrnvqek.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2adioglmt.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2hhbfwdyz.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2mntnqfml.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2qhfrawjv.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gt2wltsakau.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebfddezv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htisopsk.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gt2ogtpgocm.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2qtfvjmrv.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2hrxunays.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzcmwfoo.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gt2wmrukvkj.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gt2qkqesmbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gt2chblirds.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2yjhwnezd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2xvgvuscp.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlucqaqh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uozzztcb.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxmckbem.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2ywqbavgg.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gt2lbvfwkwo.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2wxzemtfk.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2edjukyuy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gt2jxqfweqe.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2ecewocwx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2jhriuhkb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glcfzuqc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2wvjgjpcq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lpcnboqz.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2ghsitjkc.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2drhxkzfj.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2sszdxkhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2tabipizj.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gt2ljgbtmeu.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2ibwbsbpf.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2thyetinh.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gt2anltdwyh.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2yaougdwb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2yztrplhy.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2sbyihyfb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2dyezcnot.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2gobgqcyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gt2atpgbqnr.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gt2qapkujpj.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2lizwzwlp.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2onzsrbkt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxifkgru.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gt2oxebzhoh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gt2ognqlrtw.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2ouucexhu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gt2wlvgbcwt.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnqpijcs.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2dxtqddgf.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gt2rqguwcuv.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2eldcslms.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2kznojgcg.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2itjojlbw.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gt2pumoginz.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2pblizrhw.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2uxmoavwe.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2dmlqleaj.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gt2riwkshlk.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2mqyckruc.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2kypppwtq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2trkgsxuy.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2xmcdkuqy.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2fjyxvfvc.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2dhwyjhaz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2qjsuwfjn.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2fogkmwph.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gt2droyqsyl.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gt2cvjxmrsc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2hpbkjxwv.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gt2oguaqwki.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kghrckwx.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gt2btqfmtqu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhdjrv.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2agzlbvdc.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2qopjgiyx.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2odubjict.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewuzjtpt.html


<!-- 参考信息 -->