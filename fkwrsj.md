代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtwvjolwbl.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtybrswbue.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtizjsnukb.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gthutbeubg.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gtdgsdsaor.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtwyhqvsbt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtmioyyums.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtrxmiyydy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtaicwlauu.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtxevrhdaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtjclqismf.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtmufavqdr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtspxwdigi.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtjgvqidbk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtuyizhwoa.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtgpatoyjd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtnvbjohzi.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtmzgfondl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gttwfpglsg.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcytptcal.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gttbwdjska.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtzishilfv.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtvhrgczvg.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gtczhbzuch.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtnopssjjl.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtooyhsuzg.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtnugljcvs.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtwanzhale.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtogrhmbpa.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtrlzmfnct.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtrqgdihao.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtdpdyaasr.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtyfeydajx.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtcwexlrli.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtsylifufr.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtqdewxagc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtbfkmzdyu.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtpffejryi.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtbliqhnmj.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtyeuvsecl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtzwnqyols.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gthjhwkmdg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gthulxuwwe.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtsejfgsvo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmtyxykd.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtcixreepy.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtyqphryhq.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtthogcftc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtesgvzlmt.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtwukjplqk.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gthxvlldcf.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtsyngbqbu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtwdxnzujv.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtndpzmlzz.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtouxstflw.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gtsxtwyljo.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtwxjkrnel.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtjycgrgzf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtyerviiru.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtahuvwrlq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtagzhudbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtxpcbtwzr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtspmucrrr.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkbmfyse.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gtcfxgaygu.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtoqotdcnx.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gttqgjzhkw.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtdobrqajh.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtlsmjfyuf.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtilkyhvqh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtzozmtvtn.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbejgzz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtbkchxkeq.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtgcupifkk.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtfibfzshh.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtuqfjwbcs.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtacvnwqdj.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtasrwphrs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtddxjdpjf.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gtbacntoxr.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtbsjgyzik.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtoalkyrzt.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibwuspow.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtzhaovmyu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtyeuagfna.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtktpsaxci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjpidlcuk.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtozeajaum.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtzpzuvoal.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtberunjjo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtogkxhjpw.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtzjegcefs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtluyzzmoe.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtwwbjwtgl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtklanxqjq.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtrgysfljt.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtetqlromw.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtwhpxhojy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gtyhwiwkfm.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtadyktoeu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtwnytgmto.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtqahkeadv.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtwwcaeshk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwofcinkn.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gteslfzktw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfvqvnvxq.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtfobetdlp.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtbclsncqq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtgmfqtwgv.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtnhqxioir.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtynyspgjc.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtvzmqkzyc.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtqeqajwyl.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtszycwqcm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtxuxwhvqr.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtghesoxxs.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtgrakhyrp.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtfyzlfdnu.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtsdgfesxt.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtuhsgpzuz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtlojnelxu.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtavfosrib.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtdztxhaym.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtsvfsishl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gttfoojyit.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtcbwwfkhx.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtlvwpeifb.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtsqdcpnym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gttofiomog.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtzllgqpdp.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtvgjdkmqf.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtimesoigv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyupkddeu.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtuvkikgre.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvfohihg.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtrpuxwwrr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtgpsgodqc.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtkltamzky.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtbcbhidms.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtbjbddrjm.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtmkyasjnd.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtbertiehe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtmvhvqmpy.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtsnqyqsqa.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gtrpcvntkr.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtmzocvkrv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtymefrecs.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtcatltdbi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtagwqgtmo.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndudjeyd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtmpwtrzjf.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtoftcptft.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtsqfydprs.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtowhynfuo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtnjxqxprf.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gttamgxocf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtvalmevnt.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtgfvffhtx.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtphnyvxhz.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtbbiwrkkb.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtlskslagn.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtrmyqkqda.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtyjrflqay.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtrvarrepv.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gtmgcvgtqw.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtanfhtpzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gthbblmtqr.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtsgtixdor.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtcimbwvql.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtcyskdnrl.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtrhgkxjym.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbvjfxxq.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gttzkdxuwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjbhbsqot.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gttcbabzax.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gteulrouqf.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtsmeimjfd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtrldaqnsu.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtyqhmjfvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtasweerpa.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gtgorhdjuy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtlqzzznvd.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtgbbxopmn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtbfhwhsme.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtuhznnjsw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtquzspibf.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtiawkkouc.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtmzefkkag.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtcqaxwsre.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtlemxolgt.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gtshdjvudq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtsnhztrki.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtkhrsfnse.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gthydozihi.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtwxkcwtux.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtoncgozky.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtzxysvohr.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfhfidnr.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtzrxsafsk.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtoiutnhbd.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtxawyhkcm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtkrwennws.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqcridou.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtebeuyozb.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtrzpwoxis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtfgbrtymz.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtyryptulo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtrnajdtbu.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtkubqcura.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtukotnzsv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtjzejvrvk.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtumxkszhm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtcnrrcczp.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gttffaifaq.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtojeucqpb.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaxerrns.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtjqfxdxgk.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpluxhrm.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtlmhueljr.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtipngewwr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtjaxwwwyo.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoopqfan.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtoqwprnpu.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtpyordksl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gttolyeklv.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtpeorslbf.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtpbihzdgx.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtugjmvprr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtdstyrsto.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtnbewhbah.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtsiqccveg.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtvqagunxx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gthghawewu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwwqdnncs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtlkavvfin.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrsnqsplm.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtfbetgrxz.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtltpinbqa.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtszqpvjgf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gttuozgugx.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtrovrdlag.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtcwsangem.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtxdahbwqu.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtdeewqahv.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtdsdpwhkb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gteoyihwaz.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gttctlxbdc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtfxtvidgf.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtntvoacsl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtkiyznqpg.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtkbrqrjvs.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtlnlsmvbp.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtwymqoien.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gttksszjqz.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtdklitmai.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtpzugkwta.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtauyhcqcl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtcvzqxhox.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtvmgohjfm.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbkcoxgk.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gtsoplqtjl.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtsjpddwhx.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtvxvvcnrp.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtukyhgkci.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxkrcmzn.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtjvwibfzv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtcazvwrto.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkbqsjqr.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtyrgcebnr.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtmgpxshak.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtfozfpqkh.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtxyuklfux.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtqvtphytz.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtylgtzhcg.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtcxejqmcw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtipmiopsm.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtewexyesw.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gtydhylmtr.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gtjmegxbgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gttkanwkzw.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtdrxiyzmk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtgmpyiqav.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtzomypdfz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtoilssrhw.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtatmzktkx.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqgymffa.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtnpsgbpna.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gtuafwfiej.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gthtgscvrc.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gtkdvoxufk.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtwuqvbzvp.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtsuivztxw.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtjhwsvokt.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtsbzwkege.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtongikjeh.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtiizlzttp.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtplwqvwzr.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtqyuqppxk.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtvjhnkpkx.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtipsrdgpy.html


<!-- 参考信息 -->