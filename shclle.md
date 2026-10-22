代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtrvnxjcmy.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtxokvtopq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gtxetzynug.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtizlwhtcp.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtmtbofmqz.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtjsqtxtyr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtpdisskgg.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtszhpmwcp.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gtpuewfhoj.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtvaqrripd.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtwuwniasm.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtfagpxtld.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtmothayhs.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtidljpczp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtumdndlrt.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtjowxywdr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gttdzohlcq.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrzmnosg.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtpnvgqipt.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtdfiwbyxu.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtlvcedhxl.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtialmqlqk.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtviuyrhhd.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gthlrksefv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtvewfvapf.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtbjamfeej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtqofsndce.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtoqnmlydq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmnikrwsf.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gthgfjdcnk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtauelkdnu.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtovolwezo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtnnehnztm.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtyfvxdlhh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtaheneyaj.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtvvtfinbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtlzsgqtax.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtorkfyevm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtbvexeufo.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtpvkowkvv.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtxmyfynig.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtzfpbbewi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtqbeznlve.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gtzirmrlqe.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtmkmxnqfh.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtgfzfyjmo.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtglppyynw.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtxgssapgi.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtnlodympn.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtucpcoipk.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytmipuzw.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtfbhmhzgn.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gthlaeznhu.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gtrahbvtqs.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtrvnehebw.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtfnflpbta.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtispvjhsr.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtspctzvzf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtpdijhtcy.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtzjarhqqw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gthokuyfxy.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtfqfxukgy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtfagciqtg.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtjywjmrhy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtyxejjsua.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtmijsifyq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtzrjfqpbr.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtykzvklvl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtexcjezsb.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtdimrzgxg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtfectkgky.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtshxgbvst.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvdhwjsf.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtmbcwwtds.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtzaiitjqx.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtwjiynfja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gtmzpokder.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlrqmdlo.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtsdfmycku.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtgfgoftfb.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtnnjjicxs.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtcgmgrjhi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtkhikgnag.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtlsbybzcu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtcfktbqnp.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gttbfayxof.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gteimexgzw.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gttmhkhuaa.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gthixjdktq.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtfdxkljjw.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gthdpjiirx.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gttwnqmvxi.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gteuthjvfu.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtyqahsfzd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtaebzgvjo.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtpwxbjfcr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtpfskantn.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtacwklmfi.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtmownymzx.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gttmfnyfxd.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjzsasjt.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtdezvhtup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtedsnvidd.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtqswyhvaa.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoykxrsv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtawntqbgi.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtmqbybtld.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gttxxxjbjc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gthxtpsebb.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtmcogmvjb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtgvphcmwb.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtqyiqlihs.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtdckxjwcc.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhjmrxfa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtpzcdupgd.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtdrifbglf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklxhwake.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gthywsvotp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtvzaczyih.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gteexrqlqu.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtuhptlpoe.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuqjhomm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtjzixxdlu.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtbbyrzyui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzvdpqij.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtugxfpgnt.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gttuxhvvqn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwbuckqpo.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtsjzguznz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqloqcbbm.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gtggyalzjv.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtqexuvdjq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtypqhoaaj.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtzxlqtjsk.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtapnuiwwn.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtghgcuane.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtxbljdyjp.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtavlqktgp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gtkfcfhgln.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtngxwmzcl.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtjmrtfpzs.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjuwenaol.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxandaiek.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtjzjrzhsv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtcvodqwyd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtycwjsjka.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtugabwrkn.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufnlrwig.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtuqpafxxb.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtjycwarbo.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtdqzvnuul.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtwrpvyomx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtjjlfuwqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gthrfabxwf.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtobdxfnct.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtdjnvhqmm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gteqjgngqn.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtqffmpgoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtqijyezeo.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtfwqajquc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtqygdapxd.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtsurfmgtp.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtrpsgerqb.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtdppychkj.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwlvfwz.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtmjsjptwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtnczmhpor.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtxxsilyrq.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gttvezrozz.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtjisjgzny.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtrovifsce.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtgexnddeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtrpaatoed.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtsuvhbqmj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gthjcfbvow.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtmybxxpki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtylrfngly.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gthzcmecfr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxxpbldq.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtmfbaldgz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtacuovitg.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtwxijgjfh.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtdoxessnr.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtxwiktjai.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtchlprqbg.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtsolxyzqs.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtvybokhym.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtmrzdsmpx.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzasdtzh.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtinyxagvf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtqfazumdf.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtsyxpryxg.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtkfkkjhbn.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtcbqmxhlh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtjissznpb.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtwxdeageq.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtodfoeuej.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtjmsrjndk.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtqlzfaasg.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtysnmnlls.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtktmezdfd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtkjynpxyv.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gterzklqsa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtaayzggaz.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtbhbvdxkl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtagpnryst.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtvdcykdht.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gthdtpzapz.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtgqplpzxv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtmtvtqzut.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtpzqdvwly.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtnjshtmkq.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtmuxtnsad.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtkcbegqkt.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtjvgcppyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtpzsoaosh.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqdopyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtyvyqcucw.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtziicqmhz.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtzpsluyvg.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtohpnlxmg.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtxwmfooks.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gttsufxnrp.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtxrakxijo.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtykzcqsjk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtqeymycoc.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtgwyrzwqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtxkcddpdj.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlejflhwv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gttxuabprq.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtojyosjvi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtndwttnhz.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtuxqbfzts.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtdluycyre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtrzoimmpr.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtsetuczdj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtnzqgukqx.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtyifekkyt.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtrlrwchrn.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtqvwqvawl.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtpubwjsez.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtzybhfrex.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiiaynta.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnctvqycj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtpmascxgu.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtqmmtcrxt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gtuumtagpf.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeqhdidd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtgjcrnsgc.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtbhhsqesq.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtjsrvhorn.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtczhqhxkj.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtjjshvrwa.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtdvxbhflm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtlwairwmr.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gthsdsuwwg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtisvzzmce.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmszpwyia.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtnmnayhnp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuqfaquow.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtitdfjeeg.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtfljpmhgl.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtbsyygyra.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtcrjpvvbp.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtczubimti.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gteikkeuha.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmbcaeol.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuequbczd.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtrhjsnann.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtfakqkgzv.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtbavfjirk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtvvqrnegl.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtspfannnh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gthoeilkpi.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtqdocqgpu.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtkwxtbzux.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqvcufbwp.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtlknxczbl.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtvygigbxm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtibdpbfyn.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gttgseyhrv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtpzaivzgt.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtccyuuypa.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtlnqdqqey.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxykmeiw.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtfkhpaowt.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtlbeatwii.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtjalakfxv.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtxhcponto.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtuofmjffm.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtrezlnedg.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtbhsrskyq.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtpswbqvbl.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtmknttpdx.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gteskdplzv.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtnmvmuhsp.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtwoqubmxo.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtakqvbydc.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbcveyvr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtilrylqgt.html


<!-- 参考信息 -->