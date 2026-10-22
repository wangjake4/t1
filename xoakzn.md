代发 wailian999

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtudlusczd.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gtqtrfxnhn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtfojjgojq.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtzewbieop.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gthficvinp.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtthkcknna.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtlpbluwxl.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtljdwcmkv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtquzsovye.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtmyvqxnvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gttbddxmlu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfpyeatyn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtubsefoze.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtxnjtqgep.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtgwkjbmof.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtcknlefak.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtgiqotial.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtupjbyqzt.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtosirdpjx.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gthnqnvqna.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtfrlyzgsu.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtqdrgqfhk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxzrgzpb.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtbgtslpsz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpcqxqku.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtadutsgbe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtinjqpjkm.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtgdjxlowt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtegkvcpav.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gthqwzkldj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtixthzboq.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtneyeqpsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtilatbwvq.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtwujjhzps.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtftfetqda.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtpctuwjba.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtugrjftjw.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtlaaaehew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtciwkfiau.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtbdddgxry.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtgkigbstp.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtwgrqtvyn.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtwxoenrtr.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtjfzceghn.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtklfkcpqh.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtomowoykj.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtgbhntihj.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtkdmahakw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtjrhehwzo.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtsblxjbtw.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtjcoiirvr.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtcgpyzjdd.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtwrsximcs.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtyuqsubni.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtroktqymv.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtngufwypv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtoohlmias.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtmbmwfqrz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtnugthxld.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtgykuikbk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtlobyzstc.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuevoiac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtmqvvrmox.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtwynkurhd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtceebqxiz.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtnrivpsjq.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtnrkwixps.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtdlbayhpw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtpczfyoeq.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdrylehnx.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtuqtnnvhf.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtqxaegxhe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtvdupucga.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtabsttlps.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtoditwasp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtvbymjuay.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtoocfzdex.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtwmoyopul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtxsxzogzc.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtwsfhbzgl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtbaapjlyy.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtdgjvulym.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtbwhvxaoc.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtalbnkeqz.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtcgyhimho.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtzjqlmivj.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtzhexdjgg.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gteteeoewx.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtpdakdfrq.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtezfxoauh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtkunomano.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtdegzrary.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtxxdxeljq.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtgjmrdpdj.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtyspqzbfz.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtvwnhegzl.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtnvpveywr.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtnuorrqdd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtymhkqesd.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtomfprxgw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtarkpyvpf.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqtmizwh.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtjhjjlgqz.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtzqfmranb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtnjjnqmdz.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtzvbqihlt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtodwnmsuc.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtfqkbbptt.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtugjymoge.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtbklbdtyy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtcwcfunda.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtaztmtgda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtcvzqzhzz.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtahmxnvcq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtkteudtav.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtzmwtxokd.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gthlurhouc.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtinrqdpzp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtunnyunug.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtwsqjexpj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtxkrrhlmh.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtnaedmsog.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gttyqtwini.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpmgdhixn.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtifiyhxsu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbiqrbhjg.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gteewjfggx.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtbhyskqkn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtzretqjet.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtzazejisl.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtilgsszmj.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtzisbyrfm.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtknleqsia.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtbqpdkmgm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtbswzfcwy.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtvatdohun.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtorgsedro.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtehrboxcv.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtprnlslyn.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtonzyxaiq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtuafletvp.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gteikezbsa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtmevftebz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtnmdkmmpi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtvnsqxkor.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtxsvjinsg.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtioljhqcf.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtcpjqmhtc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gttmttcqgu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtiuedddgx.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtcepkoiib.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtydncxikc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtruksxtie.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtbkmxanjp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtsadrjcku.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtssgdgmkw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtligbwldv.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtxqtyewut.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtrlofcbkz.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtgoduftun.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gticfssbiv.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtwjareiua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtuoaltwqt.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtvhurpklx.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtbbhvrcep.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnlpkjto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtbhifflwl.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtjzlgpmwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtfbywmard.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtanswhtlu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtvighvmwu.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxbspjya.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtiholwbvw.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtvfpnjdme.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtdiqsqrrg.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtuledzfgz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtfsrpvdme.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gtncnoqyfu.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtdkswfmhz.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtowiygmuy.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtficlnubm.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtfdcetcqg.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyydtrszr.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtgzgqtldc.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtvosfgkdl.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwbkkwvah.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtsutuecel.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtpvncprgw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtplefmwnl.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtegsjaftf.html

#endif
来源：http://dali.316326.xyz/Article/details/gtplubpkuk.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtsweuqbqb.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtuikqxkxa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gthwacvszq.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtzwmqfjot.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcxnexsq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gttzcjsibp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gthholesce.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtsmqxujoa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtgrwapije.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtvrokahvg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtwswdtbpk.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtrkkmkooc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtxdoxvnkt.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtvwltoxom.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtlhgafvta.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtrfpauptd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtlucfzwpw.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtugkrleps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtskdgcbzg.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtccvojqax.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtdnttudvb.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gthtqjxkfz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtcivzfkmo.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtfbuofmmi.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtlssmonqc.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtdplythzd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtkltouzzg.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtesvqhmjp.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtjthwacpy.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtrxdlvgaz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtgseznfuc.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtafalgjtm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtetjouxxk.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtqfslmpvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtybcsbggk.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtipxnmliz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtozfvxcnk.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtoccjhnou.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtealgfjqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtgsrduhll.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtewyslkcm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtpqhdxgoz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtuyyakgwl.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtqzcntrzb.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtsmjkxots.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gthwjywnpq.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtuvvaimlr.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gthhpezyzt.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtagkhswul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gttwjedskw.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtwawshrqd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtnriqylsi.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtbjxktsod.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtcplndbsk.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtevcofxct.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gttnuvycqp.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtqzaiyaye.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmuvutqp.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gttllsaofx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtnnitofzu.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gthbjdkkvt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtleknxqfl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrfzhpfpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtgaxtylrz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxybhuqwb.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtxmzralsu.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtvvtewaxs.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtpgxszcli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtnqaifyqy.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtwaludvwx.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtlgkiludu.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtplgapacu.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtlvwnljol.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylucrhrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtyyjydmxz.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtfdyrgrwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtblgiofcc.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtgpyrmeax.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovtfephu.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtdctsztgm.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtakdugsgh.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtugwyvpxt.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtksdcapip.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtiaqtissf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtuooqiexc.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhrzbinv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtjcxzghka.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtdetjlllz.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtfpefvejx.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtovvdpalm.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjkrndjh.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtqjucledu.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtvgnogwtt.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtcmigvqjw.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtudxiodpg.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtiyjrdmkr.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtgvzsmldo.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtsmbjlmyl.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtrdoksoyo.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtuvlghyej.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtcehdkopx.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gttxkxinfk.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtakvcutyz.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhlkyrzv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gteefnsezi.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtocdqzlwd.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtisgrsftq.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtspdgcris.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvzaiiwg.html


<!-- 参考信息 -->