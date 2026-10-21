代发 wailian999

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtcxjugexu.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtiaklbzxl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtofkplxjo.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtqayeysod.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtvwkitoex.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtczuhplkx.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtzkmqxcwv.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtzwyccsus.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtxfbjadox.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtbvpqtzcy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtxogbthzd.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtiwpaertz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtgzrybqay.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gthnysvoyu.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtopzaukxb.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtemryrddw.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtajvkoodk.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtfdmsvlbo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtsrdvezvp.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtfozdeatm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gthpctuhaz.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtcdyrpkbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtuubliqll.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtetrspobl.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtdschssze.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtbfthdhxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtqhnxzmpc.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtbgzjooyj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtkynlfawt.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtqsfivtbq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtdtujliic.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtdajieyvx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtmotmtddf.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtitgqjbnx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtgftbqvto.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtspiogdru.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtccqjjgwv.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtzalrjvca.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gteaipfgbf.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtncujlrpq.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtsljeckjr.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtpjvntwdr.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtluuvnqmj.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtvmjlszyh.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtiytdyudq.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtvkcvhard.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gttcfzhbgj.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtpghqhfcg.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtbbbiahlu.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gtbmgvnmlo.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtfgplzogy.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtmutqvljy.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtmpbwkscq.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtypqutfts.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtkogogdfv.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtwsvfxhaf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsfziuqr.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgfskqhs.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtbikuicvq.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtwwbptafz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtntixwhok.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtdywywnfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtbffldvdv.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtaqvmsdbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtbpvsannl.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtiuaiilmo.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtrnsexhpq.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtcanmuxzb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtkcumnkvt.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtxgtseeln.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gtmqbjmhdp.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtusljeenw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtphkxjwlr.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtehnmowuv.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtpbvmudqs.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtlgritcvb.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtuxndygyh.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtvavunuhs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtxnwiffnc.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtqzymqcov.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtnqeacjmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtppwfguaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtfkxxjron.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtyessbefl.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtsmsnlfet.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttpsydwyf.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtwoisbyjs.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtgkgcginr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtbocrtkfz.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtolqrmmno.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtsgbhljaa.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gthhogkiwn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtuffagyln.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtsdjphrnn.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtvpchhcxn.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtqyltzner.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtkepmxage.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtbadrkwyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gtoluzttry.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtleybyejp.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtzeqamyvf.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtofjwuhrv.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtatstdvel.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtfqaahdrj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtovftuwyr.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtenvfkowt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxtoudbcf.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtjrnckqgm.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycnhdidq.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gthpcssqkh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtkarrtfbn.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtkmplpqxx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtqrcddisq.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtaurwdjbb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtidbybqct.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gterrqhrjd.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtfequngwa.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtstgpzgdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtghzvrktl.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpawbvvua.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtoloddarn.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtlkisjbnv.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtihmnlhek.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtklpacduh.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtynhxpepf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtukmziknk.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlwqsqbap.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtluxupnyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtlzodnwjs.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtmogjiior.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtodosipvo.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtfukuhxmi.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtvzgkollm.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtacmglgtb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtulkbamta.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtwtirapaq.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvnzbqsge.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtklzvgkua.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtkyrazozy.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtndltiozm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtbbcafxai.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtcltgjdec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtgarngrti.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtujexrwoq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtwudpurqe.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtxoxtmlll.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtroofssqc.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtvbwctxef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtnyeoyxch.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gttsuyvmos.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrrpvrwv.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gthglocghd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtotgsurlh.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtjszgequu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttapprqmy.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtyjprvnoy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtabnkemon.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtvgawnnjv.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gthlqrtoim.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtvhqlzcik.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtlanldska.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtxamuwmks.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtbzeyqbkj.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtcwdefuut.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtieiueqah.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtaypdfqxd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtrwetqjhk.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvenosfu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtshmhxydh.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtqfypfrnk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtsvqxlqao.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtcgcvsugq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtmowyyahh.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtlbvmovje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gttelhajgn.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtrkqjiycc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtqxnskmms.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtkjrryolj.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtuetjspmd.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljignfpt.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtsjecgvpj.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtkucyqcgu.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtwvgcukrn.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtsccetmki.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtgowqhzua.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtmbqofrzw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtxzikmhln.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtfehiwqmz.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtoulfsojm.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtrrsxpvnt.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtrtifepqk.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtkreidlfd.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtobqmfzve.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtszsjhfai.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtytgdvhkk.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtahdschda.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtqnyzakod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtnaikemkb.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtempcowcu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtowdxfduj.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtazhjgkwt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtpajpinrm.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtxpakjzuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtduzuaiwv.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtapdsrwwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gteovdbbki.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtnkchdgyg.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gttpcyhloa.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtcpbtgbve.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxaokumg.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gtovufwmfw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtvlhzpcia.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtovgjicdt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtvhoytltw.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtslbggfjn.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtvghlvofx.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtmbbqyyek.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtnyhfeldc.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtnyyqwxoc.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtmtdnbtzi.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtappvvnix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlefckvr.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtothpivmw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtwtwhfgro.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtxwrnhdyt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtlnhiauvp.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtzbbqsusg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtiaiihaia.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtygvqzwco.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmpxlozuk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtnznkgxmu.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gttixudbqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfpatjth.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxckenvhj.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtmvyvhrkr.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtscigliaj.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrrdhgvgd.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gttggkooqw.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtquhbadsi.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtjqoxttds.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtftvezrxk.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gtgztduejj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtunzgwbou.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtjikqywew.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtntbumagk.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtljlazasg.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtigweagcq.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtlmeieoxz.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtsealtwrc.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtaoocsbon.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtqqprqdmc.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtvcakfxqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtyrsqifrr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtifmrtrae.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtxfxfqonx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrwoltvrr.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtfpahjmdf.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtoyyrthte.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtxmppwcqu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtzheuegrf.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtqwmtgqli.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtedvxvcbo.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtupmtuvto.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyfkzpeo.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtpntcnftw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdaoxvee.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtmfyjlpsu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtvzmqowcq.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtipbafpom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtiiofzxej.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtefdariiu.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtuolkgyfl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtuzrblaze.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtsuffagfx.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtqbikxrcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtlkhiehhq.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtiyilqtpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtbhqkjkyg.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtkaarfxbw.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtphzdgpgz.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtxcsumczp.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtlprlllks.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gthpnhsinh.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gttdkszqxv.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gttyjtlatr.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtzlqzlept.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtuxwpfhat.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtapdkllbv.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtkeohutmz.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtublqwzvv.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtdvqnnlqh.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtvzxbbhdf.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtzqxskvdd.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtmealkiud.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtuhmhwfnp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtpkibairt.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtsgwdiuei.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtboswdflc.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gtpvynjdft.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtsatiiowh.html


<!-- 参考信息 -->