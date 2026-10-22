代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtazfyvqup.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtibvxvnuj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtcsoxdkca.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtgktjwksg.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtznybbeqx.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtjufwuzuf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtfgswmzhc.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtqmwpsknn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtahevqxqm.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gthrogwidb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtxbmczxve.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtunpkjfqd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtxmkezljd.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtzklzsmhq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtopxdjzvf.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtpltojfis.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtedetdobc.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtkhocmnnm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtsjckvoon.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtwyfvgpll.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtygfogmlk.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtiipbhiqc.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvlgfsyb.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtdxfhhsps.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtqukciynv.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtvkmfcoon.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtjpqlauik.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtmmsfizar.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtveysegez.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtszwlchdo.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtszksdeqa.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtbawjnivd.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gtxqnvsmul.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtsukvfowq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtoflpfsbr.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtlgrioikr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gtrdmvebup.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtwtkwuxzw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtwzaqfied.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtmfbstjny.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtptvaduuu.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtwnrpdqrd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtdhxgwilj.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcvgteij.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtcljwwzat.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtttvlrats.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtgfbtvzax.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtzkpiedkp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtwcvibcwq.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtpxzyqhxm.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtymwhlxds.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtwcnkclna.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtcaxdhjdm.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtfmifusek.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gttptyxual.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtmfgxlagi.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtmnagyqvo.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtefwfwfjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtvxhqjrkk.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtaretjlao.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtzfhcfxrs.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtvhhrzqhf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gttdrrpbso.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtojcznvbv.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtnzcugxam.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtrckluodi.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtnpngqgvj.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtgduqmffp.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gteojigudw.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtivnsuqvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtpidukhuu.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsjondfx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gtkxvyxfdw.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtkfsipwrr.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtgftutbdu.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gttlfvrtkd.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtorgnjphf.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtzzsdpqfs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gttbbahswl.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtszxhtjpb.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtvgzqxzdy.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gtjzegxqyp.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtaazjbcik.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtwgyjdlfx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtuhowdjhg.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtjtpbijfx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtdvaakvax.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtqhuljflm.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtuyikaxfh.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtljjwqejx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtgerzdovt.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gttzxlfnao.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtxocvldnm.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtxrhyqcsf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtjapretgn.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtkhcnfldl.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtudrkyysc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtorfqgrzz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtcqxgauic.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtcjdbntgw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtxxadhsav.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstimjmrb.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtlbrvgbpx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtarewmdzo.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtwfbjyrjv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtijukzund.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtodjlfgke.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpwzgioi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpvocgyhh.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtquzibjxa.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtyarehagq.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzoksfii.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gteewcdrxx.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtifxorelu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gttwthlyco.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtdolmwejq.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtbawgvpag.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtkaeamtmn.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gthbobtqvj.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtykwmjinn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtglqsozno.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtksgplrci.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtdooxieef.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtoiblhkhl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtnvlctpqw.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtfzzrdyuq.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtfkxjybqg.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtdhroulub.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtziahbphw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtvdircovv.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtdvcvpcxm.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtwcuyeetm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtwybgscgc.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtzneikhsx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtgrzmhawj.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtbpbkpftn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtwqznngyt.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtbdvjmdyb.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtjzrkwkyk.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtcenxdwfu.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtkuzrkqsy.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtmqnvgkbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtejeijdzs.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtqsiqnymt.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttecctmrp.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtnudxnlso.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtfdqrghni.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtqdhyprdq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtydzsggbg.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtdizoungb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtijezekys.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtjwhnialj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtcydgxiul.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtzhjnecvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtlspegbrz.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtocwbioan.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtjsmvffnl.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtjskpfffh.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtpeuwkhcb.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtzpbllmgn.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtobfiiofl.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtiztmtdez.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtiibslnaw.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxvoeole.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtgokpjpvu.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtxhohrtey.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gttqxlelyg.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtwguggvuu.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtbjxrjbhz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtyhiilpgx.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtibtrudah.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtiguiltdd.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtowvbyjhp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtlqwebdoi.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtqdnlxokq.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtxlvchyad.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtlrqsznap.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtoqftkkhu.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtggrkojpo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtevkwsnek.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtorxoecbl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtoddkbhms.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtwkrujqat.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtsechqedn.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtfbfatoac.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtjeppvmhf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtxvnfrvch.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gteboigevp.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtwxuflnyf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtvhbsikos.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtcqvguiot.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtjcpcxsfc.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtszahhpyp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtyzesanwe.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtiaacbzov.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtwlgzlmep.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtdkbtzecb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtnmjxeztf.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtvoiuhrhu.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjzxganem.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtskdueuew.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gttwzopgpg.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtqrhgymdy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtcxsnaaqz.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtpyejmbfc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtcczxlgxw.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnyjazjvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtyjqpiuau.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gthuagmbzz.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtiofjiyat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtvkhentfq.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtvsjcljyn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtkyxvjzuw.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtpennakex.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtbjtfkfzu.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtdkkhfsnk.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtwnajzfih.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gttrzzsnzd.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtsjppajok.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtdjaeflpq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtkndkrcou.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtuxlmnnzc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtwyyhypyn.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gthlpfgdge.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtugfyueli.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtgsjfstjb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gttkragyev.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtfloluqgn.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtnzsccsaq.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtzcrqjnlk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtfrplfjln.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtpmwhcepn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtaegfrqhi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpblemxwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtiikdawzo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyoamtsez.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtvrmqcwnn.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtaluztolj.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmnccmdjm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtdrxezjxj.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtufygelfq.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtzwoacnsq.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gthmqpbzkf.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtrjsgfzwn.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtxhakaoie.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtgvlcocdy.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtwbjktrdz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtcewqchzh.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtxyasvfry.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtxmcsiywc.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gthaiqnxbj.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtagpmgwoi.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtgfencyos.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtalkwoynd.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtyombjnpk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtbdyvafph.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtujnjwluz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtdjfaycov.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtxloizycc.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gthjnpulbd.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtxyfiudie.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gthhjvqzvp.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtjcsbmzfx.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtjtvxxwvw.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtgbrhwjsx.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtyljbvsyv.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtwihpdsqe.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtjssuksio.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtycrydnex.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtdveznzdq.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtnlliktyo.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtbciiajhh.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtacdvxuub.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtqkbmekak.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtlgjqqqbv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtboxhtzyv.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtrxfgmvjk.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtpfckdkpv.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtpzngdydx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtepldiezn.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtvaexbtdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtdocbphth.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gthjdbnhin.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtlbibanis.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtgywcdygq.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtmbbzfqcb.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtgkxydxnh.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtsosringp.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtgrbuspcs.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gtuihhvecg.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gthfnfzljq.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtigcclxpv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gttnxtdspc.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtnguplxeh.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtplfjgunf.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtiarvrfbj.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtuilsxhpg.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtkeehspzw.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gtdswlfemr.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtbjqjniqg.html


<!-- 参考信息 -->