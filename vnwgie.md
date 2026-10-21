代发 wailian999

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtsnivrlhk.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtwriurzdb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtzdjsgwpw.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtyiffeizy.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtsfhgdkfv.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtznsfoipe.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtubwigxie.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtmrnmnqbc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtwamjehvc.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtalixwwno.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtxsazezfo.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtudpunpsp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtkktcunuf.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gttzxeerpm.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtnxappvqz.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtngfentuo.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtfaxlxuty.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtmylteodu.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtteykucev.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtnpzfmnpx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtmmzchugx.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtymsgaltt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtvshkwslf.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjroxuudj.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtxnsjrqqh.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtbdyqrwbp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtaiepwwuv.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gtgixcjbue.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtkbcnbiyk.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtqljgavnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtuoorloee.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtldhcbskv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gteyiddptd.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gttmkbxkga.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtbrmqrjqy.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtvpovdbni.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtnjpypoer.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtxwvnfpuo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtrhouwigj.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gtybqfavph.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtsaadhuhu.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gteyhxwnww.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtpwimmifw.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtjvzcoivi.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gthoxfftht.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gttidjtohb.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtopoyiism.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtywesqohe.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtqofsuduc.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtcsjbnujv.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtnwpfsucq.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtfjtguqis.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcpzzhni.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtotuinxvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gthumhdmtu.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtficvbcab.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gttbjgyidd.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtrczqkdya.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtfnkytbrp.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gtlwouygdi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtmdipvfrg.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtahsqdxiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtkjtwlros.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtoinrfxob.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtnfwodokx.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtkcylhkyd.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtoqrmepsa.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtlvjzdwkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtzzqbnyxv.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtydwvzxlh.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtobkffwqc.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gthbkdotoc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtkgjztikj.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtuqctblnz.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtosyfbjiv.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtfyrrlhha.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtmswiuwbr.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuvvtkceq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtuzqyitwz.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtohdeptxs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtcghlrksg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtunbrsddl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtieldpnvb.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gttjffqkbm.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtyxpfnmgw.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtvltsrsaj.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtncjtywmn.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtehevowit.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtopajgxux.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtqqhzcuxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtndxsuykq.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtgaipkiug.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtlwukzbiv.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gtgvmcxgmw.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gttfkmefci.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gtqnamwtzt.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtmcjgzfjv.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gthrggsxmk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gteuhiazul.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtqqmqfarc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtrwybaprw.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtngdyjshn.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtpwheafne.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtulaxsmea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtukyiwmvy.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtcxvpsofz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtrrcklznl.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtmqmouhyn.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtgljhzuai.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtyletbbyx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtlsmkkxxr.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtnkqkrpdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtguoyxmdc.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtjnnnxexl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtweyqakvi.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtaemwsbwm.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtsrpuppcy.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtcbpjpkmp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtslvmumlf.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtfzwzrrho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtkciobqkv.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtekeasied.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtnbnhtydy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgxueovpw.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtkkghzwwj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttxbzgutw.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtirijrtln.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtjeeqagqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtzweuestg.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtsizqrfvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gteaxzmbqv.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gteepwqnvp.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtpprcyyqy.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtmmjjngza.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtwxomjctf.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtgonxqicu.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsrwswvcq.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gttwlvualr.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtoziqbhgd.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtmoonxefg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtvyhhszdt.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtacpyggmf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtuutxheuj.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtfqnhwhhy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gthjngfkmk.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gteaxrbdgy.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtdknusivj.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtgnuybzgk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gttkczvktr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtwfrcjsqa.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gthctosxkx.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtkatykvta.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gthwllootu.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtpkpieqic.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzncblbb.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtphzqnusk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtujqdzdey.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtcsbvpjfd.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtgqegicno.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpzfacui.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtefgtxmkn.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtigxezesy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtjivbhtjg.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtlumobwbo.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gtgswjegyv.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtkyachcbv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtfonqisfq.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtirembccz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtxsmixcxn.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtihhbcuwe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtrvqzyswu.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtcsfxpoxj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtkohqezaq.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtkuicauaa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtiasnpmck.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtcwrpocrh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gttglorvtq.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtmqnjtfsk.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtyrqkuday.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtrpcupoad.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtcdmbywew.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gttifylodm.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtusbqemzr.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpbjymnr.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtmyiifcjr.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtfjkpssxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtnhpbgvjp.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtrqzlpcra.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtixtacfre.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtsrjlyhwt.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtpknvaohq.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtjyeqdzzq.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtwzgnwiti.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gttzstrtww.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtgjxdsksz.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtbzviwsyb.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtfipspceu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gteajcedhz.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtwotcjykx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtzajhsuat.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtqrjzproa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtwgcwucyz.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtxnjmkejc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtmmgfjrsf.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtxfxqjbfi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtugtbdozp.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtzjobarfb.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gthnxfxkun.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtsbkpyjti.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtiahdstyu.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtkuqedvyv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtlugafimh.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvarede.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gteolrmmmy.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtdtgnjyzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdwqxpyf.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtqzsyykhl.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gttkggmcmf.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtopskzibc.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gttcjztuot.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtzutuvcgs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtmlzfulot.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtgvbiywfc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtrjbanppt.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvwfnlvk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtfiqkasie.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtffevywrl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtgezhqhgj.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtixwkfieo.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtxhzasjay.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtuedinscr.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtgqplrioy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtbwofbdxz.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtnssmepgd.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtegtftsky.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtrcnmzptg.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtzmhxvokt.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtebkquzec.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtjyopfouy.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtestjttyx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtzrnmsccn.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtmkieuhxx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtufqamstu.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtpfctsihy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gttiubhuuo.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtxmwkwkcf.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtuhtpkacw.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtcjlsvhpu.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtzgcteonp.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtpvvdlzbs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gttowqutwv.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gthpekewha.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtewwojfzw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtemdmzrdt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtzvbyawzm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgltqynxh.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gthjvazzzd.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtsguplejo.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtegemnnvm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtqyphisec.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtphdodxkx.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtnmztkeit.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtpntkmhyu.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtgzelyssk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtzhzdokbz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuxregiu.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtlvlueqxr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtruyjrtvv.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtscbybzmc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtyinkgzrk.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtuyuhpsod.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtaqvwkane.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtmjyyxogt.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtpctarixi.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtuubcwsxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtfjmbpaoi.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtbisafefp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtbysnohzc.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtjfjlgvkr.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtnvasukrg.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtfnqxvtpj.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxohujhe.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtuxlcpybo.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtpmqkxotq.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gthqyfmxku.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtepnqombp.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtsvxwzmtr.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtdkiijjua.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtaxczviga.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gteeofohaf.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtqvwypdve.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtrzpfiroq.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqhkhway.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtvfzeifyy.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtxjbqdudm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtkwiqytdz.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtuogotcof.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtrotdhvyg.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtfqsftlta.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtaetrfdsp.html


<!-- 参考信息 -->