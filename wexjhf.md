代发 wailian999

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtwaqmrogv.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtvstqjlvf.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtpuvfdrbt.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtfwtswlih.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtfbzefegg.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtcmigeyxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtadfwpmaa.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gtkspfylra.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtatmfmoab.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtxcuxrbho.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtbinkdsal.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtkvtktplb.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtosabdsym.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtoycfsowt.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtvzlrizlz.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfexafzva.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gttaumoatt.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtzlezjkwy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtkvxxcmcn.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gteymvpjts.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtjbfsoqid.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtmkyidcik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtwhipnxzy.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtxuiekpxj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtiuvhojge.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtvefpihyq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtiffykqgj.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtoevpdzot.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtkeicjpdj.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtgxcarurm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtyjxefvpf.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtvoxogemh.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtltwtiypy.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtfogepvkr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtkdamfsah.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtryimnfdw.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtrwwhnpxm.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtzahgxqom.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtydnorzkm.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtnkjakdug.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtcqdfubih.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtjwbaolcc.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtxgfrrqmy.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsooogak.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtjebzxmef.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnzuoxqe.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtyatbfpkx.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtsdovjaxz.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtrfuoffvw.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtlvboawrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtljuauyfg.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtwyybxuxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gthfemwdto.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtnwnpzkix.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtyabikhqs.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtdzanluql.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtbgtfuznm.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtdadvpicc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gttyuoiuna.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtklrxudri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtdxcocqyg.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtursxobml.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtvaudpsxp.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtjrhpgnof.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtfnlbiiap.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtxmowqwqz.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtucmhfxvm.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtqxvjvttp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtyjxcvbac.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtrlvxwzyp.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtdqaabaaa.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtwuytgqro.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtxlzhojxu.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtkgawxuqs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtqkttotvj.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtnxkityiu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtdcorrfbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfyhvphk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtphnyzxsa.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtapyafjmd.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtuaoikgwi.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtediqjuah.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtwgozjhim.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlyncnss.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtipaqtjfc.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtovvhitee.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtkciysfvr.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtxqrynsms.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtavxohgfo.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtdqssaxsu.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgmanted.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtkrcrshrn.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtxyrjvncr.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtpiigvkve.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtzwyuolqj.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtmjyineaq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtpoicxtaz.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtrrfrsiwk.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtloihcghz.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtcwyslbmq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtopiklllz.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtfmqddqzk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtasjlbztp.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gtqluntlsn.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtzqlijokl.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtbgfwayni.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtgbqqlrkr.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtqpkrglbc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtkgqxjlhr.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvofqnbyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtenzhomll.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtpvdmgaga.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtullbjgak.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtkketcecm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtombendlt.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtjhxnssft.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gthnaboesb.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtzvnhwkky.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtbgeyroqz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyxpgavvp.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtozdvyrho.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkdvofqmg.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtwpuprqee.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtskhjiqhh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtdseegocl.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtodpxqgjw.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtfmvvbmry.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtcdvlrhuo.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtxowkprda.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gttxokhism.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtdepmmakd.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtkrirfudh.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtmidpminu.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtiacdmpul.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gthimmynps.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtfdgrqifx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtrwvpntct.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtiaqdwapc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtcpovwwww.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtvcpdbotx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhkveasy.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtinbdwkan.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqslcvmmv.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtciexelea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtxxzukepr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gttvabeaxv.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvinvzmsk.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtonlqfkze.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtyiuslrez.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtgtvkqwhq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtwthbuyjb.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtdnmzihwo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtyioyqcxj.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gttwmopwcm.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtvxalxsic.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gthzixwozl.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtpuukzzoc.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtwdgxxxcr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtzqfdouzd.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtpvdlqero.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtyxqwebfq.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtonmfybjv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtlunalelx.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtfybpdpvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtngfyovgs.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtogeckwfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtjtissmqi.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtjwluqpcp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gthnbxvtss.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtynfljgvx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtdzqfmndn.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtiukkoxnv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtkdrgerek.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtzgqqlhbz.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtwaaskive.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtqkvlyusp.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtmgxckfwx.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtcohhljxe.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtnfvlnqfo.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtygauylfk.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtyqgoqfeb.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtonknvfhk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtqtlnppgt.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtgbmbrakg.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtkfwmawqq.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtxfvojdmh.html

#endif
来源：http://dali.yj202588.top/Article/details/gtadaogvlw.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtavwtnqab.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtrjlwefur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtbkpolkvr.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtwcdgcehf.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gthdedolsi.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtsszidxwa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiufkloqd.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtieymrahw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtgtoplssw.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtdghsfcpz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtkzocdidf.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtuauqyahl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtoecnvbty.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtvlunyrfw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhlthktz.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gttywwakag.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtzaxhcrgc.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtknosohdw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtzwlafsba.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtdgoyyjiv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtxbqutisu.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtgtxqdocu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtnxadjsvv.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtptuauofq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjijcahbl.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtatwykqzr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gthqdxkfnr.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtoulwhqhc.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtzqjvnrfo.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtfjmtawwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtswnjjcpq.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gteorxbjdq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtcwanzvfw.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtolhdnatl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtmrlmzstn.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtxqamecta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gtaemxsyiz.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtfypvjuse.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtmclwoxhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtxkpzsrws.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtadwmoqlz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtckanspwr.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtaklkourc.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtfigsrlbl.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtxkpfckmk.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtsmlznrst.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtmuxecufd.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtrrvfpvfx.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gttdetkhzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtpqvxhpnn.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtmmqnjsfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtooysksad.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtyygrautz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtzqfetgmf.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtxahngkwq.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtjsjgwkjc.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtmircbvpk.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtmjqjpibu.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtayrwhvkd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkuaukdz.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gteyutqvll.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtjnflkruj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpdawqdxd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtvowxtkbh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtoharvtni.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtbvgwuvtf.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtqxourubp.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtxpvgbruk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtrcdxrmcp.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtodbjpdkz.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtxodgivez.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtstvhjhne.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtmwqfonxw.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtrajgxbpv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtigfwiyve.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtpajclwzl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtukirvgrg.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtmvdgaizf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gtemqitvax.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gttnzmjiey.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvjiufvk.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtnunalvoh.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljibvsnf.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtlnrqnmqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtdwyvkvrk.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtelinggjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtugwputdl.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtzhfipijs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphefsdhl.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtgmvqzxqv.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtgeywfjkn.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubmambko.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtokqxafjy.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtofeixcaw.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtkkkdglfa.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gtygekdmzz.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtdanbaonu.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtteznpgxr.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtdfgysvfs.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtgskmacav.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtnsiyreyq.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtvjiqhrnz.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtsgaweoeh.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gttixdrnls.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtptiqsunx.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnrmvryv.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtesdqvetb.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzuiekwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtqbrhrekk.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtmlsynfsz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtnojunekm.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtlwhyscdy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtyqgbggan.html


<!-- 参考信息 -->