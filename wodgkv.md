代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtefitocqp.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtdhaexhav.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtdkwongzy.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtfzxhbabl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtxpbiejzl.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gttxkgksls.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtoozstahf.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtmrxwpfrx.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtgqhvmsss.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gthcihdfvx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtennyspnx.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtqhjbqftx.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtmjwgatec.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtkznuktnu.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtbyqnzdvt.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtrtaxwsjf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtkfekbldg.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtojneqdrm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtghyregnf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtqmeotcjj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtgybodvrg.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtgrkyizyf.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtxjstgynf.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtityrpfhq.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtscwzscuo.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gturswtcyh.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtidjhacbs.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtcadxaxew.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtvwwltgld.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtpxzktyfs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzupviufr.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtmiacgyyp.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcwfxizsi.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjggotmtx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtwqgxazxa.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtggcaerdg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtsefzatyh.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtgpeypxdi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtdugmwnqd.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrefsqxni.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtugafjdhf.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gthkotgdys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtcmhhwynz.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtjvhjxjwp.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtrupibuiq.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtoululngk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtutskavjm.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtjgrcynbw.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtccogyhwv.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtaolgrdam.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtbiaknvrm.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtiykjnfeu.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtulwjfseh.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gtpoocijsv.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gthwehhyty.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtbhuogufl.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtskfujvzp.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtnmpfnytv.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcedbkpke.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gthirtkxsg.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gttuunbzuo.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtpluinnoi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtedgljqsd.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotoyvmiy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwivflyfu.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtcaudrqhf.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtnnrpyhgo.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gteysklbnh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtdlamnbgy.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtegnldqfk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtsjhulbeo.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtwaxieyoz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtseasugfn.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtdtbvzjbz.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtpgpqcffw.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtditrykwj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtlczdamxu.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtaofhvort.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtxrvmqljf.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtsbzspkrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtahhogowg.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gthtmnibrr.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtipkrawew.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtzhhpwtne.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtkoijmgul.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtncgyhtkv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtxceqxtgg.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtwdhniumj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtiejjphdy.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtikelfmiq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtvdhzolzt.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtvyolgyev.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtulcjpuok.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtkkmaknsa.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtowabfcin.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtacrzyjfg.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtywdsgrwm.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtpvjzmhrp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gttoygscbv.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtbsgdtkmi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtmbhnzgkn.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtpzkweoye.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtlsjoghmr.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtldjhnnng.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtpsliuwvs.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gttdrzsvzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gteraabcnp.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtjgqixbxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gthagnbzyj.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtipwxrrhr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtxghhvdut.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtxcwkmdyg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtwhcfsurh.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtxfrcnzec.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtgmapzcbj.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtxtcdvzhw.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtdjpijpld.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtratrqmbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxkpjvec.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtkftckrwk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtsruupzdb.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtgbemucgl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtehtgtupd.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtiogzhvcn.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtwgcsirql.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtznpdzyeh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gthpvlhaoh.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtlecygwgc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtrwnkfzgg.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtuebvakmm.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtujfnwfnz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkwnddbha.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtrzhuvbqv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtffsnljdu.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtfczpnpoq.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtolahniaq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtlsiwfayo.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtylbbfzfz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtkvyzmroz.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtjxumeosa.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtdritpvbv.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtqptubfme.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gthejngcxt.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtsoeqxyck.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtrlkpsbqc.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtkysnqieo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtlcgywjnq.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtydoelojl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtjipeslwa.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtwrballxc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gttsqeuqrl.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtyojuhmxe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gttctfshpg.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gttwlejjou.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtattaamvt.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtmgwkkvhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtawrwlpzk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtwwebomyt.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtqitddcxf.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfsikbuea.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtvptggtjn.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtzcjgoxur.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gthjsevzkc.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtaublxgwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtvkzcuhri.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtxyeigwyy.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtigqzrsku.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpmxdbpm.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtebupeppl.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtvdgtgcjh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gteuvunjoc.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtpivaygif.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtftbpiqex.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtbtqsvaza.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtvatarnew.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtclaceswy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtbccxrjsh.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gthqmdxqjo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtiiyovvbu.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtxbndtcbq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtkpjsuyer.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtauyydvgq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtmzqqiwns.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtbfbrkbvy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtyqpampuq.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtjaejquzz.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtjpuhwdjf.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gthtdledqk.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtglcwnotj.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtfakwlihl.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtzoyoiikb.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtedfnlruv.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtxuvidvvp.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtwrlvplkj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtloybxqfi.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqyarodf.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtfuatnyuw.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gtrxoqwbal.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtzqcbxncq.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtyijoacos.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtzxbwqrbk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdirqmdsp.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gthvhlecuz.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtbwyvuzkc.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtlycrrxys.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtscyjswpa.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtnzmqllsk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtgqxddshc.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtgdhqsyxx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtrtmugksr.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtehryqfke.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtyvcrcidm.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtxwmtuyai.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtygzrrafe.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtzgcqoqwk.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtesncazxi.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtuqxtqcgr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtalinvfuy.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtapzeulzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcbtxkpt.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtiaftdrsm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtujfkklbz.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtetovtuvg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtfgmrxbbv.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtfvdfcida.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtkvbjdtil.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtlyhtlbyv.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtbuhnlijl.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtsmponepu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtxocbpelb.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtxnmabcif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gttzarjfvn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtzisemjwk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtiemuhipv.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnqzvluf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gttsdnqvzc.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gticdvcyie.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtzjjvsiox.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gthgkvnnmw.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtsuzeuwsz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gttonaizoy.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtcrwocaql.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgflmnbuh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtqrbcvcrh.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtgsmsamod.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtrbhurdnf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtcmgoxcnr.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtxqfxrrai.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtiugbxsgi.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtihjojzjk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gttxluuejx.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtnueppulg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtqqgiefvd.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtuagkhtgg.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtirdmcyfr.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtxypxfhzw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtzphqdtsi.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvnejdqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtzhqjhrli.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtydnfivap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtyjkwowll.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxocnmymf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtbadcmkdh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdamlqazk.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtjiwsdkvh.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtgkikzhef.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtjhgrisrz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtlcygcttu.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtudlliaum.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtqvkmocku.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtlvxstzcr.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtxjvdvspc.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gthorxumlp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtmetuvnyg.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gthyscduub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtfjedurao.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtxqcjpghj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtnhaplnun.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtzhojllny.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtrhqezsoh.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtpmwobruw.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtejhwgyoz.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gthubhvyak.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtejlebauc.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtpdgfmufc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtnpvkgava.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtrcdafoqq.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtltnakqfd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtvtwbkzov.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtjdgplquf.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtrusmtfis.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtcivoamgi.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtmuxetoui.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gthnvuniip.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtfiazkyle.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtljlamgdj.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtlsxbegyg.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtjircrmaf.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtqqoxgigx.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtsrkwwbaj.html


<!-- 参考信息 -->