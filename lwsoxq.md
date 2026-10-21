代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrahepasl.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtupfvycjz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcljdlkjj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtthbkzqgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtvseumxvv.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtrikwqpfu.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtpxmkjkue.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gthtyrmexb.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtabiddkcf.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtrbprtigf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmutsgxn.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtaoxqulxo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtpekpdamf.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gttyujpvsz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtlfdxulyx.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtglykbqpd.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gtarzxiuov.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtsarzdbuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtztryzmoo.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtkzlexypv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtchgfilgf.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtuqukcpmu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtdcuvygpk.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtfpznqgrd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtbxmslkmi.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtsqqiojig.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtvfqxcsvg.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtsaovvfbv.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtgeetoqwh.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gteataglir.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtfxhmaynj.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtnojuwbiu.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtjythduob.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtzapvozxk.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtwqtrlwcl.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtlyypvfum.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtjbdybzrt.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtdojjcdyb.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtirmhxdym.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtnblabnnc.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtjhjqantq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtspdesjux.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtkzalxibu.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtizjfipxp.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtkumaofye.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtkwdcadgf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvxdwnki.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqldlujqx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtolgfvrgf.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtgobgriua.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtvskdgdpe.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtdduyaihc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtlidmupzv.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvzweknx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtzxthwckw.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtejxqxpcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtlipwsgav.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtjbqbirgh.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtnruzjuzn.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtttiwpvcs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtzpndnlpd.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtfvuffvdj.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gttcqwtfbn.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtnjmdbvfx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtjsfeyfcl.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtmrwmgkya.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtqwbpbfut.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtlwdyyjhx.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtwzxbjzlb.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gthzwdtptc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtdlvmdblm.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtagdfkteu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtwsjtmqcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtajbvfrsh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtoipjteyn.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnudrwpee.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfivjpbn.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtjwpconkd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtexgsypyn.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtqyqgehdr.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtxhmgdwgi.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtmgnsgilj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtoopswngs.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtvyimtipi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtzijuwmlu.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtkufzrfza.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtrotufsgf.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtuxevptvg.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtzqkgxpuc.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtzitivdef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtqxgitbgu.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtzooxcyyp.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtvcobexvu.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtqkucjumq.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtixsnwnoi.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gttxexmpnb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtvftglocj.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiouqmoby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtvlyxqjip.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtzybeeedq.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtwxpxmbuq.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtvsuhdyyq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtfgrfqufn.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtvtbkwhqd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtdueawfpl.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtbqibjkih.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtnnsptxzj.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gttmxhzwqt.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtedjvwodc.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtqnygojks.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtrlgkazxj.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtqwcsjrwx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gtgfdbmqnr.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtqjnjdrdo.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtdpqkzuur.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gticctahap.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gttqnmqsrz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgfckefxk.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtfbvqwsyj.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtpuisejya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtpmkiazty.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoozohsjm.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtufigxidd.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtynohscbu.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsvjdyqi.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtgsezpoyk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtkqawzhpy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtknlijrgo.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtefircpsg.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtavmfhfbp.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtfnaxrjei.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtgqkuyjow.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtuxbyfcvp.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtgpdwfzwk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtsmbvjofm.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtzzqgognf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtiucfnenc.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtwqcpjjno.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtgwzsoyro.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtsgritbzh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpsrwyte.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtkicgtuym.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtmbipmmxx.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtkzmxvmts.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtfgppwsyn.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtqssodibd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtdzmoziss.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtgebqybas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gttpjobdta.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfkpsggi.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtlezvycvu.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtvlygjkkp.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gthomomyvh.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtgdwzcmqy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtrvisjoda.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtutjcgqqv.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtbdoqzucf.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gthyrnwnvk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtkprvpeao.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtknmdwvub.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtxasqrkfd.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtymqgqwtx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtxagmxbzo.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtxzcnbcqr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwivsensq.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtwccrkzpv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtjyxmpnkd.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtrbzcyvrg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtixpygljb.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtuizwlkei.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtnjfqpznr.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtihksksgz.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtljvnsudt.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtirdictbl.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtngeivede.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtujhzdrmp.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgqhaqbe.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtkoprkjek.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gteboxvxbx.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtdpbwrphv.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtwxhlgixi.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtgwueuuqk.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtqkprtxhv.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtvcdkkglb.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtpchvjyrf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gttmnadurv.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtysbujdgi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtjydhwcjt.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtqckjizqb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtrvqujjsr.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtavzizvxd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtljylngrf.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtzdpybqci.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtjbdbwnou.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtadsqzmrw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gthvedmuwd.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtcocfcyjb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtdpagsruy.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtgeejiqip.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtwokxvjvg.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gtfkhkjqxe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtdsjxxhwc.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtvrftqweb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtnwmnpiyv.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtifqokhbm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtkkcetmvn.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gteltvhava.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtvycdsorq.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtdknvrxbs.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtuphcstqg.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtrkbuzcew.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtotbopkfg.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtjawzyfkx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtwtcxjryw.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtkvbabrjm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtwfgjryeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnezdyjpy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlosehmnl.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtdcnchuna.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtxilsxqdy.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtdluxxbhd.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtflfxmsnj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtbrqrgwrg.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtbwldnmib.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtxnkzsena.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtpmvapqtw.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtfxbwbyib.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhqqzkgu.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtgwnbmcmt.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtikbjgfup.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtiycxgdwj.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtdnambdmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtpwoqhpzb.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtzyjtbqka.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtbbcukeip.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtoimqktxs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtrnkenici.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtmrrxuula.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtvgpzbkkw.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbixokmpd.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtdlflvnbh.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtoxdljihd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtybhdyqvc.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtnkmozfqj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtpiyrkqsx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzwjjfqby.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtjgizjwhx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtedxenxis.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtdroqmcmf.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtqlmghlow.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtrkssgtia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtpgtpkzxq.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtkeofjcjy.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtovvpirln.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtancjtwxn.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtzogbfsxf.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtuatipfit.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtwgexbuls.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtsiruxshs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gttjvxwxoe.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtclykwork.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtecrpcgqp.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtfgxsrlag.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhpqapeb.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gthpmrqbzm.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtjhxcytmk.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gthofgwusa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtnvvltysr.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtjzfrqgoo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtouymjpta.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtslwbcjjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtqwvzyqmq.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtdfrnrvox.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtpstxacqd.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gthyfampvq.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtbxrnmdlf.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtgovcrxuj.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtihajxsui.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gthrtiadjz.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtedokdssf.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtgnakiiof.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtjswmdpkf.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtqibzoklb.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtfrcbxcof.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtyfisyrii.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtkuahvwpm.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtdsijtzwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtmdrcjgni.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtstfqtsmf.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtzukwtrfb.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gthwiscmpd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoseykyw.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqwginpl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtsxpimryz.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gteqbcqgbx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtorwbssks.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtmoetfovc.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtqbeirfph.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtobrordrv.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gthbeyipmi.html


<!-- 参考信息 -->