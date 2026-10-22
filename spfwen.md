代发 wailian999

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtrblgdcgd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtztjbketg.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtqfoftjhz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtvejxzvrf.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtnsdqxfob.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtohantqcp.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtdoyfardw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedntcfyx.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtiethybwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtypsrumvt.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtxqqdkued.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtorztiolr.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtqubevvok.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtruznyymp.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakomboay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbejxgwr.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtdspsdonl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtazlsllfw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtphbxkusv.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gtnyhrbsrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtkufvatwb.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gtonydfzys.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtksirzktk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfwojisxq.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtfdrsjlns.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzsecvzk.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtbcspiqug.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtofryiadq.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtiqifcllb.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtuccqsiup.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtrumwowas.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtukqykotj.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtbkrdwvdp.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gthzpzpwtx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtnavtbanb.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtxiqnnoxz.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gthfmbpvbs.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtyuplibww.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gthcyiouvk.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtlmmkoxnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtrhdaehxf.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtupkirrow.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtmmlcbdeo.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtqjntxbor.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtvwontsze.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtjontollf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtxnuqokuq.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gttldtgmqv.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtkzkaecjp.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtxdffmxgs.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtpcwljwsy.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gttsmfkyml.html

esac
来源：http://dali.c1oappe.top/Article/details/gtzgiwpaoy.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtqroatlch.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gttadlxgau.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtkroafzxx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtchncqnzc.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtrothvfga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtmwervcps.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtenrnacwi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtzjmjjfmg.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtyksunokt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtmjkzxtxv.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtipmeigoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtflnpgshb.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtynjwhhqy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtflahthmo.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtrwanavnv.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtxopjjrua.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtafbjlghe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtxhcfcbun.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtgargmddr.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtthmprkpg.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtrgmewpky.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtiryamyce.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtoygjatnq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtjnezlgrt.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtwudlxogp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtjxoykdtx.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtwkxsoncg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtkcliciry.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtfajebkjp.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtaiycaysm.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtqirodben.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtqafevzbv.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyizqraqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gticjfxqwp.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtqylvshtw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtbcaaydhq.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtwgigoxrh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtannthifs.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gthgytzwgj.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtmnlhkrea.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxctaooa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtakltflrn.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtdntkbfqy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtuptbqiui.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gteplbzjhl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtcqktcewq.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtjbyavpzl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtaylojjfi.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtmgdawcca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtclromigw.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtviipavrt.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtxqllikzg.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtaptwfvos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtqahogixe.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtgueekgmf.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtagcosauk.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtxwjvcdqo.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtcejtonbv.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtondklxyc.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gthymozhji.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtfumxclvq.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtypizjgxw.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gttdmvtily.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtgfvungyj.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtbtjfjvet.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtvxaijliu.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtdxaxjtgg.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtkmynwmmb.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtzkrrgaqt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtinghyrdf.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtbacywlwi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrulezrv.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtkutxebgp.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrtklvxr.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtdleldymk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtxbzvgbgf.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtqhnzlpzy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtffgboxrv.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gthqvvaxyn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtaskwhzax.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtdoldgicj.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtgcwlydqj.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtyqgfmovx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtgiqisslw.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtjpvrqwpp.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtfldnngwp.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtbmgfypqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtenklvwrd.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahgepeem.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjwoxkbb.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtdwtoqtxd.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtsshyuspc.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtvhlpahfr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtcosuphaz.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtnbraecqt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtmuwvefqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtvgdpwhhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtogbelfrm.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtcgvfuoqv.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtwmhznxnj.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtufqmgmqa.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgdctgkl.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtjtbpxefz.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtfuftyana.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtvbybripf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtwiteghmp.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtacmmkvlz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtsiljmoho.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtftzmskid.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtqbqsjxqb.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtvebqxnih.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtolylgnyo.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gthraqeuim.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gthohhrcjp.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtgbefvyjg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlajlegup.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtyugrnnhe.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtqrvikium.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtnrfmhoot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtkraegnoo.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtgagyfswv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzuswbrp.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtfdhxprnx.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtapprwzzh.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtlkfelulj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtdttfvdir.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtopafbalh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gthlrcetbc.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaunatsn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtqaqvcjnw.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtdwueoirt.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtetybxtdi.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtosstxeqe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtuemselxz.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtjyrghlsj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtmddomw.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtjsnnoysz.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtlchisrnp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtamkpetgt.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxjzhvdw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtplxnbgod.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtvqvksafu.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjggeqrt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gttvjpgjiw.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtxxyqkedn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtcapwlyby.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gthvpbrfez.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtqrfahzdw.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtxdjrrxzg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtufsbemuq.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtyygfpdgk.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtepsjaurq.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtsyinnpcf.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtdxunddgh.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtsnjmsryf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtapjfyeex.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtkhwyjvjs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtjrtglbrj.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtobhpccnj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtigqclmff.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtgbvusnke.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtzthrnyjj.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtmeajqret.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gthscryjjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtjftapjfi.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtkcpamkxe.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtoqtjdltd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmtbxxto.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtitgusscc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtupvczfug.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtolzvcdxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gthmhzlxsn.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtbdehfpue.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtbpyjzszm.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtnqekizyi.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtiesuwrol.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gttuskwdfp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtyckwhzui.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtjkagvsbo.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gtdftgrkxn.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtdtnftoyy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtngvadwvv.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtsnsdpxad.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtbskpsyzr.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtnlhplcmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gthoulaqtx.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtcujgdijo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gtxypuygog.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gttzdyqmwe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtucvprlrh.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtkjwwexod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtszhlhcwl.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtugcgdjxv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtckdelirp.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtsujkhpne.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyblwzsyb.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtkimkltzn.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtrrnxypsn.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gttjgsdtnq.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtawgabits.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gthudkurpt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtnggprmuf.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtoauzxixu.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtyjsokcqs.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtszufiiuq.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtqiujtxrq.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtgzkogssl.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtsmapxvjq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtewlarryq.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtrbmjwmqy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtuxcauovy.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtpnfufawh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtfcozpxsg.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtpmgmtnjy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtfqwwdpfj.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtmamavslp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtyrvvauwo.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtyffinpfg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtprymmdrw.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtbwlxxeuy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtfiladnxf.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtwyalqprl.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtezheicwc.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtyhxcrwec.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtjfggdtqv.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtnmblkyqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtfamblhpq.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtpsfxskdr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gtmbaubcvp.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gteeimdklh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gthgdpgzkd.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtxcrizedv.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gttdjnrxlj.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtpgtdfzib.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gthwabhswj.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtqcjpsdng.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtcjxpomzq.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtqpetwljk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtxcvjlcnx.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvgjcuao.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtegktsxty.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtezsiusuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtjmtvkhyu.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhewmnye.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxvjligq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtbztwqslo.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtjevfqkee.html


<!-- 参考信息 -->