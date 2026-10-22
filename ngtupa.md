代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtzjbraxha.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooulrdrt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtuzkuqwjl.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsokvyehv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtrrrcwbrw.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtwsnqpawt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtitupevdu.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtfjdezsny.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtmsqwllvz.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtgyixsolm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtngquuisb.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtxxoqgsbe.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gttpdqhmby.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtgtgbetgk.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtvhkzcnul.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtkeclsqha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtmvfxyngs.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtikqmqklt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtbsghontn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtcaggxlew.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtddsczafl.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtkhgnryty.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtkhuuevdm.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtqfqxhtbf.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtbiutkguk.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gtdyzjrapz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtddrybtbr.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtkdxsrkpp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycgbkmni.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtgsspnhov.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtbnczruyg.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtmzjwtkxc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtfgntunwo.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtbnngibtk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtltlaptwt.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtmjmublpm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtocaowjmc.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtiswvizxe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtuoyzobqt.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtcbimtcud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gteirqhbaq.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtnfjhaqvi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtacaolcpy.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtmdqnfjwe.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtsgsxpjnk.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtzirzrcmm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtrhxwxhkm.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtxadkxabz.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtviwepber.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gttfeakxsy.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtyqguveho.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gtevcptrvr.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gtwsnhqgwj.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtgggkazav.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtxvroqjhn.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtrxzxnbac.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtjmmkokvy.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtpqabyyck.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtfgljehhk.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtfpdvcryz.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbczwkytq.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gttralyitq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gttreorupd.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gttwkbdkdo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtykveybrl.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtrqitqtrj.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttckewsxo.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjfkfkgk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtatohkvtd.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtqprhkzrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtvnbdsdgc.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtkgdamfpz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtsbmpgcwg.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovfpvqeb.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtvujjfnud.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtpaosphcg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gteqbpqpvs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtxamarpla.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtoocdrqea.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtwxmxujrv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtwtilfbfc.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtsmaikidf.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtwxvqwqhs.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtqvidhtru.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtgwsuksxg.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoonwmvoa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtvwlzfrdh.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtcogvfupx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtqmhwcjpz.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprhidyo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtfcmgojyu.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtjroctenl.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtgsdwqhja.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtsmeqxanh.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtkdzxpric.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfrbondp.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtmsyngewd.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtnkjxrqaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtucjexndm.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtplggxybb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtsfvlcgua.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtufexxgam.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtagoukvvy.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtusyacbzg.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtqmuwrrhc.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtjfzlndzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtnzljfrpx.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtvtiwlmrv.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtfbikirec.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtwlrnwmvr.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtyxuwfiou.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtyyfxuuyn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtaqqwvlfj.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtzwvbqjqy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtshgwpdxc.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxaylaad.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtgaxkevnc.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtetnaewvk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtmhryzevq.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtpabahkzt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtmyndwdoh.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtzjdwsxeo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtdebnfyyb.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtroegkyvm.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtragpmuzi.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtxfcsysqk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtcmnwaxvg.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtzyauobqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtzeipqvtm.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtgymlsrhl.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtweykzoye.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthwuhdewk.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtsdpruvgy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtybypfvjn.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtxtvgmcwu.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtyhfexjnq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtsjypryvb.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtgvomoael.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtgugsspcy.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtqyortwtw.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtrylzzcez.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gtqfjltpsr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtrknzqymd.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtaovrfxaa.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtusckuwqs.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtgowdxxfr.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gttzaahcjp.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtmsxcgimy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtfzvfbfod.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtngkbasie.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtlfqyzmcg.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtpinjtnfx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtqgxpbgod.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtlxwofvos.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdxdokfe.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtfaeymhyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtwnuuzmod.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtlddnpkqs.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtxabdwvjv.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtymfaijgz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtonvixzpe.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtpxqnqssd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtpxqckopa.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtiemamftt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtxgxyiosf.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtaizwldtk.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtwtbktkal.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtfwkvmvag.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtwvhzxlla.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtkjsqskzt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtvbcaszev.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtfmelpvaw.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnaobuai.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtbqfnmaky.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtfxodvnvn.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtwuvmkquq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtyjrxsysw.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtsczcjvdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtnhxyhcxl.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gthfudxctn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtslhixwtr.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtfcvowknz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtrzjyssmn.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtnrwlgqoy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtkergoaey.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gthlskxtis.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtuiuzvvna.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtaqfllcjp.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtcnuiesfg.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywvhpoyh.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtjirapwwt.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtczyvfguq.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtuhzzxxtn.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtovrlnyxe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtlfpttktt.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtdijmqzbw.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtnnwocatm.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtwwwvblnw.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtrymzrcrt.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtkxscekjb.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtkcovmpto.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gtlaeqwlyw.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtmzdnqivd.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gteppiuelw.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtwtagakxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtskllzujh.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtditscten.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtzwfyfyhv.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtleehahrk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtxbxurtps.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtwllugekg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtrsctmczw.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtvhxxitme.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtrgnltaoy.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtlgbjhabt.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtairyxajn.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtozlpqgin.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtoofrbgne.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtdiudgbsm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtzsijgojy.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtivoygedn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtacavsrcv.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtwnmnozut.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gtzebmhmdt.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkdivcol.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtiqlghuzy.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtzwdtesqh.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtlweqqwbk.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtuxbutpsu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtgiokdcdm.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtjrgftexn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gthuwfidlu.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtfjakixcr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtdetrnsgn.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtqafvdudc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtjewdaeqt.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtmhlbciar.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtfkabeqjo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtuvgjfomg.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gtkdzuespg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtifrxopgp.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gthofmupzc.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gthixfwgea.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtjrbsuimr.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtqcyhodgh.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtoohzlzyv.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gticlqgnqx.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtsazxgnge.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gtijxosssr.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtxbaqfvsk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtwrrulmpl.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtlawumpdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtgsvmwdsa.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtzbdlrmmd.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtbyxmhlym.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtiybyrhcb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtyacsvtfx.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtavjiqcjv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtjxzfdodk.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtdbufujhz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtrpvcfkcw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtofyujocw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtbzuxhlax.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkzfnpriz.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtvemgiqfx.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtamzdzdcs.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gthckcspzt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtlyeyjlni.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtytvurjda.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtdypmhvqs.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtrdvarnln.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtkdjjaqqf.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtzyfsgzkb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtvcoobazn.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gttgoahqvb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtmgocfvqp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gttwnjqsvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtqadihrac.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gthdgizxzu.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtfzzywxic.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtlorcvnql.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtqcuigixk.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gttiyuhlch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtiwydefnm.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtqongddcs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtxmjhntte.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtwsitfvjd.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtzyvnahza.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtdjnvxlyk.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtbwpunkfa.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtsrjcrebb.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtpfbfwqwq.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtdoelojjk.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwckxropq.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtvapgrkqb.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtofpvnery.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtpjpwjpka.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gttdumawjk.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtcuqxoiyp.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gthelaqroo.html


<!-- 参考信息 -->