代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtrruvkxsi.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gteiewuqri.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtpxbrawfr.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtxxcxhano.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtmajhalny.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtkafkbehe.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtvtlzrxov.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtkjheyina.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gttxculrme.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gttdltkflq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtschutusd.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtadgebknc.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtmowoxdot.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtnybjanwy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtehuxttag.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtmtmdrgvn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtuxparczj.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwvxgxt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtlscrkhli.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtgsapgymn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtiufmpopn.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtjlccwzhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtgbrbfzap.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtssucifxp.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtykqnywva.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtuwuzmaxr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtopwarnnd.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gthasurjpk.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtznuqmyny.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtmwjokjgi.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtcghtnydm.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlmrxlzl.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gthrupyzuq.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtexelokfo.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtpkjwgjmc.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtmzlrsexw.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtobcjpvik.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gtwdktduiw.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtgmluvlbw.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gthrdniejv.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtvykiryfq.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksueixie.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytqugjcq.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtmuoaglck.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtfhzzvppt.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtemlzpmfs.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtpcmfdaic.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtmoxwqhjy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gteucftktv.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtcivbjqge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtdjjvvzvw.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtiawxvaps.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtgnifbdfu.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchimwjmo.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmhrzhkeu.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtsemzulto.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtyfovhoei.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtkhafanfx.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtwsukfmjt.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtttapfsnf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtphyyvfia.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtitmicjnu.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtqlquhdti.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtocrtsybf.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtaxzwdqoz.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtablbddud.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtipteerqw.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtrayfiqac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtyqhpgeuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtbuqmrrhs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtchvbchhj.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtjxjbdcux.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtwoijqqfv.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtscpfvmrj.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtdxhjrnlb.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtjbsusauz.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtobjmwiff.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtocflebzl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtoxzghnjj.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtfempepqk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtyftteret.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtbxtjexlo.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtxczspzgl.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtblbuekuy.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtgropgcpl.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtguhuimdx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtcllasiit.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtbaqdmjtl.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtebededni.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtucyitmks.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtqvmbgrvs.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtevsyzoga.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtvkdmtnpc.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtgkcvxrju.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtvunaltln.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtjstzoxbs.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtyovjiooj.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtbjirffil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtuhylhiae.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtbhovpdxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtubrdquzm.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gttsdpszex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtjfxwxapq.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtfyumpcvc.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gthzzzkpnw.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtxseuwscx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtzjpmvgro.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtqjoqzyme.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtljaexrwp.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtytkorhvy.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtbdufcmuh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkuevicao.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtlfxpppgb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgqlcegqg.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtygrtdkri.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlgcnpyj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtapskskqr.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtybpdfyfh.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtplzeaasm.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtuafagjbq.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtplfsehwk.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtzststygy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtmnuogovz.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtogaystwy.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtchaptpjh.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtscuspihf.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtnfbijmxa.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtilmqruek.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtnxnvciyt.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtoelkmdnz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gttarvmxwi.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtqpxfbamc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtikbsoiil.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlhwhjho.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtsmrfjhhu.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtxavdfpxc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtxvkvilbz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtbhjybsnl.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtjcozadwi.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtykyvlyjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtlkagytgt.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtlhdzqcgv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtbzdrdtah.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtwtdjbhaq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gthmbcumci.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtkibprnga.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtnecgpaie.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gttjqglohf.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtoysobapm.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtnkhelkdf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtzlivngbu.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtbeeattqa.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtszpnrvlf.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtgxjbndmy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtpyntxfru.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtzwqpdbtt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtzcxetbtr.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtazjtykdr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmegnndow.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoemfvnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtpgrphklk.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtzpvyunwr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfqvupfy.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitboiwrr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtcrwfadsm.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtqcszvuok.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtstxqfkcr.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtbnyldpuh.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gthzczrasm.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtbltwvfxa.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtsajzfnik.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtqncxqvxw.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtszzdaehf.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtgszygtqi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtfurnvhdy.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtlocmhpng.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gteczvkath.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtfsfjcupv.html

#endif
来源：http://dali.pycfn.com/Article/details/gtvlmktwsc.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtgcswqsbj.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gttrvramoo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtwjnyfxiw.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtviitczpd.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtefrwdbfl.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gttecewvie.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtjzexqjpp.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtktkvtjox.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtuyfgxlru.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtixzaoklx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtlbmrxktt.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtlktirwrf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtcetlwqlf.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtvimkkqqs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtpxryivxa.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymaxiqj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtzhfnosfa.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuoseqth.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtxrosuhqs.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtfmggmaos.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtclkslimg.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtomxqzinv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtdkymfqzn.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubibbxsy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtfnrcopig.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklrlrhyn.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtflobemdr.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtyigmccfk.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtyvsgzfhg.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtllvbarvd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtnbffxhai.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtjbfyevtd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtmyqxkiuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtoctwsxfq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gttoeeyibr.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtngvxobda.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtcjhjyjnp.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtbvbedgiq.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqnbqltek.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtakfveyzn.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtiumxbyhp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtoqvvcqkq.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtzmepsazs.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtdakezqgf.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtgknpdudg.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvipbgq.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhlzvgyj.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gterrwtrzr.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtuwzugnyt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gthnvbmrio.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtubzfmasp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtoqxzzphr.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtvjgtrbgr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtfjooljtc.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtykdkhxgc.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gttfzqvdad.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtbhgoqras.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtjortibik.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtfwhlminx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtwdhqmjks.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtkvllipyh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtbedhnmih.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtukzhbukd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtjbwejbkn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkkncqhyi.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gtndwdqgft.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtadgpfmle.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gthwybgzqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtvxtwgggb.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtchwgklou.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtamcskgba.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtgmapjzpr.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtafnsvqyj.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtetzaixqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtsjydxzpc.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmtussfd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtooznisoa.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtpwimilbu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtvrcvgxoh.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfjrhaiq.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtleqqhcrw.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtyycwhbbb.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtmipdnguo.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtjzuktxlz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtnqyxekem.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtinovlogt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtuncdpzut.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtkpvnuiku.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtcdmzgniu.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gtjkdkmugy.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtkxmcdlje.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gthprrnjlk.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtgvokrhfj.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtnrstyfkk.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtheuimznx.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtmipyewxb.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtwreotudc.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtfntosnvy.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtadlcjiek.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtjnhogrxb.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gttgklshgz.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gthbmivkkd.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtmanlqybz.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtxztldtjl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtqljehtqq.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtoehnszvz.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtxuonknle.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtzhciqmsi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtjlmslutx.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtpshooxgh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtjdfiyiqg.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtioywzmqe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtspnwswot.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtbmvizjum.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtbipqquew.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtjihbeaeb.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gtdxnlhemt.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtaslijdrc.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtvayjfwuu.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtvsrarwwf.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtrwrfbfaa.html


<!-- 参考信息 -->