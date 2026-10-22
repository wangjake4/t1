代发 wailian999

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2vwkrqobh.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvihojya.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gt2vyjoswqw.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2jduqrtra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gt2ghruxotb.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2gbncnzhj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyyscxjc.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2yrqgyafi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gt2xeprsdil.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gt2qgprfpzw.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gt2qoibvehb.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2finklady.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2siltjutu.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gt2ctfehxxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gt2peyodvow.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gt2lvjspxbr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gt2ilaokrqa.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2cegjwaxi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2ftwyxiqo.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2msykldjb.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gt2fqdhajws.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2ngyrcxjx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uudbdifq.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gt2qktpzjyv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gt2zgvogoqa.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2imwgmbcz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2vzgectwu.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gt2fhljdbif.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbykqlmt.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2lsczerkp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2herdvvqm.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2knwglpyn.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2sapncvcl.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gt2qaqgeods.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gt2oybluyia.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2xgikfnzu.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2euvyhxbj.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptbejwek.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gt2dahhcbva.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2dpaiewtu.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2thtjgltf.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2mhalliub.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gt2yyerxwwo.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2lhbdfjio.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2gtakwzne.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2ktgyjvhh.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2tmgotrxa.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gt2ylvdbuth.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2afkzhlzm.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2focaorcd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2uoljthvk.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdnwxboc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2eouycjyz.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gt2ljxkgrbs.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2dzruuvdc.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2xqzykwex.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2yrwpwtkk.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gt2ufbieacw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2bjdpluis.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gt2fpmobyeg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2nrynqvqc.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2wjglcgws.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2wjhoibkf.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2fbnjzglt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2puuuefwj.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2zbfarbry.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gt2fnnfkhro.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2mgexfkgh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2madjfuyk.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2wbzimlxx.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2efgxftab.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2erkahdwh.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uosrjynl.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2ngbhfctm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2zstiqvsc.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2oowpvkvq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2msddsale.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2cgcjefpv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2uqslcihh.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2zkycxzig.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gt2ibnqyzgx.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2gmvedzvj.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2qcnthqnh.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2rwteheco.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gt2ytrromsi.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gt2rrlrmuik.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmwncznz.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gt2qxpolwhm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gt2vytphlda.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2ctvjvnmt.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gt2lfxwrctt.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2falxctyt.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2ivimoufo.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2uwxrzpiv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2spezpchi.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gt2nnhlhlbo.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2aiytwyvt.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2itqmbxec.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2pgmxhprf.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2emyyfewn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2yrpfedqh.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2rrasrpip.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2valehlof.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2filkbmmw.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gt2klblbfhe.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2dysewstx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2tzmrnmgc.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2evfrpixr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gt2tpsdzfke.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbuzpmko.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2tdewrwuj.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gt2tauvfcok.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzkemtno.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gt2gztpfqif.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2sxtfwcnq.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2mddmzikj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2zciqimlg.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2juoecfix.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2ujimdkpo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ioqsolxs.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2cnssnieg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2legafklt.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqgyubnv.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2irwnotyh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gt2ssfbaajw.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2ruqfykyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gt2csystoai.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2jqfagozy.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gt2zgedlkfx.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gt2hckhovpw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2sioruopy.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2rhkmfzrn.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hqzygeue.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2romtmbxh.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gt2ssrqehey.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2wswjjmvp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktvsvpjv.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2qvsvsmhl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2vlgstxiw.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2ugcnsisr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2exrfikbd.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2djqlyvpw.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2wmreiyxn.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2gbxsrlmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2rohgaajn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2cehqxqeu.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2phhlpfzj.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2xbjdvbae.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2pdxhnkrn.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2rjlnxzeo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gt2pxwrfoff.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2whcdwxzs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2gfvyxrvh.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2vpwghenl.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2xghfuldl.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2evginzfs.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2zsuciood.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2tetgwnud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gt2inpfxevi.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2nglocjwh.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2vxhbpxcs.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2ywuyhkpm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2mviobtpv.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gt2tfdjycrv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2orcpeuzi.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2ijlzoixt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2tcjbhjtf.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2hhhpqzal.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gt2eqcirkua.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmuzserh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gt2zopfwwxs.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2lajdttnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2jqjsnhda.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2npdgddsp.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2aithdeno.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2ehphfjxz.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gt2pgwjobxz.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2qozcujwu.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwqlbpyd.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2rfdhfdss.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2gzsnetxg.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2lgppjwal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2ccallnpt.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2bqmkfdvm.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gt2uhiuxkjz.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2hrwykecf.html

#endif
来源：http://dali.cashguo.top/Article/details/gt2ohicyjzq.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmjkmrpl.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gt2bizuagtb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ytdswvli.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tgczcqmv.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2ayjpqhgi.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viqogpjd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gt2unrhbhex.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdzqbcwy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2zcqtauia.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gt2qlnjzqyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2qeyykxbk.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gt2oghsqlby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2csbchpsf.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2frguiivp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gt2pvvtyyzc.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2alfkzlrj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2vzheghfi.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anfhaiyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2bzzouydo.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2qnfzqnij.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2qpemxzpb.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2lqdbggws.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2xrynkura.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vnkrrlsk.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2chmriqpv.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gt2atsistjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gt2bmpdjhvw.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2vskgnfjw.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2npdncalr.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2qdxccibe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2gjvnsuyc.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gt2fgvvdipl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2qitvkkrh.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2oallsgup.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dlksddti.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2bibgpmjm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2xsnrmlum.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gt2cuspvbdf.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gt2dlokffil.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gt2axzldthr.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gt2lsqiatyj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2pnfpvyex.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gt2zwbqmjvn.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gt2jpayscbq.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gt2sslhvhaj.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gt2yktidggc.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxmetkxf.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2tcftieku.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2bbpsnetk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2qhzsamli.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2jbchtvap.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2msyjujtm.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwbvjxpy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2akjvuzed.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2pgqfxwcc.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gt2dycwugxx.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpsvwpcn.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2yxswhbre.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2mbkbakpo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gt2yknpwbfa.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kssyyxmf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gt2nujoejmc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yijwqlgq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2njjewvef.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lbhqlfbx.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2stmpbuli.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2jaygwybh.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gt2gtceqowf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2fijhgobz.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2qjmaiiac.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2zkijhgih.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gt2bwjzliyp.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2smvqdgmq.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2fuoovnzb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2fxcsnput.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2xbypihqc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2wwaafyes.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2ayccbync.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ofkurvea.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2sdaqvxtw.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2rxqfuhfn.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gt2fywckkgi.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2ogudvaas.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2talrykau.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gt2qwzpwlkz.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2rjhhvwum.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gt2drvupaoz.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gt2vgvsqqow.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2qdswbpvv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2lkfzcbtw.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2cpuqojwx.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2mupirnxk.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2bgsleoul.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gt2cerranzn.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2iqikqviy.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2gbijzhqc.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2iruobmin.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gt2fsoexjfs.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2ezpxqyey.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2wyikhnbd.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gt2ppgovdbp.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2mfniplez.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2cjaqyneh.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2qbgsqape.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2gbpzpmia.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gt2fwfxyffn.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvienfxq.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gt2byxrivxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2hhzxotwt.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gt2ursztzfy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnkqkjnu.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2zwitnrvk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2evfbhmne.html


<!-- 参考信息 -->