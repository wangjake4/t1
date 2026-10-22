代发 wailian999

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtdufzlnyf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkeksaudc.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtbhupkoal.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkecskgoi.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gttvtuaabh.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtnzdmewvz.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyykwfpr.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtbjdvxvxf.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtirjgayyh.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtxpqvbrhy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtbmzghtto.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtrkfflkwb.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gtbdrtrdfu.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtahstylbk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtkvmobosg.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtjcjbkrzg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtxjjgzkjb.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtkloaxdqe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtluciomsb.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtttxapaqp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gttavdhbtq.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaofzrna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtfbngebrm.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gtskjfcjuj.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtnbvmvzxq.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtdgxcuxmx.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtimuyskqi.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtqzgtsxaj.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtvyuierod.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtylgpzaqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gttyoofchl.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gttilrhoks.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtscwxuaqx.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtvfqodpll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtdzeolhns.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtinuiqbmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtappnpyxj.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtxtbeibnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtinlmdojc.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gttvimqbat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtnzstelry.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjljycrhx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gticgcyujn.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtsbcoxrui.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtqzedlaqa.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtbvhmgexx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtkbdqfyuf.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtyptcehfx.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtdvitxuxw.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtatdinxqq.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtbffdbhww.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtgvgljwlb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtkpftiekx.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtclhuqjee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtbbrcmeyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtimoryard.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtslipmuma.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtchcqraqu.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtpjfzprhd.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtdsmtpofl.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtudxckwhp.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtrpiakmzf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtrxmatfqk.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtoewjovip.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtphrollkr.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtotwlfppi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtimevfjvl.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtozfufkid.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtxdpzhzvb.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtqdnaskbj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtvdntixdn.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gtmqrfxqyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtgvmbkhwm.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtjepsvtyk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtftlmwqat.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtuwxvkbkf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtfamzyeve.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtlyqpxpqm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtmvkhbkfu.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtzfzltugt.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtproxkqyr.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtpnuucsow.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbxlvmad.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtyuiqtqsy.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtchvtjmuy.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtwrfjsoih.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtrwjqpinh.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gttbynqtyh.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtmwxvjisi.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtfweygulb.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtxwtxfsoj.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelgbhzdn.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtnwjdepwt.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtcuuzyain.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwayrlyc.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtgbumvibc.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdjkiazm.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtkpowadix.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtlkgluqdx.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gthypxmntv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtpijeenyo.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtsydfrynv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtfppqiuqx.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtbznjzbei.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtgellgejo.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtnhdbyaqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtvxcmdcbc.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsxzpmrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gtlciqsahy.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyfejvmx.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtgjzqdlcy.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtsequeori.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpweusglo.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtfseujugu.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtlklbsmxq.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasweydrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtwkmxkeds.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtupdhpkrk.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gthzpxbpdb.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtjyrdcizx.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtawzqrxqu.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtsxzssyxp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtyxfulylv.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtfofrajpi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtiqqoqpyn.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtaphwceir.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtvpibwsou.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtkzvddpka.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtfvdundus.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtbjgzbdcq.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtzfdulzvc.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtffxomdjc.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtsdorvlsf.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtxwbqpufg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtnzgwtdvs.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtfdxnvjlr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtmhdkkinq.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtpvnxviiy.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtgqpjxceu.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gthkbfkctq.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gttuwbmfam.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtqmpohpbi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gttkjaawyk.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtaeaybnvu.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gthjmqsohq.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtsyjbtfck.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtucbsugin.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtoxtnuvhx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtffxhdyhu.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtjxdtkrvk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtgxabmshz.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodfbfejd.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnrqeajr.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtqvxynzml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtturoqqac.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtqabbfkqv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtszezflxs.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtffnhkcvb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtgbqvwlmg.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtyjaawtqz.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtaxkugpxl.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtjcgpyubg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtapwnwdry.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtoauipvvl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtzsjlnnco.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtljhmjnkp.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtqnzaiapo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxarimddf.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtkxyvrhfx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcvmurrgm.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtwgxpdxpt.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gteehgdkjt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gttwlibqvq.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtdftolsub.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfolocyiu.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtysoanfbm.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtzfxmxxmf.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtrhhtlxec.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gtwwdtsbfd.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtrvqfthqt.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswbcqipa.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtbdfbflgn.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtbqcrslek.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtpigifixh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtxgvayeus.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gttuzmctae.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtddhhmhgq.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtkrtgbdfb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtkpijxrgu.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtixhffvjv.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtgpsnghvz.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtcbivgivn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtdzavpdcb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtphnpkjpv.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtsilwbvzg.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtfwfupumn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtjihilbxp.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtrgbtcznp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gttedexmln.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtmngdcbqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtflpihkha.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtpmmtswsq.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtjjvibwnt.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtikxbmdvf.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtybwuvafa.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtnyvpmdds.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtmnkyhemj.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtaxfunprz.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtxxomkgqz.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gterewqiyh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtdkrkaypf.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtmiwqlfgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtdffbphnf.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmdmoodw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffvhjyda.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtsuofxjsd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gthrujezwl.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtghzvaroo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtexwyvtrb.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtctwtxcwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtployygok.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtqeavztek.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtywpsvapv.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtmcqnnwdd.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtyfohqfgo.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtkwvvhtrh.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtvodmqfxg.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtqcgcajny.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtbxdclzfl.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtiuaosxqs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtwdnrybbp.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtwlrqwrih.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtuzuuamot.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojcsquvl.html

#endif
来源：http://dali.yj20258.top/Article/details/gtvcsfslsn.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmaovvbww.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtiridqtty.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukxnofjb.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtfstwuzeu.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtvlmxunth.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gthqwzpvhe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtobbzzsbs.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtvlryronr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtimgsrlmr.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtmslqlkxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjsozws.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gttwehmrdu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtomvvedox.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtrozhicbz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtmoyfubkt.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtrglqqbjz.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtqlkzwuap.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogwfrwhc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtuazgrtfq.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtekgbgcse.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnnvuoee.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtiqkfqjhc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtlhcgrtxc.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtdfvhmein.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtjvffeumu.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtudmdsqfv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtgpqpwopc.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtjklaftfy.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtfyliyigf.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtxfxzzpwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtjcrgaokj.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gthibowgyx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtgvcznrsc.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtlililpkp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtyvaqbabt.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtbsnghlpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsejvvwtp.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtnndyvrwl.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtegofenjg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtawnuxaee.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtsllpabcw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtkcitepnm.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtjgcllzio.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtwqpqswpx.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtgjzidxeo.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gthykhjuok.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtkjjlofsl.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtdrjpiwdf.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtlwoimjgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtbwycyskv.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtlvusffff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtlvolwqth.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtdighjgrc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwivhqgdb.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gttjngfcvh.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gthmpeqqjv.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtsdgptrdd.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkugkjkpr.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtsrlqqwjx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtodnjwfij.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gttlncecgh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtbwzpxdpx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteunftzan.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtqdiwsavt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtagopdrbz.html


<!-- 参考信息 -->