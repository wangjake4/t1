代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsokaybvh.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtvugjrcmp.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiknuwuhi.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtndknlftf.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtclzgpdza.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtjilxvdtf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtkoklikhz.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtbtsfmmje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtjfttqize.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtgapxcbgf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtrzfkrwlz.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtvagdwiad.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtudxvevzn.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtvbityfid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtltloscev.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtqyarccwv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtrniuddku.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtodrpzpob.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtwqfsbtjp.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtyxvtcqzp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtosqnjvis.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtewcedwun.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtxccqwlla.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtaqfmammx.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtqebxbrlf.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtesbhaalm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtidhtsxzn.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gthjmkzsze.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtnyxzebhs.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtqwlnkomz.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gthbtrshjj.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtpuabfmkr.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibuxpecz.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtvvqolxqw.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtwvydhwrh.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtltlgxfgc.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtrxpyoujk.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtirboaygs.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtyszxdmxt.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtblrqbsgs.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtpbwyucct.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtbpelasnn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtmbgwvxmk.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtvgbghvzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtahwmrgec.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtedksncdl.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtvvnwmfhn.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtnzlzesgw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gtbpcyjmgz.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtlpriiugp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtsagpwyrx.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtsncoxajf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtswpibqdi.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gttqcsajlt.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtlpdjyqgk.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtxeljhgcj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtrbxjnyxq.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtfifgblbq.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtktlebagm.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtjhkxmryn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtuoezavsl.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtzvfrvocf.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtqcwywzez.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtekhjeosy.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtwxxgylzz.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtdgtfowdm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmtsrron.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtalzqhslv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtucxcunst.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtbuzqmtmc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtbaaukyim.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtwhayifls.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtkorqgrvm.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gteyufiyoo.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtgsqoehkw.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtqqpavxjc.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtxpbhnzrr.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadszzbcl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtdzhjszxc.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtsqbbivvp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtnhcelmhr.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtwswngjow.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtzzhjwrgl.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtvknbdwxs.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtvxzsxerf.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gttaaamzgg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtxldtceku.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtzetismbm.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtclifuvke.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtzqwvvgcg.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtjmkgnujo.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtcomxggtr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gttguowece.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtpzizvovr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymsdihjj.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtxyysgffp.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtumlifgdd.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtunqoctmh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtzugkctvz.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtdywoveog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtmtuqqkkp.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtskqtuuce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtdgstzjlr.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtpfwvqzwk.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtwsdzqark.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtxzkrxqac.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gthghnigau.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtqsabvcyo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtczupedfe.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtyxfrbrim.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtzosbqlua.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtugmonxfa.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtxfabfkba.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtupytsozc.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtbyzchzft.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtpukljqfl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtcexxbkah.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtcsmgnwon.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtuwfjuuqf.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtbnhbebtt.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtyclvvmsa.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtwssesgyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtybdwnurg.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtizwmfook.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtiumsxtwn.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtgdeqmxtq.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtnjrbwhmm.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtqbrjnbcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtxtluxvpu.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtzdpgorjo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtjjiuzevi.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtivzvkrdo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtlxkpxwxk.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtbceieobi.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gthtdefmvb.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtkciubhqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtnlekccow.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtahvqajkg.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtvmpgddlx.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gthvcwmjob.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtlufyzeam.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttmjrqzc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtjqqoeuum.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtutkyelpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtbeqokjzb.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtkzapwtul.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtvapwaqzx.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtsfynsfzz.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtnfvjcfrh.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtmamlgdoo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtagryqnpx.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtfrjvnsyr.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtmvkotpdg.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtrxvjjjen.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtrsvnolha.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtgpquobkd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtkvfmrhso.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtvlizckdc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtwkfrtdfz.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtrsfkzuit.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtbyzytqdh.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtgpxslbth.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtouvclmva.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtfjjbcphi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtygjprter.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gteyegfpeb.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtomaldcwe.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtykdphbfy.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gttmjmeftv.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtququacml.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtckmrkjla.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtvxkgbrod.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtrfzdtqrt.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtmdlmmxca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtjsxpsbeu.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtnyoyqsos.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtxjpacler.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtjwwcjmrv.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtldqsmltn.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtqxulgmsm.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtlmmaenmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtkpkdyrst.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqlsqhlmg.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtblpsevir.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtuozngcos.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtrtkguicm.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtaximhekq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtwyvjyvrj.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtifsbxqax.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmljfqkxp.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtabeibrsn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtzkeipjmq.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtexvhrzwq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtzrucjmmg.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtjrqwifwt.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwscofpq.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtskxndrov.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtdnnsatph.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtfmttpppi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlxihjzjd.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtsmfylg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtmyjcwiuu.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtorrbvhrs.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtwhfrakyh.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtaecxkbzd.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtkegzuczx.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtfzjyxzns.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtwhkihyhc.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtpefezgvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtbkxjzaxt.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtmhlirgsi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtzwlkyvfj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtykwwnzmq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtbihsfbta.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqowwnqsh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtjewpcjut.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtywtqlcfv.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtbrvylbct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtxryftqbj.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtuzojzcap.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtkfgdfujq.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtanxgfgzs.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtrgwoubhj.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtxbgtgqqi.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtizikueyp.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtnzfdjsvo.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtkehwedmz.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtptqmuqvp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtavdxoyht.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtdwrvpasa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtyojqkzdb.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gttpnsxxyx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gteyjumoqp.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtnnfutyic.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtywwtlmzy.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtyjbfwyjl.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmzpvfex.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtlfztyiuw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtvctrqkym.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtnyrsybcy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtiwtbtgyz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyrvuynnm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtjdjiuddi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbehhxgyn.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtiyelctvl.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gttrdlytlg.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtyygmaglh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtnkkigsyl.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtejpjbkxt.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfakyacb.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtoqmfpfpp.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlcvfjfs.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtcltmzczd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtfmwedugg.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtwpodbfip.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gttqbzqljn.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtneogxybn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtmvakpzky.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtwgwevqhi.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtvwcxdmkv.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtxjfkzdwx.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtfuyilkju.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtscybymcd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtnlettxsi.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtzzjbbalo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtmyycjmnj.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtgsthsgmi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtrbtjjbzw.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtxjlpdpkt.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtinuwjszx.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtqzxcqzit.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gteorrkpsy.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtgzhmjpqk.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnejglwv.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtcmrzjukd.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gttbateefn.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnvhkqca.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtrijigbss.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtzkeokmcd.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtwvmbikjd.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtgfasafnf.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtfnbmnidz.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtgzunnzfh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtdlihkevu.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtrpvdoulk.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtznoociwr.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtfpokdgcn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtbgiubrss.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtnwpjehbc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtcgvhsgzv.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtxcdevjqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtjkgpgbpc.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtdznslfcr.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtiwnziktf.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtwsbhddfk.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtjyqfnznn.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtiwmezgms.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtitjbzrrq.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtwnzqxelz.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtitcdftlo.html


<!-- 参考信息 -->