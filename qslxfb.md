代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtoxznehho.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtrtabpxhm.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtnffxtnlb.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gthvipuxyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoadtdxc.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gthavcjuaj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtdzikjcgn.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gteyhlhfji.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtdtvaxkli.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtvrueyzln.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtqgcugarz.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtwfazratz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtjhkjwlue.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gtegnsqvpx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtkatsrcnf.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gteaxpuhvr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtevjfamsa.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtsiagqgmx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtdixaotme.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtghxcqpns.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtoxbntsrf.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqbofpih.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtdyddxuhu.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtedcxedsm.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtjficanrp.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtbmawvpjd.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtnvdczklv.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtwofjaztk.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdleeusw.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtndoeizmz.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnmmcqjl.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gteyhhposi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gttnoglsct.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtgqsxvfvl.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtxaiyemin.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtiknoepsd.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtiwhzzjbd.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtvzuqbfib.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gttevllqrl.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtvouklggj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtkkjufoxm.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtfbzviwdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtqmmpddkk.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtoyazhver.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbihzjyha.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtzaebwekh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtbauxrikv.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtbijyxhmi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtuojnrgbq.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtatsciuzs.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqemzevh.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtvcjgndsg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtiuoyxztf.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtxbaazcgz.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtgxmmryte.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtvzsjuryd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gthnntkeay.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtnuytfhaz.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtrelanrkg.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtzgeyclby.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtjwatwaql.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtfnfpottm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtywjfwfrc.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtfnsyrafh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghnxbrou.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtrszbipvo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtdemrwqpj.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtydkytqcd.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtogfpufdr.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtamrjypso.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtpeufqewc.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtqpeqondy.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtapyheumv.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtnfqrxvkg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtbdlhlwxc.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtuavlusep.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtxvihcwiv.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtbkwhaqce.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlnjsojs.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtvyzncepl.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gtqfneoetl.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtbznovphq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpzgilsue.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtbhjvjuxw.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtapeitsxk.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtpjnhemas.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtrnxknhay.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtwyymxnyh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtcjknouzk.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtkrowylea.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtsvmjxizx.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtotzvemdw.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtrmklkwyf.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtrfbebrvt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtsujcwjez.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkohfpxmq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtcigaufpp.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtqxrfwyjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gthimystko.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyqbitek.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtteewilib.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtmbuuiqjn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtyimfbqzi.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtxqcxtjvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtxiugzhhd.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtowsexxdm.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gthxrjhldz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsnkyimhn.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtqylegiek.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbtrftpnb.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gttgemisnn.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtcmlcrvri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtczmtbdtc.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtqvyprmif.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtqvwlvyzm.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtnugsysjx.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqyzsdso.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtcbqlmfsi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtsreuttpu.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtsfnvgynq.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtbtimiahd.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtbfccahym.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtgvresjfd.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtoetbeyay.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtquxpxpih.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrijjds.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtaftodvhx.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtgnlwqqry.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtdpcasikd.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gtebgjkrch.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyhrmaog.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtdozkshpv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtzwwjegrt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtldlhwtya.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gttgksqkzi.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgmvzqjtj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtekzwvyhu.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtlvhorfwf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvdeahtq.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbakbhnx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtalmqbhle.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtubvbubmq.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtjlsjilye.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybbkslmx.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtxngqnweu.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtmqdeqnxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwqlexuz.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtysfhywgg.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtlsvljgxr.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtuislwzbm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtpskfbqao.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtojkdmuyq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstkeqkpt.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtlwdrqzvp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtoyuqgcnd.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtovhknatf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gthwqtiqwm.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtpnrugfma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtpqhdagty.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gttetjcdxa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtglpcochp.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gttngwnqra.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtvklwysbf.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtsnoeetzj.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtsraomklg.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtlucutssc.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtuzzdjamc.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtcemswnnx.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtnjgcjrzn.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtiiuzlpnn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtfctyaclb.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gttvcclhkr.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtkbznhsrb.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtasanriwv.html

#endif
来源：http://dali.hammf.cn/Article/details/gtuohpsjgj.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtuzdfvwyl.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtfkjjoliy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gthkaxoesb.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtrlmjsndh.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtzvfxdcrz.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtklqteiea.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtbwhmdpkv.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtozsqxwsz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtkjsffogd.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtztbmheym.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtuhegtjhg.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtdctjoppm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtrjczamva.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtzzjucyhd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtmieyytyz.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtwmykvjjd.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtbapcjqmq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtrsjxkkfj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmmghodp.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtxplovofh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtqzbywjld.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtndevxqnu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtvntrucax.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtsjriicnc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtcxfnowfj.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gthtvjpfcr.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gtlljajvyk.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtuxmauwyu.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtysqxezgj.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtnasjdjpl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtpmmlizxa.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtbwfqrstr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtyzlgfgcl.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtcgxxcoqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtggqaosvi.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtwnlgndsd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtjolmpoti.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtsbfoxeea.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtygznkceb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtohkhvhwg.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtxttkxawp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtgoyizoty.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtiylwuyhw.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gttmophphd.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtjyolbqdc.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gttkevcmhm.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzkrffxh.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtlgwwvcco.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtswcwwlfq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtbtpflcin.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtvsxskffs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtbqwpjtez.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtkdbvoemw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtvhzwpwsb.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtvsdcpgyq.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtfqajdlra.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtbdifqiiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtstszciut.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gthrywqttt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrguklcq.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtripdiyug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtocclgifx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttntobmkb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtckbovphl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtajgngcvb.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gttolshqkt.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtzclpapzi.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtbiwmakjd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtglaevkhn.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtxgqfcraa.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtotkcgfvp.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtuxylbiey.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gteekinrkf.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtohxriiym.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtazcooffv.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtexnaobuq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtxfrnhlhl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtsjxesljg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtiyxiifix.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtlzvxbkly.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtkpohvtvg.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtgquwemdm.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtkvtkzcqb.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtylvpcwik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtfubgnqht.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtnychgyir.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtsuykwnth.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtjgcgdhua.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtrfecyznq.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtthwladzv.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtvcmwyecj.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtdhfdydlq.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtylihxpgd.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtsnrybpdc.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtpmpkoner.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfvyiput.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gthlxwkfhr.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtupbbouai.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgxwvkll.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtssrhhsin.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtthleibys.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtyybvgars.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtfuuwmnin.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtqekmzaem.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadvsdgbv.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtjeatssbs.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtatyvkfst.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtjewpbvco.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtwipcshue.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gthodcxvmd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtteaavyav.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gtvdbtttdn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtfxtsyaqe.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtqqzkraie.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtjavrnqec.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtmpuehyeh.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtbzycpgko.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtsjjvsfeb.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtwaumkbup.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtypsdrqab.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgaocwmg.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gthbuwswgh.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtsyxxwmeq.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gttspmfudo.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtzsjbpecr.html


<!-- 参考信息 -->