代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtsneyhitt.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtpfpmmswe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtynzygjpq.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtntavmkim.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzhrukwy.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtsnkwxazk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddjyebec.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtkszivrlt.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtwcsajpim.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtatwlcmod.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtceucircm.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtbilaplql.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtairittxc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtvjjfopdx.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtldpcvnub.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtoxkxcnhm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtcracqjya.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtsiwyoonf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtllfymtvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtxloifgmj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtdxegplfu.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtkixminme.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtcuvlqldx.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtbhqaonvt.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtddpteqdt.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtbpayazpa.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtqpwfcpyj.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtbzqksxsu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtozqcbuzu.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtjissczsn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtvmteanbo.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtqdtqkjdf.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtivokkifz.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtjbkvczef.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gttsrnfykp.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtxmzihyre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gtdsajvnfk.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtrpqdpobc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtfvkmhwfn.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtxjyeqdco.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtgebdnvem.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtjeieajgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtdiamfgob.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtwkcinjhk.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtydptywhe.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gttcowtvwd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtoqggflml.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtfduabhmg.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtkkqjjtlz.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gtenxhsjar.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtmzgwschv.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtkhdobusz.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtxjcphccp.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtxwxmpjyg.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtmmjkymem.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtbwjupxwf.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtsikwlwsy.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtlhnbjhxk.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtzdnsxqpy.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtnjhickab.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtgbspgxtw.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtbxqxqsyp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxwjomku.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtyepcwdjo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtjiasqcot.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtycrudhmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtsaxndupv.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtiwktplos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtjzvbvnly.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gtbhixdxza.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtsfxjoiuh.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtgkfovwju.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtgoprqfyq.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtsergyvza.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtntjvwkpn.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtbkjvqzgv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtgbensbsp.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtkcdimshb.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtqmcmbntr.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitzuctwv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptalmquy.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gthylpemaf.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtkcjlelmi.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtdljxrdgr.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtljxwkslc.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtfgsjwjky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtunworysh.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtuupjubop.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgxaoxgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtduhxoowl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodchidmz.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtszobeaix.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtbcqnxuvq.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtlgepozsr.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtlcpoqpiq.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtlzxartdk.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunyfjlxi.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtypflejia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtsvyhisdv.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtzjbwtyyb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtqqahxaby.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtngybrrkr.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtobefbxof.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydbysoif.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtldxxgahk.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtgzyoiiwr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtrxidfefp.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtsrbypohh.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtdebkxhdz.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gteplxsgzp.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtjggwyjam.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtfcuwpjgw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gttaxaktlx.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtmitrrxqu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtfdlfmcfu.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtaafzrzzh.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtyxhdbtyf.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtassalrye.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtpnnmdrlq.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtlhlbzpzn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gthipkoyko.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtjpstrxms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gthlordzav.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtvgguhuvu.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtdtotzpox.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtelddtyyk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtztghpfna.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtkqkpgcfi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgjzcsjxi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtetleylxd.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtevlwdksy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvknpipdu.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpfkamkd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteivhzste.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtdavtuysf.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gteymwzgzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gthajvuhmy.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtxenzglok.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtbbbovlhp.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gtwoixnwwv.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtasvdbvfo.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtitgftxui.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtinootlws.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtbeaezsak.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtzgqaeadg.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gtnibvitwi.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtcvhcmpfh.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtqbprhzjv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtcswjqdun.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtesmnyqoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtkrrrhvlw.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtsmubxeus.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtrtibqvzo.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gtihhwquby.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtbwukdhyq.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtprmjfnlb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtcwqgdwem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtmoukfwxw.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtljhesfep.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtuonqyyms.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtdepcriod.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtprsbonjp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtxhyunhex.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtgauvbmeh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtnyihtaxt.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtygkqpghv.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtqmwafpgn.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gtrcxxvssb.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtfljjuooq.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtimxvuscl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtdqgawkps.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtzdvxpwis.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtzpvyclpg.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtvkgsiubd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtjuxvjhge.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgklchitm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtjczysgwr.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtbpcpfian.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtmdonfscb.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtasbvasyf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtlnmqafza.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvegvlfvm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtbpizwzte.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtxyoluebd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtcmshlasy.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtskuybuif.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtvxmgvcwo.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtuatyibcu.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtjkmkqsyx.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaahebqnu.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtsgojhrne.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzozujkwb.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtqwauzyhj.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gttyutwbgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdekarnaw.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gthubivsvt.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtianjoxpz.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtactjnsvv.html

#endif
来源：http://dali.sysykeji.top/Article/details/gthckyrahc.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtscqbeeuq.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtfdetafuz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtrokgyhps.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtpxbmslwt.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtljlloldw.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtybejxecf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtrraykoze.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtcqtcixhm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtpmcjbjnf.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtdyqdohcj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtbwquyhxv.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtfibdkusv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtnexiaane.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtannlhfjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtshmqkklt.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtskfkjkih.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtxtyouxwv.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtpwsyqyzs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gthlmgiwmf.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtvnogizvl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtwsuudrgh.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtvbssjfne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtxdmehypl.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtpaabopxo.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gtmptohsph.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtnlfyiqsf.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtrdlaandg.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gthwphoysf.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtbxkpzalw.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtnrujfgpy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gttcrgxkjy.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtbwpdxzuo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtxxxnvrbv.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtvoniwyre.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtlfzheljt.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtxfvtrjva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gttkaurqaf.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtrswdleuk.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtpijkerfl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtfcvhqfwo.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gttyematoy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtuyvdlhon.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gttgyhzjlp.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtjcxkjofe.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtchyxkgyw.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtdhaexomi.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtzfvajzjm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtrgjxib.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtaiwufirn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtofzofvfm.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtvxxnlfcq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtpaawmijd.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtnjnlzkuo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiaosllnx.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtaflewsqu.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtacwwizjb.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtiykcickt.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtyweljeaf.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtdomamadz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtxkzebxmx.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtlarmppqr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gtimefketl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzlyghwtb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtzvlplxhi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkydxefrq.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtagvugkao.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtskhgfgab.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtmhbjxomz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtnzgnsbbq.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvulppyaf.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtoiqqnlnr.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtpjarrcls.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtrwvihxml.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtuwzvuvxf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtszhfzeyc.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtqyasfwuy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtdrjratsq.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gthrbcktpf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtebpmzhhp.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtvfgcdfsg.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtnmddqjpy.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxnhfzydr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtxrrmajek.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtmdqihtpe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtklnavllf.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlmkkaj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtqfrioisz.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtbpkuwjxa.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxuxsjcka.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gttoskpsop.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtaubhaxnu.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtkdgzlyeb.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtjossquum.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtbyszxikt.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtptqedhfg.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqtfvthr.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtnjvxjhai.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtnmqrevhi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtdtnenkzf.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtlvuvcqml.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtwfanzetl.html


<!-- 参考信息 -->