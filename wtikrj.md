代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtsudqgzrn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtzgusjria.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtbgxqtsps.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxnumyqxs.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtplhyoplv.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmsqmbmto.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtbbdnkjnw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gttssdiurg.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtlwsikveb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtuisedpkh.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtsyqrrmhn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtaucilhgy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gthjrfupzx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtnxknlaxn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtbqnczqcf.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtiwucpgcp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtozpenrwu.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtobhvoere.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtpwlmqycu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtarkzngxz.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtfnjyqlen.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwmitbtbn.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtiagggqpz.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtwdpqvkqv.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtuquppunc.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtpelytaly.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtrrlfzmyl.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtszaotjbe.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtrbnxxgza.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtuonaiehu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtzjhdkspy.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtjeorzdnn.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtwsnovqyq.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtuddoaaeq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtgczheszu.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtmlktwewd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtaqshfvyd.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtaquebjgv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gthrjzfwet.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtpqermbrg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtjptvtxdy.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtherbwzig.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtdrseeaua.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtfbphnczk.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtnjbwteab.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtzpbkwknl.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtsvnmuyqd.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtwqyhweck.html

esac
来源：http://dali.shuidangran.top/Article/details/gtrtyswxet.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtwxpwauqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtdibufnuq.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtxywgtbkm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtcuslikuu.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtqgbaxxje.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtkkidhfut.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gthcipiqqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtesohyfnd.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtgievseia.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gthhsqrlcz.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gthshejfbc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtmmuehmdm.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtoicyyxtw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtdaaexrbr.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtdundoofk.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtmmzuqtiy.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtvqehykia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtczodcdnb.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtudniwsdi.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtbxnallou.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtkuzxourc.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtxicfattz.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtqlmkoysa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvggkpthh.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtztzdsedl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtfawhmjcf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtlpbewcgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblsxtebv.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtetovnifx.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtpntfewhd.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtqmasaqhv.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtmbuisgpg.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtmwziwlvq.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtmqrfklxv.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtbhptulgr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtazwuhmxo.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtnaptnriu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtquiguoag.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gthbitamee.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtkvklehtv.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtrnelcqlc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtrqudkqxu.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtjytykrfr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtrsfuemxl.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gttjaebqgo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtcjonxirl.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtulyiklsb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzonnvhnl.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtkkddzrfv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtyscrbofc.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhlvpxie.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtlkmeodyh.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtdlmfhwxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtdlrdnulk.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtnhkfyjoy.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtxywaymbv.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtuahzsrkz.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgowaegu.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtkgdpovxt.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtyykvyueu.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtlxilovva.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtcaekimci.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtgapsuuud.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtxtsdapdr.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gtdzmfmxsf.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtrpjmwzoz.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtedkztatk.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtwndnbneb.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtciofiekn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtokeyypgt.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtaldwimqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtlklqhqyb.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtrqftglmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtsilybhuz.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtreqgxcpg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtrzcxqqww.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtplgluzmw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtflwbwbnh.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtqrbsmwrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtnxntthmm.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gtflaubgmb.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gttlbzthwi.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtxgpsspgq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtnnaxlhqr.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtkslnsdgm.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtgssokpib.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gteydgvfed.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtzqdzpxgx.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtadbscktl.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtgibahumo.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtbsarekll.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtiluanage.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gtwpvkavid.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtuxniypnd.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtpyhqttmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtesjnmsfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtwoqomsje.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtgvyheias.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtnxmashal.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtsczmaxqf.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtfbmypptp.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjuiivaj.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtahinhovj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gtgmvcxrmt.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtajxcpsek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtaxnfnilh.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtdtuekujp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtaluouacq.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtclmfktuk.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtygmoapoc.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtwfvgkvvf.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtatkvnsrn.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtinchgnux.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtmivqttqf.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtgiehsxak.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtfvjnjbzs.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtgpphdkke.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtlnbzpygg.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtidupvrdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtqdfywave.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtmboyjudv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtjumslbee.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtgoddzusr.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtpuxigupz.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtskaqyctg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsudfvfb.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnelxook.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gtbcgvzegx.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtkukqdimg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtfxoxnqwm.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtobcudfgv.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtgfliqjmi.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtrglpltyf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtmqimcuec.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtfjqsyuri.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtagqdnsgf.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtihfxhzac.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrrnheed.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdmmxowae.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfryblqou.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgltqudgw.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtcbldafxj.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gttqsgswgx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtpsbhusfw.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtskuodnxs.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtlwscooti.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtfwqygpra.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gtafojsjag.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtkgwifiie.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkijihno.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsvvwvxf.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtdyxidayi.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtefxkzlpd.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtvnlvvfxs.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtnsngcttc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtjvptcqis.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gthmuikleb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gttsmhvpvs.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtpkrtilwy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtmpotsasy.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtjutaexrc.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtygoxvdxf.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtyjimtwry.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtoislnmev.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtkupukkoh.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtbahpcmbn.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtpixephqv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtvvcpbzvc.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtyqkeihvf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gtdzvyuitp.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtltfsxrmo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtzzykvsla.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtgsvttjwv.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtazyxwigi.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyvjkgbh.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttkznokpc.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtdczxxvaa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gthacjvtrr.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtdpmzxkhd.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtobnvrcpd.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtwossbjxm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtgnpvuqbp.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtoisbpdkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtipnldgeo.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtmukbxpgs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gttpaewnqc.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtglbohmaf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtddrffazg.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtvpicvocy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtxslltyvu.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtmqwiomlf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtnyuzqcrv.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtflyqkazf.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtxmaekrxt.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtwcbjelec.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtzizgheoi.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtzdbbfpri.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtxomilvyz.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtxsnlcoma.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtrvulxexz.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtcjmhmtks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtatafvdiw.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtuuxaxdae.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtsrhjxtmu.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtfhpuyxqy.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtgpwpguxe.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtgcxodyin.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtmusfnveo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzubyuwof.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtmvjqvozy.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtberpbsiv.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydjkziwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtpxlxathc.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gttpnfttgu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtcbakxyjl.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtzyjrmdai.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gteaezhcbx.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtqlmpgzkv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtdqqsrovy.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtvtpjycjb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtpckiszqs.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtmicedayh.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtufokqhud.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtqgxccasa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtxjgyvbtx.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtidfotuoh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtleehcrmw.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtvyavolrg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtbyembern.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtmsjnzppe.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtxdxtwsdy.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtbcyvrvoz.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtzffgatlm.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtmxeiuggp.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtqsolfjsb.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtqrtbhnwb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtwzmtnomm.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtotpjngxf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtaczueyrn.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtqjzbroei.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtxohwdglq.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtawixlmbc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gthblugjbm.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtlsbuzefy.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqyrlrpmi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtltinrood.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gttddesorv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtzcumhbpn.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtlxkivgeg.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtvylwvmpm.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtmfwwaimc.html


<!-- 参考信息 -->