代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtifchsgwx.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gthfltxlum.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gthvpdtskc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqoaxxmyw.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtuclxmgoj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtaijtzoyw.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtrwyupfit.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtnncbwmda.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtklemfoqu.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtpbplyvbr.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtoiacjehd.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtnscdhcvf.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtidavyjxn.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtnuyxhizm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtxcjloyjd.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtugmzczaw.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtthvakotr.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtrzzsbhdx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzklxfdjd.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtquhloyij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gttxqtgmtx.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gttpsrtrlh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtxdhdmgza.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtlozwsorm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtbsjljjzq.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtudwrsavr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtelwzxafi.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtvpmorsht.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtqaxnedao.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtizikxpzw.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtduxgdndr.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gthyecfgla.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtsxrdyngy.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtsdnyhimq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtiwqernla.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtuphevanl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzexsapz.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtnaqqayxn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtqiakseco.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtveuubjjk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtxamtpopc.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtkkfrobvd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gttehppmty.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtdtjurdeo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtnpujzrbv.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtzjwgcqzm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtlypmmtkb.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtuqkmgdmy.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtrwfgtgqg.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gtmynzsnwf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gttrnjajco.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtabwlbvtc.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsljtrczn.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtufrkhjov.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtmrjporxw.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtqywiqrpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtiocizxfq.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtlhnakdtg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaooegdpk.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtvflsizaj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtsyrgiihz.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtwcnjjhyt.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtajtxxalq.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtysltyrxe.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtanhwvopu.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtuaiscdxb.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtctshbosj.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtczmkqggw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtdszalmus.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtgsogehth.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtyoycxyup.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtmzaevynj.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtccdxjadl.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtitftxxpy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtwkaaxado.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtelafzyso.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtqtyszffg.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gttnleeafb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtyrpccsuz.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtecjnymxd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtfdufukjx.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gtfurypflk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtvmchlszo.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtbtkikrvz.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhckelog.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtsiplhanq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtaclygzui.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtnoapwmdo.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtnwpkuabn.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtvlmsqpgr.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtyctgmqej.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtlykzqcot.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtzemfbfro.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtzetybgwi.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtqwaqnfwv.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtliihnvhq.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtvcysymhi.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtdisocvhn.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtmxraimgx.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtyehwsenc.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtnilnovql.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtcyptfgfo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtqftlrxtz.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtgmcpuvsp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtvvhhqypx.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtjfremgwx.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtuslvleqt.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtowrddrql.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtxrzgqkjh.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtrmlzqvcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtekgxwrql.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtobikulkc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gtyhkmgqie.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtxaiacikt.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtgcxstmqy.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtqnvokmgo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtxkdaswro.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtdmfucumx.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtnjubgmba.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtqukbjari.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtvaoknzji.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtcmowlyas.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gtupbnahxr.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtjrwurxzh.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtvszmcgok.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtiyvwwfgl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtwxpnbrfx.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtwqoytxvg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gthenpwmrn.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtlcvyzkkj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtljcyvfrj.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtkhvunyva.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtjfegrbyz.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gteuaahowl.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtzkqrbpdm.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtgqwpsvhs.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gttaszwwno.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtbyvgkuuf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtbnwwjwyw.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gthoxgkbqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtrwgnhled.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtxjhxsjjv.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtqmuwwoxm.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtcvhkxklg.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtjijobcnd.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtsyyigupl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlieovtv.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtuapbemhh.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtgrkvhheb.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtopjbskel.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtdhnnyomn.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtnxouacex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtnwqyozqr.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtpwhwcuwx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtxkqictzd.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtmanhpwcf.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtthlxzfee.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtpkzdeiib.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtdenxmsaq.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtqqqgpmlj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtchsfcxdj.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaqjdkpm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gteqdzasri.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtbytvfwlf.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtocmxskoe.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtmwosvxrh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtmshpiqzo.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtnytaektg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtwehhkvew.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtkbxtcixx.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtvvqajlge.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcxvtlrkr.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtfqtanoem.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhwfxnqy.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtdzhvqjwi.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtbssbiyaj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gttltteuad.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtbrrnfpxp.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gthymczdku.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtnicrrlpx.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtinhkufto.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtrwhggbwk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtbffaoyvy.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtrkttwmwe.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtrmlaueje.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtwiwwikfm.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gttgxzxgoo.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtlyoeyral.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtyixzezwn.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtsbydcsws.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtehkehkoi.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkaruoxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtceqkctno.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtjfwhujri.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gttvhnzspp.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtzbpbbwax.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtyiyngqxk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtyhghkzmp.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtrvdhxvsl.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtonzloqvg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtichrtmrn.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtxwfoekrn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gteuoysvxh.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtvvkciqpw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gttwpkxukl.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtyzffnfbr.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtlpqvoumx.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtpzexxavf.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtrsswjgce.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtoijyyvig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gtvjaunbib.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtrpxhvzwt.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtzuokcmmd.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtpvoumqrf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtxnpcsvnk.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtpgjbhxsf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtriwcvihv.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtdvjgkemb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtdoqpjrfw.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtlmuddmbh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gttmtyjsex.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtpzmrkpun.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtktjjqgki.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtzkrjzjir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtjutoimpa.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtpipfkuef.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtqzblwldd.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtvfqmwhlz.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtgzcmfnuh.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtxcbogocv.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtufgtxmvj.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtzkscvjtn.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqngvysox.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtyahglpmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gttfspcbhw.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gtwpzebhpw.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtmzemdayq.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtpdojwfmx.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtlptxlfhg.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtlwizupkp.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtwspqkiwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtdvkoylqj.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtscjyxnux.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmfrafsu.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gttjbchfgm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtepcxjllf.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtecakwett.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtlbzhguty.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtoxgccygx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtvlsuiqso.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtsyijgwzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrgjlykwh.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtucttxuic.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtaanwcgew.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfijgvam.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrceeeios.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqshrljmf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtfhgghevh.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtbehsbuec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtntpjhmpw.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gthnazjemp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtyobtjemv.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtrooyzpde.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuwwvagn.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtyyrtpmmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtuxoxucti.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtemqugigl.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtbacgxkcb.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtynamuzqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtgviixgvj.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtahgozjxe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtgwlhcxfb.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gtbgvgrflx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtsbksbmkj.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gthsmzxxva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtumhnpgli.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtulcuglwh.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtvmxliftn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtbypxhzda.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtxlgcalsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtiwandqzk.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtedoiabij.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtdjgcvxtj.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtwbkwpmkp.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtinpjuhpc.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtygzmwoey.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmtyyjcs.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtbkkcswxd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtmaxubqcz.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtulynclpi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtszdvylmn.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtxvwlefac.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtfjhmnojb.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gteqwxhcok.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtfcxpbhrk.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipvmqxgp.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbwuetnj.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtfweobxjk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gthyjssdcs.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtzvwbspot.html


<!-- 参考信息 -->