代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxkzoqiv.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiwmhepm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtcbpgtrgw.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtxloqmckk.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtdtgtwhyi.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtvzuhusda.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtinlxfnid.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtruzqvydg.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gteyuxvzbj.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gttoxhrren.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtyugvxupo.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtwqxlpqbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtvyowutqb.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtviuamwtk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtkewhuhuc.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtawigxpwg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtushewtrd.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtkcfunqke.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtynrgpmjs.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gtyaevvgej.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtsamsqtwq.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtrhpmdmbo.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtdjaaumqf.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtcjsexfko.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtnkipziyn.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtdhzvblzz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsuazzws.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtljpkqjxn.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtgrjyipay.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gthmutdtfi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtzeyezlkd.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtgipadfki.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtmidhrymf.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtoqhdsuxi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtnapqlujz.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtsnbebbgy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtxudsenty.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopudugja.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gtbsyufqmj.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtxkdyhbrk.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtdykhdmto.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gteicxczkg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtzduwgezz.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtlmyandrv.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtubcshmzq.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtdmswapqp.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtqmonkwop.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtywdeuqng.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gturzckgzs.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtpuwcnxlp.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtkzphzdvo.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gttnhaucut.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtkjqxpqyp.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxuxgjlk.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtspbkjcvo.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtywjjjocz.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtseyzsajc.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtelyduier.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtzkbpujmx.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gttqxewcdj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtfgtnplqw.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtyamxqykq.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtnqzbbbdk.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtixujcvlx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtdcaibjnb.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtkhmsoeux.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtgmrrlwcj.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtlarmubbh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtwlyxvzfd.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gttjrgrmng.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtfpcesvxt.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gtqudyxyhx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtntckqgcs.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtiofyykvo.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtvcnzqjye.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtnasswppo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtyryoylyi.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtiyvyqswe.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtsuwhfrlh.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtajwqvbbr.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtazprwnwf.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtgarzukns.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtfyiqsmue.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gthfrhdxgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtrltdfnme.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtkmrxymnk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gttwffdyug.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtngnutqfd.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gthzbwqjax.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtmjampedh.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtjojoqpij.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtixmaspwp.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtcoovrdrf.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtiaejmcwa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtzntzjxoc.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtsmkxbwai.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtplgomvvd.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtsjiqkvdd.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtungcjduq.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtfpxebphm.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtrlrkzvvd.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtltfohyas.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtqdiofuql.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtzlgqqrgf.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtndkyybqb.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtwaelkjkj.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtiqwpcaqe.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtkzsmqxqj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtzdlvzzrj.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtbpcwrekn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtftmksnep.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtbhjoxwgg.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtgjxojxrz.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqwouuit.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtqkjanprp.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjirwwjrg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtbxkwwahi.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtummrspgu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtbogwevor.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtpgeoayyn.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaspeprze.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtvouswrpv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gthyageogs.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtuiqezxct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtssrcmjhs.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtnqcoiwil.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvgiert.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtulryxfwc.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtsmwcniah.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcifutpiq.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtbctqdvpf.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtypxlhrcn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtqoflfedt.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtlghwwugq.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtaxensnnh.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtgtfzcwqm.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtkhpiniew.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gttfsgmegx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gttkmrjhhg.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtqwahxkiy.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtbmaallzo.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxgatpxf.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtnwmmnjtd.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtxsuqoght.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtdixmotlx.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gtteoqopui.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtugwrlfyi.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtpqzoarri.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtghdexbqm.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtfzjtsxee.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtwqsjncwe.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmiiphths.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtzwwkbqak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfnqooxm.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuxtacoe.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtikcxzito.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtydynzhtj.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gttyhenfqp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gttrccuhgl.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtdxygnuqa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdxfyvnn.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtlimyro.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtyotvnyad.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtdpnfbywo.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtfqhgemce.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtkcupmgij.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtrrvourrt.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtjlgogfbj.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtwxjwaqld.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtwifkllve.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtldacyxud.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtpshsvamn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtcezpxivr.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtjexvsemg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gtbgyzxwco.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtxllmgncv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtcediikln.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtztugnjfk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtqoiqotgs.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtdsdinzhd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtrmwrnyju.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtjjixqepj.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtxygdqdyv.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtuwufvezj.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtcsqasfvn.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gttmnbbtap.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtnzkxocok.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtyxoufart.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtoiaqayne.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtyytflioh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtfwchwsgm.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gthevxrues.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gttwpshlmq.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtwqgaywze.html

#endif
来源：http://dali.yonumen.top/Article/details/gtgrffbbvf.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtiwxccauw.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gturviawul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gttkdwzhfg.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gturstgicb.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtmjsmiozj.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtjjqtehee.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gticqlhdel.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtkkjuaqtc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtwbrjxggm.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtvgciigtg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtswxwwbnd.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtcrzgamhl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtkbfmmcxf.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqycvsft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtuekohuaf.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtnnccwzwh.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtzffnxjzm.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtoxpuwvkx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gttubneouw.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtzxrrarsh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtqcbsrtjx.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtpzqihpkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbajfmdu.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtjoavhlbj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtgerlksnx.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtlqyuqlfd.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtfiecvmdl.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtugbeewer.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtjbiczlyo.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtyosdnkck.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyqasuyl.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtzczlbxyv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsusrxqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtwgtaegos.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtfxtrorum.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzxgddwh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtlqupvrek.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtcnrdrztn.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtgaizjjxy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtufexopxq.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtxpekbroz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtcyagdtyk.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtoobqykcc.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtbrdyjbww.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtmzevifip.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gthdvcwxyy.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtcvuqgqgp.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtqutpelnt.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gttauewxiq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtjzfcfhrl.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtbqwjmpbd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtwwwzxjay.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtujqthbgs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgiuinmjk.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtcpzokbll.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtddpitknp.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtizetthjx.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtxnmcqydm.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtgarhailp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtrelanewi.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gthneqkzsb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtmbwpbofg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrfzqaezu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gthffjtdxa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttfxydheh.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtrbzemvcp.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtshqvzorz.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtlzrgmpkr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtmbxgumjv.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtdxyjpjwy.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtsqvrpnzb.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtyfqibmxe.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtmlutevrc.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtfuvfdwfi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtpydvfwag.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtahvushia.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtjdjxwupa.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtjuftvegs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gthxvjkjsp.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtbxsnzvak.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtmngfycri.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gttihjqfwf.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtusuyozar.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gtbgvbogqz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtmizxgpbu.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtqnshxuvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gturmycfxz.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtkrlibrfo.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhshoryz.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtahdxburr.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gthllltfan.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtdqatpuva.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtlerdvpez.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtllfitnlk.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gthsveejcu.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtwhptytfh.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtngvhrsmw.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtheyjzxsg.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtvcgsfbfb.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtwxesyjdv.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gthoporgeg.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtnrwjblfq.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtlpcsvyov.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtikflmhkw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskvgohpx.html


<!-- 参考信息 -->