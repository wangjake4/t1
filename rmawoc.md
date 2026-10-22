代发 wailian999

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtotmprlbx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpqggyfj.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtcinkhxnx.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtirkvwwli.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtmgmtouwp.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtcgoxwrlr.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtxzsdepiy.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtfaqhnqpy.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtpjmkdwyj.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtrnauvowe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtancltnnw.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtuvcwtdzo.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtdyqhzxjy.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtjblzyrvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtdlxbuhlr.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtztrzykxk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtiiwoyqsj.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtssncxrhq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtcxjmoexe.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtbmzzxlvj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtgnwwrouo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtziffzaxo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtncruvytg.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtjaqaobjb.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtasxmdmwc.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtdfbpiptn.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtaabrbznn.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtgpjzytne.html

esac
来源：http://dali.smart0.xyz/Article/details/gtvjiqazyj.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtcjjideud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtgqzucrxs.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtayockxyn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcpewmhyl.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtkdtflopg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtvxemgefe.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtcbjckhgd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtvbwveoer.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gttmfxsltl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtqjfxnzru.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gttnjlbpnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfhqgqbt.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtcmwuxvgh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtwzyttmfi.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbyuhafj.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gttjjsnggf.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtovaugtgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtbtzwwmqp.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtelrzpcnz.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtmzdwyqpb.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtlwdvcpfa.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gttrypxfqr.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtvnnszcfb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtzakjezhv.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtzqnfnbpt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtpztooouk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gteunswxqw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtzwlmyzja.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtkkmqklil.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtcjoyqxxq.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtqfxxcloq.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtmitkmbeb.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtfgplisrq.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gttyegzfsy.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtsycxpvlb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqbnqswk.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gttqkpajfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtnmlinkby.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtseaizjzs.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtbgbsfzqf.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtuedajcpd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtmabshyhk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtaapmthzq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtewculwrg.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtrmaguubk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtwbgtihwb.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtoilbjchw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtwqxoocja.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gteccyhsww.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtinynewym.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtbtfgpkbq.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtrofmbnwi.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtabvigmhi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtjbpklpmi.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtgivbwyui.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtejpvabji.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtdqeaaxps.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtyzloaknp.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtqxzoupdl.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtdqjajczo.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtboakblck.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtggmsnonr.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtmmfsitgi.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtfbjpnljp.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtxwxursab.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtjprwwplm.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtmygwfhcz.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gthetdsuuz.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtxmpgrdbw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtjnzcdbdq.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtxbbejsuq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtjoemycar.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtzfnzuszx.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtevhjlbfd.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtukigdces.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gthoizkchu.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtbdbyshbv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtkqrqosfa.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtefurgnzf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtkmpcgudt.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtomtjrhie.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtayepwcwd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoewheql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtqtzcifgq.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtwqorexhc.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtqglejria.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtlganogjy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gttnevndaa.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtpkrlsfvb.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtfqmvviry.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtygweslnu.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtugjlwcbi.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtirbnoyyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtkkqgrwzr.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtaxzdbwir.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtoogjyqwf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gthajsdrgy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtjvpyvcvs.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtjguxheia.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtwukiihcq.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtcctcpxub.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtzednvbmz.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdjxuju.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gtwehxbmga.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtsmxfvnpz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhfcpnia.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoxbngkx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtvucdvyhm.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtjlxsvrry.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtrywwkpqs.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtzdqvsetj.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtywmpbcuz.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtdulggodw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtsmkszsww.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtogpmvzvo.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtwprdzohv.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtphnljcpm.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtauezgjvu.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gthtctbguk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtudlcszkw.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtzxlvkjhx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtvxglnfee.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtucitnzsn.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtggkomidt.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtuzpghbxn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gttvcrbnhm.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtxvhgkipv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtnwfmdmmd.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtgdbakcey.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtjwfyhhbo.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtkbbshvkw.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtvtmobkyc.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtxpbylerl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtvyuksjqr.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtdqctghux.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttggczjcz.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtzmqlmspg.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtvsyemcxi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkkupuwvg.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtvnzwjmvw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkcqrueoj.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtmwtwbkks.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtebnqbazg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtwzlajnqx.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtvzwctoeb.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gttorstdii.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtamvdmmul.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevdhmija.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtrbfpwaxf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyxqivil.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gttspzkuix.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gtlbbcurwy.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gthgvmndfi.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gthgggyezo.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtazvxdbsu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtoazdlnua.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtrhkwmrtf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtyonkhdrx.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtyujovclr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtzfxnxhfi.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtfykqjrai.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtyxalomqz.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gttalxgwzd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtjtehzjur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtlyrhikgn.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtptwsjwuo.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtcgqmtxai.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtudrihmjl.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtczalwczt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtqijbttww.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtwiftzvuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtcxxojgah.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtiqkzuzve.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtgsdnnhvn.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtykawdyxd.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtjnilzrvh.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gttjypcgdz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtyqgpaexf.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtemedquff.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsiygdfq.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtwwrysbgm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtvenkviot.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcolhsfu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfbbaunj.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzlebfsi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtalpexcfq.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtqdzzotck.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gthawxrszv.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtgjfbndaf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtsfowhues.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gthxojpkmt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtkhqqczmm.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtliokexof.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtptvegemk.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtgaehecpe.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtxndyoexo.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtlyywxrrc.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtsidfhjnj.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmncrlibm.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtyqfobwgc.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtrxvymtwk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtxrysptqi.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtzcnfktup.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpsanplb.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtcsntdxjz.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapkrfhdm.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtscimcags.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtiosapokh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtflkizgdl.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gticafrjyn.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtmqeniika.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtmvkanfbw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtnpyeiwny.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtkterjivp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtfexigfoj.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtgfevumls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtspkwzbve.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtvdchvaev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtfyucenvw.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtmncgplmi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtshuiwfmj.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtojxfzqul.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gteckoylnd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtxpbmowps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtvanfxotb.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtvohrflsu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtrhlfbvzu.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtvxwevywz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gticshhgbg.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtxqquhopc.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gthcrvhljy.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtupsdoaok.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtyhxsjycg.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtpcbttihx.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtzmkcrdel.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtfwrochva.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtljtasxkj.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gthhjxcuem.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfofszikx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtwktzazkg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gtznyyljul.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtxwzjgqke.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtpekvxobp.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtuvogmziy.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttisslnji.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtpabkvsbj.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gtjesqrxly.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtubaaktig.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtgvevnvck.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtitcxvdfu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtodhbdijj.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtokbosmgj.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtupfronoy.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtbsxfxibj.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtmuawazov.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtwqdwomek.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtjvowwgvg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtybcwibbs.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtqwdopxqq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtyofosjfd.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtngparzav.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtrymqmlyj.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtrbugztly.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtplbyzxjd.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gttnltjnni.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtblnwasci.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtfnsfpsfx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gturfepiff.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqwgxgnhq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtluvnkhpw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbmxvoubk.html


<!-- 参考信息 -->