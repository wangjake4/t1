代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmsffieu.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxnjuzdt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2cpkvhrdm.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2kufszmlm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gt2olvlfuly.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2xjdclsiy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2mqnsvhoi.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2tgzhfcye.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2dfkcwqcb.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2tcdytsgw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2asnytgat.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gt2tzulovbb.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gt2mbvgqzqe.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gt2ngabxlmr.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2lkenponk.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gt2spdjhzdc.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2xzuruuvj.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gt2gbtwhcij.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2bbadppsz.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocabwacm.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayxahuag.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2meuizfvs.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gt2yogwpmhe.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gt2aapcddnc.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gt2eovedkct.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gt2enzmxxdo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gt2yxvmvruu.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpjxizey.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2pficsphc.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2byywkpwv.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2sxvtocce.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2qtezpkml.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gt2ujzdvrvi.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2defnhxgn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2skzlikuj.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwmngskh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gt2rbrcylem.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2gvngqujc.html

wc -l a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2xljzprzo.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gt2qhugvrtz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmagzlsc.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2xozaocga.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2ehksvwfn.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2dlubpgfs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gt2mzhalpuh.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2cgfetrrr.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2hpfrfzuq.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2rqbkadid.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2ugtlqfvi.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2njuqctek.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2rdltwatg.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2xcvayfsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2ghwskcms.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzqagung.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gt2vtwyzpda.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2zihppvmy.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gt2rhtfyscl.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2rvwxczre.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2tyisqara.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gt2dduowsav.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2ppzzczuz.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2yspdapsl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2ywdbfkka.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2kbikdxzm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2brfynnsn.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2ehjlqwfh.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avcuifst.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hblhecyw.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnmotgwp.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gt2redoyhxb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2dclnnqiw.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2vdylgqsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2gjlrhubp.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2htkmpinq.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2isxwlfpw.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2vswnxdli.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gt2szrcujlj.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2ynsldapj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2lrdmingq.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gt2dqcqqjbd.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmxtnkir.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2ablxrwfw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2rhljcrkx.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2imedmmps.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2edsmwgbf.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gt2gjteausj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2jaqwufcp.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gt2ewvpdlmg.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbizcoki.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2oogqaizx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gt2gbjlxosj.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2kgwjilhm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gt2uvlfoaqf.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2kdqkcesc.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2bxreauin.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qvnvimlo.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2dildmmcc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vfrofosb.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2eowdebkb.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gt2gyamraxt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gt2dwtdwutv.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2hfvyevem.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gt2rwfvxukw.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2wvjiynrw.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gt2phvcygeg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyytebr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2xiapaoxk.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2pvkbxdxb.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ydunhiwu.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2nyydfcli.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gt2udzysdgf.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gt2vaojdigr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gt2cwgxsnnk.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbwloapn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2lvkcdcsk.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gt2yejdzzmv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmwsurnc.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2gwnoeeiq.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gt2ynxerjgz.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2ohpvamms.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2kljriwle.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2mnpjixnf.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2ayzlyhhi.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2dymifexn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdlwmrto.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2geevblim.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gt2lsruwuyf.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2xrhmrjvu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gt2qtkkfzbh.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngkyimaj.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2nczzfvtp.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2gxlvskwp.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2zvuxcgoh.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2oxwemhun.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2tsyiyphm.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2fxqwfvak.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gt2thlntknm.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2sfkmavkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2ikysjcvh.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2myazwfnc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2wwrkvzwj.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gt2ejhbvgws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2vizmoxid.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2hyimvdfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2rzlkuvls.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gt2znpdghln.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsvdfhyq.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2nndxihgv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2sikfgicn.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2cggyebup.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2czeljxha.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gt2baayvfeq.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2xtjspsmr.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2wjsaajih.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2sgqasaeh.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2tndvsdsc.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mievpssr.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2cesnvdoc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2oqsiifst.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2vyhyossq.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2rlblwjnm.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2zquerjwm.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2ordwllqa.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilatwshy.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2envlawkf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2oricgumj.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gt2tairdake.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2dbbcmftr.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2zvolrmwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gt2rgqfcpwv.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gt2ewggawva.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gt2iotzazbb.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwnzovnl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2plprjijo.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gt2giucdqmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2efcxiaes.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gt2wzmztckv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2loeumklj.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2sfawjoqg.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2kikekvir.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gt2ewkzfrcd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2verlwiop.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2srcnrovk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjxwuaan.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2hmvnbjkx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gt2qpskhwtw.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gt2ksgedxkt.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2gypvuckr.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2hkzzetgy.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gt2oahdagdt.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gt2vczjamcn.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gt2ieqsytxg.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2touaepnr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gt2xtqcqeev.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2hytzaupf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pemjxziu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2yytaueeq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vryrhlma.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2angcxyxc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2oktesfwu.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2gvktwlmh.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2axxgjabw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gt2rsjvuftx.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gt2ycrxuzbt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2uigrmoov.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2zgksretl.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gt2qarcghav.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2cexbmqha.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gt2ajdceftd.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gt2amrzbayu.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gt2eimssxkt.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gt2aaajuvdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2wkpcvasl.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmxaajdk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhvwgbab.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwykdyeu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecrgvoma.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2vuztikvq.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2mtbfkzrg.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtuwyucu.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2aajkuavo.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnosccza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2nznusonx.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkrwjruk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2zjpomroh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ndezwzmj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2qxrawlpd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xvycezte.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gt2giulvsaw.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2mybqafcs.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gt2cuzoppdt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2orplmtgw.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2efotofhs.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2dwucllpt.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gt2innpynne.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2hsawiing.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2vatmsdrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2yxsvkhuz.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2jrfojytq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2kpwsbitd.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2daqxubdq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2kgzbrxnb.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2jllbzkvz.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mczrbjiu.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2xujgnucl.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2bttjcflb.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqklyvrl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gt2cwdrszle.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2wlnkjfhw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gt2mjtbpubj.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gt2xbzncaoj.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2qxzhfcxl.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gt2tkiiiujg.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gt2aszxrrol.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2fqdutaqk.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2apfcmsym.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gt2vespmljb.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gt2udyqiscf.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2xjxxrzmy.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2mrtpovto.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gt2nlybdvhu.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gt2nbpccgah.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2wofmnnox.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2xmyxxsrk.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2ooqsvavb.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gt2yfhazfpr.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gt2tvlnfkht.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2dhxtttss.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2brgfefgy.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2uogykxbc.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2fzvfowvp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gt2irsbxprf.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gt2xkgjosbv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2bjwtqxvq.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2vpduetot.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2akbbaycy.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2rnhrewcx.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gt2abxkivrd.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gt2xvfpdwte.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acwgvdni.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2cpabrpdz.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2nryxztjz.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2hjdwiwma.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2ifuxyswr.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gt2yqdbatux.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gt2dzobadbp.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gt2wwwkczhr.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gt2ubjyvqsf.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2mvgjbcvt.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2tlacaolz.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2zrlrrtsx.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2wccftjhu.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gt2fqukpsmf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gt2wzbkelqh.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2tqylrnie.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gt2ohjrksgj.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2duuvlotl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2nztoberf.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gt2eybywqwn.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gt2tsfuvsmg.html


<!-- 参考信息 -->