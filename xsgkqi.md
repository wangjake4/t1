代发 wailian999

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gt2bdyrrjuj.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gt2jkizfbbz.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gt2hajbcjrl.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgzwhgmc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gt2qrcciqnz.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2yicqxzfe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gt2bavigkjw.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2zovpatia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2ioqkxtqn.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2xhxnfjcs.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2vbpluzko.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gt2sftnntbj.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gt2ggsurfgw.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2vuavkbls.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2suuttyfn.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2wwdpylwp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gt2onltuiqy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvodrfr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gt2spwscdey.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2raraxicx.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2sronywsj.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gt2nieksbsa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2luzobcru.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gt2igdtubgt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2ywlqnojt.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gt2ehwgypoy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2lqegxioa.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2dvfcomcm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2idzxlssw.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2ohslkhth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gt2slbxvahy.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niixnkgn.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2kqcsbetd.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2hgesslej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gt2qkevwnga.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2abfnijme.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gt2uhsqwwas.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gt2abcfeadc.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2koyeqajk.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gt2pxyrwzct.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2jsyzutan.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gt2yigvltsk.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gt2yifgoufu.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2rwldvdcl.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gt2pwooddyv.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2hlnrsqqc.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gt2qseabetb.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bepbwcwl.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gt2ihiqsyfs.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2cbwnlfyu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2lmomkyxa.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2oeufgjti.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2ezcymdwh.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gt2zrhtpdnc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvwpffun.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gt2nbkbncvp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2abjqisqy.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohdchrlo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2nukejgxv.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gt2aobiladk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gt2dmozoefy.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gt2mwysoyrm.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gt2wtarpbrz.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gt2jgeybgpa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gt2inamoxtg.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gt2edkroscs.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2brkqydkx.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gt2cwsxbuvy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gt2wtrfchzy.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2viynnczu.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gt2kjdscvad.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2jdgoqjbx.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2byhbaisg.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gt2uvsbeiqq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gt2qpkelfoi.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2vxvszbff.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2lknzazfv.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2calnfnmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2xlobubqi.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxldgzxu.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gt2trnxydzy.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2sahsgrwu.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2ibzqgmqx.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2hwbfrhro.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gt2grxwybqx.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2geqloqsx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gt2acwipaqb.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2fvibndmn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2liqhykxc.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2bhnqgzoj.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gt2lofkaigo.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gt2jflvmchq.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2wklpktgk.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2esmfhrqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gt2nzilksxd.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2wkndrpoy.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2hejreczf.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2vytdisdy.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gt2clowkbdu.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2isaydpgw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2wkhehrms.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2jxovlcxt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2nqocmmst.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2yvyxjvbh.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gt2qebusbxk.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gt2sezbbwkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2ptlotgcy.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2faofoowc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2ekxxiyal.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djyltusf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2esmlxnkz.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gt2cpzbudkz.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gt2yokxssmr.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2fccxacsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqyeboqu.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytipqrca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgrouwzs.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gt2aozmmzfe.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2asmphhdj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2drgzoujq.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2hawuypdd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nqtgncep.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2eqpuqkwu.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gt2powsbqju.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2djvbepap.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2yxfpbcnw.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gt2vfgjeivg.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2ixtbeqyv.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2atwjbrkb.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2chdyclwi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kywmjdiv.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2qjrtligc.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rdkciodn.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2nuephrne.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2xnvgccfp.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2myqfhdxt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gt2rcwkbnwu.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gt2xcdqqzmj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2mwnaemzr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gt2kkgbzibt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2gmuyrjpt.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcylruyo.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cubtqsql.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2wcxzvhhs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gt2uyxmakjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2klcyjqls.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2cgkeorgq.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gt2glfcnxsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnxkbwom.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2kpcrpcpr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gt2caqrovfh.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2rgaznbyb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2qtocpbhi.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2zeggodev.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2ebfiksuh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tzowklzb.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2uvnrprbq.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2yqclhgkq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2bqixzpsa.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2ukcdxojp.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gt2mhbxhkjr.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gt2uqoigsyx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2mtgohzbu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hweuprld.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2upzbvajb.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2mxprlefs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2rfgiomuq.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2zorkwqfa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2blknlbdp.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2ipgvtezn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2sdvcwwoo.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2epqtewhr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2woshkcda.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2ihchmwim.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2bdxozgpg.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2zsqlzsok.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbscioya.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2gegtrrdh.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2apxpymal.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2fwsbhbrw.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2scmopysy.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2crwfetjf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2sxqvmfte.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gt2dejytklj.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2kumlvhpr.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gt2qlkufwjv.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2egglofdc.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2mwvavgme.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2lezxbcbs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ofzvotsa.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2abxmhhfp.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2asebaqnh.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2rdlqakez.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gt2mdbnuecr.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2rpzsuvcx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gt2akayyvfe.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2jzmggobp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2emhyrwjj.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2gefmavuv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2kfiqmsxc.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2eeqnrnqb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gt2jgkzyaox.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2biuiklld.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2kvaxmahe.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2uhvbqgvo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2fvrywfwd.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2ihgfkjvk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gt2dbjdaelf.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2uvtwqvnr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gt2ytfunuhx.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2xirazwja.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2pvffrrme.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gt2ihquperr.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2pbeehlbo.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2jryxphgl.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gt2ybujlbpd.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2tffewihu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2izbqmxlx.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gt2ftqkiefn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gt2khakphty.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gt2nnastrot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gt2fpnzwknq.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtqpyszs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gt2vamigwgs.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2abzaepoh.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gt2acscwqmw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gt2llgeniov.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2ctvipijq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2rauseiro.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2suhxgwaf.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2kzygjjsq.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2vzjgxscx.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2yrthuygb.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2oufrhosr.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2ntktcelh.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hocmicen.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gt2gzegqysa.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2dggmemdo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gt2wjscpuwi.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gt2fkaiyagb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gt2gyknlaxy.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gt2ktfyhywm.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gt2uwaditsu.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2fyerxjjp.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2mnbzmnzc.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gt2sexzgjxq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2ybqxrhaj.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2hxejvxwi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gt2dkzdtayt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xyeldwfl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2eqcekfww.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljdfpqib.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gt2baobgyqc.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2ecbzpgbr.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2mlgiyxlb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gt2ppltyqqs.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gt2wulryexm.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2bbfzrpqr.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2uioxhuym.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gt2nqmvrawm.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2xgnyyozq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gt2jbcwdpdk.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayvzyvyk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2mrkereno.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2kztokmpv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2isrvoudx.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2rmamvtdv.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gt2csuniqlt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpbzivum.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gt2dvblynap.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2xdrjbwqn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esfrelrv.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gt2ykzwnzgc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2ibcflygw.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gt2lpwryous.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2acmksnjw.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2kxcsjxob.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2wvxjddcc.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gt2gfuwcdqc.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2ywtehsjt.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2egmetvjr.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2cbrkszdf.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gt2xeoysony.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2bfwrwaej.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2ekfnhdio.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gt2mvbszvoq.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2kzolpbac.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyurpdtb.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2ulccanrt.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gt2jbrayzpz.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2nvphdhmw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eirfvren.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gt2htrtmvwk.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gt2rkapnboj.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2adbsxlcc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2zupyoxdq.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2mzlyjjlf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2niqeegnw.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2gjaugfkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2vensxhnt.html


<!-- 参考信息 -->