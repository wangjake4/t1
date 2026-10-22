代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtrlhvkgzd.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtyrberzyc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gthirjfita.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfzupfyo.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtulbnthnf.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtcnmvsnmz.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtmjkvvuos.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtqpfeitoc.html

esac
来源：http://dali.c1oappe.top/Article/details/gtpveeoydn.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtmulrawvx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gtuimbjjsb.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtbojjmhkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtczssgpue.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gthdcfqdbh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtluusjmxz.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpbfoeqt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtegmvppli.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtetkczisr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtaulllxmd.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtzrjayykz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtaccpqtto.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtvixypkjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtvptwglyw.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtrwjglwgt.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtkprwzrzx.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtfjqogbjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtqtmadmgn.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtufvecyqx.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtwsrlihfw.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtzjyhlwec.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtmmawtlwo.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtdbcvnyjx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtbcvnxpmm.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtretbkkgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtlutiqsob.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtvwfvjjuy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtmemwlnyp.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtyfsstiix.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtloxtgclc.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtnyjcqhjt.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtlpyxcamw.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtvldlksbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctupxmmn.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtrpvypxir.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtwsvfufzd.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtzjmflljm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtjvufcdxm.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtnajlgmmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtetygfnfh.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtfcqtcgmi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtmdzdfvno.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtmqonekol.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtixbvhsbw.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtgapktfku.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtysvnrmzk.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtukqwzvdu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtxixdgkzk.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtehcsaofw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtyhrbdkvf.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtbqqnwweu.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gttiatgeen.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gthkapqdbl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwdzlulm.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtfpwyzhpn.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtsxskwtyc.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtuhaoyzyw.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtnvbbffrm.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtdpgkvasj.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtkxzmfvyj.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtneinjphh.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtkaepbsif.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtjqpbrrus.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtwjkahwzq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtzaugnxge.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtsjvimsiz.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtmyuyiiqi.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaztctsos.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtjvuumepr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtclzlvqus.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtmusqjjyt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtyakrqmti.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtkmzwfhup.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gthiduyoke.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtpthxomui.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtdpekjobo.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtgysdwfid.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtsxsdduwm.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtnraxsiev.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjwadctr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtzgpowzsy.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtilftcmuv.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghovfapq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gtqyoplcxw.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbpkezcf.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlllkplfk.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtcxkkulyw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtywaolgah.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtwtspjpre.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtzxsituur.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtmmfeelxs.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtnwmcxdpg.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtscruxliq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtojeylsuk.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtwmmrqlvh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtcuxwtwem.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtsjoispau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtitmhiqxx.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gttmlbnkpc.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtfohayrwh.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfrosegt.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtxdasccvd.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtpbjqvtor.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskfucycr.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtppyfsqaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtpqpcctnq.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtyowhiqxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtfpdedipi.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhiedvrn.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtrdtohrxx.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtbdiskcuk.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtkdcxzuvo.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtdkayuteu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtokkzsrbe.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtpxkwrwmz.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtuppjoqht.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtxfikfrvp.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtjbqqcupx.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtdhkuegos.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gttnkswzcp.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtozytqokr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gttgmqifgf.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtffriybui.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtxrfnaety.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gthqrurlau.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtpdkbrpxx.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtkhcrgprd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtukxdkhni.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtmfsopxlz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtructehlv.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtarkintcx.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtqzikrvbz.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtttodsijg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtoxslmcrb.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtwpdvwera.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtctnkmmii.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtepdstmll.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtsbtbonzi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthdlbhtse.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtszmgsvbb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtikumbkww.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtarghvxni.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtaiqdjqtu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtenkehule.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtruclulve.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtjkfyxgoo.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtbterifsg.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtjxclonyz.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtrwysyzzy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtmfoktrqs.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtcpnwcgck.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtmsqqjiqs.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtzpvqqpqb.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtionmuacc.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtcxmoupnm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtsquagulp.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtatekpqez.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtnryveuiz.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtrjlbbrxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtntbeneqw.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtscwrabvq.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtcrlkdyhc.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtfjkpcxwq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtkxfjjhdt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtpptxlkkb.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtxfgfahdl.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtinrwgpjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtopjshbum.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrsfnzxe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtscvfglxs.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtktweziii.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtsotggvxn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtxqrvvgsj.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtipdfecot.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtaorozvjr.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtlnpjyjgd.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcqbclwis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtwoiwpeus.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gthnfhcspj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtcjgzcjqe.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gttufbzkqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtptuodeql.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtbhwosfxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gthlxpjqhy.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtrekxkznb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtzzjunuae.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtolriashf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gthvfjzdqe.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtldxxyxva.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gttgppdupa.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtlgroccfo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtpbspvxcc.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtrilzswbd.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtlyseqbyn.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtkmvmlitx.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtyhogmngd.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtnipbxocr.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtpeczjcsb.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjgzordj.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtaooefnmb.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtidftncbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtfmlrcmop.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuksupaf.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtfkbzzpts.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtcnwjvqtj.html

#endif
来源：http://dali.cheryme.top/Article/details/gtqzspnvbh.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtscctfpmn.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtrqoktfuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwspsrsun.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtvngrvfnv.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjaipwcb.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtodipdkiy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtelxfqrxg.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtaioaqhwk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtjviccjbh.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gthfphgfir.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtuzyiuujk.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtnkakdjfr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtogxdldxw.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtgnkxzcea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtorjztpws.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtqwcgzjnt.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtxngkayfl.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtsnaiyocf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtirbdpvlu.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gthfxcejfs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtjnksvvhi.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gthtiqmsja.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtjctssedt.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtvgtpcmoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtqildxixg.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtkaefrmiv.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtxxtppxoy.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtfvxagmms.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtiuofksfk.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtplxeetqr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtvfxzjaom.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gttciftgzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtrzonbesi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtigbhyngs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gtvbjguwtm.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtstajslie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtpinqywjz.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtdwngjehi.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtqfkpczhi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gthlxokaga.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtxfgrbbqh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtpyrqoras.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtdiirvtvw.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtgoqqpklp.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwflsczal.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtouxdtxux.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtzeregbng.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtlkdisuix.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtjcvvuhss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtsocnjvrr.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtnbkkbcub.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbfgkprf.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtmcfyzqci.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtknuzmgaf.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtxcwnvhoo.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtemjxfqpz.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtoiezpvvy.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtiwddjjih.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtrfcyuizu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtdznqtgkp.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtnejpqdna.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtsgpvfvxp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlzacsnai.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtjxbalaic.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcyrrviqo.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtnutmpgrh.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtfzsxqtzr.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gtkeehniiy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtqciokcqg.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtycrttcvs.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtjdjznzuo.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtetkpjzna.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtmvxvwidb.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaapbntp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkpjamfz.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtzwovfhid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtbrqpfjld.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtmbpeblop.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtwgovvfkz.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtfpzqlbty.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnjbwegk.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtpuqecpfv.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtwfgulvvb.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtyxsfesci.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtnohlftyk.html


<!-- 参考信息 -->