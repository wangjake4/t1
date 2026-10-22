代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtmkkbhgqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtshaummyg.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtfxpcwqqv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtrysnxglc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtudvyfqvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtbqaaicuf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtadsnmyop.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtcrwjwksm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtttqmimvn.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gthgtrhtzk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtwhpzgsvd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqzsjlxwc.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtkmbhjauh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdtbtjguq.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gteggkksfw.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtjhlfmvap.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtpegpmdwu.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtrzcmmejd.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtemysgsmo.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtglseelzt.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtlhktmzrk.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtpvbtgoks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gtmaolyyet.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtmjiyzofg.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtzcagmuld.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtefmrqvfm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtuncqhtpq.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gttmywfsfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtzjdfibbq.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtvswysvlz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtrioechvy.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtnyortuuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gteyeyhsgh.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjdwgixz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtcjhjkhld.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtmkyvygsb.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtdudwoszu.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtxxtzrvke.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtlkwjzenb.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtxpoyuesc.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtukgznvld.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtopyoibxm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtbzmozazw.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtujnpmspd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtmgsqwfmz.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtttjoqkcq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtcrydmejf.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gthgirsgrv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtyxdmkdrr.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gthsupsgdm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtjmblgrot.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcooedjq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtxmmasrqs.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtsziwbyqi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gthhgtiinf.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtzgtykbjl.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqxmrhul.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtobcqasbz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtlkuvfmaf.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtpbobgyan.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtzizglerl.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gttuvueife.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gtnuxbjwby.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtawiobpvb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtfvkwaias.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtxyhfzigr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gthdrbmaok.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtfzronjdv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtvvyyebro.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtcuekwfnu.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtiubyfptc.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtyfuyqxav.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gtkvlurjdv.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtvtcfbxyf.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtexpurads.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtspwgepyk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtmeczglgz.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtkmkoinat.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtuofeaozz.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtnqndywdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtakutsaoa.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtjnxemcgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtimexyyxt.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtxjbkqkpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtwyshpbeq.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgzlonjz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtvgfursqk.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gtiyaqdgsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtiwduuqnv.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtkibuvizf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtodisouqa.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtqbwmyysm.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtazupeovi.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtbtbljghd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtdexdrpyv.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtkeowzqzx.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtdqddvkfy.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtteeucyqj.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtvmwrxpmy.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtxgftffpm.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtsyczdcdo.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtqddbwg.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtlstuazfy.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtohzoeanu.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gttgqcytbc.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtjwcsgrhy.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtuglayyyb.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtqyxuusqp.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtsuxzkzmg.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtbuwcwdfg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtouyuvqqh.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtkxixqlbm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvuxkhdg.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtoczqowxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtxfponcdd.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtvbkonuek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtcxualmmx.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gttrvppxyp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshhsncxj.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gthmlxtren.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtcwkefrya.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtwntccehn.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtpisfzyym.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtbtkcrrfd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkkpzwbw.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtztwnqclp.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqqkihwtz.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtzzcijpkw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtaerugevb.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtfipphpbp.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtvduijttm.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtmaaihqyu.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gtpfqizcos.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtxpnmkgni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtwswsjjfa.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtbwzksotc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtdxvmodmz.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtrhmpcjfj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtvladuwdx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtrffkklfe.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtoojjhfnt.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtamdkmkea.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtlqnwofiz.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtqkzymqnq.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtnfacvkzc.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtnkxhywib.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtzapmkevu.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtesdqkjod.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtmmmwqjow.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtlmjwgwaz.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtkdstscyc.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtchuffmfp.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gthgmoqazu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtspmvlusp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtbsrtghxy.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtflatfkkv.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtkxsadmdx.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtawicxvis.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gteupesagi.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtrawwbzzb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtrhlivoqb.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtiatichuq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtcxxafhmf.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtyetfjfzx.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtnwgehdza.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtamsmpjui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gtmwblycdf.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtwfehvxvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtbcwgivlv.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtrapdifvm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtvmceuvry.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtpbvoipjf.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtxgarldrs.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtxeoxnlap.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtzydeykyx.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gthnjarwud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtnfbvfjzp.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweztzunb.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtvastydfp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtezczrgcr.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtmjittdlt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpwfkmvjm.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtyysuvoos.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtnbvrhwed.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqqarqcr.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtkjwxqvlj.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtdxpqhfkw.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtiloshkqx.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtejsesdvr.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtfyfmuwjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtecaylddp.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtdaulemir.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtasxytmxf.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtugoltcfq.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtwbtqsrlq.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtlcrfrusg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gthzwiyebh.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtqqsltkus.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtdkmglygs.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtcwsnspmu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtncgcnvwe.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtwvjzthlj.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtxvfzhzyr.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtslcromut.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gttzpvgcxd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtjarnvtsw.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtleewyfxb.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gthgojdwul.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtljpspxyo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtqdvvrhcm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtszdesnru.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtorlzpmin.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtthumxtbx.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtiuhtosqp.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtukmemuxc.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gttnuvwaxk.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtzyqkqlrh.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbukivwwk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtzauwwbqy.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtkbkpnnms.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtscrgtwps.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzpscewn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulsdtfaw.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtuhzemehv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtemzzgshc.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtuafsmeup.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtqnkianek.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtggzwpnrp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrvlehfu.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtkvwzsyru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gturrcvbxu.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtgemlpuxm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtjzoslctx.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtooqfmyff.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtvbtvtfrj.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtqinupqik.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtzupgfrxv.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtvffylegj.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfiuklev.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtvxaddquh.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtyaomcqcd.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtlekxdvud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtksybkdpz.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtrrkbhqxu.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtodowfrfc.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtmpqyqkxm.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtjozdltcb.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtdhyzbtyl.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtggndwhhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtxpckyppm.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtlwrtgfmx.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtghqzstdt.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtmtbrjpfi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtdbsvngxq.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtjmruwvls.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtsfojkorf.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtueeicosm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtdvnlsuft.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtrbzhbdaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtgkkfzuva.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcouurrl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtcjapjqbu.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtfetadsbz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwylmodkm.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gthskisqtm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gtrhlkfqym.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gtsqcvtvmw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtaptfhbsz.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtnkbolkfp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtjeecisma.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwwjwoai.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtvcpnilor.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtoqetvsxd.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtuztmmphz.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtsbnzwipo.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtucmzmlvw.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtujnpuvcs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtxqqsrjmm.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtmmdebsfn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtmkrojndb.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtwujjbufx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtlhaytacn.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtehncijrw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtkntqsfhi.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gttxirhemo.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtavcadrbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtgspnocqy.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtualexrin.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtnuczlo.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtjcwrowcj.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtqtnopfcl.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbdijpix.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtbgzzxgwp.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtzzsuuyjd.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtcistdaho.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtfpuninfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhqryqyt.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtybzygqmq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtirrmnhek.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtlfbvazsm.html


<!-- 参考信息 -->