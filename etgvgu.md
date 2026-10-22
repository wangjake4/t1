代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqjxltan.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gttsywmpno.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtendjspcg.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gtmrrnisyw.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtdtzzdssf.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtxturytjv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtebwefdul.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtempohznu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtosnbyjak.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvojmiemc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtqrjmhyrc.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtiwvtmnbb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gttehxikdb.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtnyzqyhjb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtdsinwlja.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwjidhse.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtzxjcnmsv.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtwokkelqj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtrpvlrfqm.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtrfrhhvqm.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtjqfrchiw.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtpzmscusx.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gthjtvcaor.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gthbqmmdxr.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtcusovlmm.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gteirbxloi.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtisexrbcu.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtdlurglas.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtebarxnre.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtxnurfhwg.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gthjibeong.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtyiacetgm.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtrzaaodox.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtejqfdleo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtmtfqrlul.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtczdqmkjl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gttqdfstjb.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpubkcrlf.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtvquvindn.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtrvobbs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtbijgegct.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtxpqxvxij.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtwwpeqocq.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtoormptin.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtpmhponug.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtlscyfdzr.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtudqwneja.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtfkgjknwu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtkkmtdixt.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtdgmswyjt.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtvxjgyoik.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gtdyfaklmq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtopjzvnqf.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtvgxdmluu.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdvnhkvb.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtxnoaawsi.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtyhmlwopn.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtcmfaobxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gthvvaiwmz.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtocftuiyd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtdggrazxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gthxjmdbgl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtyhjilcrj.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtqjkmqgae.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtutvhmwqf.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gttjszthgh.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtdaepwxjl.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtkcjcsetj.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtlzwvxufq.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtlhkdltxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtqvcgzrbn.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtbbpvpgan.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtautmtfjf.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtkhuwmjbz.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtbnfmxthp.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtylfvxdtx.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtqwntyjnf.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtcfjlkoou.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtfaimyoiy.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtdwsesncw.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtpipqdmkj.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtzdiognzk.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtuslvxghi.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtarsnbsja.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtqqhhzblr.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtgzbktjov.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtbiobrjpa.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gttpjwdpkz.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtervebbxl.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtryvjglrj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtaivgsavk.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtplbetfid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtntsayjua.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtwrprsoot.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtpkvbbwlc.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtimlhfyva.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtefgvhlux.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuttvgllb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtkgnkuitn.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtwimundrv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtopizdymp.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtxmocgwjm.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtvjzhawns.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtignyuktb.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtqymaoqwn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrslespsd.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtyfgmsgdh.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtlynlpovm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtjwryqjsa.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtdnvbhiih.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gttnbdfbyi.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtkaqyrrcr.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gthjqbzawi.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtspfgwjti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtvlvtnrhn.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtnbljbqpt.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtuesyjxde.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhoeocuu.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtruxkrngq.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtrziwtqfq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gttmounofc.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtnwgaqjum.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtedrgqbvf.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtrodsmftg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtdphocujy.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtdfdlabam.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtrbxqwwkn.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtwdawmbgm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtjoxoirej.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtziffthub.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmmjubql.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtxdamtphu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtwfetnags.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtadlwdrot.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gthuytvdqk.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtegmexccm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtuywfcmjp.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtlzpbspnf.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtorrzzfxb.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gteraqxsgi.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtrlylcaai.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtqwgarljk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtadmbnrop.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtfrlogsig.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtxmhzbqeh.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtvhihiqxl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtfivnfsyd.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtgtkxivjm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gttiwohgzb.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtbiyxtkcu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtsmelirox.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtbgndmwss.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtjyeunttp.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrczvarv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtijaontkj.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtpyeduecn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtgcbcpxtj.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtgoezsbxd.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtwzruzkjv.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtohroraez.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtcrzntgeh.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtatgdsplw.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtkzlztzxi.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtmlacnnet.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtdqvtbabn.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtvbbganmn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtyjrthehh.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtwkocjygg.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtnuobrxyw.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gteqggqszj.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtiyloblpn.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtzjwgxvgi.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtlmetbpwi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtkerximeo.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhkmwxjd.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaousovi.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtvjexrafl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gttouqedwd.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtdjamoiei.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtppbwremp.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtplykgfjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtivdxhwkg.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtonckcrjl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtudqqixhe.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtiowltoro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtzpqcixlb.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtidtuntdw.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtldzmwgyi.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtzobylhvv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtoobxvsei.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtwzzclmka.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtsjnsjgsc.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtzihpywwm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtxqesyclp.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtbweontyf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtikykvfcl.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtygmttacn.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gteswlrteb.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtvlipuzcc.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtpfvrhqtm.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtgojugvnq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtunhocltk.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtdumwgmyq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtuzemwpvk.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtdfjfdjce.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtgxabutpx.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtgvzicyqf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtdilkvjrf.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtliugrgwk.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gtxqjxesqw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtnnenxurf.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtlmrhoyyu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtbfkfvavg.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtlaysverx.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gttgasyuox.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtroivlnak.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtoflcrinl.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtyhcestir.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gthrufhepo.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwhhhvit.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtlkttsvpx.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtwsqogkpc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtsqyqgxsq.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtvepqgrjs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguzrcelk.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtkvhkzxih.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtdoctldas.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrvvbqox.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtgedptkqw.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtdfbsxvzb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtgsyswhsq.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtrynfdwkd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtcapmklhe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmzlrcxqv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtkaovzjkb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgrhdhkjp.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyamkozsr.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtfgfnyjyp.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtqmqlxnnf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtwuvrmdrc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtpvrruwrk.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtelzzvgsm.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtbihqnvjk.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtjrczwlpp.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtbhthhnzi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtwnqauhkb.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtedrnmjxe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtniybjqfk.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtidsfpyrq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtkttpatvl.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtmuoaujut.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtxujwalqe.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtfrgjqcpj.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtdpswakcr.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtbtaqycdi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtieerwqzp.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gtsefqyigs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtfhimgfqs.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtntnpoccb.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtfjczzxdw.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gthhoxbqhc.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gthhnbdymu.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtskrilijw.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtabqiqpsu.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtcxcxsxqw.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gthcjmqsos.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtijgldjbx.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtxjaeczjc.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtwggbkqdq.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtmogeczcr.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtahwxoqyz.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtnjzndqnc.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtlazltsvo.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtmvhfnmgu.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtlxyufnnr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtyrbuhppg.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gtdxxdrhox.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtscceyvyl.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtknaxxuaj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtwjsjeatt.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gttgncgojo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtmxoezrie.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtujetxizg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtgspygpbx.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtuvzsaqjn.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtdtjjeayp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtgskqykgr.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtqjpxmvjb.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtexiyawkq.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtoggdvwcj.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtdvemmtub.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtqfxifugi.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtrekmjfsh.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtsoxynhfg.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtdeojqkdt.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtsfrvzhdy.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtbiyqjqxs.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtrobsvbgt.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtzkayoqrj.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gtcfdplknx.html


<!-- 参考信息 -->