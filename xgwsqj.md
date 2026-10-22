代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtamquxkln.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyboqwwl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtfruzjkyj.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtrtpvvena.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gttfmbnuxr.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtvpwulzzb.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtaqjsjdhu.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gthfduxtno.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtuornhcrr.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtppkjyzix.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtgizznbzv.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtpflktrvd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtqupivdjn.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtktkrhsbk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtiiywlosy.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtnhfuxgid.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtohvbfctb.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtsvorlxtq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtnwbdgmqq.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtwmjjqeqx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtvgeqhsfj.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtbrbubcmj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtsyggqsze.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtuwaltxmf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtqgwmtpoe.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gttpniufvy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gtlageqcez.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtsuepmmfj.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtcphhdqki.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtpgqyncrn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtrpbtubmf.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtmklguloj.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtdaelijzz.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gttdajlqdv.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtckotftdj.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtkkpgynyr.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtbfedzczo.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gttocxpstm.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gtbctwfppb.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtjjyfwrll.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtxdysecpo.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtwosdjelc.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibjjxrmc.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gttdnebmhc.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtrpulijbh.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gttdzvieky.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtrsiteukn.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtgvmceenc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtzdlpbubv.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtftsjzmgp.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtbgewnguw.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtqnnzodhe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtuqqavtil.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gtqtkwvqhz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtfgwjkwkr.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtccrbukcy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtsfqigvuj.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtzpquuuri.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtbxgiikps.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gtwaqoamlg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtcgtjeaon.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumfyeaw.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtdpymrnyp.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtnszwytai.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtwdxzrpvt.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtiweiehrd.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gthdpjuiwj.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gttbozvtks.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtheqhfzks.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtcyumdsba.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gthelordtd.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtxiyftyii.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreclwhzj.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtwyvhvquy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtgrzrtzbr.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtjjecvcgj.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtzsedzwuu.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtjmmwuwqx.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtsfgymeyj.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjpoonma.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtkludynij.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtwdhtlrye.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtujoczrpz.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtzajcoxrr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtocrffpzk.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtyftysikf.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtxrzjeopv.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtdpfmyxej.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtcuretfqv.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gthzuqjamn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtbuvomkjl.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtvlrbchjf.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gthsaxpivs.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtysoeintv.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtlcilaxmg.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtbtkosikj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtqyobfdyr.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtobaqitct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtdcixosop.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtjxnwxjhg.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtizlrvkel.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaiasstw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtmkjvkrkt.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtwpnsgpmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtglzfcmwg.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtexzfjzbx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtdbqhmuxc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtacqnaykm.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtnxfyrxro.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtpvcuocxx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtxiluzfnq.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtqzwtkoem.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtxanxulmk.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtybfvyxad.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtpmejtcxu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajuizouc.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtpkgdmeiy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtekdtugcs.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtmdorsgqy.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtgyeggygk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtjyngijiw.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gthkhwnspt.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtuotjumao.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxurhnix.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtcgovkwlf.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtzazcxvkh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtbhvxiwyt.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtqybdnmpp.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gthhvmpxsd.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gthuxhswds.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtrndjjpmm.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtctgtokxg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtjuxyyfyt.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtbvhhtsrt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtjufihtrk.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtldpiwmkt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtbptrkgzh.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtcjijzmku.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtswosirkt.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtgnrkrxjn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtrmiemzsr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtimcncmhz.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtoyaokkom.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtiusjlkdx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtjvzullox.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaqctwjq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtlamitnmg.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtdtgouwro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtehpeqyzj.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtpkadschu.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtfletlbzr.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtvosypish.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtpdkpjyhv.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtfwcnspjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gthjuciqfb.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtruacfsrx.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtupcgtvqb.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtaizqnpvf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtogqgheog.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtfiivqdng.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmddyyuaq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtrhgeiozi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gthucxryqn.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtpcqpllvk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtbxdveaxp.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsslavawj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtmrrotjol.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtafyhlkig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtaszxbjco.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtnpbqmfmc.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtjkvshcso.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtvxmvvhej.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtysionlrh.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtsxfobztm.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtdguclktw.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtnwrletmc.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gthxcgdaej.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmcyzjmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gtwjjayhdi.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtzwefzquw.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtzldsyrug.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtogdsqkdr.html

#endif
来源：http://dali.ivvv.top/Article/details/gtowbtzukh.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtuawytply.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtzgccessq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtyqypbirt.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtqrhajhbh.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtwalicvvx.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtphnrqldd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtbvewlggc.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtwkpfbmbi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtdrqzrrvr.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtyokisfia.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtyamkzdbz.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtnxjytuht.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtjjmunlzm.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfrjotex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoizjjod.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtjsmqsvof.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtxognnmpr.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtszmshrwp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtldoldmqk.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtzgfmfcjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtswteeoeb.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtgfcfhgrg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtmjvsawad.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtzxxssrbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtesqbgqwy.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmikhfshc.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtlpfojkex.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtatrarfwe.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtzjeotlbf.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtcgzzdnqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtxquqyksn.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtqkeowvda.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtzydmpwtq.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtxpaqxdjz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gthslphhod.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtytnncbva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtnbegtvow.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtourhlyyx.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtwbddvdaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtlslbdxze.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gttetfmujb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtioyxjqyo.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtjibpkvbx.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtthzqjbcd.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtgbuvdtmk.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtzyztllfe.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtapfaqfcv.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtplzzfiue.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtzdqeffsa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtfrkwiyxi.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtyuklorul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtpdjvxynz.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtwdapirtl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtqxvqnqgw.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtylmsuelv.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gttofzsuqo.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtpboceolq.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtcutgqqhx.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtlvxrqgww.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtfscmjfcb.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtuzotttra.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtzttqqeto.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmwenwznz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtlxuvcsyh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtglayenfq.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtmdjsjhpl.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gthffziuln.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gtiqgvknkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gthdomzoqj.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtqbyovxjy.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtuompreaa.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtnxnhkxpg.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtfyzdbvme.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtgpvupvqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gtbwmxykxg.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtoolaymrs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtuhhibrgl.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtjvrfhweq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtqafivkun.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtnfyuhpcb.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtzinsghda.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtbrsfkday.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtkyecrngg.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtkosicduf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gtqrjligbl.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gttnphgqdg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtploicthc.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtsmunnwad.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtbvewumhx.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtgsduglmq.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtfjahklak.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtejvrnynj.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtxynpvbrb.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtoubfkxmf.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtjreeqmil.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtmrbhldmx.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtiddwzqlo.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtirgyrtik.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtvendnidq.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtjxvrxyim.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gthtvbsxip.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtxifklfhi.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtukyxtbtw.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtuzpftyrg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtcyhqllmh.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtteimpdck.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtersdoevs.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtxlivylzy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtsqrqtzqm.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gttzodkacp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gthfpbsoeg.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtnzuusleh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtufiouadw.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtaygnkrbi.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtxjceonvt.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtwwlboqpq.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtekyblafd.html


<!-- 参考信息 -->