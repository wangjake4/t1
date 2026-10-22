代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtefpfaofa.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtvhfyugzx.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtsnyjbftz.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtgvfyhdxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtocobdrgp.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtdqmvspcs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtxgzielrn.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtjdtutxiu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtaphjagka.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtsigqizkn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtxgayhmno.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtqbngkwbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtrsfjxtgs.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtdphlbgog.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtfehuwzey.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtfvcumksk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtqysvcuss.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gthsgkobwj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtkuyqzdgu.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtbummqany.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtxaumhudv.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtqbuoajzi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gtmxrjutgk.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtfnljlnbf.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtzwwiqpyw.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsdkcwpp.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtyaxwlqok.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtwntdmjag.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gthgjruzrl.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtkjcpxdlq.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtvanymazx.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtngdseprj.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtszyfievm.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtoertpyvp.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezzzuvfj.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtmzwwnwab.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtyndfynve.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtvmrvtjlu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtohdgqchr.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gtqnynxtwk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqmkyoka.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtgzxaxvxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtnliecqbk.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtxtwnovcv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtkfszktlh.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtuovikprw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtvjavvqkp.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtokalfxzx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtjpzbhqav.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtjgvnprkq.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtpywnblyq.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtzbdvezle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtmvdsmado.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtvnglpfcb.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtovzekhdg.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtfilqdmzv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtbmexuizz.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtvvblyfdl.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtosfyelbx.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtnaadwoon.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtzafbrzno.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtxypszgzp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtponydwsb.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtoarfuuqy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtrimqilwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtruqwyjnv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtkfkripog.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gthzmhpwlp.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtyxgwwnot.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtlngabdnu.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtcmnjilnh.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtlfgelttk.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtdpohcuch.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtncrynjif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtzmxprhcl.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtvlbtmxpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtvifwcncz.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtoyxlgrsq.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtmowxerct.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtaiqdbtos.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtrbhckoqv.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtzumvmzus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtysxyqggp.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtgqqyxuic.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtbilyjtcg.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtuedohght.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtvxaqjnzh.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtjpvzpyqn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gttdtbqhxj.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtsgssllyr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gthaakytfk.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gtfomrlwmc.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtwmwmrwnf.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtzicarzcd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtoczhbmwd.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtmwxuljcz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gthyivamfx.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvljlsnbd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtqxukgphv.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtodggtpck.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gttocjtgoc.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsprisfr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtquadcsck.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtwctzlnrh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gttswtctgk.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtureqheca.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtkcbeapcj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttxctvvse.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtiumzvrwe.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtamocbjhm.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtiqsrnebf.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtkggwkgpv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtsxostalk.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtmyxdqlhc.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtpggsrlgg.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtlfrlluzm.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gttbtsxmtw.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gthoxhccdr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtdfnppxrv.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtuocyqdyw.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtmfrtrjha.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpesvjgiv.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtqavnyvwv.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtlcaaadii.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtararbhft.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiicszai.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtrwvzknjk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtiicerprt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtsfmqqwuz.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gthwsaazki.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtanaqhptn.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtijqemump.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gturinlwgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtyvmponsk.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtxqwfsofg.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmlxposp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtlcwvdpnh.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtfbavwmhv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtytaxdrfu.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtphytwpnx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtldfydsrj.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gteiygxwca.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtwoeslmad.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtwristhmg.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtijjrokar.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gthvuuqlxz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtzkppcnjk.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtsqmkizuy.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtwxeoieai.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtwjwxvpze.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgekgvrw.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtipbosatj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtuqbmwwji.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsewxhoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtilwqhtqo.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtzngaaiqu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtjgouxrss.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtuicczkgu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtguwayyuj.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtvybyvzcn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbaccnry.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtvjuwtyjc.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtjztishbg.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gthzeresxc.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtnfjahokx.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtgvqhwdsr.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gthtjxsfqt.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtrliiepuh.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtuqrxmnam.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtcrccyysr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtwcrknidd.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtjrjdtvcr.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtpueebwfq.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtzlbvtlat.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtrgtyojej.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtcjnkkzfb.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtmuedbtxv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtqkcfidbt.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtfbhvmzdi.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtafkreqkp.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtucibputf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtpmvedixf.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtsdimcban.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gttwexcips.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtsnnuydtb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtsnncnkzy.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gttrcpfflo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtnotztqhm.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtalgakrun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtigacjsns.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtdhyxnyha.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtdmcfbppx.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtgcxcjqkq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gtampcfrwc.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtbesfyqak.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtktnttzoa.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtcqrsytcb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtqvsgzjox.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtyqkeufuf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtveidletz.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtgbyvqbgu.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtksyprzkb.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtswiyquhq.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtbkddregp.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtfuuemqoz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtqtjihqnh.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtuvawgpsv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtrbxacyxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtihapvipv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtrogrbvio.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtquntcrss.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtdsdrmvov.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gthotozavh.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnnyfjce.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtbeclrnfh.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtomlcaaow.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtxmiqkvyr.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gtfbnocidj.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtndreuxjh.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtusfuhrvk.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gturdpykgu.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtrcbvsvqg.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtglkeofpl.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjwunzguk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtgvixjyrj.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtjbzrzstq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtlwnadzds.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gttrbjxfph.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtsytrefqw.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtknpwoydy.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtkkjwcfng.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gthwvwrcae.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtwtehlkzn.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtajwvznvq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtrylhfhzg.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtrvngijcx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gthqphfoju.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvycysltg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtzdsmvsda.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgzipuhdw.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtgxjnlnjq.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtwltqsyxk.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtcemfrdyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtjwaxvrwx.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtpqbjrpyw.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtwemasvpt.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gthekompgk.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtnarvsztd.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtznupsgkg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtcppenakz.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtudjqeaco.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtfolwdhsb.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtnfkoalhy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtmgummsdj.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtmdzfjhrw.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtgecbnydg.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtnnlqevan.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtgnbufqcp.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtgxphmjhh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtipwtelvw.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtnhlanwjg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfojqngv.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtcyjpxzzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gthlsdrpgb.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtygftpwot.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqmdshfw.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtakewoehk.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtbcqtqzot.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtrnayrzcw.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtupliuwyr.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtpxnmtjyu.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtvhzicubj.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtwcmwlxfj.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtpyqvjiud.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtlrmtyxby.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gtzbscfmfk.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtmfuoybin.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqyijdew.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtzagsltzx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtvwtowqqm.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtfxeffviz.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtwqjtlotb.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gtebxuiwzz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtbzfjlztl.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtkffvbwld.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtbzlbjnyf.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtbguyofxo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtvwlzltar.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtscdkjybw.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtdshwqebu.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtpoyskmhe.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtqhkjbfib.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtwvcxqcbd.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtwpmeeuos.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtgdzkyvmh.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gtcjnbzean.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtacnkzcuk.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtyivvhpag.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gtkniihexc.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtllhebrba.html


<!-- 参考信息 -->