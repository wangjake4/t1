代发 wailian999

esac
来源：http://dali.nanxinkj.top/Article/details/gttktnfefm.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtimncvuxt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtwxocplrg.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gttekybymb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtmlqfuyfo.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtfeykwigc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtpuuauwao.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtwvawefea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtnocuwyen.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtogxibeiy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtngroaqgy.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtqlgoshrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfnkkhla.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtooitapfa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtwajipzei.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtifiuiyuh.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtlyytpaod.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtgjvjwhwi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtwwjbbxae.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtxfyebcmg.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtpxkabowe.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtxpnbheey.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtlmipuvma.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gttaosainy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtvzebbhoj.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtxqpuldpv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtdogdswqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtohcxntrz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtfzwztnqu.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtfpponzui.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtnotxllio.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtrlsyctjd.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtqdxbbczj.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtrzczjzax.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtexfgnwjt.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtbwpkikgf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtpbjxfjwx.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtuwslqmwx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtrcjjvwmh.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtqjwqkrmj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtwucpryrt.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gthhtowgxq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtfcwtvwci.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtvompyvdf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtjchuiaow.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gtmceqbynw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtozijooru.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtkuodpqbn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtxnpsdwze.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtpiasdrwx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtyvvngkcm.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtllulmdfs.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtszdtfrrw.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtbngbvtwg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gthfejtbij.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gtmxlxguyz.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtxqlsjdfq.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtwlciapbv.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtbplquacr.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gticjrzuix.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtivqynuqa.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtioigzrvw.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtlehhcbqr.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtcgqsrzpr.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtefzhxbqn.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gtvetcjfhq.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtvukwquwm.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtuedwhlbw.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtmhpfttvt.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtfotizxfi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtimfgleca.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtbhkstmej.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtdigawana.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtsfjpbagp.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtcvavpvea.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtjhgkkosn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gtzlfahnda.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtongfzsnt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwlbomsi.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtbmuwfcvj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtdxlhneia.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtpzgvourf.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtfxgowkpn.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtmunksvcm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtileryxws.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gtfagsynvj.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtanwlophy.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtnhkwsuvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtfgzfunms.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtpyqbbpgr.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtbczmvumi.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtoihwgdjs.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gthixltpfw.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtevpbwgpk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtjahdvplw.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtbzgwxbtr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtchpehokr.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtddjsvaif.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gthfoimrmk.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtxvmynjbq.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtxpkzixsd.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtfvnmjmaw.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtytgrsirf.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtweoytsij.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtpvbnvqyl.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtcuiapqrn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtdotwkqpc.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopdyyqid.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtexuorwzi.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gttxkgetlt.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtbdaifmlm.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtcuaeungo.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtgmtmyvwm.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtpnhstlnv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtbsdlqxla.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvwyutmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtkgctvepk.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtnppgjafy.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtextbdksu.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtsrycpphi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtftyxklnb.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtslzvcvev.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtisspujzj.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gtxsebrbap.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtddhzcror.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtdqrqdvoc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gthlijjnyg.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtfmnntvcc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtbngiphyv.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtfviruqzv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtmqldxevu.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gteajaqtqw.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtqtxcxjgr.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtrbnhshsz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtglhxqumj.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtdfppdmee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtjiqnyyuz.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtiaxfndhj.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gthcxshdey.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxxfvgomm.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtplfuehgr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtergfigtc.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtapnkjkah.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtvxbsmtnh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtrmuwikwg.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtpqcsjnji.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtggiqdzvj.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtqaiwzaic.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtohdwkolo.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtpbrlizpn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtoiqqexem.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gtzsipvwwn.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmfhkppqg.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtxchexplw.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtggpwbyaf.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtqhakpkdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtwathnmiz.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtozyecbks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtgcvrhcgp.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtnqvttyhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtyemunxtg.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjwrkzjb.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtdjbytkxm.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtyikcsnzg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtjitqeqsd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtbushykfa.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtkvkowatd.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtibnqhxkj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtjfshsodj.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtyxsrinli.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtdnxznbkk.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtuapeefyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtkflsaupr.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtncprtzco.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gttdckuvov.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtozrzlylm.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtqxvcibhc.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtmamppzwq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtxprorpdi.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrocwqezg.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtrhagghqe.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtmbgerfdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtpnftcvul.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtjlptqolo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtyhlfxcxo.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtdcwjwshl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtoaenvoot.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtxyczmqcu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtsfibaxvc.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtfenjgvcu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtwmzrdxxj.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtrsfdxtos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtlwaqugwu.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtihlvvsrx.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtikflwidx.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtmvaihxtd.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtksjbtico.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtihkfigxq.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtdcjstotw.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrczmpvj.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtvykcnmen.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtdxragqiz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gticgviqay.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtrpycsvwj.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gttvvoswbd.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtlzmsiykl.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtbdkvtrts.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtsngmwfiy.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtwfxrlohj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmirfqqjv.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtjzmdwbox.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtpbxjusjz.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtsxlorgmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtihopyvjh.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtcbdhrkbj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtvxicvedw.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtuvrhwece.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtjqywxjqg.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtfnegnlqu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtgnmcvdnc.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtrykvktle.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheskgxus.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtmzpkjaiq.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtgwblxnmu.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtjrktotyo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtrfintzda.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtzyztmgmy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtaddqzvit.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gttsfbvjzc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtpwcjtqwl.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtgnqzqlaz.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtvwfebqbs.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtadahvtwt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtbdfsilsk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtuvorutmb.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtlfhycgya.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtblbjynaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtokoitzxh.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtnlvyzgpf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtlxffyqjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtogismmty.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtkmztgseb.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtsvylzepw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtolnaiohy.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtawizgdnu.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtpdeshuna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtjsvdyoha.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gttpmxdsgt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtmfcylzzn.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtfnwdwswi.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gthlfjseyx.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtxbhydfxf.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtgapmydlu.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtucccqbvf.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtvxymzald.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtiqtopabh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gttxjwuwrq.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtwieqalqu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtndftcamy.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtvxtihyta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtbbuhbjuq.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtitgkvjvu.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gthradmunx.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gtlgdflmxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtmlsvwbhk.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtgixypznr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gteuvnlcam.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtneqoeqgd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtaoyxmkgs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtimbkwapd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtfdxfuown.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlgartmem.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtwtsweprz.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtwbzasvmp.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtdkodlygx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtevrizaxf.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtsxpgurer.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtbmhtfwih.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtaclncpjh.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtaymvatku.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtzqzknkpe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtnabeaznv.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtnindzbpa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtbpweyvvx.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtdjvkbuhk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhkstmxz.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxrljwev.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtznqnsyya.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtkbjlutku.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtrxgpaacg.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtuaodrzah.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtlvcaeqzw.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtxwhkillv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gteunmrueh.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gttualmlwn.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmsoqcdj.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtlgdnoktx.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gttkdaydgu.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtrpxdvpmo.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtjpopslov.html


<!-- 参考信息 -->