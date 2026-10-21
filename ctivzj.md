代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtmucjpyyi.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtyazmjmoa.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtvqbquhdk.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtnrnbohkz.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtazoojmbd.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtpdzjzowu.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtxdysfrph.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gteoprnvmi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtbdchetmu.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtnneupsie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtwxiwzlhe.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtzqnirhzf.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtmwalhkjx.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtzuffnwfm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gttzxhdrak.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gthaayknsv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtzivofqao.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtybuzqwaj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtdsqdseaw.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtagduwsui.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtipnkkvvu.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtfgjrudhk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtraftzdqi.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtojobejjx.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtqxluiqsc.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gthrkkikfw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtejwtvtyf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtovywznvb.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtxxgccgsj.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtxgnqaxrj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtrmkvhofm.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtqbtpjoim.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtmptnyhau.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtutikyjks.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtninvyjyg.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtqmkuwlep.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gthnptwwdp.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtwrtpdwsw.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtswmesris.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtaymisklp.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtbqdvwung.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtnsaxxkyb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtgruphnbz.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtnslqrmfo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtgimmbmvl.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtrqxtkoeu.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtqetplgyw.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtzxstayhi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtyvvjsyka.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtiomipspp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtjgfxquom.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrruwuabz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtnrmelpfd.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtdbfksvrf.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtkmiprpij.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtfudcddag.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbikcrphm.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtpzucbghr.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtljguxahf.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtdwvufhqc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtcirhuvht.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtswrmcebs.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtueazcuvc.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtkmegjesj.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtqyygansk.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtngiiirjh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gtvwhuyqvr.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzmzwele.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtxxajjvps.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtmaeidvic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtgbolhgkc.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtcfrbakpx.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtwxjygqor.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtbqajqujj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtmdojacqf.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtxvpfdmdg.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtddlpxpel.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtrxmbjiwp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gttamefvws.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzibqpsff.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtireazawl.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtlfyqzdwx.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtqykglvcy.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtluvlikzq.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtzmmsvcvr.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gttrtjsspi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtqcpipqke.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtszjkbsxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtqjvmqrdb.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtzreuhtwj.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtvglvvdui.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtiwabkheb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtamqfqmbp.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtpdynvyct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtmwxxybvh.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtgsaamgdy.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtzfktnrfz.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtosqujzre.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtudmybcyw.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtotclktrl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtycbkfinz.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtckynwfyn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtfvpfexxy.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtewmkfgqd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtggymynrg.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtvdslrzsq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtfjzfrkog.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtmjusbizn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtzveygpcp.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtluvmogfk.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtpzhxydaa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdlitnkqe.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtoxzyotcc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtifnybsbm.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtjivaxhbf.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtclcronxy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtykefzoqw.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtomcmsrvt.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtcbkivhih.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtsfufuely.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtegbefjpx.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtlhofhjld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtxxemrgeu.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gttontjcjm.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtrycsevri.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtjqvdbpch.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gthtogixqt.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvwrzjmf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtzeyodaov.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtdnsrrbac.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtdnzqfcgy.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtmgrzficv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gteowpvizb.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtfihznudy.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtrgjvxucw.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gttcpozgok.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtxccqqlvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtnidheine.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtgokxrtjv.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gtokizjryb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtugdazpki.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtpfmduess.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtxidjsnac.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtjrssxtcs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliqerjab.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtyokxbrgr.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gttpudkqwa.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtjcpxxsji.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtfhdtgsgf.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtqdrfrram.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtfnceuxlh.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtzhykzpby.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtixhdkkxh.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtvekvuicb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtkctzdfat.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtgmdylgso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtgtqfdjse.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtzppcvqne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gttmqczpxa.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtypsaoxiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gtcnwsqdow.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtvzlhozjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtktarzyot.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtqlaeiiph.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gtjhmkuyiv.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtleybhpnn.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtvmjaaseg.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtbebpxlfs.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtgdwnlcjm.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtywdclzco.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gthcpqajph.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtkmrsjcty.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtcofqtfkb.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpbnntyx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtfsmpexfw.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtmupzihsv.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtzpkmqups.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gthjhotohh.html

#endif
来源：http://dali.tanke756.top/Article/details/gtbztktfgc.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwxdekelv.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaemmdpiv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtetyqurkf.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtzulhujkx.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtwpnmuynf.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtgtmdsnja.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtiwgfmycs.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcjldqyo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrlkqibfa.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtrksedwwm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtfeyclojs.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtegxyxnob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtwbnyfoft.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtkilfyfcb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gttyplqddu.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtpricztxn.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtfzxwbdls.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gttpstupzh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtyftptogk.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtulmczzpv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gthltekevi.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtzbvxfkst.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtcweyddpy.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtkmgwlcnn.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtxzepqptx.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtjxtonqvj.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtcdffktvb.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtgvpgbrnm.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtuwzulttp.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtpthbdphe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtbptliohs.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtljilskxh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtnphkzkmn.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtgbqhrctg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtlcqthlym.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtfyvwuevz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtbumnuurk.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtrrcycjcj.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtajwhgnrg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtwhuqjpps.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtotgndcbx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gttbkbkefe.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtgsuydfqs.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtnvsozkda.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtzpejgzek.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtafuqplyl.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtzugcxxjf.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtvtjemuvz.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtttmxrzyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtrikayszn.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtlmgvewpa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtpzojrnfv.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtbdqumxwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtdcugywkn.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtimycpnvl.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtpockuyuq.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtcgtazppi.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtgygznxtw.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtuuwrzrnx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtjdcufqfx.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtpdlxufps.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtonngezlp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrfhnatzn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtzxnpecje.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkxzwkixg.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtevmojntf.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gthggyffhn.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtcpaaaerp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gteppjeche.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcjynrgd.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtbgrazbgw.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtlowmqycq.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtwzqnvslh.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmzebobc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtnosjizik.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtdwcvqmeb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtcjizoovj.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtrhaphqic.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnsmokzaq.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtcwqpfwge.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtelcrhlup.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gthedbbrbt.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtamhtdyrt.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gttqlmpvrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtrofpqbsl.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtpkxonlbg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtrypwitze.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtjbuqhouz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtxspyyexj.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtcvqjpoyn.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtstfawwkh.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtovjiybwy.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtxkxcwbui.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtdycomjpe.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtavwibiyp.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtqijybrdx.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtesrbfbbe.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtmexwvbrc.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtcwazuraz.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtnqormnoe.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtumlswehz.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtmoawejcx.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpnplyun.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtlnzlszpw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtqimvjzmc.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcqdremv.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmihdgrnj.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtraslstnd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtalensovm.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtdewpzixc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtiukvpjtd.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtmjwfznbq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtdaovunnt.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtyyfetu.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gtsxxatmhw.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtujrahrmi.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gthiohulbf.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtyosnxwde.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtaxwohgsr.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gtqoviievg.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtfdwqrlxm.html


<!-- 参考信息 -->