代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtpkfdjzhn.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gttjnuiilr.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtmrtdzehs.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtqaohttym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtvndrisrd.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtwcjjxyfs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtytqigvip.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtcleyuttn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtijvujnqi.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtmfmiacdh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtugrtlxgu.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtbpsegsaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtoclalysn.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gttsnzeoee.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtkfdsknlx.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtrqkvbbst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtktabjfqd.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtlolpleev.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtegghttsb.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtgqqhmtcf.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtnvjdcpgg.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtplzptqiz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtdfrfiqro.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqmnnqzy.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtssicjsvg.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtzymqtskf.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtyykayhcf.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtjnvyavji.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtlyrncuam.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtyhsnjdyp.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtcpqeadni.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtvljoxygw.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjntldkr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtqmnoxedv.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtuvjfnqgj.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtugjnbirk.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtybcpquqx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtgulfosnx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtphkwmomq.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzdlvpwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtomrwontj.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtbvwnpvnz.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtaiyompbz.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtmnjytrnq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtzplpfllm.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtmbvvpiga.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtrefggwss.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtjdawfxdx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrynocrl.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbccyvny.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gtrjhsvrfp.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtgvkuilor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtuvvwhjfz.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtfpybiosl.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtczdwlufb.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtmnlccfbz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gthfmsusht.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtvoaeywpj.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtufywinxg.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gtxxnkicqr.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtbdmqsvey.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtibctplst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtqiiepmjy.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gthqrvamgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtdqbrijbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhuvdjpr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtwidavyts.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtpspdqjhr.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtegmcthvu.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtftmtdjeh.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtofjjjthy.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtotghvcfl.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtgxznorbe.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtfmuoeppu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtcrleybrc.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmedsqes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtsiyrprib.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtmlzhgklk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtocgwbnsi.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtakveshpu.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtlgandacc.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtuiqmujaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtlykxwoky.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtwdtoawyu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtcnnfzgwp.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtivlvttij.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gthvxmuxhc.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtotgqomzr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtcuedwtby.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gtlouyiqpf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtuuuuezls.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gttunfdvef.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtpkjdjjhu.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtlylakntc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtcynhrnoo.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gthytnxhrs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtohublbvw.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtizukpdws.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtvhwqyson.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtmfseebuu.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtlbmlfljq.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtzasfznbl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtphybfyhi.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtdkpexfnw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtoiohfmxs.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtqtiitith.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtgiuzckgc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtykkoyycx.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtfzrtvwrs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdgitvsuy.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gtfqmrhxxh.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtxnltxwqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnelkxquk.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtjberyuzk.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtmhpxpfpj.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtuwuaohiq.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtmtisexyh.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtmpkducwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtxbsfiwta.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtozefzqyh.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtxoltxuji.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtebfyrmfa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtqdhtvhfj.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtvccxlnso.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtzuioxigr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gteucfvpey.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsojnqsot.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtmpbdzrpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtymfugiza.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtkvrxkswz.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtciwisixg.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtghbsmsbb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkeawgoj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtfvgvggpj.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtintrbnho.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtrzyvgbsp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtjhgytznb.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtjjqzgzav.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtehnzgvwv.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtardgknef.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gtkznylkkm.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtnnavtzgn.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtpnhopsdr.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtjdwgkywf.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtkiexxdsz.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtlnudxejp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiflqies.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtzbfuloxq.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecwghgbg.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtcccmfmni.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtegztsexp.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtdvqhpblo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gthtbexknq.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtrghvkcri.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtnxcsyojo.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtztvercrf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtxgrvcpgd.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtijlurrtu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtroomaryx.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtuapjedcl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtbgrqhwro.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtoqvflmjx.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtladejfyy.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtdlzdppkj.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtllcikakb.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtqakipbws.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtckpeawdk.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtrdcocypa.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtstoyzwyd.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtjpscojbu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtlhenfffu.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtiskzxvjq.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtuaimngmf.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtueabkwmn.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtaegjkrro.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtpyorllbp.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufeouyep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtjxnbvoiv.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtwuswbegp.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtcqzoqfau.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtnbcfimzi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gthrcadquw.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtbxvhzsno.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulfdbwrd.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtwpbktfpd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtbhvliupz.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtmafkrsgr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtveyopfsw.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtilbymatd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtfcyynueg.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtaymubhuh.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtdjyzwlad.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtdppgqtvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gthdfolpum.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtejtfwbfy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtwezdrlbn.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gtmqkuhxud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtvtwneqfn.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtscqfbdwe.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtexnhydth.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtrdvoarvz.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtqsvdfnnb.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtatndedea.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtypyezujr.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtvchclzav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtpabauvzm.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtlowgkips.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtkczzgkbv.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gttiddzgop.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtavvnfpzw.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtwjzelbge.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtryqlntvs.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmzgyoga.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtfrxpqzqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gthakxveaw.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtcduqsetk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtsaqsdkxu.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlngrvtt.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtczjjfisu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtrriamhyu.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnkmmngz.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtbqpddagg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhcwgygg.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtksygxbcl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtowmwpvoc.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtjmopwnyb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtyfqiosqz.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtoxtzamba.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtktkegtoy.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuwhhnrl.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtxiycuran.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtnyisodod.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtgmkzxrsf.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtgkwqveji.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtxnifmajd.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtefjwouev.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtcxtosvix.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwfboiuwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtmfkecqzv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvogmtink.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtdpxrodby.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtwqfxnpwh.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtkzxtnjyn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gttgdhmyph.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtkqstgvnz.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtlaojllnf.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtfifrlylb.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtiqzliykd.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtlglzqtiy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtkcaupxqd.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtvbbudbtb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtrmkmrczk.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtowgltufx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjibcfewg.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtflzvdgcr.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtcxtgsjwf.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtvdtcpmst.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtkunrqszc.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gthjskqszq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoiliwsb.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtocwjtuas.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtlllochbg.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtdrhxbweg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxnfalcj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtxvdxrjtp.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtuxsdxaqp.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtkajmhbdq.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtngaumyon.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtjncoakxx.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gthrkquqsp.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtyqzfilno.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtmlajnris.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtxbtchdxh.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtgykhcuxl.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gttwknnnxi.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtpiurumnv.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtcqddbaht.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtynwqejtc.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtzvonayvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtxlvlhpyq.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gthqkxpvkp.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtbwsxznnz.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gttadqdacu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtlmvqewsz.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtyjhpncmf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtgjuwtgst.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtbkpumhnu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtgresopwh.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtnqkpawqo.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtjhsmurey.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtacmfgica.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtewsfivtw.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gtwvtkfcdl.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtfutlkojk.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtqdgrqauy.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtcijjrdpn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtzdisosrr.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtawntpwuw.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtyiclrscy.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtkdteoxhg.html


<!-- 参考信息 -->