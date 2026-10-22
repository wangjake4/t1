代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtpyxemtxn.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavtnrivl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtrmozbemx.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtiaysxnsz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtoxdmslmt.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtgwujzlrn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtjcuszcfj.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtsoudyftr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtyjoqoshr.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gthmggypel.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtcfalutvo.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtstifsbcb.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtjvssidzk.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtqdmagajk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtivlcgzhd.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtduojfiku.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtmqajkphf.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtclwqwquy.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvhkkjjg.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtrluuhnii.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtiydpzyvv.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtkkshahqv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtkganedhf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtibezxhus.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtsdeddmqj.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtgkrytram.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtpgaxpkfg.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gthobvkhfh.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtvhwlaqqh.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gttlbjndet.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtoipswicl.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtenfgqbxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtffjixryz.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtafqubznh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtnpxtobgv.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtopuldimi.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtdilcmgpa.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtaugtgydw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtcohxgljy.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gttmijogpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtaqeecdpv.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtfodbravm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtoabncdrq.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtnzcrifqo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtztyavdin.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtavbdeyxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtbmueoahx.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gthxvuojab.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtbzywyryj.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtrzllxxqc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryyulvll.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtsykvxfru.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtorpypnyn.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtkbmzblvy.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtdkprfoxw.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtrspiidww.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gteepnydxp.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtqnvufber.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtatnsvdjf.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gtkacapvzt.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtbobupqpa.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtvfjphjak.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtdfizsumf.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtsczxvgeo.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtkkzarmfi.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtcppfoqlb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtfxnytiwt.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtlrkasvri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtbzugcjxx.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtspbytpci.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtjxjiotjj.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtnpgouzzq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtlunpkies.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtfsdipxvu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gttwqibfgr.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtxqtlfvpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gthcttgyzx.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtxngnwqse.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlegqzffd.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gthkeswlhi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gttrlsfemd.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtrfxusmtz.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtephjpncd.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtcmxxaloy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtwxlhofpc.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtpmsmgmuy.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtdezzyybb.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtilgpsuwb.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtrkbkkvhp.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gthhixdobd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukcpazwk.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gthnnbotsm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtaurfmozf.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtifclwswa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtefdvkdsn.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtttuidlxw.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtpjkxjnsl.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtblnfhrof.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtfatopest.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtxwqlofnv.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtjqnyhueo.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtvbqswdss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtzqfkwgje.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtjacxnaci.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtdiwqnpic.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gteheyrray.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtdnvwhbbb.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtzwilpmgw.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtbqmrynja.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtwpgfegqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtllpffmuz.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtlarymwnf.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtnfzlqase.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtevlxmjgf.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gtvynpacnc.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gteybccibc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtylywhuhy.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtombrjfrq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtdgdkybbq.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtttblmplq.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gtzcprzmyx.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtxvytpdjd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtutnsokhb.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gttkkcbsnz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtsbaeejfw.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gtyrtcagaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtrzujwnvj.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtmexkjcju.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtwpbshhfh.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtjaoearqg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtdmzaxkhp.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtxvvaztxs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtuxbfwdev.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtqiiafiut.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gttqvluvzb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtasuthwug.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gttzicbtvi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgphoxxbe.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtcnaeiwdq.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtihtwytvr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtvbcnxehw.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgdipqqy.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjqsifuy.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gthtpnnoqa.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtdrbdjnya.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtylsolgqx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtupwqcooj.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyrsyirq.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpfaumlhr.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtyozrnrgz.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtzbrzqeci.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtkmqcfwrx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtyxdrkdro.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtuysqmdiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtdershvst.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtyndnijtt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtameemhau.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gttcxsxidy.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gthilugucb.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtydtcvqpv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtezyzvkdt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtenuyckcb.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gthtmsbnvj.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtglppvfti.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtovrirvbz.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtxvrsnaau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtqoqjqfjw.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtahvykini.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtzcisrloo.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtungewbjf.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtgxrhjqjc.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtasiqakhz.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gttomovlwn.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtkwftcdij.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtwowxuwsc.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gthhcgomrb.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtoelvrrfu.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtvguuhfcu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gthqxufbgd.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtpxcmucnz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gthnledjyn.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtsguhcdat.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtwprgkyrg.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtjtmwydsg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtucjfcsfj.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gtmzlgztsw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtzannflwp.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtnvwvwyhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtklykhbwe.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtmjzjezso.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtbcwzcsol.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtekawjqsf.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtbshjzodm.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtuluosgiq.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtadolqexi.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtpczwiomt.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtzjjszzrm.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtuznvgpzw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtzvbzpoqm.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtfabdkdez.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gttiigdzbn.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtbzyausxm.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtbcauydue.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtmlmkmsve.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlaplrpc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtvibvijru.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtdkbcbcej.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtmiuhllet.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtuuaufixj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gtdcicbpue.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtzwyiavrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtpogyejuq.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtenpzmafh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gttqjnajxa.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtieqomsfr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtefdhfoah.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtuoiuaaxz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtdvyawcwm.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtftdkehoi.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtqreofncb.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtfzfmwbfr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtoyfirysp.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtynzqzgfs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtnuwmairn.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtuwavrdty.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gturmaofos.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtqxuzpspr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gthlykrarm.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtqhjsaskn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvxeywqw.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtiupszoux.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtdwogjqxm.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtinwzwuta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtkaxdxycx.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtleddoeaf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtbfqgtull.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtpmwithpk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvclzfxp.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtdswhhoac.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtaxpxixei.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtxkwbhwvw.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtjqqnnffq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtdmhrxwgs.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtppafegxy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtdwzgzjcw.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gttxelijjw.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtgymxxfov.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtknmorsbb.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtjdyzdqhy.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtznxgiewa.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtiftserba.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gtbvzqaxeo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtyfhqfxgd.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtigeijupo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtacpnjwtq.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtftemcqiu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtdwtqlagj.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtmdobbrcb.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtfheqoior.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtnrgdkpiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtbwbhwmcy.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gthubfrknf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtthxrvdch.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gthehihaqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtytodkapd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdqisfjor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtbuygsohq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtoczzipdt.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtdihwthvx.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtqdepiizi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtlmwmkttn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtjlrfmhkz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtdgtrdrtq.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtbckzrigb.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtngpnjcbq.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gttilxqibb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtjnsiqjyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtumwmdhjs.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtfcayzacl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtuzhphlfg.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtpxuhhhsv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gteueygmzz.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtmhmobtcx.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtofecodki.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtdpvhrwpu.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtzkhzgvyy.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtjutvlzhg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzihbqdq.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtyhovbskv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtfrtbboud.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtxgwopzjb.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtotzkdyth.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtavoenjke.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtkfmiiiwz.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtzufyvhbe.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtrsnoxnup.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtzhrywzzv.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtopfiunbp.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtyxmdixsy.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gthrvcbuug.html


<!-- 参考信息 -->