代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfnfskeln.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtpcfuidpu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtgpbsmcag.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtlvkqyxhi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gthyummgph.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtxftcdydb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtkshvnfkg.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtwxigpwwm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtyrwxpoba.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtyuihyqcj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtywwozkkt.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gttxwfsslm.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtrlgkrcjn.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtuvtembfm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtfmrunivy.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtibsprxgs.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtcqnuwurf.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtuypixjph.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtrhymtghy.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtgaxzomfh.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtkgfmqrks.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtralgtdyn.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtzudanjec.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtuqvfhunf.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtndffzkrh.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gthbqxtooa.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtgiwjjivo.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtagkjeiwv.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtjwdhhojy.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gteazzmjni.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzxjyxhm.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtwhjzfxfi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtyrzmafaw.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtfzaefjpe.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gteoueumhn.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtqufmylvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtrvnfrmir.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gthspexikl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtcmqxmjqj.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtfuohztng.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtaaiauomf.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtzowrgizd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtroqqgwgn.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtqrfeusmu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtvxcewjqf.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtluczymnw.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gterpwqqpc.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtyrfwztxb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtxsbjrcrg.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtqrphtrgr.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gthaerrgck.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtmuwfudac.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtusfysred.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtrpehqhnr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtjgtpufsc.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtrwvfhnzc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtckivfjxw.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtpozbxkhg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtmipyughv.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtbwzhziwx.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtfzclmupz.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqziyjvff.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtymrlprvc.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtpumunnvo.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtnskxtqxj.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtanksizxr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtpyuciccq.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbuxjzcc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtxlrthshd.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtihokoikn.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gttryfemiw.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtwvfapmlm.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtriqnqkyp.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtgbdwghpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtqdckzbga.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtmwvgzrfk.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtexlgsiya.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtlwuztggh.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtobvfpqgf.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtapyjbmgl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtndufwjjg.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtlfzjvtac.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtdthoqtvw.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtxqjorefp.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtzffjjfps.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gthqwqihpf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtcommnviq.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtkixbmpuj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtnijxnbea.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtzviucqlq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtzrzxxmeb.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtseyjjxyh.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtaouzdqrq.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtkphirnxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtoriholri.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtfctyegnk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtqytjhgoq.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtfpdixvni.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtsuecjghv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqhvlxhge.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtjlackzxi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpwhadthu.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtdbddvpip.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdblgwvwb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtihecpfxo.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtbmqgoqih.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtzlzufkfl.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gthmyebcei.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtuibpsmay.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlvdcqfj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtajgoiccd.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtbvpkunbu.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpsmsfve.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtsnsuqycx.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtcdzujylb.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtvpcojkjp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtrpjykosv.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtoweddyut.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtglsuwwzg.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtksuhppwi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtsfxpjfcp.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtiroaygik.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtfczbbunb.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtnzsofnjb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gthpgxybub.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtwcxlgpjv.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtwhmhliwy.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtrfpkzkdn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtmpsjgyep.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtqqsjhueu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtkthqokkz.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtqmjebwkh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtahcpmvwy.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtvndzgdap.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtvprndspc.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtcfpyvhxi.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtikshjzgd.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvtbnxgmy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtrcqleeze.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtibutrpea.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtwbdhuixt.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtwclniwhp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtmxtemlyl.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtndpevbfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtfcurskmm.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtaslqsmni.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtkddnifkb.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtinkfrezk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtcazbwhhu.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtboavxufw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtflcabjsg.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtuexxtahz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gtrddmfvfl.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtqouarvhl.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtzhpkwhmk.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtjjcmyhef.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtbfmmlitw.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtdpgusqug.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtlnaezyao.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtvkvmypir.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtlcmdczfs.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtuydnbola.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtwsblldoc.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtfpvhprnh.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtyhmddnll.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtkjjogohg.html

#endif
来源：http://dali.redwolf501.top/Article/details/gttighcfet.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtknutqywo.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtyexepmqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtbhzppsre.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gtdpmewrpz.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtkhuubtgv.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtmqcvcvli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gthnfqvnmj.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtvidebqtz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtuhshjhjx.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtuwuavkew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqkiuvic.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtmxdvoprr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtkeljncvc.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtovvtwexi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gttnygljwv.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gtieeloxng.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtupchbtqs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtdlbiqxpy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtpkluclsm.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtnycuyluk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtknsgddhj.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtjtnbmura.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gthnrkkgyc.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtutlwedyq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtdsrlnwft.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gtfbmmpvvh.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gtemrndcwe.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtrmiwljgh.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtfxaljjik.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtuwihsxrr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtuozdobxz.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtitumpnrh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtelntgxey.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gthlzzqhpf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtpzjwhxnv.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtxhnrwczh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtwrsjfugs.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtbcugcikc.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtkqphquxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtvhzhlcqh.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtotuquzdo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtjhretuzc.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gtnldsjvfd.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtdsbuuwvx.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtcvksthni.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtasmauvej.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtghdimixy.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtsiuntbeh.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtdgtynvsx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gthvtjjhdb.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtdurgtaad.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtcnugbmpu.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtnzzkduym.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtjojkgach.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtmfqrducj.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gttekxaqlu.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtupgnyqek.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtrilmzibl.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtxvsktywk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtobsluxiv.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtdpcedfwq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtcekjxnyq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbdbrargb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtbhrgnkkf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxqwaamkf.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtuemrfoch.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtlmjbwctl.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtkoaaixpk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtjyqxxaln.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtocmkbwkt.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtrcprxoyf.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtqzidjkmb.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtzhrjbyeb.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtvcdtnejo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtaxqjougl.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtucxwbgvk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlohrjqzq.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtptzslryb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfycfojwl.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtaoluenfh.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtferffkdj.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtcarvxwwo.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtuqqzwsnp.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmiygpdc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtrkklxssq.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtzojxcpgf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtnvfekdsv.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkelxosu.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtcahsuiig.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtwhswdufg.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtvdsjmygp.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtbuznqzeh.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtgdgdwfus.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtiqtbezgf.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtefgefube.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtoxbdkwxn.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtgvvgqmog.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtnkrggtjg.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gttfwstqmp.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtipgmmvxf.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtjnihizdz.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtcjslfyhn.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtjdswwvqd.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtrgttopii.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtgsxqwmkf.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtsbapoatv.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtojrmedpm.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtqyxidpgq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtqsuklzma.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtrkgfalpg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtqxsdqvfx.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtyrmqrknm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtdiptnvne.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtqcscjluj.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtecyibkse.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtwzpnbluj.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocpzqxdm.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtgnzbdude.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtvealyrsk.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtoggcwuvb.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gthlhlffyd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtqkbrweuk.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gttccdcaay.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtvlhptpss.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtjnmmftor.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtktyhpsbr.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gttqaigkvy.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtlywkwvzo.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtlxoayntf.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtomjrlvez.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gtrzjyhorz.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtqiwfnxha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtcrtnleqq.html


<!-- 参考信息 -->