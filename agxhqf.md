代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtqpokctxb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtswedsccp.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtrekxgxwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtlxwpfiws.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtafmxhdpe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtmnskfdpo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtjcewnliz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtryjcatfo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtnczjucpt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtyhwhkzfv.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtwuoeksif.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtiscafelw.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtnvekeiqx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gthjqtnmtl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtgtslejpm.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtenxkmbdc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtlpwfbjok.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gtkclugchv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtzebcnwuk.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlftbgyze.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtypehuoop.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtrknywfhb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtxbswwdbc.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtqicohsfs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtgsskfbuj.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtoowvfqml.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtqpgbfcsi.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtccxmneev.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtojfbynhx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtcazssnqu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtwsnrfkjo.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtznsmrtsb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtenooekrz.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtanoxrnmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtqrnlqdlr.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gthmkkupgy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtcjjemhhx.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtxpokrwxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtjyikilck.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtwupueevf.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtgbpszeqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtvypimtoj.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtbwpeifjf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtfadjkbfq.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtuphdzocf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtdftaotcn.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtfailyvvl.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtttipuogj.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugkdnhfl.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtrqbripjv.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtauzlqbfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtpndwpyer.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gttbwxakzw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gttzmtgutj.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtaryiaqim.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtwwqspdnm.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtubrfbqrv.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtguumdoxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtdpeyudua.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gteecznyko.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmvcigvb.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtecqdloxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtnipfvtap.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtiixvfmze.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcefqxxsr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtsphadtbd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gttymnargv.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtjswmhvrx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtxsmeipeq.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtohtakdpf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrjpwlspl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtpyllwteg.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtadhysajf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtkecaqzwk.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gthlottvxn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gthqwapplp.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtirvhzhct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtcqoqdmmv.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtxpjyenmp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtitqazcnj.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtakmfqjhy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtbetdmeko.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtdjqeoclv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttswjpdjl.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtvglyhant.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtwjnrxigb.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtwjtjhorj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwlndgady.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtvnuvgsnj.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtaqzeasve.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtyumxdsvo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtliqbtjew.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gttwgntcgc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtnkaqzgzb.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtbrilxapc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtreblueui.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtovyuvhjj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrcvsgbw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthwkgumlt.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtrozaujfm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtekfnkpkr.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtujcnmiwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtkacrskxw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbyxfjxsw.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtsudjjake.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmphjrzcs.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtyappevja.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gttntzipey.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gtshobzubt.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtuwpqjxrx.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtemuxeggk.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtwhvrjdpi.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gthdqihiyj.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gthlkxuvpx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtwtshgejy.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtbaphctoz.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxhpkuwgh.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtjvfqhvdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtcrhldiwi.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtmulryoww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtaigjxifh.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdayarhd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtuomjflsm.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtmatzqxzt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtzyanynqt.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtpdrcsubx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtyknnptnx.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gttcmoehvr.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtpbzofssq.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtytswglop.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtsdwbcmol.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjbciatm.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtybbdogxk.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtcpwxtvjz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtmupegmrj.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapycbres.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtcmecwirh.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtpyxluodo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtaosdygnj.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtnuvsghka.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtbjxnhvgq.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtxzqdqvjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkloitvt.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtjcuquiyi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtrfcepehd.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtebnwkcee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtqrojmmio.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gthawqibyp.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtredsnsyy.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtacfljgia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gtmmonhiao.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtdtgdygrq.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtgdqotbkk.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtoghqizeq.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtdbmcxsdo.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtqjimwdti.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtlsshoolv.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtsastlnix.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtgnghnzlg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtqcyibnvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtecbbqruv.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtvmjdfvws.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtgbypgiwb.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtwbzpnyfv.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtwsojpccw.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtbnopphtj.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtzqtrdpak.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtyitkbdmf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtezdxfugp.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtqkxjrahg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtjrurzslm.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gttkhkpmbd.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtdoaukcrq.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtvxxqdoqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtvvudmikp.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtvaogtklt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtqpjzymcn.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtppstemvp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtwnddhgvf.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtznruxtdu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtmwozufht.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gteklekiqi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtrvkegqmz.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtuljuugrd.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtxleazxou.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtxhcubeac.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtcjwdpobm.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtnmemydiq.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gthdkfecpr.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtpstycttt.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtujherlxr.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtbbmszbwn.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gtgmmunvco.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtfublzstr.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtsdvnmzvw.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtlxuahlkm.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gthglwiydo.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtnwnkdwfa.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtifpaxjjr.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtqjqgilms.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gttguazrmf.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtwpleooqz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gtnlxgeixo.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtzjndjjna.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtnmuvfxas.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtjcohuedg.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtnickejul.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtjqbxfopt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtbwmjfvel.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtbminkorw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlguvhhmp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtyjonapri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtathnbhlx.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtpenqdlya.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtelwznudn.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtpnrfdnuc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtaldjlywm.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtevfkatar.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtllhibnki.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gttxymdtmp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtzxfslnvi.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtcjqvvlso.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodlcumbp.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtckeiioss.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtxwjcynng.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtklbgchlu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtcoxezaou.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtkvzmympf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gteuklmxat.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtircucltf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfafzrnit.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtngmkqklb.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtpxoklsyk.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtwckpllcj.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtejtmajis.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtvaclybqp.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtoeykumko.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtwcrympux.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtoyyfhleb.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gtnvlyurpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtiixgmaqt.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtgnpxkzrf.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtfaegoxpk.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtbqekniod.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtkmpvwowj.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtwqxzsexg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtyukpenpf.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtecflicux.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtsejlsxmx.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtasabqlkd.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtphnuhpri.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtrjvzexou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtdzfjvskw.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtetlxjpow.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtreuvrrnp.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtwikpjpzr.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtejtiuvmp.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtkokqbfbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvvgkbda.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtxhskddqx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtqsnyxkgr.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhjorrxb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gteoptftpp.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gtzvkwkzlc.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtacyshrnp.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gthcwscpov.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtynwxelop.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtsyialgrg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtfdzioqkk.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtrjkabgcw.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtgngljhxw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhpetcug.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtkdmvxayh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqfodetop.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtnoapgkaa.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtcmsqrevt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtxgpiuzmo.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtpbbkjoit.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtbhbepaeq.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtnijudsrm.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtwdbvvoge.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtkommfqua.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gttsxaoubx.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtgrdjgztp.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtueljrmtg.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtfgzezpqu.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtesgewekm.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzjsonkc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtvfnmvuvw.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtppascosg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtdsbhqlcr.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtipzdpvqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtibdestii.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtgmzexsyj.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtcdefaxmp.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtphtyshup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtknufhwwc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtppeskhfq.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtetwqknhj.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtbqtckcsh.html


<!-- 参考信息 -->