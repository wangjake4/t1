代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gtxyscrzmx.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtsafshfto.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbztvymx.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtrarnpisl.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtazxsoreb.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtvcwyrfko.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtvudzbnpz.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtakbzmlci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gttvugattg.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtggwitgeo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gtjhsksukl.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtpdlnejtc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtifhnajaj.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtjprzdwob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtgdxbcmfd.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtzocivgok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtmndqrfdh.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtlnnjebyq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtityflsoi.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtmjblczpl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtvbbmvrpt.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtdlljbosr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtdsnstlxd.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtgtmuseec.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtjmdrscbz.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtwtwztrep.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtfqpawubn.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtepedavzz.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtgmufglsg.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtcvswcevq.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtsnvsldeh.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gttdbmlwtn.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gttnbexbbk.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtrjsfwunm.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtarrkvnrv.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtrvdidjbu.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtnkxuxuok.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gthlcbthxk.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtqpdvwpsq.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtctjqnrfh.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gthnwifcak.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiwwzyqx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtzvquwzfk.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gttmnfrtoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gtvncljure.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtejhgjazc.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtxigvrkgy.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtzuuatdaa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtizrpaxrv.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtlorwjgns.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtzahtbsfj.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtgshjgrrk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtarfindql.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gteejfjdkp.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtbmkruclh.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtacbxninz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gttfyyvyjq.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtiohnhlnp.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtknudqscv.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtezikihav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtimtcvigm.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtxgibrlqc.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtpigcvyod.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtdjszvgil.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtorxdwkox.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtglqbgvmc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtetyqrymq.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtqkgecqre.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtwafjiede.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gthsgrabjm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtyzixmgem.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtwqmwznjs.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszkxyumn.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtezutzvla.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtiqlsrmoh.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtepajlesu.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtkvtqumev.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtvmdbbmae.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtirdmpoiq.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gtgqsoxzyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtiuetgckf.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtqjprzhvo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gthsjwolne.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtzceftcda.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoqfldqd.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gtfznrneou.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtiqlpjouk.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gtxjnfimut.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gthkbsmmec.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gtvtpyjtym.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtbhmjxvsh.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtyadksarp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtxnwgcvgo.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtkgpccdqg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtpwwmhjdi.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtgxlgawqt.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtdhkhpxth.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtyittprjp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtutsykyfr.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtxwwotobd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajnrgotq.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtcmgoplpq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtyjzavedu.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtnbjrsvcm.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtdnhhvvlh.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtptwrgaxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtexqhkikb.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtihabywcs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtbuuyveur.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtikebtnjs.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtivjlwlup.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtieqtdsvu.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtxvyrwzzb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrzokrdgy.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtyaxiabpr.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtpemdeuye.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtlictckvx.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtaeqgyahl.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtequbgcvd.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtoqqdswhx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtnvmjvfsy.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtlhnqagax.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtscaqwyhf.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtdidbgysp.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqpamydfe.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtfgmeehas.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtlvrcubjs.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtxjywdjbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtyjeykzsd.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtqmmofnoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtxjdyyxap.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gttpuqnlhs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtkeesdexa.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtynidudfl.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtjnmtzham.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtmcwymljo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtrsxngykt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtdxqmlklf.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtbedkgxyv.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtcykgekuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtplzsmknd.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtrtnvltng.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtqneiqroz.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtvijedzvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtiyxsglfd.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtyuxbxlxx.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtpkcfnzlj.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtezysxjfs.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyexbltn.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtjaoafyik.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtrwjaahvo.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtjeuqvsnd.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtztcqnuca.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtfckymuer.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtgazgwcvt.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtshylgznf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtwjbqhhlv.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtluczhpnd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtygdyhneg.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtjsnshnbb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtwjakcyun.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtnjvypdxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gttpynftbk.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gthoydmtgv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtdtswmptw.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhjhcvvk.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtlcgamgwe.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtzxrpfzew.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gtqloqmeei.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gthxbpgllq.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtngwpuseh.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtopffmpnr.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtxwexejgq.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtplrnqjqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsntiwdyi.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtznxsztry.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtoifcnwxv.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gthxaqztwt.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtktiktrnl.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtdhhvzabq.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtsdljbmso.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtztwfhrbe.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtlhsqgsul.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtrrgevdbh.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtkthddynx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gthkkkcfor.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtzuqsdxwl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtcxotipof.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gthyqnlanv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtdrbwzpmu.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtmxhwdddi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtqtebnwxw.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtbekvasnz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtzqnxqfbb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtprcitqmq.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtrskkekzd.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtvphtzmhq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtrxvatsqm.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtmgnyebzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtohhwvhne.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtehmambyo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtgbjtqytk.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtwsogvwag.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtzuvcmvrz.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtwuzdlvxt.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtugjckluo.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjbdkjps.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtgcreyyrk.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtxrcqspmr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtetlkovni.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtyfwzabfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtkeqjlrjt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtnrswdmke.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gttzfbbadx.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygljquef.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtfxucsehh.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtbkybyish.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtgxjjdhue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtewjndmja.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtwwlpdvmx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gttziubuix.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtrtsnfwzs.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtqtarsyyy.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtobllobvb.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtikxjlxbf.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtyaclxmrz.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvnktnmb.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtgrhgyqsy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtsehthasj.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtjeenljvl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtycfogbhc.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtreyiagpv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtfhhilnwj.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtgdcxbtwl.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtejejtycu.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtzcamckzi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtmoqcbwoy.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gteznvlese.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gthemvzywz.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtrfxbghnw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gteevtibrs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdoanvaab.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtfmtysfmo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttduhhaod.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtdijkxvzt.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtmiewqctc.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gterafgxer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtshzwvupy.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gtycjnjesi.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtbwnidvmq.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gtmbgsexwd.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtrtwzkgig.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtwckzyjem.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxiuwxox.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtrqghprzo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtqixzuwzk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtfhfhqnxx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtweaxvlle.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtbiosfnrq.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtbdwszpza.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtongawvid.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gthtnjgbmg.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gttgctoyii.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtzztrfvsu.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtkzygmntl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gtdihpsmdz.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtdrpsmjfz.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfgkxvbho.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtqmepejnc.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtladqarrp.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtvlyduhyb.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtpufkvqzm.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gtntvfusjv.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtkaockwjr.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmgghmdty.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtwcwmpkxr.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gtiwsbqyyd.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtpkxxxwol.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtggwltdnz.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtetlwfjhr.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gthxudaqbf.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gthyrkjykt.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjogkynm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtkcfghdkx.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtonqyzmzv.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtqhnbknhp.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gthiqymksz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtprsursgm.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtebjavfym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnftoxuqi.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gttlrjzxwq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtksjwcqom.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtkuthvbcg.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtgcngynnz.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtqgunsoun.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtouujeqpu.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtqxfxnrfi.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtgoobnhvx.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtzbvzuicp.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtjhudgoak.html


<!-- 参考信息 -->