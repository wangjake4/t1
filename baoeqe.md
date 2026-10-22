代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtrukjwpie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtsvovoujp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtluarbxuy.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtibigtufz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtcobrrhmu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtlrmzpivj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtpkmqzjkh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsbdowhid.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gthzwcfvrf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnaehquwz.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtacqiqdup.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gthvasuuuz.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtaqcxqdhi.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtqxisvknj.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtjhyhfitz.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtecadydzk.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtgfjgpgxo.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtxmmnellq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtmupkzmmq.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtnppijijp.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtmkigwgfk.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtplagfywv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtsuzwpzxu.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtiukkhkfv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtckbsipgt.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtcdpddfoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtrthxrkcc.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtlclinkmb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gtbdrapswh.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtnygwxszn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtvihoifyr.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtwxszfmmg.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gthggbzvle.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtvlwkqlmz.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gteytpvvrw.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtexzdxwon.html

esac
来源：http://dali.birdmap.top/Article/details/gtmgiifggc.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtruubascf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtrsuwdaxa.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtkftcozdq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtzpwdzhem.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtmrlfernl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtyspjypwd.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtynuhxrwf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtqaxtqzwl.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtuywrzlij.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtgqllqktv.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtahwsinrq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtrxvfnmap.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtixjdxfah.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtqabsekoe.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtvgagawur.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtjzoxeunp.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtipdfmeff.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtbxmssbej.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtarlrmrjf.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtmaswqbsa.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtmfyqvveo.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtsmggeawm.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtwyxiflus.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gteomehlys.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtykxqffkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtpexxmljd.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtmpifrkdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjrdirsep.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtcsmgfyti.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtshyrtbxa.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gttemfjjzl.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtocwguifs.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtpxcqbzfx.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtzjgorgpm.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxomwsvud.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtantsoley.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtruveeues.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gtxtjxltji.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtsclrigwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gtufydxumn.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtgdwjwvmi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtnwyjefuy.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtszakouqp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gttdjkslhx.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtqwvrgsor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gthgklyjji.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgqbsqef.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtyvqwggut.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtgrpjpmyt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtearpuqla.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gttvidkdvq.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gtfzumwynf.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gteyysorcu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtnufdcjns.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtlvtnnbmt.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvftzdjm.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtwqsktngh.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtsstqxwgw.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtggzddobj.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtbryygelw.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtbiynford.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtwhqkwqfs.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtcpssxmth.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtpldbeevp.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtuwnweway.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtzrbkszxn.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gtucyenjdn.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtnapqbjwp.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtlolkikea.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtswrhhkxd.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtezzdapdd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsbkezeoj.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtvmxovlxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtxdkmcryv.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtjhtydqwl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtbwjsmheq.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtmiilgilm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtmbakpopg.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtoxorvgqm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtxtzxyvmi.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtospxodot.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtmjljaatp.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtvdbttkjc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtneiscfou.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gttvenbumh.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtupstsmgl.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtsbgwdxyj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtqlkgrtvb.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtnlovjdnf.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtmsgivleq.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtmcvavebx.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtbzyiudan.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtykfrloit.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtdlpbeylt.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtbmdkczcf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtljlskcjp.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtvxklttrd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtkdbmkzpu.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtiwjwpedr.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtvbrnmhtl.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtqpksgelh.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gthgcdikbr.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gthnhzjwsy.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtzsmgenmf.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtlfeobbag.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtbhqoduuz.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtmgxythnm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtfeziqigs.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtfhalxdho.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtpbgpuxps.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbmfolal.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtywzqtevu.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtkzoucosx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtduunujzn.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtkwnoyyen.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtgczmwtpc.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtilysvbne.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtnwckuxwy.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtqgyjfabg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtvjrwfndi.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gttqmajxkf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtnnjsrewq.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtrorvikci.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtawbsuyhz.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gthcoyvvga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtffgnkhtm.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtwrroysms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtdxctcrps.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtuejvkcvt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtoihysqwj.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtmimjmcbe.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtizlwtdwm.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gttfkoqein.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gtqamafuvg.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gttrqsbghl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtteuuvuzm.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtolweigxh.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtnmxyovbd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnqyuwgmm.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtlyqxklbp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjjcfynqz.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzazhwfet.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtrojyvbib.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtkscybdkw.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtcdcjpcnd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrrmukce.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtixvdnpzn.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtiakhrozh.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtsdgkrckr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtfogrhjxy.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtvkxhqemy.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtteckahhe.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtzkxtpckr.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gttxzdwdkr.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtgskjhbob.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtfeczzquq.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtpuiprupd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtbjrhdjam.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtyvrzraeu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtlgvxmcfw.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtoubvhjfx.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtimitzcby.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtagspbmpr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gteoifrqpp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtzchyjrjh.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtkdbftada.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtzzqcsrza.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtfttacolm.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkqqhckx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnfqshem.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gthmimxrfz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtoipnvoho.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtmjxmzzty.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtwktrwcko.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtpvbkoeab.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtopoogrwa.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtmujwdvqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtelntonwx.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtxqmxpqoe.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gttchqzmkw.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gteecbzklp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtmiydapzs.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtkhujvaqo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtwwmzwggw.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtcrksgsys.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtwgeuoeiw.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtdrbsqgxy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtxznkucsr.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtkpafczsw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtlzvqjsvw.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtksyiuqwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtqgqryert.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcejuehq.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtrddxjamy.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtrukswcim.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtrvaumwcw.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtedwablpe.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtottmmhjh.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtweeuuldw.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtnlffgurr.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtmoatbnaq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gthzznmamt.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtnmycxdcb.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtejkqwyvj.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gttsxomaih.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtclvtjtxm.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqwkrrkcw.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtrqkitgsb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtivxzzuly.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtmlvbtizr.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyswobbed.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtdprpbbuj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtarzkjzpr.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtsrxtmyzf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtstqpitoq.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtxwrozjnq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtajmkabiz.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtxkhokgqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtlqpqhsty.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtlhagtdnl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtcyfphzag.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtbecdwvtu.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtnjpoyvre.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gthocjkehc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtzlgrglxf.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtdefchbmd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtzfjpahci.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gtxcgyacvs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtqhtprmsq.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtgtkvkkbw.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtydaqtabn.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtdatrxuer.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtghniryic.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtdcjvuoca.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gtuxlkahvs.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtsqwiehvh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtcnszzhdf.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtmnlbolyg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtyyxahaij.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtnyuqiuob.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtlzoaipts.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtvigjclpq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtegivrrix.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gthwzytqfu.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtpxoivdmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtrnvvhxvm.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtpzdxqxxr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtgmjlxrze.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtgniasikg.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtdrfomdsi.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtybbytozo.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gthmqhetvp.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtcufstygk.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtaozwzzqh.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gttyacybuc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gturjhdzah.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedcnecru.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxypvyco.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtoysckhjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtxibsxhog.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gttlmbtdkv.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtsvlwoywb.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gttdlcuigo.html


<!-- 参考信息 -->