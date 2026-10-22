代发 wailian999

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gt2nivoetpd.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2rjljvmin.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2aodplxtw.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gt2asrwmpzu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gt2sgpulkjp.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2lghylvwr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2jrjuupff.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2ykssczqd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2obiixwms.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2txtaqiuf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2tzcbjuez.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2wxiatlof.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2rssdumcy.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzkmvcvf.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2sqteojvu.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2dycvksjd.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdlbybbd.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gt2mrhatmgo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2pqovsxkf.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gt2qmqncoeg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2otvurejm.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2xekmesvn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2ocgutznj.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqiddkjh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2efvlenci.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2ttnanbaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2rkcelplv.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2qwbotqpd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojxpfqvb.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqtlvxal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2lfktrimj.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2cihegfdc.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdfranab.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gt2gyyylshp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2horfgepl.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2vksjoysx.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2gsllqybh.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2cmrcqwkc.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2ojxeillq.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2kbclvcjk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gt2xejirwjt.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2exdrzygz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2vlljxjgm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqjsyaub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2gaehzekh.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2ypyzfjxf.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2uezczbzf.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gt2nqjzjhwe.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuswspgb.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gt2foarmqdi.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gt2fffwgevh.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2ukqwrvjt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2rucbsock.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gt2oclxztrh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gt2ppmccngq.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gt2axskyomq.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gt2okbnukzp.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gt2limfkjjx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwtocdro.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gt2mkkdgvxj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2vakfxtim.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2eddshwce.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2vjbrgqzu.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gt2gpcldsez.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gt2dcfsfvwm.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gt2fnfeblwo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gt2aymnagbf.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbkbvswg.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqcdbllk.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2yerqfmbw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2jmjnpvhx.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gt2ovjjdhoc.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjmqhxto.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gt2qemuuyhd.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gt2lizlhbll.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2ufttqkhc.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gt2glbmxahi.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gt2rkqzadgq.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2fqgclhba.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gt2aazeejsc.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2rhtflgae.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2ahhdsqgj.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2nkwfjlcc.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gt2hjufisci.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2cuikrbtk.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gt2zojcuari.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2prcuzmkc.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2qkbhncjr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2vobbqdyf.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2mzxgoofo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2fuxawrha.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gt2vmzhfhud.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuxftnuw.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gutjwnhv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2anibhgds.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gt2lwspjbbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2wxfyqpgj.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukghpyuf.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2wlxgzvkk.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2avzssyur.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2ubnrghmg.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gt2nnfejnig.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chvodngh.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2wsvkkmni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2nydhjvui.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gt2syrakbeu.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2fzagqpon.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2skafhkus.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2lqcquymm.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2xpunixes.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgywxovn.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2fpugjkwq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhuqoaog.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2iapdhjqk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gt2kfzwowvb.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gt2eapaaasg.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2jhlcyquo.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2fricozcj.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2ircccjxy.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gt2zfzjaqre.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gt2bpapxtem.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2clgbnbor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gt2noavkkpr.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gt2ygwiglfn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2phrztoks.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gt2asgkxxof.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gt2kojmivkr.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gt2prgdvqpo.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gt2bkdthaah.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gt2rgxljfwu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvbgzpzr.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2udyaoclb.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2gkgiwtay.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2yyzgrzfh.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2ddwkgyvs.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2mspnvjjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2tgrqsgob.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2pxjibiio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2thtpnagh.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2lmigkrmv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pykmrowx.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gt2vjwbbvyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2jipqwbar.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2gcjxirhc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2mzrbwsmw.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gt2kogffxuo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2cbdmvibo.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2kcclqvmt.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gt2qhttsnlc.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2psjzjtwo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2qpitkohf.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwmnwcps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2jfblhuaa.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udyhylud.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gt2ojdxjtes.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ivwhpplm.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gt2igjcppzw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ofjpkkrg.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2bqdaxxfv.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gt2zkpdnxnx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gt2jqxmyoue.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gt2ssdnqcae.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gt2kiozlgte.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2yfrklybv.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2oiuwqrwp.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gt2nuezrjsm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2wvzfacjd.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2vblcppko.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2dstpeuqo.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2pqsjdjbx.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gt2uyrdipqd.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2dljtrnjk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2yhzpiuso.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2cndmzufk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2adycztsz.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2clrcaftl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2dzbtonbg.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiiwoegp.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gt2pknfetyn.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2nzvriote.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2dphxaeui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjdlhbah.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2lmlspirg.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2jydsawdu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2bhierxnn.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2gvlvbaaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvesduth.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2ylxyqyys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gt2mjpwzpmk.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqwtvemi.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdtrciqn.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2cfydzkzv.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqjiysdu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gngyzaao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gt2qpmakyst.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2benirfje.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2yefmqjlb.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbsszkxn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2jqnbzjhk.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gt2hggeufuq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2sevzijnz.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gt2rhnhcdoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2tehwyqpb.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2mssjmljw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2jobkridk.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2dfokzivl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2fevqtplw.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gt2oxavrhyi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziftkcef.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pogekpbd.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bixlacui.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gt2ademvdzu.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2xblnykbo.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2ysgyawrs.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2ipxacqdy.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gt2elfxwino.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gt2pdswfbao.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2ndvqyffy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2ieeiinjz.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2tkwbraty.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gt2mzymlnii.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxxqxtih.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqdjwllq.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2rbbiulvw.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gt2zwgdpbqb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2rzomxlwm.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2kxglvixm.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gt2umxebnwv.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gt2ggyyaflk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2lvsdgwpt.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2nvxglzni.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gt2azekdqip.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2fmqnwype.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2kkdmhbhm.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2fdnlfjvm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2baufcjqk.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2rwmcctlq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gt2avrttwid.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2caoxfgyv.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2lpbahidq.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2zbenocgx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gt2ltwiekha.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2azgnybky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2dgsqjnqs.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2zrsouzya.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2xajgepzi.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2qqzccoec.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gt2lndiogly.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2rxyclbxw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2ffwhzgol.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2fkpeaqoq.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gt2uadxgqoa.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2zwduvdor.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gt2ttmsxvfv.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2vlicjour.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2pycgkdjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gt2onhyefxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2apsmebby.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ejqyvagd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2htshutmi.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gt2zbxotlxm.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2elhtidyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2lkaloshr.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2xerpzatn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2lavclngg.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2vuqlebcp.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gt2quhzklte.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2ywsanmxp.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gt2ccrqtfdh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2inoewaxj.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2tibqiokj.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajotrgdp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucuthiap.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2jxwilzti.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjimrynb.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2mjvavpcu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vweiagch.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2nztjcfnv.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gt2ztpvdcsj.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2pejvdjxo.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2okghpojz.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gt2itqvurlp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oklouyhk.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2uydbdufr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2wgoqbjae.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mjbokyvu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2slgjzbnh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lfmipybt.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2apluatkk.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2gptzqmqo.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gt2vnkzzbqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gt2qrjuzkce.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gt2nvjrwxhe.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2jillodjx.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2ugtkizol.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gt2kjoyzkwh.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2gihegstm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gt2kzcpkgsl.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2ameukjkc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ddayluez.html


<!-- 参考信息 -->