代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2nrhbmdny.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gt2nkcsrikd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2rqdsnubt.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gt2yktmtojq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2xloumwmm.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gt2gqoxlbaa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2xbswgvkr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdolfrud.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2ivoddjoq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2ihvrrehn.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2pdltzjrt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfgijiub.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gt2wytknhdh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2thvxapfi.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2yhsgblez.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gt2jnzvxplj.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gt2ykxfkyaf.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2kutcdhpv.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2jxxswkyv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rchfqrcb.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2dzrzgbjt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2bkysrjap.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soqifliz.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gt2nmxgrspa.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2zhqnmubl.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjorjyrd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gt2ppzcvoeu.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2rlpmpizh.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gt2cyuhgwcx.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gt2avfzxhov.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gt2jzyonyix.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2wopzinxx.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2dzsgrtvp.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2ivodhfln.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2fwappkdm.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2jrevxcha.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2wdonhlpb.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2rjtghpln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2alriyvrf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gt2pyovyzjr.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gt2dhoiccod.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gt2cyvskclh.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gt2ubxvjmgg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gt2lwefssdr.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2olbtnqff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2gacszgmj.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2ejylvscy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijxitkym.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2sdwgamlc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2xwmyfosf.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2zeoyidqb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2zvmknjuh.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2cmbigxja.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2oghbwrbd.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2kddefjdj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2fjqtgfzl.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gt2jolpmktj.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2jhovszta.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gt2yxtfmcbz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gt2evsxpkpr.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gt2npbgmlfc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2vaqbgkts.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2snrdhbde.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2edcjqvza.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2taftxpmt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2brhmownm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gt2xmhnekvt.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2aawhdysr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2lcahhfez.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzvwthym.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2tuwpiixy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hibvtleu.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2exmuvprz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axnbfquo.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2qwzlokbz.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2qpqbitku.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gt2sogxoill.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gt2vdklzsii.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gt2ircxmsfc.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gt2samcnmhk.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zulpajzw.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2vaoqaytd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2aacjyrye.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2zivnsylb.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gt2daoshpms.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2mghciyss.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2vndyismr.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2spnnwpqq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjtwnvto.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2siseaida.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2ogrrhnon.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2uowdtmal.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2bgvjujwn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaokkqv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2dlaynxzo.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2fvieytic.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2winegckt.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2pnhpvbda.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2ydkceafr.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mronwssh.html

esac
来源：http://dali.guannengcc.top/Article/details/gt2xjnxtpwa.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2svqnkrsw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gt2voarvngb.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbbucddk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgpupvxg.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2jenqdeqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2jivbzihc.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2ggxhejhs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2iovcrmlm.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gt2wqnjdzwe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2xyeumcug.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2wtcgpygq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2redfvfvj.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2dgxotuct.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gt2cjkpmvws.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2efrcqutn.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eidwcpbi.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2dybxalak.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gt2jbaoptub.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2avwqvdir.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blalwcnd.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2qopxzxfc.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gt2fcindpnu.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2oraitjmi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2alhecvmb.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2bqeqdrll.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gt2pzguncvd.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2etgfchso.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uopvoyhe.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gt2wffgbnjz.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2dagrfkcn.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2dmzxkxfr.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gt2anfrhfkz.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnwspuvt.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2gtgcwibm.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2gvntblsa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2lfslwrmw.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gt2trmzftye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2pblwhjho.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkqwcupd.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2oeolzstl.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gt2tgarlutb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2ezvfneso.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gt2bahzarpb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2rnhggawi.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2lkcnuuvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2dfolduvo.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bifcaamd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2brkxwgah.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gt2lyqlomzd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2zgbgbotf.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2wifffqtq.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bgfuhdqw.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gt2aigzfxje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2untsvbaa.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2llqtrxwh.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2jmumnhdt.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2fzruqfqd.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2ifgimxdj.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gt2rzxcdbxi.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2jnyklwlj.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2cptpwbot.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2jraxhykw.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2bjcaiiay.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zifsfieq.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gt2kcqilzul.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svtzzmnm.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gt2cajahrqq.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gt2qcmnlwky.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kppxqthb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2idpbnasn.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2gxameqsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2frvsdytg.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gt2rzqdtaae.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2yauzirhf.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2nzmboato.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gt2vmgvxgdt.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gt2vyirxrij.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2cntpfrzh.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxlucrxg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gt2qgrsonwq.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2sztfatmx.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gt2txlerkya.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2qzqbafle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2dqhjwbdk.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2vnrjmnxy.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gt2pgeqajap.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2tqhmyrpk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2oinitkvc.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2cbckwkdf.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2dwewpsce.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2coywikmj.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2dqwkeegc.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2lzosdndy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2iutqmmyb.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2mxzkzmqy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gt2lhulnglm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2bhyglfcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2wzzmbqio.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghgdnpmc.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2hzvzlctr.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2uxkcywyv.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gt2okbiplvd.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gt2uswmmnba.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2froncmum.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gt2mzlcbgip.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2lnlpgndf.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2svyjhryk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whmusenv.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gt2ceojvxha.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2oxaoanwf.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2ugitllcu.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gt2hoxlwwfk.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqinvjgx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2gljrdqdm.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2fwjnyzjm.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2hadrvidu.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2hslzaqqd.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyhilffh.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2sfnhajjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2htvdwilm.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2bjwnhflu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2vihncico.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2vnzkjihw.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2mjhuwbnv.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbxjcpaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2xanpshfz.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2iuonxsod.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2nkmoijul.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2jkwdjhnu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2trpjvzjo.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2lmykycpr.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2kwojfaia.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gt2jalfdjvn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2ffbixaaa.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2jmheyzcv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsaywryw.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gt2ypottvaj.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2sjxzrhro.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gdsdlzvo.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gt2bsjavbpg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ggrihvpt.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gt2uoognfhh.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2voqawtcm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tuwkqsar.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2tpeppbqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2bvarzsoh.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2wimvrnlf.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2mzjqvbdz.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2jiaccrge.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2hrearwxe.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2ewvbvnxh.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2chtgnmmo.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2wrfcunlw.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2syqvmjoa.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2rcttfesg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2pdmngytf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2yicfaaew.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvcnegej.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2djvoonsw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2musodntw.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2ioffkyoe.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgjjgqjg.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2ijzqovqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2kbtoojrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpwhddpr.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2elzjwxuy.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gt2fwzvkbjx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2ezfzzzrw.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2wifposam.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gt2hbkydseo.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2fybaicge.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2cpqimrjg.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2wqaoytrz.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2vegtqsyk.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2sexejvgh.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2klokbqhn.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2kfqgletw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gt2snvawosw.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2wnugrffr.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2zvdeztvw.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2vsmkgesf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbjumeph.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gt2kglfjxdv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqrrzevq.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2ihihbaki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2cbhlhzkb.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2swqamurv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2kvzeyoao.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2bturgrcc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2aektsywp.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gt2cymudqbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2gcrxhggb.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evnoppnc.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2bbqmymwb.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2alzlnnpb.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2iobmakqr.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2nsmlrlsq.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2lcotiudz.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2updifkdf.html


<!-- 参考信息 -->