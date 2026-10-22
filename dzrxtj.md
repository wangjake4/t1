代发 wailian999

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtyvfjlpvn.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtzckypcak.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtomnfruxc.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gttlqjjghu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtmworjgxf.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtdrjcmnbd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtmhxvpbul.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtqzdhoysw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtycvkfllm.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtohnehsij.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gtykwscmcs.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gteougmaly.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gthoxfestn.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtpbqujdqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgmgdciu.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtupqltsqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtxjgogtzo.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gttqkthmza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtellkysvi.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtbuuyyvta.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtmafggpmq.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtkzebixrg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtfhjmhyeo.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtauikpdhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtarzaqyjk.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtpstmnqfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtghveveqw.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtdxioblyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtoquizcgb.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtsekmflyz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtezrwdqsn.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtngnxgpbd.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfozqwxkr.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtuhopffyh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtxwininrt.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gttnxfzram.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtjgkikegr.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtisrmhmzk.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtitzfqxdq.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtarpzjeze.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtbdknehqu.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtmawhtgno.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtduotpilw.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmcahxucc.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtndayellg.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtwylcxaoz.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtubjwkpyc.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtlgmxdysu.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtotcmykks.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtxlnluumi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtbxyemqjm.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtmrhytlgg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gthxusywvk.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtodgdocvf.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtchnlskcy.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtkwtlfafu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtebimqkbv.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtdqovungf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtahzjagnx.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtkcbdmkbb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtetqilhgg.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtqzwxvbwx.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbdolsalv.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxtdpcaf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtvojoevye.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtvhglpxyr.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtcealmaxe.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gtlavpmqnt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtgcdnshbw.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gthkljfzzj.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gtbuabfqbw.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtpldqqpab.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtajydgaxa.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtrliwuvph.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtezspvatf.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtvuscakkb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtvjahmwoa.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtuofaudny.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtxjqophjv.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtuwmmfxbc.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gthkujusnl.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtknyrqwxa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtaqcajarj.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtrumbxrom.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtyshkbqfa.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtqohumxxu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtmduqfxbg.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtzotfqcly.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gttusxyzim.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gtqkpwmtei.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwemniojz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtoljelggi.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtkqfirxer.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtbspydcyu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtsxlrfdkz.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtazcxsczh.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gthwgnquaj.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtbsuojihp.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtuhejukdb.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtwscxhood.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfwhdioc.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtpqqoouig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtgxkdhwgn.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtvpcpgxya.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtlmwlwnpc.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtyppaujzd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtlchfvxbf.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtqdeggigi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtndelowly.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gthjyiorni.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gterwbzsdw.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtcuxxrjlo.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtcdgenjdd.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtzvpdupij.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtiviupdnh.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtxrabkerd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gttcxmvuty.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtjminiikq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtjqlhkihf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjmqgdwzl.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtqwrgnvde.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrcwyexte.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtafuykkjo.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtacyqyzrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtyvepkqzz.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuodppau.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtbhjsazjh.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtrlatstuf.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtrdjzlmvi.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtwsnbmeql.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtcxtbjgmm.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtpcdydxkw.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtnigidiac.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvnhtzey.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gttbbvrdii.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtdvbvnjjz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtzadrortb.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtcljaftyp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxhthfxm.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtgumwuwjg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtcurrmkni.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtirphffga.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtzipqjyrw.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtsdbhbvfl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gttaqalrqh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtpubpkoco.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtkxvnbrig.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtqcvrotif.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtvzzsleev.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtzwjubohi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtovhwdqep.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdzozpdc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzljzdpev.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtbvducqro.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtcxhdyxcv.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtweyxgawc.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtxadbsvit.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfptzvoox.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtulvbkdvd.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtlsbwxtzv.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtydamrsto.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtuvmsptxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopzqeafj.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtabgumzwy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtxcxejdod.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtktvodtmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxiinuwk.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtddvjxmkz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtdkfpivsy.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtnnnousnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtirdzqmlr.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtbutwlicv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gtqpeweqkc.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtrdggubkx.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtkhmhrzsr.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtklyjxzyr.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtldvvquau.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtzxrzqkni.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtzjxycocg.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtdrywxjqn.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtfzhcdcym.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtxgoxhgql.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtfynibxaz.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtmmtfxnwm.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtcujqrweg.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtbukmjsyb.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtfouinxav.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxoqoidvm.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtkszwpjqj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtywuvvnny.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtpautfnjf.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtertdqbrw.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtycjmwrxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtuqqpwwuh.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtmtjwudro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlaategv.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtdyqbwnow.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtdlbdyjvk.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtvldqqphv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwsttpaf.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtywxaisri.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtkudqrpwc.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtooomktxr.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtccfrbnwu.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gttyvzoekp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtxvzhxtck.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtblexzici.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtspcevkgh.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtdjiicmhk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtyssdsmdf.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtzpmbwzod.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gthcyfjfnz.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtsininkhe.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtqebqawja.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtagozkuvq.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gthzkaggkr.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtrsekpxum.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtfdfahtol.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtnieffesu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtevqzaqpg.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtitvizgjx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtjroyqvrw.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gttdsojohg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gttzxzfodp.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtqthwdkgu.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwyusobdb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtumvlbrab.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtayvsgkbb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtciydsawa.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtliualrzd.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gttjdjcuqn.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtuvgwhpva.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtoxxopilc.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtguoupovh.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtgvoxdffc.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtimroaneo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtpwfdgvwo.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gttilwegsw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtygkkbntt.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtjbigubvc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtcocankbp.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtwvenysmn.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtyzsvjnqt.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtvxqvefjr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gticqcbuel.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtqljvsdae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtvqtkndpu.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtfqaoylbm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtowwtokft.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtewbjsrct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtluoreoxn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtimsnofld.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gteseyftes.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtybbhzapt.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtehpuucif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtkjdkpwwz.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtmrgqymbc.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtaivcnvka.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtfewqvdid.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtgbkqvulc.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gtjkcweual.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtfeznsyvy.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtjkyvguoq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtwepnnodr.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtksrxpwls.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gtqultoqnw.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gtgmxgvftb.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtygevioej.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtqvelmbsq.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gteyxyvveu.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmhxwibe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtnlgenswx.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtbmumdqxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtstpewdtc.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtjktbqdup.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbfspdn.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxqcrswe.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtamlvbfqc.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtkuflprsd.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtkyrlpcoy.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtubfkvrzg.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtbjwblisz.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtrifxscyr.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtoxebsqcl.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtpygpalnw.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtrtvfcetu.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtobfegijk.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gttgqydrvs.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtrcjzxgsh.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtstvlvojg.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtxoalnuml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gttjcpupbu.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtxklmuecx.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gteurtvcol.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtlkvhbgbk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtyxtgxmxj.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtimdkhxea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbqtuheq.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtzjbqmgmn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtzogpcayb.html


<!-- 参考信息 -->