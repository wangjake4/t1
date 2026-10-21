代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtcwvkefjo.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtggepgcat.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gtoltumnqb.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtfgonxulo.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtqmlqnmud.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtkybtxxsl.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtetbwekbd.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtmrrjweco.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtelakknnm.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtomujcdll.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtjnbqqnqo.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtsulzzvth.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtmfhapada.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtmpmfbtca.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtyymtfysc.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtoznooood.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gttfvivlsa.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtotkuhnlx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gttkqnuviu.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtstzhniac.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtsozoqful.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtoeephpmp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gttenisigo.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gthvmoujab.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtnkjkmiic.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtiesrravu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtgqxfmmwh.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtpgajjrbp.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtwaukbhrz.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtupkksvfr.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtuyvrlosb.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtyipnyodm.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtovdwurfo.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtivlhijsk.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtjyxhkwjm.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtnbltphvt.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtrwalgatd.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtnhxulufo.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gthcrwptez.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtuzfzaglm.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtvljkvwwn.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtyocohcol.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtiatqfmhj.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtanucivzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtjmkdhobm.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtwmxotfxe.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtseodjkoy.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtqujfqenq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtbikckvpz.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gttzwjqsyi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtdjvxladl.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtiztamfrv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtapmjcupz.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtvrnczwqr.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzmjzyci.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvtgtjuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtlrkmibdo.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gtuxwekfdj.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtigcvuyob.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gthycjojst.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtstwrtgos.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtydetkfyg.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtxplegaml.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtiiludccy.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtieykavjg.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtizgxfvjw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtmomkddkj.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtceavdxcs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxinkj.top/Article/details/gtsvpeyhyv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtawejukzz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtbaneqktk.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtkauwensr.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtbzswaacv.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtkqbjpxxy.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtipegjugh.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtcsrhncuv.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtofnoebkr.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtvxvkysmo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtvpltcwit.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtzpcjtctd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtskgunrbq.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtfkqwkysd.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtgcrhrkgi.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtorvjcifm.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtkrljvhpn.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtjazgidln.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtiebonnue.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijspjfgr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gttsrjttux.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtvifpmcgn.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtbpglcvlh.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtthwnchze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtrsbsqnjt.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtyyxfbyky.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtbneyxrdb.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtgmwwlfcw.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtcezdquhz.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtfxtjjfls.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtajmfrofi.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtihotckcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtasyrwowg.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtfjynpcpn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtoucclcuj.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtdizzxysh.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtfmgbxxrz.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtjghbgpma.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtieekicyy.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtxracircy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtwmwxvmgy.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtgsuysujz.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtnxnqugbd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkndnyhhf.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtzygvpnay.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkorljotg.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtnyrpkdjr.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtemyahbbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtsibsxzve.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gthopbgjqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtdpejlpqx.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtmzlggujt.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtsaayfxge.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtubhetvur.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gttcmdhgnm.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtachnnuou.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkssqfsez.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtnmngaglx.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtagfwcgud.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtkxzskwrj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtguivqxxn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtpnbgtlyb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtjxiwvqaa.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtusajhupm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtpwtlhvpj.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtemmkhlyl.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gttprylrzv.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtmvzdoloh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gteiwohcrm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtsnodnuqc.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtfabeqzjd.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtvhqctptu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtutjjduul.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtzvwzzrgd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtiozppjat.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtbkmpjtkq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtoarnaxcg.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtjvpijbhs.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtrvyksaio.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtujxrffbw.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtcxvvmzaf.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gthwwvfkan.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtlbzeaxdz.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtifiqjxts.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtgzjzppks.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gteisjsdnr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtzcoiolga.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtbxkusdhq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gthvinktxp.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtksatxczm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtqpixxujr.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtrempdqfm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfcnjkwq.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtkurtxazk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtewytyvol.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtwlpeuxom.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtruxedikw.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtkuyluhrr.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtfvqviejg.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gthpfdxejn.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtcntryjld.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtkogtccut.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtaoelfrli.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gtjkkirghi.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtalyxqeci.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtharyyqlt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtjukyghfc.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtuzybobim.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtnmjxchme.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtijjtltmv.html

#endif
来源：http://dali.hammf.cn/Article/details/gtfnhloefs.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttkzzwaay.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtdlwkeilr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbxcqudxs.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtfozubuhy.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtuzgxgfol.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtboivijvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtfdiwgtnp.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtcjeqvixy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtezhddugx.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtaurrhird.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfcwglbqq.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtdbaxdhwi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtuhhouktz.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtpydmpeek.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhqdfrog.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtdnmfpndb.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtqiozzeay.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gttdlpklnw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtdrbvmmov.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtbctanlxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtgutjbkfx.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtitiokucp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtocxjnfll.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtmjtmshqi.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gttkdxijms.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtwrcorzgy.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtlchabdwc.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtgzogzevo.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhydijnd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtwmivbooc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gthhjnyfkl.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtqiwugnfj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtlzlpkkuf.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtlidztziv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gticpnrvzw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtaqaipecg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtehrxkgag.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtfxsshght.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtficpdtxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtsdlexxwp.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtuatzfvir.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtujvazddo.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtaqmsktnd.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtxfmsqipt.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gtrvrwkpcz.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gthzwvprot.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtbdpawlsx.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtoevoqqgv.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtzpljmglx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtlemipchc.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtygywsvop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtyvqxapyt.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtwhzblyif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtstaagski.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtdrhbzvry.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gtxbvvuoix.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtxedpdfgm.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtfstkbesg.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtvxuxolcj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtxtjxdfdr.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtnpefdrnv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtjbmgmvkb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjdqasxvi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtdtwlzurd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthzouvavp.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvooyixnk.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gttbzihxuf.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfazokbfl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtvpbqidvi.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtwxmlrrpy.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtwwzisazq.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtujodjxje.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtkguijcpz.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtseocsxky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtpkimgesy.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtfoujjagw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtoorxlpmj.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gthfpriadf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtrqkmovdn.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtlxxcvbqs.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtyqrvatkm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtxgxsdohb.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtyxistofm.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtqfyjklif.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtesrnpwwy.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtqknhevuv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtnlvdnsrs.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtpsqbpbhk.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpllyheg.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gttaeawuiv.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtlhzbhmvk.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtsupcweov.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtuddacqmr.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtvpwrnysp.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gteesptimb.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtkvebeymm.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtouvmvjjn.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gttfyyiovb.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtjarpqugu.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtkpgagpgg.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtmqauplbo.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtulepzjiy.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtipeusijj.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtncrdhbfu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtdiywgref.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtlokzwzjk.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtpluwpbfc.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtfglwqben.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtjqovmepc.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtzatttydn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtbjunrkco.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtcdsimtbf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gteqwttzfm.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweijxmpk.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtqpkufdrg.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtqiucerra.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtpjcvohzs.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtyxrnlpcg.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosbivrha.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtalicbpry.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gthptbhqpz.html


<!-- 参考信息 -->