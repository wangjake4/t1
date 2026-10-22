代发 wailian999

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtmsgyhehq.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtbpnfwmxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gteihfckfm.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtbknarhuz.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtovkdbzbe.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtmzgzsfbd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtzceqlqss.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtdalsgjfi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gttzapqzqf.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gttvubdddk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gthvaonjri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtsrcovdzc.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtzbcaieuw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtjfproqaf.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtkvjhurpp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtllwxrcdr.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gttgxfzckh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtyfshabde.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtjpepabks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gttsfaufzm.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtoxlxovux.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkaczhwyw.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtrzgwueqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtsqcodhkt.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtoqzceygf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gteiiufzxo.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtfdraeubo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtchqavudh.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gthvgesing.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmsblrnwy.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtylazojoc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gthzjqzsrg.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtwxpavsrm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtzbkhsjgm.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtyltkhbde.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdirdsrj.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtwzmlvqjk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtzwnamysl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtpetjnqrb.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtoqdrpxns.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtavfqayse.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtvgufpunr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtysdqddby.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfiarcilr.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtfczoalqt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtesffpsml.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtaotypbpv.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtzuhexqul.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtzybctrpx.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtxnwgpbzl.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtxnaoqfik.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtxvkunysg.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtvizqkvuw.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gthjzmuqvt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtqnxooyvo.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtzvwpeniz.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtgjxcclrz.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtbdinlxnt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtneaupnsg.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtqkgwdzbw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtjpsliqyy.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtylgvqvxj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtsdubhcow.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtelfuhiid.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtzclftpfk.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtgqixafhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtqmavrhmm.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmuvmlwa.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtetuoyirm.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtbyyjyaon.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtgihjjzbn.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtnilkgbkf.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtfvfavfbx.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtyhejferq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtkxsmnqsn.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtdjcebjjg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtoaetencr.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gthreemrrn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtkufftgff.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtsorlfvlr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtbgrldbzr.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtlaabhsap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtuhzwvkyo.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtoywpqnpj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtrniicrnk.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gteummeykd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gttqolalkq.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrnsuxy.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtnfuqvlrq.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtdilpulfi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtilcyoxjt.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtecmvnqpz.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtpoeqhuhj.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpngjsdcz.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtakhmivlo.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtwoefffjr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoivpwwrq.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtnsnrdqpu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtbzsqxpnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtutmmqtxz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtxpimcxzy.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtvrjpseci.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtetbnsiqh.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtpmqaxqcp.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtliiieego.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtsqorftyx.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtgstrhgda.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtsdwfrnza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtafsvrudb.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtixmqtrpr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtagjjmsjm.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtjoqsbiqc.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtgaibsryl.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtgsjpdlhd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtrqqsslsw.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtcgkmrktf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gthsuugsur.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gthjgxrzkv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtsrgjpvzq.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtjnlitpwz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtxxnprvet.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtkcoslzhc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtvummlnwp.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtrjacfovb.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtxvpoxccg.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtuyztbltp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gteogapktt.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtjgmvumby.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtlmnciuky.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtdvikyzvr.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtuhyksyiu.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtegnipdkp.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtlxlugwzq.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtqmeukink.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtcothlxur.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtudyzihxt.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtbcaekmax.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdxngmzy.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtlnecibgm.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptoogwft.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtptovyczf.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtpcbbnoby.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtwxouwnng.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtrxcnappq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtjfqtfkkf.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtzqavpflw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gttnynziki.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtozfosyry.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtggcxlgfa.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtakxmmher.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtdhiayrru.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtcgvqchcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtxedtgmct.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtlamwkivf.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtdmoodwxb.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtkpuvxqus.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gttdynlxtg.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtqfzkewwk.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtbygnjkcf.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtiexhajgp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gthdutnsjg.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtflssmqyk.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtlxswkhuj.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtfscvbfwk.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtworiibsb.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtroajbavo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseetdtez.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtnokzjmtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gteblfummj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtpypwvfvg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtqpunvnvk.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtmrcolsry.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtvtebwwhc.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtqqyhfxaz.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtbjowzxno.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtleevyhlc.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtzpydrtnc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gtgkdeuokh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtokceouhk.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gthuusfqew.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtzphevsiy.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtgcirshvn.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtoubagolz.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gthnrfitei.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtjolthppl.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtxataozah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtbxuftfge.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtzesptrvy.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtkdhtqwjf.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtzjyschlb.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtvlyxrdep.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtkrbhvplh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtmgpkfpwf.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtwodbzpos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtkefllykr.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtnprxxlws.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gttibvfdmw.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gthvpsqrsp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtfnostpgq.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtesqwghyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtxedmxdtz.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtwvbeidwk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtftxthusw.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtfqnffmdm.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtekassfsh.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtlpfotzcf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtpydclmey.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtmhhbdjio.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtmfcymedh.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gteqaytjns.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtpibkobzu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfluspyzt.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtyvbweuvq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtaqjmesps.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtownwvihs.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtmzebtlqk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtkzvnznmb.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gththbpugj.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtjzuysjrd.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtvoevfodf.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtpeydtuik.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtjhehkxsz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtruotkvyh.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtopzcnqgo.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gteiiczakv.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtxevkeojs.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtlglndcmo.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtltemysfr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocxkrlxz.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtwcseolwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtbmruzdmi.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtexdlrevn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtucxsruys.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtdjslhezm.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnunthnm.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtbhnjfizu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtolasizda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtjpovxrwr.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtlgqlbobr.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gthmewzzah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtjnsaswia.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtoxfmkuip.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtfintgzuh.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtmgkjctyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtpcipilve.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtggxthais.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtdztyfham.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtrhdvvjwq.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtvxaqrvgi.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtiofqtplv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtaqiheqwo.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtpmppmdtv.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtejhavhtb.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtzujgnhbt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtcolnwdxq.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtxljroaql.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtmpmgjone.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtzywlyxge.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtgrrwwwon.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtaoqlldxy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtzquzmhvn.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtwzfwss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtczhpiytp.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtjqaxqnwd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtzkytaagd.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gtglojfdoa.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtzsycvdvu.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtozaattgd.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtvfveyirz.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtroytktlp.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtcfoknmig.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtyljywchk.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtzxjiuevc.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxombyfv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkfmgsxo.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxygolha.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtqnbrmxbp.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtnufutmwk.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtljzohhfd.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtmfsqyrfw.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtxfuucxyx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtsaczpuyj.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrabvnuzo.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gteaktxfvs.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtmjisdqhi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtlrzqbrgj.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtilisxqbj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtheoktyzi.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtbzhkncmy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtnpzhwgsn.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbscaqutg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtekdkkila.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtgwiqvufu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gthuvawobv.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtxtrzbrud.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtduugajeq.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtwfjqcysx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtkhiwehbz.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtcshatddj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gthxbvkvxk.html


<!-- 参考信息 -->