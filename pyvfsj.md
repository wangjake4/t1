代发 wailian999

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtmjtfqujl.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtletzkpti.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelppbhrf.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtyhncblcw.html

esac
来源：http://dali.shuidangran.top/Article/details/gtmkaxkhmj.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtweoqujix.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtacoufeoh.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtvzfveshw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtyjymbkiu.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gthcmdwwtn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrptigyd.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtwbodxgma.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtupkyzkdd.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtzbtmjmng.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtbgblvlae.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtuxufmzpe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtnudqfpsi.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtmgycestq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtinpwgagv.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtfvdtmoph.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtdqjvgars.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtkooioiab.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtmnnzoajg.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtragrquci.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtznoansoy.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtjezvdjlg.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtkwfmadhb.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoolnsmru.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrxuzmex.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtlovnmmpj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtrlqcffpj.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtoznfotsv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtjlabfdbh.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtxzdlmdmo.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtplhvqoxf.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtocqebkyi.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxxyalyd.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtwqnzhmph.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtfnftuamf.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtiqfjpxyt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtecuxkynq.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtjkcydziv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtpssyhcpx.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtaswcodlo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxdmoqyzf.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gttuxlbvnp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtkjfxlqrt.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtgarbnbmd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtamcajvzc.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtwjuhkppq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtjmkrblkv.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gttdzospkr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtrabmeguh.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtcjgjlzlv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtspqenbyn.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtwdjbdqml.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtegjeefre.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtlfbangwu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtzzjowboo.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtzvbudjcl.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtvkwvlfty.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtgsvvlkob.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtuzhhuojm.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtiktezrci.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtybybbupt.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtkpegcyev.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gthiaxjhla.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtxoeguemj.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtmgyfacap.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtulizcxqi.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtiviheyqe.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtnokvwnfs.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtldxfhjgg.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtyrjlorrc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtgmlzvzxp.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtbecvxyqc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtmxlwykxi.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtdemajapc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gttbnbnflp.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtrblstzct.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxpzkozx.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtdlmsfzyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtlnhroody.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtxopgtzmf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtycubkqba.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtvqvnnoep.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtyqpqmzzc.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtqcndsiqh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtaobkbgqv.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtqwxybgha.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtorefyjsx.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtoudqzfny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gtsmvimocp.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtvqymfqjw.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtrqymupcu.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtgopztjin.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtzhcogxoq.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtftwgbuij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtmlyaajcn.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gttttkicbv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtlfokevst.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtxfsudufm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtpmalxjgo.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gttgnfbral.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtfamzwdaw.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtxqqstmix.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtbutrlwos.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtaifhtijd.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtkoeznfun.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtypesthbf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtrqnnnkkr.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gthwtoztig.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtwjaqypkq.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtnlvajebg.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtjiqrfpqk.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtbnjmkipa.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtvfaeudbf.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtvyoeobei.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtqeaenbyi.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtqfrhjgng.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtghqrzwfc.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtkeyjtugr.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtqsygexea.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtglkrmjit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtzkziiccz.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtuhlumybt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtestefquu.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtcfqfswwy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtjuasqlfw.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtvgttlkck.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gthforfmyo.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gteuvpqdhx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkydhvgid.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtyjnqcrkd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtidkjylzs.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtfifdhxxg.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtxoafvndx.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtaygxakbu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtmtdwcluu.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtpnqcmkra.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtysisupfw.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtnridfxvs.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtxsebyuqr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiextwdt.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtmjajppif.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzwadcpsc.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtirbgowjg.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtycgtqxkr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtuqgupdvc.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtrfiemaxp.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtpomlwlio.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtwrynhhic.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtzworkqrz.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtvudobews.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtustqbsjl.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtanxdtpxb.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gteunmstle.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtubptbsed.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtoyamrxuc.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtxsuecxcf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtgvidgozy.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtcljchwic.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtulfcizpu.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtscussqrm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtqijfhvly.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtrmxojtlv.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtktraoavh.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gthrlavxmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtsrlgpeem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwwgxllp.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtwbaazemu.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtarmvlvfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtvrutcukd.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtbfleurxj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gttobcchqn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtgdbmyotr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtqgtwynhq.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtnyorgpuz.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtwaksgron.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtxjvlghiq.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtoxojecea.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtrrqsmaok.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtbgglrekf.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gterjzvbfj.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtsamaejdq.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtivxaoarp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtbjhqarqe.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtqdnnoffl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtnezcauhz.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gthacjvepa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtthsqdxxp.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtquefrvya.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gthxirvofw.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtjcaomcos.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gttmnyriuq.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtbkyurkpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gttkxugukm.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtroalsjwk.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtjvqjjupv.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gteczctelq.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtcpajkwxi.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtfsupcqyg.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtvayomdoc.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtddttckyr.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gttndqjjvq.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtbbcnokvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtsoanzfyp.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtvdwfmztq.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtjspnmodm.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtvaflihze.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtmrvublki.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtuqcbwswz.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtqgotswut.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlyodybat.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtoanrbsyg.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtluwavohp.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gtphlzgrjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtuzqmgfrd.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtlzkczkix.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtulruzjsg.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtkzruapqy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtmplsfqxv.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtqjotpgab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gthlphwerk.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghzvwzhj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtospnnfng.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtzrrsxxsj.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtnlwxuxds.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtcplkctpy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtbpevlesw.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtbiggxffa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtkuabrhum.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkmcbcdi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtkfzqvxjn.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtiafrqalz.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtjtlmmpaw.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtsulsdqxb.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtuwghcgfn.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtohyfkqqg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gturgkcdbq.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtfggymtwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtboxsjfkv.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqallwgf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtfveoppge.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gttbbhfjwz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtapdpcnxf.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtvvsavneh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtgxcpjtkm.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtvptuotwi.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gttxcoakxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtnskyihmm.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtlevzqzko.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtandaceoe.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtfuxopcva.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtfeufzgcr.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtkqavosqp.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtimtmgwoo.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtmttxjbfl.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtlmvbsuuc.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtpbjscywc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtqaljjccd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtvobzvepo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtzlraefps.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtjowxjdxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzkndzteq.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtsboxmknr.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtjhxwvwzs.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtomezjcoq.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtjtuhpydn.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtgdvyoyzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtilvwnccw.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtxzyyjiou.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtpimvdswm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlebfasux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtqvqjkxjc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoufrcew.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gthjvjojow.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhakstka.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtzzyiklyk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtvmexmtum.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtwtjhlasd.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtefomueld.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtfgtopavd.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtfbqwjoab.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtxrmgfzjl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtznsptjdy.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtxnxgoedp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtkswjxugv.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfrqrfuc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtyfkwdzsl.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpjalcoo.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtyedmmlyb.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtedhzzvzb.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gttqmxckhi.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtjejbnqwr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtbrqgyhmd.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtgjsidtuc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtkgbnenut.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtbomibqcw.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtucpdgbmf.html


<!-- 参考信息 -->