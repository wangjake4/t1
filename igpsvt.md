代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtlintnsmc.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtxupmymci.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gttalskfjg.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtalqffrln.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gtpxhxfarc.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtjrdrsmch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtfoporgoo.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtmonwgebb.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtbnikgpuj.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtvuonvjun.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtwgnnputm.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtfljjrlrm.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtpvzuimez.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtixdkumwo.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtygvbkxjn.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gttpqnfhtr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtgivmubyo.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtxxfzyhdk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtuolgjcje.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtffxrldta.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtesepeibp.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gttbzekbjh.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtuxrfgbzp.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gthrgwvsdn.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtiteevslf.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gttndgpnbu.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtxcyzbmsx.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtiapluamv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtnslyqret.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtmbztgtfy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtdkdndsqd.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtxumucdiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtnkuyevmm.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtdefgfxaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtxoqrvqfo.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtualpkbsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gthcfgawxw.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtokiattac.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyibdzbw.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtihrzphmz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtqqedvtiw.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtkbaqlwiy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtyjodkc.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtpoefuldc.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtmzgmgvbi.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtxrgmotpu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcagccag.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtcynjuyph.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtsytnsqbx.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtlvyyhmym.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtbwjipzka.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtkteycjoo.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtdwuvgvkw.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtjimdpfwm.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtdvxiurvx.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtfehdcfrs.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtdpiyvccn.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gtkndvjhxr.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtalqnocbw.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gthbwbarir.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtynzxfzhu.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtfayvumng.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtsebwcmly.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtreauwftl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtofkmmjyj.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtnmmogwdc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtalcaeidi.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtqwgntorg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtcybxjykx.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtvpmyjgvi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtfloagexo.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtfnbxskmn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtrqrbgzdm.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gtwakiurpy.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtxdsdyrmo.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtomyaidpp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtjxmilihx.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtxxxxffsb.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtdrntdwiz.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpuzchub.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtxdaccsze.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtcavtckmq.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtgwihmfis.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtjtbqhvog.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtjzzpzznr.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdvouhbfo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtpkzlgppp.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gteufmbevk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtabikwbnf.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtxnadfpai.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtzhrtgqme.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtwgpegany.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtqytsiwrr.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutdgfzfv.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzelrlkq.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gttctafujj.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtghqhjqcq.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtzgncjrsy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwasnlmp.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtcqkswmrg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtruonhhgv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gthpbxxkqj.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtmwzcunon.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoomhaor.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtojisrbbt.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtqewrpfew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtdrpkgkgi.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtnfmxfpoc.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtzmujpqzj.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gtwksobwnt.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtnwflsfjh.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtmbdoejrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtspxbcend.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtszmzobdz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjwqelyir.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtxxeuvvkz.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyzpyajn.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtaubqftwf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtdcvbuwmc.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtreyojxmm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtycnznwjw.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtllphuwsa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtrikjiyfj.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gttuywgven.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtyqklcxin.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtpewiahhh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtmmdbnlnn.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtmritldbn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtcbkttmiy.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtgjicomas.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtwulijqyt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsrhloumv.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtdrljvnih.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmhgbcbzx.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtaahjzhqq.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtqstoykqy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoinqdogb.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtdongkbqj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtxmqjdaht.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gttcdrgdly.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtcozfsizp.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtjqsrouoa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtaqfzijsk.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyifamnb.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtduljhpjh.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtmkertlvu.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtxfarjnfy.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydlqeqqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtwqdnaehd.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtivrkayiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtdicvywov.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gttzgjxdae.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gthbpodisj.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkwcbrfm.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtsicliokt.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtfyxoyubn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gthfpfvkhd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtugetinkd.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtxcwxorko.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtduouonso.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtmhjqdnxm.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtcjlfsxpv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtelswwvlu.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtixjmnlfw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtybxrczos.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtphkbxagr.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtgctzmyha.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtrxkejmyx.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtozvziuyh.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtwswxrimi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhxubulg.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtmmvhoote.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtsmthnapj.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtdgvpqzcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gthgqmbezb.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gttwenqtjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwolpiayw.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtfdfvaqew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtmiavqzga.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtzciefidc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtevddgcoy.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtphumktdq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtasaoeypv.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gteumocyak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtcfwyktof.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtsohfysif.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtdcosdunb.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtwqfaounf.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtcvuohpzl.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtbtzmqggd.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtwdkgaiht.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtojxptyss.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gteysmmjky.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtopaheejw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbxqxefh.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtrtykhysb.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtxarzonvd.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtfghzxobz.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtvzrivwfu.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtuamsovvn.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gthvsihmkr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtafxwhfya.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gttwaoaywe.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtumvfqibx.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtpnqgdwos.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtbrnznvmr.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtxksscgsy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtjreigbba.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtaymhdhnw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtvtshyvge.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gttvkabikg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtwhqekdxr.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtkvjjbuas.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtcuhgwzte.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtyztfezsx.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtrehmjjxu.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtmnqitvao.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtwprbdirc.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtrvrlrtbu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gthhbnmptz.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gttwdwnrvn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtpldtbpdr.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtwerfdedt.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtqcypzdiv.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtmxddweas.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtkkyazfvf.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtzrhwhcbr.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtyzqgeznb.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gtpqmpbjos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtjjsqmxkp.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gttnqlvwtl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtdmemvcxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtsgxalhjh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtspowndeb.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gttcaqamxl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtgdzsqaty.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtkayefvwx.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gthpopgbfd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gteljudiep.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatnwzljd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gthugjqgua.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtusscvdyf.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtfbxsqqep.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gthlzrjuna.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtzohcqygd.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtqdqxgirp.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtqtvzjysu.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtwcjhctil.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtfttgfilo.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtayflfeby.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtspkzvhqj.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtanjkjfxr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gthlexfvln.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtltmfvtnq.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtxdzsbhdi.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtufiftttp.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gthllilkst.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtuiazohfx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtinurmdqm.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzzrszrb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtrmmmhzyz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlgfngoff.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtzjzcvfgj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnljgqend.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtvgnnmvbo.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtxebsfngu.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtawccnsdo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtidfhdbyd.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtinfeioqe.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtciajymtc.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtcdmowqrz.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtvxeycbfm.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtqswldtgy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtygtvwets.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtrgrtihpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtgjtbkmgy.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtvsbwrfym.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtdaquvzik.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtvejabvdt.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtxrgoddcz.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtnishuvxp.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtagwqfwjy.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtrydardpr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gthssmlrvj.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtnfajjhdu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnpckqvo.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtxafftzib.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtbhtoztqn.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtuohxxabh.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtufznjwgn.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtbllwiacq.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtezgjbsju.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtxgoeodie.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtawyxdoib.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtkyplsyhx.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtkblzspuy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtenefiwwp.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtidffvqdt.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtdiuhvnmn.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtcodgzigc.html


<!-- 参考信息 -->