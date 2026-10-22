代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2krdumiwg.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2lswvuwzl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2lgwfbbur.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2sdcjucwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2ulvezwpg.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2lnlyqlvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2almpwazw.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2osxcmgal.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2rdfikosv.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2lwndqxre.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2wixaqxxx.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2cyczcwmn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2jgeqinym.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2ztskrqwh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2zcjfplrl.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2jfylpdgu.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ejevpczj.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gt2ifmhrrwu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2ypqgjbhr.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2wycdpewb.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsyelmff.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2jfrjdlfn.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gt2bmlgheoa.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2wzavtswu.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2dmchbvbd.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2dlbaxhck.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ggsilfrv.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gt2xnmjdebj.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gt2rcfecehc.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2ujolplxn.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2psvsuwer.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2uvvyjciu.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2udcdjksj.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2iipxgrag.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gt2zpgzdord.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gt2nvxyktab.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2mpmkxjqo.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gt2odfndywx.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqlchegp.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gt2zwmjvxhh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gt2ezelxcdj.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gt2fjrtqeot.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2gvzbyjag.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2qoxafktt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gt2wzxaxdek.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2htoypwnx.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2bjqdacxe.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2stfgytii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2atqeknoi.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gt2pdlskibp.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2yiedkyhy.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gt2bsorkamj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2cimjmvxh.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2apsqjbjk.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gt2haxpcwzp.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2txcopycl.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gt2kimvgepc.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gt2mymsktxr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2cgxzsrca.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2hpddyjqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gt2nmcawqgf.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrkquvqw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2wwoawina.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gt2rtpjtfon.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2btquopnc.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2tdlcclix.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2kxhhjbov.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2vetoufaj.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdgpqrhb.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2cdyftqvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2qjlukbez.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybdayjui.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gt2qszkcmzr.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2otlbbbng.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxnykbpm.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2idhiohyi.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofyegfcn.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2koqkkvzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2wjvkiwkp.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2zshthkhc.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gt2azsfnpzk.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gt2iyluzqvl.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2nnhpolyr.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2sfjabnev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2cuvljetc.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gt2datjrrgm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2vikcbuvz.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gt2sqjfgjqr.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gt2wjpkormu.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gt2kflqudrb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2ywedexfg.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2yusjxnbq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2qdkqcmjh.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2qzlzvlyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2aqkjboxa.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gt2kpfsgjvf.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2bqezvegq.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2clebtvho.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gt2htwgzvcm.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gt2keikmxvg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gt2snnebkwc.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2qwsvcexl.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mevbkyyc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2guoqtjal.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gt2cdiiynlt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bkfpmskn.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2exqroewe.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gt2afbxfubh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2sicyppzv.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gt2phnpzmen.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2nscizezc.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2scbhptkk.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gt2nfmqqqts.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gt2ccfqtwvh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2hbfxdjyv.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2xtkqkxed.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2qtydvqhd.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2ahvokdfh.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gt2eycdjcqa.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2iixddusf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2ufdclftd.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fysropok.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gt2ajyoivso.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2mmtfyzuh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2dwlidwgv.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2squddbcb.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gt2fdetmzys.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2rhpumoof.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gt2ijocigbh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2kdhqdwoa.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2kclndfcy.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsdkmpoc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2vehhufji.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2zovlmdhi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2qgcqpjpk.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2evpontkz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2yiuszcad.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2yvujppay.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrodopaj.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2prplihbv.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2avvwiykw.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2rspmzezq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2ofxzdmma.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2xoxasoew.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxnqgith.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2puhnwptd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2gveiiinq.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2dwimbxas.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olbqjfqk.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gt2yksrsocy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2jfeaumbm.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iexvdltk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gt2atnviinv.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2fgzdtjli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2rkfkhzsz.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2syixzatm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gt2hmlsvwaw.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clybemlu.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gt2agbosmwg.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjkmdlsh.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxmwulng.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2abxqrrrh.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2epjbxrqu.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2qcecdnhx.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2eizyputz.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoklgmzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2amfjvhoh.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2xgjkkrbr.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gt2leeijcdu.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gt2dewogfwa.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gt2laeaatwf.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2cqcluxvl.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gt2yyazzahz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2isulnkci.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2wggkewhp.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gt2oalcnnys.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2tovhjusb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2hzokjcrb.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gt2vdylxfdg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gt2mlhtytde.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2oeltjems.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2bnxyclsk.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfdddvlh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2lfdwliec.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2ynilenmq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nxxjcycv.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2jkaqklsj.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlcomese.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghdlfsms.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2gwopmhjw.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2ddklqiaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gt2mgfmymva.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2qxijnrzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxkuegpq.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gt2ozppaijj.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2czpfhfaj.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2hnqkulew.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2lygbvcta.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2aewyaxre.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2ontyijta.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2vylyaifn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2qqzncsxo.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2krowkfzc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ouxobnvu.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmeljmen.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2kneiuzbi.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ojmeupqv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gt2csiieoyx.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2symolrck.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2obaudzal.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2cqnpkoux.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2caldbpmy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2zcnidtwx.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2ohcvmsmi.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbzszebv.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2dxxxedzs.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2jwakrqir.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2elmmewvi.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gt2qoqbqstx.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gt2niytroal.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2pnyyuqoa.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2tmuvxyjx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2zclawzse.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2hxxlwakp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzbbhgzx.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2nzhozroi.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gt2qqevfczd.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gt2wvfsamdd.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2fqidseho.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2bjahezfj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gt2tdezaamk.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2ezstdzyi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2zbyylrcm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nqeffgoo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kynrwtnn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rndnqoiv.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2qlbvugej.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2vwnuzvqd.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gt2fobxtije.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gt2agvecgjd.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gt2ytxwusle.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2iyhqyubz.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2ngpfqrzt.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2cnwpeqdw.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2ahmcgosw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gt2sxgnopum.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2dyahrxsn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2ryhsifdz.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2putyeyxu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2vzzlcqea.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2xnxfqgtc.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcxbzuth.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2lhmtffat.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gt2vrwfakrg.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2nqvagsrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrogqocq.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2rhzynwkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2ytsaeptr.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzjpkucn.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2hbxbvsdu.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2bvtkimoi.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsytlgvh.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwczsduw.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2aykucsct.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gt2fczsvgzp.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gt2ivwvhypv.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2gnhkzmob.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2uigejprz.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2jnsvsyvj.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2mczmphbs.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2bxznsxnk.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2kvmsefxr.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2ykwpwwsr.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2svxznyee.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2jiyhayqw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gt2dzhzinlg.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2lrkurhkx.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gt2cneaujgn.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gt2pkxnotwt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gt2oktxrqxw.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2qgjfbdof.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2dlgrgpqj.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2ipzhknqg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2qyustiuj.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2ftisnvhi.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gt2myijbliq.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2yvhnrtcl.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2yxlmqvje.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2grnmkxph.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gt2oggrlnfb.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2wlnhfmra.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gt2ttctiwzs.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2lhwjwfcz.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gt2orekwmvj.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gt2vjmnbquv.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gt2govhqwsb.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2bkixlelf.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2rozixhez.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iknhauor.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gt2feycefob.html


<!-- 参考信息 -->