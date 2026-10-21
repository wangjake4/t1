代发 wailian999

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtuxgdloin.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtyfognrzz.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtkfowjiai.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtetaopold.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtxiapykan.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckniuddj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtozdosysc.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmbnocsk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtazhthxip.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtzyxukukt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtnvgzoqoo.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtbvqinhnl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtiyhvxjqr.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtajtebycd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtuhirdyle.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtaalghpag.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtyotufxre.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gteqitxdlp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtcfeextjo.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtghulocsa.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtuwiqldhp.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtvkznbajc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gtvpmamnsh.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlmfojgz.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtsurdhyaa.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnegxulc.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtufhhaben.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtnliikmtf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtqwbadxpv.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtwsogammi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtljudddlu.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtaffdwark.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtqgqrqggx.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtemzxenvk.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gtszihisgj.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtospdffro.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtvkxjdbcf.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtyqlwwuux.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gthkauzybh.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtutkxbltw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gtwswvslfi.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtauofwdox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtlmmaoasa.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtajxcukok.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtomccqhug.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtuvkhscls.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtuvojgxke.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtstqkdgcv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtdafprqyk.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtkkbwczzo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtruokzdhi.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtbgyklfmn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtgdxhnwvg.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gtqyhiolty.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtxxxkpzpg.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gttrhqjghc.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtfajtxusy.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtfnuxitpl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gtbbjzipez.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtfuuezscy.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtqbfmujvb.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtfqtynaps.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtaubijguo.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtdawtudvl.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtckxbfpyt.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtmahczwfm.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gtltpatqks.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gttwjjbrlx.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtlsyaktnz.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtrhokptoy.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtrkjshovr.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtidnxofmb.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcawolck.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtlpsngyal.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gticmiprdu.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtrsorrrao.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtvegofwtz.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtjcxzvyiy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtgxrhmtdb.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtiozrdzgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtpcbubhdx.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtargppkky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtihecqogn.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtwxnesnas.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtfhmwtpxv.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtptixkike.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtksaljrbp.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gttjdpucdn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtfejfjnwg.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gtbcavtllx.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtqdikwzqx.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtxkosfdff.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtzvgvexfc.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gttuxixxww.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtvwembtpl.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtvqpvuaud.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gttwmfxyld.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtvafxvffh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gttmhvsqyo.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtiwjkklrj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtnwzbivct.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtbsxbmpcw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtknnauwev.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtequfyscl.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtyxukurcz.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtzzdbzfkg.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtpqpsyfok.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtrkesyett.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtcouvvvfa.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtnmeiyenc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtkbddsnkr.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtcvpbkawj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtwqtvcmom.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeukrbgg.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtzoisqxbk.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtbrfxzdis.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtkxglbtst.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnrniuvw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtjixzqemo.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtvyqziqza.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gteojsfqvf.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gtmrxtizup.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtzwehneeh.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtswxfannm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtfyxaumwm.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtbyffahnz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtsuiduslu.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtxlyrxorx.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkehutddi.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtihrhwjad.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtnkakbyqi.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtcnqfvwlt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtzvklimem.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtwehmuudf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtblhnmqqi.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtcadoirer.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtjxwpomzh.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtasmxtiji.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtdhnwjvyn.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtizjcaitl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtbzxoifwf.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtupmnmeef.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gttzepphrw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbbtjjzu.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtiyossgvb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtefkbnyyl.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtyybipxqh.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gthnyxwdxs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gteqqteaqx.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtafpdikkh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtydwjejpo.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhqpiwot.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtlhcllvig.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtffgjsmnj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtzwnmsxpy.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtjfbvdcpu.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfcoieyhn.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtzwfvqxch.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtrbwvtqie.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtkzfesuhx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvibbduj.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtnnafnhoe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtwdjibahj.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gteclssuod.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtppazcovt.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtnrohfixh.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkqsqitz.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxfznuqfv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtjwbcvzgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtrvijfhsb.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtczcpopws.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiljrcgjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtajfrtvfq.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtbbakpkyi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtbjolvyfm.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtjgtqxhjk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtiqzbdibo.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtadojibpz.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtincffhrn.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtycycpfyq.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtfgrrvqtd.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gteanrdrzi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtfpuzpbbp.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtfpvohndt.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtmugxbisw.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtxymynhov.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtexveloun.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtiusnxvgm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtojfbcwyi.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtaflouqiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtbxpsuqax.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtiqxygwml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqdcyrst.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtuasykmzw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gteykvdfql.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gtpsvnpxza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtuxscjxif.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtnyklmrsb.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtliqtelwp.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtkicokxyn.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtdmtdgtgc.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gticrphftm.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtgpfirtgm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gttvhxuqzi.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtssnoecvf.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtmtblqixt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtxrsptqjj.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtryqatulh.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtufqhcfns.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtogqejdej.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gtwlthbesa.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtgbqftrxc.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtjlzflblz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgyfnmflb.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtxsvzyklc.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtlptidcfu.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtlhtcpuuo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtjybscqjp.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtdrebdwzb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtmvocxwiy.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtuwdnycto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtptihkyil.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtrpradzai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtoikebinc.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtdkiryatr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtjfewyhyc.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtaomivmxv.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtetdolvju.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtpztararj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtozltawge.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtofoqxuar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtlbudhffy.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtzafpjbre.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtoftmasld.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtvnipwgkm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gttkiqssgg.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtpyuoxzkx.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtbfowqjtn.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtqjvknved.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtamptvmov.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtdznhjttz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtecajnhak.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtkkyuzbod.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtdjveyzpe.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtubslewlr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gtxidoubjo.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtfsfztwgm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruyrvmjy.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gthqfvlzzl.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtpflkjdbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtwspsdeax.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtibdftcxi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoayrqjx.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtlkcwnark.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklbwrrkq.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtpdkfglye.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtohanjyao.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtdiqdsnya.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtkglplriw.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtcgarrxup.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtfacanocc.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtjchbnsph.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtknllrhvc.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtikbrqase.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtmdzmhslj.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtybtkcklm.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtmklzupxx.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtkbqxjsuv.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtpajofeeb.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtkwoxrvas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtxwawarpj.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtjmsahswq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtlnjipggw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxorditf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtfdcrwppz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrvzbibjk.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtbkagusfj.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfubqhypb.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtizuxrkxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtnfkavusv.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtrfflfaai.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtscuqdhgj.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtdfcltkmf.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtxagbckjl.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gttmkvzgzj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtkznjuyod.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtvzbkhcpq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtetlswfsk.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtbhesdrqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtenjiqgyh.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gthywvtyck.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtkftnwxuj.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtwldabylw.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtulimvnmx.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtmmyyymqe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gticigxpwk.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtzqzljqfh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtnzcpxxlo.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtfbdstbpt.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtcyoaqenr.html


<!-- 参考信息 -->