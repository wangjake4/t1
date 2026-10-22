代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtwalqbbjk.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtcprvcdsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gttgqvivlf.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtqctoviqa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtdnzshubz.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtzweepoxw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtlcmqsshk.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtjnppbvrn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtkustmapy.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gthxotkfyl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtrhrnrugu.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtdhrzgbos.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtpfpprhik.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtvmobrexy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtyujekzde.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gttijojaec.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiqfadcx.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtpibbwezz.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtwvlltolv.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtapjjkzwv.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtwhkmooap.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtfahkyypn.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gtckzmtsel.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtapjghucr.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtriekkfxw.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtkseavxku.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtyfjzntop.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtctxhnkye.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtqlrvqsyk.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtlwvnjxaa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtacanxjzg.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtudlkjqim.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtjbdwqpkj.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtkuazihqv.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtvryksvnb.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtlwtektnb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtopnzoxhz.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gttzojhbkz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtsfreulvr.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtqbkkrvqw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtidgeczpm.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtsqffocch.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtmuiunvcu.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtvwfcggpd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtyqptbqte.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gthlixqmaz.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtgndiexkv.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtwfyqywqa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtafhrjnbx.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtzeyfhvkb.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtoqmlhyrh.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtqzqtpbmt.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gteiwfhrik.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtcquurcfz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtfxrivdtx.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtauaulfuc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtanurntqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtvclxgyyi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjpxhzns.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtqcodgaru.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtssieusxw.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtnzghooni.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtunruswjx.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtilcguzhf.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtntsxinis.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtnplclefr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtlavaoobp.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtrqazvbno.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtynewedty.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtfjhyswyt.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtvbfmqovf.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtcibasbnl.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtvbgzxacq.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtjkhjsten.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtpvygrefw.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtkputzxta.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtszskakpe.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtcfnbsbcn.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtdexxmutr.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtxlsqueqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtzxacdvwd.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtqysmlthn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtcbzjjmev.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtqknyaqny.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtvgilmrph.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtnnbwkiym.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtrunnlams.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtjoiabjqa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtaqdqjohl.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtpigmoxds.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtcecmuosh.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtihvvkkck.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtxqnzmrcg.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtjqlmxkjn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtwmizsdfj.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtzjynwkfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gttgzpqqoq.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtqzkdxkqg.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtrnvlginh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyodnqisn.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtneaeumqo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtosfavbyz.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtpzlpnuan.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtrbnjysii.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtsklrsfgq.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtnouoogqw.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtphzcdeky.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtjcyhxukw.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gthlofqwwq.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtauasrwny.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtqtbqnaay.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtiwhywtwm.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtitkxxydl.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtnrfqcimp.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtrryypswr.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtygggpghk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsdkxwip.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtegvvyxdv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtnconlxns.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtxnzctkqj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfncbvzn.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtnmywojki.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtlhhefyor.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtzxciqjxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gthscmvuri.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtednlvjgz.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtbassbvsq.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtaniliufh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtkvjxrori.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmiwxwag.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtejvnbyia.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtcwzasqpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtcevztkuj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gthalkatwk.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtzfybihhl.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtxczqfgla.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtegqdekxg.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtfljjjgra.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtbzutpbfh.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtzzaffoup.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtfeaqmolt.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtnynrdylj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtqfpvcwxx.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtgwggsavr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtyoqxcqqb.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtasjilxzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gthnrvrlmp.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtavanmefh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsmxqfen.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtyesxdnys.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtuuontdcl.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtcsurtxqj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtswjldgdx.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtivwoejvz.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtmzbdljnz.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeeztbqw.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtopdobbmb.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtmyxxviqx.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtwgfzoioz.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmpcixyr.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtaisaxnpi.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtwvnfizqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtwjjqnxfj.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtcjfxcqrh.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtbqrgptrr.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtzcmkxoos.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtadmfljfn.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtlztibcby.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtmwqjvfum.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtemjpibnp.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gttargixmh.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtecmumdsz.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdcozsiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtmhvqdsui.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtgggxruvt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtmutmbrco.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtgimlgxxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtsaczvgfr.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtbdjdtixz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtzlogylgo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtpgaqfvxv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtylzzsfvc.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtcnnffejq.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtchkmokad.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gthhzqclvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtqdipsxyw.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtqxeusmln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtabmfmaty.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtjjrchefa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtsjsvvnxm.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gthtwuezhs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtirxqljke.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtbiobfrhm.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtkxqhyeko.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gthfqbohpm.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtittfxzbj.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtrbjkviky.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtejnyyvgl.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gtvekzxgrv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtgvnjawqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtffxyiucv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtmtpagyxc.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtahsxkghw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gttqnwquba.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtdavhytqo.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gttrdspiza.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gttttetpau.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gteznmunqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtlswnkjrx.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtajuyxeph.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtzosldrsu.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gtrezxcamn.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtfxizzpsh.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwsxdyrl.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gthhqjhwgg.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtozkzcvfv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtadikdqqj.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtyfntucwy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtukryvfmc.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtprxidtob.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtkxmwexwm.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqjjbxsz.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtsyzkjmvg.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtstqfukli.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gteuiuwqxv.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtvqvslzif.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtxncnmlgu.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtwkzpapnt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtbqiimqtm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtulebfgxs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtwraoeogz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdzjgomrx.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtsdmmujis.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtfggnylyn.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtitopgahi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gthobrsfmh.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtdulsipua.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtysiywteo.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtfmxlnawt.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtyriqwetf.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtjxkczmaf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtgfhvlmtb.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtjzgzlirp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtwjdaqhjv.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtvnotenwa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtarzfogpn.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtzsbjddyg.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtguumuvbv.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtnmpndelc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtxfswbexw.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtqqzffalj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtgyigvjvj.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtkcepjbqs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gtauigvsfe.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtmlkyfznm.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtloslzcgo.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtarkwpgoe.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorbehlhr.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtbxzaplxt.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtennvpigg.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtloytokyd.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtaunwyztw.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gttihbvdjk.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtkipewbza.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gtbnmwwgtx.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtmumcfqdg.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtawgwnrhf.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtvbrkjiut.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtkumnlbje.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtdeuebqay.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtgxowavtb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtudxbdgmi.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtozyhjlrg.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtlffdgczv.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtnhrarayh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtcubddufx.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtcoqqotih.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwgyashe.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gthduiioou.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtaanfpadu.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gtfpyfltca.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtimunujlg.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtklfyjkae.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtezjsdhww.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtigjddwfi.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtmemuybza.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtqjejlkeg.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtnvcshnnn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gthrnmvkfh.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtczfzqpxv.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtqnzvavok.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaenhyusj.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtrwdtwumn.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtpcoklcgl.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtklzvdclu.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtwrkrwodq.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtcoehqkaj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtkekbepfm.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtslxryuzl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyahnfwoy.html


<!-- 参考信息 -->