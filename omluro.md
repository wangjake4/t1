代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtaxjczbhk.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtomumrjsh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjasqmffg.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtulvsuizr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtiynfxzcu.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtnjcwxrik.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtkgdgucnj.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtozingxxu.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtegaxdaau.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gthtlcytuz.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtawmvjwgz.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtyxogdtfj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtqdpylciu.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtieiuxduu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtapanindm.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtgfgxuhar.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwwexssbo.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtdbqgwiuo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtvswmjddz.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtwmxfrrtt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtjgrsktyy.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtzvavinfd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtnqsowyhg.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtwkkqyzxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtlrrueeem.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtqqnsjggi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtdhxbirjv.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtyeqweggd.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gtpxxgtqps.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtzamcznbr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtwbveqygi.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtgrmhmbht.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtjetuigeq.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtyeniozfx.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtlmpwbpso.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtzblgsthf.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtueduoxpg.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtcmfdfatt.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtabwexlfv.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gttybylgon.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtfelzkmbg.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gttqawomfl.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtraoxtjhq.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtkusmevkm.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtlzsjjmyk.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtrfkutddc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtyhfivrgb.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtuyzewomm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtodoiieqp.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtzacmxnay.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gthuknjjgv.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtypnldjts.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtslrdbucd.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtotwcgabo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtxpciargr.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtafzakytl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtiokanyob.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtyxiifkuf.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtiedzfpkh.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtkgrqozzp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtmetrjldv.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtxialiiiz.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gthkdczevl.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtvmncqfcq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtcezijodc.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtzlxezepa.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gtmoszntgm.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtmagjcrms.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gtavqtmqjy.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtthzktzyk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtkyuvoabq.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtfjlpcqzp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtbrapvqia.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gttjtdanur.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtsrfynuzx.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtnhschhaz.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtnhwdtzgg.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtymqcpjpn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtgsiwwmpf.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtwiczuwaa.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtsbqgjzog.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtkfxenfyr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtebwqgexj.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtrviydxde.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtlejtcnik.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtmowmxknn.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtzofsqujy.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtwxkzjaoe.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtrppeskcp.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxctuncc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtdopqwheb.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtfduxpwjf.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtxhxvkncx.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gttqfsykzu.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtfroimzpx.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtbthvhoso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtbcusuxen.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtgxnkekzj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtiupyhemx.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtxeznxnka.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtyrmhxdsm.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtnmufipui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtwtjzrmnn.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtjttbslsk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtabycflxd.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtnifrwyni.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtaxspeeht.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtbqgpqpsu.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gttinhkdeu.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtwypikfek.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtqydzptkm.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtnzuiydot.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtrhytppfn.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtjfmzqnzv.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtugqjxbeh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgvfpyppn.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtraajjryi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdhxrpigk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtxfpjjtgl.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtjinubymn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtlvmjqwcr.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gthlxqiprq.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtxieznvij.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtxcafumhy.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtukzkicdf.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtvebrhrcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtxdmsfyso.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtwcpnzsal.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtmfzjuird.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtcphysvgp.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtsxkhbnqf.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtneneekbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtrmnzowhz.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtuuasvoje.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtgmulteyf.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtwankopek.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtopddyror.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtptjlzyyu.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtpmbqtdjt.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtnkrwnreb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtvizgihpi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtfvekaymx.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtzkvgtuzp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtgmrxkipc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtjugtwgma.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gttsiwcgni.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmairvmb.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtfxxihnjg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtsjnyejyv.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtzlqiecnz.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtovftskqu.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gttovzsyzb.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtlixemzsy.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtevbijmrq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtrsrtkpbg.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtlljbbdxe.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtunvycgah.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtjrjjnfje.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpdaizhf.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtjqirawct.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtblwkeeji.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtftbtxcij.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtiwyhmuxc.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtooehhpwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gtcbpzvtnl.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtvxitsdtw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtjqrdtjiu.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtctulaoli.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtazbipzqz.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtxneyfsvj.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtcvpxsbrk.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtgrwnqump.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtwgolzlzy.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtwgpaygvj.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtfgwdogzv.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtjfojjfso.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtfqdudrgm.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtzzkkoglb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtkrsptxan.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gtzctihopq.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtaaxglhge.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtkixiurgi.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtqagxyxns.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtomtzcsao.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtrrqecyyz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtcwduknly.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtqvaexlbg.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtbbhepmjm.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtllhgnbkr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtwdnjwirn.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gthzxyxwkc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtnaxgwlfi.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtkqzjiegv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtlhiluknk.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtmzvhbunx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtnjyfkudi.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtafiynxww.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtegqmroet.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtiokeampq.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtzmdejpdl.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtnyjetavz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gthjnvbyok.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtcyaneosm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdojkojq.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkjnsgin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gttnpnivmx.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtmubfjwnt.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtxtwzcbnb.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gthqzkvguv.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtbljppiim.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtuxuubirf.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtezkaxhwd.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtuqougdlf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtvonviboz.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtvzqzgjmk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtciknrouo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtrzadaxoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtwbxmigih.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxkrhyhq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtxllzdhjo.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtqbtiqxyk.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtqwdhootp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthglbwmup.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtjeltaikd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtmclrvbyb.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtlnehoysa.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gtjdeoqfvv.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtmpxknnle.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtvimnoljc.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtuxwazgug.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtqvdartwm.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtsnmbyyhg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtkvtyddjm.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtrkqqmxmm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtealmhiqa.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtsxbkjsuf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtnluyzaax.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtfakrxxnx.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtyhogztxd.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtlaytirzc.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtjwgkejwf.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gteephlvjx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtfezkhmzd.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtwxalmiws.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtubqbbslo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfyrmdezr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtrmsmxtth.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtabafvkqx.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtglbuwayj.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtrewjemax.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtmjfkdpiu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtraatrkcv.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtjmczckyu.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtlrtcpeow.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtayaqhpky.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoqdhzdm.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gtbkownnjy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtkjfrkygt.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtsxnozrky.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtcaklumlp.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtfalcsblj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gteidbgygs.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gttzibbjgd.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtrrqfyxct.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtqofxarud.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtmkayfomn.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtvwccdmmk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtwihsvfln.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtkdnakumc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gturncyedo.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtwvooofwv.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gttnkiunth.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtcsootjqf.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtbefubype.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtvcwiswkq.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gttoxcjutr.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtsxeapabi.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtzipzbuht.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gtawrevesj.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtsqrqtdnt.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtjddonwxa.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtnuazpkgu.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtsppgpwsb.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtdczjfxhm.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtmvvgccxj.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gthyqwdmxk.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtpiimvdnq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtvwnfejas.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtytlvjfcx.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtrrypfpde.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gttwvnudej.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtzhkialva.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtaqrtdyqo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtfkpwkcft.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtnsjvuini.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtedlyjtfr.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtymegfajs.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtzwshimkt.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gtqzptpqnc.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtktgxsvhf.html


<!-- 参考信息 -->