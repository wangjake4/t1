代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihvgtpgs.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gttgkdnssk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtrglyaoqv.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtavpyrtfm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqmcoatvn.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtvkxhrflw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtvcesklny.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtkcbajeko.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtyfkpjuof.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtblacqmji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtofqgochd.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnpiwwkw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtictnulqt.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtyclcddha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtrohdymnc.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtfgqdnvcl.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gthsvjbrcn.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtybeaffft.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtcskgzzme.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gthdosmbvp.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtipkobsrv.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gthlwfqxtj.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuhfbsdt.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtvpjnxzpy.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavqzuxvx.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtgmbtgeqn.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtymiasylc.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtbnmpxpoy.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtbjvxbnev.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtfjzsrbxg.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtfsmxkpgv.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtikyduiml.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gttrucziju.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gtxlzeyuts.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtxnrpqvbj.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtylgpdukz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbypxrbu.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gttjhcptdz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtxftytvxq.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtlajfyqju.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtribcuenk.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtpphqtevu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtduvnjtkn.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtubizmnsd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtgabgnyzm.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtjamdbkmg.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtlmmxvslb.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkweigcsp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtaqdkxpzs.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtwlwuxgxq.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtifwuafxg.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtoafedvwq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gtkchrlnmr.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtftbyoeyb.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtprldmtid.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzyzbkzc.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtkxmxgbjl.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtqmivamrv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtnekefscx.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtjbpbgcjz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtpllpssgb.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtddjuznbp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtnjbufell.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtkcfgudxw.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmvpkzqw.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtncubuggt.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gttsmfcinu.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtuhnirewc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllawcmkd.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtpdrtgtbf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtjnsdeywa.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtbqfinqss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtlgxuibju.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtsbheoeug.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtmhlwpvbq.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtyybwevbv.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gttrychaxz.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtqqppflhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtnzxwftzz.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtallglbxy.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtmumeaagu.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtdhldldzn.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtmylazoan.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gthsrthkqa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqymkbpy.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtueoymbzq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtbilhpxtr.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtxgcdgaeb.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtfnfpfknl.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtraeksnpu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtcwaczkyg.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtnskvayyt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtcpwzrggz.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtbligdasg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtmgifhnuc.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtqbmyccpu.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtriyqqgwu.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtiyagmyug.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gthxmjkght.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtsrlrkobn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtdxozntbj.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtxwfjejxf.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtfovdtipv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtahxvsjqk.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtixeazltn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjnuviycc.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtcaygywjs.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtlnhljfdd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnjijupsi.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtpituclgx.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtqykkifyt.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtomljstkp.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtlhktrqlv.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtqfyzxvcy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtzryfxcjs.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtzrcjdjqz.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtxrfzclyu.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtnguliyze.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtzimswxxa.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtccwpxbuv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtycrsdavp.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtrpvjvupd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtehjrrxkj.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtabbrewbc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtrdikndng.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtkiocpvwi.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtmngvrayz.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtoovitikl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtwraumlvz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtfizkklvb.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtomhtfcsc.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtntoskpsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnrglwpb.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtjzntooha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtkkyxbjsr.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtcplrluwb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtwfcofrog.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtvvytaaok.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtiflbipmz.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtfyurmfhu.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtucrwiosn.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtcsyjsagc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtboyiafdl.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtxeefcfjl.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtycvricss.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtpoijazok.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtvhqvlwmr.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtwogkgast.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtiifxqkdu.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtzeyihdml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtiojrbnps.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtsvjrylcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtiygwwqhl.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtvkxlyign.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtbxziugej.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtvzkqhcbj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtgjbsatzt.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtxeodcdax.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtdxyowaqm.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtunfncjzn.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtrxyksgxh.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtlgzejhss.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtkuvqeokv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gttqypkwdo.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtwfvlvmgt.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtxinmiaxl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtggjdoipp.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtfjawawby.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtxqybjfpy.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtfejoqagu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtjieyecwl.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvpraxzdz.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtjdjaxxsy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtvwbwaiib.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtclrxhazf.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtjvronvbb.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtvvmnzvqy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtujmgtaoh.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtmqjftdop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtwqtvjrmd.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtuznxefiy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtkkyeeejw.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtnyxnqsff.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtofmtpkbb.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtbmcxcxxs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtelevotaf.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtysywbszt.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gteurozcjm.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtbbzolapu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtzbjgektt.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtsznamvqp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtvbytcloi.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtycvlavct.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gthrmbfkqu.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtlnnwvadk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtlvswtnwc.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtoehotdtq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtquqbemlq.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtnzxxrvlc.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gttbueiiwz.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gthwrhckmw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtnldrzofw.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtogabapqw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtskswjfht.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtjqiawdkn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtpqshzkap.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gttddpsohh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtqznupuht.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzqmuig.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gtzzzxfdhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmfxjrzn.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtpzstmpoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzpkjafmv.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gthjjarwzc.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtzrdiweqb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtngsseqpo.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtmoxbgrrd.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtjpfxkfwi.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtffixnvhp.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtezvcwoss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtslpvplom.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtiipbreaz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtojzmulvc.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtcmycexnk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtpcbmmvyt.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gttqrkkizm.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtyrrbzgtd.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtcxnkfues.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtsvlehvfs.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtlsvvlwyb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtngxhfrhn.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtcyevrgau.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtqhpwqpux.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdetktrmv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtczkgpame.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvnwhqlem.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gttzfcwuaz.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtlgljtefh.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtdxhlzexc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtwqgzxhfp.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gthyloiukb.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtcuutiuom.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gttuzjanee.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtnhgrztsf.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtucaodlza.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtkyoaihhy.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtlhejvwxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtcgjhwbxb.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtygfzbasj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gthwmqyuwa.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gthqfsqtnw.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gttwvytelh.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtauwsttbi.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gteafhdvra.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtkdtbbjei.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtgvscqnhi.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtnyxamqxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtnokjtdld.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gtzyjggmnw.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtomtyykhw.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtkjvympdx.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtdtmnspbw.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsvupzwt.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtxpmfimlg.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtcixymixa.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtookjudrd.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtvkohatml.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtlocimiaj.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtvkhloceq.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtdwaboqzy.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtfaxrgrtc.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtkksowfqz.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtnllwrlwj.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtvluyulna.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gttvdumgdg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtbqmoucue.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtppvonyzz.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gttkxsohjh.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtjoysthpg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtqrjvivag.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gtfloloqjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtdmpunwpa.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtetdnmxbo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtfplmoljr.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtokscauqn.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtafxlxsqd.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtkzrmshda.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtmqgapmcd.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtsuzpxbrp.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtapgpdjfa.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtsqdfjywl.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gtyhsftfmr.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtnumsloqq.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gtktthgclc.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtjonivzjx.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtjjcqvxwz.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtiwkhgkcw.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtxthtlgmz.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gthamxgkbc.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnaxqorc.html


<!-- 参考信息 -->