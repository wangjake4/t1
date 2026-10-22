代发 wailian999

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtbcmqrmar.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzfyujkfv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvfsilaa.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtoyesddmx.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtiinesggs.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtspsgehbb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtbyyofmrk.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtlcnbqfqz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtuxbkfysl.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtczrgjmgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtffrqgzrf.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtduyqqrwl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtcshcuvpy.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtjfpqrkhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtjfalgwnu.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtoiflyzlp.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtxqmewdbw.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtyutgsvai.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gthxjflwap.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtrfwljhcq.html

esac
来源：http://dali.fzhhl.top/Article/details/gtwxqsfgfx.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbqxrozps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijeiunoj.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtjkxkwfyv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtzaouwjln.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmucmqyip.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtosknaccb.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwfddmfvd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtblgdzima.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtzddtzzqq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtxhddazif.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxylrti.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtkhfjojpt.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtabxpfkyg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtaxfuscrd.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtcptmnhqb.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtoqbklohq.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtdtecsatb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtggvwbadu.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbwzylrc.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtkxtmqali.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtvavppgqi.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtnazbljwt.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtveabmkuw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtzlhkcsqx.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtekalhkbp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gttreibhxn.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtvjkfwxus.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtrvksfzlg.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gthinxjdqy.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtsulnjman.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnllnwdw.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtltrttyia.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtrgfgslmr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtvimflilw.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtlknpqcyo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtjvmhczrl.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtmeyvzppg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtkftbgwvx.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtkvserizb.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtgnclbxxh.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtocvxeeal.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtlubdmsey.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtdgszoteq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gttlbltomy.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gtsksphndn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtbskrshka.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtbkczquhd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtaqnnjyfa.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtyricllmw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gthrctgppw.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtlrpcrkkh.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtaivtiyyt.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtckdlaohv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtfuaimzdr.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtppqkxqwh.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklwqrgcd.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtojrepgwm.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtqeldgwcy.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqqgmayq.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gthbkrejaa.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtufpxgnlx.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtzabcrsgw.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyusntuxa.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gtrqmnqrgb.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtoflpdbjb.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtwkpjomol.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtsxbvcdik.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtdoquljih.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtokhhezfo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtorpmwtlw.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gttqcejwns.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtieesrwvy.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtxvrfnywh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtffnuvnkk.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtrsyabxfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtsgdhqtff.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtgkduolge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtiaohgdvs.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtfbeklvyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gteoiuxxyi.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtgsjbwvav.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtubpiurbb.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtlmfgtipy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtevwktkfm.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtrachlxws.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknnjwujd.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtopfmdtjv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtcbwtbsey.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtpehuudqt.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtcxnodyiy.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gthuszjopb.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtgtinmzib.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gtmxugchzn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtpqahtzmx.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtjwrecdqs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqlawwix.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtbutczuug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtelplplaj.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtlafrbrne.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtwfcqxecd.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtljvjtohb.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtapjssdcx.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtngkbjtnw.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtkvpifpbp.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtdcutyvbk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtypjkpqdd.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtxxhvlwku.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtoyfyblbr.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtrsagojib.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtkcixnugi.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtqlmiwlym.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtbkioecso.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtlldwqcfa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtnimuawog.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqshojvkh.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gttjjamprn.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtsnvthvtz.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gthtjtbpsb.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gttojzzgct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtgpkkfmtm.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtqodcibaa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtubmeiaij.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtftarkizy.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtsgazvoyu.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtlgvllqho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtjpomctov.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gtdecvzmly.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtasuiiixj.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtidowwuvq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtvxkjwwwg.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtyygdkghk.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtnapmzzwz.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtifrlhlgj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtsdfyfhyd.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwigthkf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtsoqbtyqt.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtxpvztnbj.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtbwopmmnx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgbvleskk.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtrhxtmvmd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcbqmnlev.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtkinzwgog.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtkraifrhh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtyxlfbggg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtcfyyhehy.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtkqxkzhri.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtskjonjze.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtdogbpvwl.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtbkmdsjvn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtskfblerr.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gtyouyxfvo.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtakjdkvkp.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtjfgybvun.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtyofdzmjt.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gteslkohrn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsermssjz.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtsisfetlg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtfkqkiuvq.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtbscrqdct.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtmobnfhzi.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtxmjlxnfe.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtvllnipjg.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtqzkzslyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gthwrbnsme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gthywfmgua.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtjauhjych.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtjpccnuxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtdyxnxbza.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gthjkycsaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtoprpafpz.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtlszkycpm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtrpeiysvy.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtoudmrfan.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtqdxssqnh.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gthzjlqczh.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtcbtxuqyc.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtfwaxlcto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtyzyugmae.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtsnelodlz.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtgnhuddnd.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtdnwszqrn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtfvmqoxvv.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtfubahzsx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtkkhxjqlq.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtnbypyrza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtypkawhnf.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtytahvagc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkrcdvuh.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtqtfjxyeo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtduiqbsam.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtramsbalw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtiyfvkgbd.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtpzpjhrbd.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtfavrtoso.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtkqdlrydx.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtdpwptbky.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtaiaxprei.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtdipihxoc.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtnbyhzynr.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtmdskxvbl.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtcdthjlmk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtyhrcymvj.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtbfdxmuqv.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtfkucugbr.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtafilaowz.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtbtyulkfv.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtnqvayhac.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtobnzwogf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtpmydflfw.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtsheczbws.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltdiugua.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtiworcmnu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtesseegrq.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtfhbmovbz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtqbmuwaik.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtjwkqzkqy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtsfenkjed.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtzohjvoiz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gthmixfyid.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtchkjzpdf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtgeszlvek.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtpliyjcgm.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtcjycvtxq.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtbwfitjne.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtwfpqbtfy.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtxrkbojfy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtcscfbmel.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtmfvdpsdi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtvpwekqoe.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtiofnfpxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gttrpkclju.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtdhvfwkuj.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtdtdypyvh.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtnrbihovp.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtvddddddk.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtolruchgk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtwtewuefr.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gteuwoexiw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpcczpbas.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtsvuiokor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtaqwgqrce.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtpgvmlqcv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtsyfrwdbw.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gthdxrqkgh.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtxjuluaei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtddmfjyxn.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gttbcclwmp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtztlbkisv.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtuvzsyazy.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtkuwvopdg.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtsugowsmj.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtzxntumiz.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtvqfnzgcq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtbgxkoqou.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtnvmzxeqn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtexbdqvqw.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtocnuebbh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfraatsos.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtogmuaipv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslnwcehn.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtaoluuhxh.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtfyzguqjl.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtqxvqdkua.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtpvtizvxa.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhmfcmct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gteojeltnn.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtyddeyiwv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gthkilmflc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtobusngcb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtodlsixgw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdveogtwr.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtsushklzc.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtzlmeivah.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtffnvntuk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtyikinptu.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtowfhlrzv.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtrsiwhppe.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtvdcfthdn.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtxrgzfifw.html


<!-- 参考信息 -->