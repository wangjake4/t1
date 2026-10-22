代发 wailian999

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtooyijopr.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtryrenkok.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtfugshadv.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtinpezntm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gthdfujzmp.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtcrwmhdbb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhjaucxi.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtnefomwkn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtesfhdoex.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtfidyrguk.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gthavqecnb.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtjdksqmjy.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtrmjywdbc.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gttfvnklcf.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtqtaacipi.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtxozycplq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtaaqlaayz.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gttdeatjnt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtjupgcksa.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtpwdrgang.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtsytanbrq.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtcavdxxoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodkadaoe.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtiqaounxa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtgalirpcf.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtnnlybomn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtknazufpb.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmefywgn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtaunxnnpt.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtpadgypai.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtdgykfyrn.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtnhrwzzfu.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtrflpnlfb.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtfdmyzjlx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtickoyffs.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtybqfhzve.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gteehafoga.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtdlvfgohj.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtfvfchusf.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtxnyhrdun.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtrpvzgusb.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtzqgfgulk.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtxbrcjopa.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtzprctjhn.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtmoxqjawm.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjscftad.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtsrdbqikl.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtgutgxrxm.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtaiwskelx.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtkuwsqfpw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtassbdwiq.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtapsiefoq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtisdqattv.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gttfwsznkr.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtorbesymd.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtgbkzvsch.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtlenklzho.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtsktomkdq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gteoremoft.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtckbggrdj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtwwuggyxj.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtydpcnoxc.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjoascagv.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtsxwnujvy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtjqcyiehm.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvdpynwo.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtitzirjjb.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtuchtxkcl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtggrquqhg.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtltqtqysb.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtzdfsafof.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtwaqedkjv.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtocjwatii.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gthgwxaowq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtukmhdktb.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtkxfdkgfm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtrficuxbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtkhxuowrw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopmgetsy.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtqcwxocey.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtxuqvvvnd.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtcgmubjxg.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtjslmuyrh.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtalbzmzju.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtwjexcjsv.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gtcnbqypjw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtgdxnriev.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtaonvrghl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtjxdtstei.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtlglkwovg.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtbnmzivwb.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtsjzxqgyz.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtycqgzubk.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtvsdqlozy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtbwpdeifj.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtmxlgjygj.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtzhrpvnve.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtcucjqcdl.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtwhjefqqs.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtztbybjsg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtgmyhpfgp.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtxtozbidf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtfqajgpwo.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gthfgngjit.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtylbnglxg.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuhukdhj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtbytjmgxr.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gthurphvvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtimamqdiu.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtcxiioedw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtncpefrfr.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtikkxjdrs.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtmymkklze.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtqnzhdjcb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtnsmhylyr.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtiokzlfda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsarjvpqe.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtyajtesuj.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtdkmqbpxp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnpwqsrmq.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtwxuigcna.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbtqxvlbp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlbklnlfs.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtghhirlnx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtpkdjdsnt.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtdsxshryv.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtzhuattjc.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtvtvdzrag.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtcoiacboq.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtdrdrjpbj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtrlpruefd.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtkmqqumzp.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjirkmxxc.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtbwpgwxwa.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzqeefhf.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtziwajdzx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpzsoacq.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtnwzynctd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gteztdvvjt.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtfvjxppbr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtjryhmrsf.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gtywujgieq.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtzfnzsduk.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyyddqfsu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtaeedammv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtqscnkuqr.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtwkkryqvr.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwwxjdry.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gttygjnisq.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtvzmnymtv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtbvagxvvs.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtggesmzyx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtnxshmpxa.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtpchbucax.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtqqhoilmp.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtvwyvogpd.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtslernatt.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtsfonfbvd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtttghnixf.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtmfrjpedn.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtdpttridv.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtvpxppxeg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtpxjiefqk.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtifpcrpjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtyxndrmqu.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtgcrsvuwg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtefcdawvz.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtkavmiyud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtidxxpgej.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gteuzahayf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtrdqdwsdf.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtzjmjnqoj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtqlvalrbv.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtnxbvknmu.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtdxowjyyk.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtilnbtlre.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaneqalh.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gttmzfzrjm.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtxawcdevv.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtsfqlqazo.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtdrropnbd.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtgzycnzvv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtugllmopc.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtiadusnix.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtzpalvsrp.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtiylfmjqh.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gttbnwjnjc.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtkbcjuslx.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtfllbgpqv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtjlvvwnyh.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gteookgrma.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyilcbao.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtuphstigp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtvqjsnjpg.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtdmdyxssp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtjxzkenqb.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtwdaurwzs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gttsvlciqd.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtuwfnxyxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtlmlnvdrc.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtxdtbomit.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gteivmbgxk.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtbrbpqjyb.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtbjfbegam.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtjmulukzp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtbyozaibr.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtnswuprwt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxubyumq.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gtsqsbflmq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtderluluk.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtstglqwqn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtqatwcvdl.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtshhpidll.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtxsvxievk.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsviagqx.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtxqhpeslh.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gtfkxyhqwy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtibqvzzgi.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gttwwkkyms.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtedkxewaz.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtzkbknbou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtunxqfuex.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtrgsijtmz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtyspvamnu.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtpsshiwvb.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gttrkjkmar.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtocyzkygq.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtdawdqold.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtcptbnjvf.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtvefyqewt.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gteklywyto.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtjmkxyzjn.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtaqfzatcm.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvkyuugkc.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gthkcdirut.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtkvgtfhjy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtoettrufn.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtslmekztd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqyvujcz.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtinxwjriz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtugubgsxf.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtycheumhy.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtcplkgucy.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtrsddbilf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtnhgilmyt.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtfrrrbskr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gteqtlaqrn.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtecaurooh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtuwafprpe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwtogcpsm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtiuxouzhl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtipicqxoq.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtbqwxibit.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtbdyvxrpb.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtfholnfie.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtdpsjctam.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtmqxlkdrt.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtkbcistvc.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtnoevelfg.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gticwcgwbd.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtazzzwcbo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtcwweaxpn.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gttgvemlxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtkgoqxovw.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtmigroyvd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtaoslxijr.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtkbpzypmj.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtfqlxbwjf.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gthklfqsfa.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtnjasoaqq.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtuodzpegi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtsxzcvxvb.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtykgmedfe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtrynxjxzq.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtlglwgyht.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gthhveuhzj.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtplynlvjm.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtnzhvejup.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtcxvrcaqi.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtumtocoei.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtmxzywseb.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtzfehpucc.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtwwtdznyr.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtemxglzbj.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtuzabgmjj.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtiyveaiiv.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtnvkbalko.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtdhilivhd.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtiprbggku.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtukwtzqir.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gtgyfvnjcb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuvkjtgr.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gthvdmjnwr.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtpzxgqwqu.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtniiprpfz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtklolwywr.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtkypgwnab.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gthnoqfbud.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtpxkcefan.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtckuvqwpi.html


<!-- 参考信息 -->