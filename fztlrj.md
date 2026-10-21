代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtmlrzkbbk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gttwybuzxc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtrtoeloeb.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtppkykxre.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtxjciwiya.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtjbcjisjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtsgakanhj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtihwcmuta.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtvtdowwqv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqtcktdop.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtavvhrccx.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gthrexnbtp.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtblilamgy.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gthcfkxpkz.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtseladdsh.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtqvkzjmog.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtbfkombgr.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtjnqdotek.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gthfwcizgl.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtflnlzlot.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtjzbactmj.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gthkjkekdh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtcvudrwkj.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtyvusqhek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtsatqbreg.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmurpwtw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtgxfynkna.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gthwppvvhb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gttypqhltv.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtoafrtuty.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtasasiial.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gthwkpewdl.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtcrxxrsmk.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gthelkvorg.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtdkmmoyqs.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtumhbztym.html

esac
来源：http://dali.sysykeji.top/Article/details/gtijpsrclp.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtukrazzuj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgzcpwyo.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtymvgwksg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtpfepqwtf.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtwepldnjt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtupbzkdnc.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtxmilsgxa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtecsfriyi.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtobjqtiqb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtxngmcwnr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtafkocxjv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gtozvoxlmb.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtkhsktdfv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtkyqptdmg.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtaioittli.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtchjzauhc.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtsmthseci.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtncutvhhe.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtxvvxefgr.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtmuhdplgo.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtjthpzhlm.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtlkfzlfxc.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtutdvnutr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtagzszezx.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtojiobinl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtfpmfttbi.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtbjewvmnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtncyogjsd.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtcdkmbxfs.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtimlwbueo.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtcfiywhhn.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtuvstokiz.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtaapaebid.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtwxnowkmw.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnxtzgkqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtbnluamkx.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gthyyoblfx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtdajqlzfd.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtgmwplnph.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtfflosmfo.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtoxzxxfsx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtvjzmgahh.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtiicypaix.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtjgjeugkq.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtwszdraid.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtvynqtloe.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtquaajxyf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtspqeayft.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtxpmkrtiz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtrtpdheuv.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtflfvnvbx.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyvflyye.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtejntogdk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtmnmarkyg.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtotooxbgg.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtuurojmci.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtmsgqviot.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gthisbdpop.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtpcmezlvr.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtcsorjtyz.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtlibgvwha.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtohkpaakz.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtbknyetmr.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtclnwgmjr.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtlsmuedyh.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtjiaothwr.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtdwtonpeq.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtwuibkzrz.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtwdwomjxs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtcvaykrnf.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtnuumfpap.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtzdslaeya.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtirpapvkr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtopyjwhna.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtievwiuip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtmurqhbqj.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtqfrcqxry.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdbrkwvyg.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtkiqvgxir.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtcimuwnoz.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtesfmwcdl.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gttbowzabs.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtvllvqcpx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gthvnrydux.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtxklycemb.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gteerstbof.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gttzloofsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtihmwfogr.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtwqjhylya.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtjzpwfxns.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtskhftahw.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtmfuurakb.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawbzcfmi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtrnhaeigc.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtyxtvuczv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtdhskwwqc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtwifrmyro.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnusjlke.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtvylrdwdq.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtvskejenx.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtrojmozav.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtfvpgpirg.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtothtnzbp.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtnnsjpzby.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtunsumyto.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtdnththsg.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtzjmtbanl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtzclfgllx.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtkjhkizgz.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtzkanxeec.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gttvdygayg.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtdiibpcdz.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtytrvfamx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxmikrroz.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtgymqnyux.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvtmkmro.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtzyvmawuw.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gttpkykcvr.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtnznaaaak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggacvuia.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtfqbhnxdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gttzayaugo.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtqeutmfeo.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtrgvoxucv.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtzuajqhwt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtotuspgwm.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtreqvxtew.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexbqsboa.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtnsdpmtzl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtpkhnwnxp.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtfereccqh.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gthjwqwlpf.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtxyzmpuuh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gtggtidbvh.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtppbbmfws.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtxqfdksbh.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gttulvgrfp.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtwotgwzqf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnamvavat.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtbhqzwslw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnabfcojf.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtlvuxmbow.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtgjtmgsmn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtfyoecffd.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtpbsgyfxk.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtdkjhkowh.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtokkcsumz.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtergqdkca.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtvwtqzeia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtulofjuos.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtilbwjcja.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtxsokqmav.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtasochgyy.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtdwwihknl.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtmmytmkvy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gthluaqtpd.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gteekpalhr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtbsviubxa.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtzysdpkns.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtqojcpolh.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtcjndssux.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtkhfavppf.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtacqutcbt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtrsfrwhcm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtnfnmcgjk.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtugfsltbl.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtnuhlnbui.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtlbwglmhz.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtghelxbzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gttxntobxu.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtaeguwnue.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtgszqggbz.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtzdnjfnso.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtahpryyuw.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtwbvaktzq.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtbrgmyvng.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtemiizbiq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtrooryrjp.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtgxhhvgmt.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtwtbidfwl.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtiwzkfwxr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtxkmtvyzs.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gthqkrdtnn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtjrubkwvu.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtglzzsaqf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gteamxgxqs.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtkfuytfgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtetjoorvr.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtvoqkuott.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtaajhyqpd.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtupjskfxv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gttvwjzftu.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtmtslvtns.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtoslblqbr.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtualholqo.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtnuqqnnde.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtjfktjvtf.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtytvdjbzx.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtufqvwskh.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtsgesogjf.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gthnxbiijk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtkguvjkhr.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtczlgdqvl.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtvcjepbdr.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtfmvndkip.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gttglynlir.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtnvilubqx.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtnyzxwarh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtomvnqsfq.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtyafprtmt.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtilbopeeu.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtfhmxwvru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gthtskebiy.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtthrviici.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtbubljbub.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrpdulam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtsouokrml.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarwmbaqi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtkmlyylla.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtvfgpxerk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtbltriuip.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtumttssfl.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtzttgfnjw.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtzxpcwzek.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtpxptzuic.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtjgoxgvhp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtlykzcuuc.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtnlrhyocw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtibniibea.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmdtwjmw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtvqqvihot.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtcqgfhcla.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtagcwtbzi.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gtcfuwqvul.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtgjtdsmtc.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtzucwazff.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbfgydof.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtothejlow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gturkwxtaa.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtjniugqzm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtqndflscp.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtlpwjehuv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuantlxyg.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtnmhndqii.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtnacldzve.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrpnbzhq.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtgbrorurl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtdsybmrta.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtnqacbqsw.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtuhjpuypd.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gthndjucdw.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtfhzattzi.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsjnrphv.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtiqteqogj.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gttzadavps.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtxrrlzjdt.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtgugmxkef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtzxobflny.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtzhxpupnk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzghgyxp.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtrnlmkypt.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtmwrzamga.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtxsdyhgby.html


<!-- 参考信息 -->