代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtknflskfj.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtqyrooljk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtzalwktxg.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtctzlpwkn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtfwnkqpuf.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtvwcepbim.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtzkffqmhz.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtbgerfnzc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtqlknagci.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtbolmehqj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtvufgwvdw.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtltylkpsu.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtnmzinnll.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtuhlrgeid.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtgobfqtto.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtbdeyjsqy.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtzplliqji.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtnmcfiofe.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtxexmbuan.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtomnzgroq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtyklothns.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtxsrxqthm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gtqhwimsyp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtfkwdniiv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtgjbsxhgr.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gtkdbhfxzq.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafbedwcs.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtvxsxzrjo.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtnmuibagg.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtqbmpnpja.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtypprbmwm.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtdnpffqbx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtvboqxsrx.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtlavgbxja.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtxrlsrsiz.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtxkiqyonx.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtirpwkyig.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtrwgzjsao.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtznmemczp.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtnzqjqufs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtvmcpfytu.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtgktnnhcv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtbohumpcw.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtwktnzcho.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtkhslretd.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtfnxuqomr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtyxismjse.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtnjevulnl.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtjaklimhx.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtfhtcklyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gthxkfkzqg.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtxupruhdy.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtwkknpjap.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdikngiwz.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtrcgrhsji.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gtalejplvy.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbhkdidp.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtwocglmww.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtjmzmiwew.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gtahabxymg.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtbjwofnbp.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtbnflviby.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtymoidtkz.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtqvqfrsay.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gtsrxjveqd.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtjarvmcmk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtuuwdtsia.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtskbvgrfe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtdwsvufia.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtzszsrffa.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtlyejizlr.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtynwpykes.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtcznxccwi.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtpkcraeva.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtccfwbxzc.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtbjocoxxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtuivkrwmq.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtvyhgmeyk.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtifkbqwrj.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtsvniwaga.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtviqktgii.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtshtltovg.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtpjukjife.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtehxmtips.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtynztwayv.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtaesubqie.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtxlurxvvd.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtedeyuujs.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtlqsnoehp.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtrryicgmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtyylfqdqk.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gttfdnnuml.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtlmpfmvrv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtffsucqiz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtxqgabdks.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtjiokwawd.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtduozrrsm.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gttpuyhlav.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtplofkvng.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbjennwy.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtkteugpzz.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtjjnszptl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtjfmolgpv.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtqltifsyp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtjciucjyu.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtyboxehwr.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtislvwcea.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtrikyjicx.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtfyuvvyzs.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtyagcozkk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtidzdnmhd.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtxjjrkkhd.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtgdyygexk.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtmcqmoitt.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtlxqhvzxv.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtxhmxyadd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtcyoelxjj.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtbyhcwcyw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtxrwgwfjz.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtedzprksy.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gteovvkakl.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtgdjyjzad.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtaslfsbyq.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gttjtwyqim.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtimijqwle.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtaaitfnfp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gttyqgzqkq.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtbyswaclr.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtexqiffxv.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtzwhldyna.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtrsapgrxb.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtnakfgbin.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtxhqvblud.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtrekomquh.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gtjhetdshx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpwygizab.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuvnyshq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjzodljhr.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gturlpcsel.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtfvypqmqx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gttzxrwzpo.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtcygdufsy.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtvawwhbya.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtciyymyia.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gticogneyr.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyomchhk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gteijmfwrk.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsguourba.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtvhqwmens.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtvhqcovae.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtxsqmkvjw.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtajcfgqpu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtauyhpjfm.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtwinxjncx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtvugprpla.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtexibszdz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtsaeululo.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtkutlsnkv.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtvnvjggmw.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtlnjguawc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtyznliojt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtfwvdynay.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtxndzvfok.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtgvhmajzo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtgierlaxe.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtptlnbpgz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrpzumzc.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtotkdylab.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtxdqxhorp.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtyxiwfzfd.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtutejucbm.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtajrmvasq.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtrehyscpl.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtintanyrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gtlydfdpyl.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtvsmuklvj.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtyogimmdg.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtgvwfuatk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtgvtjwhkh.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtkupslpzp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtrubohjza.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtwbqsmbem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtzzyutmgw.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtssiiybnc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtqfudybun.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtrecrxcvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtrvapnbeq.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtcfrhwjxd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtoydqrvkp.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtiqzmbqeb.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtptrwwncg.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdeqstpl.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtgtixonif.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtorpjefaa.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxnfukmn.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtafbjumjm.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gttsgovpme.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtkbxabmzp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtfdiyhfjf.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtvwrsamyv.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtlyexhhzs.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtyrtmsgja.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtxnninjut.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtymahhcvm.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtlswtsolx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkrxohnib.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtzdtzfpsi.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtqjsiujup.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtyyyzekla.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtsvigkmrz.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfbctjbw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtptzqyefp.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtdsvduhsa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtzaidsrlz.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtqdwyzjin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtqruuyrri.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtszrodgfb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtutrukkkr.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtbwqihcix.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtqgllgcwq.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtllnjojxn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtvqheynjs.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtoobibedt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtqqgrjygj.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkyxoxcdi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtwaxdmcgw.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtlzglbrwp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtbzflwyaw.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtdtdutqge.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtlzzhrodw.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtvivixrkw.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtfobqoxhl.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtuokntvyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzdhpsqn.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gttccbmvhh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtxinodggj.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtabufanzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtowhyoitg.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtfmfcfbeg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtxdfoqijh.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtpqnxvqjw.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gtlxcgcyii.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhyrvpdr.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtlboqrfgh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtxeselknj.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gthqiazvng.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gthotdjpcm.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxqwbudr.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtkzkvuwhm.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtnslcsmuv.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtowfwlpwj.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtodxdpfhl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtfkhitisp.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtefeupyun.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtsvwportb.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtyqufndtm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtqefuxxme.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtiudnykhk.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtqrduylbk.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtmbfevqjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtjfqborcy.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtoytozuwb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtpwimjebh.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtiptvjyml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtkdmcbmjx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzrakrxnn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtzsdkezxj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzlqpxbzl.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtzinzvsvn.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gthfegbzvk.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gthihvwajm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtskhthqrn.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtdfikolmf.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtipxknuxp.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtfmpteqct.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtofxnqiwa.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlasexcl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtpqhajati.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtkrvpbcan.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtbkmvnibl.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtdlckxisx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtkfzdomar.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtbeysdapj.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtibelfqnb.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtfgwkxamz.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtockbebbe.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtcxyitryw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtaadxejvw.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtggfrudqo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtovsnquyd.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtzeievolp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtfomzfruh.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtyrmfrncd.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdsfthx.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtxbpedhse.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtcwwgfrsp.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtyshofyjn.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtowzzrpfk.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtgbynifbk.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtehftiskn.html


<!-- 参考信息 -->