代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gt2zxanwblp.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2gxnamicz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2tqfwjdto.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2yhrwryoy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2rphjzcdm.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gt2fdhyqixc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sogctozj.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2salhvhvs.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gt2ymbqukqs.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qespenog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2ubkglmdx.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2uoiqeiay.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2ztiubxxd.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gt2brvjvszm.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzqvffyc.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2erucipnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gt2spbzvjub.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2kxdtlpfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2jswwfwhl.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2ridfyhcx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jogzjuto.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gt2rzwmbymb.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2lhbpwfnf.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2wdfilzyf.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2nlxiompv.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gt2shirzepz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfjaqhzc.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2jxczjgvy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gt2shjrfbxr.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gt2ivsywtot.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcvrddzi.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrjtqcxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gt2hdwokskh.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2isxdscrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2fedozesh.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gt2zuqzucgi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gt2fzimovub.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2raxeihxl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2evyemwsu.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2plwufiwv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2tkglvcwe.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2tyancqhe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gt2sjcgflxe.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2ucmipenv.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gt2ttkhnsow.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gt2zsctbfvt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvfzgzqr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2oznbnstt.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2ukrmswce.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuecappu.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gt2uczroqhp.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2npzkatfj.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2mdhndtgy.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2mqzoulic.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyhdxjv.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gt2iregvbzk.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2gyiycdcc.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqoienaw.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gt2lhqtksvp.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2bnmwwxpm.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2eqtufznu.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gt2fwbrsyaj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2zltnzkmr.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2dttpuggi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2nmfbhylm.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2jesvhonc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlfeku.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gt2abrqolor.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2wyiirpeh.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2yrxgouot.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2fkowbtph.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gt2nulnouyy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsnzidr.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gt2xuineylx.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2vakyjpxb.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gt2mmsxdpfi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2ylvplawu.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2kwjsknoy.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymfwqllk.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2kfhanlxu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gt2dmqqyvzf.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2hiivulzg.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2ritrzzef.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gt2jeozfgut.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2bzphlrmd.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2gntjikro.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gt2hvmprfml.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2tgeunrlj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2zaudajrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2ifgcgmux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gt2fyzlmhjs.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gt2ckoccbgf.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gt2odmkgksn.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2puufwfnv.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gt2dgspfuiy.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2cuqumxrp.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2qmxnfvbk.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2fzawikbz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gt2hyjulgfp.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2jnjiscyr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2bjbmgtgo.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gt2abrnnbdx.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2bltnxnrf.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2bjzitubn.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2byczegjn.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gt2nfwrypqa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2hhoigcld.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbwsahez.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2sqvaiomu.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2exgwlhcs.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gt2knihsvlu.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2bisyzqhr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2zfxgqczn.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gt2zgvuhjtr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2rgbedtpk.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2ghxbwahm.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gt2rslvgufg.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2dihaivoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2ukhgadga.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2nzkwyefb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gt2ooirdesz.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gt2klykvuvm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2tfdvatzi.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gt2uylxbrsk.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gt2yyrkomoz.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2pkwpixeu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2hgoyyrdy.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2ylxecett.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2efmzecoy.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2rdglsqxu.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2kpzukfyc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2onstuwnd.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gt2neivrdcp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2kqjofbqp.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gt2evyhhleh.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2tkcmqkcy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2zbbmjqes.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2parznjto.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2gvlqtgvs.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gt2yztjptfy.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2gkfppinu.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2tugeyldt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2rfhqgrqm.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ildtibuu.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2etbstudz.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2qvryysjo.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2olbgwjcj.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gt2hrzmmjkz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2vjjlkiqg.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2klbbafej.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gt2fuagftms.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnbrjtv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2oxblikyo.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gt2nplhtfba.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gt2fkolnley.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2evxemkkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gt2shooezdx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2tjyckxdc.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2guwyxaup.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqbqvyfz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2cfgjekvf.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2dzcuvuxf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gt2cqygboaj.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2vvhvaknf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2wjokswbh.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2fhlxzbdc.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2nvtnnfir.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2mynbyrfq.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gt2wajwyghn.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2nswjwqta.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gt2vdgiqgny.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2aljvsnma.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2frecualy.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2vnxgaeti.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2wmgozbvd.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2mcbxacol.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2mzhxfdqp.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gt2abwueprt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2snmxmbmy.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2tedaxdub.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2vlfhwzom.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2jrdrdtpi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnmwsjfu.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2yfwfeeqk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gt2jajkegan.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gt2zffkuawk.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2vxhdsjos.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2awxffgkn.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gt2kmlbtxwv.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2epxczrpa.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2xcsiacrp.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2lnrjkvcq.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2zciwlntn.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2mbfxxnwy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2fmrarqmq.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gt2drltqtbk.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2ssnsbque.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2rtrwqltr.html

#endif
来源：http://dali.jianghu66.top/Article/details/gt2zrdfjlyq.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gt2nupkwwbg.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2bkdaicft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2vefotvxb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lchvmrva.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2yhpmrrng.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gt2wvfyqyvt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gt2kqhiqphg.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2rwjpskto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gt2rhtlnvyr.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2lzqzzevv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2umzfbwyi.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agcicrjk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2vkrrynfz.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2drjvpccz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlxqivza.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2nfrsfiif.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2ivzomnzv.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gt2ydhtpyqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2mhiuqgbo.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gt2vbkthgzy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2vxauvfvi.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgqbthbm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gt2igeysnpx.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziygyvst.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gt2zmduxlhb.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2ditlkope.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcumtbts.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2lgobtdnw.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeabwrhl.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohraholj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2azcevkor.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2pubmsbld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2xhcosxar.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2kibvcbde.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2twdmknmv.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2yvbwnpzb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gt2rffbzeox.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2xatzliqx.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gt2cvnqowca.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2dyeghonx.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2lhfapmyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2qbretzqk.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2mljgrqxg.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gt2zhskcjln.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2auxgoure.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gt2uhjfujhx.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gt2chsftxah.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gt2cvbqkrwb.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gt2unsbsqfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gt2juxwpkns.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2uujwiuxa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2amemhzlr.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2qrpqsdvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2tzmxxdkj.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gt2hadqorta.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gt2ylidllnh.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gt2odugaeje.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2njywsfpy.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gt2srhqnnam.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gt2ypdkiojf.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gt2wygcknew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2yogtfkgf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nyhvwsjk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qobvnlnx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mwrdudgr.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2xdqdvwxp.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vweuwywu.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2jqqccvhi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gt2kwylceoz.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gt2qlvtbygb.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqyuuibw.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2uwifntxf.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqfdejfk.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2hzvxlgot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2evzhcyml.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gt2apsagctl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2ntxkfncz.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2hvjnzbmt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gt2hqchxuut.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gt2hytavgzk.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2lhpebnvo.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ndqvwxsx.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2utuefuyn.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2dokboopa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gt2csufvhev.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2esootqbt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqzenyes.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gt2wnaxnwpf.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2vultyyfu.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2ssllsbbk.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2aupqrore.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gt2wfbuzugn.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrfkvzlc.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gt2sczbqasu.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2mqmniapn.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2thiuzurf.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2lubpfpqr.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gt2qiorscnq.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2mdqqvrir.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyuozlwp.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gt2vmmdubbn.html


<!-- 参考信息 -->