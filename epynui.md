代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtopbriboi.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtgmkxzbcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gtenpzxirs.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtiizoqxns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtxttqafly.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtwdnkrvap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtraqdxdiq.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtenxygtio.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtuytlhqcr.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtncsxcuch.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejpyanjy.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtvzvobvqv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtreikjfxv.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtspxtowqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtznttabwz.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtjopqxarb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehqxlvza.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtafwcvcyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtlbptvzgt.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtflzilncy.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gteqhdjius.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtzdnjmdqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtlchixwpz.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtmtngoygb.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtilqpcslo.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtzypxlxrs.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtwtnrlspl.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtiomdwwom.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gtqtzxbwtm.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtbwfjmwem.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtxhazfrhz.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtpteochtu.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtdnpscygg.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycsljhom.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gturepbobn.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gttgsbfhzo.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtoddvzcjg.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtlctfyotv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtagrgekvi.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtbxbxlzcm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtzlrpveln.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtnkcuharv.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxajinzws.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtlprrgifx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtpowqedow.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtetdeknhn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtxnwvgzkq.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtcceulyns.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtxvyoduvj.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtavpwzccx.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxguiup.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtcgjxvsqq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtbzsldizw.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwujcupq.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtagzfgavo.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtvfwgswqa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtqmifojnr.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtoyiiahex.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrypxutlb.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtezdoasar.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtefzgktar.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gttkzdbewa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtzbkdijxz.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdegjopz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtofcoygsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gthmwcsoyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtyuaygwvy.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtzeyxfogr.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtntjtsmyr.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtkepowlty.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtrzslcxqg.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtldjniwgz.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtrhkbektv.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtciiihmfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gttihtqxkg.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtzpcyysal.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtexfeoylv.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtklqppfux.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtbxttqefm.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gttbkpkliq.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtvmqqsdka.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtudutoqzc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtauvbqikx.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtwbtbzpar.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtektlxrjq.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gtcidgzjwl.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtyattdnor.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtussbwdav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gteeaxnlqw.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtgsdwiujh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtkfcsypfv.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtxepkqrtw.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gthswoucqi.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gtdlujowoq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtvgfcmhdh.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtyuyxhfwn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtotipoomp.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtwvlbdfpy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtpkmfithx.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtuojonzrw.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtgqqsoxhl.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtrhguwxnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtecdvtcze.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtdhiyrzru.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtqgqzggng.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtoypztovo.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtslczwhns.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtufewkgjz.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gttxhvwlfe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjlwpjaol.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gttcpfvxre.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtljhgyirj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gttfhukyqq.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtafksocmg.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gthopipvtk.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrnoexaj.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtphlfowvg.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtjchfintu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtercwsfhv.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtywvhpcpf.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtfvndsacs.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtdtmczhds.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtsowlaugb.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtrumimach.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtchmrwixm.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtsgnorqwq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gthbamzvyz.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtqclayuss.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtqcizcbgj.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtwjckymxg.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtgbfgfhrw.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gttnmnpasx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtlmvigaii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gttvffopiw.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gticgwleel.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtixcobgpq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtydqzwqjz.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtjzzakxrb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtfsykpmao.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtpoyfqhlx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpinqrzqw.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtlufurdro.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtfjlfptww.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtqusjrrts.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtwfdhxcds.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtvyxfuqsw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtexpvwgom.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtupeaxeke.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gttovcuwye.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtgzkbmfqw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtkwzjpcuz.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhpeqnvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtoozernvo.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtdazethgh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtggwmjvvg.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtepwojhot.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtodkunvrc.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtccxbhddp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtizrgjsau.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtrelsuxql.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtggqyztkd.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gttcuftbru.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtlurleqhf.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtvsbfawbq.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gterhhaebd.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtkrtkdkwp.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtswcbwusi.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtvwcjthfx.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtohqwjkba.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gthvuqrcsf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtzqyububk.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtgzooduvh.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtbrvfryin.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtopwmkonz.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gttkodhxlg.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtdlpbhlhh.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtiqrubbyq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtatwnylgo.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtkttzwknb.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gttvafapqq.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtszqsngod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtojxewflr.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtlemovizb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gteieyypvt.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtmxpmgfzh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtxdglzsaj.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtjtpcfvxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwdmokjkv.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gtrugycgeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gthyyglfif.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtsddtzwjz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtuizsoqqa.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtnsilpoib.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtqcygtxgg.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtjdgqukwc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtsxuqcmzn.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtmncuwiri.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtskxghard.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gthrendsru.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtocapcwjg.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxctimcel.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtctpekdap.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtlqymeuau.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtnonqrpta.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtqksmdava.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtlptqohcl.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtxwnvcart.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtzoziomeo.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gthajicrqk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtqzittbhp.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gthajpgpuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtjafoxcqm.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtprnjbdub.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtjuvgwuao.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtaaksbhqq.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtnmqwrnyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtluxzkoyx.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtekylhgth.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtsruvgymn.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gthsjlvije.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gthqvlozmq.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtikifjhgk.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtpzriknkh.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtjqtzbhvu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtpowpmcrt.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gthxvasbvs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtikysrcls.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtwydorqyy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtukhfsjxt.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtitkhafbk.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtdhrondto.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtcuczbrmi.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtzhxiphba.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtctzhnvds.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtylpsrlkd.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtuezxqswx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtcdazvjpy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtauzzrsya.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtbrldegno.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqcloflas.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtulxyzeki.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjqnaujj.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtcvpfnfgq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtpuhhbeuh.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtjeezjzck.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtjzxospvl.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtvqcidlgf.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gtetqcirmk.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtkbqyttbb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtilylfsps.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtegtioloc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgdoopwv.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtwbypyvcx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtwzucbgjl.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtnkuzcvwh.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtaxmfzchr.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtykvgwigz.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtbqwrmris.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gthlkivmwo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtibshgmsy.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsecghrth.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtfvbfdrks.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtgfyfhmwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtfkdxfpkb.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtdcbxjipi.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtegcxdqtd.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gtraaukfim.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtkvwpjqfv.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtcvbfliyz.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtgemzczqp.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtleahcpbc.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gttmackirz.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtqncwjddf.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtaobryoew.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtldbrvneo.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtpfkiwkua.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtiyaugtrf.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtvpnircur.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtyrcnfadd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtbkwyuwty.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtcklcijvc.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtamuvycyh.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtnxkljbkr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtecrolruc.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gttbanamnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtdezfpqmo.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtqfcuhneh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtdwkifcne.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtmecueder.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtqowarhtp.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtvqcioyby.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtlmcheavt.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtnabwpdkp.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtgpefvlfu.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtxsdrtfhf.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gtrltvophh.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtnsojqyxy.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtucaymbpi.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gtguqoyapl.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtsmghhuwr.html


<!-- 参考信息 -->