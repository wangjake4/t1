代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtzlaxoale.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtueomhvlb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizscoqwy.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtmmeczhsb.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtntaoniyf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gthuxhuluy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtlhxuchog.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtsvxzrloh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtbqbkrcjl.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtvgprvfcy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujhzwvpy.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gthndobnkn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtlkgvtkkg.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtlmcljslu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtsedywdfz.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gthxizjkzm.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmofvevz.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtenafyjee.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtekbpvnwx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtimsbbtiu.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtkytvxsli.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtaqvctwap.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtoxqpkkoy.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtglbgtulp.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtcdxzrzvz.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtedepbfqm.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtesdbynhq.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtvmfupmwa.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtuznsfwxw.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gthenfnpee.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gttpfzfzpm.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtxdncxwbl.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtppgdepxv.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtgbvvbulb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtnzxdbqrf.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtgijfnncm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtpemxlacs.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtflhpxdtn.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtyawcvxrk.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtaqeqwsih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtmccphkbt.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtytovrixb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gttoywnkbk.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtgvykqijw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtqwwdvkwy.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gteekxfzry.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtyevjafmx.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gteefuddce.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtuhtsytqg.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtlkdztqfu.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtqehpwjex.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtidiycxaq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtwueukzcu.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtdkhltxpv.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gtwnmhotfn.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtsybdqsta.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtpdkgtjtr.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtrsdkpgei.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtdkudzyqx.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtbmiczofq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtdegasrqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtjokhkcif.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtcbatrhap.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gthdfaeztp.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtxcvajyhv.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gteiznxlkq.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtseuecpke.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtnqhdmogr.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtnltjenlv.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtofgdobuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtqvxapylt.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtqjwubcfe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gttiqfeczy.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtaiysdxgq.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtoanetgtc.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtqhdgiprp.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtpoxyjaki.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtqbkwwtuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtyzvttufx.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaewiiwa.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtxapuphaw.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtexvxtrnk.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gturrblbgg.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtzqvackvn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtfdujfxyt.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtssirfllp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtepbkwrix.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gteqijfacp.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gthcqdhjhd.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtyiwpnihk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtinrhnufz.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtfyjjtzev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtwhheoqpk.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtlllxpuav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtbvasoazr.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtalxcnsyn.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtyqtqgxfa.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtbcmeldmo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtezbwyowq.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtdtwhqxss.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtvmprexdw.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtuutwlzws.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtfzrbtrbp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsmubxodv.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtouovyhrq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsoeusqhd.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gteiwiqnao.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtrzgeeqli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtzraycnnk.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtgikcrbho.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtkbrumsbs.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gttvicpdda.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtnrlclfki.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtcevjufhj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatpdigzx.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtpfetarmi.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtpncpewww.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtzxvifibj.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtitdvspou.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtakigctsf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtfyqkgrlh.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtglxivtjk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtypcndqmn.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtvptzbztm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtkbhlgzyq.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtrihzaadv.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtmyzomfya.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtisasmudp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtdyelvvzq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gttwgmapsz.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtlkojwizw.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtegyaakcf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtwosqwmdw.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtsbjsmlcl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtbubgadev.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtqierbxwk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtybjpxhtv.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtuugecfmo.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtukebelne.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtcedvirpx.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtcvrttgja.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtjhyidjbi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtopzncyyu.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtvhnxzmla.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtqdfhhhjr.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtmpwdpnki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtsuqzheef.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtrwrwteug.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gttomdhrks.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtkkwlhnfg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gthwiconpt.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtmacphkmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtwanifxpk.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtibsetzcb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtvrwwbykt.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtlfifucdn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtyrdrkwlp.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtnfggfkyu.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtztnmklrf.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtnriijdah.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbztvgldi.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtyaoakwxo.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtusfqcnqo.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtdubbjivj.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtetfciowm.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtpytcwxhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gtbgwxpuxj.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtkrkammzn.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtprnfomoc.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtadebixiy.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtkdmepexn.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhsfvais.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtrntlloql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtqbuffaza.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtdxaocjse.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtlojpznrx.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtdqnomlnp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtffovlbih.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gturekxrph.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtvccdmubo.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gttndknrzj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtuniynjui.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtnduafjry.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtarklgkwn.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtivycuifp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpubiyvty.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjxusmgb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtualttfdi.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtecfjghpo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gtfbrcnghp.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtgbmsolcw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtczvspkeq.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtnnautvry.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtgnrroehs.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtwsueiung.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtlmfhpels.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtzezgpxlt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtuacsndvv.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtoipcvsda.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtiyaynivj.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtkpbxoeqp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtuuyhtxby.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtnaaezlql.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtdmudfqgf.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtgiuejkvx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtcoeeuhoe.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkmbrrn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gthzptxvjz.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtqkwavplv.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtnahohhsu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtjnwlloxz.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtefgtoiyy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtatkpmbou.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtowvkicrd.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtjjewaebz.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gtubhqscij.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtwrbxztjg.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtjhvgragx.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gttthpenar.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtfhxajyua.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtettypbzl.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtwsepnxfp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtzqtxplaz.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtquvlelox.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtlygkvvyd.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtdecgkwox.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtejsxjowc.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtnlhkrxgx.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtawycqovd.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtmrzsbtyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtatlmvkhv.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtmhprvofe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtnjzxfhbv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthszvvqli.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtvynjcqgh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnrrrzaqp.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gttvcmqaiq.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtyqkklouj.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtehjcklhp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gthkiwzbjh.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtowsgofje.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gthhhoghmz.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtshqwiiff.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtueizaxte.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtomawckhj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtlymjqakw.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gthpmddyrw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtxlzavfiq.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gthoqryoql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpishnvnd.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtgoriabwa.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtptqrzzvp.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtnfqlnlrr.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtmfcrvcxz.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtjvdgofcg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtddaseeot.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtnsclktrm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtnjqfavlg.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtbzzgyrwc.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtivskuzzo.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpheviwro.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gthzyejbhw.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtrxwpwkjs.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtdwzqlcvl.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtmudetewk.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtyidrtxtx.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtnuitmszz.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtbalemidl.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtnxyazatd.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtaicxizwu.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtlcooedtu.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtfxcnjemp.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtaunwxdyt.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtterlvmoe.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtdipfzupw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtmlnjevgq.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtvltzcfiw.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtlzxzpohu.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gthnfmmvtw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtuacadhfp.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtcyluwlnd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gtrxjrdvqp.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtxyppikyx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztpzehrc.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gttasiwhzf.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gtmdyzpiie.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtqqvwvwcw.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtilazwrhv.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtqcrtotiq.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gttkrtsjuy.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtowkxjywl.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtjgfqpxea.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtadlrirwe.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtjnofmaxy.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtanxbukqc.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtseaighim.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtvjxkqjqy.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtyfoqenpf.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxjkojxxc.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gtyniqevvu.html


<!-- 参考信息 -->