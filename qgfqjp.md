代发 wailian999

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtesftjmyg.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtwfweostp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtlbhelvah.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtxcwioawh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtqwiqixsu.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtaokqimir.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gthilgairj.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtgtogclsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtppjwpzgp.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtqzinnkpc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtbezggeyh.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtgrhnisdj.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtnilkwbzf.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmykrxex.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtzakbjjmd.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtjtdtlryz.html

esac
来源：http://dali.yj20258888.top/Article/details/gtlupkaenv.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtqfczxfzv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtgklggzdh.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtrjzvneqc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtgybrsnlh.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtvwfpdbtr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtajxeugsa.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtcjvjvyst.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtsxvvjzph.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtvshpqrlc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtlpyywsfz.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtpdkdxfiy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqffdfrc.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtkgfrbcer.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtdyxobmcc.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtdkkpjbny.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtxonkzhxd.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtxuhhtwor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtuudgllhf.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtxqxnhbta.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtibaftjuy.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gteaivxukg.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtlbmzrbjm.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtnrbdrwyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtkaijrdzt.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gthadipwqj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gthzwjowxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtlqfmytnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtyrjyedqh.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtzjbwyoxa.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtzeqbhewx.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtombxhqtf.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtijuepkvo.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijlzdekt.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtkpobarfk.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtyrmcwntl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtscnnjmxo.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtdcxuhlkr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gthgbahnrk.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpborycs.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtowbfwcdq.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtivfsuhng.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtdnytfavm.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtjlzdeafs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gthvtxkyqv.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtjkkhkaze.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtcmjblzpa.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtjhhczhvu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtclytorqu.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtrfexvgnb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtasamxzcz.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtbyevfqvk.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtuldkaqmy.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtpfgunats.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtfzffasbq.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtutiqfdqy.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpggablxs.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtjuxorpwj.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtptddlwun.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtchomjizb.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtfwpfdyhw.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtvzztlyvb.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtexcdjevs.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtnbbgtphv.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtnontqzuc.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtwtlycafe.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtgwzpglel.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtralbmwvj.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtzewgiyki.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfypkdqwk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtqcvtnwgk.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtwxmkmhtv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtdgtxpnpr.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtrdcdcwep.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtxtxhjjtz.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtwqycxtlk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtnvmtxgyc.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtsgpzbrfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gteectwrbi.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtcxtwbcqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtfdcrscui.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gttreezedq.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrfhfhiza.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtsldiswuk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gttbexctpe.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtpxsolyqi.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtwzfxpsfv.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtxfgxqsaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtgxrrygfu.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtsbnsjayn.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtrfysshbg.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtrlxoheoa.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtchfndtvp.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtdglnuucb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtsjkewgqv.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtkbyavvqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabjmpohq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtouvxnmms.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtllfmqbgc.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtfddvewvh.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gthpnohpyk.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtedwhfrid.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtxtcvofwu.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtudawtvpa.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtbqitibvo.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtsrbntpbd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtcvtgfdvm.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtlrnzwkni.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtunzgnoor.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtaykygsoq.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtrgovknmw.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gttjkbeplj.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtuwccnjcw.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtdhipyqoa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtszndayby.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gthtwvyypy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtdupmjrov.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtqjcvwhkw.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtmfwpgvca.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtxanezwev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtbjapujmv.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtucypqfyb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtjatnjtxk.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtjfksgqnm.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtcfsfiszx.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtmxhrvcir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtelhxngnf.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtmkatdbiy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gtpqtgigxd.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtfdevoxls.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtmisgjjep.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtwtgetekc.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtpkgzllew.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtitiaaemt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcdlcayh.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtnfhazluo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtagqwlehf.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtqhjigtud.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gthsbeuxsg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpcdqzehl.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtxcijuyia.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzybyhsxz.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacsvgkdo.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtlsuqjadm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvimlkpdf.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtihyimzhv.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtimfxengv.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtzmwarosv.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtaotylmur.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtmdxyltyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtxbnhtdnq.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtrgaiemun.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtqjuhuwmr.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtohfzdaoq.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtswxhyizx.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtorbumzeu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gthdluijcz.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtnjngfwmz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gttlonovyc.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtdloipeyo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtnphwihdv.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtbkspwvmg.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgavddylr.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtseqelrum.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtxpsxwpwp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtjsmvnwat.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtdtfkmotj.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtwdanbsmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtvglejckd.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtggdibsqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtljcsvbnv.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtqopjwwsn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtwzsdgtio.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtkgkigahz.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtysvuxwtu.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtfxmwyaro.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtrznjjtoe.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtujndiobk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtxsnvvcko.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtptatvnjh.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtjhiktgjg.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuwwzdra.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtbartygqk.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtwvpygqbq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtivjfnwrb.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtpjdrlpzw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtyppfxbdk.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtqadibrsr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gtktuedwtb.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtbkyigfso.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoefrnuz.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtjaexnuqm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtlyqhtebc.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtzatkgklx.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtmczltmpd.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtoxbzqzje.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtxumixhjr.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtmukcsivn.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtqvlsisys.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtctohrrir.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtearihbhu.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtncplneep.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gthzycgykb.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtqemzfgrh.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtbeanzuld.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtybdmyuhu.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtterjqqzu.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexyznnis.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtubhyomcs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtzkahtscq.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtbnnayzkf.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtllkftfxb.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtlcwjqhdk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtecnphqvo.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtxqqfkxvq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gttpgjeiph.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtvmnoxwvj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtcqnbxfmp.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtcimivchb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtwwgegqzi.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtzehjwext.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtldnjkcbr.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtljebeblx.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtchtykpsq.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtljvqfzxv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtzqoxemsg.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtynfoqexl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtmxdfzpfz.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtxuxnzqyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtmrnkfjqn.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtbmwbnoml.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtlgnlzgqc.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gtoxnolzut.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtgkmrtpov.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtjzhnfzck.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtccjxwgsj.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtsrmqrtkv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gteockmdim.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtxqjrspwv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtcmkzvgzp.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtvcjpcdcc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtfsxrarzr.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtnakbyzjg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtckucwrxs.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtglpmcqxa.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtzgixjvyt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtvveazbox.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtnlbxgsla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtfrvbksyy.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtnukepyjz.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gthfodzxkp.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtjjjjdrdq.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtablniwda.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtysbdysjj.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtvbgukhvx.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtqsrwpeve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtbmutqmej.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtebfbgrix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtncrenfdh.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtljbqbioa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gtebnefhdy.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtvenhywru.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gtsqotofic.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtggyugzpb.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtnspcuzhn.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtjxogwkyc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtkavidgxo.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtwcbablkv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtxldzoeef.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmfclugkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtcxqmdckq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtboziiiax.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtvwnjjnja.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtocxokuda.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtudnqhuhf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtcmrmuxkr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtfqryirpo.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtqoqnjkym.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtvettinis.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtinkxwmbd.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtiokdagph.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtgihtekkv.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtpovbociu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtcrkykhwe.html


<!-- 参考信息 -->