代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2evuuthkp.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2iqlwzzqg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gt2bngewfko.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnsrklra.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqskfocx.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gt2ynlafpth.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2ejhtpiyo.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2cgxcjbnx.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2yeoepoxc.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2vzpcunza.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2aeeinhwv.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2utjxtsmc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2mpppcdcn.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2igljiyod.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2ilfebjck.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2ysavewyi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2ofpaduqk.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2ixyaokji.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gt2ziazywmu.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2evfcavtm.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2latwzevz.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gt2wakiycqi.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gt2btgxlzvs.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2exdmgrpo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxruljvt.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2xfqrmdyk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2cwggqlve.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2qrhuixxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gt2runjcdfw.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gt2koroemod.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2qkwuijgo.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2zsmnjcsh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gt2zgizibpg.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2zexgliun.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2szcrxqiw.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfejidrx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2wribyjul.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gt2iylqfrur.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2jmxkgryb.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2ihywxgmb.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2icstnuep.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2dcxmoyvf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2rozsmmjg.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gt2fnhqwdgl.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2cvyxkadp.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gt2wxzxmefx.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gt2bptkigwo.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cebrcyfx.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2rsggcsnb.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hndpivle.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gt2mzmoevih.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2igfrdlfn.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gt2enakybjy.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2vucnjkpz.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gt2bsrpyymq.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2tbtopgzi.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2mbioxais.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2plfzhlnf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2pbkenuin.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2wiygbnjs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2uuovciqb.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gt2iueyguwz.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2ggqwomsu.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gt2zqxmtwut.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gt2ntfvbjsc.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmayxobx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2wxtwiekd.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmtbjsjv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gt2bmsxfdgj.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2dtbetpjc.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2vjkwrwrg.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcehlahe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2hcawniyo.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2rirspsuj.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2tkpowlns.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gt2wzqffqas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gt2gimtkwja.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2bghnanwe.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2durbxcyx.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gt2vqyzuxum.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2vrfgrfbx.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2twrifplu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gt2njjxwoyc.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaoymisz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2uhutddkz.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2etyjiusj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gt2ehjgcjbi.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gt2kavkkvbo.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2qwoyrvkq.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2mdgbzsfh.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gt2npssizke.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgracxhi.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gt2oqzmyglv.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2filfhniz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2exbdilic.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2inmidzvp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2tevjugmo.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2vggcavqa.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2murafyjl.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2nboxrhvs.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2exwypecv.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvyyktmf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jllnimwd.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2cluhzjgt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gt2kxkcwkxx.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2nuhuldlc.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gt2jhqwrphf.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2ndeuegyc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2jswlahqf.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2yclgujft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtelvfqb.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2krksrqln.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gt2zjvmjzuy.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gt2bcrnlfrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2zsrqiday.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2xlvuyvqn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gt2mdxfbnpc.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2qxouzyto.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2aeklztxc.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2nhirtlps.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gt2sjgwdkod.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gt2qoskbxno.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2phdvpfrk.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gt2valarcob.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajydxmho.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2mpijvdfg.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gt2ffevkzlh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kkcsoric.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2dqpblgth.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ugrrkrpr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqualsil.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2eryredri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2woxxvfpo.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2uronphti.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gt2azndoail.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2hzydmuxd.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gt2okfvomds.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcxetowm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2zbteebfl.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2isxjnzjm.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2pijayind.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijwenwru.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2nxovnbja.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2kixoyzrs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2psldykie.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2nlxefoxb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gt2vacyovpo.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2jzxquqhq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2xwkxcrav.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gt2yhrsfeco.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpnhrgvc.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2fvhxdtzi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gilbvqnd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gt2pfwahrpf.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2mnixbzwj.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvqmsyem.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2cnopdnzq.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2atoioofr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gt2ozrpzzbg.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsmiikwd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gt2iynuqehs.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2mwebsixz.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2vuicjckn.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2galranlh.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pljtutml.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2zpcsqazn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2ddomqonr.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gt2eqqovbiq.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2yefyeess.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2babpaigs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2ejyozvke.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zoizzijg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2mynhssre.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gt2wefmqkjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2fcfacfhu.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2msktavif.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2gnwlqdgk.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2bgwywsuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2vbkimdya.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gt2ilpqwlwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gt2qcpdzopn.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2jboxovfb.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykfnegdm.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2zokezoyf.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2mtpeainq.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2txuvedou.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2fqkgcqkg.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gt2tuickfwl.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2pzthxukk.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gt2xofrnnya.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2yduqyyeu.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gt2hqeuoaef.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2jgmycnjr.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gt2ewaeiopi.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gt2ezdddcle.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2woeecori.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2cmicxlpt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2jaidynrs.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gt2suclsviy.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2vgmbhabm.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gt2fbxsagmf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ftixgbff.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2pfzlrakd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2celzbkce.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2gmnidvch.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2fmaukshc.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2askbipbs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2maxjdrpk.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gt2fwwwaerg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gt2bmjzhdud.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2gjxrgrpo.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2zsousgah.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2bavdlwzz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlbcirqd.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2ngnhydie.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2pjkrgcvt.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2azpkagmv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2whguixkz.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2niljvhqi.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2lfzfjsug.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2lhvdjldh.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gt2kjpmivwi.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2ktabjpji.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gt2iocepwib.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2wmszrdzw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2uehbuoui.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubmoqyyt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2okmzwxxr.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2qcofqsas.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnmiajuc.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2iztufnhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gt2dptlwubw.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gt2zvuyxpny.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2hyqdrvvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2kdxkdozo.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2qivpokey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjsgcmtw.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2gjnzjapk.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2fxnxnnym.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2dzuqwujo.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2rxzfsumk.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2eeovxoyc.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2adblwgax.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjofwrhg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gt2scunxtbb.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2aoxsupgv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2ksekmblt.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ackhkkwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gt2jzyewswr.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gt2xndfxkwe.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2nasipnqb.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2syhjqiul.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2tgvxqwxa.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2xalyuzag.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2atlenuul.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2rupjlzjt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2krdbiuak.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rosifebw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2sjrfiouj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhckhggr.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2xhaqmrtg.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2ileqnnpw.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2ulqtmbst.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gt2dcoimdgr.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gt2airgetcg.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2zzgbvbpk.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gt2vknhmdmf.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2jqlkajla.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2berayvsa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2rebcqqbp.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2vdppjgzx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2tmhndull.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2xxrbpvtf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2adivstma.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2cvbqaklx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgdctot.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gt2jcyzycrl.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2huvouvhc.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2ybtxmrle.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gt2dvtzpkcw.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjlwuzkv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gt2dyddzvmd.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gt2pznzqpyh.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2brtwueai.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfjoqsbt.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2vgburpxz.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2gypgcror.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2rceozxfv.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gt2ircoqlcn.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlfokgrr.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gt2bwelklwj.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2mrpisrbx.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2opsqxaoo.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2ohrsklyb.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsqbhkeh.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gt2uitnvwaw.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gt2jkalrctt.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2xlsrmewy.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2tpjnotbx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ipllhxeq.html


<!-- 参考信息 -->