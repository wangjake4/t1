代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtjzlixhjq.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtntybxrmg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtkadvymgp.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtdzvhookm.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtgdcguill.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gttyngueou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtdaltrukf.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtgoreyili.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gtwmoamtal.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtjcdznlaz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gthfcckynf.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtsdpzfgft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtcsxstsdc.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtgzaqvqza.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtlbunjsii.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtfryycpup.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtjodsivwe.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtxqquxyxr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtutnfufoj.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtculzwhqe.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gttozwydlb.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtenssltuw.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtmyzkrwse.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtmvzrfdrq.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtvmhoyojw.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtoavpxvra.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtobwlnova.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtdwxvsiug.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtqjswjhif.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtbchtzfjj.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgzwkxzx.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtwhdbyqgs.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtceqievyf.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtdwdlbife.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtnxaioift.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtparyiikg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtjbhborou.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtjnrrglho.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtquhtazux.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtcqwpnjuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gttcgtgxgw.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtcszrkoff.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtkwmallqm.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtbtshzxhh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwqiqqsm.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtcgrcgitq.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtmcomkxek.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtzozwafls.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gthhdijjmo.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtancnyara.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtfztfmsxr.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtfbrizjqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbegxyuj.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gttnfkyymn.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gttuifrshl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtdqnbpuqi.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtyygvzeen.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtnnovnhrt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtfsjwlpre.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtbuatoyan.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtdkggozrx.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzgpbpvv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtgdcibxlg.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtqwdtwlcv.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gttdjeiqqy.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtqqvxbjbs.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtuvxpgnti.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtcmadgaxo.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtdztsgykv.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gttymrwwnf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtzqmcuzcr.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtbygzxnsm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtqcjhwzjf.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtmsmtdsbj.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtdfqxligx.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtouxwnvxy.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkzvssdw.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtokocjpzl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gttqwcbdbz.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtdmnmmvgy.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gttrlhkssh.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtklfiqryu.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gteepvtkyr.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtcdztanwa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtwgbvrekk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtqahbmayn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtshnebxra.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtajpiscyl.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtwjkhbder.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtvsrzxgcm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gttgejfsup.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtrbxxzbow.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtlimgjqnh.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtdhjqtolr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtwllnhiyc.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtgildipoe.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtfqqsnlwk.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtyiprzbwh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtkpyhpzbo.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gttzuwxxce.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtkyliogro.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtlnosvyww.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtaghmztkv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlpxdrxtp.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtaeezuumh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxlvdchdb.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gtclbbjeiv.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtcezggbrk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtrwnysvrx.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtgkixkfbi.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtrplnuzrj.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtftikaymf.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtvsrupbht.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtiiteiswk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtxrjftpqp.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtrxqppvht.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtlyiflloc.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtlwdddygi.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtnoavscck.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtlvhdyvfo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtpypnzhgm.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtldzujcrw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtziymubnr.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtgixgnoyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtdunazzwn.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtqgkuxizy.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtpdegdyra.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtbvtadzwo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtskzzgdna.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtkleudvwp.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtawfhdrew.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlyoxhbym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtvfgrwnqz.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtzrngnyci.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtrtdlgpth.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtmdwrpbvw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtdgppzirn.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtayjeoqpr.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtijcxqkfh.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gthleezray.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtalwegdsl.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtfetuccjw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtcixdyyxk.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtkhnsqznh.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtfooutamz.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtbdoqzbld.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxvjbqdih.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtyaasjwse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwwotzza.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gttqndjmcx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtskzkyvqw.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtapojwowt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gttdrwswkf.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtnofhhsmf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtacjbkmjw.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtcrdpgsxj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtlmvunnad.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtohfolodr.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtvnazecgs.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtwbgiccai.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpguvstq.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtfnijbhgc.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtnzuegdnj.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gttzlznunc.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gthcsiqqyg.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwyhsghmk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtcwkiyrkx.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtazhaqrei.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtsbagugkm.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtqgrvqefp.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtatzngwti.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtilpqrmso.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtomtlcbzb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtzvxaabmr.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtstkffdye.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtevksemct.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtnfopkpaw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gttuejilhw.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtkssuutog.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gttbnbjxmn.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqavxpuh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtnnbsdghb.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtmgwidkho.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtqdrahsks.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtdxttekpx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtoaqbqvbi.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtlribmftl.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtxrkvqgow.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtetfhljxd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtgywryrql.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtaeeujwsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtfsiicvds.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtajgdiunb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtyyvshyse.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtlrpypwki.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtarhtpkrg.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gthzykjjwb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtlzdnfuvk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtmwfmhqhk.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtusiezbsx.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtpdfpbwae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhjdkvaw.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqhmahze.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtjuoozfyv.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtikhajixk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtvfjhdcvz.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoxseeit.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gteuyemvdk.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtztyxetnh.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtmtoyjgyx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtpzsnnphc.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtdgciwpfq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtcbvirnqn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtrwfhwpsk.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtdezeqqis.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtfnjfpval.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtxfpceoim.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtaouuzgww.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gttcfrqinq.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtbidufcrb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtakdtgzug.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtyoycpeyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtfoybekbo.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtiwsebckp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtlhanllnw.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtzmwiqksd.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gthqzanyyc.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtfkxezqkj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtvdleoxfo.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtqqxxfzdu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtrthrehhz.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtiytdigyt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtwzvuzrdc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttsvcwrtl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtmgwblelx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkbnarwmd.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtwbbzsceg.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtedinupcm.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtppybakkj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtbodcwfza.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtbizxagtl.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtjsafmext.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gthnmwlzei.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtgammdbdu.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtnincvhir.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtjrqhhvwm.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqciixzak.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtlogbmnbm.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtedolqcay.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtfxtadajp.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtldxzccbo.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtoeoezfli.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtbxkplssj.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtqvauommf.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtbpvlvfvn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gteufknqua.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtnmlknofo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtkabpxoox.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtmvhftpso.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqglzvxoa.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtscdmmqxu.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gtkxsgnmxz.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtjzymboag.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gthckchsfh.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtyqduboyr.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtuawiynfl.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllevjuti.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtpvtlopyh.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gttfnbrgvo.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtezxyyyqu.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtiflrbsyl.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gthkedkpdk.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtoekqbfop.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtuqacxxhp.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoffwryfu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtawvzfrfr.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmavpzoxm.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtnqknreca.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gtnordpsjz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtzxgtzhse.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtdvmesrjo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtfnbianae.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtruybdgwb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtqbsbmodh.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtkhklqoqi.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtkkuazhpq.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gthoaqsnzu.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtcvjwivxk.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtmxcgbfys.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenakmfuu.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtkmpzmqox.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyjhrwly.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtqunjrgsk.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtozjnliwz.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gttegboijq.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtidmplswz.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgffvyoic.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtutabfd.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkxmikhb.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gttwmsfxzu.html


<!-- 参考信息 -->