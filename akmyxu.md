代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gteigvnoif.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzlsohzk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtlqnczzrp.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtyxotdexi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtvkvwfmqr.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtpkwvylfv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtexuwxhty.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtitlbohkm.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtrgcrkrdk.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtukzqcqss.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtcsdxsnkz.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gthysjtrhh.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtnhvhlmli.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtuysupezk.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtdehdqdjy.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtagmfqfqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtxmfkhkvk.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtcgxzgazw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtdivjiftj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtaglmmxsr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gteffaocej.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtwqjthods.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtepylzqwv.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtpgwvtzun.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtrwjvpxxz.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtknxyfclj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtyyowxltc.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtfipfsbws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtinzofuzo.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtxyiexbyc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtzaiwudhc.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtoxnbazze.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwofjuadg.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtqhssmwez.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gthiefchts.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtrhcothuv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtmermeqbg.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtgzatndsr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtbbifzgfp.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtibqqtvke.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gthnsxrxci.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtginzmxmm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtgebsrhux.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtaqctljln.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtqucascfv.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtksxcungl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtwfvgtoxm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtyqinolbh.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtvbxnltgi.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtbeytafay.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtaboiynbi.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gttpoayblv.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtickkrzgf.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtutuymhfs.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtloqsezan.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtpmurhrat.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtyzqltpia.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtyfdtzvqb.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtinhlvvfg.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gtorfbuisv.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtefxpieoq.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtdnompepl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtghkltwqy.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtkiuvwyfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtsqzzuekt.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtrmtogbyn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtbkdurkqi.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtyhopouwi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtbfshdn.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtcpwfjtfp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtffcjqrhy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtfnmeikoe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gtyynkwibq.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtfoocmose.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtckkvlurc.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtnqcpcyxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtzyboydfp.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtnelxiwmh.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtvuyftaqt.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtbjcjxbys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtuulkixha.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gttiawnqpa.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtlpvfkzhr.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtesyvsemx.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtrakizqij.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gturceafxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtqnhjkikm.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufdejrrm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtpwoykplm.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtmakhcmwl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtjfmgqykf.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtzwdwcevc.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtsofhrkel.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllxnzcpb.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gthyrstbnq.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtxsxogdow.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtvngcoype.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtjmynsotk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtbqytwfnf.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gthnvhjycl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gtuauclkhh.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtkvqxnlla.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtfbjcsvsh.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtfsmvibfc.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtcfvocvuf.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtjtiniwoz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtfcroucom.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtvxigyjvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtsteolklq.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtczoefenz.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtvjgddmfg.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtzeiwprlf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtjhinelgg.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtazojvalv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtdqvmqufk.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gtwjrjlvqg.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtvzedoiiw.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtvnijymqa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtchjkyiqg.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtyibyfnhv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtofhldjry.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxuipawo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtajrrgzqy.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtdazwzxnp.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtmozbbqcv.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtfehuyfjc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtvbzgpolc.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gthctekpif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtwrplyfqi.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtqpvlbset.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtcsdrxfjc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgzphacpo.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtzobcohpi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdjvnpjtf.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtepunxcth.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtotwcnsrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtqmbbhcje.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtkkklving.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtntdpjjrk.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtnhehdpxo.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gttuxivujc.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtmekelqso.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzprmetaq.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtpptbkiqe.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtfttdifsm.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtyshsljus.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtxfswgbqj.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gttlxgmiit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtvsgjjeqm.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtydiqldfh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtoimehfep.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtjnhovbji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtpozfgaik.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtzcarmgdt.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtquhifryh.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtvytbcxpg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gteihewjnt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtncewdatz.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtcrnygamz.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyubkjmvb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtlrmjcuxd.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtqnjmxwhr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtlomyblpn.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtpqfntgnn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtcmigkrif.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtgaizkdez.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gthndyponp.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtbrnkleot.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtkmcmrxhl.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtxniqbwhv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtverzsadz.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtnrtjqhtd.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtberjanqp.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtafthmetv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gthqcqxxyf.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtauiyealh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaunpgvi.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtnktipdsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtgnloljwg.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtspcfnbzh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtmcwclbmt.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtzqqgbwse.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwvcoipb.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtxfnrdrmf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gttxfavatx.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtynknaicp.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gthptyogpo.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtfshgcyql.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtfrlidsya.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtimzedhye.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtfevogenj.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtmqqbwcko.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtmmbynoeq.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtildjfhtp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbomyegw.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtvjjvrtbn.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtkhcusqqe.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjrgktwr.html

#endif
来源：http://dali.ivvv.top/Article/details/gtqpsqddvc.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtvwsdabkf.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtgvqkwokz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgprnfna.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtstqwuimz.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtpwgnuclo.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtlngrzdyf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtaevoyboi.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtubhwsiaf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtzefzlxqv.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtswvvcpcj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtpbsolsbb.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtjmkaqjqz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtxtbvxvtv.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtzrjfnokx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtvfrdbqrs.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtrmkwoybl.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gthhgjxyft.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtdmlsxzri.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtwcpoqadj.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtoikplrcw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkxcpcdy.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtcmgmznmf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtaehdbcvx.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtgatsvfdf.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtshjxmplm.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtrxuejjoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtdwcruukv.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnslspnki.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtxyllsbwe.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtskpoixua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtetcirclf.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtaiujrayc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtqsvqtuxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtgfibpyay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtmbltukvv.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtpjlytsja.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtrfkjwmau.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtlxiuplgw.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtfbvclylh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtrsorkvah.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpxbvyby.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyosfhilx.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtckeokxsz.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtbuhftthq.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtfsnztczf.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtwiytzkpz.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtnkhsoqsv.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gtretuxckl.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtkkideauh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtuxrvelfe.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtfggyorns.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtvvgxaslm.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtlcozxlem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtobvhkcfg.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtadchokbt.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtbfuulias.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtutekfgud.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gtzkdptgtc.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtkzgbzcew.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtizsnivdy.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtwfxghhsf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtkppsovtw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwxbfmxeh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtlqmnzmaf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtleluedjm.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtdqapkxgg.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtwqshdxye.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtwzdcozlw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtovjzqebg.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtuvdrljzk.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtdxvgwaky.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkujtcfdg.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gttmkoaiit.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtmeqtvidr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtgysbucwz.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtfnbidrsy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkvrihhxn.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtinnpjpjp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtjanbhmlh.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtntclxuhn.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtyqwhouhi.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gtzocaqres.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtfqvxkcnw.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtzgkqpqxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtudncxnfq.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtqjitsuif.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtmkaapfrn.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtmobvcvcg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgzfdtkmg.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtaekzynkf.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtvflnzjfi.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtjkwzinem.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtquirbvas.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpylsbbpz.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtnxmntqso.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtepqnhpto.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gthubwmpjg.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtobpzpanl.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtasoptpmm.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtizhgthgl.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtvrypkyxe.html


<!-- 参考信息 -->