代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2wnsagmzt.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2hmowrsze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ojffttxz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2lfveabpy.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2ganxsjlr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gt2snsoygnb.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptqzngjx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2enhglwoj.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2pyvrpvno.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2tgaryqvn.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2ozaoczjt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2okyozldc.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2ballxezn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2cpqrskps.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2prhfwcpx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ibrrmdyt.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gt2mwlwjkvd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ryogbcip.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2leqsafdk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2hpjwxqyt.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2oqgytkrc.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2nykvkbnw.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2uvcwebjh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdcygtgz.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gt2nzvoatai.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2nfxxksav.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2ynmhquuc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2vdzbtbwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2tzlivwrm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gt2mxkptlug.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uinxwplb.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2hsngkwrg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2sopoknho.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2xvzevbss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gt2otsdummz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ohmokkcu.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxtmdvir.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2klbphwbr.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2skjnmqbk.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2vonzcbzz.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2edqjgjqk.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2avjforyq.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2wwzfhubq.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdeewkom.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2ftxgolvy.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2ihwsccfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2zqwkgxwo.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2edvsqszq.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2xdhxiszy.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2lmrbkaie.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2pfjvzbok.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkopmzhf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2wdycixkw.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcuyqfuk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2wfbcjqvt.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2pizrruax.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2nfundwzm.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gt2dquaihmd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2criwwzzw.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2wwjivsyh.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2fkunwkuz.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2pqoklfpe.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2ovzgqcwb.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2bylvqvjd.html

esac
来源：http://dali.smart0.xyz/Article/details/gt2fartzbwu.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acaiwjhb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzbsiifw.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gt2ujebqnen.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2wdcshawt.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gt2dmrlxsoi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2emfnwdyi.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2irvyotma.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gt2mnwblswy.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2doxgssbh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hkpsqmgs.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2qemidjve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2wkwyyqyf.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxioqirf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2rmwhgolh.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2aaziisrr.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2ukxyebtr.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2qsfremqe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2tujryvwp.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xchcbkbj.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2adxazskb.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2pvvwnyfg.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ilatvrlw.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2gtvgsjhc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aumbrqmt.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmtetvxl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2rpmdfjmy.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gt2cvplkrqi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2lyrdblvs.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2wrvhajej.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2groljuwx.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2slhnazwy.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2ftssmsaw.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2zfnbbfgi.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijmesmcy.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2zoqnnsxv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2euewvjso.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2vqwwhero.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gt2csbgpsta.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsdwmhwz.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gt2jegveqmu.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2jqsqkejd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2vwkxrwbc.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2stjeqywr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gt2eukpovrf.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gt2ulpucfqd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2qrvybbyn.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gt2tambwoer.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gt2fnckagqp.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttmvfwai.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gt2neinpiak.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2jwrpwhpm.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2retwxtxk.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmtumknx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gt2fsgulrdj.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2dpwywapm.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2hlnwlopr.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2mgmisjsq.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2cdcywnfs.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2dlmhmgze.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2japwdtsk.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2hgwglwxi.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2qaymsyba.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gt2vffjoedc.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2tcsvpvef.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmrwnatj.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2aouduszn.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2xrpwdlvt.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2ibvzfafh.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gt2wembtfrw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqfekhsi.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2satljttb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2zamqmjco.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2sfanomys.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2cjfdmrds.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2bocjqhjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gt2tlpfbemx.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2fawqoryb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ongmaubd.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgeiwcay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2wjeiivgo.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2xskpjpjb.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiwavmoc.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2pmmglcyg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2myggcilf.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2jouuhkkl.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2taicpinr.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2dtnezvht.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2eqyxvfgx.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gt2bisskatk.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2tmsmlzsu.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gt2rzleqwyj.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gt2khydirhj.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbinwaaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2epriljxv.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2pgxazanh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gt2imazxbwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtzxxeat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gt2nsosfznd.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gt2dzlvkmpv.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2wprotatx.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gt2lndgbgmh.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2nexebqbl.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2isshzwww.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyqrtbuj.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2jphwtnxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtoambbi.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2rstjnnzj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gt2ggsgofvj.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2jeywfcaz.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2pbwujrfs.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2gkydohcw.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gt2ztlvppth.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrnkjcr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2msatnrrk.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2kzdbkarr.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gt2olfuzxkg.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2udehurqe.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2guypyxhb.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2mzgvtytj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2uksxtoje.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbazfoms.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2kwdammua.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2cxjfqouc.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gt2ebrtyika.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2qdzsxapy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gt2gfoxtfjs.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2olcmdfqs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gt2sktglaks.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2pngzpcpm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2rowddqba.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufnexcib.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gt2nijhutpa.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gt2rnlbasgm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gt2cqgdystc.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2imxoerbl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2gvocwdfa.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gt2ghdrrzvo.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2lelcdtoe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hifoaftb.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2yvkydyye.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dqeprzks.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2indiasoj.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2vmsphzae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2hhhozkld.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gt2wxgatrkt.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ribhderv.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2wjmmbgvv.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsjeabny.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gt2qtomunnp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2cdtrqhzf.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2xiukncmc.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gt2jfvpjupo.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2xugemceo.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrsjrdsq.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2zfkebfgl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgbpsrqm.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2yhmvmdqx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2skzibjnw.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2kuhtzrps.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gt2blxrjdrl.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gt2mktldcuf.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2fuidnfyu.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2hohxavos.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2gndprjui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2ccqsfaro.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2velalzfl.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2eolwmsxi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2qrfmjsmh.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gt2eejitmof.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gt2dizpzgyt.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2jjhnxcst.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2jmfpfgkt.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2qkorgqsg.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gt2tffvtzbh.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gt2tfqsqhpb.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gt2szqdjdhe.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2trykvlbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2moenilev.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2oquqbexb.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipjpuofm.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gt2pfqsygxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2crzvbuhn.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2gzdarfup.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2zojyizdn.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2zqgwlczq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2qhhrjeou.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfuock.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gt2vmkpqmpl.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gt2rsuybtbs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2oyzxrwim.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2lhtacpkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2njfjvkkt.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2pwgvevjs.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xaktigjz.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlmtgnzw.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2znjxmyor.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2fkknvpnq.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2rtvqdlpd.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2phpvvdnl.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gt2gjcltsrj.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gt2eqgchwlh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2rkdsftqj.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2kenhqhre.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gt2dppfrhfn.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gt2bzmqzxwj.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2popbptsh.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2bpjqszhp.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gt2duvdsecu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gt2rrvxjhkg.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2pmbyjsau.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2gyqeqjtm.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2gkwwvcdj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gt2butclmgh.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gt2vlzkznen.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gt2qpohlkdg.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gt2fuzihtbv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2dtmnclbb.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2crjjyqbj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iigrovju.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvsgwkfm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gt2ddjlowvm.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gt2lwiykoke.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2mobnjyos.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gt2zrjpziiw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2mgppmupi.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gt2dxowmsbe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2zbhquqyp.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2ztvmcnqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2dpnwyajv.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2gacsvhnh.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gt2vacxodjh.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2apcjkmmw.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2qjazkmkx.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkptspfv.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gt2rmdzyldb.html


<!-- 参考信息 -->