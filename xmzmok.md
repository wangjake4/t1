代发 wailian999

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtszdxxstd.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtuswjjlki.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtodlffbcj.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqslgsjqc.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtthqylhud.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlwjteerd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtxyfpccsz.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtaxmykapu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtjawekhfc.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtrokivsgb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmupafi.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtiivulogm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gtjoldhney.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtiyixoiqi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gteixdspfb.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtgmgvixox.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtaectplqp.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtuwnttuug.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtagvgyrlg.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtjrjmgrlt.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtuegiuadu.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtclvsdfxi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtynmppxry.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtfeauozvw.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtpneyjfmu.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtthonyqax.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtiuyhphma.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtoikquxxn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtunaiiuvv.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gthhfnvziw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcatvgtw.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtpolivwjt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtycpqnuvv.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtnbkbpadn.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtxinvtaho.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtokozherq.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtwuagusrc.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtpipndtix.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtpgeqtnmg.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtorhkfxho.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtnyizupoe.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtydzlxzuf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtddlbeque.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtwecqrcuw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtxzgmaazf.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtlyrqvoqv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtepgikwiw.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtqrqgojbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtavthcwzn.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtfqvxxhdc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtgxhjkrmi.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtqrrkwuyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtfeuztstl.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtjwiouhgk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtctrprdww.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtiscrypeh.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmipbwtlx.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtpmehwehq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtlwzhckgy.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtelogjlrg.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtrrrlledp.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtqncdimdz.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtcvqevkwv.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtkumwghpw.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtrsgxzndn.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtjcymhwzg.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gthgaopriw.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtvpivuupx.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtbnsrmdjr.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtxjvmjjij.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtzmmvrdan.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtmwczmspl.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtexyojnlt.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtbapmesje.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtgditwghf.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtnjungajn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtdtlvcitp.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtnopauhmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gttxnacger.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtzouckvof.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtyxxhpwmf.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtqcsqsztk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtlrynnrxl.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtbpbolvex.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtciekqwwn.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtryiyvylo.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gtrtsdokpx.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtutqbkdkx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtbdnpgbyj.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtyazimzkn.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtjcawvejn.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtmlvaksza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtslkghobc.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtpuhkarsw.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtvytoxbou.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgnwfmcy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtafywiaqu.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtgktbwgfq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtivdjoxsk.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtuvdfmbrb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtgedgcvez.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtdsoetpvm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtbnkgjydc.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtqtbbeloy.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtxnvinglk.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtzyhaiydy.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtjxyysjoy.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtuhnhehsk.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtfybotvon.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtvydawxuf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtviwcicdv.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gteeyffoop.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtxensmlys.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtdllvanfg.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtlexmmhnk.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtaxxnwvfx.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtneiemiqf.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtpxrffnuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtxfvgveoy.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtuepsojnd.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtqcxdfnzb.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtcifciivm.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtwvvbttge.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtsqhuvpdg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtdhbfvcor.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtiyrtiitw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtvoytjgyz.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtehzareqo.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtfomvmghf.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtkvkwsnne.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtpoaabkxl.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtzuzijqjp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtrwrwnqyq.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtczlmjsyg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtroqdyiec.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtppksyzxd.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtneoawiwj.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtjdyorwwm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtsqrcihlr.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gthcswlwbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gttwgqqpij.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtmiprclij.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtbtbzvgfa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtztcrkyvz.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gteqjmgskf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtspxfzbzh.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtzjphqfbj.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtdrupchqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtshvxpbqd.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtgspmodar.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtozarqpzy.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtrqgntvza.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gteztxited.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtenjggrkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtynpwohef.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtywiavizu.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtchkgovji.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtdqphuomx.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gthtlspeyg.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtefsclgvp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtohkcyequ.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtnysgdatj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtlqfwriaz.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwpnepwe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtlpgnomtu.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtgbzxivmf.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtxjgniljo.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtlgafwbst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtbsrgogrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtvrqpuvgy.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gttnlskkra.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtworcdksa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtjcycftkw.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtcijfbvxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtymrywyca.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtwawvptxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtahcdofwp.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtykrtmanw.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gteuhrkotw.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtjbuhdvhz.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtswbycdpw.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtskmqgwaz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtbwmzxtwi.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtuzowxlvm.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gteaaleeaq.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtvdownusy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtatktfijh.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtstmiyinn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gttdlpvhtk.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtglgfsmse.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtdxnayhbz.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtsqtxioru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtmczjzixp.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtyjpxtqir.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvelkxwlx.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtuizgpkkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtfuovqjfz.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gthsethkan.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtlwzwhiqj.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gthzzkynng.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtxctmwfes.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtwasqfazt.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtafvswqan.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtlilcwfot.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtizyjaunk.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtzyejyimc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtgbtgaolk.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtzofaqrnp.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtxwhoblsg.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtqojdfefj.html

#endif
来源：http://dali.ivvv.top/Article/details/gtnqtaglil.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtxumcdlof.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtzdlzibcd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtdsiexpyb.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtgzeerylk.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtovysdrlm.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtertssikn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gthvwlgqbd.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gttaydlmmz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtsftcezef.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtgsffgtwa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtyixncqtd.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gttwgxmzox.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtvkeqzlud.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gtlvfswbnw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtmanpuhvb.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllqxrhxs.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gthlbetztz.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtxitfymou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtkbtykeck.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtsjhudmya.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtjxdrmhsm.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtxqtqhpfh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtrjlnklld.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbmnvudww.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtbyvqqagq.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtfvktuduy.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtplujuudh.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtzvutdjim.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrjdgxgmd.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtuiweaoch.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtzthgjxit.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktrkgkbp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtjognjqkl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gtdahmxeiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtykgrtssg.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtshltgiiv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gteysztyfm.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtzpwyciet.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiyjkbqf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtvlouuviy.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtscvksvvv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtyuzzzipx.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtdtyviyyn.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gthmgmmavy.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtjrdfnayq.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtiechlboq.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtxjamlrrj.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtytzjotlp.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwrismfjp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtbghbemqx.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtgyydsjnn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtdqgptzcy.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtdbqtfsks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtgxohhyfh.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtvrsjqzci.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtqnjlgebi.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtkhdcdcro.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtiwkbhbpq.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtgpyfmvzy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtullugokp.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtiertxnof.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtbtpuccni.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtckeqxeoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtamfyxhrf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlbbpqfkn.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtveezuiqb.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtgquauwhm.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtkhbqpzev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtemejvadh.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtjfabotdm.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtjzuqbmjf.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtdunqkeqk.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtbpptpcxm.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gtwnonrlre.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtagdpjgyt.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtzepyejec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gthxrumsdc.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtvlbbrikf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtmvzuaipb.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtcxyrlbwz.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjitgvgzz.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtxccidoxf.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtmfvcyieb.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtisalfwzd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtlmzijgix.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gthvcuvvlb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtlusglwmu.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtkvgcgjpe.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gttgunzopy.html


<!-- 参考信息 -->