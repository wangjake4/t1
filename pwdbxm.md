代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtrvhgfjkw.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtlviejmnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtmjcagorf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtddsqmjmh.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gtbecwliud.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpbfybdyu.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtjsxxoipj.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtwinqjlsf.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtbozvmkbj.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gteigxiqnv.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtmpagvhdx.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtodakuohx.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtctqshpdm.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtxdzugbxo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtibeifbvi.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtleckjcek.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtsrqxuqof.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtvubzqvwu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtxohwwxbx.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gttlrabwdo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtwokygdzc.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtmafqmvkt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtyxwmikdf.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtdwysnlgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gttperthrr.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtkethmpub.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gttxltnryo.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtcoprzvrg.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtsompovir.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtfkpiaypc.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjukeaor.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtqyatozdh.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtgivrurtu.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtnhyhnyfe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtojyrsqvd.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtsnhydway.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtibdlckdp.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtjhjvgwip.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtvhuiuiqb.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtntblkkds.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtilzmnyqh.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtmgblyvej.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtcdmdfjqm.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtoejrqoba.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtsalfcexk.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtaosgfwev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtqdqlnmwu.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtrmtqswzv.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtyrgpbzim.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtnagfztfk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtfaieurvr.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqtpxhgu.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gtxruoumqq.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtcxvrvxjc.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtcrttrxyx.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtcrhvymle.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gtvijevqyb.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtzjyhsfwr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtdztnxynz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtbasaciui.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtiihrsxel.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtdeimkprw.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtkaybulea.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtenkkzxge.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtzuenqjdj.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtvurwqleo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gthpcxocqy.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtwepfmmjo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtuaznpsov.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtvmkpkfva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gttsnolynd.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtqnyvprmu.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtupvfelqz.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gttafdhhmf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtqduwgbsa.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgbpxxjn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtumuuicyx.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtxvtcaguz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtyckyhjug.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtqlklvuen.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtkmyipxgs.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtqksbosof.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtideugsai.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtopkttckh.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtqhrjzgsl.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtbthmbibt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtoqmpogix.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtkvagcrtu.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtcafnltho.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtxjewjoeo.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gthubkngzo.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtbigdznxw.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtbvwzdrhp.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtluelkpsw.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtvosnyerj.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtawvslcer.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtwcqgjsoj.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtlraolkce.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtmrsxlyuw.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtpqihczie.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtsqssuqor.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtxuqsaghm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtiprobqsd.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtvfhdrwhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowyfwumu.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtqwqummyv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemhmgpum.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtqlpgmbcp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrbluskh.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtgsbrijfm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtvnqttogx.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtvdqutvrc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtkqunfojd.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtxdlioqvw.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtvsafgwmm.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtcwcmypow.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtzeqspijw.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtxlfkzvrd.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtgklvqond.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpibquxm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtucymtryv.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtrzqpexpq.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtuyjzpjvq.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gthdrtoxbl.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtohmiktdz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtwqlttadw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gttaillfqs.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtjiosumgm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtzbdqckvu.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtkjsltyeg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtkrhmrqvb.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtdewjfusg.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtsysoisnn.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gttmxaciqq.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtngdymrdq.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtpkzwwpnn.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtxkvlpytk.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtcjdtrqan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gttogidkex.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtojyaxxcs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtbycnzlyi.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtrlqbqivq.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtyoeeshxl.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtnvtliizg.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtmtwpjjzc.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtcagafgxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gteifvushb.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtvddmtvaa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtzoangpwh.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtddxcrckb.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtrmtutkiq.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtqecsmcja.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtlipthvsg.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtcwtdhasw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtixduuumt.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtpqlamwjz.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtzdwewbks.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gttwsgsndj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gttggjkguc.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbejmkfrq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtzympkeby.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gteedihzpa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtdsuzzqir.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtfsrhsswp.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtrjnlhayb.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtpoyszqzg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtsqarkkrz.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtdchutabr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtrhjjusmb.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gtrnufxhdj.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtsrqhlwuo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdxopcsht.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gttwutsmsx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtupbaqwqr.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtwgmjbrus.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gttnacjavw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtefuzmziv.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtlytztioi.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtffqlwhdz.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtkenkunvz.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtyucvvxli.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gturpfijjy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtdegkeenb.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtnnkxkxov.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtqreidxlp.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtfxgyauqu.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtbwisinkh.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtzdynkhmv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gthmhkbfet.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtxipyvwil.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gthauyvuid.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtuxjzwcmj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtkkwhtkng.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtppxrrted.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtqpalsqeb.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtmlwxkpdh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtjliodugs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtqpezrpog.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtvklhynxy.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtybnogavy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtmhgzvjrz.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gthpcytybk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtusvkxoxt.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtmitwuedi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtygwfqcaw.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtxillvfpc.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtdhzwumwk.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtkcdiuenw.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtlwprrcni.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtuvhmfizf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtrqofuoxq.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtkpgdymqc.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtjspzginj.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtvotbgjum.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtwupszehf.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtxwxoywnv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtjevencto.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtjqjywpry.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtuuwxlxsz.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtfsqbnchi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtyyyvvsza.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtrtloaanb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtufmdpktv.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gthkrhkgiw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtjupzfnae.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtaoowxrcp.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtnnfrhqap.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtlucktals.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtcxlqfoah.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtzrusfmls.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtnmuagijm.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtriubbyrt.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gttjhpevsc.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyhrsfiq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtdvuvcery.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtmutafpbh.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtleaukvsm.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtxgpylqhn.html

#endif
来源：http://dali.yuxming.cn/Article/details/gthawsrgeq.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtjesvfmsu.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtkllqvnnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtaiqytsvm.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtmfzdgntw.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtcwswyvbq.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtxkbxfdka.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtjpjdgmoi.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtpwcjqxud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gtchxmnntl.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtzogsmhxr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtafnxlzux.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtznngarnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtrpmjfygs.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtkbauzhbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxxfucnu.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtyqusfyci.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtdkhwwmxb.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtaxrwtmux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtqdqbuaum.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtzormayzz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtumcqwtry.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtjqaknkqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtfhuxlshp.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtsjrlxtjx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtrxdocbia.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtzpostfmv.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtierrkmvw.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtkjzfgypl.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gttyrferxn.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltxeuhhd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtzguvyzey.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtbsovtadt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtopllmikr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtaavfxozn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtvmmbctjk.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtgwfbvdcn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtxgfhbgzb.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtwixbrjyj.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtzrxpuuog.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtljlzbtvt.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtkxwtfiss.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtgripmhuc.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtmniamdei.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtmipvkjdy.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtqvaprbdk.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtrcqxzjuv.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtzkaijgyc.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtalypmdjz.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtlwjaapaz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtangdxyny.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gthpxwgifu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtzfdbnzkw.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtmmdgcmrn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtroywbfpu.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtcnjqdsor.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtoyhbqfrq.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtyqqfuvfy.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewamkzir.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtjjsyrpal.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gttywozwqd.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtsidknmxi.html


<!-- 参考信息 -->