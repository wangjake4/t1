代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxamqixyw.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtmoywqgpp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutumqycq.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtdyahplrd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidppsirc.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtosfxzzpi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtswmbryxn.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtfewsvimc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gthhvfsxoh.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gtlbudgzkk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gttbbnyyok.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtbplhhrfr.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gthqwxzede.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtmkaevpik.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtazyueych.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtbinogatq.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtstitzcob.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtoyfitnvw.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtcwsdmdsq.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtbgiigpps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtkpryuvfu.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtrzhrsaev.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtagtipeac.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtsjezcxnd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtjnklbbsz.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtalmukorf.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtakiryomr.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfxunvji.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtptycufuq.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtkssbarvo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gttvhqhngq.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtnackflkz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtaedxglfk.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtbmawitkb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtgpkthfnv.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtyrpmbvrx.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmfsdgdmn.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtkykakagc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtqourdqwa.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtoeatiyly.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtkzomubct.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtbgkaqdbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gttizatpsy.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtmimiuodx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtpptmrych.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtunzolizl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gtcocsflsl.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtpwizrhaa.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gthleyciyd.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtmbygnklo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtxsbiggrg.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtieiammsr.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtorjwlkgq.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtkgicwdry.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtihrxdgtr.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtfreygubn.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtkcdqmzeb.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtijtumygc.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtavqndnml.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtububihpz.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtfbopltvn.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjkhghgh.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtaclfshfr.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtdjkjrcbd.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gteehkwgic.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtqoihvpuk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtvcyjicdj.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtrquddmbu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtbssobebw.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gteanotcja.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtnkhzdjwt.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtdvinivny.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtbwsztvye.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtbrrmrqyr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtsrstxfbn.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtychhjhzq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtthpfaprg.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveflulza.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtickygjit.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gttsgpxhzs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtxckddwpp.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtfswmfwws.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gtqzbalyev.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtlevaytgk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtjytafusm.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtfsgaqzhh.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtcnhioxpe.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtgoscmieh.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtrfqquwhz.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtecamqjzq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtoagcfcnq.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtgzusvmhd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gtebebjfbv.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkfdblfxo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtgmmfgbgo.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtitdhtkbx.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtrklkpcrl.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtbdzyqfoz.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtrshufpyr.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtzffllzri.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtygvvoobw.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtbdxfvqak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtiukjjxdt.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gthbqkrxak.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtniykdebs.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtoujhcabb.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtkheldfll.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gthybcnatg.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtrmhgetxt.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtcsgsphbb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtmzvxneeq.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtjjxllkiy.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtzdswbwmh.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtydasmlli.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtphizbhml.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkebprtsq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtgiwasxgs.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtulsxawgi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtvkntssmy.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gteibvhszj.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtgzxaqbrx.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtdotxzczr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtreaykrug.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtpeswjvkc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtzrseecfl.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtelkjydyt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtkkdpezkp.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtkypkvzor.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtumipifro.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtwxtvnhxz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gttvxdpqvm.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtevqfhiai.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gthnilqewj.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtqqrxwpsf.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtzpuhdstj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsvjomvnj.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gthggfyxmo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyyhadxsh.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtmungbapi.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtgjccbtrl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtfvqcvejg.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gttqcechcw.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpbqonzd.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtifmbhtge.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtbayhdaws.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxjngrsg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtehnvkdtk.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtuekudpil.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtancpdqhz.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtvglxjsxo.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtnxabmsxr.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtcwkerczr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtjpuujqfs.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtsixtzbij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtoudqcrzn.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtyjqbclqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdbzsmld.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtlxhftqjv.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrszhofd.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtkdreztmd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gthdivypov.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtdgiwilge.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtsnarkxdp.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtrkqcdzig.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtrbqvowyr.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtuwthstty.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtrfwsmbmw.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtmdyrmvst.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtnepdncag.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtyifymsnw.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtyfvidegi.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gticqxzuzl.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtufxhhehj.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtkeerwjbq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtmmokptkd.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtausccmeb.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtrmnfieum.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtpkanveqm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtyqwlucvj.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gthyunhfft.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtfhoyqnaz.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtcpnkbdxf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtjiowwwak.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtmrfgynsz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtbvtlmxfb.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtpvgxyyrv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtabdhcdgj.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtxblvgbhm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtscndudia.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtwtidjtrd.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gteixilcxf.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtnofyinpx.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtaxdqzjpv.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtzaemomuz.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtijzikzsn.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtnancefdz.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwigxrutf.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtggweflsd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtfdcrrtzn.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtipykmnws.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtlwzekjch.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtjudmrpug.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtqbuohosm.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtqnxelgrg.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtvlwnoaiq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtsjevpsan.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtondasrqc.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtyqdijrkn.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtugknqfsq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gteyooigeu.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfqobdrg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gteldhumqf.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtyqdrxern.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtjfbyhtii.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtsdsyfuqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtajhndoex.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtnqkplcvx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtupedfecb.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtdfvqxxxr.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtodgnvdou.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtvzjbmafj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtngdmheem.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtbcheirns.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtbhvgfaxw.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhjwsitp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtsbonhsqr.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gthmebjuir.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtjbjyyvey.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gttqawxyqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtfesqvyjx.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtqxuxcsaf.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtswhvmffd.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloseyqop.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtrqzwcdru.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gttcwmqmfk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtstbdqqpm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtfzzkhexd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtqzovvmjo.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtpurnfmou.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtptmljgbh.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtlkaofogt.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtdturrjxd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtteusyrdh.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gttqgjkyae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtvrngqrtg.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtcavtodzj.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtaqocnxwm.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtgupqpllr.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtvsxmveus.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtdfxrffxg.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtunnrboro.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtjaghunlj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtaacifusd.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtrfiuzfta.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuimqurtc.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqohgvxd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtumodvhdt.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtmvxmdsta.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtgkodhpxq.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtjcahgcve.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtjjyoyzax.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtkhswadtj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtmrbuzpqx.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtlfrdpavt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtgdtrxkyd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtexivweot.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtfasokfkh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthyajusce.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtvjmzexcn.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtubirwbok.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtqiqqmpwz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtdfwrpasw.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtdzapnccu.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtjaqyobfr.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtahfhbjca.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtsurookns.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtkjcwdyyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtduldmegc.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtsdjxmetw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtwvpxolih.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gtideiidlr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtalqaount.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtwpafzqgj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtyvfazgiz.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtzauwbxto.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtujmtogdd.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtpvgxxkqa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtwvkbcafw.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtlsvmjhgg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtlbcfgvid.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtilmfqsgj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gturiewltw.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtvsjnxzyx.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtrcvgobee.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtqebkonjh.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtzpoagvqh.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtxguurcfu.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gthofpragc.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtrjgyqniu.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtdxcidcdg.html


<!-- 参考信息 -->