代发 wailian999

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtfcarawfd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtetbobzav.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtchidkhnz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtogmthqpn.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtmdwdroqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtcngbkhvs.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtyljaejuj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtengwjnol.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gteyjypgyr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtdehczutg.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtsjzrmxcs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbafqhhax.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gteytqtkrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtwtabmtfu.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtynenmgnh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtkvyufjlu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtwftoalyd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtzugwulle.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gthjpsegld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtogffsnvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtvlnsvsco.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtvlnvbxfv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gttehsyfdn.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtbvwqtrsg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtbwmyhpvn.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtbhxrvveu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtwbvfgyhq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjzwyuebg.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtpklwgwlj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcmncjlir.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtdeuczqnp.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtuygianbs.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtncravwzo.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwawknd.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtqcctunyw.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtcdgcejdn.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtxyrmjfzj.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtrjjyiwsz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gttpzhnhpj.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gttjsfznri.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtbkcofmcp.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtziuxvols.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtbnnyypnb.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtyrgqfije.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtviiznogr.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwgdijeu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtyrsjimma.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtubpuljnn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtytzvxuct.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtsaazyuer.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtniugoxre.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gttqjovjsz.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtahxmryvu.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtkbalafqa.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtfdhfitmy.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtzohmjtql.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtlllzypmz.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjkkzrnl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtwkzxnpze.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbfofoxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtylbsokxd.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtfroyzzys.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtdouajxsk.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtbkyioqeo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtqdrkmpsd.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnjsyzig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtpuddqmog.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtxrwdtaqz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gtcdgqknxf.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtywcoesjh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtzeyivwfe.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtzeckqwti.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtdmhojxsl.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtvxxpkgjo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtjlahezpb.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtxjyeegzf.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtgladmron.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtplivzxew.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtziqnfwto.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtsbmzfobg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtwlzcobow.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtrmafqsfu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtxfrisuki.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtcbampkal.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtengqtmwb.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gthouepmjt.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gthktvcczr.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtgdzrdnkd.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtbqgfkxel.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtpmijpnxa.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtjhwzasgd.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtnevvwgtp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtdpdbiwgw.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtkjckldxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtooewdzix.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtsjwrbvbo.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjomiqybe.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtxynfkoso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtvcjcooqk.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtanalfpjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtmnqotpul.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtvfqscdyp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtkbqznooc.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldvzfagj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtvlhdhmjm.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtavijrxxl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtpkciolxm.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtnptmhson.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtqyqcluxe.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtwikosbnj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtdplkmpsa.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtzdklgcau.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtxtfwvera.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtidtaotnr.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtdumookzo.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtbmzrzlbz.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtszhplsmc.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gttgxqvlxs.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtimufggyp.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtyushrnsd.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtyxpcdkvx.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtmfzuzafp.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtejvsihkt.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gttjnnyefb.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtvbcteebw.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtruwkvxye.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtphfaaqtu.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtiyofmazp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtiibomcuo.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtkamqmtod.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlozvrvnl.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gttbfppmkm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtdovnhrwt.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtzxfhsmye.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtovaiqkxp.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtaoqskwzz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtvknjgsxb.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtiujiplop.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtimdaobvm.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtjuuujupc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtnpmzipbn.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gteohwtooi.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtstxfrnpo.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtxvlrfryk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtjuvlnoij.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtjxflwbkc.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtjwdvyzeu.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtbmymojty.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtkoycdzcm.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtwpvebdzk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtobstiqdl.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtpiwjhaxd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqnqffui.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtlamkdxtn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtgupfcndt.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtsgqzvjqd.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtfvfetgzx.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtmjhykabm.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtmhtapysn.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtqeyaurzs.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtgsxfjnin.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtazzakljq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gttlzavfqq.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gttekkkrhw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtvrkghdkc.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtoapwofkr.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtbuwtyfvi.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtjxuapzgl.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtimcjkrvp.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtsukualpx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtxphfvjbd.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtkvvpqnlf.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtrzhhspby.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtmpyxpafa.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtckqltoux.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtciyrznml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtwtwswwwq.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtbrbclxfp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gttnzjejnr.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtmxzivrio.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtmfdwhwnh.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtqlboqvmb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtuhugtthb.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtquqevijf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtrieikhcw.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gthhqpnnkb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtqyxedzns.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtplindyov.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtayjciuga.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtwqoyhcbi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtfdptoyha.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtrgckholv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtwzjoepvi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtbdbazmyl.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtcoxwmwwu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnmpvxogj.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtafomxkgb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtitkmjgkn.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtlsonujot.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtliscrbjm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtcjsryjnl.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtvgdtsruo.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtqhfreqno.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtpxzasqzl.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtbukpeaxj.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtfxosvkvj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtccsqucwj.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtaoxoultb.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gthcygwdxr.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gturitwxog.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcjecfmw.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtfvenqggi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gthfxzaprs.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtfjwmubvs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtgxwjvynu.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtfoncnncx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtasgpybnm.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtofiffnda.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtihxigeoc.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtmcnxfstw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtekrsptqq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtbpkljtqj.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtfwislpbz.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtortsgmhl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gteuxeqwuv.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtowdonptr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreyhamon.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtxnbzxzae.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtfgsjeskb.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtlcwvermb.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtvvfbpnbe.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtcgbjhhxf.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtwtynhley.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvmapwnq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtaskqwnhb.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtpldqszrx.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtopzrknaf.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtykstcoqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtstyjisuu.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtfokmwsrq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtnomckpgd.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtxsdyyqgu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtnybpdwjt.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtoydxexku.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtoywcdtwm.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtmcadeham.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtbmudlhqo.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtgdyyeuza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtvkvoleip.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtfgsdzwdq.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtywjoqhce.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtqctymvqf.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtmbkmxzlq.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyfzhiuc.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtnfegwthu.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtgbezwozp.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtanizyart.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gtssqcyqhf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtictxpsls.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtjjkjoagr.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtwhghsiwj.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtuaflamfw.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtoaqkpkpm.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtogpibhwl.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtxhudfouq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsvbsmgc.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtezepolba.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtgfehnjll.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtiaataymr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtuwrmcqiv.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtxdlkhcma.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtafuimvzy.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtsyxtutse.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtetfexwgr.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtttaxktuz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtanczfglb.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtjmsijtoz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtqtxlgzwk.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtoxkoigyg.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtvneuplpw.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtmglgtetf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtvuwiobqd.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtyubalbeq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtcjbbuobl.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtywtzdcls.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgidtyovz.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtfqirnfuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtbarzxlxl.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gteopynfxo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gthulicuwm.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gthenayfnb.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthhudhefm.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtirbsopgl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtchcjuunu.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtqkjlmspn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwzhihwb.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtefcrficl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtpugbhqsv.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtxrupqbpu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtwegrekil.html


<!-- 参考信息 -->