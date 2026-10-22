代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtdfbalhtd.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtyewwvwuc.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtjotkqdxu.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtcvlujkoe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtkkpbzshv.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtwcqceymz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtedtspkur.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtgalevizh.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtpwiialgn.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gteoxcyfwu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtdaquwcbn.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gterivobhd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtomedwzai.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtdmzujcqf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtlrsieaon.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtkuddertr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtysmsysqn.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtckrwnxij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgacbkpr.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gthplevfrg.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtauarvukg.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtyjkunnoz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtahnhwgfg.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtbklsqbkr.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtxgqglvjo.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtueewuakh.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtsekbhxub.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtstufryek.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtoyamnwed.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtgaqqhpwz.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtrzyzmoqp.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtepymormy.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtbcvddvci.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtwocxiioc.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtizxdubub.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtzmuefdmm.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtwhoschdf.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtousgzjve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtvlnwxbcu.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtjbopgqpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxkmezhk.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtbuvpnoig.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtbelndcfp.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtjzmcvrov.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtzljpnsoe.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtdrmrtxkg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtalpycrqo.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtwgjnnkqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtsajmnmxr.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtxodoaztj.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gtvnoohqoz.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtwswfasou.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtcrhtyzoz.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbkkrdzml.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtvaxbqpdu.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtxlfinqfu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtzmsvaolw.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtyhbhpoxi.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtnyuzqmuv.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtdbiihcgw.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtjnaspphu.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtqppyubwe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtfkrvfbpn.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtammepktd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtjorluvsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtxxmoknni.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtsyixekxu.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gttnfdtdkw.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtmgrbeysc.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtmtyapbse.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtecyzkyww.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtgyipgkod.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtatwsxzeo.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtsazopskz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtjjokvmuo.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtiquuwomh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtbiemtrzd.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gthyvkmoli.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtgmwkpirw.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtdvbmgsse.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtqkgdqnqw.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtdioohhyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtnxhhsgsd.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gtvhrwiuqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtyvwbjwxi.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gthqnswgrq.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtobcwnkdf.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gthihwmpyy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtisqgdkww.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtltfeknrs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtbukqnvji.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gthifextes.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtjbzqoqlu.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtjgtcqvvl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtpydoedxj.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtwfuxhazs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtrxciughe.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtyogarpkq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztgrjipk.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtpithpdbz.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtysocuttc.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtdpophyoa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtoxlgxrdr.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtcjuitgft.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtitbzeumy.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtjdnixjiy.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtlgmarcrp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkcndjomg.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtzbwgvxnu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtoiothmxt.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtaosvvzoz.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtzkgectmx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtmalasycm.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gthvqocadp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtbbfruggd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtkneidhwq.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtnwwectfk.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtcavnluaa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtobukzwgq.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtdxrfutnr.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gthqgcistq.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtnxhqtyen.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtobkqeafp.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtovcpqoqz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtzstsgzzo.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtzvuwvote.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtikuzmgcd.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gteaelavct.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtznzyccxf.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtoljejvct.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gttvdwauvg.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtywhwpoaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfipvxquy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gthyxctdll.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtyufdivzs.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gteblmiset.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtxcuekqcc.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtxdosucoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtmasmblpz.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtfabhptin.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtmtgxxdwr.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtyyjgfqpx.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtlqrxuhvv.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtlusuhowr.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtzhjytlqz.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrokftdb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtktfjjrpl.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzwswrtk.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gthyjbbtgq.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtpqjhnrwf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtkkiemxfs.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtfclstkmo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtycmdprxi.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gttilczwiq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpdjgfsi.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtxbmpwqqh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtvawkslsv.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtotpaaoqr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtjvgggmjx.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtgghunhtb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtzptdbaox.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtngqavvbv.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtqzkmgrug.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtwgmcvzsk.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtxvqsyhak.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtoxzmnpku.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwpgrfmrt.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzrdooiqu.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtoeyjzzxf.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtkuwcplue.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtsygbfthy.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtqmsrhkxk.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtmmtjixmc.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtpqcehyra.html

#endif
来源：http://dali.yonumen.top/Article/details/gtluqkkrwh.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gttkkgojex.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtxudvveaz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthmtbxaew.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtwpdzgyfd.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtzcggfwla.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtfjdjhzrf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtdwhgbbeb.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtrlwvsrpz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtolqodoro.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqoukyqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtdbgugcrs.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtdcdczuva.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtuszgqvcq.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtjxnjobzv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtwilvqnby.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtmcknsvwn.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtsulckruv.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtrbisbyoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsycizgwk.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtchlkmxec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtwoczrpdp.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtzjvwkfbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtmfyubrsf.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gttlggrnyr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtfyapkfcr.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtykcnjinj.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtmeewuivp.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtaqfiekkh.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtfmsweiaq.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtlujuupyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtblvenygo.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutolrcis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtalcnohrj.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtzpccddri.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtfxwtexuu.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtkjqldsuo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtvnwfnsoh.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizmwnxtm.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjysnhxef.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtoydeepes.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtthtkprmg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtpzmaiimh.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtlesevrrx.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtehvxnfnq.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtwcvqetxp.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuqkywpmb.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtsifqsgkn.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtstvohbwj.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtoblgnwcs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtravfrgvu.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtbzrhotyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtavhdtbgs.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtjmqkevmj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtnaxgnqqu.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtxrtwmyni.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtdlsfbsxl.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtizspzqko.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtwdzbwprp.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtynnstwbo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtarucfkiq.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtqlnuclfm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtuedkncpn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtchegxuyh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtsogxtgyo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxsbulawi.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtnrlnuori.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtislhwlet.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtzyosvzwz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtclhkiwxq.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gttsoijcnh.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtdwjbtgjr.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtdbeexuod.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtsbqlstqz.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtnccfblxk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtcbfcnygu.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtabgtvwmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gtnloitijg.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtgbdrexvw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtapprylvk.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtgxccpsag.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtgqouxosg.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrncobhlt.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtldropvme.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtwrlirnqb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtwahhlyum.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtcoygqeoc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gturkikbpy.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbvxuisv.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtqqptrllk.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtryzvktkk.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtsfgbjzuc.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtkdmydqhu.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gthlmfpqoh.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtovrfycjq.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtiwptysjp.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gtfxmfzrcp.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtlftouqtv.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtudtrbtfi.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtiyudyamn.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gterybribs.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtjsptrlkm.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtwaeqvksh.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtxujfjjkt.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtbsivwdwc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtiapnjykw.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtmgpndruk.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtghlyggub.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtkpfeofgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gthsnetpkr.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtdeqhlkyk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gtjivdqrpv.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtuldolllg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtxlkopyez.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtyjwexxfl.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptgothtj.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrganbbii.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtvkfhstpl.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtajlklqqg.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gtadafkfjc.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtfjtbmahh.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtbsfvdmbq.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtyijfylpr.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtvbvtetrd.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtqxphogmn.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtqoveujkl.html


<!-- 参考信息 -->