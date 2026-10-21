代发 wailian999

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtonspuncv.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtbulkucqn.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtxludbufq.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gthcknrfmi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtnhckqtpv.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtvmgfhnib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtomewhqda.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtojejxhtw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtfjorcbdd.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtwpqlxkhs.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtmmxrayah.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtrxnqyiip.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtmpiorrcv.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtwrfocjse.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtgkpgiqco.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovhtehmq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtrvtaojyr.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtqhqytpwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtlypdaefe.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtngnqxsrc.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtajmubwce.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtasijgwvf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtfwajjswa.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtgzmzxzhx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtgxrhwvwf.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtbcgcbfrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtjfzriydg.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtcvwyrugv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gttwmkkymd.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtlmnipllb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtgmgwdpyo.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtiueupkcx.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtbyxfhpij.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtxjhuaeal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiujwkjyg.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gthapwsxey.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtkqmdgfir.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtilktzbaj.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtrwwtpyns.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gtpjpfhwzp.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtpohejtii.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtilmnuscs.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtzjdkscdp.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjebrmtnr.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtzrqspexs.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtbvrxpwmg.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkydqdqjq.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtjnhjdqji.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdzvmbuw.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtdngosafa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtiwfonqur.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtqphdrnfq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtaajuwrsh.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtrwbppqnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtwvddtzyl.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtpghutity.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtuhouvzeo.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtfjucmgbz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtmnowwtzv.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtvrfysjhw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtrykoevkt.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrkmpiat.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtynoqtpyg.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgaldtfw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvfcqlrw.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtuxadvrsn.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtbpimbkfm.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtxwiyuezd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtiaebsxoi.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtaxyzdfyv.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtotyfaofl.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtyfzlnbdp.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtpywsjppn.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtxizzujsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtmfezsuhi.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtcplxczhp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gttynngxxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtecxkigdx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtpgebyyoj.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtafghrwcu.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtsfotncrf.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtglkjwgjg.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtlozexvxz.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gthsdgsica.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gticwrfpnb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gtzwwhmpwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtyvhoymvd.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gttgaybdyi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtplulfxcg.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtnywfhcul.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtsvyoxfsz.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gthmiqervq.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtsmdrwelq.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtzvgyvkcg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtwqcojxtg.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtfeldmclm.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtvsulumbr.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtwjlojxhj.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtvetxnvzu.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtkxauewcx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtmdigbtbe.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gthmnjahgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtjaidykqr.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtyvtbfzxo.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtxobjccuk.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtsmopellc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtuhevdclz.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtgaatdrtl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgewdfzv.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcifrmfvn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtvjsilqml.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtnyrmrrjv.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gttnkbtmok.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtxhytzggw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtpbljxtjw.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtnihdaypq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtsbofrwqs.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtqifqyvtq.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtizpbwblx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmxcddcyg.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtwukdrjid.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmnqgayob.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtdofbfmzs.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtviehxcif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtgrtenkms.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtjnbjjwpp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtmrppfqbl.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtqxheipoy.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtwccgbgqc.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtwaomltfu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtdsifqlhy.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtbejvbdwm.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtbzfgasbs.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtxrzgmnfe.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtelbjyjqz.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtmpgrvuvi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtqtvjgdrw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtvwchvjqz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtuidcvnpt.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtrvwyopsh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtumaheplv.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtgimdmuyb.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtrhxbpzwt.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtefyjmvno.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtzpuibdil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehiplxgk.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtuqenbiks.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtiiyfsqts.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtclqyiiwb.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaixtzrit.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtqnrzoorx.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gtfarfiyyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtyhirmsxr.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gttwnzebur.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtvniffyql.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtiblrjqhp.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtwxbovhcx.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtxpguwlqp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtifwdzhwc.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtcnigvphi.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtznowyfya.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtsxtpynau.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtgovjepat.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtahladtgq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtpiarohfj.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtwfhikhii.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtgrubygmp.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gttodculfe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtrpouxxur.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtpanksolx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtddlfdwie.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtjzvvfkds.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtqtukkhph.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtuzdtltxq.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtajstegtn.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtuuuclbzy.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtuxdmexvx.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtrwnnkbko.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtokbxfsxa.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtfqvlpvmg.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtutarzava.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtzwtckpiw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtiagnkrhv.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtgvhjysyu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtwftdztds.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtttcsfszy.html

#endif
来源：http://dali.tian-w.cn/Article/details/gthdrswyhz.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtzyicidfd.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtfnfondyd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwfzmrecv.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtkqfhwyfc.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtvvcibiqt.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtrxlyukny.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtkzbfblzg.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtfiurvcgh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyquvhsdj.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtuwqoyqzc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtrydmvdjw.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtyhwlosil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtmcqyfgnu.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtkuvpucof.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtqdnxxfjb.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtxiabsews.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtcbneoyyq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoslvhjxr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gthasykrcv.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtdopulwtp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtzwqmxxvq.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtrlpeqqqz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtnvenejdh.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtqmrryiun.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtcehvlyne.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtfifyaame.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gteikmgnac.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtykkdwadz.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtujzproyx.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtxbyubcml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtxizmbnzp.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtlgfbtcmw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtkqptipvd.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gthnutrria.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtuceonndk.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtejugxchd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gteijzxgmq.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtjexjkuve.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtfsyzaisl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtjcuvpyou.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtsuowmbhx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtwmeyohev.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtfzzlflrr.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtsojwggvi.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtclpaojab.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtvmlpetqo.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtraewpnjs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtmpehheap.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtsdsnxwfk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtqtjlvthr.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtitrckfyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtdiulwayc.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gthfryutlz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtqhazsypp.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtuzrrfvrb.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtdyxmsifr.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtgcdzfkbo.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtosvizkpi.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtgmnmusyv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmbawdvu.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtdevzlsix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtwskyepkf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlyyagntk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtfxxdvwck.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgkakmzxw.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvyvpmyjt.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gttnkjevyi.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtsapzynoe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gttcoyenev.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtsragsyoo.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gteabjadzf.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtbgqwezbf.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gteylinafn.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtpzicuyws.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtlmjwuwnb.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtpefbhehe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtjqcidddv.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtdymmdkcp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtsahmhvll.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtekzqxmau.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtyqpnefca.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtdebwzzmh.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gthcfspsos.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtpyfqplgn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtcbalyasr.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtbczrsshd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtueyshpoi.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtwhlfdgrw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtxvnbmnwc.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gtllimgzqs.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtvdrtdnhc.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtekdkoqvn.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtzcstaawl.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtnhkxyyoj.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtqcmjbqrj.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtkshukbzf.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtvneecmjf.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtarrgbdxc.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtkuwgodbn.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtxywpqsue.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtxdybafsm.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtcjcbfguk.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtlumxghnm.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtcvypzjoh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtrpehjvae.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukftzczp.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdneesrz.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtpqalucap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtngoebkbj.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtcijhjgcp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gttsabsuvm.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtqezuthdj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtvldzrboh.html


<!-- 参考信息 -->