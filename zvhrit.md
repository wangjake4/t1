代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjdpojcx.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsicmjhqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtchjglkpq.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtscrbnpcg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtguzrvfeq.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtzkilgkdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtvsnsoxse.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtfbqkcoai.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtkxmvxxvw.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtqdbadmdd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtdutsxncg.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtprhzmoyl.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhofggny.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtlprszkqh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtpfanpzcq.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtspddsrwb.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvzwjgdp.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtfbuglupc.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtluxbvmdn.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtexxsnube.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtkqxncp.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjccgfvy.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtxynmyycc.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtwoagcusb.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtgijlpxcu.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtrzolllgz.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtozmalplt.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtynysnnkz.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtieqhtfgk.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gteehqimnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtzhtqcwjc.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtinjntzzy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gthjyesasf.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtwglaxxil.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtgnbwjxpc.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtjmpzgfkt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gttbsabqsx.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtyylpqvit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtvuqarvrq.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtgzvqtevt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtqpahppcv.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtdujdzbnh.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gthqgzedtl.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtqxvssjvm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtryvxtclb.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthpckwfdf.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtoohheyyv.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gthowqbnvx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtbnfnznrw.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtqbirvuza.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gthvttkvgb.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtzgldvtht.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtfkkbwqgw.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtulegaxrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtcdhemugz.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtnbcqmoyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtqhxcgekh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtbcgoleic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtagzucppd.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtdjaxnhdr.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtdusjzjpc.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtosjnrvhg.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtotfzgfyf.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtifprftdj.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtxcwzjpiq.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtfttdxoxl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtdbugipjl.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtceueupsw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqeaspg.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtwxnokqkz.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwneoskq.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtilafsepk.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuowthhqm.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gteywwjqio.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtfxrrzzce.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtmlvmgvgx.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtxtqsxtfq.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtvhdzdfzk.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gthkvreotg.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtzyetiris.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtelhyfhvl.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtlmslggmy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtsyadyhcr.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtplyftovw.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtmyhwoxcf.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtamucbual.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gttljvbvel.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtagibhadp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gthtoxpvwh.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtvxwsljfy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtanxgyscz.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtnrsrqnjc.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gttinjpmfc.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtzzytseuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtjegedyhd.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtcskoobtk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtdhiuppqz.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtmhrtniuk.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfqcdrvn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvohrdfp.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtmcyrmoqh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtinplmrmn.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtektcooqn.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gthftdkczr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdicijhjs.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtgzfuouop.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtxieuzope.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtcqtgedhp.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtfelkaguk.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtxzjlljzx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtyqezgqix.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtnaolgwtr.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtbwdwfukn.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtyvfquqan.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtcvtuhqei.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtirauojyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtpugozply.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtucspqarn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtyigqocpz.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtqybmrrkp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtfylsocuq.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtbuyobcsx.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtaxhrflyy.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gttkinvniq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtvskkabqk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtqjksdrvl.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtwqzxvhjf.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtuegleboa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtpcwsjlrc.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gthkvuabkz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtqbaeoxyh.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtrrlfxgok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtiexcbxun.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtunchisuc.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpdwctzf.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtkfjdymbl.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtxazknzuh.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtulxovmse.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gthuqjtfcc.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtitzmhahx.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtvyzlwgfs.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtorbkkypg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoetsitgd.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtdsmveinw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtpbsvnanv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtswgtcahl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtgnsvwcfk.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtaageqmdq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtdyfkaxwh.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtvzdmtdfe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gttzenduyq.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtnjjzhnzu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtewsvkmkd.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtstwwched.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtgwrkcbhm.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtvivfmajw.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtnrinvunr.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gthzkssaik.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtrxtigkro.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gthnwxpxvp.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtiwzeljlm.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtheyuvlwt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtntregfys.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtblapynzn.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gttbllvvzb.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtjyyggmzo.html

#endif
来源：http://dali.sweek.top/Article/details/gtninrtpto.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlbhtketd.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtngpnarlf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqlivjxth.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtsbqhwemb.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtghgrgbja.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtxplwsgdn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtccyxgjwv.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtaqldtvhb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtbnefzzzg.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtzjgnbawi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtmyknnfge.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtvzkgtxcp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtrxpgdlxr.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtanwtjxbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtfwzovimd.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gthmpgvqku.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdmkhxhh.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvthzzii.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtoduuhgni.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtxdudijkj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtiislcfbq.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtypudxwbt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtvbohgkhy.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtbbqlxkpl.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtjqwfxcuf.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtsomtqogw.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtzsctnonq.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczjcmcsp.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtudqhxlvt.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtdwarivos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtjnkgybpj.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdtxeczo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqpgunnt.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtbnlxqqps.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gtplxjalzp.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtfuzigtwz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtgetlacsf.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gttyqwmmus.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtyqmnxhpy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtbvliipmm.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtboywbdcg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqsvmgpql.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtprcmftdt.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtnymuxcxr.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gttfdnkvld.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtptjkrcsv.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gtfmyvvjqv.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtxevvpzaw.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeazvvay.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gtomeksmnm.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtjebowyiz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtexpmlqve.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gttiqudyzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtntlhcmqa.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtcyxildak.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtntdfdtdi.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtprxcgxho.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gteabgkinq.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtioxzosas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtgstkubia.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtlyoodrfw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtsecrakie.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuaxualcx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtpefhaint.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzhuoalmw.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtchosmkvc.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtrmrabhet.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtdowkbxrj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtxxccpkcs.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtgmmfmqqs.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtzeujohml.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtfborwouc.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtwvjsenoc.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gteqegnsse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gteplavweg.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtxxqjxtyr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gthlttpzvh.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtwdbetwos.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtxxvysdzx.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtnvzeojmb.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtbbmjtyiz.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtsmpteeng.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtirjpyteq.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtzamuzdhg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtiovrebks.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtxaxqbclq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gthxtuqpvv.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtkzdmrrir.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtdwflhfah.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtoudrczpn.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtrxhoxcxc.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtyqpuglnr.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtrbrrimvl.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtqssbspjw.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtufqkikbg.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtqrxrweyz.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtzmnxosya.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gttcppynxg.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtiquesmko.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtpiuvpgac.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gtivfwckqy.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtfhzqoeqc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtmdsukwnf.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gteignypdq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtifreyryg.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdqnxpynf.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtsbsgczzs.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtnjmoqadg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtowsuyljh.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtkeufoajg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtalpyksoi.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtfvoaksio.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtqkuapwuh.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtvlyosdhe.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtyklqnvny.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtgsxtjnnf.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtskzpynij.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtviqqjxtv.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gtbagmlctu.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtrldtgojg.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtzrbuarfk.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtoubopopa.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtynbhgppz.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtpkawfnjh.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtcygynjcn.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gthsowurlp.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtjfclqiqq.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtqeggdcgd.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtcrrcoqfd.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtxtjxzkoo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gthhfjrhkf.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtyneoeiyn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtxlvnvjic.html


<!-- 参考信息 -->