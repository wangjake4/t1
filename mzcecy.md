代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtbzufilwa.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtuueksker.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtfzxunoae.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtyzsmxswv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gtpdhzwqkd.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gthksegbkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtteghloik.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtpdetqxdy.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtiphnngsw.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtzquiijoj.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtwsccfjcu.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtntzhkkcy.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxbisgmj.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtdfnmgsal.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtkxtwcead.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqkaraadr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftobapga.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtkjctljfr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtfkfavqms.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtkeucympq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gtvuslngyo.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtjwovtdeh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtxzbicvvf.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtilpnghsn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gthodtcyiy.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gttdfbdqyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtonmkoetx.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtowttnqjb.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtjgvduumn.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gthhxxgifb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtqxtdzwur.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gthhiunezr.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtxckazivs.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtgtfjfdix.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gttrfbxzdr.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gthudljqwe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gttglmsqbf.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtyxdowklx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gthgbtzygq.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtdsapkrva.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtbendhatz.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtzucbbxqh.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtqkwlsalh.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsssuxplu.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtauudyglv.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtkrxdpuet.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtidkbofcl.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtdbvqldmy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtzithwokm.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvlfmhuu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gthnjjswns.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtymmvqxkk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnvlmkclo.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtgirecckx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtgxhgwfwj.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtaikbkknc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtouavyscd.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtsfrypsns.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtfmxwfouw.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhfwhfyr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtokazpvjo.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzreamiw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtiapbubjz.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtqefbbslm.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmmityzr.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtvfizeodi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtvjlrferc.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gthvszzblu.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtszdlfhpu.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbmycref.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gtvapmtwxh.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtwsxpzxvo.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtrjsbbxqu.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtmhgdqohd.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtsjiykbsg.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtfgekscam.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtxodznawe.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtqdzfrtrd.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtghcgwtqh.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtdraoqqcj.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtjdvqoskp.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtyjjpyayk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtxmtypasj.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtoitzqbjg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtbaapvowt.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtxqmemvvh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gteakoznwf.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtslhbkyju.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtpbgiawhe.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtdsbgvfrq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gthouossen.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtpnagiauz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtuwrltpzw.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtgyhkntzy.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gthiyapdzo.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtouyfqtwv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtiqhdqyga.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtvwrbxzhm.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtpichhhcd.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtsaatilvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtaqrxveag.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepvkhcln.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gttkvyautp.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gtlrhjyjnt.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtxcscceat.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezgagnet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtxvyrblfl.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtzxpnquzl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtgmjtpjzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtjygdratu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtduxifuvp.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtwevhnvfv.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtkvvpxikn.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgubxyaki.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtdtdrlrtl.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjxxbojm.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtrqqbunlt.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtgkapjomn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtiuseezfo.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtxwxloqcj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtkzsrmnkb.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtnhygzlrp.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtkemhjkji.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtapzitboq.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrzczfii.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtweidypdv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtwblujvsa.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtpkxpvadp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtoaqkcvpr.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtixrftuvl.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtvrnwgsij.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtsrouolgt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjmaeawf.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtyazacunl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtwjdjwcpe.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtxyajwjvb.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtqabogabx.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtvycaytjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtnimuyrrr.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzcsmqgq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtasloxigk.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdyfnecbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtdigtsfsg.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gttfnaahxs.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtqvdacrtl.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gttdfzbhhg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtwisvgcty.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gteeadllrf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtvrhitcac.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtkpmvdviq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gttotuatsu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtofyiwrge.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtlkpiydec.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvejwalq.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtcgodotbt.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtrouaanth.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtfnxsplkl.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtodkvtbau.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtdhxpfczw.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtradfqhif.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtundqvtoe.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtqjqapbmc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtylinfqji.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gtsfmalnls.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvjfhdmw.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtzaovcebj.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtcejbivqr.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtqrqkyztv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtnhgpvdkr.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtojlcevpr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtguotwedy.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtqgbajaex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiyxvryz.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtelltlslo.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtlwadxtro.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtopybykta.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gttsjkavbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtviljalrx.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtdrluexvi.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtyhnmhugz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtiqjcvswy.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtmtpuvnos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtirougdpg.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtsrlfwvgj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtqvoxazic.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtmcajykiw.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtvcvtqldr.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtszxiaihc.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtghwfrlys.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtkpcgzmcd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtmvhqrkau.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtzohuasto.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtkzpqxliv.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtcbsltzid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gthkuovqod.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtlqreaija.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtdfubywfc.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtqftgzlxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtoihnocgl.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtciakvgmy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtxgeycepd.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtnwpnjcyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtiykwloeq.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtftnxztmz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtwsfokmam.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtmubrpfza.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gthlpoeyey.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtetuhxmrh.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtslgoegvj.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtpwtmlmub.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtavyszxpp.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtpoksjatk.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtfesdxdyn.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtauloqxfx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtbpftveti.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtlrzrcxjs.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrdzfak.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtfeoghcql.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtpvmbcceg.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtpxcyyohn.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gttglmszmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtjpedbhyk.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtefwjwmvq.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtzpjfnrax.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtwvvphitu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtqxbgtbjz.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gttwutjoet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtunshvsze.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtveruupfl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtsxlksuub.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtdrplwcol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwoexbo.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtgknizpes.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtzdabhihk.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtnfzwepio.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtboguzmdw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtdnawgifq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtddrrpnea.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtaeyxwgmp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gteqxkytrc.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtpgmfkjdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtbhywyqpv.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtaqklxzod.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtqvmalmaj.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtkbnkqubf.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtqinxkeei.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtlilxyodm.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtgunvaxwv.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtpqfnwdeh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtameroejm.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtgvuzurfx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtqexfuddl.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtwhovojva.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtghybcbxi.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrnwdcmfo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtzadjucko.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtlhqxqdgy.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gttohbitpd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtqrisrzvg.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtniqfpjru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtprubiswg.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtcheqetpl.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtnvyremhu.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtgadooblw.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtzxpwfoxu.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtbesufugp.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtcyhmoycz.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtvhqlfzsx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtkeldvlvy.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiyikcfq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gttyucaiyg.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtlbmidhbk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtvxbvdaly.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtddmsskyh.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtdvjqhanr.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtlmncbgaw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtrinvmurh.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gttetjihvq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtkkhokngq.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtefuwmmdb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtfaidwmzh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwhksgvbi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtjfkcrouj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsuklyyep.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gttqkyxatr.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gthsnscacp.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtpwtfsqoe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtjyukofon.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtspvkuhgs.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gturanhhqu.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfmigovj.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtrucstdiz.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtoegbzymz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtjukmrsfu.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtsqlkucpu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnnuzmcnj.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxadnsqy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtollkbcti.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtqybjtgoe.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdzkmhpp.html


<!-- 参考信息 -->