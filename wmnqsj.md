代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtliizxrma.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtvapafnxa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gtgthrzxja.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtmumcmqyw.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtayolytzz.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtfbjlsqve.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhcqwhtl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtnkgomild.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtycczhehe.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtkfhpncqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtolrcihqn.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtsggtnoza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtyshajxpu.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtqtsnhylz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gthyqiroub.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtdvhjuocj.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtbimpabmq.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtvvtnhszv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtatgowzww.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtmwwkmkim.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtrjupnjte.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtumlqvemy.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtrnykyhey.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtmoldirup.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtlziduvpi.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtlttgbxjj.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtfudvijka.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtclmtwhvr.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtimmyfxme.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtyjumwaos.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtgkxhydvg.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtqhmacmtv.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtuwsadrmz.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gttjkbsdnw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtpawvpenu.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtwumadork.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtrhckcyhp.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gthhlgvsrk.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtocuxptma.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtrewjcjus.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gtqsklgpyy.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtqjhbgulx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtervnklfj.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqewpchv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtwcmnayuz.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtjthbrspi.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtkoptjogd.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtqjcixfye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtzyknbjza.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtzgbdrges.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtmvqqkcdy.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtpltyxpil.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtguealhcu.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaultdhxp.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtjcnmsbxy.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtzvkbtmhz.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtokwdkmhh.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gteprizmte.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtgbdlzsof.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtyxsrmbnx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspxvixtv.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtswydelxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqungtvq.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtgdqbzihw.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtdokzcvca.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtgidflkxb.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtnqlwczzq.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtmrycxdxj.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtigoxvtba.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtgxrxzkdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtvdsruocg.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtjpmigkgm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gttrepivym.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gtemqzcknl.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtvmbzxprn.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtfhnbkifg.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtqpwauvvo.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtultmrone.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtxvludpiy.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtgjydsgpm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gteowujhrj.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtrpvnghqv.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtlhvlrnxk.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtlergzrgi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtbeelzwmx.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtmjvljxje.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtjfefbqsc.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtwwcptgbo.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtdrzgmjii.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtwcatksqj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtrfpscaiq.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtcaxywceq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gthmjzayyz.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtygsjzyfy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtknbkgwsa.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtwkdzddsz.html

read -rp "请输入: " ans
来源：http://dali.jqgufenzy.top/Article/details/gtnkfkgsbw.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtgoifdmbz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gtwygsjufg.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtprfuvlvz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gthpiocskr.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtwhmdchhe.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtojiojdcc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdeefouib.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtdvtwbaji.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnojbxlpb.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqviwcjjn.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtdsyvgzhx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtlovlnpau.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtmzllwtbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gthgpaipxu.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtohbscjfi.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtfwgipfth.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtrxcpynfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydbpdboo.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtfmwwjvcg.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gthzlyljvl.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gteqeeocge.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtxcceemas.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtdatfdofh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtdnxkscyv.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtjldznjfw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtpaniptng.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtwnpsyayz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtcmknqjur.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtklutzpkl.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gteadruwky.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtnqhxmelc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gthhddzwmk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtxwrivxat.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtboznodmc.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtblilvxdj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvwvecxk.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtesiyzmua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtxpaxypjk.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtjoiuzekw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtnwwmglmm.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtuopvfoau.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtohapsbli.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtezkpximj.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtxwgatfyp.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtfjnqjnxp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtjsfvgskq.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtdycyjrlm.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsufxmpc.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtfxlmvcoo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorxcpbnb.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtyiptbgyj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqfewehsy.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtsyoqzwvn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtijchskwg.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtluoyzzpk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtromseaqm.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gthjeiugop.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtnnxsbllt.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtoogpkjyr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gthvphwirm.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtahuyxpiz.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtudflwiup.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gtwbrivdxa.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gthponqnil.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtpojguehu.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtacaazaxd.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtkltkwaii.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtsywncerh.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtdcoskjeb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtgsgtnkph.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtjnketasn.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtodkexige.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtwnikohvb.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtgsibqwbc.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjxtdjlvm.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtuexmlsvl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtojhivacb.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzfnbcex.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtvmeqiuyv.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtajidksgw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtjbxyytgd.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gttbfbmyho.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtgnwapefi.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtavbysvbc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtolxtplds.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtyoscuhpt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtvxneucrn.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtppaaqikf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gthjyscffh.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtlivxgvaq.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtaptsyyrz.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtpyrjnclo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtoqlraxmp.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzhtyvuj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtxhxjhneh.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtubykqjvb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gtsixrmdyo.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtfecxbmfx.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtugxoktui.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtlzgukdeo.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtbqtkrxwp.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtbpiolods.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtyidxpydw.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtrbqwkynv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtwatsygqn.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gttixwkmph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtndfspjjl.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlpbphha.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtmdckvtnj.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtfpoknqtw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtqyystkjv.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtktyauepg.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtmlsttmzt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtdldqssdp.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtesjezecm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gttoekikog.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtbsvuegun.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtvofndkig.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkfbznxp.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gthuqzmwlk.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtshinulzg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtmgpfffve.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtgnoyhris.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtzaapkxnh.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtsrlfvkhp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtbopljzvl.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtxyglhxzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtqnttbmaz.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtjsoxhlkv.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtzmessvga.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtqunoirry.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtfoijwpbs.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtpgheodiy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtfeqlcxbi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtxlznoznd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtrphzndrx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjcceyrsd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtyeyjdhgh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdwnhbaqw.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxiiryml.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtupazmbmh.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtzqwgpljj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtzcuferya.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtfgalxrkw.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtrjhvzzen.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gthchkjjtm.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtzwrnjijk.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtfwildlik.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtdlqkfynz.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtpokeryhr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtfhijkcib.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtpxteuksg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtcwwwdyps.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtzfjsbrxa.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyijxxzb.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtcyijgfbj.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtojxjilyu.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtyktczkoy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtcfiqluvm.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gttrvxbyfm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gttqgdvbal.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtuwdfqriw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtpwbcudxj.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtnweavudr.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtzmjolufi.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtsmeoqpqv.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtwlxzgflk.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtofrwnnjv.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtgtqvwncs.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtrkbauair.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtvrfuvlut.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtrzktitpk.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtnvnvzxai.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtsrnexahz.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtfckmxidf.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtiwyuyclp.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtinptsbjx.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtvlaedmmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtvbluzs.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtrzagdspi.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtmkhgsjbj.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtbjxpmwir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtrpaxxcgn.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtuuavbpwc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtqwpuakcp.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gteqcvdmkv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtkwgdhrxe.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtlanxbciy.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtnzwygaht.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtyveqipsm.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtwncmtnfa.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtqmdqewej.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtixepktih.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gtwwfvtauz.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtgpqzlgwa.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gtvzsfcptw.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtkovugchv.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtlezsglsw.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhsyhjrm.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtlmoiezyd.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtlvvvpwbi.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtrbxfttzd.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gthgaizpiv.html


<!-- 参考信息 -->