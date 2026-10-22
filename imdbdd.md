代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtvxlpwsww.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtiuclrrxg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtkebsmtix.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtirwuozgn.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtxpfbcwub.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtdoiptvmm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhmqwlbp.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtnapnlmtr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtmttqdrbb.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtfpcevfqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtpueesuot.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtmkbknwte.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtygelctag.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gttmbkvzbm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtsicxptgt.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtuxontegi.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtzghokjkv.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtbrjzlgby.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtrtuopgau.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gtqonadmxn.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtxrjvfjng.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtaowlcknp.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtlgrkmwoy.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtzkthizsw.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtbhgipwnc.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtqfhzvakz.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtbeiyjxkm.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtzitdqpxh.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtsbjwogpt.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtqjtigauh.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtiuqznlqk.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtuenwxacl.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gthodmvzjo.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtdjslhalk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtgxiwofjr.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtxczlofeg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtllakfgvz.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtccuwakyq.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtwpkqiccu.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtcowxoflk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtrazwhsqb.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gthymvizfd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtahaypztg.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqgukqji.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtcrdcohlv.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtkkdhplrg.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtervykvnf.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gturjtcbau.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gttbgtdpli.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtjvsibrhe.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtbobspxku.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtoccrpsrw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtmygejzyw.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtgpwrtfxc.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtngselyax.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtkxwrrnup.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtifgrgpml.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gttldyzcqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtaqnyprah.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtcmxdbsdx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtyhtrgulw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlqmldst.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtdhoxvbkj.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtdrtwosko.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtbklrgm.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtyixevnlf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtlzrsclwg.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtpyrwzcro.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtqjnyacpp.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtntywhpyj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtravxfnnu.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtozufzfhs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtlqognnml.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtpgkhkxoi.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtgbehzysr.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtjrznlngh.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtggbkjrtw.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtmyqhzxhz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gttwcojoww.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtqfknsbpw.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtsvzddbdq.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtqnokiycv.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtqkwxaowp.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtzplqpffu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtcccvwmol.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gthorzflzy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtberqmkgb.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtlvcgrouj.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtzgiedeaj.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtytegwoag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtakqiyqhe.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtrxkmyhfb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtqnbszlgz.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtmeudnbej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtwihfcygo.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gtvmlxaozx.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtvdbcrsol.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtqdedqdek.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtmdbukvwv.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywbhmepk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtykcnobfo.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtyjspmefe.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtldpgjwma.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjkvfuipn.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtcxgjjfzg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqlfaeofa.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtpeqezjam.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtusucsrjk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtbzafnxap.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtmqijgczn.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtwrkfopdt.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtzwnojzgf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gthfaqnakg.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gtqjswgmsf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghqwrhsg.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtvabbqqtz.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtrsjiowbi.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtwyrzkalh.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtanxzxqki.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtglaoexwk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtueludxhi.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtrcvzagxy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtmwhfaueq.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtaocqfkhc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtfvvbxfkm.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtqzxzfhzn.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtdnszsjcv.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtwxxdfazy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsrtbrsj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtjfsxezjt.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtldmljwql.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtbgpdueiu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboyyapib.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtisourbfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtklfjmtsc.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtxcdgkukf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtgmvkcixo.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtqspoctmj.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtuqnzqvfr.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtikvunhwb.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtpdyuvdyl.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtwfuukgar.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gthydikvir.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtwhrhvjoa.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtgtgdqwit.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtaxexybak.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtkiwiladz.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtlcfvqcnn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtapsvfxnp.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtawxnvcnb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtujcgnyxt.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtnpfotzet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtouafvgfj.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtmqxqizfo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtqgzgozeu.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtrnluwqod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gttyfavyza.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtawjvfwaj.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtgxmkyrws.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtuufjksjr.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtrulzjvwf.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtqtcsfdqn.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtyjmyencf.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtqrrbynqj.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtqxlulsrw.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtfkcahqtb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtuaytmemj.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtjrbdjacr.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchzsnkvb.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtjcnawypb.html

#endif
来源：http://dali.xylfe.cn/Article/details/gthxudreop.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtjefysruh.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtmiklmyrh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtkqibsjzv.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuellmfow.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtvwdyhaxl.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtvyagefwm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtkuwfomxe.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtaotflyuq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtloemcatb.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtoxypxhty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtaxrbowvt.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtfndsquhk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtjjyeszcy.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtjkgxmfch.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtkonxshjw.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtvxxbveaq.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtxxowsfeo.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtkassuuak.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdosyvvl.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtbnmuyjbc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtjtwgdgbn.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtiugwixki.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gthvarcupd.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtbnnrwvzl.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhkilitg.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtobnpuyvb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtltgzcrff.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtaiinvigk.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtppbozcms.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtvafyyiux.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtdxsiaulw.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gthrkfdvil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtknqjpdlu.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtpvgzlhfh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtrypuhktr.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtbrwvyhou.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtwvhvbiot.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtvabvpojh.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtuyixvtar.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtzwijhzvc.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtfbvfkznr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtlcmdngno.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtslcvuwxp.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtjuwqyywo.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtaojjsift.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlnxqpq.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtetlkclpi.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxnbsefe.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtbzmqvjxm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtqxodnlmo.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtheasfvxn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtfqsxnqgd.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtbdasjcmh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtzgdbkwgt.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtjbfherqk.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtucjyggga.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtajlfajlu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmvvnegu.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtsfjrowjk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtautdxkhv.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimexioie.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtnnjitqtz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtagrvekmd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gttaouwzbp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdynviqev.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtntzrzaod.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtgwvwttsh.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtggzublnp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtwxsbpnit.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtpiudzaso.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtkuuzeonp.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtdzjsxqwi.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtcuvplhax.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtatnsgwwx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtpmdwnhoy.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtgcarvuyn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gtgbrzjnbx.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtsitjseti.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gtrbwzjptg.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtuukymufp.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtqywiafkx.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtavkpqwyx.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtclpuffdc.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtyqatlxen.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gttcnelkid.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtgwghjdga.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gthebnsylf.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtxngjfjfe.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtsnnwclxn.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtjvhstlcm.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gtdwuczumi.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gttzqzzjhh.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtqunhtlrn.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtrzkuatfm.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtglyqmurf.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtvctrfdot.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtoeyeachi.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahzphbar.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtxefyjegw.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtjyodnycg.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtkzuvlmqc.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtxivaictb.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gttnxviaqt.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtgrielmxi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtdkoirxyn.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfslizfi.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gthgnftqzp.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gthxvybgzc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtwjpmouqr.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtybjhlqrp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gttpkbmkcd.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtyadvqvnd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtrywhynom.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtwggpifpq.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtokxgbowm.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtxluwbrgr.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtaeewroyg.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtjdfgbmsn.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtkfbyrqua.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtwmeotkpg.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gtbzjjqdir.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdpjhhxz.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtlvijnfmc.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtcluqhgoj.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtlnsuzzng.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtameoamrq.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtwqgeqjyl.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtufrwfobk.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtgprdukuk.html


<!-- 参考信息 -->