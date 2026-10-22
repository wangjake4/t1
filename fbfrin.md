代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtregxhagd.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtwtgbkhjl.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtspowxgtt.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtrnpselid.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkhlpgwo.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtbhycetpx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtexkeopys.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtaurvfrdu.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtluxkeqea.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gthmsbfgaf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gthdqlofwq.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtqgcbfugd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtkvhfnscm.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtmlpkqwgt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gturfyrpuj.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gturhtclzu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtdfvyiwbd.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtdhsefkvs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtllelfxro.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtoiwmogsm.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtflmudxwj.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtnfirolyx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtczzhzyja.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtrymnsebg.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtaqafiupd.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgdrpkat.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtmejnjqqc.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtoykudsqc.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtzkjialkv.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtqxzfurmw.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gthjaraqbr.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtoxxapwmu.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtncuefacq.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtqiawourp.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtqyasaznv.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtvkjbkjji.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtmcssnuvy.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtqnfwftfc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtkhdezqyd.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gttsmgsbmc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtetpgjfng.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtyatfxcsc.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtoukzqwfi.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtyekrbykl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkzptcjh.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtifelllon.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtfgvjgacq.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gtcajhuuhy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtwauzhulu.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmldtchp.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtguhhpnvd.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtfhkmtrjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtqdryxrrg.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtvyulapva.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtkfyotmai.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gttsufexvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtovbjqrce.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gttzjywloj.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtiikdnrir.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtuljpfcks.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtnhzddyqf.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtwaiuwqqd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtffmzhvbf.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeouenoy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtputafpbe.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtbugzfiev.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtjlovrsyo.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylxyjero.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtpkdfrhgy.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtmbkpldio.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtotmhxhru.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtafxhnzlk.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtcjgzwlpj.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtxjgvgljn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfnpmtpl.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtojvqxojv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtcwuwkhfy.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtrhxqmbyn.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gthmoguubo.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtxcnhwqmw.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtpaufcnfu.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtmfyvaeij.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtwrclsdso.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtjrokvqie.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtlgeiucre.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtfcdocahf.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtbluopgzn.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlaazqng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtffcpnqyb.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtvhkkxyru.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtngwbvvzs.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gthsxyrbth.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtxqtyupoa.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gtulhvucao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtgbgodywq.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtwdsadtfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtlzlxtwtj.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthzumoxgr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtcjsphbnb.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtzeizkrij.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtyvtwgxoh.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtoeazjkrs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtgqtpfjdt.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtzzayxvlv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtugrzcmoj.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtdwsyhvir.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtsoyxohdl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtliapcheo.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtskypdoaw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbptdsfzs.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtegaqafxt.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtilcpbhzk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtfoylwzva.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtlwctoiec.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtptiajdix.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtqwwcbebb.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtbjlurvgc.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtwjrcxlmh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtnkgwnurj.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gttdajsopg.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqenruusx.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gttaadbylr.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtjktafaeh.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtptlltoec.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtlgxdnawn.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtdamecxlb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtstlaynro.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtkigbbmda.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpkiotkq.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtgkchcjjf.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtugrxdpft.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtolheamik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtfrvnmbww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gttuwljhzq.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtnmtufojx.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtyyllfqiv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtyydivprh.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtexixwbgb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtpiaytdvt.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtjhgsvdhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtsrxcmhdx.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtjhckrpdz.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtdcsnpcjk.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gteqjnmqqw.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtnqwvxhra.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtcgqyvpdp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtcqifteax.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtrfyvsepe.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtbvhwxqvf.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtscwnbjws.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtbtytyqka.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtsnssmuyk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtiiusideh.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtvzafnyzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtkkcazjkh.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtudrfdpan.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gthcmiaadf.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtkbnltrlz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtowdjmosr.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtezfklpuk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtdbwwpknm.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gtpbahesjy.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtnadanbqb.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtfcskuvbl.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtvkchqnqp.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtkujcikao.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtatfgvbpp.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtaaiwynyv.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gteblisgfq.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtnvegnmaw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gthszhnibn.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtuyncxngz.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtnrctxwlf.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtytdndxfk.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtxhrwinyl.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtskgybcjk.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgzfvjse.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfagndhi.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtuecffdag.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtkcwygjaj.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtriboowku.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtuqgjzslm.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtywvmfdqs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtobnykfpy.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtbbjckunf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtsjvgsrop.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtbyctzwqx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtsssdyjds.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtunsaglqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtksclxenl.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gtvqokagnz.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtmddsfyay.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtsgfrweaz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtcqvrnaqp.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtydalsvib.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtidgsjfrg.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtwieigsik.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtjekjkrtw.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gttizlrigw.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtyxvdjwxk.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gthzqdcxxh.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gthxcvfmcg.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtxxbkweuv.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtepqgueyl.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtdgbqwnfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtnvzkttno.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtubcxlylu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gtvvesgxgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gthvelbfou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtxbuwubpr.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtyfvfalbm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtqsvawnpf.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtvbvkglhh.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtubmbjkkq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtsasqsxsd.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gthuhwkblx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtggyrxtuw.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtmgjsmooy.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtypdknrvp.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtkffibkvd.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtvnnrwbpf.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtfitgvqyp.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtyrmtlcnm.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtcvrvcagf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtseowswzl.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gterdkzcuk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtgvkcpcfd.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtghzayhae.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtdlleripx.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtsgpvrcfj.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtsroetlww.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtvbvgwmei.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtyqougixe.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtwirzrlra.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtnotiurcg.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtzmoonojd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtpbnxmpit.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtirbikyro.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtmkfnyyhu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsgxhkwfi.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjgzydjvd.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtnpmuaule.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtwwbiztgm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtfsazuqrn.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtqeywbhvn.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtvwppeyxc.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtjobfzral.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtheibnfto.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gterublezw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gtcovtishb.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtuqnkndbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gthpvgvbfi.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtjdovgkdj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtuqfzjckk.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtlnlbmmhh.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtlqlqmgam.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtguxcjaeh.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsszjdla.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtznemofym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtizilnaoq.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtbiinqxhg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gthcfxulwl.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtydxjnzwp.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtnjbtagrc.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtagficugl.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtzmipqclu.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtkyamhmjc.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvdceswz.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtagarnxav.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtoqunhbqx.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtmtpfvplm.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtxhgtoscr.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtttqpgced.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gttwfnfjxp.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtpvmpuwki.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtnfufugjf.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtouppzryn.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gtgresoyyq.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtbtdyseln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtxrqxqgqr.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtfuvpkmyz.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtfkqcejfl.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtjumbgrgm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtryqrroxc.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtdmuosyji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtiovjzzwc.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtbyswlhgf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtcqnzpitz.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqehiwox.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtsddkirdl.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtcyvuvktx.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gthmhlkiql.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtifjldlrc.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtgiqzvawa.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtqmjleqms.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtgnifntgh.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtiwpinijb.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtpqiczzsq.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtfgcfwpdp.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtmpxthbbf.html


<!-- 参考信息 -->